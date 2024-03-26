# Hackerrank-C-

You will be given two positive integers,  and  (), separated by a newline.

Output Format

For each integer  in the inclusive interval :

If , then print the English representation of it in lowercase. That is "one" for , "two" for , and so on.
Else if  and it is an even number, then print "even".
Else if  and it is an odd number, then print "odd".
Note: 

Sample Input

8
11
Sample Output

eight
nine
even
odd



using namespace std;
#include<iostream>
int main(){
    int a,b;
    scanf("%d %d", &a,&b);
    for(int x=a;x<=b; x++){
        if(x/10==0){
            switch(x){
                case 1:
                    printf("one\n");
                    break;
                case 2:
                    printf("two\n");
                    break;
                case 3:
                    printf("three\n");
                    break;
                case 4:
                    printf("four\n");
                    break;
                case 5:
                    printf("five\n");
                    break;
                case 6:
                    printf("six\n");
                    break;
                case 7:
                    printf("seven\n");
                    break;
                case 8:
                    printf("eight\n");
                    break;
                case 9:
                    printf("nine\n");
                    break;
            } 
        }
        else{
            if(x%2==0){
                printf("even\n");
            }
            else{
                printf("odd\n");
            }
        }
        }
     return 0;   
    }
