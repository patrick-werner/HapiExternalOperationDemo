# Project Name

This project is a Spring Boot application that utilizes the HAPI FHIR library to provide FHIR resource operations, including reindexing and resource conversion.

## Prerequisites

- Java 11 or higher
- Maven 3.6.0 or higher

## Getting Started

### Clone the Repository

```sh
git clone https://github.com/your-repo/project-name.git
cd project-name
```

### Build the Project

```sh
mvn clean install
```

## Project Structure

- `src/main/java/de/gefyra/provider/ResourceConversionProvider.java`: Provides an operation to convert FHIR resources.

### Convert Resource Operation

The `ResourceConversionProvider` class provides an operation to convert FHIR resources. You can call this operation using the following endpoint:

```
POST /$convert
```

#### Parameters

- `inputResource`: The FHIR resource to be converted.

## License

This project is licensed under the Apache License, Version 2.0. See the `LICENSE` file for details.

## Contact

For any inquiries, please contact [pa.f.werner@gmail.com].
