#include <stdio.h>
#include <string.h>

int main(void)
{
    char str[80];
    char res_str[80];
    char *star = "********"
    int len;
    printf("단어 입력 : ")
    scanf("%s", str);
    if (len <= 5)
    {
        strcpy(res_str, str);
    }
    else
    {
        strncpy(res_str, str, 5);
        res_str[5] = '\0';
        strncat(res_str, str, len - 5);
    }
    
}
