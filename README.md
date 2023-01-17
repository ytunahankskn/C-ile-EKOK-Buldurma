#include<stdio.h>

int ekok(int , int);

int main()
{
    int a,b,i;

    for(i=1;i<=2;i++)
    {
        printf("EKOK icin sayi giriniz = ");

        if(i==1) scanf("%d",&a);
        if(i==2) scanf("%d",&b);

    }
    ekok (a,b);
}

int ekok(int a, int b)
{
    int sayac;

    for(sayac =1;sayac%a || sayac%b != 0 ;sayac++)
    {}
    printf("EKOK = %d",sayac);
}
