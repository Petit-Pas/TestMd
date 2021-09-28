```
![Alt text](https://g.gravizo.com/source/svg/custom_mark13?https%3A%2F%2Fgithub.com%2FPetit-Pas%2FTestMd%2Fblob%2Fmaster%2FExampleGraph.md)
<details> 
<summary></summary>
custom_mark13
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
C -> B: WorkDone;
destroy C;
B -> A: Request Created;
deactivate B;
A -> User: Done;
deactivate A;
@enduml
custom_mark13
</details>
```