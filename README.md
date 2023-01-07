# ANN - Artificial Neural Network

[**Chi tiết bài viết**](...)

**Dưới đây là tóm tắt lí thuyết**

## 1. Giới thiệu
+ Các neuron sinh học nhận các xung điện ngắn (short electrical impulses) gọi là tín hiệu (signal) từ các neuron khác thông qua các khớp thần kinh (synapses) này. Khi một neuron nhận đủ số lượng tín hiệu từ các tế bào thần kinh khác trong vòng vài phần nghìn giây, nó phát ra tín hiệu riêng của nó.
+ Vì vậy, các tế bào thần kinh sinh học (biological neurons) có vẻ hoạt động theo một cách khá đơn giản, nhưng chúng được tổ chức trong một mạng lưới khổng lồ hàng tỷ tế bào thần kinh, mỗi tế bào thần kinh thường kết nối với hàng nghìn tế bào thần kinh khác. Tính toán phức tạp cao có thể được thực hiện bởi một mạng lưới rộng lớn các neuron khác đơn giản.

### Tính toán logic với Neuron
+ Warren McCulloch và Walter Pitts đã đề xuất một mô hình neuron sinh học rất đơn giản, sau này được gọi là neuron nhân tạo: nó có một hoặc nhiều đầu vào (input) nhịn phân (on/off) và một đầu ra (output) nhịn phân.
+ Các tế bào thần kinh nhân tạo chỉ đơn giản là kích hoạt đầu ra của nó khi có nhiều hơn một số đầu vào nhất định của nó đang hoạt động.
+ McCulloch và Pitts cho thấy rằng ngay cả với một mô hình đơn giản như vậy, có thể xây dựng một mạng lưới tế bào thần kinh nhân tạo tính toán bất kỳ một cách hợp lý nếu chúng ta muốn.

## 2. Artificial Neural Networks (ANN)
### 2.2 Giới thiệu ANN
+ Mạng thần kinh nhân tạo (ANN) hoặc hệ thống kết nối (connectionist systems) là hệ thống máy tính lấy cảm hứng từ mạng thần kinh sinh học tạo thành bộ não động vật.
+ Bản thân mạng neuron không phải là một thuật toán mà là một khuôn khổ cho nhiều thuật toán Machine Learning khác nhau làm việc cùng nhau và xử lý các dữ liệu đầu vào phức tạp.
+ Các hệ thống như vậy "học" để thực hiện các công việc (task) bằng cách xem xét các mẫu, thường không được lập trình với bất kỳ quy tắc cụ thể nào.
> **Ví dụ**, trong nhận dạng hình ảnh (image recognition), nó có thể học cách xác định hình ảnh có chứa "cat" bằng cách phân tích các mẫu hình ảnh đã được gắn nhãn thủ công là "cat" hoặc "no cat" và sử dụng kết quả để xác định có "cat" hay không trong các hình ảnh. Chúng làm điều này mà không cần có bất kỳ kiến thức nào trước về "cat", ví dụ như: mèo có lông, đuôi, râu và khuôn mặt giống như con mèo. Thay vào đó, chúng tự động tạo ra các đặc điểm nhận dạng từ tài liệu học tập mà chúng xử lý.

+ ANN dựa trên một tập hợp các đơn vị (unit) kết nối hoặc các nút (node) được gọi là neuron nhân tạo (artificial neurons), mô hình lỏng lẻo các tế bào thần kinh trong não sinh học.
+ Mỗi kết nối, giống như các khớp thần kinh (synapses) trong não sinh học (biological brain), có thể truyền tín hiệu từ một neuron nhân tạo này sang một neuron nhân tạo khác.
+ Một neuron nhân tạo nhận tính hiệu có thể xử lý và sau đó báo hiệu cho các tế bào thần kinh nhân tạo kết nối với nó.
+ Trong triển khai ANN chung, tín hiệu tại một kết nối giữa các neuron nhân tạo là một số thực (real number) và đầu ra (output) của mỗi neuron nhân tạo được tính toán bởi một số hàm phi tuyến (non-linear function) của tổng các đầu vào (input) của nó.

### 2.2 Khi nào sử dụng ANN
+ Xử lý dữ liệu phi cấu trúc (unstructured data)
+ Không bắt buộc phải diễn giải kết quả
+ Có nhiều thuận lợi với các cấu trúc đã biết

**Ví dụ:**
+ Hình ảnh là dữ liệu phi cấu trúc
+ Không quan tâm đến việc tạo sao mạng lại biết đó là chó hay mèo
+ Thuận lợi với cấu trúc mạng CNN

### 2.3 Ứng dụng
+ Mục tiêu ban đầu của phương pháp ANN là giải quyết vấn đề theo cách mà bộ não con người sẽ làm. Tuy nhiên, theo thời gian, ANN chuyển sang thực hiện các nhiệm vụ cụ thể khác nhau, dẫn đến sai lệch so với sinh học.
+ ANN đã được sử dụng trên nhiều nhiệm vụ khác nhau, bao gồm computer vision, speech recognition, machine translation, social network filtering, playing board & video games, medical diagnosis.
+ ...
