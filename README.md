# Quinn: Online Stream Concurrency Optimization for QUIC

[![License](https://img.shields.io/badge/license-Apache%202.0-green)](https://github.com/Tencent-tquic/blob/develOP/LICENSE)

Quinn is an innovative algorithm designed to optimize stream concurrency over the QUIC protocol. It combines a utility function with online gradient descent (OGD) to dynamically adjust stream concurrency, resulting in improved file transfer performance under various network conditions.


## Features

- Optimizes stream concurrency in QUIC connections for more efficient file transfers.
- Achieves up to 60%-80% improvement over state-of-the-art algorithms in high-concurrency scenarios.
- Dynamically adjusts concurrency in response to changing traffic conditions for enhanced fairness and system efficiency.


## Prerequisites
Before getting started, ensure you have the following installed:
- Rust (latest stable version)
- CMake
- OpenSSL
- Git


## Installation
To install and set up Quinn, follow these steps:
1. Clone the repository:
   ```
   git clone https://github.com/wdj55556-bit/Quinn.git
   cd Quinn
   ```
2. Install dependencies:
   ```
   sudo apt-get update
   sudo apt-get install cmake libssl-dev pkg-config
   ```
3. Build the project:
   ```
   cargo build --release
   ```
   
   


## License

Quinn is under the Apache 2.0 license. See the [LICENSE](LICENSE) file for details.
