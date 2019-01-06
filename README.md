# deret-1-4-3-5-7

    #include <stdio.h>
    #include <stdlib.h>
    int main()
    {
    int N,i,Sum;
    printf("Masukan jumlah bilangan :");
    scanf("%d",&N);
    Sum=0;
    for(i=1;i<=N;i++)
    {
       if(i%2==1)
      {
           Sum = Sum + i;
           printf("\t%d",i);
      }
      else if (i%2==0)
      {
    Sum = Sum - i;
          printf("\t-%d",i);
      }
    }
    printf("\nJumlah deret = %d \n",Sum);
    system("pause");
    return 0;
    }
