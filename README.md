# rust-new-project-template

A good starting point for a new Rust project. This template provides a well-structured setup for developing Rust applications, including formatting, linting, testing, and building.

## Features

- **Development Environment**: Configured with a `.devcontainer` for VS Code, including a Dockerfile to set up a consistent development environment.
- **Continuous Integration**: GitHub Actions workflows for linting, formatting, testing, and building the project.
- **Makefile**: Simplifies common tasks such as building, testing, and formatting the code.
- **Rust Tools**: Pre-configured with Clippy for linting, Rustfmt for formatting, and Cargo for building and testing.

## Getting Started

### Prerequisites

- Docker
- Visual Studio Code with the Remote - Containers extension

### Using the Template

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/rust-new-project-template.git
    cd rust-new-project-template
    ```

2. **Open in VS Code**:
    Open the project in Visual Studio Code. When prompted, reopen the project in the container.

3. **Build the Project**:
    Use the following command to build the project:
    ```sh
    make build
    ```

4. **Run the Project**:
    Use the following command to run the project:
    ```sh
    make run
    ```

5. **Test the Project**:
    Use the following command to run tests:
    ```sh
    make test
    ```

6. **Format the Code**:
    Use the following command to format the code:
    ```sh
    make fmt
    ```

7. **Lint the Code**:
    Use the following command to lint the code:
    ```sh
    make lint
    ```

## Makefile Commands

- `make help`: Show help information.
- `make version`: Show Rust versions.
- `make lint`: Lint the project using Clippy.
- `make test`: Run tests.
- `make run`: Run the application.
- `make build`: Build the project.
- `make release`: Build the application in release mode.
- `make all`: Run all tasks: format, lint, test, run.
- `make clean`: Clean the project.
- `make document`: Generate the documentation.
- `make fmt`: Format the project.
- `make bump`: Bump the version of the project.

## References

* [noahgift/rust-new-project-template](https://github.com/noahgift/rust-new-project-template.git)
* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
* [hello-rust](https://github.com/nogibjj/hello-rust)
