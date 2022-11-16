# Software-Technology-Project
Dự án: Mạng xã hội chia sẻ kiến thức y học <br/>
Project môn học làm về công nghệ phần.
Dự án mô phỏng một mô hình mạng xã hội với một vài chức năng khác biệt.

Tổng thể mạng xã hội bao gồm:
1. Trang login và register
2. Trang dành cho admin
    Chứa các thành phần bao gồm:<br/>
      -Quản lý danh sách người dùng, và người dùng là bác sĩ <br />
      -Xem thông tin hồ sơ của người dùng <br />
      -Duyệt người dùng là bác sĩ muốn tham gia, người dùng là bác sĩ muốn nâng cấp lên người dùng cao cấp(thêm các chức năng duyệt bài và xóa bài viết) <br />
3. Trang Home <br/>
    Chứa các thành phần bao gồm các thành phần cơ bản của mọi người dùng:<br/>
        -Danh sách bài viết của các bác sĩ<br/>
        -Danh sách bác sĩ theo dõi<br/>
        -Thanh chuyển hướng đến các trang khác<br/>
        -Logout<br/>
    Các thành phần chỉ có khi đăng nhập với tư cách bác sĩ:<br/>
        -Tạo bài viết mới<br/>
        -Xóa, chỉnh sửa bài viết <br/>
    Thành phần của bác sĩ cao cấp:<br/>
        -Duyệt bài viết của các bác sĩ thường<br/>
4. Trang profile cá nhân<br/>
    Chứa các thành phần:<br/>
        -Chỉnh sửa profile cá nhân<br/>
        -Xem các tin nhắn của bản thân<br/>
        -Đề cử thăng cấp lên bác sĩ cao cấp(chỉ có nếu là bác sĩ)<br/>
5. Trang xem danh sách các chuyên khoa hiện có, có thể tìm bài viết theo từng chuyên khoa tại đây
6. Trang bảng xếp hạng của bác
    Chứa các thành phần:<br/>
        -Bảng xếp hạng bác sĩ từ cao đến thấp (đánh giá dựa trên tổng lượt like các bài viết của bác sĩ đó)<br/>
        -Mini profile của bác sĩ(chứa tên, sđt, chuyên ngành)
        -Bảng tin nhắn với bác sĩ
