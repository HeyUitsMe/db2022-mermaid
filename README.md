# db2022-mermaid

## Entity Relationship Diagram

```mermaid
erDiagram
        
Student ||--|{ StudentSchool : enrolls
School ||--|{ StudentSchool : accepts


    StudentSchool {
        int Id PRI
        int SchoolId PRI
    }
    
    Student {
        int Id PRI
        varchar FirstName " "
        varchar LastName " "
    }
    
    School {
        int SchoolId PRI
        varchar Name " "
        varchar City " "
    }
    
```
