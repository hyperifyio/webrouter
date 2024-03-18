# `hyperifyio/webrouter`: WebSocket-based TCP Routing for web applications

## Overview

`webrouter` is a project under development by [HyperifyIO](https://www.hyperify.io), designed to 
provide utilities to create raw TCP connections within web environments. 

Leveraging a WebSocket-based routing mechanism it enables use of more advanced 
features like custom mTLS connections within the browser environment, enabling 
end-to-end encrypted mutual TLS (mTLS) connections tailored to the specific 
needs of custom software projects.

`webrouter` is engineered for developers seeking to implement secure, raw TCP 
connections in browser environments, making it an essential tool for web 
applications that require custom TLS settings for enhanced security and 
privacy.

Note, `webrouter` only provides the TCP network routing. It does not provide 
SSL encryption. To use mTLS, you would use standard SSL libraries like Go's 
standard library and build your solution for WebAssembly. We may provide a 
client library later though. We also provide 
[webhsm](https://github.com/hyperifyio/webhsm) for secure handling of PKI 
secrets.

**Project Status**: Currently in active development, `webrouter` is moving 
towards its first major release. Our team is focused on ensuring the platform's 
reliability, performance, and ease of use. Stay tuned for updates and 
milestones by visiting our [project issue](https://github.com/hyperifyio/webrouter/issues/1).

## Key Features (TODO!)

- **WebSocket-based TCP Routing**: Innovative approach to manage raw TCP 
  connections via WebSockets, enabling secure, real-time data transfer.

- **Seamless Integration**: Designed for easy integration into existing web 
  applications, enhancing security without compromising performance.

- **Developer-Friendly**: Offers comprehensive documentation and examples, 
  making it accessible to developers of all skill levels.

- **Scalable and Reliable**: Built to handle high volumes of connections with 
  minimal latency, ensuring reliability and performance at scale.

## Getting Started

Instructions on setting up and using `webrouter` will be provided upon the 
project's release, including detailed documentation on installation, 
configuration, and API usage.

## Contribution

HyperifyIO welcomes contributions to the `webrouter` project! Whether you're 
interested in enhancing functionality, fixing bugs, or suggesting new features, 
your input is greatly appreciated.

Join our community on [Discord](https://discord.com/invite/UBTrHxA78f) to 
discuss development, share ideas, and contribute to the project.

## License

`webrouter` is available under the Functional Source License, Version 1.1, MIT 
Future License (FSL-1.1-MIT), allowing for use, copying, modification, and 
redistribution for approved purposes, excluding competitive uses. Two years 
post-release, the software will also be available under MIT license terms. For 
complete license details, refer to the [LICENSE.md](LICENSE) file.

## Support

For support or further inquiries, especially regarding the implementation and 
usage of `webrouter` in your projects, please contact us directly at 
info@hg.fi.
