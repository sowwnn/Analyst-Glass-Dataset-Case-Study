# prj_glass
Bài toán gom cụm bộ dữ kiệu Glass băng thư viện Sklearn
# Giới thiệu bài toán
Để hỗ trợ cho việc điều tra hiện trường của các vụ án, các điều tra viên cần phải thu thập và phân tích các mẫu kính tại hiện trường thành các nhóm khác nhau. Qua đó giúp việc điều tra trở nên thuận tiện và dễ dàng hơn.
Vì thế mục tiêu bài toán của chúng ta hôm nay là phân cụm các mẫu kính đã được thu thập. Vậy làm thế nào để chúng ta có thể phân cụm các dữ liệu? Làm thế nào để biết được các đặc trưng riêng biệt của từng loại dữ liệu?. Đó chính là những vấn đề chúng ta sẽ giải quyết mà chúng ta cần tìm câu trả lời.


## Bộ dữ liệu:
* Gôm 214 mẫu dữ liệu:
* Mỗi mẫu gồm 9 thuộc tính (loại bỏ thuộc tính phân lớp: Type) như sau:
  ●	RI : Chỉ số khúc xạ
  ●	Na : Natri
  ●	Mg : Magie
  ●	Al : Nhôm
  ●	Si : Silicon
  ●	K : Kali
  ●	Ca : Canxi
  ●	Ba : Bari
  ●	Fe : Sắt
  
  path: dataset/glass.data
  
  ## Kết quả:
* Sau khi chạy kết quả bài toán ta nhận được 3 cụm riêng biệt và có các đặc điểm sau:
  ●	Cụm 0: Độ RI cao nhất, giàu Fe và đặt biệt cao Ca
  ●	Cụm 1: Đặt biệt giàu Mg và ít Al và Ca
  ●	Cụm 2: Giàu Na, Al và Ba nhất nhưng lại ít Fe


//Sho-RC
