```markdown
# Sherlock

Sherlock is an open-source tool for searching usernames on multiple websites and social media platforms. This tool helps you track the online presence of a username across various internet services.

![Sherlock Logo](https://raw.githubusercontent.com/sherlock-project/sherlock/master/images/logo.png)

## Contents

- [Installation](#installation)
- [Updating](#updating)
- [Basic Usage](#basic-usage)
- [Troubleshooting](#troubleshooting)
- [Recommendation](#recommendation)
- [Contributing](#contributing)
- [FAQs](#faqs)
- [Contact](#contact)

## Installation

Before using Sherlock, make sure you have Python 3 installed on your system. Then, follow these steps:

1. **Clone the Repository**:

   Open a terminal and navigate to the location where you want to keep the Sherlock tool. Then, clone the official repository from GitHub using the following command:

   ```bash
   git clone https://github.com/sherlock-project/sherlock.git
   ```

2. **Navigate to the Sherlock Directory**:

   Change into the Sherlock directory that you just cloned:

   ```bash
   cd sherlock
   ```

3. **Install Dependencies**:

   Ensure you have all required dependencies installed by running the following command:

   ```bash
   python3 -m pip install -r requirements.txt
   ```

## Updating

If you already have Sherlock installed and want to update it to the latest version, follow these steps:

1. **Navigate to the Sherlock Directory**:

   Ensure you are in the Sherlock directory:

   ```bash
   cd /path/to/your/sherlock/directory
   ```

2. **Update Sherlock**:

   To make sure you have the latest version of Sherlock, use the following command:

   ```bash
   git pull
   ```

## Basic Usage

Once you have Sherlock installed or updated, you can search for online usernames as follows:

```bash
python3 sherlock.py username
```

This will search for the username on various websites and display the results.

## Troubleshooting

### Issue: ImportError: attempted relative import with no known parent package

If you encounter this error while running Sherlock, follow these steps to resolve it:

1. **Navigate to the Sherlock Directory**:

   Make sure you are in the Sherlock directory:

   ```bash
   cd /path/to/your/sherlock/directory
   ```

2. **Run Sherlock using the following command**:

   ```bash
   python3 -m sherlock sherlock username
   ```

This should resolve the problem of relative import.

## Recommendation

If you experience issues or wish to perform a clean reinstallation of Sherlock, you can follow the following recommendation:

1. **Delete the Sherlock Folder**:

   Open a terminal and execute the following command to delete the Sherlock folder:

   ```bash
   rm -r /lib/python3/dist-packages/sherlock
   ```

   This will remove the current Sherlock installation folder.

2. **Reinstall Sherlock**:

   After deleting the folder, you can follow the installation instructions in the corresponding section of this README.md to reinstall Sherlock:

   ```shell
   # Clone the repo
   $ git clone https://github.com/sherlock-project/sherlock.git

   # Change the working directory to sherlock
   $ cd sherlock

   # Install the requirements
   $ python3 -m pip install -r requirements.txt
   ```

   This will allow you to perform a fresh installation of Sherlock.

Please note that this recommendation is helpful if you encounter issues or want to start fresh. Be sure to back up any important data before deleting the folder.

## Contributing

If you wish to contribute to the development of Sherlock, feel free to read our [contribution guidelines](CONTRIBUTING.md) and join our community on [GitHub Discussions](https://github.com/sherlock-project/sherlock/discussions).

## FAQs

You can check our list of [frequently asked questions](FAQ.md) for answers to common queries.

## Contact

If you have any questions or issues, don't hesitate to [contact us](https://github.com/sherlock-project/sherlock/issues).

## Follow Me

- [My GitHub Profile](https://github.com/Rootuser47363)
- [My Twitter Profile](https://twitter.com/empanadadeUwU47)

Enjoy using Sherlock!
```
