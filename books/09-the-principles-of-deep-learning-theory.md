# The Principles of Deep Learning Theory

> **Tác giả:** Daniel A. Roberts, Sho Yaida, Boris Hanin  
> **Nhà xuất bản:** Cambridge University Press (2022)  
> **Trọng tâm học thuật:** Lý thuyết trường hiệu dụng (EFT) cho Deep Learning: Giới hạn vô hạn chiều NTK, khai triển 1/N & cơ chế học biểu diễn  

---

## 1. Thông tin thư mục (Bibliographic Information)

| Thuộc tính | Chi tiết xác thực |
| :--- | :--- |
| **Tác giả** | Daniel A. Roberts (MIT), Sho Yaida (Meta AI), Boris Hanin (Princeton University) |
| **Nhà xuất bản** | Cambridge University Press (2022) |
| **ISBN** | 978-1-009-00234-9 (Hardback) |
| **Liên kết chính thức** | [Trang arXiv chính thức](https://arxiv.org/abs/2106.10165) |
| **Bản PDF miễn phí** | [Tải PDF chính thức (arXiv:2106.10165)](https://arxiv.org/pdf/2106.10165) |
| **Quyền truy cập** | Bản thảo hoàn chỉnh của cuốn sách được các tác giả phát hành mở trên arXiv. |

---

## 2. Tóm tắt cốt lõi (Executive Summary)

*The Principles of Deep Learning Theory* phát triển một lý thuyết định lượng nguyên lý đầu (first-principles theoretical framework) cho mạng neural sâu bằng ngôn ngữ Lý thuyết trường hiệu dụng (Effective Field Theory - EFT) từ vật lý năng lượng cao. Tác phẩm đi xa hơn giới hạn chiều rộng vô hạn ($N \to \infty$) bằng phép khai triển nhiễu loạn $1/N$ để giải thích chính xác cơ chế biểu diễn đặc trưng (feature learning) và động lực học huấn luyện.

---

## 3. Cấu trúc nội dung (What's Inside)

| Phần / Chương | Tên chủ đề | Trọng tâm học thuật |
| :-: | :--- | :--- |
| **Part I** | Kiến trúc & Phân phối tiên nghiệm | Khởi tạo trọng số ngẫu nhiên, truyền tín hiệu (signal propagation) qua các lớp sâu, phương trình điểm cố định và trạng thái tới hạn động học. |
| **Part II** | Giới hạn chiều rộng vô hạn ($N \to \infty$) | Quá trình Gaussian mạng neural (NNGP), Neural Tangent Kernel (NTK), chế độ huấn luyện lười (lazy training regime) và sự đóng băng biểu diễn. |
| **Part III** | Hiệu chỉnh chiều rộng hữu hạn ($1/N$) | Khai triển nhiễu loạn $1/N$, hàm tương quan 4 điểm (4-point correlators), tương tác giữa các nơ-ron và cơ chế học biểu diễn thực thụ. |
| **Part IV** | Động lực học huấn luyện & Tối ưu | Dòng chảy gradient (Gradient flow), biến đổi biểu diễn qua chiều sâu mạng và các nguyên lý xác định tỷ lệ chiều sâu / chiều rộng tối ưu. |

---

## 4. Định hướng người đọc (Reading Orientation)

| Tiêu chí | Chi tiết |
| :--- | :--- |
| **Độc giả phù hợp** | Nhà nghiên cứu lý thuyết deep learning, nhà vật lý lý thuyết chuyển sang AI muốn giải thích "tại sao mạng sâu hoạt động" bằng công thức định lượng. |
| **Tiên quyết** | Đại số tuyến tính, giải tích đa biến, xác suất giải tích, tư duy vật lý lý thuyết (phép khai triển chuỗi, tích phân Feynman). |
| **Trọng tâm ứng dụng AI/ML** | Cung cấp công thức định lượng chính xác để thiết lập siêu tham số tối ưu (tỷ lệ độ sâu/độ rộng, scale phương sai khởi tạo) mà không cần thử sai ngẫu nhiên. |
