# cNEO

cNEO is a fast, lightweight C-based compiler and bootstrap for the NEO programming language, designed for efficient and reliable software development.

## Overview

cNEO is a high-performance compiler written in C to bootstrap the NEO programming language, a statically typed language inspired by modern programming paradigms. It compiles NEO code with zero library dependencies, transpiling to C for speed and portability. cNEO aims to provide a minimal yet powerful toolkit for developers building scalable and maintainable NEO applications.

## Features

- **Fast Compilation**: Leverages C for high-speed compilation of NEO code.
- **Zero Dependencies**: Compiles NEO code without external library dependencies.
- **Transpiles to C**: Generates efficient C code for cross-platform compatibility.
- **Lightweight**: Minimal footprint for rapid development and deployment.
- **Statically Typed**: Inherits NEO’s robust type system for safe programming.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/neolang/cneo.git
   cd cneo
   ```

2. **Build cNEO**:
   Ensure you have a C compiler (e.g., `gcc`) installed.
   ```bash
   make
   ```

3. **Install**:
   ```bash
   make install
   ```

## Usage

Compile a NEO program (`example.n` or `example.v`):
```bash
neo example.n
```

Run the generated executable:
```bash
./example
```

or Run executable directly:
```bash
neo run example.n
```

## Contributing

We welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License

cNEO is licensed under the [MIT License](LICENSE).

## Contact

- **Website**: [neolang.io](https://neolang.io)
- **Email**: [info@neolang.io](mailto:info@neolang.io)
- **GitHub**: [@neolang](https://github.com/neolang)
