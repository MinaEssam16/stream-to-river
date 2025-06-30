# 🌊 Stream to River: An English Learning Journey

![Stream to River](https://img.shields.io/badge/Release-v1.0-blue.svg) [![GitHub](https://img.shields.io/badge/Visit%20Releases%20-%20%F0%9F%93%8E%20https://github.com/MinaEssam16/stream-to-river/releases-green.svg)](https://github.com/MinaEssam16/stream-to-river/releases)

## Overview

English | [中文](README_CN.md)

[Streams to River](https://sstr.trae.com.cn/) is an innovative English learning application designed to help users record, extract, and manage English words, sentences, and relevant contexts encountered in daily life. This tool integrates the principles of the [Ebbinghaus Forgetting Curve](https://en.wikipedia.org/wiki/Forgetting_curve) to facilitate periodic learning and effective memorization.

During the development phase, we extensively utilized [TRAE](https://www.trae.ai) for code development, debugging, annotation, and writing unit tests. We also integrated features like image-to-text, real-time chat, speech recognition, and word highlighting through the [Coze workflow](https://www.coze.com/).

## Project Introduction

### 1.1 Project Background

Streams to River V2 is a word learning and language processing microservice system built on the [Hertz](https://github.com/cloudwego/hertz) and [Kitex](https://github.com/cloudwego/kitex) frameworks. This system offers a comprehensive solution for API services, focusing on the needs of English learners.

### 1.2 Features

- **Word Management**: Users can easily manage vocabulary lists, adding new words and phrases as they encounter them.
- **Contextual Learning**: Capture and store sentences that provide context for new vocabulary, enhancing understanding and retention.
- **Periodic Review**: The app employs spaced repetition techniques based on the Ebbinghaus Forgetting Curve to optimize learning.
- **Integration with Other Tools**: The application can work seamlessly with other educational tools and platforms.

## Getting Started

### 2.1 Prerequisites

Before you begin, ensure you have the following:

- A stable internet connection.
- A device capable of running web applications (desktop or mobile).
- Basic understanding of English language learning principles.

### 2.2 Installation

To get started with Stream to River, visit our [Releases](https://github.com/MinaEssam16/stream-to-river/releases) section. Download the latest version of the application. Follow the installation instructions provided in the release notes.

### 2.3 Usage

1. **Sign Up**: Create an account to access all features.
2. **Add Vocabulary**: Start adding words and sentences you encounter.
3. **Set Review Reminders**: Use the spaced repetition feature to set reminders for review.
4. **Track Progress**: Monitor your learning journey through the dashboard.

## Architecture

### 3.1 System Design

The architecture of Streams to River is modular, allowing for easy updates and feature enhancements. The key components include:

- **API Layer**: Built on Hertz, this layer handles requests and responses efficiently.
- **Service Layer**: Implements business logic and manages data flow.
- **Data Storage**: Utilizes a robust database for storing user data, vocabulary lists, and learning statistics.

### 3.2 Microservices

The system is designed using microservices, enabling scalability and flexibility. Each service focuses on a specific function, such as:

- **User Management**: Handles user accounts and authentication.
- **Vocabulary Service**: Manages vocabulary data and retrieval.
- **Review Scheduler**: Manages spaced repetition schedules.

## Technologies Used

- **Hertz**: For building high-performance APIs.
- **Kitex**: For microservices management.
- **TRAE**: For development and debugging.
- **Coze Workflow**: For integrating advanced features.

## Contributing

We welcome contributions to enhance the Stream to River application. If you wish to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch and submit a pull request.

### 5.1 Code of Conduct

We expect all contributors to adhere to our code of conduct, promoting a positive and inclusive environment.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please open an issue in the GitHub repository or contact us through our website.

## Future Work

We plan to introduce more features based on user feedback, including:

- Enhanced analytics for tracking learning progress.
- Additional integrations with popular language learning platforms.
- Community features for sharing vocabulary and learning tips.

## Conclusion

Stream to River aims to transform the way people learn English by making it more interactive and personalized. We believe that with the right tools, anyone can master a new language. Visit our [Releases](https://github.com/MinaEssam16/stream-to-river/releases) section to download the latest version and start your journey today!