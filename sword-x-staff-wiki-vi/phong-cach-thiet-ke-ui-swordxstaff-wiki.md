# Phong cách thiết kế UI — SwordxStaff Wiki (Fandom)

- **Trang quét:** https://swordxstaff.fandom.com/wiki/SwordxStaff_Wiki
- **Ngày quét:** 20/11/2026, khung nhìn 1919×998 px, chế độ sáng mặc định, không đăng nhập
- **Nền tảng:** Fandom (skin FandomDesktop), theme tùy chỉnh riêng của wiki
- **Tóm tắt một câu:** Light theme với khung nền tím–chàm bão hòa, nội dung trắng nổi ở giữa, banner art game anime, dải tiêu đề tím oải hương, chân trang tím mận–đen với link vàng gold — cảm giác fantasy/RPG rõ rệt, không phải theme trắng/xám trung tính mặc định của Fandom.

> Lưu ý quan trọng: các mã hex dưới đây là **ước lượng trực quan** từ ảnh chụp màn hình (công cụ quét không đọc được computed style, lấy mẫu pixel bị lỗi), không phải giá trị pixel chính xác. Dùng để tham khảo phong cách và tái hiện gần đúng, không dùng làm thông số kỹ thuật tuyệt đối.

## 1. Bảng màu

| Vai trò | Màu | Mã hex (ước lượng) | Ghi chú |
|---|---|---|---|
| Nền trang (khung ngoài) | Tím–chàm đậm, bão hòa | `#6865C6` – `#6A67CE` | Màu chủ đạo, tạo khung 2 bên nội dung |
| Nền nội dung chính | Trắng | `#FFFFFF` | Tương phản mạnh với nền tím |
| Dải tiêu đề khối (H2) | Tím oải hương | `#A78BDB` – `#AB8FD8` | Chữ trắng đậm, căn giữa |
| Viền thẻ/khối | Tím trung bình | `#7D63B8` – `#8A76C0` | Viền khoảng 2 px |
| Link trong bài | Tím | `#6A2FBF` – `#7A3ECB` | VD: "200+ skills", "companions" |
| Chữ thân bài | Xám đậm | `#333333` – `#3A3A3A` | Trên nền trắng |
| Thanh wiki khi cuộn (thu gọn) | Tím oải hương rất nhạt | `#E9E2F5` – `#EDE7F8` | Chữ chuyển sang đen |
| Chân trang chính | Tím mận rất đậm | `#2A0A2E` – `#2D0A2E` | Nền các cột link |
| Link chân trang | Vàng / gold | `#FFC500` – `#FFBF00` | Nổi trên nền tím mận |
| Dải cuối trang | Đen | `#000000` | Dòng "SwordxStaff Wiki is a Fandom Games Community." |
| Nút chính | Đen / tím mận đậm | `#000000` – `#2A0A2E` | Chữ trắng, chữ hoa |
| Khung quảng cáo trên | Đen | `#000000` | Toàn chiều rộng, cao ~250–280 px |
| Chữ "ADVERTISEMENT" | Xám | `#999999` | Chữ hoa nhỏ, giãn chữ |
| Facebook | Xanh dương | `#1877F2` | Icon mạng xã hội |
| Discord | Tím–xanh | `#5865F2` | Icon mạng xã hội |
| X (Twitter) | Đen | `#000000` | Icon mạng xã hội |

## 2. Kiểu chữ (Typography)

- **Font:** sans-serif hệ mặc định của Fandom (dạng Helvetica / Arial / Rubik). Tên font chính xác không xác định được từ lần quét chỉ đọc.
- **H1 (tiêu đề bài, VD "Home"):** ~32–36 px, chữ thường (không hoa toàn bộ), màu xám đậm `#3A3A3A`, trọng lượng nhẹ–trung bình. Hai bên có link phụ nhỏ màu tím: "Sign In to Save", "View source".
- **H2 (tiêu đề khối: "Welcome to the Sword x Staff Wiki!", "Mix & Match! Master of Skills", "Get Started"):** ~16–18 px, chữ trắng **đậm**, căn giữa, đặt trên dải nền tím oải hương.
- **Thân bài:** ~15–16 px, màu `#333333`–`#3A3A3A`, giãn dòng ~1,5–1,6. Văn bản trong khối chào mừng/giới thiệu căn giữa.
- **Menu wiki:** chữ hoa, ~13–14 px, đậm, màu trắng trên banner.
- **Left rail:** nhãn chữ nhỏ ~10 px, icon đen/xám.
- **Tiêu đề cột footer:** chữ hoa trắng, ~12 px, đậm. Link cột footer ~14 px, màu vàng gold.
- **Dải cuối trang:** ~12 px, trắng/xám nhạt; link "VIEW MOBILE SITE" vàng gold, chữ hoa đậm.

## 3. Bố cục (Layout)

- **Khung tổng thể:** một cột nội dung chính căn giữa, rộng ~1.230 px trong khung nhìn 1919 px (từ x≈370 đến x≈1600), lề tím 2 bên mỗi bên ~300–320 px. Nội dung trắng nổi trên nền tím.
- **Thanh điều hướng toàn cục của Fandom (global top nav):** cao ~45–48 px, nền trắng, cố định ở đầu trang, chữ đen. Trái: logo Fandom (chữ đen + biểu tượng ngọn lửa đỏ/hồng với trái tim vàng). Phải: ô Search trắng viền xám nhạt, bo góc ~4–6 px, rộng ~320 px, có icon kính lúp; nút "SIGN IN" nền trắng, viền và chữ đen/tím đậm, chữ hoa đậm; nút "CREATE A FREE ACCOUNT" nền đen/tím mận đậm, chữ trắng, chữ hoa đậm, bo góc.
- **Khung quảng cáo:** ngay dưới top nav, nền đen toàn chiều rộng, cao ~250–280 px (quảng cáo bên thứ ba).
- **Community header (đầu trang wiki):** banner ảnh game-anime toàn chiều rộng, cao ~300 px (nhân vật nữ tóc đỏ, kiếm, nền tím–xanh, lớp phủ gradient tím nhạt ở dưới). Góc trái banner: ảnh đại diện wiki hình vuông ~100×100 px + tiêu đề "SwordxStaff Wiki" trắng, sans-serif đậm, ~26–28 px. Menu wiki ngay dưới/đè lên banner: EXPLORE, KINGDOMS, COMBAT, EVENTS, BEGINNER GUIDE (chữ hoa trắng, ~13–14 px, đậm, có mũi tên mở rộng). Bên phải: "56 PAGES" trắng, nút "Discuss" và icon mặt trăng (đổi theme) dạng ô viền trắng bo góc. Khi cuộn xuống, thanh này thu gọn thành nền tím oải hương rất nhạt, chữ đen, vẫn giữ menu + Search + SIGN IN + CREATE A FREE ACCOUNT. Có nút "Switch to Dark Theme" (không bật trong lần quét).
- **Left rail (thanh bên trái):** rộng ~66 px, nền trắng, cố định dọc bên trái, icon đen/xám + nhãn chữ nhỏ ~10 px. Thứ tự: Home, Explore, Saved, Progress, History, Utilities, Fandom Four; dưới cùng: Settings, More. Lưu ý: đây là thanh công cụ của Fandom, **không** phải menu danh mục wiki dạng cây — danh mục wiki nằm ở thanh ngang trên banner.
- **Cột công cụ nổi:** bên trái nội dung có cột hẹp với các icon "View source", "Sign In to Save", "Page Tools".
- **Trang chủ (cấu trúc khối):** khối chào mừng bên trái ~770 px + ảnh sự kiện bên phải ~360 px; tiếp theo "Mix & Match! Master of Skills" bên trái + quảng cáo 300×250 bên phải; tiếp theo khối "Get Started". Không có cột phải cố định dạng sidebar bài viết truyền thống trên trang chủ. Khối "Get Started" liệt kê "56 articles" và "228 files".
- **Bo góc & khoảng trắng:** các khối có viền tím và bo góc ~8–10 px; khoảng trắng thoáng, nội dung không bị dồn.

## 4. Thành phần (Components)

### Nút bấm
- **Nút chính:** nền đen/tím mận đậm, chữ trắng, chữ hoa, bo góc.
- **Nút phụ:** nền trắng, viền đen/tím, chữ đen/tím.
- **Nút tải app:** huy hiệu "Download on the App Store" và "GET IT ON Google Play" màu đen, chữ trắng. Ngoài ra có nút "Join Us" và link "Create an account".
- **Nút Discuss / đổi theme:** dạng ô viền (trắng trên banner).
- Trạng thái hover/focus chưa quan sát được trong lần quét tĩnh.

### Ô tìm kiếm
- Nền trắng, viền xám nhạt, bo góc ~4–6 px, rộng ~320 px, icon kính lúp. Có ở cả top nav và thanh wiki thu gọn khi cuộn.

### Thẻ nội dung (cards)
- Trang chủ không có infobox nhân vật/vật phẩm. Các "thẻ" thực chất là **bảng bố cục (layout table)** dùng làm thẻ nội dung.
- Kiểu thẻ: nền trắng, viền tím ~2 px, bo góc ~8–10 px; tiêu đề là dải màu tím oải hương với chữ trắng đậm căn giữa; bên trong có ảnh minh họa game, đoạn mô tả ngắn và link tím.
- Không có bảng dữ liệu có tiêu đề cột/sắp xếp trên trang chủ.

### Liên kết
- Link trong bài: tím (`#6A2FBF`–`#7A3ECB`); link đã xem có thể đậm hơn.
- Link footer: vàng gold trên nền tím mận.
- Link ra ngoài: Official Website (game.boltray.com), Official Facebook, Discord, X, Google Play, App Store; cộng đồng: Community Page, Rules; bản quyền: CC-BY-SA.

### Chân trang (footer)
- **Phần chính:** nền tím mận rất đậm, logo "Fandom" trắng với biểu tượng ngọn lửa hồng/vàng. 6 nhóm cột: EXPLORE PROPERTIES, OVERVIEW, COMMUNITY, ADVERTISE, FANDOM APPS, FOLLOW US. Tiêu đề cột chữ hoa trắng ~12 px đậm; link cột vàng gold ~14 px (VD: Fandom, GameSpot, What is Fandom?, Terms of Use, Community Central, Support). "FOLLOW US" có icon mạng xã hội trắng; cột "FANDOM APPS" có mô tả trắng + huy hiệu App Store/Google Play.
- **Trên chân trang:** khối trắng chứa dòng bản quyền "Community content is available under CC-BY-SA unless otherwise noted." và quảng cáo "Your Fandom Needs You." / "THE FANDOM AWARDS" nền hồng đậm–tím, nút "CAST YOUR VOTE" vàng.
- **Dải cuối:** nền đen, dòng "SwordxStaff Wiki is a Fandom Games Community." trắng/xám nhạt ~12 px; link "VIEW MOBILE SITE" vàng gold, chữ hoa đậm.

## 5. Điểm đặc trưng — vì sao nhìn là biết wiki này

1. **Khung tím–chàm bão hòa** bao quanh nội dung trắng — khác hẳn theme trắng/xám trung tính mặc định của Fandom.
2. **Banner art game anime** (nhân vật, kiếm, hiệu ứng phép thuật) thay vì màu trơn.
3. **Dải tiêu đề tím oải hương + chữ trắng căn giữa** lặp lại ở mọi khối nội dung — dấu nhận diện mạnh nhất của trang chủ.
4. **Chân trang tím mận–đen + link vàng gold** — tương phản cao, cảm giác "hoàng gia fantasy".
5. **Nội dung nhấn mạnh:** "Third Way RPG", "200+ skills", "Mix & Match", chuyển class miễn phí mỗi tuần, 56 bài / 228 file.
6. **Menu wiki theo chủ đề game** (KINGDOMS, COMBAT, EVENTS, BEGINNER GUIDE) thay vì menu wiki chung chung.

## 6. Gợi ý tái hiện bằng CSS (tham khảo)

```css
:root {
  --page-bg: #6865C6;        /* nền trang tím–chàm (ước lượng) */
  --content-bg: #FFFFFF;     /* nền nội dung */
  --header-band: #A78BDB;    /* dải tiêu đề khối */
  --card-border: #7D63B8;    /* viền thẻ */
  --link: #6A2FBF;           /* link trong bài */
  --text: #333333;           /* chữ thân bài */
  --footer-bg: #2A0A2E;      /* nền chân trang */
  --footer-link: #FFC500;    /* link chân trang */
  --radius: 8px;             /* bo góc khối/thẻ */
  --content-max-width: 1230px;
  --font-stack: "Rubik", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```

- Nền trang: tím–chàm đặc; nội dung: khối trắng tối đa ~1230 px, căn giữa.
- H2 khối: nền `var(--header-band)`, chữ trắng đậm, căn giữa, ~16–18 px.
- Thẻ: nền trắng, viền 2 px `var(--card-border)`, bo góc 8–10 px.
- Header: banner ảnh toàn chiều rộng cao ~300 px, tiêu đề wiki trắng đậm 26–28 px ở góc trái, menu chữ hoa trắng 13–14 px.
- Footer: nền `var(--footer-bg)`, tiêu đề cột trắng hoa 12 px đậm, link `#FFC500` 14 px, dải cuối đen.

## 7. Giới hạn của lần quét

- Mã hex là ước lượng trực quan, chưa đo pixel chính xác.
- Chỉ quét chế độ sáng, không đăng nhập; chưa xem dark theme (có nút chuyển theme), trạng thái hover/focus, và giao diện mobile.
- Quảng cáo (khung đen 250–280 px trên đầu, khối 300×250 trong trang) là nội dung bên thứ ba, không thuộc theme của wiki.
- Cấu trúc trang chủ lấy từ nội dung thật: khối Welcome, "Mix & Match! Master of Skills" (200+ skills, dual-class, 6 class ranks, rank 7 đang phát triển, đổi class miễn phí 1 lần/tuần, giữ nguyên level và skill), khối "Get Started", link cộng đồng (Community Page, Rules, Facebook, Discord, X) và kho ứng dụng (Google Play, App Store).
