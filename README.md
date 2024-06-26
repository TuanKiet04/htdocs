# E-commerce website

## Giới thiệu

Dự án E-commerce của chúng em cung cấp một nền tảng thương mại điện tử nhằm cung cấp các sản phẩm thời trang hiện đại, năng động dành cho thanh thiếu niên và người trẻ tuổi. Trang web giúp người dùng dễ dàng tìm kiếm, mua sắm và cập nhật những xu hướng thời trang mới nhất.

## Tính năng chính

- **Danh mục sản phẩm đa dạng**: Quần áo, phụ kiện thời trang, giày dép, v.v.
- **Thiết kế giao diện thân thiện**: Giao diện trực quan, dễ sử dụng.
- **Cập nhật xu hướng thời trang**: Thường xuyên cập nhật các bộ sưu tập mới nhất.
- **Dịch vụ khách hàng**: Tư vấn trực tuyến, chính sách đổi trả linh hoạt.

## Công nghệ sử dụng

- **Front-end**: PHP, CSS, JavaScript, Bootstrap
- **Back-end**: PHP, MySQL
- **Server**: Apache (sử dụng XAMPP)

## Yêu cầu hệ thống

- **Web Server**: Apache
- **Database**: MySQL
- **PHP**: Phiên bản 7.0 hoặc cao hơn
- **XAMPP**: Phiên bản mới nhất

## Hướng dẫn cài đặt

### Bước 1: Clone repository

```bash
git clone https://github.com/yourusername/TH_PTHTTTNT.git
cd TH_PTHTTTNT
```

### Bước 2: Cài đặt XAMPP

1. Tải và cài đặt XAMPP từ [trang web chính thức](https://www.apachefriends.org/index.html).
2. Khởi động Apache và MySQL từ bảng điều khiển XAMPP.

### Bước 3: Cấu hình cơ sở dữ liệu

1. Truy cập phpMyAdmin tại `http://localhost/phpmyadmin`.
2. Tạo một cơ sở dữ liệu mới với tên `shop_quanao`.
3. Import file `shop_quanao.sql` từ thư mục dự án vào cơ sở dữ liệu vừa tạo.

### Bước 4: Cấu hình dự án

1. Sao chép tất cả các file của dự án vào thư mục `htdocs` của XAMPP (ví dụ: `C:\xampp\htdocs\your-repo-name`).
2. Mở file `config.php` và cập nhật thông tin kết nối cơ sở dữ liệu nếu cần thiết.

### Bước 5: Chạy dự án

1. Mở trình duyệt và truy cập `http://localhost/TH_PTHTTTNT`.
2. Trang web của mọi người sẽ được hiển thị và bạn có thể bắt đầu duyệt các sản phẩm thời trang.

## Sử dụng

- **Đăng ký và đăng nhập**: Người dùng có thể tạo tài khoản và đăng nhập để mua sắm.
- **Thêm sản phẩm vào giỏ hàng**: Người dùng có thể thêm các sản phẩm vào giỏ hàng.
- **Thanh toán**: Tiến hành thanh toán đơn hàng.
- **Quản lý đơn hàng**: Người dùng có thể xem và quản lý các đơn hàng đã đặt.

## Đóng góp

Chúng em luôn hoan nghênh các đóng góp từ cộng đồng. Để đóng góp cho dự án, hãy làm theo các bước sau:

1. Fork repository này.
2. Tạo một nhánh mới (`git checkout -b feature/your-feature`).
3. Commit các thay đổi của bạn (`git commit -m 'Thêm tính năng X'`).
4. Push lên nhánh (`git push origin feature/your-feature`).
5. Tạo một pull request.

## License

Dự án này được cấp phép theo giấy phép MIT - xem tệp [LICENSE](LICENSE) để biết thêm chi tiết.

Cảm ơn thầy đã quan tâm đến dự án của chúng em!
