  #include<stdio.h>
int main(int argc, char const *argv[])
{
  int A,B,C,D,E,a1,a2,a3,a4,a5;

   A=40000,B=20000,C=30000,D=15000,E=10000;
   a1,a2,a3,a4,a5;
   printf("A. Nokia     =40000$\nB. Iphone    =20000$\nC. Samsung   =30000$\nD. Mi        =15000$\nE. Lenovo    =10000$\nPlease enter the quanity such as  0 for not intrested and,1,2,3 for quanity");
   scanf("%d%d%d%d%d",&a1,&a2,&a3,&a4,&a5);
   printf("A. Nokia      |  %d *%d  =%d$\nB. Iphone     |  %d *%d  =%d$\nC. Samsung    |  %d *%d  =%d$\nD. Mi         |  %d *%d  =%d$\nE. Lenovo     |  %d *%d  =%d$\n \nTotal Amount:-            =%d$",A ,a1,A*a1,B,a2,B*a2,C,a3,C*a3,D,a4,D*a4,E,a5,E*a5,A*a1+B*a2+C*a3+D*a4+E*a5);
   
   return 0;
}

