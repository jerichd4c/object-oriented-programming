<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/jerichd4c/object-oriented-programming/tree/main/jframe-file-explorer">
    <img src="https://raw.githubusercontent.com/jerichd4c/ReflexJDBC/main/java_logo.svg" alt="Logo" width="80" height="80">
  </a>
</div>

<div align="center">
  <h3 align="center">Jframe File Explorer</h3>

  <p align="center">
    A minimalist Java tool for browsing and managing files using a modern JFrame graphical interface.
  </p>
</div>

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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

![File Explorer](sample_img.png)

This is a lightweight, responsive Java application designed to function as a desktop file explorer. Utilizing Swing/JFrame, it offers essential functionality to open, read, display statistics, and conditionally encrypt `.txt` files directly from your workspace.

### Built With

* [![Java][Java-shield]][Java-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

* Java JDK 11 or higher

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/object-oriented-programming.git
   ```
2. Navigate to the project directory
   ```sh
   cd object-oriented-programming/jframe-file-explorer
   ```
3. Compile the source
   ```sh
   javac -d out src/main/java/exploradorarchivos/core/FileExplorer.java
   ```
4. Run the program
   ```sh
   java -cp out exploradorarchivos.core.FileExplorer
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [ ] Modularize the source code for better maintainability.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Once launched, the JFrame window lets you browse to a `.txt` file, open it to read its contents and view basic statistics (line/word/character counts), and optionally encrypt it before saving.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Java-shield]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://www.java.com/
