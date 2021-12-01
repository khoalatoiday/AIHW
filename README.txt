B1: Cài môi trường:

C1: Cài jupyter notebook (hiện tại t đang dùng anaconda3 để load jupyter notebook, mọi người có thể chọn IDE mình yêu thích)

C2: Cài python(tải python.exe) và thiết lập môi trường chạy trên Visual Studio Code hoặc sublime text
-------------------------------------------------------------------------
B2: Cài thư viện:
Mở cmd của python: 
Cài pip: python(hoặc py) -m pip install --upgrade pip
Cài các thư viện sau: tensorflow, keras, numpy, opencv-python,matplotlib, scipy

syntax: pip install numpy ,...
-------------------------------------------------------------------------
Mở 2 demo 

demo 1: train với model CNN: chỉ cần chạy file test.ipynb

demo 2: train với model SVM: 

+ chạy file Train Data trước (chạy 2 lần và lưu vào 2 file with_mask.npy, without_mask.npy
+ chạy file Train Model

Hiện tại mình sẽ không dùng google colab do dataset quá lớn không thể ném lên đó được. Muốn dùng google colab thì phải đưa dataset lên mạng. Ai biết thì có thể ném lên nhé :))) rồi nhúng đường link dataset vào google colab chạy cũng được đỡ phải cài mấy bước môi trường các thứ :v. Cái này t chưa tìm hiểu 

t đã cố gắng commend code mn đọc rồi có thể tìm doc để đọc thêm:

Nhìn qua thì có thể chia 4 phần như sau

- Train model CNN và mô hình CNN
- Giải thích thuật toán hair-feature like của viola jones algorithm (chỉ giải thích, không code do khá nặng)
- Load model và sử dụng hair-feature (cái này có sẵn rồi chỉ cần nhúng vào là xong). Đoạn này sẽ giải thích cơ chế real-camera để lấy ảnh
- Ứng dụng và tự train lại model với dataset của chính mình(demo 2): giải thích phần tự build data và đánh giá độ chính xác của 2 dataset
Trước mắt thì t cứ mở bát phần 1 nhé, do trong trường hợp nếu chỉ cần 1 người nói. Mn cứ xem qua rồi t2 hoặc t3 call 

Thân ái :))


