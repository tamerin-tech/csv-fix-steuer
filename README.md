Sure, here's the updated usage instructions for your README.md:

```markdown
# CSV Format Converter (US to DE)

## Description

This utility converts CSV files from US format to DE format suitable for bank accounts, credit cards, and other financial documents. It alters the decimal point from a dot (.) to a comma (,) and changes the field separator from a comma (,) to a semicolon (;), as per German financial systems standards.

## Usage

1. Place your original CSV files with US format in the `./data/inputs` folder.
2. Run the script using the command `node index.js`.
3. After the script is executed, find the converted files in the `./data/outputs` folder.

## Installation

Ensure Node.js is installed on your system. The installation steps differ slightly depending on your Node.js version:

- For Node.js version 18:
```bash
npm ci
```

- For other versions of Node.js:
```bash
npm install
```

## Running the Script

Execute the following command in the root directory of the utility:

```bash
node index.js
```

## Disclaimer

This utility is provided "as is" without any warranty. The user assumes full responsibility and risk of using this utility. The author is not liable for any damages or losses resulting from its use.

## Contributing

Contributions and bug reports are welcome. Please open an issue or a pull request on the project's repository.

