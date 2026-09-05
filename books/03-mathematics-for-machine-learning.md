# Mathematics for Machine Learning

> **Tác giả:** Marc Peter Deisenroth, A. Aldo Faisal, Cheng Soon Ong  
> **Nhà xuất bản:** Cambridge University Press  
> **Lĩnh vực:** Toán học nền tảng cho Trí tuệ nhân tạo & Học máy  

---

## 1. Verified Bibliographic Information (Thông tin xác thực)

| Thuộc tính | Chi tiết xác thực |
| :--- | :--- |
| **Tựa đề đầy đủ** | *Mathematics for Machine Learning* |
| **Tác giả** | Marc Peter Deisenroth, A. Aldo Faisal, Cheng Soon Ong |
| **Đơn vị công tác (Affiliation)** | • Marc Peter Deisenroth: University College London (UCL) & Imperial College London<br>• A. Aldo Faisal: Imperial College London<br>• Cheng Soon Ong: Data61, CSIRO & Australian National University (ANU) |
| **Nhà xuất bản** | Cambridge University Press |
| **Năm xuất bản** | 2020 |
| **ISBN-13** | 978-1-108-45514-5 (Paperback) \| 978-1-108-47014-8 (Hardback) \| 978-1-108-67993-0 (eBook) |
| **DOI chính thức** | [10.1017/9781108679930](https://doi.org/10.1017/9781108679930) |
| **Trang chủ chính thức của sách** | [mml-book.com](https://mml-book.com) |
| **Trang chính thức của NXB** | [Cambridge Higher Education - MML](https://www.cambridge.org/highereducation/books/mathematics-for-machine-learning/0DEE2C33E689C83B4B27CE92B60EA479) |
| **Mã nguồn & Notebooks chính thức** | [GitHub - mml-book/mml-book.github.io](https://github.com/mml-book/mml-book.github.io) |
| **Tình trạng bản quyền & Truy cập** | Bản in và eBook thương mại do Cambridge University Press phát hành. Nhóm tác giả cung cấp bản PDF hoàn chỉnh miễn phí và hợp pháp trên website chính thức [mml-book.com](https://mml-book.com) theo giấy phép **Creative Commons CC BY-NC-ND 4.0** (Ghi công - Phi thương mại - Không phái sinh). |

---

## 2. Executive Summary (Tóm tắt cốt lõi)

*Mathematics for Machine Learning* là tác phẩm cầu nối toàn diện và hiện đại nhất giữa các phân ngành toán học nền tảng với các thuật toán học máy kinh điển. Cuốn sách giải quyết triệt để vấn đề "học toán nhưng không biết dùng ở đâu trong ML" bằng cách chia cấu trúc thành hai phần đối xứng: Phần I trang bị 6 công cụ toán học cốt lõi (Đại số tuyến tính, Hình học giải tích, Phân rã ma trận, Giải tích vector, Xác suất & phân phối, Tối ưu hóa liên tục); Phần II lập tức áp dụng trọn vẹn các công cụ đó để xây dựng từ con số không 4 trụ cột học máy lớn (Hồi quy tuyến tính, PCA, GMM và SVM).

---

## 3. What's Inside (Cấu trúc chương mục xác thực)

Cuốn sách gồm 12 chương được phân định mạch lạc thành 2 phần lớn (đối chiếu trực tiếp từ website chính thức mml-book.com và ấn bản Cambridge):

### Part I: Mathematical Foundations (Nền tảng toán học)
* **Chapter 1: Introduction and Motivation**
  * *Tầm quan trọng của Toán học trong ML*: Cách dữ liệu biến thành vector, ma trận và không gian đặc trưng.
  * *Sự khác biệt giữa góc nhìn đại số và hình học*: Trực giác không gian nhiều chiều.
* **Chapter 2: Linear Algebra**
  * *2.1 Hệ phương trình tuyến tính*: Khử Gauss-Jordan và không gian nghiệm.
  * *2.2 Không gian vector, không gian con*: Tính độc lập tuyến tính, hệ cơ sở và số chiều (Dimension).
  * *2.3 Hạng ma trận (Rank) & Ánh xạ tuyến tính*: Ma trận biểu diễn biến đổi tuyến tính.
  * *2.4 Không gian Affine*: Phép tịnh tiến và biểu diễn hình học.
* **Chapter 3: Analytic Geometry**
  * *3.1 Chuẩn (Norms) & Tích vô hướng (Inner Products)*: Khoảng cách hình học và năng lượng vector.
  * *3.2 Góc và Tính trực giao*: Hệ cơ sở trực chuẩn (Orthonormal basis) và quy trình Gram-Schmidt.
  * *3.3 Phép chiếu trực giao (Orthogonal Projections)*: Chiếu lên không gian con và ma trận chiếu.
  * *3.4 Phép quay trong không gian*: Ma trận trực giao và nhóm quay.
* **Chapter 4: Matrix Decompositions**
  * *4.1 Định thức và Vết (Trace)*: Thể tích song song và bất biến biến đổi.
  * *4.2 Trị riêng và Vector riêng (Eigenvalues & Eigenvectors)*: Phương trình đặc trưng và ý nghĩa hình học.
  * *4.3 Phân rã Cholesky*: Phân rã ma trận đối xứng xác định dương.
  * *4.4 Phân rã trị riêng (Eigendecomposition)*: Chéo hóa ma trận đối xứng.
  * *4.5 Phân rã giá trị suy biến (Singular Value Decomposition - SVD)*: Cấu trúc hình học của SVD và xấp xỉ ma trận hạng thấp (Eckart-Young-Mirsky Theorem).
* **Chapter 5: Vector Calculus**
  * *5.1 Đạo hàm đơn biến & Đạo hàm riêng*: Gradient của hàm vô hướng nhiều biến.
  * *5.2 Gradient của hàm nhận giá trị vector & Ma trận Jacobian*: Quy tắc chuỗi nhiều biến (Chain rule).
  * *5.3 Gradient theo ma trận*: Đạo hàm của hàm vết và dạng toàn phương.
  * *5.4 Lan truyền ngược (Backpropagation) & Tự động vi phân (Autodiff)*: Đồ thị tính toán trong mạng neural.
  * *5.5 Đạo hàm bậc cao & Ma trận Hessian*: Độ cong và tối ưu hóa bậc hai.
  * *5.6 Tuyến tính hóa & Khai triển Taylor*: Xấp xỉ địa phương.
* **Chapter 6: Probability and Distributions**
  * *6.1 Xây dựng không gian xác suất*: Xác suất rời rạc và liên tục.
  * *6.2 Quy tắc tổng, quy tắc nhân & Định lý Bayes*: Cập nhật niềm tin trong không gian tham số.
  * *6.3 Thống kê mô tả*: Kỳ vọng, phương sai, hiệp phương sai và ma trận hiệp phương sai.
  * *6.4 Phân phối Gaussian*: Phân phối chuẩn đa biến, tính chất biên duyên và có điều kiện.
  * *6.5 Tính liên hợp (Conjugacy) & Họ phân phối mũ (Exponential Family)*.
  * *6.6 Biến đổi biến ngẫu nhiên*: Định lý đổi biến và ma trận Jacobian tích phân.
* **Chapter 7: Continuous Optimization**
  * *7.1 Tối ưu hóa không ràng buộc*: Gradient Descent và lựa chọn Learning Rate.
  * *7.2 Tối ưu hóa có ràng buộc*: Nhân tử Lagrange và bài toán đối ngẫu Karush-Kuhn-Tucker (KKT).
  * *7.3 Tối ưu hóa lồi (Convex Optimization)*: Tính chất hàm lồi và sự tồn tại nghiệm tối ưu toàn cục.

---

### Part II: Central Machine Learning Problems (Bốn trụ cột Machine Learning)
* **Chapter 8: When Models Meet Data**
  * *Khung làm việc thống kê*: Dữ liệu huấn luyện, mô hình tham số và hàm mất mát.
  * *Ước lượng hợp lý cực đại (MLE)* và *Ước lượng cực đại hậu nghiệm (MAP)*.
  * *Giảm thiểu rủi ro thực nghiệm (Empirical Risk Minimization - ERM)* và hiện tượng Overfitting.
* **Chapter 9: Linear Regression**
  * *Xây dựng bài toán từ nguyên lý đầu tiên*: Phương pháp bình phương tối thiểu (Ordinary Least Squares).
  * *Nghiệm giải tích*: Phương trình chuẩn tắc (Normal Equations) qua đạo hàm ma trận.
  * *Hồi quy tuyến tính Bayes (Bayesian Linear Regression)*: Phân phối hậu nghiệm cho trọng số và dự báo có khoảng tin cậy.
* **Chapter 10: Dimensionality Reduction with Principal Component Analysis (PCA)**
  * *Góc nhìn cực đại hóa phương sai (Maximum Variance Perspective)*.
  * *Góc nhìn cực tiểu hóa sai số tái tạo (Minimum Reconstruction Error Perspective)*.
  * *Thuật toán PCA hoàn chỉnh thông qua Eigendecomposition và SVD*.
* **Chapter 11: Density Estimation with Gaussian Mixture Models (GMM)**
  * *Mô hình biến ẩn (Latent Variable Models)* và phân phối hỗn hợp Gaussian.
  * *Bế tắc của MLE nghiệm tường minh*: Đạo hàm của tổng logarit.
  * *Thuật toán Expectation-Maximization (EM)*: Bước E (kỳ vọng gán cụm) và Bước M (cập nhật tham số).
* **Chapter 12: Classification with Support Vector Machines (SVM)**
  * *Siêu phẳng phân tách biên cực đại (Maximum Margin Separator)*.
  * *Bài toán SVM gốc (Primal formulation)*: Thiết lập điều kiện KKT.
  * *Bài toán SVM đối ngẫu (Dual formulation)*: Tối ưu hóa dạng toàn phương với ràng buộc.
  * *Thủ thuật hạt nhân (Kernel Trick)*: Ánh xạ vào không gian vô hạn chiều và định lý Mercer.

---

## 4. Reading Orientation & Target Audience (Định hướng người đọc)

### Chân dung độc giả phù hợp
* **Người học Machine Learning muốn vượt qua mức "gọi hàm thư viện"**: Muốn hiểu cặn kẽ bản chất toán học đằng sau từng dòng code `fit()` và `predict()`.
* **Kỹ sư AI / Data Scientist**: Cần một cuốn sổ tay toán học tra cứu nhanh các công thức đạo hàm ma trận, phân rã SVD và tối ưu hóa lồi.
* **Sinh viên Đại học ngành CNTT, Toán tin, Khoa học dữ liệu**: Chuẩn bị nền tảng toán học đồng bộ cho các khóa học chuyên sâu về Computer Vision, NLP hoặc Deep Learning.

### Kiến thức tiên quyết (Prerequisites)
* Toán phổ thông vững chắc (đại số cơ bản, giải tích 1 biến).
* Khả năng tư duy hình học và không gian.
* Không đòi hỏi kiến thức trước về Machine Learning (sách tự định nghĩa từ đầu trong Chương 8).

### Vai trò trong hệ thống tri thức AI/ML
1. **Khung từ vựng toán học chung**: Cung cấp ngôn ngữ chuẩn hóa (Matrix calculus, SVD, Lagrange multipliers) được sử dụng trong 100% các bài báo khoa học và mô hình AI hiện đại.
2. **Làm sáng tỏ "hộp đen" thuật toán**: Giải thích tại sao PCA lại là bài toán trị riêng, tại sao Ridge Regression chính là MAP với tiên nghiệm Gaussian, và tại sao SVM lại biến thành bài toán quy hoạch toàn phương đối ngẫu.

---

## 5. Repository's Assessment & Ecosystem Placement (Đánh giá độc lập)

> [!NOTE]
> **Vị trí trong bộ sưu tập 10 cuốn:**  
> Đây là **Trung tâm điều phối nền tảng (Level 2 - Core Engine)**. Hầu như mọi cuốn sách lý thuyết và ứng dụng nâng cao trong repo đều giả định người đọc đã nắm vững các kiến thức trong cuốn sách này.

* **Điểm mạnh vượt trội**:
  * Đồ họa minh họa hình học trực quan xuất sắc, giải thích trực giác bản chất ma trận và gradient.
  * Tác giả cung cấp toàn bộ code Python / Jupyter Notebooks trên GitHub đồng hành cùng sách.
  * Tính thực dụng rất cao: không đưa vào các chứng minh thuần lý thuyết không ứng dụng trong ML.
* **Giới hạn**: Không bao quát các mô hình Deep Learning phức tạp (Transformer, Diffusion) hay các bài toán học tăng cường (RL); đó là nhiệm vụ của các cuốn sau.
* **Lộ trình kết nối khuyến nghị**:
  * Bắt đầu song song hoặc ngay sau `01-elementary-probability-for-applications.md`.
  * Sau khi hoàn thành Part I và II:
    * Nếu muốn nghiên cứu **Bảo đảm lý thuyết, Cận sai số & Tính tổng quát hóa**: Đọc tiếp `04-understanding-machine-learning.md`.
    * Nếu muốn làm chủ **Kỹ thuật phân tích dữ liệu thực tế, Hồi quy phi tham số & Mô hình nhân quả**: Đọc tiếp `05-advanced-data-analysis.md`.
    * Nếu muốn mở rộng sang **Đồ thị và Cấu trúc quan hệ**: Đọc tiếp `10-deep-learning-on-graphs.md`.
