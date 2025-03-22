#include <stdio.h>
#include <math.h>

int main() {
  float radius, area;
  const float PI = 3.14159;

  printf("Enter the radius of the circle: ");
  scanf("%f", &radius);

  if (radius < 0) {
    printf("Radius cannot be negative.\n");
    return 1;
  }
  
  area = PI * pow(radius, 2);

  printf("The area of the circle is: %.2f\n", area);

  return 0;
}
