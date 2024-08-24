# NoScript Configuration

This repository contains a NoScript configuration designed to enhance security by managing JavaScript and other potentially harmful content for a wide range of domains.

## Table of Contents

- [Introduction](#introduction)
- [Why I Made It](#why-i-made-it)
- [What is NoScript?](#what-is-noscript)
- [How to Use This Configuration](#how-to-use-this-configuration)
- [Configuration Details](#configuration-details)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This NoScript configuration is tailored to provide an extra layer of security by controlling the execution of JavaScript and other dynamic content on various websites. By using this configuration, you can ensure that only trusted websites are allowed to run potentially harmful scripts.

## Why I Made It

**Staying safe has never been so easy!**

I created this configuration to enhance my personal online security. By following the **principle of least privilege**, this setup ensures that only trusted sites can execute JavaScript and other dynamic content. I use this configuration personally and update it every week to keep it current and effective.

## What is NoScript?

NoScript is a powerful browser extension that enhances security by allowing JavaScript and other potentially harmful content to be executed only by trusted websites of your choice. It is a built-in key security component of the Tor Browser, which is widely used for defending against surveillance and censorship.

### Key Features of NoScript:

- **Selective Script Blocking:** Allows JavaScript and other dynamic content to run only on trusted websites.
- **Anti-XSS Protection:** Provides the most powerful anti-XSS protection available in a browser.
- **Pre-emptive Script Blocking:** Prevents exploitation of security vulnerabilities (known and unknown) without loss of functionality.
- **Ease of Use:** Enables JavaScript for trusted sites with a simple click.

## How to Use This Configuration

1. **Install NoScript:**
   - If you haven't already, install the NoScript extension from the [official website](https://noscript.net/) or your browser's extension store.

2. **Import Configuration:**
   - Download the configuration file from this repository.
   - Open NoScript's options and navigate to the "Import/Export" section.
   - Import the downloaded configuration file.

3. **Apply Configuration:**
   - Once imported, the configuration will automatically apply the specified rules to the domains listed.

## Configuration Details

The configuration file includes rules for a wide range of domains, ensuring that only trusted sites are allowed to execute JavaScript and other dynamic content. The rules are designed to follow the **principle of least privilege**, providing maximum security while maintaining usability.

### Example Configuration:

```json
{
  "domains": {
    "example.com": {
      "scripts": "allow",
      "objects": "allow",
      "media": "allow"
    },
    "untrusted.com": {
      "scripts": "block",
      "objects": "block",
      "media": "block"
    }
  }
}
```

## Contributing

Contributions are welcome! If you have suggestions for improving the configuration or adding new domains, please open an issue or submit a pull request.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your branch to your fork.
5. Open a pull request against the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Stay safe and secure with NoScript!
