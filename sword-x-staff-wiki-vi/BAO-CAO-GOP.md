# BÁO CÁO GỘP — Sword X Staff: Bách khoa của user + Wiki Fandom (bản dịch tiếng Việt)

Ngày: 2026-11-20. Thư mục site cuối: `~/workspace/swordxstaff/site/` (tổng ~205 MB).
Mở bằng cách mở file `site/index.html` trong trình duyệt, giữ nguyên cấu trúc thư mục
(vì mọi link/ảnh đều là đường dẫn tương đối).

## 1. Site gồm những gì

| Thành phần | Số lượng / vị trí |
|---|---|
| Trang chủ (file của user, giữ nguyên nội dung + tools) | `site/index.html` (432.822 ký tự, từ file gốc 414.876 ký tự — chỉ thêm khung Fandom + mảng tìm kiếm wiki) |
| Bài wiki đã dịch sang tiếng Việt | 53 bài trong `site/wiki/<slug>.html` |
| Trang chính Wiki (mục lục wiki theo nhóm) | `site/wiki/index.html` |
| CSS wiki | `site/wiki/style.css` |
| Assets của user | 683 file trong `site/assets/` — `art/` 12 jpg, `icons/` 276 svg, `official/` 395 png/jpg |
| Ảnh gốc Fandom đã cào | 228 file trong `site/assets/fandom/` (~188 MB) |
| Tổng số file HTML trong site | 55 (1 trang chủ + 54 trang wiki) |

Bản dịch wiki làm từ nguồn đã cào trước đó (`~/workspace/swordxstaff/raw/`, `pages.json`);
bản làm việc còn giữ tại `~/workspace/swordxstaff/vi/` (không sửa trong đợt gộp này).
Quy ước dịch đầy đủ tại `~/workspace/swordxstaff/vi/GLOSSARY.md`.

## 2. Bài wiki đã dịch (53 bài)

Nhóm **Bắt đầu chơi** (11): Sword X Staff, FAQ Ra Mắt, Hướng Dẫn Tân Thủ: Cuộc Xâm Lăng
Hỗn Mang, Chọn Lớp Nhân Vật, Tổng Quan Các Lớp Nhân Vật, Chuyển Lớp, Tất Cả Về Chuyển Lớp,
Tiến Trình Phát Triển, Hệ Thống Theo Mùa, Tổng Quan Kỹ Năng, Thăng Cấp Kỹ Năng.
Nhóm **Lớp nhân vật** (10): Chiến Binh (Warrior), Pháp Sư (Mage), Hiệp Sĩ (Knight),
Đấu Sĩ (Duelist), Thuật Sư (Sorcerer), Hiền Giả (Sage), Cuồng Chiến (Berserker),
Thánh Hiệp Sĩ (Paladin), Đại Pháp Sư (Archmage), Bí Thuật Sư (Arcanist).
Nhóm **Kỹ năng theo lớp** (6): Kỹ Năng Chiến Binh / Pháp Sư / Hiệp Sĩ / Đấu Sĩ /
Thuật Sư / Hiền Giả.
Nhóm **Bạn Đồng Hành & Fantomon** (10): Bạn Đồng Hành, Fantomon (tổng quan), Fantomon,
Akane, Molly, Reina, Dryason, Hermes, Narss (Thủ Lĩnh), Rolla.
Nhóm **Thế giới & hoạt động** (11): Bản Đồ, Cõi Vật Chất, Đấu Trường, Bang Hội,
Phụ Bản Hàng Ngày, Trái Định Mệnh, Tượng Nữ Thần, Thương Hội Commercium, Gian Hàng,
Khúc Dạo Đầu Hành Trình, Bí Ẩn Nguyên Tố.
Nhóm **Khác** (5): Ice Spike, Water Shot, DiscordIntegrator, BOLTRAY GAMES, SwordxStaff Wiki.

Quy ước dịch: tên riêng nhân vật giữ nguyên; tên lớp dịch + kèm tên gốc tiếng Anh ở lần
đầu xuất hiện trong mỗi bài; tên kỹ năng/bùa/vật phẩm giữ nguyên tiếng Anh như trong game
(để tra cứu khớp với game), chỉ dịch nhãn và mô tả; giữ nguyên mọi con số, %, số ô, số lượt.
Mỗi bài wiki cuối trang có dòng nguồn + link về bài gốc trên `swordxstaff.fandom.com`,
ghi chú CC-BY-SA. Dữ liệu trong file của user (giftcode, tỉ lệ, 26 nghề, build meta…)
được GIỮ NGUYÊN như user viết, không đối chiếu/xóa theo wiki.

### Trang không tạo file bài (3 trang trong tổng 56 bài gốc)
- **Main Page** (pageid 155): bản gốc chỉ là trang đổi hướng tới SwordxStaff Wiki →
  đã gộp vào `site/wiki/index.html` làm trang chính Wiki.
- **LastEdits** (pageid 374): trang động, nội dung trống (0 từ) → không tạo file.
- **Character page** (pageid 451): chỉ có thông báo “Candidate for deletion”, không có
  nội dung thật → không tạo file.

## 3. Khung Fandom đã thêm (không sửa nội dung/tools của file user)

- Thanh menu Fandom dưới topbar: **EXPLORE / KINGDOMS / COMBAT / EVENTS / BEGINNER GUIDE**
  (trỏ tới các bài wiki tương ứng). Có mặt ở cả trang chủ và mọi trang wiki.
- Sidebar trái trang chủ: thêm nhóm **“Wiki Fandom — Bản dịch tiếng Việt”** liệt kê đủ
  53 bài theo 6 nhóm trên + link “Trang chính Wiki”. Các trang wiki có sidebar tương tự
  (tự cuộn, đánh dấu bài đang đọc).
- Breadcrumbs: “Trang chủ / Wiki / Tên bài” trên mọi trang wiki.
- Footer: ghi nguồn CC-BY-SA + link Fandom gốc + link Trang chủ / Trang chính Wiki.
  Có ở trang chủ và mọi trang wiki.
- Nút chuyển sáng/tối: file user ĐÃ CÓ sẵn (`themeToggleBtn`) nên không thêm nút mới.
- Dark theme của file user được giữ nguyên; trang wiki giữ theme sáng gọn nhẹ vốn có
  của bản dịch, chung topbar/menu/footer tối màu kiểu Fandom.

## 4. Tìm kiếm chung (Ctrl+K)

- Ô tìm kiếm của trang chủ đã mở rộng: thêm mảng `WIKI_INDEX` gồm **53 mục** (tiêu đề
  tiếng Việt + nhóm + mô tả), `SEARCH_INDEX.push(...WIKI_INDEX)`, click kết quả wiki
  mở đúng file `wiki/<slug>.html` (nhánh `if (p.wiki) { window.location.href = p.wiki; }`
  đặt trước `switchTab`).
- Placeholder của ô tìm kiếm đã ghi thêm “, 53 bài wiki…”.
- Tìm kiếm trong trang wiki: các trang wiki có link “🔍 Tìm kiếm (Ctrl+K)” về trang chủ.

## 5. Tính năng của file user đã giữ nguyên

Đã đối chiếu còn đủ trong `site/index.html`: tìm kiếm nhanh Ctrl+K + dropdown kết quả;
nút đổi Sáng/Tối; sidebar 11 mục (Tân Thủ/Kinh tế/Giftcode, Cơ chế chiến đấu, 26 nghề,
120 kỹ năng, Build meta, Trang bị/Ngọc, Cổ vật/Fantomon, Đồng hành/Món ăn, Mùa giải/
Bản đồ/Giả lập, Bestiary, 6 máy tính); checklist ngày/tuần dùng localStorage
(`dailyRoutineChecklist`, `resetDailyBtn`); 17 giftcode; ma trận tiền tệ; tỉ lệ
summon/pity; từ điển VI↔EN; công thức chiến đấu; cây 26 nghề; giả lập lắp skill 8 ô
(`customBuildClass`…); lò rèn; ngọc; 18 cổ vật; 12 fantomon; 75 đồng hành; 26 món ăn;
mốc sự kiện; reset mùa; bản đồ Kanstein; 6 máy tính (trong đó có máy tính Primostar
`outPsStars`). Không sửa nội dung, số liệu hay JS gốc của file user.

## 6. Quy tắc asset — ưu tiên bản gốc Fandom khi trùng tên

Quy tắc: nếu một file trùng tên ở cả hai bên (assets của user và assets Fandom đã cào),
luôn dùng bản Fandom và bỏ bản của user; chỉ giữ bản user khi Fandom không có file cùng tên.
Kiểm tra bằng **tên file, không phân biệt hoa/thường**.

**Kết quả kiểm tra: 0 file trùng tên giữa hai bên → 0 file bị thay.**
Cụ thể: 683 file của user và 228 file Fandom không có tên file nào trùng nhau
(kể cả khi so không phân biệt hoa/thường). Kiểm tra thêm theo nội dung (hash MD5):
cũng **0 file trùng nội dung** giữa hai bên. Vì vậy toàn bộ assets của user được giữ
nguyên, toàn bộ ảnh Fandom nằm ở `site/assets/fandom/`, không phải sửa link nào.

### 4 trường hợp trùng phần tên (stem) — đã kiểm tra, KHÔNG thay (để user đối chiếu)
Bốn cặp sau trùng phần tên nhưng **khác định dạng và khác loại tài sản**, không phải
cùng một hình nên không áp quy tắc thay thế:

| File của user | File Fandom | Vì sao không thay |
|---|---|---|
| `assets/icons/classes/warrior.svg` (2,7 KB, icon vector 80×80 tự vẽ) | `Warrior.jpg` (927 KB, ảnh 1920×1080) | Icon giao diện vs ảnh artwork lớp — khác mục đích; trang chủ đang dùng icon này (2 lần tham chiếu) |
| `assets/icons/classes/mage.svg` (2,7 KB, icon vector 80×80 tự vẽ) | `Mage.jpg` (990 KB, ảnh 1920×1080) | Như trên; trang chủ đang dùng icon này (2 lần tham chiếu) |
| `assets/icons/regions/aqualis.svg` (1,1 KB, banner vector 480×180 tự vẽ) | `Aqualis.jpg` (1,2 MB, ảnh 2208×1242) | Banner trang trí vùng vs ảnh chụp vùng — khác loại tài sản |
| `assets/icons/regions/verdantglade.svg` (1,1 KB, banner vector 480×180 tự vẽ) | `Verdantglade.png` (2,6 MB, ảnh 2208×1242) | Như trên |

Nếu user muốn dùng ảnh Fandom thay cho 4 icon/banner này thì đó là thay đổi thiết kế
(đổi icon nhỏ thành ảnh lớn), cần user quyết — hiện trạng giữ nguyên cả hai bản.

## 7. Kiểm chứng cuối

- **Link/ảnh gãy: 0.** Quét toàn bộ `site/` (3.966 link `href`/`src` trong markup,
  sau khi giải mã URL-encoding): **0 link gãy**. 18 link nhìn như gãy trong lần quét
  thô chỉ là biểu thức mẫu trong JS (`${icon}`, `${c.img}`, `assets/icons/relics/relic-${idx}.svg`…)
  — các file đích mà chúng trỏ tới khi chạy đã đối chiếu đều tồn tại
  (relic-0..29, comp-0..24, dish-0..25, 120 skill svg, 7 region svg).
  33 link tên file tiếng Trung/ký tự đặc biệt dạng `%E5%A5…` và
  `Skill_Assend_Left_%25_Side.webp` giữ nguyên như gốc — trình duyệt tự giải mã nên
  vẫn mở đúng file trên đĩa (đã đối chiếu tên thật: `Skill_Assend_Left_%_Side.webp`,
  `Narss_(Chief).png` đều có). Không đổi tên file, không sửa các link đó.
- **JS không lỗi cú pháp:** `node --check` trên toàn bộ script của trang chủ (229.799 ký tự) — PASS.
- **Wiki:** 54/54 trang có đủ header/menu/sidebar/footer/breadcrumbs + dòng nguồn Fandom;
  122 tham chiếu ảnh Fandom trong các bài wiki đều trỏ tới file tồn tại trong
  `site/assets/fandom/`; không còn link nội bộ gãy; không còn đoạn tiếng Anh dài chưa
  dịch ngoài tên riêng/thuật ngữ đã quy ước (tên kỹ năng, địa danh, tên độ hiếm
  Rare→Immortal giữ nguyên theo glossary).
- **Chưa kiểm bằng trình duyệt thật:** checklist/máy tính/giả lập chỉ mới kiểm tra ở mức
  mã nguồn + cú pháp JS (các `id` và hàm còn đủ); chưa chạy click thử trong trình duyệt
  vì môi trường làm việc này không có trình duyệt thật. Nên mở `site/index.html` bấm thử
  checklist, 1 máy tính và ô tìm kiếm “warrior” trước khi chia sẻ.

## 8. Lưu ý về chất lượng bản dịch / lỗi của wiki gốc (đã giữ trung thực, không bịa)

- 4 bài Arcanist, Archmage, Berserker, Paladin có bảng Techniques/Charms **giống hệt nhau**
  và cùng dùng ảnh minh họa của Warrior — lỗi sao chép trên Fandom gốc; đã dịch đúng
  nguyên văn, không tự bịa kỹ năng mới.
- Bài Narss: infobox gốc ghi sai thành “Reina” (lỗi copy-paste của wiki gốc) — đã sửa
  thành “Narss” trong bản dịch và ghi chú tại đây.
- `skill-overview`: gốc ghi “five types” nhưng chỉ liệt kê 4, “three categories” nhưng
  liệt kê 4 — đã dịch sát số gốc, không tự sửa số.
- `class-selection` gọi nhánh lớp 2 của Chiến Binh là Duelist, còn `classes-overview`
  gọi là Fighter — dịch mỗi bài theo đúng gốc của bài đó, không tự thống nhất.
- Tên độ hiếm giữ nguyên tiếng Anh (Rare → Epic → Legendary → Mythic → Divine → Immortal)
  vì chưa có bảng dịch độ hiếm chốt trong glossary.

## Sửa lỗi ảnh thiếu — 2026-11-20 16:2x +07 (sau bàn giao)
- Nguyên nhân: 251 ảnh trong các trang wiki chỉ còn placeholder lazy-load 1x1 của Fandom (src là GIF trong suốt), do lúc dịch đã làm mất thuộc tính data-src/data-image-key. Trang chủ không bị (0 placeholder).
- Đã khôi phục đủ 251/251 về file local trong site/assets/fandom/, đối chiếu theo data-image-key trong bản HTML gốc đã cào: 234 file thường + 13 file tên có dấu nháy/ngoặc (Wind's Delight, Wind's Whisper, Dew's Blessing, Wind's Shadow, Warrior's Essence, Narss (Chief)) + 4 ảnh trang Dryason / Classes Overview (alt đã dịch sang tiếng Việt nên phải đối chiếu theo tên trang).
- Kiểm chứng sau sửa: 0 placeholder, 0 URL ảnh Fandom ngoài, 0 link/ảnh local gãy (quét toàn bộ site).
