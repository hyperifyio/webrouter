# `webrouter` by [HyperifyIO](https://github.com/hyperifyio): Enhancing Web Connectivity

`webrouter` marks a significant stride in HyperifyIO's journey to fortify web 
application security and connectivity through innovative Public Key 
Infrastructure (PKI) solutions. This project is at the forefront of enabling 
advanced network communication within web environments.

## Revolutionizing Web-Based TCP Connections

At its core, `webrouter` introduces a novel WebSocket-based routing mechanism 
that paves the way for implementing raw TCP connections in browser settings. 
This enables the development of web applications that demand custom TLS 
settings, including the utilization of mutual TLS (mTLS) connections, for 
unparalleled security and privacy.

`webrouter` is crafted for developers who aim to integrate secure, raw TCP 
connections within their web applications. It emerges as an indispensable 
resource for enhancing web application security without compromising on 
performance.

While `webrouter` focuses on TCP network routing, it is essential to note that 
SSL encryption is not directly provided. Instead, developers can utilize 
standard SSL libraries tailored for WebAssembly to create secure mTLS 
connections. Additionally, our [webhsm](https://github.com/hyperifyio/webhsm) 
project offers robust management of PKI secrets to complement the capabilities 
of `webrouter`.

**Project Status**: `webrouter` is under active development, progressing 
towards its firstl major release. Our team is dedicated to optimizing the 
platform's reliability and user-friendliness. For the latest developments and 
milestones, follow our [project status](https://github.com/hyperifyio/webrouter/issues/1).

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
