#include <stdio.h>

int main() {
    int nombres;
    
   
    printf("combien d'éleves dans la classe: ");
    scanf("%d", &nombres);
    
    int marks[nombres];
    
    for (int i = 0; i < nombres; i++) {
        printf("entrerla note d'élève %d: ", i + 1);
        scanf("%d", &marks[i]);
    }
    
    printf("\nles notes des étudiants sont :\n");
    for (int i = 0; i < nombres; i++) {
        printf("Student %d: %d\n", i + 1, marks[i]);
    }
    
    return 0;
}


