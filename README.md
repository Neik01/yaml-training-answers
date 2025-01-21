# Introduction

## YAML là gì?
- YAML viết tắt của "YAML Ain't Markup Language".
- YAML được thiết kế dành cho con người giúp việc đọc và viết dễ dàng.

## Tính năng chính:
- Cú pháp đơn giản, dễ đọc.
- Hỗ trợ cấu trúc dữ liệu lồng nhau.
- Có thể mở rộng với các loại dữ liệu tùy chỉnh.
- Độc lập với ngôn ngữ lập trình và thường được sử dụng với các ngôn ngữ như Python, Java, etc.

## Ứng dụng phổ biến:
- Tệp cấu hình cho các ứng dụng (Docker Compose, Kubernetes, Ansible, etc.)
- CI/CD pipelines (Gitlab CI, Github Actions,etc.)
- Trao đổi dữ liêu giữa các hệ thống.

## So sánh giữa XML, JSON và YAML

| **Thuộc tính**         | **XML**                                                        | **JSON**                                                        | **YAML**                                                        |
|-------------------------|---------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|
| **Dễ đọc cho con người**| Khó đọc hơn                                                   | Khó đọc hơn                                                     | Dễ đọc và dễ hiểu hơn                                           |
| **Cú pháp**             | Dài dòng hơn (verbose)                                        | Cú pháp rõ ràng, yêu cầu nghiêm ngặt                            | Cú pháp tối giản                                                |
| **Nhận xét (Comments)** | Hỗ trợ nhận xét                                              | Không hỗ trợ nhận xét                                           | Hỗ trợ nhận xét                                                |
| **Phân cấp (Hierarchy)**| Phân cấp được biểu diễn bằng các thẻ mở và thẻ đóng           | Phân cấp được biểu diễn bằng dấu ngoặc nhọn `{}` và ngoặc vuông `[]` | Phân cấp được biểu diễn bằng thụt lề (indentation)        |
| **Lưu trữ (Storage)**   | Tốn nhiều dung lượng lưu trữ và băng thông mạng               | Nhẹ hơn so với XML                                              | Nhẹ hơn so với cả XML và JSON                                  |
| **Trường hợp sử dụng**  | Tốt nhất cho các dự án phức tạp yêu cầu kiểm soát chặt chẽ về schema | Ưu tiên trong phát triển web và truyền dữ liệu qua HTTP         | Tốt nhất cho các tệp cấu hình, bên cạnh các tính năng của JSON |
