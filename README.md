# db2022-mermaid

## Entity Relationship Diagram

```mermaid
erDiagram
        
Student ||--}| StudentSchool : enrolls
School ||--}| StudentSchool : accepts


    StudentSchool {
        int Id
        int SchoolId
    }
    
    Student {
        int Id
        string FirstName
        string LastName
    }
    
    School {
        int SchoolId
        string Name
        string City
    }
    
```
