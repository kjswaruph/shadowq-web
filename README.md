# ShadowQ Web Application

Web application for ShadowQ discord bot built with Spring Boot and React.

## Technology Stack
- Java 21
- Spring Boot 
- PostgreSQL
- React with Vite

## Prerequisites

- JDK 21
- Node.js 
- PostgreSQL
- Git

## Getting Started

### Backend Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/shadowq-web.git
cd shadowq-web
```
2. Edit the application.properties.example
   - Edit file `application.properties.example` to `application.properties`
   - Update the credentials in `application.properties`
   
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/shadowqweb-dev
spring.datasource.username=your_username
spring.datasource.password=your_password 
```

3. Configure the database:
   - Create a PostgreSQL database named `shadowqweb-dev`

4. Run the backend:
```bash
cd backend
./gradlew bootRun
```

### Frontend Setup

1. Install dependencies:
```bash
cd frontend
npm install
```

2. Run the development server:
```bash
npm run dev
```

### Endpoints

- /
- /

## Contributing

1. Fork the repo 
2. Make your changes
3. Write/update tests
4. Create a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details
