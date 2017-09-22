# _Ping Pong Simulation 20XX_

#### _[TODO]_

#### By _**Rane Fields**_

## Description

_[TODO]_

## Ping Pong Mode Specs

|                                                 Behavior | Test Input | Expected Output                                                                |
|---------------------------------------------------------:|------------|--------------------------------------------------------------------------------|
| It can take in user input and output something back      | "hello"    | "hello"                                                                        |
| Only allows numbers to be entered                        | "asd3"     | exception                                                                      |
| It can count up to the given number                      | 5          | [1, 2, 3, 4, 5]                                                                |
| It can also replace all multiples of 3 with "ping"       | 5          | [1, 2, ping, 4, 5]                                                             |
| It can also replace all multiples of 5 with "pong"       | 7          | [1, 2, ping, 4, pong, ping, 7]                                                 |
| It can also replace all multiples of 15 with "ping-pong" | 16         | [1, 2, ping, 4, pong, ping, 7, 8, ping, pong, 11, ping, 13, 14, ping-pong, 16] |

## Prime Pong Mode Specs

|                                                    Behavior | Test Input | Expected Output                                                                                     |
|------------------------------------------------------------:|------------|-----------------------------------------------------------------------------------------------------|
| It can take in user input and output something back         | "hello"    | "hello"                                                                                             |
| Only allows numbers to be entered                           | "asd3"     | exception                                                                                           |
| It can count up to the given number                         | 5          | [1, 2, 3, 4, 5]                                                                                     |
| It can identify all prime numbers in the list               | 7          | [2, 3, 5, 7]                                                                                        |
| It can replace all prime numbers in the list with "prime"   | 5          | [1, prime, prime, 4, prime]                                                                         |
| It can also replace every 3rd prime with "prime ping"       | 5          | [1, prime, prime, 4, prime ping]                                                                    |
| It can also replace every 5th prime with "prime pong"       | 17         | [1, prime, prime, 4, prime ping, 6, prime, 8, 9, 10, prime pong, 12, prime ping, 14, 15, 16, prime] |
| It can also replace every 15th prime with "prime ping-pong" | 49         | [..., 40, prime, 42, prime, 44, 45, 46, prime ping-pong, 48, 49]                                    |

## Link

_[TODO] https://lydianlights.github.io/epicodus-ping-pong/_

## Setup/Installation Requirements

_To download the source code of this project, just follow the listed instructions:_

* _Download a git client if you don't already have one. I recommend [Git Bash](https://git-for-windows.github.io/)._
* _Clone the project using the link: `https://github.com/LydianLights/epicodus-ping-pong`
(instructions on how to clone can be found in your git client documentation)_
* _Open the project folder in your favorite plaintext editor_

## Technologies Used

_This project is a simple html page with linked css and js files. It makes use of the [Bootstrap v3.3.7](https://getbootstrap.com/docs/3.3/) CSS framework and the [jQuery v3.2.1](https://jquery.com/) Javascript library._

## Known Bugs

* _[TODO]_

### License

*This page is hereby released as public domain. No permission necessary for modification and distribution.*

Copyright (c) 2017 **_Rane Fields_**
