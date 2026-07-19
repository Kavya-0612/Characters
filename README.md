#include <stdio.h>

int main() {
    char str1[100], str2[100], str3[100];

    // Reading three lines of input
    scanf("%[^\n]%*c", str1);
    scanf("%[^\n]%*c", str2);
    scanf("%[^\n]%*c", str3);

    // Printing the same lines
    printf("%s\n", str1);
    printf("%s\n", str2);
    printf("%s\n", str3);

    return 0;
}
