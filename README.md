# LexiIELTS — IELTS Vocabulary Website MVP

## Chạy thử
1. Giải nén thư mục.
2. Mở `index.html` bằng Chrome, Edge hoặc Firefox.
3. Dùng website ngay; không cần cài package hay chạy server cho bản demo.

## Chức năng có sẵn
- Dashboard và thống kê cơ bản.
- Thư viện từ vựng: thêm, sửa, xóa, tìm kiếm, lọc trạng thái.
- Import CSV UTF-8, xem trước dữ liệu, bỏ qua/cập nhật từ trùng.
- Tải template CSV.
- Flashcards: lật thẻ, tự đánh giá, lên lịch ôn tập cơ bản.
- Hoạt động từ vựng Listening, Speaking, Reading, Writing.
- Tra cứu thử qua Free Dictionary API và lưu từ.
- Phát âm bằng Web Speech API của trình duyệt.
- Lưu dữ liệu trong localStorage của trình duyệt.

## Lưu ý quan trọng
Đây là MVP frontend chạy trên trình duyệt, chưa phải hệ thống production:
- Chưa có backend, database server, tài khoản thật, đăng nhập, phân quyền nhiều người dùng hoặc đồng bộ giữa thiết bị.
- Dữ liệu được lưu trên trình duyệt hiện tại. Xóa dữ liệu trình duyệt có thể làm mất dữ liệu.
- Tra cứu demo dùng Free Dictionary API, không phải Oxford. Để tích hợp Oxford chính thức, cần API/giấy phép phù hợp và xử lý khóa API ở backend.
- Hoạt động 4 kỹ năng là bài tập từ vựng nền tảng, không phải bài thi IELTS đầy đủ và không chấm band điểm.
- Thuật toán ôn tập hiện là bản đơn giản để minh họa; cần BA/PO chốt quy tắc trước khi phát hành.

## CSV template
Các cột: `word,meaning,translation,pos,ipa,example,topic,level,notes`
`word` là cột bắt buộc.
