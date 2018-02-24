# Cách cài đặt Ubuntu Server 14.04 trên Vmware Workstation 12 Pro

## Yêu cầu:

- Máy tính đã cài đặt VMware Workstation 12 Pro.

- Tải file cài đặt Ubuntu Server, Download file ISO tại [link](http://releases.ubuntu.com/trusty/). Nên dùng bản LTS để có sự ổn định.

## Các bước cài đặt:

- Bước 1: Tạo một máy ảo VMware mới. Chi tiết các bước theo từng ảnh.

    <img src="./Picture/1.png" />

    <img src="./Picture/2.png" />

    <img src="./Picture/3.png" />

    <img src="./Picture/4.png" />

    <img src="./Picture/5.png" />

    <img src="./Picture/6.png" />

    Sau khi ấn Finish bạn đã tạo thành công một máy ảo để cài đặt Ubuntu Server. Nó sẽ tự động Start và đưa chúng ta đến phần cài đặt.

- Bước 2: Cài đặt Ubuntu Server 14.04 và các thiết lập. (Chú ý: để di chuyển giữa các phần khác nhau khi cài đặt, dùng phím TAB. Còn để tick/lựa chọn một option, dùng phím ENTER.)

    1.Chọn ngôn ngữ English, ấn Enter.

    <img src="./Picture/7.png" />

    2.Tiếp theo chọn Install Ubuntu Server và nhấn Enter .

    <img src="./Picture/8.png" />

    3.Tiếp theo chọn ngôn ngữ mặc định của hệ thống và cài đặt Ngôn ngữ .

    <img src="./Picture/9.png" />

    4.Nếu quốc gia của bạn không có trong danh sách  chọn Other và chọn Country của bạn .

    <img src="./Picture/10.png" />

    5.Chọn lục địa

    <img src="./Picture/11.png" />

    6.Chọn quốc gia

    <img src="./Picture/12.png" />

    7.Chọn ngôn ngữ của bạn,  chọn một ngôn ngữ chung như mã hóa UTF-8 để sau đó  không gặp vấn đề với bàn phím.

    <img src="./Picture/13.png" />

    8.Tiếp tục nhắc cấu hình lại Bàn phím

    <img src="./Picture/14.png" />

    9.Chọn ngôn ngữ bằn phím

    <img src="./Picture/15.png" />

    10.Chọn giao diện bàn phím

    <img src="./Picture/16.png" />

    11.Tải các thành phần bổ sung

    <img src="./Picture/17.png" />

    12.Thiết lập tên máy chủ hệ thống 

    <img src="./Picture/18.png" />

    13.Thiết lập người dùng quản trị. Nhập tên đăng nhập và nhấn vào Tiếp tục .

    <img src="./Picture/19.png" />

    <img src="./Picture/20.png" />

    14.Thiết lập mật khẩu.

    <img src="./Picture/21.png" />

    15.Nhập lại mật khẩu.

    <img src="./Picture/22.png" />

    16.Nếu máy chủ của bạn có chứa dữ liệu nhạy cảm, bí mật hoặc quan trọng trên Users nhà phân vùng, màn hình kế tiếp cung cấp tùy chọn để đảm bảo tất cả các dữ liệu bằng cách mã hóa thư mục. Nếu không cần thiết phải mã hóa dữ liệu chọn No và nhấn Enter .

    <img src="./Picture/23.png" />

    17.Nếu trong khi trình cài đặt chạy và thẻ giao diện mạng của bạn có kết nối Internet, trình cài đặt sẽ tự động phát hiện Vị trí của bạn và thiết lập đúng múi giờ của bạn . Nếu thời gian cung cấp không được thiết lập đúng, bạn có thể chọn nó bằng tay từ danh sách khác, chọn No và nhấn Enter .

    <img src="./Picture/24.png" />

    18.Tiếp theo là phân vùng để cài đặt. Chọn Guided-use entire disk andset up LVM và ấn Enter.

    <img src="./Picture/25.png" />

    19.Chọn phân vùng đĩa,

    <img src="./Picture/26.png" />

    20.Viết thay đổi cho đĩa.

    <img src="./Picture/27.png" />

    21.Chọn Continue

    <img src="./Picture/28.png" />

    22.Sau khi bảng phân vùng đã được ghi lên đĩa cài đặt. Chấp nhận sự thay đổi bảng phân vùng và nhấn Yes .

    <img src="./Picture/29.png" />

    23.Cài đặt hệ thống.

    <img src="./Picture/30.png" />

    24.Nếu không truy cập Internet qua proxy thì hãy để trống và Tiếp tục .

    <img src="./Picture/31.png" />

    25.Cấu hình Apt.

    <img src="./Picture/32.png" />

    26.Chọn Không cập nhật tự động vì trên máy chủ bạn nên thử cập nhật bằng tay hệ thống hoặc có thể chọn Install security updates automatically để tự động cài đặt các Update liên quan đến bảo mật.

    <img src="./Picture/33.png" />

    27.Cài đặt OpenSSH để có thể SSH vào server bằng cách nhấn phím Space bar và chọn Continue .

    <img src="./Picture/34.png" />

    <img src="./Picture/35.png" />

    <img src="./Picture/36.png" />

    28.Các gói đã chọn đang được cài đặt trong khi tùy chọn cuối cùng được hiển thị trên màn hình của bạn yêu cầu Cài đặt GRUB sang MRB . Bởi vì hệ thống không thể khởi động trên mình mà không có GRUB , chọn Yes .

    <img src="./Picture/37.png" />

    29.Nhấn Continue để khởi động.

    <img src="./Picture/38.png" />

    30.Đã hoàn thành xong quá trình cài đặt. Login bằng User name và Password đã tạo nhé.

    <img src="./Picture/39.png" />


### Bài viết tham khảo tại [Hướng dẫn cài Ubuntu Server trên VMware Player](https://medium.com/pymi/h%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-c%C3%A0i-ubuntu-server-tr%C3%AAn-vmware-player-726f1f08ad35) và [Cách cài đặt Ubuntu Server 14.04 nhanh nhất](http://vdo.vn/thong-tin-huu-ich/cai-dat-ubuntu-server-14-04.html).
    





    
