# Khái niệm cơ bản

## Một số quy tắc cơ bản
- Phần mở rộng (extension) sử dụng `.yaml` hoặc `.yml`, ưu tiên `.yaml`.
- Có phân biệt viết hoa và viết thường (case-sensitive).
- Sử dụng space thay vi tab cho indentation.

## Các kiểu dữ liệu trong YAML

### Dữ liệu kiểu đơn lẻ (Scalar)
- String
- Numbers
- Booleans
- Null

### Dữ liệu kiểu tập hợp (Collections)
- Sequences (Lists)
- Mappings (Dictionaries)

## Nhận xét (Comment)
Ví dụ:

```yaml
# Heading comment: thông tin tổng quát về tập tin: tác giả, phiên bản, thời gian,...
# Author: QuanTM
# Last Modified: 2025-01-01

# Block comment: thông tin về một nhóm dữ liệu
# Scalars
string: Hello, world
number:
  int: 12345
  float: 3.14159 # PI - inline comment
boolean: true

# Collections
# Sequences
fruits:
  - orange
  - apple
  - strawberry

# Mappings
person:
  name: Jerry
  age: 24
  gender: Male

```
