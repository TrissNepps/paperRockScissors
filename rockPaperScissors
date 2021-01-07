const getUserChoice = userInput => {
  userInput = userInput.toLowerCase();
  if (userInput === 'rock' || userInput === 'paper' || userInput === 'scissors' || userInput === 'bomb') {
    return userInput;
  } else console.log('Error. Please type rock, paper, or scissors into the input')
};

const getComputerChoice = () => {
  switch (Math.floor(Math.random()*3)) {
    case 0:
      return 'rock';
      break;
    case 1:
      return 'paper';
      break;
    case 2:
      return 'scissors';
      break;
  }
}

const determineWinner = (userChoice, computerChoice) => {
  if(userChoice === 'bomb'){return 'You blew everything up. You must win!';}
  if (userChoice === computerChoice) {return 'The game is a tie';} 
   if (userChoice === 'rock'){
    if (computerChoice === 'paper') {return 'You lose!';}
    else {return 'You win!';};}
    
    if (userChoice === computerChoice) {return 'The game is a tie';}
    if (userChoice === 'paper'){
      if(computerChoice === 'scissors'){return 'You lose!';}
      else {return 'You win!';}
    }

    if(userChoice === computerChoice){return 'The game is a tie!';}
    if (userChoice = 'scissors'){
      if (computerChoice = 'rock'){return 'You Lose!';}
      else {return 'You win!';}
    }
    
  
    };

const playGame = () => {
  const userChoice = getUserChoice('bomb');
  const computerChoice = getComputerChoice();
  console.log('You threw: ' + userChoice);
  console.log('The computer threw: ' + computerChoice);
  console.log(determineWinner(userChoice,computerChoice));
};

playGame();
