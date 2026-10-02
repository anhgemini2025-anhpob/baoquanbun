# HƯỚNG DẪN SỬ DỤNG PHỤ GIA CHO BÚN TƯƠI TRUYỀN THỐNG VIỆT NAM

> **Ứng dụng Web & Cẩm nang Kỹ thuật Thực phẩm Thực chiến**  
> Bám sát Thông tư 24/2019/TT-BYT, TT 17/2023/TT-BYT, TT 08/2024/TT-BYT và Văn bản hợp nhất **09/VBHN-BYT (06/09/2024)**  
> Nhóm thực phẩm áp dụng: **06.4.3 – Sản phẩm dạng sợi đã làm chín (Bún tươi)**  
> Domain dự kiến: [https://baoquanbun.vercel.app/](https://baoquanbun.vercel.app/)

---

## 📌 Giới Thiệu
Dự án được xây dựng nhằm mục đích cung cấp cẩm nang tra cứu và công cụ tính toán phối trộn phụ gia an toàn, đúng chuẩn pháp lý cho các cơ sở sản xuất, cán bộ kỹ thuật, QA/QC và quản lý xưởng bún tươi truyền thống trên toàn quốc.

### 🌟 Tính Năng Nổi Bật
1. **Đính chính 7 sai lầm nghiêm trọng:** Làm rõ mã nhóm thực phẩm chuẩn 06.4.3 (không nhầm lẫn với nhóm bột 06.2.1), cơ chế độ tan của Acid Sorbic, tính bền nhiệt của Acid Lactic, bản chất tạo gel của Amylose trong gạo.
2. **Cảnh báo chất cấm tuyệt đối:** Nói KHÔNG với Hàn the (Borax), Formol, Tinopal huỳnh quang, Javel tẩy trắng.
3. **Bảng phụ gia chuẩn nhóm 06.4.3:** Giới hạn ML Sorbate (2.000 mg/kg), Phosphat STPP (2.500 mg P/kg), phụ gia GMP (Acid Lactic, Acid Citric, Tinh bột biến tính 1422, Xanthan gum, Guar gum).
4. **So sánh 2 phương pháp:** Phương pháp có gia nhiệt (trong khối bột trước đùn - luộc) và Phương pháp không gia nhiệt (phun sương/ngâm bề mặt sau làm nguội).
5. **Ma trận Hiệp đồng & Tương kỵ:** Khám phá công nghệ nhiều rào cản (Hurdle Technology: pH thấp + phụ gia + lạnh 4–8°C + bao gói kín).
6. **Máy tính phối trộn tương tác:** Tính toán lượng cân tự động cho mẻ bột gạo khô ($B$), hệ số ra bún ($Y$), tỷ lệ lưu giữ ($R$) và tự động kiểm tra kịch bản xấu nhất ($R=1$).
7. **Trị 7 nỗi đau sự cố:** Chẩn đoán và xử lý dứt điểm tình trạng bún thiu chua, chảy nhớt, đốm trắng, khô cứng qua đêm, bở nát khi chan nước lèo, tồn dư chập chờn.
8. **Đọc Online & Tải File Gốc:** Xem trước và tải về file PDF (289 KB) cùng bản Word DOCX chuẩn.

---

## 👨‍🔬 Thông Tin Tác Giả & Bản Quyền
- **Tác giả / Người trình bày:** Kỹ sư **Nguyễn Đức Duy Anh**
- **Hotline / Zalo tư vấn:** **+84 908 095 693**
- **Phiên bản:** 1.0 (Tháng 10/2026)
- **Đơn vị phát triển:** **DUY ANH DIGITAL LAB**
- **Hệ sinh thái:** [ungdung.vercel.app](https://ungdung.vercel.app)

---

## 🚀 Triển Khai (Deployment)
Dự án là ứng dụng Web tĩnh (HTML5, Tailwind CSS, JavaScript thuần) hoạt động mượt mà không cần cài đặt backend phức tạp.
- Triển khai Vercel: Cấu hình sẵn trong `vercel.json`
- Domain: `baoquanbun.vercel.app`
