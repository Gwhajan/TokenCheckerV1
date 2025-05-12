# Discord Token Checker

A high-performance Discord Token Checker designed to rapidly and accurately validate large volumes of Discord tokens. Built with efficiency and speed in mind, this tool helps you manage and verify token validity seamlessly.

## Features

* 🔍 **Fast Validation:** Quickly checks the validity of Discord tokens.
* 📊 **Detailed Logs:** Provides clear and structured logs of valid, invalid, and locked tokens.
* ⚡ **High Performance:** Optimized for rapid processing of large token lists.
* 🔒 **Secure:** All operations are executed securely, ensuring no data leaks.
* 🗂️ **Customizable Output:** Easily configure where valid and invalid tokens are stored.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Gwhajan/TokenCheckerV1.git
   cd discord-token-checker
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the checker, simply execute:

```bash
python main.py
```

You can place your tokens in a text file named `tokens.txt`, with each token on a new line. The output will be saved in separate files for valid, invalid, and locked tokens.

## Configuration

You can adjust the following settings in `config.toml`:

*`threads`: The number of concurrent threads for checking tokens.
*`proxyless`: If true, the checker runs without proxies. If false, it expects a

Example configuration:

```toml
threads = 50
proxyless = true
```

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For custom bot development or inquiries, contact me at [Biozard Services](https://discord.gg/GVPjdhzTZ3).
