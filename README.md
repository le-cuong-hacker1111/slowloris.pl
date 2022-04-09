# slowloris.pl
DdoS  Slowloris extremely strong
Slowloris là gì?
Slowloris về cơ bản là tấn công từ dịch vụ HTTP đến máy chủ luồng. Nó hoạt động như thế này:

Chúng tôi bắt đầu thực hiện nhiều HTTP yêu cầu.
Chúng tôi gửi các tiêu đề (mỗi ~ 15 giây) để giữ các kết nối luôn mở.
Chúng tôi không bao giờ đóng kết nối trừ khi máy chủ làm như vậy. Nếu máy chủ đóng một kết nối, chúng tôi sẽ tạo một máy chủ mới tiếp tục thực hiện tương tự.
Điều này đang thực hiện kiệt máy chủ luồng và máy chủ không thể trả lời người khác.
@article { lecuonghack er1111,
title = "Slowloris",
author = " Le Tran Van Cuong
" ,
   journal = " github.com " ,
   year = " 2022
    " ,le-cuong-hacker1111/slowloris.pl
   url = " https://github.com/
   
   git clone https://github.com/le-cuong-hacker1111/slowloris.pl
   
   cd slowloris.pl
   
   chmod  a+x slowloris.pl 
   
   use: ./slowloris.pl
   
   ./slowloris.pl -dns  103.200.23.15
   
   ex: ./slowloris.pl -dns (IP)  {will attack}
   
   Done
   Code veried
   
