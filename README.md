# quiz-microservices

URL for postman

Question service: Running on ports 8080 and 8081 getScore(POST) : http://localhost:8080/question/getScore JSON : [ { "id":16, "response":"datetime" }, { "id":12, "response":"[1, 2, 3, 4]" }, { "id":10, "response":"ArrayList" }, { "id":7, "response":"do-while loop" }, { "id":4, "response":"throw" } ]

getQuestionsByIds(POST) : http://localhost:8080/question/getQuestions JSON : [6,4,7,3,5]

getByCategory(GET) : http://localhost:8080/question/category/Java

getAllQuestions(GET) : http://localhost:8080/question/allQuestions

QUIZ SERVICE create Quiz(POST) : http://localhost:8090/quiz/create { "categoryName":"Python", "numQuestions":3, "title":"Python Quiz" }

get Quiz Questions(GET) : http://localhost:8090/quiz/get/4

submit Quiz(POST) : http://localhost:8090/quiz/submit/4 [ { "id":16, "response":"datetime" }, { "id":11, "response":"len()" }, { "id":14, "response":"To iterate over a sequence of numbers." } ]

API GATWEWAY GET- http://localhost:8765/QUIZ-SERVICE/quiz/get/1
