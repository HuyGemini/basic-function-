#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int random(int n){
    return -n + rand()%(2*n);
    // return value range from -n to n
}

int main(){
    int i,a;
    srand(time(NULL));
    for(i=0;i<20;++i){
        printf("%6d ",random(200));
    }
    return 0;
}
