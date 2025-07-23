# **[Tên dự án]**

> [Thêm một câu slogan hoặc mô tả cực ngắn về dự án của bạn ở đây. Ví dụ: Nền tảng quản lý công việc hiệu suất cao dành cho đội nhóm.]

[Thêm các huy hiệu (badges) nếu có, ví dụ: build status, code coverage, license, etc.]

[![Build Status](https://shields.io/travis/com/user/repo.svg)](https://travis-ci.com/user/repo)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Mô tả chi tiết hơn về dự án: mục tiêu, các công nghệ chính sử dụng, và nó giải quyết vấn đề gì.

---

## **Mục lục**

* [Giới thiệu](#tên-dự-án)
* [Mục lục](#mục-lục)
* [Yêu cầu hệ thống](#yêu-cầu-hệ-thống)
* [Hướng dẫn cài đặt](#hướng-dẫn-cài-đặt)
* [Cấu trúc thư mục](#cấu-trúc-thư-mục)
* [Hướng dẫn đóng góp](#hướng-dẫn-tạo-pull-request)

## **Yêu cầu hệ thống**

Để có thể chạy được dự án này, bạn cần đảm bảo đã cài đặt các công cụ sau:

- Xcode 15.0+
- Swift 5.7+
- [Homebrew](https://brew.sh/) installed


## Requirements

- Xcode 15.0+
- Swift 5.7+
- [Homebrew](https://brew.sh/) installed

## **Hướng dẫn cài đặt**

1. **Install Homebrew Dependencies**:

   ```bash
   brew install xcodegen swiftlint swiftformat
   ```

2. **Clone the Repository**:

   ```bash
   git clone https://github.com/{github-username}/project-ios.git
   cd project-ios
   ```

3. **Generate Xcode Project**:

   Use `xcodegen` to generate the Xcode project:

   ```bash
   xcodegen
   ```

4. **Open Xcode**:

   Open the generated Xcode project:

   ```bash
   open project-ios.xcodeproj
   ```

5. **Build and Run**:

   Build and run the project in Xcode.

## Cấu trúc thư mục

The project follows the Clean Architecture principles with the following layers:

- **Presentation**: SwiftUI views, navigators and view models.
- **Domain**: Business logic and use cases.
- **Data**: Data sources and repositories.

### Linting

1. **Linting**: [SwiftLint](https://github.com/realm/SwiftLint)
2. **Formatting**: [SwiftFormat](https://github.com/nicklockwood/SwiftFormat)

### Packages

1. [Alamofire](https://github.com/Alamofire/Alamofire.git): for API requests
2. [Kingfisher](https://github.com/onevcat/Kingfisher.git): for loading and caching remote images
3. [LinkNavigator](https://github.com/interactord/LinkNavigator.git): for navigation management
4. [Factory](https://github.com/hmlongco/Factory.git): for dependency injection

## **Hướng dẫn tạo pull request**

Để đóng góp, vui lòng làm theo các bước sau:

1.  Tạo một **branch** mới cho tính năng của bạn (`git checkout -b feature/ten-tinh-nang`).
2.  **Commit** các thay đổi của bạn (`git commit -m 'feat: Thêm tính năng XYZ'`). Vui lòng tuân thủ theo [Conventional Commits](https://www.conventionalcommits.org/).
3.  **Push** lên branch của bạn (`git push origin feature/ten-tinh-nang`).
4.  Tạo một **Pull Request** mới.
