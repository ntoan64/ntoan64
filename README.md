<h1 align="center">Nguyễn Thanh Toàn</h1>

<p align="center">
  <b>Fullstack Developer</b> · React · Node.js · MongoDB · TP. Hồ Chí Minh<br>
  Mình thích làm sản phẩm <b>chạy thật, có người dùng thật</b>, từ giao diện tới server.
</p>

<p align="center">
  <a href="https://anlivingspaces.com"><img src="https://img.shields.io/badge/Dự_án_đang_chạy-anlivingspaces.com-1b3a31?style=for-the-badge" alt="anlivingspaces.com"></a>
</p>

---

### 🙋 Về mình

- 🏠 Đang phát triển và vận hành **[AnLiving](https://anlivingspaces.com)**: website cho thuê phòng kèm trang quản lý và cổng cư dân, phục vụ một doanh nghiệp thật tại TP.HCM
- 🌱 Đang học thêm: **Java · Spring Boot · PostgreSQL**
- 🎯 Đang tìm cơ hội **thực tập Fullstack / Frontend** tại TP.HCM
- 🤖 Dùng AI (Claude, Codex, Google Stitch) để làm nhanh hơn, còn mình tự quyết định, kiểm tra và chịu trách nhiệm với sản phẩm

---

### 🚀 Dự án nổi bật — AnLiving

> Tự làm từ đầu đến cuối: trao đổi nhu cầu với chủ nhà → thiết kế giao diện → frontend + backend → triển khai → vận hành hằng ngày.

<p>
  <img src="anh/trang-chu.jpg" width="100%" alt="Trang chủ AnLiving">
</p>

<table>
<tr>
<th width="50%">Khách tìm phòng</th>
<th width="50%">Chủ nhà quản lý</th>
</tr>
<tr>
<td><img src="anh/danh-sach-phong.jpg" alt="Danh sách phòng và bộ lọc"></td>
<td><img src="anh/admin-so-do-phong.jpg" alt="Sơ đồ phòng"></td>
</tr>
<tr>
<td>Lọc phòng theo khu, giá, diện tích, số người, tiện ích; mỗi phòng có trang riêng để chia sẻ</td>
<td>Sơ đồ phòng theo khu, đổi trạng thái 1 chạm; dashboard nhắc việc cần làm</td>
</tr>
<tr>
<th>Trên điện thoại: chi tiết phòng · cổng cư dân</th>
<th>Xử lý yêu cầu của cư dân</th>
</tr>
<tr>
<td><img src="anh/chi-tiet-phong-mobile.jpg" width="49%" alt="Chi tiết phòng"> <img src="anh/cu-dan-ho-tro-mobile.jpg" width="49%" alt="Cổng cư dân"></td>
<td><img src="anh/admin-ho-tro-cu-dan.jpg" alt="Xử lý yêu cầu hỗ trợ"></td>
</tr>
<tr>
<td>Gallery ảnh, nút liên hệ nhanh; cư dân gửi báo hỏng, theo dõi tiến độ, xác nhận chi phí</td>
<td>Tiếp nhận → xử lý → báo phí → hoàn thành; báo tin cho quản lý qua Telegram</td>
</tr>
</table>

**Điểm kỹ thuật:**
- **REST API** Express với 3 nhóm quyền (công khai / quản lý / cư dân), xác thực **JWT** và cookie **HttpOnly**, mật khẩu **bcrypt**
- Chống dò mật khẩu (rate limit), chống giả IP, CSP/HSTS, chống sửa đè đồng thời
- Backend đóng gói **Docker**, chạy trên **Cloudflare Containers**; ảnh và bản sao lưu lưu trên **R2**, sao lưu tự động mỗi ngày
- Chuyển trang gần như tức thì nhờ tách code theo trang, cache và tải trước dữ liệu
- SEO đầy đủ (sitemap tự sinh, Open Graph, JSON-LD); Chính sách bảo mật theo Nghị định 13/2023
- Test tự động: 23 test API (`node:test`) + test trình duyệt (Playwright)

🔗 **Xem web thật:** [anlivingspaces.com](https://anlivingspaces.com) · 📖 **Giới thiệu chi tiết:** [ntoan64/anliving](https://github.com/ntoan64/anliving) · 🔒 Mã nguồn để riêng tư vì là dự án của doanh nghiệp — mình sẵn sàng demo hoặc chia sẻ khi được yêu cầu.

---

### 🛠️ Công nghệ

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000" alt="JavaScript">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=fff" alt="Vite">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=fff" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=fff" alt="CSS3">
</p>

**Backend & dữ liệu**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=fff" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000?style=flat-square&logo=express&logoColor=fff" alt="Express">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=fff" alt="MongoDB">
  <img src="https://img.shields.io/badge/JWT-000?style=flat-square&logo=jsonwebtokens&logoColor=fff" alt="JWT">
</p>

**Hạ tầng & công cụ**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=fff" alt="Docker">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=fff" alt="Cloudflare">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=fff" alt="Git">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=fff" alt="Playwright">
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=fff" alt="Claude">
  <img src="https://img.shields.io/badge/Google_Stitch-4285F4?style=flat-square&logo=google&logoColor=fff" alt="Google Stitch">
</p>

**Đang học**
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=fff" alt="Java">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=fff" alt="Spring Boot">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=fff" alt="PostgreSQL">
</p>

---

### 📫 Liên hệ

- 🌐 Dự án: [anlivingspaces.com](https://anlivingspaces.com)
- 💻 GitHub: [@ntoan64](https://github.com/ntoan64)
