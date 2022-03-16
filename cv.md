# Kirill TSurkan
******************
## Junior Frontend Developer
******************************
### Contact information:
* Phone: +7 977254238
* E-mail: ysurkan2019@yandex.ru
* Telegram:  @Teacher9018
* [codewars] (https://www.codewars.com/users/teacher90)
******************
## About Myself:
Hello! My name is Kirill, I am 31. For 6 years I worked as a teacher of economics, history, social studies. A year ago I started to be interested in programming, and 7 months ago I enrolled in courses on web development, during this time I got acquainted with a lot of technologies: JS, React, HTML, CSS and many others.
I have a great desire to become a professional developer in the frontend, so I spend all my time studying
******************
## My Skills:
HTML5, CSS3
JavaScript Basics
React, React-route
Webpack
Babel
Git, GitHub
******************
## Code example:
Create a function that returns the name of the winner in a fight between two fighters.

Each fighter takes turns attacking the other and whoever kills the other first is victorious. Death is defined as having health <= 0.

Each fighter will be a Fighter object/instance. See the Fighter class below in your chosen language.

Both health and damagePerAttack (damage_per_attack for python) will be integers larger than 0. You can mutate the Fighter objects.
```
function declareWinner(fighter1, fighter2, firstAttacker) {
  let attacker = firstAttacker
    while(fighter1.health > 0 && fighter2.health > 0 ) {
      if (attacker == fighter1.name) {
        fighter2.health = fighter2.health - fighter1.damagePerAttack
        attacker = fighter2.name
      } else if (attacker == fighter2.name) {
          fighter1.health = fighter1.health - fighter2.damagePerAttack
          attacker = fighter1.name
          }
        }
    if (fighter1.health <= 0) {
      return fighter2.name
    } 
      return fighter1.name
     
 }
 ```
******************
## Courses:
* Yandex.Practicum (7 months, in progress)
* HTML Academy basic practice
* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
******************
## Languages:
* Russian(general)
* English - pre-Intermediate

