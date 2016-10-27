# Binary-Search

#include <stdio.h>
int main (){
	int array[100], c, n, s, first, last, middle; 
	printf("Enter the number of elements \n"); 
	scanf("%d", &n); 
	printf("Enter %d elements", n);
	for(c=0; c<n; c++)
		scanf("%d", &s); 
		first = 0; 
		last = n-1; 
		middle = (first+last)/2; 
		while(first<=last){
			if(array[middle]<s){
				first = middle+1; 
			}
			else if (array[middle]==s){
				printf("%d found at location %d \n", s, middle+1); 
				break; 
			}
			if (last = middle-1)
			middle = (first+last)/2; 
		}
		
		else{
		(first>last); 
		printf("%d is not found in the list", s); 
	}
	return 0; 	
}
