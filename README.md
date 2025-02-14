# prime-test1
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

   int n,i,c=0;
    scanf("%d",&n);
    for(i = 1;i <= n; i++)
    {
        if(n%i==0)
        {
            c++;
        }
    }
    if(c==2)
    {
        printf("yes");
    }
    else
    {
        printf("no");
    }
        /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
