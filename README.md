# Bash script to obfuscate php files

The script is recursively strip comments and whitespaces down of  php files in the given project folder.

## Installation

```bash
composer global require nazares/nobfus
```

## Usage

before you start add `.ignore` file in your `$PWD` directory

```bash
nobfus path/to/your/php/project
```
