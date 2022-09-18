------------------------------------------------------------------
Career.csv: Dữ liệu về nghề nghiệp gồm có 14 tiêu đề nghề nghiệp.
------------------------------------------------------------------
Taxonomy: Phân loại lớn nhất của hệ thống dựa trên Minor Group của tiêu phân loại nghề nghiệp SOC.

Industry: Phân loại mức 2 của hệ thống dựa trên Broad Occupations của tiêu phân loại nghề nghiệp SOC.

Career: Tiêu đề nghề nghiệp

Tool/Platform/Framework/Programing Language/Knowledge: Các năng lực thuộc lớp Tool, các đơn vị được ngăn cách bởi dấu phẩy (,).

------------------------------------------------------------------
Course.csv: Dữ liệu về khóa học trực tuyến gồm có 999 khóa.
------------------------------------------------------------------
Name: Tên khóa học.

Link: Đường dẫn đến khóa học xác định ra một khóa học cụ thể.

Rating: Đánh giá trung bình về một khóa học trực tuyến trên nền tảng web của nó.

Enroll: Số lượng học viên tham giá của một khóa học trực tuyến được thống kê trên nền tảng web của nó.

Instructor: Giảng viên hướng dẫn của khóa học.

Time: Thời gian ước tính hoàn thành khóa học.

Level: Mức độ khó của khóa học đối với người học.

Fee: Học phí của khóa học.

Program: Chương trình mà khóa học đó thuộc về.

Subtitle: Phụ đề hiện có của khóa học.

Subject: Chủ đề khóa học (được lấy theo danh mục của nó trên nền tảng mà nó thuộc về).

Organization: Tổ chức hỗ trợ/cung cấp khóa học.

Tool/Platform/Framework/Programing Language/Knowledge: Các năng lực thuộc lớp Tool, các đơn vị được ngăn cách bởi dấu phẩy (,).

------------------------------------------------------------------
Chú thích cho các lớp năng lực thuộc IT_Technique
ents: thực thể

Competency: Cột chứa các năng lực đầu ra 
(dùng trong mqh Course <--TEACH_LO--> Competency)

Competency_P: Cột chứa các năng lực là yêu cầu đầu vào (prerequisite) 
(dùng trong mqh Course <--REQUIRE_LO--> Competency)
------------------------------------------------------------------
Knowledge có 1499 ents: Các lý thuyết bao gồm tập hợp các định lý, chân lý và cơ sở khoa học để góp phần hình thành các kỹ năng nghề nghiệp khác.

Programing Language có 157 ents: Ngôn ngữ lập trình nói chung - yếu tố cơ bản nhất tạo nên chương trình máy tính và tương tác với các hệ
thống máy tính. Ngôn ngữ lập trình ở đây bao gồm cả ngôn ngữ lập trình, ngôn ngữ đánh dấu, ngôn ngữ truy vấn dữ liệu,...

Framework có 267 ents: Một khung chương trình hoặc thư viện sẵn có cho một ngôn ngữ lập trình hoặc một kiến trúc.

Platform có 227 ents: Nền tảng/Dịch vụ/Môi trường cung cấp cơ sở
để xây dựng các ứng dụng/phần mềm hoặc cung cấp một nhóm các công cụ
tích hợp là giải pháp phục vụ cho một nhóm mục đích nghề nghiệp.

Tool có 875 ents: Các phần mềm/công cụ phần mềm có mục đích sử dụng 
nhất định và có khả năng phục vụ cho một kỹ năng/một mục đích nghề
nghiệp.