---  
share: true    
---  
  
# Hello 1    
  
## What to say!?    
  
# Hello 2    
  
```puml  
  
Alice -> Bob  
  
```  
  
    
    
  
```puml  
  
@startuml  
  
A -> B: start handshake  
  
B -> A: close handshake  
  
@enduml  
  
```  
  
    
    
  
  
```puml  
  
@startuml C4_Elements  
  
Person(personAlias, "Label", "Optional Description ABC")  
Container(containerAlias, "Label", "Technology", "Optional Description XYZ")  
System(systemAlias, "Label", "Optional Description 123")  
  
Rel(personAlias, containerAlias, "Label", "Optional Technology")  
@enduml  
```  
