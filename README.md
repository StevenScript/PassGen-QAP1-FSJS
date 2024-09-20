# PassGen-QAP1-FSJS

## Author

**Steven Norris (stevenscript)**  
_September 19, 2024_

### A CLI Password Generator by Steven Norris (stevenscript)

This is a command-line interface (CLI) tool for generating passwords, built as part of my Full Stack JavaScript course's first assignment of this term. You can customize the password's length and reduce complexity by excluding numbers, uppercase letters, and special characters. The default behavior creates a secure, complex password.

---

## Features

- **Default Password**: If no flags are specified, a default password of 8 characters is generated, including numbers, uppercase letters, and symbols.
- **Customizable Options**:
  - `--setlength [number]`: Specify the length of the password. The default is 8 characters.
  - `--nonumbers`: Exclude numbers from the password.
  - `--nouppercase`: Exclude uppercase letters from the password.
  - `--nosymbols`: Exclude symbols from the password.
- **Help**: Use `--help` to display usage instructions and examples.

---

## Usage

In the terminal, navigate to the directory where the project is located or link the package globally via `npm link`.

### Linux Examples:

- **Generate a default password**:

  ```bash
  passgen
  ```

- **Generate a password with 12 characters, no symbols**:

  ```bash
  passgen --setlength 12 --nosymbols
  ```

### Windows Examples:

- **Generate a password without numbers and uppercase letters:**:

```bash
node PassGenerator.js --nonumbers --nouppercase
```

- **Generate a password without numbers, symbols, and uppercase letters:**:

```bash
node PassGenerator.js --nonumbers --nouppercase --nosymbols
```
