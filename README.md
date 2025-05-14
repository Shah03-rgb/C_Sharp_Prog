# C--Prog
This GitHub repository contains the basic C# projects I've made during my College Career.

The file named "lQuiz_app_C#.zip" is a basic Quiz App I made in C#.

This ZIP file contains various ".csproj" and ".cs" files structured in the following format:

SimpleQuizApp/
├── SimpleQuizApp.csproj
├── Program.cs
├── Models/
│   └── QuizQuestion.cs
└── Services/
    └── QuizService.cs

"SimpleQuizApp.csproj" is the project file used by .NET to define the app’s configuration and dependencies.

"Program.cs" is the main entry point of your application.

"QuizQuestion.cs" defines a quiz question class with: (i) QuestionText: the question to ask
                                                     (ii) Options: list of choices
                                                    (iii) CorrectOption: index of the correct answer (0-based)

"QuizServices.cs" contains the core logic of the quiz application. 
It is responsible for: (i) Displaying questions and options
                      (ii) Accepting and validating user input
                     (iii) Keeping track of the score
                      (iv) Giving correct/incorrect feedback
                       (v) Showing final results                                                    
