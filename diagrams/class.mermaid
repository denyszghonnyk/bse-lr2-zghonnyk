classDiagram
    User <|-- Player
    
    class User {
        -int userId
        -String username
        -String password
        +login(String login, String pwd) bool
        +logout() void
    }
    
    class Player {
        -int currentScore
        +joinSession(String code) bool
        +submitAnswer(int questionId, int answerIndex) void
    }
    
    class Quiz {
        -int quizId
        -String title
        -boolean isPublic
        +addQuestion(Question q) void
        +getDetails() String
    }
    
    class Question {
        -int questionId
        -String text
        -List~String~ options
        -int correctOptionIndex
        -int timeLimit
        +validateAnswer(int index) bool
    }
    
    class GameSession {
        -String sessionCode
        -String status
        -int currentQuestionIndex
        +startSession() void
        +nextQuestion() void
        +endSession() void
    }
    
    class Result {
        -int resultId
        -int scoreEarned
        -float responseTime
        +calculatePoints() int
    }

    Quiz "1" *-- "5..*" Question : містить (Композиція)
    GameSession "1" o-- "0..*" Player : включає (Агрегація)
    GameSession "1" --> "1" Quiz : використовує (Асоціація)
    Player "1" --> "*" Result : отримує (Асоціація)
    GameSession "1" --> "*" Result : генерує (Асоціація)
