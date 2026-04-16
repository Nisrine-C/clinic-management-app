# Medical Clinic Management System

A web-based medical clinic management application built with Java, Spring Boot, JPA, and Thymeleaf. This project provides a platform to manage patients, doctors, appointments, consultations, and user roles efficiently.

---

## Features

- Manage patients: add, edit, delete, list, and search patients
- Manage doctors (Médecins)
- Schedule and manage appointments (RendezVous)
- Record and view consultations
- User and role management
- REST endpoints provided for patient operations
- Modern UI with Thymeleaf templates

---

## Tech Stack

- Java, Spring Boot / JEE
- Spring Data JPA & Hibernate
- Thymeleaf
- H2 (or other) database
- Spring Security
- Maven

---

## Project Structure

```
src/
 └── main/
      ├── java/ma/enset/jee_tp3
      │     ├── entities/     # Patient, Medecin, Consultation, etc.
      │     ├── repository/   # Spring Data JPA Repositories
      │     ├── service/      # Business services
      │     ├── web/          # Spring MVC Controllers (PatientController, etc.)
      │     └── enums/        # Enum classes
      └── resources/
            ├── templates/    # Thymeleaf HTML views
            └── application.properties
```

---

## Getting Started

1. **Clone this repository**

   ```sh
   git clone https://github.com/Nisrine-C/JEE_TP3_JPAThymeLeaf.git
   cd JEE_TP3_JPAThymeLeaf
   ```

2. **Run the Application**

   ```sh
   ./mvnw spring-boot:run
   ```

   The app will be available at `http://localhost:8080/`.

---

## Example Endpoints

- Web interface for patient management:  
  `http://localhost:8080/patients`
- REST endpoint for patients:  
  `http://localhost:8080/api/patients`

---

## Screenshots

<details>
<summary>Screenshots (click to expand)</summary>
- Patient list
- Add/Edit Patient forms
- Dashboard
</details>

---

## License

This project is for educational/demonstration purposes.
