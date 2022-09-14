### quiz-app

This quiz application will take a csv file as an input, in 'question, time' format. And will expect player to answer these questions in limited time.
Whether the time expires, or the player answers all the questions; game will end and print the score.

To run the app, move the code file to your desktop and run the command below in your terminal:

```
go build Desktop/cli-quizz-app/main.go && ./main -csv=problems.csv -limit=10
```

If you'd like to change the source file, you could change the arguments of the command.

ozcanfahrettin @2022, Istanbul
