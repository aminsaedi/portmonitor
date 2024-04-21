
# PortMonitor: TCP Socket Waiter

### What is PortMonitor?

PortMonitor is a simple yet powerful command-line tool written in Rust that waits until a TCP socket becomes open. It's perfect for automating tasks that depend on a specific port being available.

### How does it work?

PortMonitor takes a single argument: the TCP port number you want to wait for. Once you run PortMonitor, it will continuously check if the specified port is open. As soon as the port becomes available, PortMonitor will exit with a success status code (0).

### Usage

```sh
portmonitor <port_number>
```

### Example

```sh
portmonitor 8080 && curl http://localhost:8080
```

## Installation

### Using Cargo

```sh
cargo install portmonitor
```


### Using install script

```sh
curl https://raw.githubusercontent.com/aminsaedi/portmonitor/master/install.sh | bash
```

## Contributing

Contributions are always welcome!
If you'd like to help improve PortMonitor, please open an issue or submit a pull request.

## License

[MIT](https://choosealicense.com/licenses/mit/)

