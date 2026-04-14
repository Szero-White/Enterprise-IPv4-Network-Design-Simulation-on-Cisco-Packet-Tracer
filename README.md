# 🚀 Enterprise IPv4 Network Design Simulation on Cisco Packet Tracer



## 📄 Giới thiệu Dự án

Dự án này trình bày quá trình thiết kế, mô phỏng và cấu hình một hệ thống mạng IPv4 cho doanh nghiệp sử dụng phần mềm Cisco Packet Tracer. Toàn bộ bài tập tập trung vào việc triển khai các công nghệ mạng thực tế, giúp nâng cao kỹ năng chuyên môn về thiết kế, vận hành và bảo trì hệ thống mạng doanh nghiệp.

## 🛠️ Các công việc đã thực hiện

- 🗺️ **Thiết kế sơ đồ địa chỉ IP:** Phân tích yêu cầu, lập bảng địa chỉ IPv4 cho từng phân đoạn mạng, đảm bảo tối ưu hóa tài nguyên địa chỉ.
- 🔗 **Cấu hình kết nối PPP:** Thiết lập kết nối Point-to-Point Protocol trên các liên kết WAN giữa các router, xác thực và kiểm tra kết nối.
- 🌉 **Cấu hình GRE Tunneling:** Tạo đường hầm GRE giữa các site nhằm đảm bảo truyền dữ liệu an toàn, hỗ trợ các giao thức định tuyến động qua môi trường không hỗ trợ multicast.
- 🛣️ **Cấu hình định tuyến:**
	- Định tuyến tĩnh giữa các phân đoạn mạng.
	- Cấu hình các giao thức định tuyến động (nếu có yêu cầu) như RIP, OSPF, EIGRP để tối ưu hóa đường đi của gói tin.
- 🔀 **Cấu hình chuyển mạch:**
	- Thiết lập VLAN, chia nhỏ miền quảng bá, cấu hình trunking giữa các switch.
	- Cấu hình Inter-VLAN Routing để các VLAN có thể liên lạc với nhau.
- 🌐 **Cấu hình NAT & DHCP:**
	- Thiết lập NAT (Network Address Translation) cho phép các thiết bị nội bộ truy cập Internet.
	- Cấu hình DHCP Server cấp phát địa chỉ IP tự động cho các thiết bị đầu cuối.
- 🧩 **Các yêu cầu mở rộng khác:**
	- Thực hiện các yêu cầu nâng cao hoặc tùy chỉnh theo đề bài (bảo mật, kiểm tra kết nối, giám sát, ...).

## 📁 Cấu trúc dự án

- `Enterprise-IPv4-Network-Simulation.pkt`: File mô phỏng mạng trên Cisco Packet Tracer.
- `Enterprise-IPv4-Network-Report.pdf`: Báo cáo chi tiết quá trình thực hiện, cấu hình và kiểm thử.
- `Final-Exam-Requirement.pdf`: Đề bài kiểm tra cuối kỳ.
- `Enterprise-IPv4-Network-Config.docx`: Ghi chú, hướng dẫn hoặc tài liệu bổ sung.
- `README.md`: Giới thiệu tổng quan dự án.

## 🖥️ Các bước thực hiện trên Cisco Packet Tracer

1. Khởi tạo sơ đồ mạng, thêm các thiết bị Router, Switch, PC theo yêu cầu bài toán.
2. Kết nối các thiết bị bằng cáp phù hợp (cáp thẳng, cáp chéo, cáp console).
3. Gán địa chỉ IP cho các interface trên Router, Switch Layer 3 và các thiết bị đầu cuối.
4. Cấu hình VLAN trên Switch, gán port vào từng VLAN, cấu hình trunk giữa các Switch.
5. Thiết lập Inter-VLAN Routing trên Router hoặc Switch Layer 3.
6. Cấu hình kết nối PPP trên các liên kết WAN giữa các Router (bao gồm xác thực nếu có).
7. Thiết lập GRE Tunnel giữa các Router để kết nối các site từ xa.
8. Cấu hình định tuyến tĩnh hoặc động (RIP, OSPF, EIGRP) để đảm bảo các mạng con liên lạc được với nhau.
9. Cấu hình DHCP Server trên Router/Switch để cấp phát IP động cho các thiết bị đầu cuối.
10. Thiết lập NAT trên Router để các thiết bị nội bộ truy cập Internet.
11. Kiểm thử kết nối toàn mạng bằng lệnh ping, traceroute, kiểm tra cấp phát IP, kiểm tra truy cập Internet.
12. Lưu cấu hình, xuất file mô phỏng và hoàn thiện tài liệu báo cáo.

## 👨‍💻 Kỹ năng & Kiến thức thể hiện

- Thiết kế, lập sơ đồ mạng doanh nghiệp chuyên nghiệp
- Cấu hình thiết bị Cisco (Router, Switch) thực tế
- Hiểu và triển khai các công nghệ WAN (PPP, GRE)
- Thành thạo các giao thức định tuyến (Static, Dynamic)
- Quản lý VLAN, trunking, Inter-VLAN Routing
- Thiết lập NAT, DHCP server
- Kiểm thử, giám sát, xử lý sự cố mạng

## 📦 Hướng dẫn sử dụng

1. Mở file `52200271_NguyenCongToan.pkt` bằng phần mềm Cisco Packet Tracer.
2. Quan sát sơ đồ mạng, kiểm tra các cấu hình trên thiết bị.
3. Đọc file báo cáo PDF/DOCX để hiểu rõ từng bước cấu hình, lý thuyết và kết quả kiểm thử.

## 🏆 Thông tin tác giả

- **Nguyễn Công Toàn**  
	MSSV: 52200271

---
