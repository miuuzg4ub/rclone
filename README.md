# Contributing to Rclone

Thank you for considering contributing to Rclone! Rclone is an open-source command-line program to manage files on cloud storage.

## How to Contribute

1. **Bug Reports & Feature Requests**: Please check the [Issue Tracker](https://github.com/rclone/rclone/issues) before opening a new issue.
2. **Pull Requests**:
   - Fork the repository.
   - Create a feature branch (`git checkout -b feature/my-feature`).
   - Run tests before submitting (`go test ./...`).
   - Format code using `gofmt`.
   - Commit your changes with a clear, descriptive commit message.

## Building from Source

Make sure you have Go installed (Go 1.21 or newer recommended).

```bash
git clone https://github.com/rclone/rclone.git
cd rclone
go build
```

## Running Tests

To run the short test suite locally:

```bash
go test -v ./...
```

For more detailed contribution guidelines, please visit the official [Rclone Documentation](https://rclone.org/contribute/).