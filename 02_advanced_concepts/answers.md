1. Lợi ích của anchor và alias: Tránh sự lặp lại và tăng tính nhất quán
2. Khi muốn ghi đè giá trị anchor, ta dùng <<:
    ví dụ:
    ```yaml
    default: &default_user
      name: John Doe
      age: 20
      email: johndoe@gmail.com

    user1:
      *default_user
    
    user2:
      <<: *default_user
      name: Jane Doe
      email: janedoe@gmail.com
    ```

3. Sự khác nhau giữa literal và folded:
    - literal `|`: Giữ nguyên các lần xuống dòng
    - folded `>`: Chuyển các ký tự xuống dòng thành khoảng trắng

4. Block chomping bao gồm:
    - Strip `-`: Loại bỏ tất cả dòng trắng và ký tự xuống dòng ở cuối chuỗi
    - Keep `+`: Giữ lại tất cả dòng trắng và ký tự xuống dòng ở cuối chuỗi
    - Clip: Lựa chọn mặc định. Giữ lại ký tự xuống dòng cuối cùng, nhưng các dòng trắng sẽ bị loại bỏ