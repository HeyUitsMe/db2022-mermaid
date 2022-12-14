# db2022-mermaid

## Entity Relationship Diagram

```mermaid
erDiagram
        
Student ||--|{ StudentSchool : enrolls
School ||--|{ StudentSchool : accepts


    StudentSchool {
        int Id
        int SchoolId
    }
    
    Student {
        int Id
        String FirstName
        String LastName
    }
    
    School {
        int SchoolId
        String Name
        String City
    }
    
```
