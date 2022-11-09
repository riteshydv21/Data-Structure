#include <stdio.h>
#include<conio.h>
int main(){
    int i,j,M[3][3];
    for(i=0; i<3; i++){
        for(j=0; j<3; j++){
            printf("enter the value for M[%d][%d]:",i,j);
            scanf("%d",&M[i][j]);
        }
}
printf("two dimensional array element:\n");
for(i=0;i<3;i++){
    for(j=0;j<3;j++){
        printf("%d",M[i][j]);
            printf("\n");
        }
    }
    return 0;
}
