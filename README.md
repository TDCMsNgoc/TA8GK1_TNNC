# ĐỀ THI TRẮC NGHIỆM TIẾNG ANH 8 - GIỮA HỌC KỲ 1 (NÂNG CAO)

> Ứng dụng web ôn luyện và thi thử trắc nghiệm trực tuyến môn Tiếng Anh Lớp 8 Giữa Học Kỳ 1 (Nâng cao).
> Được thiết kế chuẩn GDPT mới, giao diện trực quan, tương thích hoàn toàn trên máy tính, máy tính bảng và điện thoại di động, sẵn sàng chạy trực tiếp trên **GitHub Pages**.

---

## 🌟 TÍNH NĂNG NỔI BẬT

1. **Đề thi chuẩn 40 câu hỏi nâng cao**:
   - **Phần A (Câu 1 – 4)**: Phát âm (*Pronunciation*) - Gạch chân phần phát âm khác biệt (/s/, /z/, /iz/, /t/, /d/, /id/).
   - **Phần B (Câu 5 – 8)**: Giới từ chỉ Thời gian & Nơi chốn (*Time / Place*).
   - **Phần C (Câu 9 – 16)**: Cấu tạo từ (*Word form*).
   - **Phần D (Câu 17 – 40)**: Các cấu trúc ngữ pháp trọng điểm (*Structures*: So sánh hơn/bằng, prefer/would rather, spend/take, liên từ therefore/however/otherwise/although, mục đích so that/so as to, v.v.).

2. **Chế độ làm bài nghiêm túc (Theo đúng yêu cầu)**:
   - **Đồng hồ đếm ngược 20:00 (20 phút)**, đổi màu cảnh báo khi còn dưới 5 phút và dưới 2 phút. Tự động thu bài khi hết giờ.
   - **KHÔNG GỢI Ý ĐÁP ÁN** trong lúc sinh viên đang làm bài.
   - Hỗ trợ **Đánh dấu câu hỏi cần xem lại** (Flag for review) và **Bảng ma trận 40 câu hỏi** giúp nhảy nhanh đến câu bất kỳ.
   - Thanh tiến độ hiển thị trực quan số câu đã chọn.

3. **Chế độ xem kết quả & Lời giải chi tiết (Chỉ hiện sau khi nộp)**:
   - Chấm điểm tự động theo thang điểm 10 (mỗi câu 0.25 điểm) và thang 40 câu.
   - Thống kê tỷ lệ chính xác và thời gian hoàn thành.
   - Phân tích chi tiết biểu đồ năng lực theo từng **Chuyên đề** và theo từng **Cấp độ nhận thức (NB, TH, VD, VDC)**.
   - Hiển thị đáp án đúng (màu xanh lá) và đáp án của thí sinh (màu đỏ nếu sai).
   - Khung **Giải thích chi tiết** lý do ngữ pháp, phiên âm, cấu trúc chuyển đổi câu cho từng câu hỏi.
   - **Bộ lọc câu hỏi**: Xem tất cả, Chỉ xem câu đúng, Chỉ xem câu sai, Xem câu chưa làm.
   - Nút **Làm lại bài thi** và **In kết quả / Lưu PDF** (đã tối ưu giao diện in ấn đẹp mắt).

---

## 🚀 HƯỚNG DẪN CHẠY VÀ SỬ DỤNG

### Cách 1: Chạy trực tiếp trên máy tính (Không cần cài đặt gì thêm)
1. Tải về hoặc mở thư mục dự án `TA8-GK1-TRAC NGHIEM NC`.
2. Nhấp đúp chuột vào tệp `index.html` (hoặc chuột phải chọn mở bằng Chrome / Edge / Firefox).
3. Ứng dụng sẽ mở và hoạt động đầy đủ 100% ngay cả khi không có kết nối Internet!

---

### Cách 2: Triển khai lên GitHub Pages (CHẠY ONLINE TRÊN GITHUB)

> 💡 **ĐẶC BIỆT**: File `index.html` đã được **đóng gói trọn gói (All-in-one / Standalone)**. Toàn bộ CSS giao diện, dữ liệu 40 câu hỏi và JavaScript điều khiển đều đã được tích hợp sẵn bên trong `index.html`. Do đó, bạn chỉ cần tải đúng **1 file `index.html`** lên GitHub là ứng dụng chạy 100% hoàn hảo, không còn lo bị lỗi thiếu thư mục `css` hay `js`!

#### Bước 1: Tạo Repository trên GitHub
1. Đăng nhập vào [GitHub.com](https://github.com/).
2. Nhấn nút **New Repository** (Tạo kho lưu trữ mới).
3. Đặt tên Repo (Ví dụ: `tienganh8-gk1`).
4. **LƯU Ý QUAN TRỌNG**: Chọn chế độ **Public** (Tài khoản GitHub miễn phí chỉ cho phép chạy GitHub Pages khi repo ở chế độ Public).
5. Nhấn **Create repository**.

#### Bước 2: Tải file lên GitHub
- **Cách đơn giản nhất (Trực tiếp trên web GitHub)**:
  1. Trong trang Repo vừa tạo, nhấn vào **Upload files** (hoặc **Add file** -> **Upload files**).
  2. Kéo thả file `index.html` (và các file `.nojekyll`, `.github`, `README.md` nếu muốn) vào trang web.
  3. **LƯU Ý**: Hãy kéo thả trực tiếp file `index.html` vào khung tải lên (để `index.html` nằm ngay tại thư mục gốc, **KHÔNG** kéo cả thư mục cha `TA8-GK1-TRAC NGHIEM NC`).
  4. Nhấn **Commit changes**.

#### Bước 3: Kích hoạt GitHub Pages (Bắt buộc)
1. Tại trang Repo trên GitHub, bấm vào tab **Settings** (ở thanh menu trên cùng).
2. Ở thanh menu bên trái, tìm và bấm vào mục **Pages**.
3. Tại phần **Build and deployment** -> **Source**: Chọn `Deploy from a branch`.
4. Tại phần **Branch**: Chọn nhánh `main` (hoặc `master`), thư mục giữ nguyên `/ (root)`, rồi bấm nút **Save**.
5. Đợi khoảng **1 đến 2 phút**, tải lại trang Settings -> Pages, bạn sẽ thấy thông báo màu xanh kèm link dạng:
   ```
   https://<ten-tai-khoan-cua-ban>.github.io/<ten-repo>/
   ```
6. Bấm vào link đó là bài thi sẽ hiển thị đầy đủ và chạy trực tuyến cho tất cả học sinh!

---

### ⚠️ BẢNG HƯỚNG DẪN XỬ LÝ LỖI GITHUB THƯỜNG GẶP:

| Hiện tượng lỗi | Nguyên nhân | Cách khắc phục |
|:---|:---|:---|
| **Lỗi 404 Not Found** (There isn't a GitHub Pages site here) | 1. Chưa vào **Settings > Pages** để chọn nhánh `main` và ấn `Save`.<br>2. Hoặc repo đang để chế độ **Private** (Riêng tư).<br>3. Hoặc bạn kéo cả thư mục `TA8-GK1-TRAC NGHIEM NC` vào GitHub nên file nằm ở `/TA8-GK1-TRAC%20NGHIEM%20NC/index.html`. | 1. Vào **Settings > Pages**, chọn Branch `main` -> `Save`.<br>2. Chuyển repo sang chế độ **Public**.<br>3. Đảm bảo file `index.html` nằm ngay ở trang chủ (Root) của Repository. |
| **Trang web trắng tinh hoặc mất giao diện** | Khi tải lên web GitHub, các thư mục con `css/` hoặc `js/` bị thiếu khiến trình duyệt không tải được file. | File [**`index.html`**](file:///d:/websiteabc/TA8-GK1-TRAC%20NGHIEM%20NC/index.html) hiện tại đã được **tích hợp sẵn toàn bộ CSS & JS**, không cần bất kỳ file phụ nào khác! Chỉ cần có `index.html` là chạy 100%. |
| **Lỗi Jekyll build failed** | Trình biên dịch Jekyll của GitHub gặp lỗi phân tích. | Đã có sẵn file [**`.nojekyll`**](file:///d:/websiteabc/TA8-GK1-TRAC%20NGHIEM%20NC/.nojekyll) trong thư mục để tắt Jekyll. |

## 📁 CẤU TRÚC THƯ MỤC DỰ ÁN

```
TA8-GK1-TRAC NGHIEM NC/
├── index.html          # Trang giao diện chính của bài kiểm tra
├── README.md           # Hướng dẫn chi tiết dự án & cách triển khai
├── css/
│   └── style.css       # Toàn bộ CSS phong cách hiện đại, responsive, hỗ trợ in ấn
└── js/
    ├── questions.js    # Dữ liệu 40 câu hỏi, đáp án, mức độ nhận thức và lời giải
    └── app.js          # Logic đếm giờ 20p, chấm điểm, khóa gợi ý, ma trận câu hỏi
```

---

## 📊 BẢNG ĐÁP ÁN & CẤP ĐỘ NHẬN THỨC CỦA ĐỀ THI

| Câu | Đáp án | Mức độ | Trọng tâm kiến thức |
|:---:|:------:|:------:|:--------------------|
| 1 | **D** | NB | Phát âm đuôi -s/es (/s/ vs /ɪz/) |
| 2 | **D** | VD | Phát âm đuôi -s đặc biệt (/z/ vs /s/, gh = /f/) |
| 3 | **C** | NB | Phát âm đuôi -ed (/ɪd/ vs /t/) |
| 4 | **C** | VD | Phát âm đuôi -ed (/d/ vs /t/, gh = /f/) |
| 5 | **C** | NB | Giới từ chỉ giờ: *at + giờ* |
| 6 | **A** | TH | Giới từ: *in + tháng*, *on + buổi của ngày* |
| 7 | **B** | TH | Giới từ vị trí: *on the wall*, *in the corner* |
| 8 | **B** | VD | Giới từ: *at + nơi công cộng*, *on + thứ*, *at + giờ* |
| 9 | **A** | NB | Từ loại: *ask + O + to V1 (concentrate)* |
| 10 | **C** | NB | Từ loại: *a lot of + N (creativity)* |
| 11 | **B** | TH | Từ loại: *a/an + Adj + N (enjoyable)* |
| 12 | **C** | TH | Từ loại tính từ phủ định: *unexpected* |
| 13 | **C** | TH | Từ loại tính từ chỉ cảm xúc người: *feel stressed* |
| 14 | **C** | TH | Cụm danh từ số nhiều: *tourist attractions* |
| 15 | **B** | VDC | Bị động & cụm danh từ: *are attracted by*, *fascinating beauty* |
| 16 | **D** | VD | Cụm danh từ cố định: *under great pressure* |
| 17 | **B** | NB | Cấu trúc: *It takes + O + time + to V1* |
| 18 | **C** | NB | Cấu trúc: *spend + time + V-ing* |
| 19 | **C** | NB | Cấu trúc: *be fond of + V-ing* |
| 20 | **B** | TH | Cấu trúc: *be keen on + V-ing/N* |
| 21 | **C** | TH | Cấu trúc sở thích: *prefer V-ing to V-ing* |
| 22 | **A** | NB | Cấu trúc: *would rather + V1 + than + V1* |
| 23 | **A** | TH | Cấu trúc: *would rather + V1 + than + V1* |
| 24 | **B** | TH | Chuyển đổi câu: *find it interesting = interested in* |
| 25 | **A** | NB | Tương đương: *sth is interesting to sb = sb is interested in sth* |
| 26 | **B** | NB | So sánh hơn tính từ ngắn: *bigger than* |
| 27 | **A** | NB | So sánh hơn tính từ dài: *more difficult than* |
| 28 | **C** | TH | So sánh hơn trạng từ: *more fluently than* |
| 29 | **B** | VDC | Kết hợp: *want + to V1* & *spend + time + V-ing* |
| 30 | **B** | TH | Trạng từ liên kết: *; therefore, (vì vậy)* |
| 31 | **C** | TH | Trạng từ liên kết: *; otherwise, (nếu không thì)* |
| 32 | **B** | NB | Liên từ nhượng bộ: *Although + clause* |
| 33 | **C** | TH | Trạng từ liên kết: *; however, (tuy nhiên)* |
| 34 | **A** | VDC | Kết hợp: *so that (mục đích)* & *however (đối lập)* |
| 35 | **A** | VD | Cụm từ chỉ mục đích phủ định: *so as not to + V1* |
| 36 | **B** | TH | Viết lại câu: *have an intention of + V-ing = be going to V1* |
| 37 | **A** | VDC | Cấu trúc tân ngữ giả: *find + it + adj + to V1* |
| 38 | **B** | VD | Chuyển đổi câu: *prefer V-ing to V-ing = would rather V1 than V1* |
| 39 | **A** | NB | So sánh bằng: *as + adj/adv + as (fast)* |
| 40 | **B** | VD | Chuyển đổi: *It took + O + time + to V1 = S + spent + time + V-ing* |

---
*Chúc các em học sinh ôn tập thật tốt và đạt kết quả cao trong kỳ thi giữa kỳ!*
