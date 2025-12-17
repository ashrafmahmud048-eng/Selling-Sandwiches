#include <stdio.h>

int main() {
    int A, B, C;
    scanf("%d %d %d", &A, &B, &C);

    int cost = B + C;
    int profit = A - cost;

    printf("%d\n", profit);
    return 0;
}

