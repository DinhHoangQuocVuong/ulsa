# Shopping Cart Application

## Giới thiệu

Shopping Cart Application là một ứng dụng thương mại điện tử được xây dựng bằng Spring Boot, cho phép người dùng duyệt sản phẩm, thêm chúng vào giỏ hàng và thực hiện đăng ký người dùng. Ứng dụng hỗ trợ quản lý danh mục và sản phẩm cho người quản trị.

## Tính năng

- Đăng ký và đăng nhập người dùng
- Duyệt và tìm kiếm sản phẩm theo danh mục
- Quản lý danh mục và sản phẩm (CRUD - Create, Read, Update, Delete)
- Hệ thống nhắn tin cho người dùng về trạng thái hoạt động (thành công, lỗi)
- Hỗ trợ tải lên hình ảnh cho danh mục và sản phẩm

## Công nghệ sử dụng

- **Backend:**
  - [Spring Boot](https://spring.io/projects/spring-boot): Nền tảng xây dựng ứng dụng
  - [Spring Data JPA](https://spring.io/projects/spring-data-jpa): Quản lý cơ sở dữ liệu
  - [MySQL](https://www.mysql.com/): Cơ sở dữ liệu
  - [Thymeleaf](https://www.thymeleaf.org/): Công cụ template cho frontend

- **Frontend:**
  - [Bootstrap](https://getbootstrap.com/): CSS Framework để tạo giao diện người dùng

## Cài đặt

### Prerequisites

- Java 17
- Maven
- MySQL

### Bước cài đặt

1. **Clone repo:**

   ```bash
   git clone https://github.com/username/repo.git
   cd repo
2.Cấu hình MySQL:

Tạo cơ sở dữ liệu ecommerce_db.
Cập nhật thông tin kết nối trong file application.properties:
properties

Copy
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=password
3.Chạy ứng dụng:

bash

Copy
mvn spring-boot:run
4.Truy cập ứng dụng:

Mở trình duyệt và điều hướng đến: http://localhost:8080
