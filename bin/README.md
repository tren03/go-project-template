## `/bin` Directory

This folder is used to store the compiled binary files of the Go project.

### Purpose

The `/bin` directory is intended to hold the **compiled binaries** for this project. When you manually compile your Go source code, the resulting binary will be placed in this folder, keeping the project organized by separating the source code from the compiled artifacts.

### How to Build the Project

To build the project manually and generate a binary:

1. Open a terminal and navigate to the root of the project.
2. Run the following command to build the project and output the binary into the `/bin` folder:
   ```bash
   go build -o ./bin/myapp ./cmd/myapp
