# 6010405564
#include "stdio.h"

void main()
{
  float req,gpa1,gpa2;
  int cre1,cre2;
  printf("Input the previous semester GPA: ");
  scanf("%f" ,&gpa1);
  printf("Input the previous credits: ");
  scanf("%d" ,&cre1);
  printf("Input the credits this semester: ");
  scanf("%d" ,&cre2);
  printf("Input the required GPA: ");
  scanf("%f" ,&req);
  gpa2 = ((req*(cre1+cre2))-(cre1*gpa1))/cre2;
  printf("The GPA this semester should be %.2f" ,gpa2);
  
}
