#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    printf("Guessing Game\n");

    // Seed the random number generator
    srand(time(NULL));

    // Generate a random number between 1 and 100
    int targetNumber = rand() % 100 + 1;

    int userGuess;
    int attempts = 0;

    printf("Try to guess the number between 1 and 100.\n");

    do {
        printf("Enter your guess: ");
        scanf("%d", &userGuess);

        attempts++;

        if (userGuess < targetNumber) {
            printf("Too low! Try again.\n");
        } else if (userGuess > targetNumber) {
            printf("Too high! Try again.\n");
        } else {
            printf("Congratulations! You guessed the number %d in %d attempts.\n", targetNumber, attempts);
        }

    } while (userGuess != targetNumber);

    return 0;
}
