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

- Gets and Installs the latest stable version Android Studio
- Java version 17+


## **Hướng dẫn cài đặt**

- Import project code via **File > New > Import Project** or **Open an existing Android Studio project**
- Select project directory, and click **OK**
- Sync gradle by **File > Sync project with Gradle files**
- Connect your AVD or real device (check connected device by command **`adb devices`**)
- Install via **Run > Run 'app'**

## Cấu trúc thư mục

The project follows the Clean Architecture principles with the following layers:

- **Presentation**: Views (Jetpack compose), navigators and view models.
- **Domain**: Business logic and use cases.
- **Data**: Data sources and repositories.

### Linting

1. **Linting**: [ktlint](https://github.com/pinterest/ktlint)
2. **Detekt**: [detekt](https://github.com/detekt/detekt)

### Packages

1. [Retrofit2](https://github.com/square/retrofit): for API requests
2. [Glide](https://github.com/bumptech/glide): for loading and caching remote images
3. [Coroutines](https://github.com/Kotlin/kotlinx.coroutines): for asynchronous programming
4. [Hilt](https://github.com/google/dagger): for dependency injection
5. ...

## **Hướng dẫn tạo pull request**

Để đóng góp, vui lòng làm theo các bước sau:

1.  Tạo một **branch** mới cho tính năng của bạn (`git checkout -b feature/ten-tinh-nang`).
2.  **Commit** các thay đổi của bạn (`git commit -m 'feat: Thêm tính năng XYZ'`). Vui lòng tuân thủ theo [Conventional Commits](https://www.conventionalcommits.org/).
3.  **Push** lên branch của bạn (`git push origin feature/ten-tinh-nang`).
4.  Tạo một **Pull Request** mới.
