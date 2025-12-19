# hello_length.c
#include <stdio.h>
#include <string.h>

int main() {
    char text[100];
    printf("Enter a string: ");
    gets(text);
    int length = strlen(text);
    printf("Length of the string: %d\n", length);

    return 0;
}
