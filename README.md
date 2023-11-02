# FirstFullStackApplicationTutorial
I got most of the tutorial done but I got stuck at the end because my react app isn't calling my get API correctly.

        GET http://localhost:8080/api/v1/employees/$%7Bid%7D 400 xhr.js:256  (Bad Request)

This is the error I'm getting.
I think its because $%7Bid%7D is being read literally instead of being converted to the number that represents the id.

