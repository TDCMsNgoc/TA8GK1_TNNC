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

Để đưa trang web lên GitHub và có link trực tuyến chia sẻ cho học sinh/sinh viên làm bài:

#### Bước 1: Tạo Repository trên GitHub
1. Đăng nhập vào [GitHub.com](https://github.com/).
2. Nhấn nút **New Repository** (Tạo kho lưu trữ mới).
3. Đặt tên Repo (Ví dụ: `tienganh8-gk1-tracnghiem`).
4. Để chế độ **Public** và nhấn **Create repository**.

#### Bước 2: Tải code lên GitHub
- **Cách qua giao diện web GitHub (Đơn giản nhất)**:
  1. Trong trang repo vừa tạo, nhấn vào **Upload files**.
  2. Kéo thả toàn bộ các file và thư mục trong dự án vào:
     - `index.html`
     - Thư mục `css/` (chứa `style.css`)
     - Thư mục `js/` (chứa `questions.js` và `app.js`)
     - `README.md`
  3. Nhấn **Commit changes**.

- **Cách qua Git CLI (Nếu máy có cài Git)**:
  ```bash
  git init
  git add .
  git commit -m "Initial commit: TA8-GK1 Trac Nghiem NC"
  git branch -M main
  git remote add origin https://github.com/<tai-khoan-cua-ban>/<ten-repo>.git
  git push -u origin main
  ```

#### Bước 3: Bật GitHub Pages
1. Tại trang Repo trên GitHub, chọn tab **Settings** (Cài đặt).
2. Ở thanh bên trái, chọn mục **Pages**.
3. Tại phần **Build and deployment** -> **Source**: Chọn `Deploy from a branch`.
4. Tại phần **Branch**: Chọn nhánh `main`, thư mục `/ (root)`, rồi nhấn **Save**.
5. Đợi khoảng 1 - 2 phút, GitHub sẽ cung cấp cho bạn một đường link trực tuyến có dạng:
   ```
   https://<tai-khoan-cua-ban>.github.io/<ten-repo>/
   ```
6. Bạn có thể gửi đường link này cho học sinh để làm bài thi trực tuyến bất kỳ lúc nào trên điện thoại hay máy tính!

---

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
