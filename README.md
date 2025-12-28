# Info

Этот репозиторий был создан в рамках обучения в **EPAM Rolling Scopes School (Frontend)**.

На момент прохождения курса у меня уже было более 16 лет опыта в web-разработке. Основная часть этого опыта — фриланс и работа в небольших локальных командах, где я часто была единственным разработчиком и отвечала за все технические решения.

Цель участия в школе:
- систематизировать и дополнить уже имеющиеся знания и навыки
- закрыть пробелы в современных frontend-подходах
- освоить корпоративные практики разработки
- научиться работать в условиях командной разработки, code review и формализованных процессов

-------------------

### Guessing game

---
⚠️ DO NOT SUBMIT PRS WITH SOLUTIONS TO THIS REPO ⚠️

### Description

Your task is to implement `GuessingGame` class

#### Methods:

##### `setRange(min, max)`
this method accepts min and max value of range of number to guess

##### `guess()`
this method returns solution candidate (you make an assumption based on range and previous assumptions)

##### `lower()`
this method is called if prev call of `guess()` returned number which is greater than answer

##### `greater()`
this method is called if prev call of `guess()` returned number which is lower than answer

Your implementation should use [binary search algorithm](https://en.wikipedia.org/wiki/Binary_search_algorithm) under the hood to pass all tests

### Prerequisites
1. Install [Node.js](https://nodejs.org/en/download/)   
2. Fork this repository: https://github.com/rolling-scopes-school/guessing-game/
3. Clone your newly created repo: https://github.com/<%your_github_username%>/guessing-game/  
4. Go to folder `guessing-game`  
5. To install all dependencies use [`npm install`](https://docs.npmjs.com/cli/install)  
6. Run `npm test` in command line or you can run tests in browser with `npm start` and open http://localhost:8080
7. You will see the number of passing and failing tests. 100% of passing tests is equal to 100p in score  

---

### Submit to [rs app](https://app.rs.school)
1. Open [rs app](https://app.rs.school) and login
2. Go to [submit task page](https://app.rs.school/course/submit-task?course=rs-2019-q3)
3. Select your task (guessing-game)
4. Press the submit button and enjoy

© [lesnitsky](https://github.com/lesnitsky)
