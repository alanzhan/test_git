this is a test_git markdown

switch dev branch

second test branch

@startuml(usecase.png)
actor Spark
actor IVR

IVR -> (case): comment
(case) <- Spark: comment

@enduml

http://10.224.56.239:8080/docs/webex-telephony-dsa/myfilename.png


<img src='http://g.gravizo.com/g?
@startuml;

actor User;
participant "First Class" as A;
participant "Second Class" as B;
participant "Last Class" as C;

User -> A: DoWork;
activate A;

A -> B: Create Request;
activate B;

B -> C: DoWork;
activate C;

C --> B: WorkDone;
destroy C;

B --> A: Request Created;
deactivate B;

A --> User: Done;
deactivate A;

@enduml
'>
