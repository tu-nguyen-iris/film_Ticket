
Chi tiết:
- Trang chủ client: Có chức năng:
	+ Đăng nhập, đăng xuất,tin tức , xem chi tiết phim đang chiếu,click vào tên tài khoản, dropdown menu sẽ hiện ra(Gồm Lịch sử đặt vé, , đăng xuất,chỉnh sử thông tin người dùng ).
	+ Trên menu navbar sẽ có route link tới trang chủ, search phim
        +Carousel sử dụng slick carousel
	+ Tiếp theo là movielist, bao gồm phim đang chiếu và phim sắp chiếu,phần này sử dụng thư tiện slick-carousel cho react để trong component riêng, bao gồm các thông tin liên quan đến phim, khi click vào icon play trong 1 item sẽ hiện thị modal play trailer thông qua url truyền vào. Khi hover hiện button, click vào buttton "Đặt Vé" sẽ route link tới trang chi tiết phim.
- Chi tiết phim: chứa các thông tin về phim ,đánh giá , chứa tabs đặt vé gồm hệ thống rap và địa chỉ cụm rạp đang chiếu phim đã click vô , khi chưa đăng nhập thì lúc ấn vào thời gian sẽ đc đưa tới trang đăng nhập và đăng ký
- Trang đặt vé: Người dùng sẽ chọn ghế xem phim thông qua danh sách ghế hiện trên màn hình, các màu tương ứng với tình trạng ghế, thông tin đặt vé hiện lên bên phải màn hình, khi người dùng bấm nút đặt vé, nếu chưa đặt ghế nào thì sẽ hiện thông báo yêu cầu đặt ghế
- Trang quản lý admin web phim:
	+ Dành cho tài khoản quản trị, nếu không phải tài khoản quản trị sẽ không thể vào trang này.
	+ Có 2 mục là quản lý user và quản lý phim.
	+ Quản lý user: Có chức năng thêm mới, sửa, xóa và show các tài khoản user, không thể xóa các tài khoản là quản trị và user đã đặt vé.
	+ Quản lý phim: Có Có chức năng thêm mới, sửa, xóa và show các phim hiện có.

*Api do Cybersoft cung cấp, chứa thông tin user và phim,rạp
userAdmin:456tien
pass:3213211
