#include <iostream>

int main()
{
    //Math
    for(int num = 1; num <= 100; num++)
    {
        int primality = 0; 
        for(int mod = 2; mod <= num/2; mod++)
        {
            //Modulio 
            if(num % mod == 0)
            {
                primality += 1;
            }
            
        }
        //Prime Checker
        if(primality > 0)
        {
            std::cout << (num + "Is Composite") << std::endl;
        }

        else
        {
            std::cout << (num + "Is Prime") << std::endl;
        }
    }
}
