# Components
---
## Root
* WelcomePage
  * Button to start game
* CharacterSelect
  * Character options
  * Confirm Character Button

## Stage
* StagePage
  * State: wordToGuess, charCount, countdown
* ListOfWords
* BuildCharacter
  * Component for parts of characters
  * Connects with CharacterSelect?
  * Passes props to guesses component

## Guesses
* WordComponent
  * WordToGuess passed as props
  * CharCount passed as props

## Countdown
* CountdownComponent
  * Countdown passed as props

## Endgame
* WinComponent
* LoseComponent
* PlayAgainComponent
  * Clears stage
