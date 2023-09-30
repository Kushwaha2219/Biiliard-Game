#include<stdio.h>
int main(){
	int p1[5],p2[5],i,lead,winner,mxwin,mx,sum1=0,sum2=0;
	printf("----------------------------------------------------------\n");
	for(i=0;i<5;i++){
		printf("Enter score of %d round for player 1\n",i+1);
		scanf("%d",&p1[i]);
		printf("Enter score of %d round for player 2\n",i+1);
		scanf("%d",&p2[i]);
		printf("----------------------------------------------------------\n");
	}
		for(i=0;i<5;i++){
			sum1+=p1[i];
			sum2+=p2[i];
			
			if(sum1>sum2){
				lead=sum1-sum2;
				printf("Player 1 is leader and lead for %d round is %d\n",i+1,lead);
				winner=1;
				printf("............................................................\n");
			}
			else{
				lead=sum2-sum1;
				printf("Player 2 is leader and lead for %d round is %d\n",i+1,lead);
				winner=2;
				printf("............................................................\n");
			}
			if(mx<lead){
				mx=lead;
				mxwin=winner;
			}
		}
	
	printf("***************************************************************\n");
	printf("Maximum lead in all round is %d and overall winner is Player%d",mx,mxwin);
	
	return 0;
}
