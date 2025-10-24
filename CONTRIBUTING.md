# Hướng dẫn đóng góp

Cảm ơn bạn đã quan tâm đến việc đóng góp cho kho tài liệu KHTN-THCS! Đóng góp của bạn sẽ giúp cộng đồng giáo viên có thêm nhiều tài liệu chất lượng.

## Cách thức đóng góp

### 1. Đối với người mới bắt đầu với GitHub

#### Bước 1: Tạo tài khoản GitHub
- Truy cập [github.com](https://github.com) và đăng ký tài khoản miễn phí

#### Bước 2: Fork repository
- Nhấn nút "Fork" ở góc trên bên phải của trang repository
- Repository sẽ được sao chép vào tài khoản của bạn

#### Bước 3: Thêm tài liệu
- Vào repository đã fork trong tài khoản của bạn
- Điều hướng đến thư mục phù hợp
- Nhấn "Add file" > "Upload files"
- Kéo thả hoặc chọn file từ máy tính
- Viết mô tả ngắn gọn về tài liệu
- Nhấn "Commit changes"

#### Bước 4: Tạo Pull Request
- Nhấn nút "Pull Request" 
- Nhấn "New Pull Request"
- Kiểm tra các thay đổi
- Nhấn "Create Pull Request"
- Viết tiêu đề và mô tả chi tiết
- Nhấn "Create Pull Request" để gửi

### 2. Đối với người đã quen với GitHub

```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/KHTN-.git
cd KHTN-

# Tạo branch mới
git checkout -b feature/them-tai-lieu-[mo-ta-ngan]

# Thêm tài liệu vào thư mục phù hợp
# ...

# Commit changes
git add .
git commit -m "Thêm [mô tả tài liệu]"

# Push to GitHub
git push origin feature/them-tai-lieu-[mo-ta-ngan]

# Tạo Pull Request trên GitHub
```

## Quy tắc đóng góp

### 1. Cấu trúc thư mục

Đặt tài liệu vào đúng thư mục theo quy tắc:

```
Khoi-[6/7/8/9]/
  ├── Giang-day/         # Bài giảng, tài liệu học tập
  ├── Kiem-tra/          # Đề kiểm tra, đánh giá
  └── Ke-hoach-bai-day/  # Giáo án, kế hoạch
```

### 2. Quy ước đặt tên file

**Định dạng:**
```
[Khoi]-[Chu-de]-[Loai]-[Ten-tai-lieu].[duoi-mo-rong]
```

**Ví dụ:**
- ✅ `6-Sinh-hoc-Bai-giang-Te-bao-thuc-vat.pptx`
- ✅ `7-Vat-ly-Kiem-tra-Anh-sang.docx`
- ✅ `8-Hoa-hoc-Ke-hoach-Phan-ung-hoa-hoc.pdf`
- ❌ `bài giảng 1.pptx` (không rõ ràng)
- ❌ `dethi.doc` (thiếu thông tin)

**Lưu ý:**
- Không dùng dấu cách, thay bằng dấu gạch ngang `-`
- Không dùng ký tự đặc biệt, dấu tiếng Việt trong tên file
- Viết hoa chữ cái đầu mỗi từ
- Tên file phải ngắn gọn nhưng đầy đủ thông tin

### 3. Định dạng file được chấp nhận

#### Tài liệu văn bản
- `.pdf` - Định dạng ưu tiên cho tài liệu đã hoàn thiện
- `.docx` - Cho tài liệu Word có thể chỉnh sửa
- `.txt` - Cho ghi chú đơn giản

#### Bài giảng
- `.pptx` - PowerPoint
- `.pdf` - Bản export từ PowerPoint

#### Hình ảnh
- `.jpg`, `.jpeg` - Cho ảnh chụp
- `.png` - Cho ảnh có nền trong suốt, sơ đồ
- `.gif` - Cho hình động (nếu cần)

#### Video
- Ưu tiên đăng link YouTube, Google Drive
- File video trực tiếp: chỉ file nhỏ < 50MB
- Định dạng: `.mp4` (ưu tiên)

#### Bảng tính
- `.xlsx` - Excel
- `.csv` - Dữ liệu bảng đơn giản

### 4. Yêu cầu về nội dung

#### Chất lượng
- Nội dung chính xác, khoa học
- Phù hợp với Chương trình Giáo dục Phổ thông 2018
- Không có lỗi chính tả, ngữ pháp nghiêm trọng
- Trình bày rõ ràng, dễ hiểu

#### Bản quyền
- Chỉ đóng góp tài liệu bạn tự tạo hoặc có quyền chia sẻ
- Không vi phạm bản quyền của người khác
- Ghi nguồn nếu tham khảo từ tài liệu khác
- Tôn trọng quyền tác giả

#### Thông tin bổ sung
Trong mô tả Pull Request, vui lòng cung cấp:
- Tên tài liệu
- Khối lớp
- Chủ đề/Bài học
- Loại tài liệu (giảng dạy, kiểm tra, kế hoạch)
- Mô tả ngắn về nội dung
- Nguồn (nếu có)

### 5. Ví dụ về Pull Request tốt

**Tiêu đề:** 
```
Thêm bài giảng Tế bào thực vật - Lớp 6
```

**Mô tả:**
```
## Thông tin tài liệu
- **Khối:** 6
- **Môn:** Sinh học
- **Chủ đề:** Tế bào - đơn vị cơ bản của sự sống
- **Loại:** Bài giảng PowerPoint
- **Nội dung:** 
  - Cấu tạo tế bào thực vật
  - So sánh với tế bào động vật
  - Hình ảnh minh họa
  - Bài tập củng cố

## File đính kèm
- `6-Sinh-hoc-Bai-giang-Te-bao-thuc-vat.pptx`

## Nguồn
Tài liệu tự soạn theo SGK Khoa học Tự nhiên 6 - KNTT
```

## Quy trình review

1. Maintainer sẽ xem xét Pull Request của bạn
2. Có thể yêu cầu chỉnh sửa nếu cần
3. Sau khi được chấp nhận, tài liệu sẽ được merge vào repository
4. Bạn sẽ được ghi nhận là contributor

## Báo cáo vấn đề

Nếu phát hiện vấn đề với tài liệu hiện có:
1. Mở một Issue mới
2. Mô tả rõ vấn đề
3. Đề xuất cách khắc phục (nếu có)

## Hỗ trợ

Nếu cần hỗ trợ:
- Mở Issue với nhãn "question"
- Liên hệ qua email (nếu có)
- Tham khảo [GitHub Guides](https://guides.github.com/)

## Code of Conduct

- Tôn trọng mọi người đóng góp
- Giữ thái độ chuyên nghiệp, lịch sự
- Chấp nhận phản hồi mang tính xây dựng
- Tập trung vào lợi ích của cộng đồng

---

Cảm ơn bạn đã đóng góp vào KHTN-THCS! Mỗi tài liệu của bạn đều giúp ích cho hàng ngàn giáo viên và học sinh. 🙏
