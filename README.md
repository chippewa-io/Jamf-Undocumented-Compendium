# Jamf Undocumented Compendium

This repository aims to document the undocumented abilities of all of Jamf's products, including Jamf Pro API, Classic API, Jamf School API, Jamf Protect API, the Jamf Binary, and the Jamf Database. It serves as a comprehensive resource for Jamf administrators and developers who seek detailed insights and examples on leveraging the full potential of these products.

## Table of Contents

- [Introduction](#introduction)
- [Product Documentation](#product-documentation)
  - [Jamf Pro API](#jamf-pro-api)
  - [Classic API](#classic-api)
  - [Jamf School API](#jamf-school-api)
  - [Jamf Protect API](#jamf-protect-api)
- [Jamf Binary](#jamf-binary)
- [Jamf Database](#jamf-database)
- [Tools and Resources](#tools-and-resources)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

The various Jamf products provide extensive functionality for managing Apple devices in different environments. However, not all capabilities are well-documented or easy to find. This repository aims to fill that gap by documenting these lesser-known features, providing practical examples, and offering best practices for using these products.

For the most up-to-date and accurate information, always refer to the official documentation:

- [Jamf Developer Portal](https://developer.jamf.com/jamf-pro)
- [Classic API Reference](https://developer.jamf.com/jamf-pro/reference/classic-api)
- [Jamf Pro API Reference](https://developer.jamf.com/jamf-pro/reference/jamf-pro-api)
- [Jamf School API Reference](https://school.jamfcloud.com/api/docs/)
- [Jamf Protect API Documentation](https://learn.jamf.com/en-US/bundle/jamf-protect-documentation/page/Jamf_Protect_API.html)
- [Jamf Title Editor API Reference](https://developer.jamf.com/title-editor/reference/gettokenclaims-1)
- [Jamf Security API Reference](https://developer.jamf.com/jamf-security/reference/login)

## Product Documentation

### Jamf Pro API

The Jamf Pro API offers modern RESTful endpoints for interacting with Jamf Pro. This section includes documentation on:

- Authentication
- Device Management
- User Management
- Inventory
- Policies
- Configuration Profiles
- Webhooks

### Classic API

The Classic API provides SOAP-based endpoints and some RESTful endpoints for legacy integrations. This section covers:

- Computer Management
- Mobile Device Management
- User Management
- Inventory
- Policies
- Scripts
- Extension Attributes

### Jamf School API

The Jamf School API offers endpoints for managing educational environments. This section includes documentation on:

- User Management
- Device Management
- Class Management
- Inventory

### Jamf Protect API

The Jamf Protect API provides endpoints for managing and monitoring security threats. This section includes documentation on:

- Threat Detection
- Device Management
- Security Policies

## Jamf Binary

This section documents the undocumented features of the Jamf Binary, providing practical examples and best practices.

## Jamf Database

This section covers undocumented aspects related to the Jamf Database, particularly useful for on-premises deployments.

## Tools and Resources

This section compiles useful open-source tools and resources for interacting with the Jamf APIs, such as:

- [Jamf Pro SDK for Python](https://github.com/macadmins/jamf-pro-sdk-python)
- [macOS CPE Resources - Jamf API Recipes](https://github.com/jp-cpe/macOS-cpe-resources/tree/main/jamf%20api%20recipes)

## Contributing

We welcome contributions from the community to enhance and expand this documentation. To contribute:

1. **Fork the repository:**

    Click the "Fork" button at the top right of this page.

2. **Create a new branch:**

    ```sh
    git checkout -b feature/your-feature-name
    ```

3. **Make your changes and commit them:**

    ```sh
    git commit -m "Add detailed explanation for API endpoint XYZ"
    ```

4. **Push your changes to your forked repository:**

    ```sh
    git push origin feature/your-feature-name
    ```

5. **Create a pull request:**

    Open a pull request to the `main` branch of this repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Special thanks to the Jamf community for their continuous support and contributions.
- This project would not be possible without the extensive API work done by Jamf.

---

For any questions or suggestions, feel free to open an issue or contact us directly.
