# Ox64-CP2102 Configuration Guide

This repository provides a comprehensive guide and tools for configuring the CP2102 USB-to-UART bridge to enable high-speed serial communication with the Ox64 single-board computer. 

The Ox64 is a versatile RISC-V based SBC equipped with a variety of communication interfaces. This documentation focuses on preparing the CP2102 to interface with the Ox64 at baud rates up to 2000000 bps.

## Getting Started

Before you begin with the configuration, please ensure you have the following:

- A CP2102 USB-to-UART adapter
- The Ox64 single-board computer
- Access to a computer with the necessary drivers installed for the CP2102

Detailed steps for the entire setup process are provided in the [Configuration Guide](docs/CP2102_Configuration_Guide.md).

## Prerequisites

- [Silicon Labs CP2102 Drivers](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)
- [CP21xxCustomizationUtility Software Package](https://www.silabs.com/documents/public/example-code/AN721SW.zip)

Please make sure to install the above software before proceeding with the guide.

## Documentation

- [CP2102 Configuration Guide](docs/CP2102_Configuration_Guide.md): Step-by-step instructions on how to reconfigure your CP2102 adapter for high-speed communication.

## Troubleshooting

For common issues and their resolutions, please refer to the [Troubleshooting Guide](docs/Troubleshooting.md).

## Contributing

We welcome contributions to this repository! If you have suggestions for improvements or have developed a more efficient method, please see our [Contribution Guidelines](CONTRIBUTING.md) for how to propose changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Silicon Labs team for providing the tools and software that make this possible.
- Kudos to the Pine64 and Ox64 communities for their invaluable support and resources.

## Contact

For further assistance, please open an issue in this repository or reach out to the community on the [Pine64 Forum](https://forum.pine64.org/).

Thank you for using or contributing to this project!
