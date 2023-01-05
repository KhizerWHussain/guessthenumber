let randomNumber = Math.round((Math.random() * 100));
let userInput = Number.parseInt(prompt("Guess the number between 1 to 100"));
let chances = 0;
let score = 100;

const guessTheNumber = () => {
    while (userInput !== randomNumber) {
        chances++
        userInput = Number.parseInt(prompt("Guess the number between 1 to 100"));
        if (userInput < randomNumber) {
            console.log(`Hint: ${userInput} is less than original number`);
        }
        if (userInput > randomNumber) {
            console.log(`Hint: ${userInput} is greater than original number`);
        }
    }
    if (userInput === randomNumber) {
        console.log(`Congrats your guess is correct`);
        console.log(`Your Scored ${score - chances}`);
    }
}
guessTheNumber();
