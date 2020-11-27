# menu
creating a program of a restaurant where as in that we are supposed to enter anumber so that we'll get a suggested difh.
#include<stdio.h>
main()
{
	int b=0;
	printf("BINDU CAFE COFFEE");
	scanf("%d",&b);
	switch(b)
	{
		case 1: 
		printf("1. loaded nachos \n rs:125");
		break;
		case 2:
	    printf("2. pasta \n rs:200");
	    break;
	    case 3:
	    printf("3. pizza \n rs:145");
	    break;
	    case 4:
	    printf("4. sushi \n rs:250 ");
		break;
		case 5:
		printf("5. sandwich \n rs:90");
		break;
		default:
		printf("sorry bro! \n you can enter only b/w 1 to 4");
		 
	    
		
	}

}
