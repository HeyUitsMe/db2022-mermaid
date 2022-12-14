# db2022-mermaid


## Entity Relation Diagram

'''mermaid
erDiagram
Student ||--|{ StudentSchool : enrolls
School ||--|{ StudentSchool : accepts

StudentSchool {
int Id
int SchoolId
}

Student{
int Id
String FirstName
String LastName
}

School{
int Id
String Name
String City
}

'''
