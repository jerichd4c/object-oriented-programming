<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/jerichd4c/object-oriented-programming/tree/main/office-space-proyect">
    <img src="https://raw.githubusercontent.com/jerichd4c/ReflexJDBC/main/java_logo.svg" alt="Logo" width="80" height="80">
  </a>
</div>

<div align="center">
<h3 align="center">Office Space Project</h3>

  <p align="center">
    A Java console application for simulating and managing an office space represented by a matrix.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is a Java console application that simulates and manages an office space, represented abstractly by a matrix. It allows users to choose between two matrix sizes (4x6 and 5x4) to simulate a workplace ("sede"). The application provides functionalities to manipulate elements in this matrix, representing employees and a boss in different cubicles.

Features include:
- Viewing specific cubicles or the full office layout.
- Assigning employees to cubicles.
- Assigning, viewing, or removing a boss.
- Removing employees.
- Viewing adjacent office cubicles.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Java][Java-shield]][Java-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

* Java Development Kit (JDK) 8 or higher.
* A Java-compatible IDE (Eclipse, VS Code, IntelliJ IDEA, or NetBeans) or terminal to compile and run.

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/jerichd4c/object-oriented-programming.git
   ```
2. Navigate to the project directory
   ```sh
   cd object-oriented-programming/office-space-proyect
   ```
3. Compile the Java file
   ```sh
   javac src/main/java/ProyectoSedes.java
   ```
4. Run the program
   ```sh
   java -cp src/main/java ProyectoSedes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Upon running the application, you'll be prompted to choose the data type (Integer, String, or a mix) to populate the initial matrix. After selecting your preferred option, choose up to 2 locations (Sede 1: 4x6 or Sede 2: 5x4).

The main menu will display the following options:
1. **Mostrar cubiculo**: View the contents of a specific row and column.
2. **Mostrar oficina completa**: Print the full matrix layout to the console.
3. **Asignar oficina**: Add a new employee to a specific cubicle.
4. **Mostrar jefe**: View the current boss's position.
5. **Asignar jefe**: Assign a new boss to a specific position.
6. **Deasignar jefe**: Remove the boss from the office.
7. **Eliminar empleado**: Remove an employee from a specific position.
8. **Mostrar oficinas adyacentes**: View the content of the adjacent cubicles (up, down, left, right).
9. **Salir**: Exit the program.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Translate console output and user prompts to English
- [ ] Rename Java variables and methods to English conventions
- [ ] Update code comments and documentation

See the [open issues](https://github.com/jerichd4c/object-oriented-programming/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Java-shield]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://www.java.com/
