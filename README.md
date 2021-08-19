# Operations-on-matrices-using-C
The following program is about mathematical operations done on matrices using C

#include<stdio.h> 

int main() 

{ 

int mat1[3][3],mat2[3][3],result[3][3]; 

int i,j; 

printf("Matrix 1 - Enter values of 3 * 3 matrix"); 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

scanf("%d",&mat1[i][j]); 

}  

} 

printf("Matrix 2- Enter values of 3 * 3 matrix"); 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

scanf("%d",&mat2[i][j]); 

}  

} 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

result[i][j]=mat1[i][j]+mat2[i][j]; 

}  

} 

printf("Addition of Matrix is:\n"); 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

printf("%d\t",result[i][j]); 

}  

printf("\n"); 

} 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

result[i][j]=mat1[i][j]-mat2[i][j]; 

}  

} 

printf("Subtraction of Matrix is:\n"); 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

printf("%d\t",result[i][j]); 
}  

printf("\n"); 

} 

for(i=0;i<3;i++) 

{ 

for(j=0;j<3;j++) 

{ 

result[i][j]=mat1[j][i]; 

}  

} 

printf("Transpose of Matrix is:\n"); 

for(i=0;i<3;i++) 

{ 
for(j=0;j<3;j++) 

{ 

printf("%d\t",result[i][j]); 

}  

printf("\n"); 

} 

return 0;  

} 
