# Running the Project

## Prerequisites

Before starting, make sure you have:

- **Java** installed (`Java 21` recommended)
- (Optional) **Gradle** installed globally (`gradle -v` to check)

## Installation

1. **Clone the project**
   ```bash
   git clone https://github.com/CoCoSol007/hyper.git
   cd hyper
   ```
2. **Grant execution permission to the Gradle wrapper (Linux/Mac)**
   ```bash
   chmod +x gradlew
   ```

## Running the Project

### Using the Gradle Wrapper (recommended)

- **On Linux/Mac**:
  ```bash
  ./gradlew run
  ```
- **On Windows**:
  ```sh
  gradlew.bat run
  ```

### If Gradle is installed globally

You can use the command:

```bash
gradle run
```

## Other Useful Commands

- **Build the project**:
  ```bash
  ./gradlew build
  ```
- **Clean generated files**:
  ```bash
  ./gradlew clean
  ```
- **Run tests**:
  ```bash
  ./gradlew test
  ```
