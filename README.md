flowchart TD
    A[Usuário<br/>(Navegador Web)] --> B[Frontend<br/>Next.js]
    B --> C[API REST<br/>Spring Boot (Java 17)]
    C --> D[PostgreSQL<br/>(Railway)]
    E[AWS Lambda<br/>(Python + yfinance)] --> D
