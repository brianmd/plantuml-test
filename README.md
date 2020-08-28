Below is a plantuml diagram composed directly in github

```
@startuml

abstract class AbstractList
abstract AbstractCollection
interface List
interface Collection

List <|-- AbstractList
Collection <|-- AbstractCollection

Collection <|- List
AbstractCollection <|- AbstractList
AbstractList <|-- ArrayList

class ArrayList {
  Object[] elementData
  size()
}

enum TimeUnit {
  DAYS
  HOURS
  MINUTES
}

annotation SuppressWarnings

@enduml
```

![simple uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/brianmd/plantuml-test/master/simple.uml)
