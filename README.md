# Reflection-modul2-NgocTD<br>


<h1>SAU KHI KẾT THÚC MODUL 2 </h1> 
MỤC TIÊU PHẢI ĐẠT ĐƯỢC :<br>
+Thành thạo PHP <br>
+Vẽ được UML cho bài code<br>
+Thuần thục lập trình hướng đối tượng (oop) <br>
+Thiết kế được Cơ Sở Dữ Liệu và sử dụng được SQL-mySQL<br>
+Phát triển case study là 1 PHP WEB  bán đồ chơi trẻ em xịn bằng 35% shopee.
<br>
<br>
------------------------------------------------------
<br>
<br>
<h1>HÀNH ĐỘNG ĐỂ ĐẠT ĐƯỢC MỤC TIÊU TRÊN</h1>
<br>
<br>
+ Mỗi bài code vẽ UML để giải<BR>
+ Ngồi bàn 1 mỗi khi học lỹ thuyết để tiếp thu chuẩn chỉ<br>
+ Đi hỏi bài ngay khi không tự giải quyết được ( sau thời gian tìm tòi )<br>
+ Time box thời gian khi học tại nhà 4hours/day (nhiều hơn rất t)ốt<br>
+ Thứ 7 lên CodeGym học với các anh <br>
+ Ngủ đủ 6hours/day <br>
+ Giảm thời gian xem youtube (không liên quan đến việc học) xuống 45min <br>
<br>
<br>
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++
<br>
<br>
<br>
<br>


































































<h1>Buổi 1 ngày 25-1-2021</h1>
Hôm nay đã học được : <br>
Lamp là gì , hiểu được vòng chạy từ client qua server đến web server tiếp tục gửi về cho application server, application server lấy dữ liệu từ CSDL và trả về web server, web server response lại cho cl <br>
Giao thức : cách thức giao tiếp giữa client và server<br>
Web tĩnh là web được fix cứng người dùng không tương tác trực tiếp với web được,thêm tương tác trực tiếp giữa người dùng với web thì web sẽ thành web tĩnh  <br>
<br>
<br>
<br>
<br>
<br>
<br>---------------------------------------------------------------------------------------------<br>

<br>
<br>
<br>
<h1>Buổi 2 ngày 26-1-2021</h1>
<br>
<br>
Hôm nay hạc được :<br>
Chèm 1 file PHP a vào 1 file PHP b với Require / include  
<br> phân biệt 2 ông này <br>
require và include đề để đưa  1 ông file PHP a vào bên trong ông PHP b<br>
Khác nhau: Khi gặp lỗi trong quá trình thưc hiện ông require đưa ra cảnh báo lỗi và dừng luôn trương trình   còn ông include sẽ tạo ra cảnh báo và chạy trương trình đến phần bị lỗi thì dừng <br>
<br>
<b> require_once :</b> thực hiện require là thêm ông PHP a vào ông PHP b, chính vì vậy khi require lần 2(cái này do ông code quên ) tức thêm lần 2 sẽ có nhiều thứ bị trùng tiêu biểu tên hàm ---> lỗi!!! Do vậy ông require_once giúp check lần thực hiện  require_once lần 2 lần 3 đều được hiểu là đã require rồi và không thực hiện lại nữa
<br>
<br>
<b>include_once: </b> Giống ông require_one  include_once lần 2 -3 ... chỉ tính 1 lần 
<BR>
<BR>Ông nào hay quên thì xài <b>require_once</b>  và  <b>include_once</b>  để nó kiểm tra hộ !

<br>
<br>
<br>
<br>
<h4> Mảng associative</h4>
Ta dùng vòng lặp  "foreach" để duyệt mảng<br>
<b>foreach( $nameArry  as $key => $v)</b>






<Br>
<Br>
<Br>
<Br>
--------------------------------------------------------------------------------------------------
<br>
<br>
<br>
<h1>Buổi 3 ngày 27-1-2021 </h1>
<br>
<br>
<br>
Hôm nay học được:<br>
+ Access modifier là các từ khoá được sử dụng để quy định mức độ truy cập đến lớp và các thành phần của lớp

Các mức truy cập:

+ public: có thể truy cập từ bất cứ đâu<br>
+ private: các phương thức và thuộc tính chỉ được phép truy xuất trong cùng một lớp<br>
+ protected: các phương thức và thuộc tính được phép truy xuất trong cùng một lớp và ở các lớp con (kế thừa) <br>
<br>
+     __construct() vs __destruct()

Để can thiệp vào quá trình khởi tạo đối tượng, chúng ta sử dụng hàm __construct() <br>


Để can thiệp vào quá trình huỷ đối tượng, chúng ta sử dụng hàm __destruct()<br>
<br>
<br>
<br>
<br>
<br>
---------------------------------------------------------------
<br>
<br>
<br>
<h1>Buổi 4 ngày 28-1-2021</h1>
Hôm nay học được: <br>
<br>
+ Namespace (tên miền không gian) là một hình thức để đóng gói các hạng mục có liên quan lại với nhau<br> <br>
+ Trong PHP, namespace được thiết kế để giải quyết 2 vấn đề mà các tách giả của các thư viện và ứng dụng thường gặp phải khi cố gắng tạo ra các đối tượng hoặc hàm có thể tái sử dụng được<br> <br>
+ Các tên gọi bị trùng nhau giữa những lớp/hàm được tạo ra, so với các lớp/hàm có sẵn của PHP, hoặc các lớp/hàm do một người khác viết<br> <br>

