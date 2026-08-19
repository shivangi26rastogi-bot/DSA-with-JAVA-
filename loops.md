# loops 

## syntax  for loop :
'''
for ( initialization ; condition ; updation ){

    statement

}
'''
* initializaton is done one time wherreas condition and updation and statement are done again and again until condition fails .

* if declaration is done outside the loop then we can print the value of that variable after vanishing of the loop.

* iterations are ki itni baar chl rha h loop == (end - initial +1)

## decreasing loop 

# syntax for loop :
 
'''
for(int i =n ; i >=1 ; i--){

    statement;

}
'''

## AP QUES 

1. syntax : condition known 
        '''

        for (int i =a ; i <= (a+(n-1)*d) ; i += d){

            sout (i);

        }

        '''

2. syntax : when we know thw number of terms 
        '''

        int a , d ;

        for(int i =1 ; i <=n ; i++){

            sout(a)

            a += d

        }

        '''


## G P QUES 

*  synatx :  
        '''

        int a , d;

        for(int i=1; i<=n ; i++){

            sout(a);

            a *= r;

        }

        '''

# BREAK STATEMENT :
* when the condition encounter break statement terminate the near by loop.

# CONTINUE STATEMENT :
* when the condition encounter then continue skip the iteration.

# built in function 
* Math.sqrt(n)

# WHILE LOOP 

## syntax :   generally ,used when there are more than one conditions .
* jb bhi iterations na pta ho .
'''

initialization ;

while(condition){
    satement ;
    updation;

}

'''

# DO WHILE LOOP

## syntax : it runs or execute atleast once if there is false condition
'''

initialization;

do{

    statement;
    updation;

}while(condition);
'''

### finding last digit n% 10 , deleting last digit n/10

## limits of INT 
* maximum value == Integer.MAX_VALUE;
* minimum value == Integer.MIN_VALUE;