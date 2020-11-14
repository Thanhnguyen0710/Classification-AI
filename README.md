# Classification-AI
Câu 1:
Em làm như hướng dẫn của bài tìm f  rồi tìm label của từng i tính max_score và label của
max_score so sách với label nếu khác thì cập nhật lại.

Câu 2:
Em sẽ sắp xếp mảng từ lớn đến bé rồi lấy ra 100 phần từ đầu tiên
cho chạy code sẽ thấy đáp là a

Câu 3
Gần giống với câu 1 nhưng khác với câu 1 là khi cập nhật thì cần 1 biến tau biến tau được
tính như công thức bài đã cho và hàm accuracy để tìm ra weights và max_acc tối ưu nhất

Câu 4
Vì mỗi số đều có cách khoảng trống khác nhau nên em Tính số lượng vùng trong lưới 
features, bằng cách gọi đệ quy 4 hướng pixArray() Có thể có 1, 2, 3 vùng, đó là 
1 feature để tăng độ chính xác

Câu 5
Em làm như hướng dẫn trong bài là tính f là trainingData[i][0]. Tính max_score và lấy
label của max_score so sánh với trainingLabels[i] nếu khác nhau thì sẽ cập nhật weights

Câu 6
Em sẽ thiết kế các feature của con pacman như: con ma gần nhất, viên năng lượng gần nhất,
số viên năng lượng còn lại, thức ăn gần nhất và số thời gian sợ còn lại của con ma
