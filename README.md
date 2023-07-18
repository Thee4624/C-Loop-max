# C-Loop-max
วิชาภาษาซี   Loop Maxinum

#include <stdio.h>
#include <conio.h>
int loop,input,i,max;
main()
{
	printf(" Enter Number for loop : ");
	scanf("%d",&loop);
	printf("\n");
	for(i=0;i<loop;i++){
		printf(" Number #%d : ",i+1);
		scanf("%d",&input);
		if(i==0||input>max){
			max=input;
		}
	}
	printf("\n Maximum is %d \n\n",max);
}
