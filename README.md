[![tp2](https://github.com/EnriHeller/Paradigmas-TP2-G07/actions/workflows/build.yml/badge.svg)](https://github.com/EnriHeller/Paradigmas-TP2-G07/actions/workflows/build.yml)
[![codecov](https://codecov.io/gh/EnriHeller/Paradigmas-TP2-G07/branch/main/graph/badge.svg)](https://codecov.io/gh/EnriHeller/Paradigmas-TP2-G07)

# GWENT Clone

This repository contains a Java implementation of the GWENT card game from The Witcher universe, developed as part of the Paradigms of Programming course (TP2) at FIUBA.

## Group 07

- **Matias Domine Folco** - [MatiasDFFIUBA](https://github.com/MatiasDFFIUBA)
- **Enrique Heller** - [EnriHeller](https://github.com/EnriHeller)
- **Andy Mayuri** - [AndyPinta](https://github.com/AndyPinta)
- **Franco Montanelli** - [francomtn](https://github.com/francomtn)
- **Andrés Moyano** - [MegaPZD](https://github.com/MegaPZD)

Corrector: **Joaquin Pandolfi**

## Progress on Report
https://docs.google.com/document/d/18iqyxu4yDWuSU02GvPL2Z80ao-PXP8TGW9Ev1fI3kvU/edit?usp=sharing

## Application

The latest version of the application can be found in the [releases](https://github.com/fiuba/algo3_proyecto_base_tp2/releases/latest) tab and can be run on Linux, Windows, or Mac as follows:

```bash
$ java -jar <file.jar>
```

## Development

Those who wish to contribute to the project can consult the [development guide](./docs/Desarrollo.md).

## Project Structure

- **`src/main/java/`**: Main source code, including controllers, models, and views for the game logic.
- **`src/test/java/`**: Unit tests organized by deliveries (entrega_1, entrega_2, etc.).
- **`diagrams/`**: UML diagrams using PlantUML for classes, packages, and sequences.
- **`docker/`**: Docker setup for containerized deployment.
- **`docs/`**: Documentation, including development, Docker, and PlantUML guides.
- **`informe/`**: Final report in LaTeX.
- **`scripts/`**: Build, test, and deployment scripts.

## Technologies

- **Java**: Core language.
- **JavaFX**: For the graphical user interface.
- **Maven**: Build tool.
- **JUnit**: Testing framework.
- **Docker**: Containerization.
- **GitHub Actions**: CI/CD pipelines.

## Installation and Execution

### Prerequisites

- Java 11 or higher
- Maven

### Build and Run

1. Clone the repository:
   ```bash
   git clone https://github.com/EnriHeller/GWENT_Clone.git
   cd GWENT_Clone
   ```

2. Build the project:
   ```bash
   mvn clean compile
   ```

3. Run the application:
   ```bash
   mvn javafx:run
   ```

### Using Docker

Use the provided scripts in `docker/` to run the application in a container.

## License

This repository is under the MIT License.
