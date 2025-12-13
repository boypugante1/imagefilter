# ImageFilter: Custom Image Filter for MRTech IFF C SDK 🎨

![ImageFilter](https://img.shields.io/badge/ImageFilter-C%20SDK-blue)

Welcome to the **ImageFilter** repository! This project demonstrates a custom image filter designed for the MRTech IFF C SDK. Our goal is to provide an efficient and flexible solution for image processing, particularly in the fields of machine vision and low-latency applications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Introduction

Image processing is a vital part of many modern applications, especially those that rely on camera systems and real-time data. The **ImageFilter** project showcases how to implement a custom filter using the MRTech IFF C SDK. With support for various formats like DNG, TIFF, and efficient processing on GPU using CUDA, this project aims to simplify and enhance image manipulation tasks.

## Features

- **Custom Filters**: Create and apply custom image filters tailored to specific needs.
- **Support for Multiple Formats**: Handle DNG, TIFF, and more.
- **GPU Acceleration**: Utilize CUDA for faster processing.
- **Low Latency**: Designed for real-time applications.
- **REST API**: Easily integrate with other systems.
- **Compatibility with GenICam**: Streamline camera control and image acquisition.
- **Support for H264 and H265**: Efficient video encoding and decoding.

## Installation

To get started with **ImageFilter**, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/boypugante1/imagefilter.git
   cd imagefilter
   ```

2. **Install Dependencies**:
   Ensure you have the MRTech IFF C SDK installed. You can find installation instructions in the SDK documentation.

3. **Build the Project**:
   ```bash
   make
   ```

4. **Run the Application**:
   After building, you can run the application using:
   ```bash
   ./imagefilter
   ```

## Usage

Once you have the application running, you can apply filters to images. The basic command structure is as follows:

```bash
./imagefilter --input <input_image> --output <output_image> --filter <filter_type>
```

### Example

To apply a custom filter to an image, use:

```bash
./imagefilter --input image.jpg --output filtered_image.jpg --filter sepia
```

### REST API

The application also provides a REST API for integration with other systems. You can send a POST request to apply filters programmatically.

```json
POST /apply-filter
{
  "input": "image.jpg",
  "output": "filtered_image.jpg",
  "filter": "grayscale"
}
```

## Contributing

We welcome contributions to **ImageFilter**! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request to the main repository.

Please ensure your code follows the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out:

- **Author**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [your-github-username](https://github.com/your-github-username)

## Releases

You can download the latest release of **ImageFilter** from the [Releases](https://github.com/boypugante1/imagefilter/releases) section. Follow the instructions to execute the downloaded files and start using the application.

![Releases](https://img.shields.io/badge/Latest%20Release-Download%20Now-brightgreen)

## Acknowledgments

We would like to thank the developers and contributors of the MRTech IFF C SDK for their hard work and dedication. Their efforts have made this project possible.

## Conclusion

Thank you for your interest in **ImageFilter**! We hope this project helps you in your image processing endeavors. If you have any questions or suggestions, feel free to reach out. 

Explore the potential of custom image filtering and unlock new possibilities in your applications!

For more information, visit our [Releases](https://github.com/boypugante1/imagefilter/releases) section.