# assignment
#include<stdio.h>
#include<conio.h>
int main()
{
	int score[7]={10,11,12,13,14,15,16};
	int ans[7];
	int count,sum=0;
	float avg;
	int answer;
	for(count=0;count<=7;count++)
	{
		sum+=score[count];		
}
avg=sum/7;
	printf("\nsum=%d",sum);
	printf("\navg=%f",avg);
	for(count=0;count<7;count++)
	{
ans[7]=(score[count]-avg)*(score[count]-avg);
printf("\nans[7]=%d",ans[7]);
}
	
getch();
return(0);
}
output
sum=91
avg=13.00000
ans[7]=9
ans[7]=4
ans[7]=1
ans[7]=0
ans[7]=1
ans[7]=4
ans[7]=9
