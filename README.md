# Student Database Management System

A student-record management project. The existing project description lists staff login, student-record CRUD, marks management, and attendance management.

> **Repository packaging note:** The application source is currently stored as `student_database_management_system.zip`; the repository root does not contain the extracted Spring Boot source tree. The features and technology stack below are taken from the existing project description and have not yet been independently verified against the contents of that archive.

## Features described by the project

- Staff registration and login.
- Add, view, update, and delete student records.
- Add, view, update, and delete student marks.
- Add, view, update, and delete attendance records.
- Home, About, and Contact pages.
- Staff logout.

## Technology stack described by the project

- Java and Spring Boot for backend application logic.
- Thymeleaf for server-side HTML rendering.
- Spring Data JPA and Hibernate for persistence / ORM.
- MySQL for relational storage.
- Spring Security for authentication and authorization.
- HTML, CSS, and JavaScript for the user interface.
- Maven for dependency management and builds.

## Repository contents

- `student_database_management_system.zip` — archived project source.
- `Results/` — application screenshots and supporting files.
- `README.md` — project overview and stated technology stack.

## Inspect and run the application

Extract the archive locally before attempting to build or run the project:

```bash
unzip student_database_management_system.zip -d student-database-management-system
cd student-database-management-system
```

The repository does not expose the extracted `pom.xml`, Spring Boot entry point, application properties, schema scripts, or database configuration at its root. Once extracted, inspect the project files and follow their Maven / Spring Boot setup instructions. Configure the MySQL datasource and create the required database before starting the application.

## Documentation and code-audit status

The high-level features and stack are documented, but the implementation cannot be accurately audited from the current root-level repository contents because the source is packaged in a ZIP archive. Extract and commit the source tree (excluding secrets and build outputs), or provide the archive for a deeper review, before making claims about database schema, endpoint design, validation, or security configuration.

## License

See the archive's license and third-party dependency terms.
