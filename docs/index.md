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
!include  https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml  
  
@startuml  
  
A -> B: start handshake  
  
B -> A: close handshake  
  
@enduml  
  
```  
  
    
    
  
  
```puml  
!include  https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml  
  
@startuml C4_Elements  
  
Person(personAlias, "Label", "Optional Description ABC")  
Container(containerAlias, "Label", "Technology", "Optional Description XYZ")  
System(systemAlias, "Label", "Optional Description 123")  
  
Rel(personAlias, containerAlias, "Label", "Optional Technology")  
@enduml  
```  
