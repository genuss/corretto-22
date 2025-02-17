# Change Log for Amazon Corretto 22

The following sections describe the changes for each release of Amazon Corretto 22.

## Corretto version: 22.0.2.9.1
Release Date: July 16, 2024

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 10 or later, x86_64
+ macos 12.0 and later, x86_64
+ macos 12.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 22.0.2.9.1:

| Issue Name                                                        | Platform | Description                                                                        | Link                                                                   |
|-------------------------------------------------------------------|----------|------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| Import jdk-22.0.2+9                                               | All      | Updates Corretto baseline to OpenJDK 22.0.2+9                                      | [jdk-22.0.2+9](https://github.com/openjdk/jdk22u/releases/tag/jdk-22.0.2+9) |

The following CVEs are addressed in 22.0.2.9.1:

|      CVE       | CVSS |    Component     |
|----------------|------|------------------|
| CVE-2024-21147 |  7.4 | hotspot/compiler |
| CVE-2024-21145 |  4.8 | client-libs/2d   |
| CVE-2024-21140 |  4.8 | hotspot/compiler |
| CVE-2024-21131 |  3.7 | hotspot/runtime  |
| CVE-2024-21138 |  3.7 | hotspot/runtime  |


## Corretto version: 22.0.1.8.1
Release Date: April 16, 2024

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 10 or later, x86_64
+ macos 12.0 and later, x86_64
+ macos 12.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 22.0.1.8.1:

| Issue Name                                                        | Platform | Description                                                                        | Link                                                                   |
|-------------------------------------------------------------------|----------|------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| Import jdk-22.0.1+8                                               | All      | Updates Corretto baseline to OpenJDK 22.0.1+8                                      | [jdk-22.0.1+8](https://github.com/openjdk/jdk22u/releases/tag/jdk-22.0.1+8) |

The following CVEs are addressed in 22.0.1.8.1:

| CVE            | CVSS | Component                      |
|----------------|------|--------------------------------|
| CVE-2024-21011 | 3.7  | hotspot/runtime                |
| CVE-2024-21068 | 3.7  | hotspot/compiler               |
| CVE-2024-21012 | 3.7  | core-libs/java.net             |

## Corretto version: 22.0.0.37.1
Release Date: March 20, 2024

This is a Linux-only bugfix release. For other platforms please use 22.0.0.36.2.

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 22.0.0.37.1:

| Issue Name                                                        | Platform | Description                                                                        | Link                                                                   |
|-------------------------------------------------------------------|----------|------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| Fix zlib linking issue                                                  | Linux      | Fix an issue where some binaries were incorrectly linked against `libz.so` instead of `libz.so.1`                                         |  |

## Corretto version: 22.0.0.36.2
Release Date: March 19, 2024

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 10 or later, x86_64
+ macos 12.0 and later, x86_64
+ macos 12.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 22.0.0.36.2:

| Issue Name                                                        | Platform | Description                                                                        | Link                                                                   |
|-------------------------------------------------------------------|----------|------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| Import jdk-22+36                                                  | All      | Updates Corretto baseline to OpenJDK 22+36                                         | [jdk-22+36](https://github.com/openjdk/jdk22/releases/tag/jdk-22%2B36) |