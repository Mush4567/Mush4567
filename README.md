#include <stdio.h>
int main() {
         int day = 0;
         printf("Write days: ");
         scanf("%d",&day);
         int years = day / 365;
         int all = day % 365;
         int month = all / 30;
         int days = all % 30;
         printf("%d years,%d months,and %d days", years, month, days);
         return 0;
}
