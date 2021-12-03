# Chương 1: Giới thiệu về AWSDeepRacer

## 1.1. AWSDeepRacer là gì?
- AWSDeepRacer là một trình mô phỏng đua xe 3D dựa trên đám mây, xe đua quy mô 1/18 hoàn toàn tự trị được điều khiển bằng phương pháp học tăng cường và giải đua xe toàn cầu.
- AWS cung cấp mô hình trong Amazon SageMaker và đào tạo, thử nghiệm và lặp lại một cách nhanh chóng và dễ dàng trên đường đua trong trình mô phỏng đua xe AWS DeepRacer 3D.
- Nó cung cấp cho bạn một cách thú vị và thú vị để bắt đầu với học tăng cường (RL). 
- RL là một kỹ thuật học máy (ML) tiên tiến giúp học các hành vi rất phức tạp mà không yêu cầu bất kỳ dữ liệu đào tạo được gắn nhãn nào và có thể đưa ra quyết định ngắn hạn trong khi tối ưu hóa cho mục tiêu dài hạn.

## 1.2 Học tăng cường (Reinforment Learning)

### 1.2.1 RL là gì?
- Có thể RL là một cách tiếp cận tập trung vào việc học để hoàn thành mục tiêu bằng việc tương tác trực tiếp với môi trường.
- RL giúp **agent**(ở đây là xe chúng ta muốn huấn luyện) có thể làm được **task**(nhiệm vụ ta giao như hoàn thành đường đua...) bằng cách đưa ra những **action** miễn là **maxize reward** (đạt được hiệu suất tối ưu).

![RLSample](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ku3g98430x8nn7q7snx1.gif)