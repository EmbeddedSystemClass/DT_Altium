PIF.
video minh họa: https://www.youtube.com/watch?v=cDKGagANcZ4

Nguồn: 
https://sites.google.com/site/vanhoipc/v-chatbox/ung-dung-vdhk?tmpl=%2Fsystem%2Fapp%2Ftemplates%2Fprint%2F&showPrintDialog=1
http://mualinhkien.vn/chi-tiet-bv/huong-dan-lam-mach-on-ap-5v-don-gian-dung-lm7805.html

# Mạch ổn áp 5V với ic 7805.
Nguồn vào 12V DC. Diode D0 (1N4007) dùng tránh mắc sai cực nguồn. Nếu Bạn gắn sai cực, nhờ tính ghim áp của diode, nó sẽ giữ cho mức áp nghịch ở ngả vào của bo ở mức 0.8V, mạch sẽ khi bị hư.
Tụ C1 (1000uF), tụ hóa lớn dùng làm kho chứa điện, có công dụng ổn định điện áp đường nguồn, ở đây Bạn sẽ có 12V dùng cấp nguồn cho các dãy Led. Bạn cũng có thể cấp đường nguồn này cao hơn để có thể mắc trên một nhánh được nhiều Led nối tiếp hơn (xem phần hướng dẫn ở phần sau).
Tụ C2, C4 có trị nhỏ 104pF (0.1uF) có công dụng lọc bỏ tín hiệu nhiễu tần cao nhiễm trên đường nguồn.
 
Tụ C3 (10uF), mắc ở ngả ra của ic ổn áp 7805 dùng tránh phát sinh hiện tượng dao động tự kích bên trong ic ổn áp 7805.
 
Mạch dùng ic ổn áp 3 chân họ 78xx, với ic 7805, trên ngả ra sẽ luôn có mức áp 5V với độ ổn định cao, chúng ta sẽ dùng mức áp này để cấp cho chân 40 của ic vi điều khiển AT89C51/52....