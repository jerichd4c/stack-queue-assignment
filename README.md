<a id="readme-top"></a>

<div align="center">
  <h3 align="center"> Stack and Queues Assignment </h3>

  <p align="center">
    A C++ project demonstrating fundamental data structures: Stack Inversion, Priority Queue Processing, and Linked List-based Priority Queues.
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

This project contains optimized C++ implementations of fundamental data structures crafted for academic coursework:

- **`TAREA2_PilaInvertida.CPP`**: Reverses a stack in-place using a temporary stack while maintaining the original stack structure.
- **`TAREA2_ProcesarDatos.cpp`**: Processes queue data by priority order without using standard queue classes, demonstrating FIFO compliance.
- **`TAREA2_ColaDePrioridadSimple.cpp`**: Implements a priority queue template using simple linked lists, where each priority level contains its own internal queue.

### Built With

* [![C++][Cpp-shield]][Cpp-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, compile the source code natively via GCC/G++.

### Prerequisites

* GCC / G++ (MinGW on Windows)
* C++11 or higher

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/data-structures-assignment-2.git
   ```
2. Navigate to the project directory
   ```sh
   cd repositorio-local-tarea-1
   ```
3. Compile the desired data structure
   ```sh
   # Compile Stack Inversion
   g++ TAREA2_PilaInvertida.CPP -o bin/PilaInvertida.exe
   
   # Compile Priority Queue Processing
   g++ TAREA2_ProcesarDatos.cpp -o bin/ProcesarDatos.exe
   
   # Compile Linked List Priority Queue
   g++ TAREA2_ColaDePrioridadSimple.cpp -o bin/ColaDePrioridadSimple.exe
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Execute the preferred binary to run the interactive console environment:

```sh
# Run Stack Inversion
./bin/PilaInvertida.exe

# Run Priority Queue Processing
./bin/ProcesarDatos.exe

# Run Linked List Priority Queue
./bin/ColaDePrioridadSimple.exe
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [ ] Refactor `TAREA2_ColaDePrioridadSimple.cpp` to implement a dedicated `push` function for inserting data into priority queues, instead of traversing all nodes to reach the target queue.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Cpp-shield]: https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white
[Cpp-url]: https://isocpp.org/