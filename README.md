\# Blood Banking System



A full-stack blood banking application combining a \*\*Java Spring Boot backend\*\* with a \*\*React frontend built using Vite\*\*.



The application is organized as a monorepo to keep the frontend and backend in one repository.



\## Project Structure



```text

BloodBankingSystem/

├── backend/

│   ├── src/

│   ├── pom.xml

│   └── mvnw

│

├── frontend/

│   ├── src/

│   ├── public/

│   ├── package.json

│   └── vite.config.js

│

└── README.md

```



\## Technology Stack



\### Backend

\- Java

\- Spring Boot

\- Maven

\- Spring Data JPA

\- REST APIs



\### Frontend

\- React

\- JavaScript

\- Vite

\- HTML and CSS



\## Application Features



The source project describes the following functionality:



\- Donor registration and management

\- Donor search and filtering

\- Blood request management

\- Blood inventory management

\- User and role management

\- Dashboard and administrative features



\*Feature availability and end-to-end functionality are yet to be verified.\*



\## Getting Started



\### Prerequisites



\- Java Development Kit (JDK)

\- Node.js and npm

\- Git



\### Backend Setup



Navigate to the backend directory:



```bash

cd backend

```



Run the application using the Maven wrapper:



\*\*Windows:\*\*

```powershell

.\\mvnw.cmd spring-boot:run

```



\*\*Linux/macOS:\*\*

```bash

./mvnw spring-boot:run

```



\### Frontend Setup



Open another terminal and navigate to the frontend directory:



```bash

cd frontend

```



Install dependencies:



```bash

npm install

```



Start the development server:



```bash

npm run dev

```



Follow the local URL printed by Vite.



\## Repository Organization



This repository brings together two separately maintained source repositories:



\- Backend: https://github.com/Gnaneswar-S/BloodBankingSystem-Backend

\- Frontend: https://github.com/Gnaneswar-S/BloodBankingSystem-frontend



The code is retained in separate directories to preserve the original application structure.



\## Project Status



\- \[x] Backend and frontend source files combined.

\- \[x] Monorepo initialized with Git.

\- \[x] Combined repository pushed to GitHub.

\- \[ ] Backend build and startup verification.

\- \[ ] Frontend startup verification.

\- \[ ] Frontend-backend API integration verification.

\- \[ ] End-to-end application testing.



\## Attribution



The backend and frontend source code were obtained from the separately maintained repositories linked above and combined for organizational and learning purposes. Original authorship, licensing, and applicable attribution requirements should be respected.



Further development and modifications should be documented separately.



\---



\*\*Repository:\*\* https://github.com/Gnaneswar-S/BloodBankingSystem

