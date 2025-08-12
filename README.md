# transfercloud.io_shell_upload

## Overview

This repository demonstrates a security vulnerability that existed on the leech servers of transfercloud.io in 2017. At the time, their servers did not enforce file extension checks, which allowed for arbitrary file uploads, including shell scripts. By exploiting this oversight, I was able to upload a shell and gain access to all files leeched by users.

## Disclosure and Resolution

Upon discovering the vulnerability, I responsibly reported my findings to transfercloud.io. The issue was subsequently fixed by their team in 2017. As a token of appreciation for the responsible disclosure, I received a 3-month premium coupon.

## Purpose

This repository serves as an educational reference for security researchers and developers, highlighting the importance of validating file uploads to prevent unauthorized access and remote code execution vulnerabilities.

## Usage

*This repository is for educational and demonstration purposes only. Do not use it for malicious activity. Always follow responsible disclosure practices when you discover vulnerabilities.*

## Lessons Learned

- Always validate file uploads on your servers.
- Restrict executable files and enforce strict file extension and MIME type checks.
- Practice responsible disclosure and collaborate with service providers to improve security.

## License

*No license specified. Please contact the repository owner regarding usage permissions.*

## Acknowledgements

Thanks to transfercloud.io for addressing the issue and for their cooperation in resolving the vulnerability.

---

*Original exploit and story by @akzedevops.*
