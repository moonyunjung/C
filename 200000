#include <stdio.h>

int main(void){
    int arr[9];
    int i;

    for(i = 0; i < 9; i++){
        scanf("%d",&arr[i]);
    }

    int max = -1000000;
    int max_index;;
    for(i = 0; i < 9; i++){
        if(max < arr[i]){
            max = arr[i];
            max_index = i + 1;
        }
    }

    printf("%d\n%d\n", max, max_index);

    return 0;
}
