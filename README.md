DESCRIPTION:

In this project, we are required to combine the fundamentals of Javascript, HTML and CSS to create a web-browser game of Rock, Paper, Scissors. It is a simple game against the computer, and the first project involving Javascript.

What I learned:

1) It is a good idea to plan out your approch to logic prior to coding. Havinig a rough diagram will help to ease the coding before you start.

2) It gets tricky to add in-line css in js script, best to leave it seperate and link it via \\userChoice_div.classList.add('green-glow');\\

3) Logic workflow of javascript:

- defining userChoice in buttons: addEventListeners (click, funtion())

- defining computerChoice in a function getComputerChoice by running Math.flow(Math.random() *3) against choices[array of rps] and choices(randomNumber)

- definining game function in switch cases for win/lose/draw conditions and recalling their functions

- defining individual win/lose/draw functions 
