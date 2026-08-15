# Gói khởi đầu — Hồ sơ nhập ngành COS673

Giải nén là chạy. Không cần cài gì lên máy.

## Năm bước, làm một lần duy nhất ở Bài 1

**1. Tạo tài khoản GitHub.** Vào `github.com`, chọn Sign up.
Chọn tên tài khoản cẩn thận — nó nằm trong địa chỉ web của em suốt bốn năm.
Dùng dạng `hoten-mssv`, tránh biệt danh. Dùng email cá nhân, không dùng email trường.

**2. Tạo kho chứa đúng tên.** Bấm New repository, đặt tên **chính xác** là:

```
<tên-tài-khoản-của-em>.github.io
```

Chọn **Public**, tích **Add a README file**, bấm Create repository.
Tên kho phải trùng từng ký tự với tên tài khoản. Đây là chỗ hay sai nhất,
và khi sai thì trang không hiện mà cũng không báo lỗi gì.

**3. Đưa các tệp trong gói này lên.** Trong kho vừa tạo, bấm
**Add file → Upload files**, kéo thả toàn bộ tệp trong thư mục này vào, rồi Commit.

**4. Bật GitHub Pages.** Settings → Pages → Source chọn **Deploy from a branch**,
Branch chọn `main` và thư mục `/ (root)`, bấm Save. Đợi một tới hai phút.

**5. Sửa ba dòng đầu của `_config.yml`** thành tên và mô tả của em, rồi Commit.

Xong. Trang của em ở `https://<tên-tài-khoản>.github.io`.
**Mở bằng cửa sổ ẩn danh để kiểm** — ở cửa sổ thường em đang đăng nhập GitHub
nên trang vẫn hiện dù chưa xuất bản đúng.

## Tệp nào cho bài nào

| Bài | Tệp | Nội dung |
|---|---|---|
| — | `index.md` | Trang chủ, dẫn sang sáu trang |
| 1 | `career.md` | Chân dung nghề của tôi |
| 2 | `roadmap.md` | Bản đồ học tập bốn năm |
| 3 | `team.md` | Cẩm nang làm việc nhóm |
| 4 | `digital.md` | Dấu chân số của tôi |
| 5 | `ai-audit.md` | Soi một công cụ AI |
| 6 | `reflection.md` + `ai-log.md` | Nhìn lại học kỳ và nhật ký AI |

Mỗi trang đã có sẵn khung. Chỗ nào có dấu `…` là chỗ em điền.
Nhớ **xoá dòng ghi chú màu xám ở đầu mỗi trang** trước khi nộp.

## Ba điều nên biết

**Commit vào nhiều ngày khác nhau.** GitHub ghi lại thời điểm từng lần commit,
và em không sửa được lịch sử đó qua giao diện web. Đó là dấu vết không bịa được,
cho thấy em làm bài trong nhiều buổi thay vì dựng cả hồ sơ trong một đêm.
Cách nhẹ nhàng: commit khi có dàn ý, khi viết xong phần chính, và khi sửa lần cuối.

**Trang này công khai.** Đừng đưa lên số điện thoại, địa chỉ nhà, ảnh căn cước,
hay ảnh chụp có mã xác thực. Bài 4 sẽ nói kỹ vì sao.

**Đừng xoá `_config.yml`.** Nó là thứ biến các tệp `.md` thành một trang web có
giao diện. Xoá đi thì trang vẫn chạy nhưng trông như văn bản thô.
