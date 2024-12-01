# Security Policy for EduPlanner

I take the security of **EduPlanner** and its users' data very seriously. This Security Policy outlines my approach to ensuring the safety and integrity of the project on GitHub. By following these guidelines, I aim to protect both the software and its users from potential vulnerabilities.

## Code Contributions

- **Code Review**: All pull requests must be reviewed by at least one other contributor before merging into the main branch. This ensures the detection of potential security vulnerabilities or bugs.
- **Security Vulnerability Disclosure**: If you discover a security vulnerability in the codebase, please report it immediately through the GitHub issue tracker or contact us directly via email. Do not publicly disclose the vulnerability before it is resolved.

## Authentication & Authorization

- **Access Control**: Only authorized contributors will have write access to the repository. All contributors must use strong, unique passwords for their GitHub accounts.
- **Two-Factor Authentication (2FA)**: We highly recommend enabling Two-Factor Authentication (2FA) for all contributors to GitHub to add an extra layer of protection to the repository.

## Data Protection

- **User Data**: EduPlanner does not collect sensitive personal data. However, any data that is collected (such as timetable or academic data) will be stored securely, using encryption where applicable.
- **Data Access**: Only authorized individuals (e.g., team members and admins) should have access to any stored data. The principle of least privilege will be enforced.

## Dependencies and Third-Party Libraries

- **Third-Party Software**: All third-party dependencies must be reviewed for security risks before being added to the project. We use trusted sources for libraries, such as npm and PyPI.
- **Regular Updates**: Dependencies will be regularly updated to mitigate known vulnerabilities. We also encourage contributors to check for security updates for any dependencies and report them.

## Security Testing

- **Automated Testing**: We use automated security tests where possible to identify vulnerabilities in the code. This includes tools to check for known vulnerabilities in dependencies, code injection, or other common attack vectors.
- **Manual Testing**: Manual testing will be conducted periodically, especially before major releases, to ensure the security of the application.

## Incident Response

- **Security Incident Reporting**: If you notice suspicious activity or a potential security incident related to EduPlanner, please report it immediately to the project maintainers via email or GitHub issues.
- **Incident Resolution**: Upon receiving a security report, the issue will be assessed, and if necessary, a patch or update will be developed and tested. A timeline for resolution will be communicated to affected parties.

## Security Best Practices

- **Sensitive Information**: Never commit sensitive information such as passwords, API keys, or private tokens to the repository. Use environment variables or configuration files that are excluded from version control for storing such information.
- **Encryption**: Where sensitive data is involved, encryption should always be used to ensure confidentiality and integrity.

## Licensing & Compliance

- **Open-Source Compliance**: EduPlanner is an open-source project licensed under the Mozilla Public License 2.0. All contributions must comply with the terms of this license, ensuring that the project remains secure, open, and transparent.

## Continuous Improvement

- **Security Audits**: Regular security audits will be conducted to identify and address potential risks. We encourage the community to submit security improvement suggestions.
- **Feedback**: We welcome feedback from users and contributors to enhance the security of the project.

## Contact Information

For any security concerns or questions regarding this policy, please contact me through the **GitHub issues** page or via email at [contact@kaelian.dev](mailto:contact@kaelian.dev).
By following this Security Policy, we ensure that EduPlanner remains a secure and reliable tool for its users. Thank you for helping us maintain a safe environment for everyone.
