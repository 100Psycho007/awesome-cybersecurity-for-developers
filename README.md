# Awesome Cybersecurity for Developers 🔒

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/100Psycho007/awesome-cybersecurity-for-developers?style=social)](https://github.com/100Psycho007/awesome-cybersecurity-for-developers)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-October%202025-brightgreen)](https://github.com/100Psycho007/awesome-cybersecurity-for-developers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated collection of cybersecurity resources, tools, and best practices specifically designed for developers. From secure coding to DevSecOps, this list helps developers build security into every stage of the development lifecycle.

## 🎯 Why This List?

Security isn't just the responsibility of security teams—it's everyone's job, especially developers who write the code that powers our digital world. This list focuses on practical, developer-friendly security tools and resources that integrate seamlessly into modern development workflows.

## 📋 Table of Contents

- [🛠️ Static Application Security Testing (SAST)](#️-static-application-security-testing-sast)
- [📦 Software Composition Analysis (SCA)](#-software-composition-analysis-sca)
- [🔐 Secrets Detection](#-secrets-detection)
- [🐳 Container Security](#-container-security)
- [🌐 API Security](#-api-security)
- [🔧 IDE Plugins & Extensions](#-ide-plugins--extensions)
- [📚 Learning Resources](#-learning-resources)
- [🏆 OWASP Top 10 Guide](#-owasp-top-10-guide)
- [💻 Secure Coding by Language](#-secure-coding-by-language)
- [🚀 DevSecOps Tools](#-devsecops-tools)
- [📖 Books & Courses](#-books--courses)
- [🎥 YouTube Channels](#-youtube-channels)
- [📰 Blogs & Newsletters](#-blogs--newsletters)
- [🏅 Certifications](#-certifications)
- [🤝 Contributing](#-contributing)

---## 🛠️ S
tatic Application Security Testing (SAST)

> Tools that analyze source code for security vulnerabilities without executing the program.

### Open Source SAST Tools

#### [Semgrep](https://semgrep.dev/) ![GitHub stars](https://img.shields.io/github/stars/semgrep/semgrep?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Fast, open-source static analysis engine that finds bugs, detects vulnerabilities, and enforces code standards.

**Key Features:**
- Supports 30+ languages including Python, JavaScript, Go, Java, C#
- Custom rule creation with simple pattern syntax
- CI/CD integration with GitHub Actions, GitLab CI, Jenkins
- Low false positive rate with contextual analysis

**Languages Supported:** Python, JavaScript, TypeScript, Go, Java, C#, PHP, Ruby, Scala, and more  
**License:** LGPL 2.1  
**Free Tier:** Yes (Community rules)  
**Last Verified:** 2025-10

#### [Bandit](https://github.com/PyCQA/bandit) ![GitHub stars](https://img.shields.io/github/stars/PyCQA/bandit?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Security linter for Python code that identifies common security issues.

**Key Features:**
- Detects hardcoded passwords, SQL injection risks, unsafe functions
- Configurable severity levels and exclusion rules
- JSON, XML, CSV, and HTML output formats
- Pre-commit hook integration

**Languages Supported:** Python  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [Brakeman](https://github.com/presidentbeef/brakeman) ![GitHub stars](https://img.shields.io/github/stars/presidentbeef/brakeman?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Static analysis security scanner specifically designed for Ruby on Rails applications.

**Key Features:**
- Detects SQL injection, XSS, command injection, and more
- Scans models, views, controllers, and configuration files
- Fast scanning with minimal setup required
- Detailed security reports with remediation advice

**Languages Supported:** Ruby (Rails)  
**License:** MIT  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [MobSF (Mobile Security Framework)](https://github.com/MobSF/Mobile-Security-Framework-MobSF) ![GitHub stars](https://img.shields.io/github/stars/MobSF/Mobile-Security-Framework-MobSF?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Comprehensive mobile application security testing framework for iOS and Android.

**Key Features:**
- Static and dynamic analysis capabilities
- Supports APK, IPA, and source code analysis
- Web-based interface with detailed reports
- Malware analysis and API testing

**Languages Supported:** Java, Kotlin, Swift, Objective-C  
**License:** GPL 3.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

### Commercial SAST Tools

#### [SonarQube](https://www.sonarqube.org/) ![Commercial](https://img.shields.io/badge/Commercial-orange)

Leading platform for continuous code quality and security analysis.

**Key Features:**
- 30+ language support with deep analysis
- Quality gates and security hotspots
- IDE integration and pull request decoration
- Comprehensive security rules based on OWASP, CWE, SANS

**Languages Supported:** Java, C#, JavaScript, Python, PHP, Go, and more  
**License:** Commercial (Community edition available)  
**Free Tier:** Community edition  
**Last Verified:** 2025-10

---## 
📦 Software Composition Analysis (SCA)

> Tools that identify vulnerabilities in third-party dependencies and open-source components.

### Open Source SCA Tools

#### [OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck) ![GitHub stars](https://img.shields.io/github/stars/jeremylong/DependencyCheck?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

The gold standard for open-source dependency vulnerability scanning.

**Key Features:**
- Supports Java, .NET, JavaScript, Python, Ruby, PHP, and more
- Integrates with Maven, Gradle, Ant, SBT, and CI/CD pipelines
- Uses National Vulnerability Database (NVD) and other sources
- Detailed HTML and XML reports

**Languages Supported:** Java, .NET, JavaScript, Python, Ruby, PHP, C/C++  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [Trivy](https://github.com/aquasecurity/trivy) ![GitHub stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Comprehensive vulnerability scanner for containers, filesystems, and Git repositories.

**Key Features:**
- Fast and accurate vulnerability detection
- Supports container images, filesystems, and Git repos
- Multiple output formats (JSON, table, SARIF)
- Easy CI/CD integration

**Languages Supported:** Multiple (via package managers)  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [OSV-Scanner](https://github.com/google/osv-scanner) ![GitHub stars](https://img.shields.io/github/stars/google/osv-scanner?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Google's vulnerability scanner that uses the OSV database.

**Key Features:**
- Scans lockfiles and SBOMs for vulnerabilities
- Uses comprehensive OSV.dev database
- Fast and lightweight CLI tool
- Supports multiple package ecosystems

**Languages Supported:** Multiple (via package managers)  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

### Commercial SCA Tools

#### [Snyk Open Source](https://snyk.io/) ![Commercial](https://img.shields.io/badge/Commercial-orange)

Developer-first security platform with excellent SCA capabilities.

**Key Features:**
- Real-time vulnerability monitoring
- Automated fix pull requests
- License compliance checking
- IDE and CI/CD integrations

**Languages Supported:** JavaScript, Python, Java, .NET, Go, PHP, Ruby, Scala  
**License:** Commercial  
**Free Tier:** Limited (500 tests/month)  
**Last Verified:** 2025-10

---## 🔐 Secre
ts Detection

> Tools that scan code, commits, and configurations for exposed secrets like API keys, passwords, and tokens.

### Open Source Secrets Detection

#### [TruffleHog](https://github.com/trufflesecurity/trufflehog) ![GitHub stars](https://img.shields.io/github/stars/trufflesecurity/trufflehog?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

High-entropy string and secrets scanner with verification capabilities.

**Key Features:**
- Scans Git repositories, filesystems, and cloud storage
- High-entropy detection and pattern matching
- Verification of found secrets against live services
- Supports 700+ secret types

**Supported Sources:** Git, GitHub, GitLab, S3, GCS, filesystems  
**License:** AGPL 3.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [GitLeaks](https://github.com/gitleaks/gitleaks) ![GitHub stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Fast and lightweight secrets detection tool written in Go.

**Key Features:**
- SAST tool for detecting hardcoded secrets
- Customizable rules and allowlists
- Pre-commit hooks and CI/CD integration
- SARIF output format support

**Supported Sources:** Git repositories, files, directories  
**License:** MIT  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [detect-secrets](https://github.com/Yelp/detect-secrets) ![GitHub stars](https://img.shields.io/github/stars/Yelp/detect-secrets?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Enterprise-friendly secrets detection tool with baseline approach.

**Key Features:**
- Baseline methodology to track known secrets
- Plugin architecture for custom detection
- Pre-commit hook integration
- Low false positive rate

**Supported Sources:** Files, directories, Git repositories  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

### Commercial Secrets Detection

#### [GitGuardian](https://www.gitguardian.com/) ![Commercial](https://img.shields.io/badge/Commercial-orange)

Comprehensive secrets detection and remediation platform.

**Key Features:**
- Real-time monitoring of Git repositories
- Automated incident response workflows
- Historical Git scanning
- Developer education and training

**Supported Sources:** Git repositories, CI/CD, cloud environments  
**License:** Commercial  
**Free Tier:** Limited (25 developers)  
**Last Verified:** 2025-10

---## 🐳 
Container Security

> Tools for scanning container images, Kubernetes configurations, and container runtime security.

### Open Source Container Security

#### [Trivy](https://github.com/aquasecurity/trivy) ![GitHub stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Comprehensive security scanner for containers and other artifacts.

**Key Features:**
- Vulnerability scanning for OS packages and language dependencies
- Misconfiguration detection for IaC and Kubernetes
- Secret detection in container images
- SBOM generation and compliance reporting

**Supported Formats:** Docker, OCI, Kubernetes, Terraform, CloudFormation  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [Clair](https://github.com/quay/clair) ![GitHub stars](https://img.shields.io/github/stars/quay/clair?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Static analysis tool for vulnerabilities in application containers.

**Key Features:**
- Layer-by-layer analysis of container images
- API-driven architecture for integration
- Support for multiple Linux distributions
- Webhook notifications for new vulnerabilities

**Supported Formats:** Docker, OCI images  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [Grype](https://github.com/anchore/grype) ![GitHub stars](https://img.shields.io/github/stars/anchore/grype?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Fast vulnerability scanner for container images and filesystems.

**Key Features:**
- Scans container images, directories, and SBOMs
- Multiple output formats (JSON, table, CycloneDX)
- Database updates for latest vulnerability data
- Integration with Syft for SBOM generation

**Supported Formats:** Docker, OCI, directories, archives  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

---

## 🌐 API Security

> Tools for testing and securing REST APIs, GraphQL endpoints, and web services.

### Open Source API Security

#### [OWASP ZAP](https://www.zaproxy.org/) ![GitHub stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

World's most widely used web application security scanner.

**Key Features:**
- Automated and manual security testing
- API scanning and testing capabilities
- Extensive plugin ecosystem
- CI/CD integration and automation support

**Supported Protocols:** HTTP/HTTPS, WebSocket, GraphQL  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [Nuclei](https://github.com/projectdiscovery/nuclei) ![GitHub stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Fast and customizable vulnerability scanner based on simple YAML templates.

**Key Features:**
- 5000+ community-contributed templates
- Fast parallel scanning
- Custom template creation
- Integration with CI/CD pipelines

**Supported Protocols:** HTTP/HTTPS, DNS, TCP, SSL  
**License:** MIT  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

---##
 🔧 IDE Plugins & Extensions

> Security extensions and plugins for popular development environments.

### Visual Studio Code

#### [Snyk Security](https://marketplace.visualstudio.com/items?itemName=snyk-security.snyk-vulnerability-scanner)
![Free](https://img.shields.io/badge/Free-brightgreen)

Real-time vulnerability scanning directly in your IDE.

**Features:**
- Vulnerability scanning for dependencies
- Code security analysis
- License compliance checking
- Fix suggestions and automated remediation

#### [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
![Free](https://img.shields.io/badge/Free-brightgreen)

On-the-fly code quality and security analysis.

**Features:**
- Real-time detection of bugs and security vulnerabilities
- Support for 25+ languages
- Integration with SonarQube and SonarCloud
- Quick fixes and rule explanations

#### [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
![Free](https://img.shields.io/badge/Free-brightgreen)

Git integration with security insights and blame information.

**Features:**
- Git blame and history visualization
- Security-focused commit analysis
- Repository and file history exploration
- Integration with security scanning results

### JetBrains IDEs

#### [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint)
![Free](https://img.shields.io/badge/Free-brightgreen)

Multi-language security and quality analysis for JetBrains IDEs.

**Features:**
- Real-time code analysis
- Security vulnerability detection
- Code smell identification
- Integration with SonarQube projects

#### [Security Code Scan](https://plugins.jetbrains.com/plugin/12156-security-code-scan)
![Free](https://img.shields.io/badge/Free-brightgreen)

.NET security analyzer plugin for JetBrains Rider.

**Features:**
- Static analysis for .NET applications
- OWASP Top 10 vulnerability detection
- Custom rule configuration
- Integration with build processes

---

## 📚 Learning Resources

### Beginner-Friendly Resources

#### [OWASP WebGoat](https://github.com/WebGoat/WebGoat) ![GitHub stars](https://img.shields.io/github/stars/WebGoat/WebGoat?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Beginner](https://img.shields.io/badge/Difficulty-Beginner-green)

Deliberately insecure web application for learning security concepts.

**What You'll Learn:**
- Common web vulnerabilities (OWASP Top 10)
- Secure coding practices
- Penetration testing techniques
- Security testing methodologies

#### [Damn Vulnerable Web Application (DVWA)](https://github.com/digininja/DVWA) ![GitHub stars](https://img.shields.io/github/stars/digininja/DVWA?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Beginner](https://img.shields.io/badge/Difficulty-Beginner-green)

PHP/MySQL web application for learning web security.

**What You'll Learn:**
- SQL injection techniques
- Cross-site scripting (XSS)
- Command injection
- File inclusion vulnerabilities

### Intermediate Resources

#### [PortSwigger Web Security Academy](https://portswigger.net/web-security)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Intermediate](https://img.shields.io/badge/Difficulty-Intermediate-yellow)

Comprehensive web security learning platform with hands-on labs.

**What You'll Learn:**
- Advanced web vulnerabilities
- Burp Suite usage
- Manual testing techniques
- Real-world attack scenarios

#### [OWASP Juice Shop](https://github.com/juice-shop/juice-shop) ![GitHub stars](https://img.shields.io/github/stars/juice-shop/juice-shop?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Intermediate](https://img.shields.io/badge/Difficulty-Intermediate-yellow)

Modern vulnerable web application with progressive difficulty levels.

**What You'll Learn:**
- Modern web vulnerabilities
- Client-side security issues
- API security testing
- Advanced injection techniques

---## 🏆 OW
ASP Top 10 Guide

> Comprehensive guide to the OWASP Top 10 vulnerabilities with prevention strategies for developers.

### A01:2021 – Broken Access Control

**What it is:** Restrictions on what authenticated users are allowed to do are often not properly enforced.

**Prevention for Developers:**
- Implement proper authorization checks at the server side
- Use deny-by-default access control mechanisms
- Validate user permissions for each request
- Log access control failures and alert administrators

**Testing Tools:**
- [Burp Suite](https://portswigger.net/burp) - Manual testing
- [OWASP ZAP](https://www.zaproxy.org/) - Automated scanning

### A02:2021 – Cryptographic Failures

**What it is:** Failures related to cryptography that often lead to sensitive data exposure.

**Prevention for Developers:**
- Use strong, up-to-date cryptographic algorithms
- Implement proper key management
- Encrypt data in transit and at rest
- Use secure random number generators

**Testing Tools:**
- [SSLyze](https://github.com/nabla-c0d3/sslyze) - SSL/TLS configuration analysis
- [Testssl.sh](https://testssl.sh/) - SSL/TLS testing

### A03:2021 – Injection

**What it is:** User-supplied data is not validated, filtered, or sanitized by the application.

**Prevention for Developers:**
- Use parameterized queries and prepared statements
- Validate and sanitize all user inputs
- Use allowlists for input validation
- Escape special characters in outputs

**Testing Tools:**
- [SQLMap](https://sqlmap.org/) - SQL injection testing
- [Commix](https://github.com/commixproject/commix) - Command injection testing

### A04:2021 – Insecure Design

**What it is:** Risks related to design and architectural flaws.

**Prevention for Developers:**
- Implement secure design patterns
- Use threat modeling during design phase
- Follow principle of least privilege
- Implement defense in depth

**Resources:**
- [OWASP Threat Modeling](https://owasp.org/www-community/Threat_Modeling)
- [Microsoft Threat Modeling Tool](https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling)

### A05:2021 – Security Misconfiguration

**What it is:** Missing appropriate security hardening or improperly configured permissions.

**Prevention for Developers:**
- Use secure configuration baselines
- Implement automated security configuration scanning
- Remove unnecessary features and frameworks
- Keep all components up to date

**Testing Tools:**
- [Lynis](https://cisofy.com/lynis/) - Security auditing
- [Docker Bench](https://github.com/docker/docker-bench-security) - Container security

---## 💻 S
ecure Coding by Language

### Python Security

#### Best Practices
- Use `secrets` module for cryptographically secure random numbers
- Avoid `eval()`, `exec()`, and `pickle.loads()` with untrusted input
- Use parameterized queries with SQLAlchemy or similar ORMs
- Validate input with libraries like `cerberus` or `marshmallow`

#### Security Tools
- **[Bandit](https://github.com/PyCQA/bandit)** - Python security linter
- **[Safety](https://github.com/pyupio/safety)** - Dependency vulnerability scanner
- **[Semgrep](https://semgrep.dev/)** - Static analysis with Python rules

#### Secure Libraries
- **[cryptography](https://cryptography.io/)** - Modern cryptographic library
- **[bcrypt](https://github.com/pyca/bcrypt/)** - Password hashing
- **[PyJWT](https://pyjwt.readthedocs.io/)** - JSON Web Token implementation

### JavaScript/Node.js Security

#### Best Practices
- Use `helmet.js` for security headers in Express applications
- Validate input with libraries like `joi` or `yup`
- Use `bcrypt` for password hashing, never plain text
- Implement Content Security Policy (CSP) headers

#### Security Tools
- **[ESLint Security Plugin](https://github.com/eslint-community/eslint-plugin-security)** - Security-focused linting
- **[npm audit](https://docs.npmjs.com/cli/v8/commands/npm-audit)** - Built-in vulnerability scanner
- **[Snyk](https://snyk.io/)** - Dependency and code scanning

#### Secure Libraries
- **[helmet](https://helmetjs.github.io/)** - Security middleware for Express
- **[bcrypt](https://www.npmjs.com/package/bcrypt)** - Password hashing
- **[jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)** - JWT implementation

### Java Security

#### Best Practices
- Use prepared statements to prevent SQL injection
- Validate input with Bean Validation (JSR 303/349/380)
- Implement proper exception handling without information leakage
- Use Spring Security for authentication and authorization

#### Security Tools
- **[SpotBugs](https://spotbugs.github.io/)** with **[Find Security Bugs](https://find-sec-bugs.github.io/)** plugin
- **[OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/)** - Maven/Gradle plugin
- **[SonarQube](https://www.sonarqube.org/)** - Code quality and security

#### Secure Libraries
- **[Spring Security](https://spring.io/projects/spring-security)** - Comprehensive security framework
- **[OWASP Java Encoder](https://owasp.org/www-project-java-encoder/)** - Output encoding
- **[Bouncy Castle](https://www.bouncycastle.org/)** - Cryptographic library

### Go Security

#### Best Practices
- Use `crypto/rand` for secure random number generation
- Validate input and sanitize outputs
- Use context for request timeouts and cancellation
- Implement proper error handling without information disclosure

#### Security Tools
- **[Gosec](https://github.com/securecodewarrior/gosec)** - Go security analyzer
- **[Nancy](https://github.com/sonatypecommunity/nancy)** - Dependency vulnerability scanner
- **[Semgrep](https://semgrep.dev/)** - Static analysis with Go rules

#### Secure Libraries
- **[bcrypt](https://pkg.go.dev/golang.org/x/crypto/bcrypt)** - Password hashing
- **[jwt-go](https://github.com/golang-jwt/jwt)** - JWT implementation
- **[validator](https://github.com/go-playground/validator)** - Input validation

---#
# 🚀 DevSecOps Tools

### CI/CD Security Integration

#### [GitHub Actions Security](https://docs.github.com/en/actions/security-guides)
![Free](https://img.shields.io/badge/Free-brightgreen)

Native security scanning integration for GitHub repositories.

**Features:**
- CodeQL analysis for multiple languages
- Dependency vulnerability scanning
- Secret scanning with partner integrations
- Security policy enforcement

#### [GitLab Security](https://docs.gitlab.com/ee/user/application_security/)
![Commercial](https://img.shields.io/badge/Commercial-orange)

Comprehensive security testing integrated into GitLab CI/CD.

**Features:**
- SAST, DAST, dependency scanning, and container scanning
- Security dashboard and vulnerability management
- License compliance scanning
- Security policy as code

### Infrastructure as Code Security

#### [Checkov](https://github.com/bridgecrewio/checkov) ![GitHub stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Static analysis tool for infrastructure as code.

**Key Features:**
- Supports Terraform, CloudFormation, Kubernetes, Helm, and more
- 1000+ built-in policies for security and compliance
- Custom policy creation with Python or YAML
- CI/CD integration and IDE plugins

**Supported Formats:** Terraform, CloudFormation, Kubernetes, Helm, ARM templates  
**License:** Apache 2.0  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

#### [TFSec](https://github.com/aquasecurity/tfsec) ![GitHub stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=social)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Open Source](https://img.shields.io/badge/Open%20Source-blue)

Security scanner for Terraform code.

**Key Features:**
- Fast static analysis of Terraform code
- Checks for potential security issues
- Custom check creation
- Integration with CI/CD pipelines

**Supported Formats:** Terraform  
**License:** MIT  
**Free Tier:** Yes (Open source)  
**Last Verified:** 2025-10

---

## 📖 Books & Courses

### Essential Security Books

#### [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470)
![Intermediate](https://img.shields.io/badge/Difficulty-Intermediate-yellow)

**Authors:** Dafydd Stuttard, Marcus Pinto  
**Focus:** Web application security testing and exploitation  
**Why Read:** Comprehensive guide to understanding web vulnerabilities from an attacker's perspective

#### [Secure Coding: Principles and Practices](https://www.amazon.com/Secure-Coding-Principles-Practices-Graff/dp/0596002424)
![Intermediate](https://img.shields.io/badge/Difficulty-Intermediate-yellow)

**Authors:** Mark Graff, Kenneth van Wyk  
**Focus:** Writing secure code from the ground up  
**Why Read:** Practical guidance on implementing security throughout the development lifecycle

### Online Courses

#### [Cybrary - Secure Coding](https://www.cybrary.it/course/secure-coding/)
![Free](https://img.shields.io/badge/Free-brightgreen) ![Beginner](https://img.shields.io/badge/Difficulty-Beginner-green)

**Duration:** 8 hours  
**Focus:** Secure coding practices across multiple languages  
**Certificate:** Yes (paid tier)

#### [Coursera - Software Security](https://www.coursera.org/learn/software-security)
![Paid](https://img.shields.io/badge/Paid-orange) ![Intermediate](https://img.shields.io/badge/Difficulty-Intermediate-yellow)

**Provider:** University of Maryland  
**Duration:** 7 weeks  
**Focus:** Software security principles and practices  
**Certificate:** Yes

---

## 🎥 YouTube Channels

### Security-Focused Channels

#### [OWASP](https://www.youtube.com/user/OWASPGLOBAL)
![Free](https://img.shields.io/badge/Free-brightgreen)

**Focus:** Web application security, OWASP projects, security conferences  
**Best For:** Staying updated with OWASP initiatives and web security trends  
**Frequency:** Regular uploads

#### [LiveOverflow](https://www.youtube.com/c/LiveOverflowCTF)
![Free](https://img.shields.io/badge/Free-brightgreen)

**Focus:** Binary exploitation, reverse engineering, CTF walkthroughs  
**Best For:** Understanding low-level security concepts and exploitation techniques  
**Frequency:** Weekly uploads

### Developer-Focused Security

#### [The Cyber Mentor](https://www.youtube.com/c/TheCyberMentor)
![Free](https://img.shields.io/badge/Free-brightgreen)

**Focus:** Ethical hacking, penetration testing, career guidance  
**Best For:** Developers transitioning to security roles  
**Frequency:** Regular uploads

---

## 📰 Blogs & Newsletters

### Essential Security Blogs

#### [Krebs on Security](https://krebsonsecurity.com/)
![Free](https://img.shields.io/badge/Free-brightgreen)

**Focus:** Cybercrime investigations, data breaches, security news  
**Why Follow:** In-depth reporting on major security incidents and trends  
**Frequency:** Multiple posts per week

#### [OWASP Blog](https://owasp.org/blog/)
![Free](https://img.shields.io/badge/Free-brightgreen)

**Focus:** Web application security, OWASP projects, community updates  
**Why Follow:** Latest developments in web application security  
**Frequency:** Regular posts

### Developer Security Newsletters

#### [tl;dr sec](https://tldrsec.com/)
![Free](https://img.shields.io/badge/Free-brightgreen)

**Focus:** Security tools, research, and news for busy professionals  
**Why Subscribe:** Curated security content with practical insights  
**Frequency:** Weekly

---

## 🏅 Certifications

### Developer-Focused Security Certifications

#### [Certified Secure Software Lifecycle Professional (CSSLP)](https://www.isc2.org/Certifications/CSSLP)
![Paid](https://img.shields.io/badge/Paid-orange) ![Intermediate](https://img.shields.io/badge/Difficulty-Intermediate-yellow)

**Provider:** (ISC)²  
**Focus:** Secure software development lifecycle  
**Prerequisites:** 4 years of experience in software development lifecycle  
**Validity:** 3 years (with continuing education)

#### [CompTIA Security+](https://www.comptia.org/certifications/security)
![Paid](https://img.shields.io/badge/Paid-orange) ![Beginner](https://img.shields.io/badge/Difficulty-Beginner-green)

**Provider:** CompTIA  
**Focus:** General cybersecurity fundamentals  
**Prerequisites:** None (recommended 2 years IT experience)  
**Validity:** 3 years (with continuing education)

---

## 🤝 Contributing

We welcome contributions from the community! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to add new resources, report issues, or improve existing content.

### Quick Contribution Checklist

- [ ] Tool is actively maintained (updated within 12 months)
- [ ] Resource is relevant to developers
- [ ] Links are working and accessible
- [ ] Follows formatting guidelines
- [ ] No duplicate entries

### Recognition

Contributors are recognized in our [Contributors](CONTRIBUTORS.md) file and in release notes for significant contributions.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [OWASP](https://owasp.org/) for their invaluable security resources and community
- All the open-source security tool maintainers and contributors
- The cybersecurity community for sharing knowledge and best practices
- Contributors who help keep this list current and comprehensive

---

## 📊 Statistics

![GitHub stars](https://img.shields.io/github/stars/username/awesome-cybersecurity-for-developers?style=social)
![GitHub forks](https://img.shields.io/github/forks/username/awesome-cybersecurity-for-developers?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/username/awesome-cybersecurity-for-developers?style=social)
![GitHub contributors](https://img.shields.io/github/contributors/username/awesome-cybersecurity-for-developers)

**Last Updated:** October 24, 2025  
**Total Resources:** 50+ tools and resources  
**Categories Covered:** 12 major security areas  
**Languages Supported:** 10+ programming languages

---

*Made with ❤️ by the developer security community*