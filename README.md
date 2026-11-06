# Trà sữa Tẹt Phượng (v32)

Game chạy thẳng trên trình duyệt, tối ưu cho Samsung (Android) và iPhone (kể cả 13 Pro Max).
Tất cả file nằm cùng một cấp, không cần thư mục.

## Danh sách file (tải lên cùng một chỗ, ở gốc repo)
- `index.html` : game
- `manifest.webmanifest` : để cài ra màn hình chính
- `sw.js` : chơi offline
- `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` : biểu tượng

## Đưa lên GitHub Pages
1. Tạo repo mới (Public) trên github.com.
2. Bấm **Add file → Upload files**, kéo thả toàn bộ file trên (không kéo thư mục), rồi **Commit changes**.
3. Vào **Settings → Pages → Build and deployment**: Source chọn **Deploy from a branch**, Branch chọn **main** và thư mục **/(root)**, bấm **Save**.
4. Đợi 1–2 phút, mở link `https://<tên-github>.github.io/<tên-repo>/` trên điện thoại.

## Cài ra màn hình chính
- **Samsung / Android (Chrome hoặc Samsung Internet):** bấm menu ⋮ → **Thêm vào màn hình chính** / **Cài đặt ứng dụng**.
- **iPhone (bắt buộc dùng Safari):** bấm nút **Chia sẻ** → **Thêm vào MH chính**.

## Lưu ý
- Tiến trình lưu trong trình duyệt của từng máy. Trên iPhone, Safari có thể xóa dữ liệu của trang web lâu không dùng, nên hãy cài ra màn hình chính và thỉnh thoảng vào tab **Sao lưu** để xuất file.
- Khi cập nhật game: ghi đè `index.html` và đổi `VERSION` trong `sw.js` (ví dụ `ttp-v32-2`) để điện thoại nhận bản mới.
- Chơi dọc màn hình. Nếu xoay ngang, game sẽ nhắc xoay lại.

## Có gì mới ở v32
- Khách tăng dần theo đội ngũ: chưa thuê ai thì khách dừng ở mức sàn (40 ngày thường, 48 ngày lễ và cuối tuần trong 30 ngày đầu; sau ngày 30 là 50 và 60). Thuê Mai, Linh, Hana và mua máy ép ly tự động thì trần khách mở dần tới 60 (30 ngày đầu) và 120 (sau ngày 30). Số khách còn tăng theo ngày như cũ.
- Thú cưng chạy nhảy, đi qua đi lại và quay đầu ngay trước quầy ở màn hình quán.
- Mọi bé đều tăng tip (khách boa thường hơn và nhiều hơn) và tăng kiên nhẫn cho khách. Tổng tối đa: khách +15%, kiên nhẫn +20%, tip +15%.

## v31
- Khách theo SỐ KHÁCH mỗi ngày (mỗi khách vẫn gọi 1 đến 3 ly): 30 ngày đầu có 40 đến 60 khách/ngày (ngày thường 40 đến 52, cuối tuần và ngày lễ tăng lên tới 60). Sau ngày 30 mở giới hạn, khách nền tăng dần và ngày lễ, cuối tuần có thể lên tối đa 120 khách/ngày. Từ sau ngày 30, số khách còn tăng theo công suất quán (nhân viên, máy ép ly).
- Thêm ngày lễ: ngày 12 (Ngày hội thiếu nhi) và ngày 25 (Ngày nghỉ bù) trong chu kỳ 28 ngày, cùng các ngày lễ cũ và cuối tuần.
- Thú cưng (mục Thiết bị, mở từ ngày 5, nuôi tối đa 4 bé): 6 chó (Phốc Sóc, Chihuahua, Poodle, Bichon Frise, Maltese, Shih Tzu) và 5 mèo (Anh lông ngắn, Ragdoll, Scottish Fold, Munchkin, Ba Tư). Mỗi bé tăng khách, tăng kiên nhẫn của khách, một số bé tăng tip; tốn tiền ăn mỗi ngày (tính vào chi phí cố định) và hiện ngay trước quầy. Tổng cộng tối đa khách +15%, kiên nhẫn +15%.

## v30
- Bán theo số LY nhưng tổng kết theo số KHÁCH. Mỗi khách gọi từ 1 đến 3 ly. Giới hạn ly mỗi ngày: 30 ngày đầu tối đa 64 ly (cuối tuần, lễ nhiều hơn ngày thường), từ sau ngày 30 ngày đông tối đa 120 ly.
- Sự cố bất ngờ xảy ra NGAY TRONG GIỜ BÁN, ngẫu nhiên, trung bình khoảng 14 ngày một lần (mất điện, ngập đường, vỡ ống nước, chập điện, rào đường thi công, chủ quán ốm). Khách đang chờ phải về, quán đóng cửa ngay, chỉ tính doanh thu phần đã bán; tiền thuê và lương vẫn tính, có sự cố tốn thêm tiền sửa chữa.
- Máy ép ly tự động hoạt động thật: tự dừng rót ở vạch ĐẠT, ly đúng đơn thì thanh xanh chạy 0,7 giây rồi tự ép và giao ly; có nút Tắt/Bật tự động trên máy.

## Từ v29 trở về trước
- Thuế tuần phát đầu ngày 8, 15, 22,... có 5 ngày để nộp, biển báo ở tab Cửa hàng và Nhập hàng, công tắc Tự động nộp thuế.
- Vốn khởi điểm 520.000đ; tiền thuê ưu đãi 7 ngày đầu 40.000đ, 7 ngày kế 55.000đ, sau đó 70.000đ.
- Chống phá sản sớm: trong 10 ngày đầu, cuối ngày còn dưới 60.000đ thì gia đình cho mượn không lãi (tối đa 2 lần).
