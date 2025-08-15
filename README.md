```mermaid
---
title: ProJect
---
classDiagram
    
    ClassStudent --|> Form1
    Classinformation --|> Form1
    CheckNameStudent <|-- Classinformation
    CheckNameStudent --|> Form1
    class Classinformation{
        -string No
        -string NameClass
        -int marean
        -int kad
        -int leave
        -DateTime()
    }
    class ClassStudent {
        -string subject
        -string NO
        -getSubject()
        -getNo()
    }
    
```
