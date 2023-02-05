# PSAT 

## Recursion Function - Factorial

```
factorial(int n)
{
	int fact = 1;
	if(n==1)
		return fact;
	else 
		fact = n* factorial(n-1);
		return fact;

}
```
## Explanation

factorial(5)
	else: fact = 5 * factorial(4) => 24
			
factorial(4)			
	else: fact = 4 * factorial(3) => 6
	
factorial(3)	
	else: fact = 3 * factorial(2) => 2
	
factorial(2)
	else: fact = 2 * factorial(1) => 1
	
factorial(1)
	if: return 1;
