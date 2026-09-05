# Curated AI/ML Foundations Library

[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Repository Status](https://img.shields.io/badge/Status-Curated%20Collection%20in%20Progress-blue.svg)]()
[![No Piracy](https://img.shields.io/badge/Policy-No%20PDF%20Distribution-success.svg)]()

Một thư viện giám tuyển (curated library) chất lượng cao dành cho các tác phẩm kinh điển về **nền tảng toán học, thống kê lý thuyết, thuật toán học máy và lý thuyết deep learning**. 

Repository này được xây dựng theo tiêu chuẩn học thuật nghiêm ngặt: **tuyệt đối không lưu trữ hay phân phối lậu tệp PDF/sách**, chỉ cung cấp metadata xác thực, mục lục chương mục chuẩn xác, tóm tắt khái niệm cốt lõi, ma trận so sánh liên môn và định hướng lộ trình học tập độc lập.

---

## 📚 Danh mục 10 tác phẩm trong bộ sưu tập (Collection Index)

| # | Tác phẩm (Book Title) | Tác giả | Trọng tâm chính | Mức độ Toán | Hồ sơ chi tiết |
| :-: | :--- | :--- | :--- | :---: | :---: |
| **01** | **Elementary Probability for Applications** | Rick Durrett | Nền tảng xác suất trực quan & Markov chains | Nhập môn | [👉 Xem Profile](books/01-elementary-probability-for-applications.md) |
| **02** | **Probability: Theory and Examples** (5th Ed.) | Rick Durrett | Xác suất giải tích độ đo & Martingales | Nâng cao | [👉 Xem Profile](books/02-probability-theory-and-examples.md) |
| **03** | **Mathematics for Machine Learning** | M. P. Deisenroth, A. A. Faisal, C. S. Ong | Đại số tuyến tính, Giải tích đa biến, Tối ưu hóa & 4 trụ cột ML | Trung cấp | [👉 Xem Profile](books/03-mathematics-for-machine-learning.md) |
| **04** | *Understanding Machine Learning: From Theory to Algorithms* | S. Shalev-Shwartz, S. Ben-David | Lý thuyết học máy kinh điển (PAC, VC, Rademacher, Convex) | Trung cấp - Nâng cao | *(Đang biên soạn)* |
| **05** | *Advanced Data Analysis from an Elementary Point of View* | Cosma Rohilla Shalizi | Hồi quy phi tham số, Mô hình phụ gia & Suy luận nhân quả | Thực nghiệm - Nâng cao | *(Đang biên soạn)* |
| **06** | *Algorithmic Aspects of Machine Learning* | Ankur Moitra | Phân tích thuật toán ML từ góc độ CS lý thuyết (Tensors, ICA, GMM) | Nâng cao | *(Đang biên soạn)* |
| **07** | *Mathematical Analysis of Machine Learning Algorithms* | Tong Zhang | Bất đẳng thức tập trung, Online Learning, Bandits & RL Theory | Rất nâng cao | *(Đang biên soạn)* |
| **08** | *Machine Learning with Neural Networks: An Introduction for Scientists and Engineers* | Bernhard Mehlig | Mạng neural qua lăng kính Vật lý thống kê & Động lực học | Nâng cao | *(Đang biên soạn)* |
| **09** | *The Principles of Deep Learning Theory* | D. A. Roberts, S. Yaida, B. Hanin | Lý thuyết Deep Learning tiếp cận qua Vật lý lý thuyết (EFT, NTK) | Chuyên sâu | *(Đang biên soạn)* |
| **10** | *Deep Learning on Graphs* | Yao Ma, Jiliang Tang | Biểu diễn học & Mạng neural trên đồ thị (GNN, GCN, GAT) | Trung cấp - Nâng cao | *(Đang biên soạn)* |

---

## 🗺️ Bản đồ quan hệ & Hệ sinh thái (Ecosystem Taxonomy)

Mười tác phẩm trong thư viện không đứng độc lập mà bổ trợ lẫn nhau, tạo thành 4 trụ cột học thuật hoàn chỉnh:

```
[1. XÁC SUẤT & TOÁN NỀN TẢNG]
  ├── 01. Elementary Probability for Applications (Trực giác xác suất & Markov)
  ├── 02. Probability: Theory and Examples (Lý thuyết xác suất độ đo chuẩn mực)
  └── 03. Mathematics for Machine Learning (Đại số tuyến tính, Giải tích & Tối ưu)
             │
             ▼
[2. THỐNG KÊ THỰC NGHIỆM & DỮ LIỆU]
  └── 05. Advanced Data Analysis from an Elementary Point of View (Phi tham số & Nhân quả)
             │
             ▼
[3. LÝ THUYẾT HỌC MÁY & KHOA HỌC MÁY TÍNH THUẬT TOÁN]
  ├── 04. Understanding Machine Learning (PAC-learning, VC-dim & Tổng quát hóa)
  ├── 06. Algorithmic Aspects of Machine Learning (Phân rã ma trận/tensor từ góc độ CS)
  └── 07. Mathematical Analysis of ML Algorithms (Tập trung xác suất, Bandits & RL Theory)
             │
             ▼
[4. DEEP LEARNING CƠ CHẾ & HÌNH HỌC]
  ├── 08. Machine Learning with Neural Networks (Vật lý thống kê của mạng neural)
  ├── 09. The Principles of Deep Learning Theory (Effective Field Theory cho Deep Learning)
  └── 10. Deep Learning on Graphs (Hình học đồ thị & Cấu trúc phi Euclid)
```

---

## 🧭 Gợi ý lộ trình linh hoạt (Flexible Exploration Pathways)

Không có một thứ tự duy nhất bắt buộc cho tất cả mọi người. Tùy thuộc vào xuất phát điểm và mục tiêu cá nhân, bạn có thể lựa chọn lộ trình phù hợp:

1. **Lộ trình "Thực chiến & Nền tảng ứng dụng" (Applied & Modeling Pathway)**:
   `01` (Trực giác xác suất) ➔ `03` (Toán cho ML) ➔ `05` (Phân tích dữ liệu & Nhân quả) ➔ `10` (Học sâu trên đồ thị).
2. **Lộ trình "Lý thuyết Học máy chuẩn mực" (Theoretical ML Pathway)**:
   `01` ➔ `03` ➔ `04` (Lý thuyết học thống kê cơ bản) ➔ `06` (Góc nhìn thuật toán CS) ➔ `07` (Lý thuyết nâng cao & Bandits/RL).
3. **Lộ trình "Cơ chế Vật lý & Deep Learning chuyên sâu" (Physics-of-AI Pathway)**:
   `01` ➔ `02` (Đo lường & Quá trình ngẫu nhiên) ➔ `08` (Mô hình Hopfield & Boltzmann) ➔ `09` (Lý thuyết trường hiệu dụng cho mạng sâu).

---

## ⚖️ Tuyên bố Bản quyền & Chuẩn mực Kiểm chứng (Policy & Verification Standard)

* **Chính sách Không vi phạm Bản quyền (No-Piracy Policy)**: Repository này tôn trọng tuyệt đối quyền tác giả và nhà xuất bản. Không có bất kỳ tệp sách hay PDF nào được lưu trữ hay commit trong kho mã nguồn.
* **Liên kết chính thống**: Toàn bộ liên kết trong các file profile đều trỏ tới trang phát hành chính thức của Nhà xuất bản (Cambridge University Press, MIT Press, v.v.) hoặc trang học thuật cá nhân được tác giả công khai hợp pháp.
* **Phân định thông tin**:
  * **Verified Bibliographic Information**: Thông tin thư mục, ISBN, tác giả và cấu trúc chương mục được đối chiếu trực tiếp từ nguồn xuất bản chính thống, không suy diễn hoặc hallucinate.
  * **Repository's Interpretation / Assessment**: Các phần đánh giá, phân loại đối tượng và gợi ý lộ trình là góc nhìn tổng hợp học thuật độc lập của repository nhằm hỗ trợ cộng đồng tự học.

---

## 📄 License & Copyright

```text
Copyright © [YEAR] [COPYRIGHT HOLDER]
```

* **Giấy phép cho nội dung gốc (Original Content)**: Toàn bộ nội dung nguyên bản do repository tự biên soạn — bao gồm `README.md`, các hồ sơ sách (`books/*.md`), các phần tóm tắt khái niệm, mô tả tổng quan, đánh giá giám tuyển độc lập, tài liệu điều hướng và cấu trúc metadata — được phát hành theo giấy phép **[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE)**.
* **Điều kiện tái sử dụng**: Bạn được tự do chia sẻ (sao chép, phân phối) và điều chỉnh (chuyển thể, phát triển tiếp) các nội dung gốc của repository này cho bất kỳ mục đích nào, với điều kiện bắt buộc là **phải giữ nguyên thông tin ghi công (Attribution)** phù hợp và dẫn liên kết tới giấy phép CC BY 4.0.
* **Bảo lưu quyền của bên thứ ba (Third-Party Rights Exclusion)**:
  * Bản quyền của 10 cuốn sách được giới thiệu, toàn văn nội dung nguyên tác, công thức, bản thảo, tệp PDF, bản dịch, bìa sách (covers), tài liệu của nhà xuất bản, logo và nhãn hiệu thuộc về các **tác giả, nhà xuất bản hoặc chủ sở hữu bản quyền tương ứng**.
  * Repository này **không cấp phép (does NOT license)** và không tuyên bố quyền sở hữu đối với bất kỳ tác phẩm hoặc tài nguyên nào của bên thứ ba.
  * Các liên kết ngoài (External links) chỉ đóng vai trò chỉ dẫn tới nguồn phân phối chính thống/hợp pháp và **không cấu thành việc chuyển giao quyền sở hữu hoặc bản quyền** cho repository này.
  * Repository cam kết **không lưu trữ, tải lên hoặc phân phối lại (redistribute)** bất kỳ tệp PDF, bản dịch toàn văn, cover artwork hoặc tài liệu có bản quyền nào của bên thứ ba.

