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
- Xcode 15.0+
- Java version 17+
- Flutter 3.19.6


## **Hướng dẫn cài đặt**

1. **Add PATH**:

1.1 Adding this to your shell's config file (.zshrc, zprofile, .bashrc, .bash_profile, etc.)
```
export PATH="$PATH":"$HOME/.pub-cache/bin"
```

1.2 Restart the terminal.

2. **Install FVM**
```
dart pub global activate fvm
fvm flutter pub get
fvm dart run build_runner build --delete-conflicting-outputs
```

ref: https://fvm.app/documentation/getting-started/installation

## Cấu trúc thư mục

The project follows the Clean Architecture principles with the following layers:

- **Presentation**: Views, navigators and view models.
- **Domain**: Business logic and use cases.
- **Data**: Data sources and repositories.

### Packages

1. [retrofit](https://github.com/trevorwang/retrofit.dart/): for API requests
2. [cached_network_image](https://github.com/Baseflow/flutter_cached_network_image): for loading and caching remote images
3. [injectable](https://github.com/Milad-Akarie/injectable): for dependency injection
4. ...

## **Hướng dẫn tạo pull request**

Để đóng góp, vui lòng làm theo các bước sau:

1.  Tạo một **branch** mới cho tính năng của bạn (`git checkout -b feature/ten-tinh-nang`).
2.  **Commit** các thay đổi của bạn (`git commit -m 'feat: Thêm tính năng XYZ'`). Vui lòng tuân thủ theo [Conventional Commits](https://www.conventionalcommits.org/).
3.  **Push** lên branch của bạn (`git push origin feature/ten-tinh-nang`).
4.  Tạo một **Pull Request** mới.
