# Ejercicio 1: Students Classrooms Courses

## Diagrama ER con Mermaid
```mermaid
erDiagram
    STUDENTS ||--|{ CLASSROOMS : have
    STUDENTS {
        int id_student PK
        string name_student
        string classroom_id FK
    }
    CLASSROOMS ||--|{ COURSES : have
    CLASSROOMS {
        int id_classroom PK
        string description_classroom
    }
    COURSES {
        int id_course PK
        string name_course
        string classroom_id FK
    }
```

## Tabla normalizada: 1FN
<img width="422" height="428" alt="image" src="https://github.com/user-attachments/assets/c5ae595d-bff1-4017-a19a-be78e8c8d58f" />


## Tabla normalizada: 3FN
<img width="603" height="137" alt="image" src="https://github.com/user-attachments/assets/fa6d3734-be69-4723-919c-700778979bbe" />

## Diagrama ER (de Chen)
<img width="335" height="291" alt="image" src="https://github.com/user-attachments/assets/d8d4221c-1e3a-4d23-b18e-8a7a2d2b3a0c" />

## Diagrama UML (Database Schema - Patas de gallo)
<img width="376" height="254" alt="image" src="https://github.com/user-attachments/assets/b6df19d2-f391-4ecb-846c-bc665a23b29e" />
