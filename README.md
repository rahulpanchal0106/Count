# Custom Bash Configuration

## Overview

This repository contains custom bash configurations that can be used to personalize your shell environment. The main purpose of this configuration is to move the `.bashrc` file to a custom directory (`~/new_dir`) and update the `.bash_profile` or `.bashrc` to source the `.bashrc` file from this new location.

## Usage

### Prerequisites

- Bash shell

### Setup

1. Copy the code from a perticular function directory

2. Paste the function into you `~/.bashrc` or `~/.bash_profile` configuration file.

3. Save the changes and exit the text editor.

4. Reload the `.bash_profile` or `.bashrc` file to apply the changes:

   ```bash
   exec bash
   ```
   
  or
  
   ```bash
   source ~/.bash_profile
   ```

   or

   ```bash
   source ~/.bashrc
   ```

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or create a pull request.

## License

This project is licensed under the [GNU GPLv2.0](LICENSE).
