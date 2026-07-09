# Ejercicio 1: Students Classrooms Courses


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
