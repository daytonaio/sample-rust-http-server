# Rust Http Server

This project is a build of a web server in Rust on bare minimum from scratch with only `std::TCPListener`. This is only a fun project to learn rust.

---

## 🚀 Getting Started

### Open Using Daytona

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/). Make sure that you have a `provider` installed.
2. **Create the Workspace**:
   ```bash
   daytona create https://github.com/daytonaio/sample-rust-http-server.git
   ```
   You should get something like: `{"outcome":"success","result":"done"}`
3. **Open Workplace in you IDE**

   ```bash
   daytona code
   ```

   select your project that you. created recently. it will open in default editor.

4. **Build Application**:

   ```bash
   cargo build
   ```

5. **Start the Application**:
   ```bash
   cargo run
   ```
   Running on `http://localhost:5000`

---

## ✨ Features

1. It supports api requests and html files,
2. We can create a api route for the following methods:

- GET
- POST
- PUT
- DELETE

_We can add more but as of now I don't have time to add them, If you want then feel free to add and work around._

3. The Project is completely memory safe as the language Rust is and very performance effective as it doesn't and a clone of any request and saves every bit of memory.
