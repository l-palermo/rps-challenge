# ROCK - PAPER - SCISSORS

This is a web app to play the famous hand game RPS on the web!

## Domain model

Player  --> Enter the domain URL  --> Page<br>
Page -->  shows -->  Game title, name box, submit button<br>
Player  -->  Enter -->  name<br>
Page -->  shows --> Game title, player name, rock paper scissors buttons<br>
Player  -->  Click -->  Rock button<br>
Page  -->  Shows  -->  CPU random choice and winner

## Getting started

* Please clone the repository typing on your terminal: `git@github.com:l-palermo/rps-challenge.git`
* Then run `bundle` to install dependecies

## How to use the software

* From the folder `RPS-CHALLENGHE` run on the cmd line:`$ rackup` (check what port the server is listening to)
* Move to the browser and in the URL line type: `http://localhost:"#portnumber"/`
* if show a message error `Address already in use` type: `rackup -p 9393` (-p specifies the port number)
* To run tests: `$ rspec`
** Test coverage 100%

### Example of usage

![](images/SS1.png)
![](images/SS2.png)
![](images/SS3.png)


