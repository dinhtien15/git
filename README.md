BÁO CÁO TÌM HIỂU VỀ SERVER VÀ LINUX CƠ BẢN

1.Phần cứng máy chủ

  Phần cứng máy chủ là gì: Là các thành phần linh kiện cứng cấu tạo lên hệ thống máy chủ
  
1.2.Các thành phần

   + Bo mạch chủ,bộ vxl(CPU),bộ nhớ RAM, ổ cứng(HDD), bo điều khiển raid(RAID Controller), bộ cung cấp nguồn(PSU)

1.3.Server là gì?

  +là trung tâm kết nối các máy tính trong một văn phòng, công ty cơ quan lại với nhau,.. Là nơi trao đổi dl, điều hành chung của mạng máy tính
  
  
1.4. Các dạng máy chủ thường gặp

1.4.1. Hình dạng

+Tower Server (máy chủ tháp): máy chủ dạng đứng, thiết kế nhỏ gọn có thể mở rộng bằng cách nâng cấp RAM, CPU, ổ cứng

  ->Ưu điểm: làm mát dễ dàng, khả năng mở rộng cao

  ->Nhược điểm: cồng kềnh và nặng hơn các dòng máy chủ rack,tiếng ồn của quạt chuyên dụng cho tower máy chủ khá to

+Rack-mount Server(máy chủ rack): máy chủ dạng nằm được thiết kế đặc biệt để gắn vào tủ rack máy chủ

   ->Ưu điểm:dễ dàng gắn vào tủ rack, khả năng làm mát tốt nhờ được trang bị quạt bên trong

   ->Nhược điểm:các giá đỡ nhiều máy chủ đòi hỏi nhiều bộ phận làm mát hơn, làm tăng chi phí năng lượng

+Blade Server: là một kiến trúc mới nhất hiện nay thay thế cho những máy chủ server truyền thống

  ->Ưu điểm: hao tốn năng lượng thấp, cung cấp sức mạnh xử lý cao trong khi chiếm không gian tối thiểu

  ->Nhược điểm:chi phí năng lượng, chi phí trả trước

1.4.2. Chức năng

+Dedicated Server:chạy trên phần cứng và có các thiết bị hỗ trợ riêng biệt

  ->Ưu:tài nguyên độc lập, hiệu suất cao,người dùng toàn quyền quản trị

  ->Nhược:nâng cấp phức tạp

+VPS(Virtual Private Server):được tạo ra bằng phương pháp ảo hóa để chia tách máy chủ vật lý riêng thành nhiều máy chủ ảo khác nhau

  ->Ưu:chi phí vừa phải, phù hợp vs các doanh nghiệp vừa và nhỏ

  ->Nhược:phụ thuộc vào server vật lý

+Cloud Server:được xây dựng trên công nghệ điện toán đám mây, ảo hóa ứng dụng

  ->Ưu:cơ chế đồng bộ dữ liệu, khả năng tự động thay thế khi gặp sự cố 

  ->Nhược:

2.Tủ rack

2.1.Tủ rack là gì?

   -tủ rack hay tủ mạng là loại tủ đặc biệt được thiết kế để chứa máy tính và các thiết bị cntt như server,switch,router,...

2.2.Các loại tủ rack

2.2.1Tủ Server Rack

  +là loại tủ được sử dụng phổ biến nhất, cánh cửa tủ trước và sau được đục lỗ thoáng góp phần làm mát cho thiết bị

  ->Ưu điểm: được bảo vệ trong không gian kín tránh tác động bên ngoài

2.2.2.Tủ Wallmount Rack

  +là loại tủ được thiết kế treo tường ,phù hợp với hệ thống mạng đơn giản

  ->Ưu điểm:nhỏ gọn tiết kiệm không gian sàn

  ->Nhược: hạn chế về kích thước và khối lượng thiết bị trong tủ

2.2.3.Tủ Open rack

  +là hệ thống giá đỡ sử dụng để chứa máy tính và các thiết bị mạng, bao gồm hệ thống khung được xếp khoa học, không có cửa trước sau và mặt trên

  ->Ưu:lắp đặt, tiếp cận dây cáp, bảo trì thiết bị dễ dàng

  ->Nhược: thiếu an toàn

2.2.4.Tủ Our Door Rack

  +là loại tủ được thiết kế để sử dụng ngoài trời, phù hợp cho các thiết bị viễn thông và điều khiển
      
  ->Ưu:tính bảo mật cao, an toàn

  ->Nhược:vận chuyển khó khăn, chi phí đầu tư lớn.

3.Chẩn server 1U,2U,3U,...

  -U là đơn vị đo kích thước tủ mạng có quy đổi tiêu chuẩn 1U=1,75 inch=4,45cm

  -Số U là đơn vị đo chiều cao tủ mà các nhà sản xuất tủ quy ước để đo các chiều cao của các thiết bị mạng

4.Server Twin
  
  -máy chủ cặp, được thiết kế theo kiến trúc twin

   VD: máy chủ Twin 1U gồm 2 máy chủ con gọi là node, mỗi node kích thước 0,5U theo chiều ngang, 2 node sử dụng chung 1 nguồn điện
   
   ->Ưu điểm:giảm nguồn điện chi phí làm mát, không gian và tăng hiệu suất so với máy chủ 1U

5.Mainbroad,CPU,RAM,HDD(Santa,SSD)

5.1.Mainbroad: là nơi gắn kết tất cả các linh kiện và thiết bị ngoại vi thành 1 khối,điều khiển tốc độ và đường đi của luồng dữ liệu giữa các thiết bị

  -bao gồm:Socket CPU(liên lạc vs các thiết bị khác thông qua chip cầu bắc),Chíp cầu bắc(VGA-RAM), chip cầu nam(giao tiếp ổ cứng,chip LAN,chip Audio,USB,khe PCI,chip SIO,chip
  
  BIOS), chip SIO(keyboard,mouse,ổ mềm,cổng máy in, cổng serial),chip BIOS(chứa ctrinh CMOS Setup,POST)

5.2.CPU(Central Processing Unit): bộ xử lý trung tâm, xử lý tất cả các lệnh mà nó nhận được từ phần cứng và phần mềm chạy trên máy tính

5.3.RAM(Random Access Memory) bộ nhớ truy cập ngẫu nhiên.

  ->hiểu nôm na là nơi máy tính lưu trữ thông tin tạm thời để chuyển cho CPU xử lý

  +SDRAM(Synchronous dynamic random access memory): Bộ nhớ truy cập ngẫu nhiên động đồng bộ

  +DDRAM:DDRAM chính là SDRAM nhưng tần xuất xử lý thông tin của nó được cải tiến nhanh gấp nhiều lần

  ->DDRAM 1,2,3,4 ~ 266-400mhz,400-800,800-1600,1600-3200

5.4: HDD,SSD

5.4.1. HDD(Hard disk drive):lưu dữ liệu bằng cách ghi lên đĩa từ được xoay trên động cơ, có loại kích cỡ 3,5 và 2,5 inch , SATA 3, 5,25inch(máy tính thế hệ đầu)

  ->tốc độ ->100mb/s

5.4.2. SSD(Solid state drive): là ổ cứng điện tử, là thiết bị lưu trữ dl cho máy tính sử dụng bộ nhớ bán dẫn như SRAM,DRAM

  ->3 loại ổ SSD: NVMe,SATA(sd hầu hết cho laptop hiện nay),M.2

  ->tốc độ ->3500mb/s

6.RAID CARD(Redundant Arrays of Inexpensive Disks) có chức năng hỗ trợ RAID có thể vận hành trong máy chủ là nơi tập trung các cáp dữ liệu nối các đĩa cứng trong hệ thống RAID và nó xử lý tòa bộ dữ liệu đi qua nó

- Có 2 dạng Card RAID là card Onbroad và card RAID rời

RAID 0 : yêu cầu tối thiếu 2 đĩa cứng, cho phép máy tính ghi dữ liệu theo phương thức Striping. VD: có 100MB sẽ dồn mỗi đĩa 50MB

-> Ưu điểm : thích hợp cho những người dùng cần truy cập nhanh khối lượng dữ liệu lớn, nhanh

-> Nhược : Nguy cơ mất dữ liệu do cơ chế ghi thông tin xé lẻ

RAID 1 : Dữ liệu được ghi vào 2 ổ giống hệt nhau (Mirroring), 1 ổ gặp trục trặc ổ còn lại vẫn hđ bình thường, dung lượng cuối cùng của RAID 1 = Dung lượng ổ đơn

->Ưu : nếu một trong 2 ổ bị hỏng không lo bị mất dữ liệu, an toàn

->Nhược : Hiệu năng không cao

RAID 0 + 1 (RAID 10) : Cần tối thiểu 4 đĩa cứng để chạy, dữ liệu được ghi đồng thời lên 4 đĩa, dung lượng cuối cùng = tổng dung lượng 4 ổ /2

->Ưu : tổng hợp ưu điểm của 2 hệ thống RAID 0 và 1

->Nhược : chi phí khá đắt

RAID 5 : dữ liệu và bản sao lưu được chia lên tất cả các ổ cứng ,dung lượng ổ đĩa cuối = tổng dung lượng đĩa sử dụng trừ đi 1 ổ.

VD: 8 đoạn dl(1-8) 3 ổ đĩa cứng, 1,2 được lưu vào ổ 1 và 2 riêng, bản sao lưu ghi vào ổ 3. 3,4 đc ghi vào ổ 1,3 sao lưu vào ổ 2, đoạn 5,6 được lưu vào ổ 2,3 sao lưu vào ổ đĩa 1. sau đó lặp lại 7,8 lưu vào 1,2 lưu trữ ổ 3. 

-> Ưu : đảm bảo tốc độ cải thiện, giữ được tính an toàn cao

RAID 6 : là sự cải tiến từ RAID 5, mỗi dữ liệu được lưu trữ ở ít nhất 3 vị trí(trở lên), yêu cầu tối thiểu 4 ổ cứng, cho phép hỏng 2 ổ cứng hệ thống vẫn hđ bình thường -> RAID 6 thường chỉ được sử dụng trong các máy chủ chứa dữ liệu cực kỳ quan trọng

-> Ưu : độ dự phòng cao hơn và hiệu suất đọc tốt hơn

-> Nhược : máy chủ thực hiện quá nhiều thao tác ghi , hiệu suất sẽ giảm

NIC Card ( Network Interface Card) là bản mạch cung cấp khả năng truyền thông mạng cho một máy tính còn được gọi là LAN Adapter

Chức năng : truyền tín hiệu ở lớp vật lý và cung cấp các gói dữ liệu ở lớp mạng

Các thành phần của NIC Card : Bộ đk, Ổ cắm ROM , Cổng NIC cho cáp/bộ thu phát, Giao diện Bus, Đèn báo LED, Giá đỡ

