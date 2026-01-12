#include<stdio.h>

int main(){
int a=1226;
int k=3;
printf("Enter pin number:\n");
scanf("%d",&a);
while(a==1226&&k>=3)
{printf("menu:\n");
printf("1.Balance\n");
printf("2.withdraw \n");
printf("3.exit \n");

k=k+1;

int b;
scanf("%d",&b);

if(b==1){
printf("balance;$700");

}else if(b==2){
int c;
printf("Enter amount to withdraw:");
scanf("%d,&c");
printf("collect your cash! Thank you");






}else if(b==3){
printf("Thank you");


}else{
printf("wrong option please try again");


}
}




if(k>3){
printf("card locked maximum attempts");
}






    return 0;
}
