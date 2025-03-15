# 📧 Email Validator in PHP

Welcome to the **Email Validator in PHP** project! This repository contains a simple yet effective email validation script written in PHP. The script checks the email format according to RFC standards and verifies the DNS records of the domain.

## ✨ Features

- ✅ **RFC 5321 Compliant**: Validates email format according to RFC standards.
- 🌐 **DNS Verification**: Ensures the domain has valid MX or A records.
- ⚡ **Lightweight**: No external dependencies or APIs required.
- 📜 **Easy to Use**: Simple and straightforward implementation.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- 🐘 PHP 7.0 or higher

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/email-validator-php.git
   ```

2. Navigate to the project directory:

   ```sh
   cd email-validator-php
   ```

3. Run the script:

   ```sh
   php email_validator.php
   ```

## 🛠 Usage

To use the email validator, simply call the `isValidEmail` function with the email address you want to validate. Here's an example:

```php
<?php

require 'email_validator.php';

$email = "example@example.com";
if (isValidEmail($email)) {
    echo "The email address '$email' is valid.";
} else {
    echo "The email address '$email' is invalid.";
}
?>
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter) - your_email@example.com

Project Link: [https://github.com/yourusername/email-validator-php](https://github.com/yourusername/email-validator-php)

## 🙏 Acknowledgements

- [PHP Documentation](https://www.php.net/docs.php)
- [RFC 5321](https://tools.ietf.org/html/rfc5321)
- [DNS Records](https://en.wikipedia.org/wiki/List_of_DNS_record_types)

## 📷 Screenshots

![Email Validator](https://via.placeholder.com/800x400)

## 📚 Additional Resources

- [Understanding RFC 5321](https://www.example.com/rfc-5321)
- [DNS Record Types Explained](https://www.example.com/dns-records)

## ⭐️ Star the repo

If you find this project useful, please consider giving it a ⭐️ on GitHub!
