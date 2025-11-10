# Print-a-Square-of-stars
Using C language program is made which gives the output of Square of stars
#include <stdio.h>
int main() {
    int n, i = 1, j;
    scanf("%d", &n);
    while(i <= n) {
        j = 1;
        while(j <= n) {
            printf("* ");
            j++;
        }
        printf("\n");
        i++;
    }
    return 0;
}
