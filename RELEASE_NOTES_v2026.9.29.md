# AI for Boss 26.9.29

**AI for Boss** là trợ lý AI chạy trên máy tính cá nhân cho chủ doanh nghiệp nhỏ, người kinh doanh một mình và người đi làm ở Việt Nam.

Bản này là kênh tải công khai. File cài đặt được build từ kho nguồn riêng tư `LucDinhLe/ai-for-boss`; kho public này không chứa mã nguồn app.

## Tải xuống

| Hệ điều hành | File | Dung lượng khoảng | Ghi chú |
| --- | --- | ---: | --- |
| Windows 10/11 | `AIforBoss-2026.9.29-win-x64.exe` | 346 MB | Khuyến nghị cho đa số người dùng Windows. |
| macOS Apple Silicon | `AIforBoss-2026.9.29-mac-arm64.dmg` | 387 MB | Dành cho Mac M1/M2/M3/M4. |
| Linux Debian/Ubuntu | `AIforBoss-2026.9.29-linux-amd64.deb` | 321 MB | Cài bằng gói `.deb`. |
| Linux khác | `AIforBoss-2026.9.29-linux-x86_64.AppImage` | 400 MB | Chạy dạng AppImage. |
| Kiểm tra file | `SHA256SUMS.txt` | nhỏ | Dùng để kiểm hash file tải. |

## Tiện ích chính

| Nhu cầu | AI for Boss giúp gì |
| --- | --- |
| Viết và chỉnh nội dung | Soạn bài, email, tin nhắn, phản hồi khách, bản nháp marketing. |
| Làm việc với tài liệu | Đọc, tóm tắt, rút việc cần làm, chuyển tài liệu dài thành đầu việc rõ ràng. |
| Báo cáo và điều hành | Gom số liệu, viết báo cáo tiến độ, báo cáo tuần, rà rủi ro, đề xuất bước tiếp. |
| Bán hàng và chăm sóc khách | Soạn câu trả lời, xử lý từ chối, nhắc công nợ, xếp hạng khách tiềm năng. |
| Tự động hóa việc lặp lại | Đóng gói quy trình thành kỹ năng và chạy lại khi cần. |
| Làm việc nhiều bước | Có thể dùng công cụ, sửa file, kiểm tra kết quả, không chỉ trả lời một đoạn chat. |

## Sơ đồ cách AI for Boss làm việc

```mermaid
flowchart LR
    A[Anh chị giao việc] --> B[AI for Boss hiểu mục tiêu]
    B --> C[Chọn kỹ năng hoặc công cụ]
    C --> D[Đọc dữ liệu được phép]
    D --> E[Tạo kết quả: nội dung, báo cáo, tệp, bản nháp]
    E --> F{Có rủi ro?}
    F -- Không --> G[Báo kết quả]
    F -- Có --> H[Hỏi anh chị duyệt trước]
    H --> G
```

## Điểm mạnh

- **Tiếng Việt và bối cảnh Việt Nam:** hướng tới chủ doanh nghiệp nhỏ, người kinh doanh một mình và người đi làm ở Việt Nam.
- **Không chỉ chat:** có thể xử lý tệp, dùng công cụ, chạy quy trình nhiều bước và kiểm tra lại kết quả.
- **Có nguyên tắc an toàn:** không tự ý gửi ra ngoài, xóa dữ liệu, tiêu tiền hoặc làm việc khó hoàn tác nếu chưa được duyệt.
- **Có thể mở rộng:** thêm kỹ năng, kết nối công cụ và quy trình riêng cho từng mô hình kinh doanh.
- **Chạy trên máy cá nhân:** phù hợp với cách làm việc có tệp, trình duyệt, tài khoản và dữ liệu cục bộ.

## Lưu ý khi cài đặt

### Windows

- Bộ cài hiện chưa ký số, nên Windows SmartScreen có thể hiện cảnh báo.
- Nếu tải đúng từ release chính thức này, chọn **More info** → **Run anyway** để cài.
- Nên thoát app cũ trước khi cài đè.

### macOS

- Bản hiện tại dành cho Mac Apple Silicon.
- macOS có thể báo không xác minh nhà phát triển vì app chưa notarize/ký qua Apple Developer.
- Nếu tin nguồn tải, mở bằng chuột phải → **Open**.

### Linux

- Dùng `.deb` cho Debian/Ubuntu.
- Dùng `.AppImage` nếu muốn chạy trực tiếp trên bản phân phối khác.

## Kiểm tra file tải

Release có `SHA256SUMS.txt`. Nếu hash không khớp, không cài file đó; hãy xóa và tải lại từ release chính thức.

## Nguồn build

```text
Nguồn build: kho private LucDinhLe/ai-for-boss
Private source commit: bc136e1feb9f1f5c0a2c4a8e91e90caee85becdd
Build run: 36656857632
```

## Giấy phép

- Mã nền Hermes giữ giấy phép MIT.
- Phần AI for Boss do Lê Đình Lực viết, đóng gói và định vị theo giấy phép riêng / PolyForm Perimeter 1.0.0.
- Kho này chỉ chứa file tải và mô tả phát hành, không chứa mã nguồn đầy đủ của sản phẩm.
