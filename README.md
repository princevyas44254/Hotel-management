#include <stdio.h>
int main(){
    int r;
    printf("enter a number :");
    scanf("%d",&r);

    if(r==1){
        printf("ROOMS ARE AVAILABLE");

    }
    if(r==0){
        printf("ROOMS ARE UNAVAILABLE");
    }
    if(r>1){
        printf("YOU ARE ORDERING FOOD\n ");
        int s;
        printf("ENTER ROOM NUMBER : ");
        scanf("%d",&s);
        int i;
        printf("PRESS 1 FOR VEG AND 0 FOR NON-VEG\n enter number :");
        scanf("%d",&i);

        if(i==1){
            printf("YOUR ORDER IS VEG\n THANKS FOR ORDERING");
        }
        if(i==0){
            printf("YOUR ORDER IS NON-VEG \n THANKS FOR ORDERING");
        }
    }
    if(r<0){
        printf("ADD YOUR CONCERN\n CONTACT NO: 907***");
    }
    return 0;
}1
