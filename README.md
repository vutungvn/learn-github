Conventional Commits Guide

1. Cấu trúc chuẩn
   <type>(<scope>): <description>

- type: loại thay đổi (bắt buộc)
- scope: phần bị ảnh hưởng (tuỳ chọn)
- description: mô tả ngắn gọn hành động

2. Các loại type phổ biến
   Type Ý nghĩa
   feat Thêm tính năng mới
   fix Sửa lỗi
   docs Cập nhật tài liệu
   style Format code, không đổi logic
   refactor Viết lại code, không đổi chức năng
   perf Tối ưu hiệu năng
   test Thêm hoặc sửa test
   build Thay đổi build system
   ci Thay đổi cấu hình CI
   chore Công việc khác

3. Ví dụ

feat(auth): add login with Google

fix(cart): correct total price calculation

docs: update installation guide

refactor(user): simplify validation logic

test(auth): add unit test for login

4. Quy tắc viết commit

- Viết bằng tiếng Anh rõ ràng

- Description viết thường

- Không dấu chấm cuối câu

- Ngắn gọn (khoảng 50–72 ký tự)
