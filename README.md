# db2022-mermaid

## Entity Relationship Diagram

```mermaid
erDiagram
        
Student ||--|{ StudentSchool : enrolls
School ||--|{ StudentSchool : accepts

    StudentSchool {
        int Id PK
        int SchoolId PK
    }
    
    Student {
        int Id PK
        string FirstName
        string LastName
    }
    
    School {
        int SchoolId PK
        string Name
        string City
    }    
```
