---
layout: post
title: Kiến thức toán học cơ bản để làm việc với Deep learning
category: deep-learning
tags: neural-networks machine-learning deep-learning
---

Trước khi bắt đầu vào việc học mạng nơ-ron và deep learning, chúng ta cũng cần chuẩn bị một số kiến thức nền tảng của toán học cần thiết. Một vài chủ đề toán học quan trọng để chúng ta có thể hiểu được các chủ đề trong phương pháp học nhiều tầng **Deep learning**.

ĐẠI SỐ TUYẾN TÍNH
=================

Đại số tuyến tính bao gồm các dạng liên tục chứ không hoàn toàn là Toán học rời rạc, nhiều người làm khoa học máy tính có rất ít kinh nghiệm với nó. Hiểu biết về đại số tuyến tính là một kỹ năng cần thiết để có thể hiểu được và làm việc được với các thuật toán **Machine learning**, đặc biệt là với **Deep learning**.

Nghiên cứu về Đại số tuyến tính liên quan tới các đối tượng toán học sau:

1. **Đại lượng vô hướng (Scalar)**: Đại lượng (số) vô hướng là đại lượng được mô tả hoàn toàn chỉ bằng độ lớn. Mô tả bằng một con số mà thôi, không hơn không kém. Ví dụ như tốc độ, thể tích, khối lượng, nhiệt độ, công suất, thời gian, ... Chúng ta viết các đại lượng vô hướng bằng chữ cái không in đậm, có thể viết hoa, ví dụ: $$ \(x_1, N, y, k\) $$
2. **Vector**: Vector là một mảng (1-D) chứa các phần tử của nó là dãy các số vô hướng. Các số này được sắp xếp theo một trật tự và chúng ta có thể xác định các số này bằng chỉ số thứ tự của nó. Thường được ký hiệu bằng chữ cái không viết hoa in đậm, ví dụ: $$ \(\mathbf{y}, \mathbf{x}1 \) $$
3. **Ma trận**: Ma trận là một mảng 2 chiều (2-D), mỗi phần tử của nó được xác định bởi 2 chỉ số. Thường được ký hiệu bởi chữ cái viết hoa và in đậm, ví dụ: $$ \(\mathbf{A, X, Y, W} \) $$
4. **Tensor**: Ten-xơ là đối tượng hình học miêu ta quan hệ tuyến tính giữa các đại lượng `Vector`, `Vô hướng`, và các `ten-xơ` với nhau. Theo định nghĩa thì `Vector` và `Vô hướng` cũng là ten-xơ. Bậc (hay *hạng*) của một ten-xơ bằng số chiều của mảng cần để biểu diễn nó, hay tương đương với chỉ số cần để đánh dấu các thành phần của mảng. Đại lượng `vô hướng` là ten-xơ hạng **0**, ...


Liên kết tham khảo
==================

* [Basic Mathematics for Deep Learning](https://medium.com/towards-data-science/deep-learning-basic-mathematics-for-deep-learning-a82981e95e3b)