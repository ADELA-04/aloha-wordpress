## ***Mục lục***

[1. Giới thiệu Wordpress](#1)

- [1.1. Wordpress là gì?](#1.1)

- [1.2. Các đặc điểm nổi bật của Wordpress](#1.2)

[2. Bắt đầu dự án ](#2)

 - [2.1. Giao diện](#2.1)
   
    - [2.1.1. Giao diện Admin(CMS WordPress)](#2.1.1)
   
    - [2.1.2. Giao diện người dùng](#2.1.2)

 - [2.2. Chức năng](#2.2)

   - [2.2.1.Admin ](#2.2.1)
     
      - [2.2.1.1. Quản lý nội dung:](#2.2.1.1)
    
      - [2.2.1.2.Quản lý người dùng](#2.2.1.2)
    
     - [2.2.1.3.Quản lý giao diện](#2.2.1.3)
    
     - [2.2.1.4.Cài đặt và quản lý plugin](#2.2.1.4)
    
     - [2.2.1.5.Quản lý cài đặt tổng thể](#2.2.1.5)


   - [2.2.2. User ](#2.2.2)
     
     - [2.2.2.1. Tìm kiếm sản phẩm](#2.2.2.1)
   
     -  [2.2.2.2. Quản lý giỏ hàng và thanh toán](#2.2.2.2)

     -  [2.2.2.3.  Quản lý tài khoản cá nhân](#2.2.2.3)

      - [2.2.2.4. Tương tác và đánh giá sản phẩm](#2.2.2.4)

     - [2.2.2.5. Các chức năng khác](#2.2.2.5)

 [3. Cài đặt ](#3)
 
[4. Sử dung ](#4)

 ---



<a name = "1"></a>
# WordPress
# 1. Giới thiệu Wordpress
<a name = "1.1"></a>
## 1.1. Wordpress là gì?
WordPress là một phần mềm nguồn mở (Open Source Software) được viết bằng ngôn ngữ lập trình website PHP (Hypertext Preprocessor) và sử dụng hệ quản trị cơ sở dữ liệu MySQL.

WordPress xử lý bằng ngôn ngữ PHP để hỗ trợ tạo blog cá nhân, và nó được rất nhiều người sử dụng ủng hộ về tính dễ sử dụng, nhiều tính năng hữu ích. Qua thời gian, số lượng người sử dụng tăng lên, các cộng tác viên là những lập trình viên cũng tham gia đông đảo để phát triển mã nguồn WordPress có thêm những tính năng tuyệt vời.

Hiện tại, Wordpress là CMS (Content management system) phổ biến nhất trên internet. Nó cho phép bạn dễ dàng cài đặt những blog phức tạp và các website trên nền tảng lưu trữ MySQL với quá trình xử lý sử dụng PHP. Wordpress đã cho thấy được áp dụng một cách đáng kinh ngạc và là một sự lựa chọn tuyệt với cho việc dựng các website và chạy một cách nhanh chóng.

<a name = "1.2"></a>
## 1.2. Các đặc điểm nổi bật của Wordpress
- Dễ sử dụng: WordPress được phát triển nhằm phục vụ đối tượng người dùng phổ thông, không có nhiều kiến thức về lập trình website nâng cao. Các thao tác trong WordPress rất đơn giản, giao diện quản trị trực quan giúp bạn có thể nắm rõ cơ cấu quản lý một website WordPress trong thời gian ngắn.

- Cộng đồng hỗ trợ đông đảo: Là một mã nguồn CMS mở phổ biến nhất thế giới, điều này cũng có nghĩa là bạn sẽ được cộng đồng người sử dụng WordPress hỗ trợ bạn các khó khăn gặp phải trong quá trình sử dụng.

- Nhiều gói giao diện (theme) có sẵn: Người dùng có thể chỉnh sửa, tùy biến giao diện một cách đơn giản, nhẹ nhàng.

- Nhiều plugin hỗ trợ: hỗ trợ nhiều plugin có sẵn và cho phép cộng đồng người dùng viết các plugin cho WP.

- Hổ trợ Widget dạng kéo – thả: Thay vì phải động vào code, bạn chỉ việc kéo – thả ở những vị trí thích hợp.

- Dễ phát triển cho lập trình viên: WordPress là một mã nguồn mở nên bạn có thể dễ dàng hiểu được cách hoạt động của nó và phát triển thêm các tính năng.

- Hỗ trợ nhiều ngôn ngữ.

- Có thể làm nhiều loại Website: Dùng WordPress không có nghĩa là bạn chỉ có thể làm blog cá nhân, mà bạn có thể biến website mình thành một trang bán hàng, một website giới thiệu công ty, một tờ tạp chí online bằng việc sử dụng kết hợp các theme và plugin với nhau.

<a name = "2"></a>
# 2. Bắt đầu dự án
# Dự án: Aloha-WordPress
![Screenshot (615)](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/7abe0462-f925-425f-b22c-075298798394)


#### Mô tả ngắn về dự án: Aloha là một website thương mại điện tử mã nguồn mở:
#### Theme: Flatsome.
#### Plugin: Woocommerce và một số Plug-in thông dụng khác
<a name = "2.1"></a>
## 2.1. Giao diện: 
<a name = "2.1.1"></a>
### 2.1.1. Giao diện Admin(CMS WordPress): 
![Screenshot (620)](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/c3cfc591-8381-48ae-b557-6e8c312f7c72)

##### - Cập nhật: Nơi thông báo những bản cập nhật mới bao gồm gói cập nhật WordPress, Giao diện, Plugin.
##### - Bài viết: Quản lý toàn bộ bài viết. Tại đây bạn có thể thêm, bớt chuyên mục và bài viết. Bài viết là những nội dung đăng tải để người xem vào đọc, như là bài viết bạn đang xem đây.
##### - Thư viện: Nơi quản lý hình ảnh, video trên website.
##### - Trang: Quản lý các trang của website. Trang là nơi bạn đăng những thông tin cố định, xem như là sườn của website WordPress. Chẳng hạn như: Trang chủ, Giới thiệu, Liên hệ, Điều khoản sử dụng,…
##### - Phản hồi: Những phản hồi, bình luận của người xem về bài viết.
##### - Giao diện: Quản lý giao diện của website. Trong đây bạn có thể cài đặt giao diện mới, quản lý cũng như tuỳ biến giao diện đang sử dụng.
##### - Plugin: Quản lý và cài đặt các plugin (tính năng) cho website wordpress.
##### - Thành viên: Quản lý, thêm bớt, chỉnh sửa các thành viên. Tuỳ vào mục đích của website, bạn có thể cho phép thành viên tự đăng ký và chỉnh sửa thông tin.
##### - Cài đặt: Cài đặt tổng quan cho toàn bộ website.

<a name = "2.1.2"></a>
### 2.1.2. Giao diện người dùng: 
#### - Trang chủ
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/704b4a88-13d7-4eb3-af50-b48f1241dfa2)

#### - Trang tài khoản
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/24f5644e-38b6-41ec-bca3-e2eb4442845f)
#### - Trang sản phẩm
![Screenshot (618)](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/90e4fe39-7a29-44f2-8d55-84a0a2a399d9)

#### - Trang chi tiết sản phẩm
![Screenshot (616)](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/462d42c5-6fff-4422-861c-6a1ec9a05139)

#### - Trang thanh toán
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/f652cead-641f-4512-8513-b2f5096efda0)


<a name = "2.2"></a>
## 2.2. Chức năng: 
<a name = "2.2.1"></a>
### 2.2.1. Admin: 
<a name = "2.2.1.1"></a>
#### 2.2.1.1. Quản lý nội dung:
+ Tạo, chỉnh sửa, xóa bài viết, trang, danh mục, thẻ tags.
+ Quản lý phương tiện như hình ảnh, video, tệp đính kèm.
  <a name = "2.2.1.2"></a>
#### 2.2.1.2.Quản lý người dùng:
+ Thêm, chỉnh sửa, xóa các tài khoản người dùng.
+ Gán các vai trò và quyền hạn khác nhau (admin, editor, author, contributor, subscriber).
  <a name = "2.2.1.3"></a>
#### 2.2.1.3.Quản lý giao diện:
+ Cài đặt, kích hoạt, tùy chỉnh các giao diện (themes).
+ Quản lý các widget, menu, header, footer.
  <a name = "2.2.1.4"></a>
#### 2.2.1.4.Cài đặt và quản lý plugin:
+ Tìm kiếm, cài đặt, cập nhật, vô hiệu hóa các plugin.
+ Cấu hình các tùy chọn và thiết lập của plugin.
  <a name = "2.2.1.5"></a>
#### 2.2.1.5.Quản lý cài đặt tổng thể:
+ Thay đổi các thiết lập chung của website như tên, địa chỉ, múi giờ, v.v.
+ Cấu hình các tùy chọn bảo mật, SEO, hiệu suất.

<a name = "2.2.2"></a>
### 2.2.2 User: 
<a name = "2.2.2.1"></a>
#### 2.2.2.1. Tìm kiếm sản phẩm:
+ Tìm kiếm sản phẩm theo từ khóa.
  
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/d470c69e-cb8c-41c0-836a-10798fe8cc36)

+ Lọc sản phẩm theo khoảng giá.
  
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/f6822aef-953d-4107-a42d-961932d5e10b)

+ Xem chi tiết sản phẩm, ảnh, mô tả.
  <a name = "2.2.2.2"></a>
#### 2.2.2.2. Quản lý giỏ hàng và thanh toán:
+ Thêm, xóa, cập nhật số lượng sản phẩm trong giỏ hàng.
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/cd0ced04-af81-4bc9-b56f-e63b92a1ad29)

+ Chức năng mua hàng nhanh thay vì phải truy cập qua trang giỏ hàng.
+ Xem tổng giá trị đơn hàng, phí giao hàng.
  
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/848c936b-a694-48d6-bad1-f7cb1657efc1)


+ Phương thức thanh toán (Thanh toán khi nhận hàng).
  
  ![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/b34e5a21-051b-4c95-9128-ed7957ad36b3)


+ Điền thông tin giao hàng và thanh toán.
![image](https://github.com/ADELA-04/Aloha-WordPress/assets/169277562/a9a28b80-f60c-493e-a14e-953cd1eefc91)

<a name = "2.2.2.3"></a>
#### 2.2.2.3.  Quản lý tài khoản cá nhân:
+ Tạo, đăng nhập, cập nhật thông tin tài khoản.
+ Xem lịch sử đơn hàng, theo dõi trạng thái đơn hàng.
+ Quản lý địa chỉ giao hàng.
+ Đặt lại mật khẩu.
  <a name = "2.2.2.4"></a>
#### 2.2.2.4. Tương tác và đánh giá sản phẩm:
+ Viết đánh giá, xếp hạng sản phẩm.
  <a name = "2.2.2.5"></a>
#### 2.2.2.5. Các chức năng khác:
+ Đăng ký/hủy thông báo.
+ Chia sẻ sản phẩm trên mạng xã hội.


<a name = "3"></a>
## 3. Cài Đặt
Cách tải :
```
git clone https://github.com/ADELA-04/aloha-wordpress.git
```
<a name = "4"></a>
## 4. Sử Dụng

Mục đích sử dụng cho mục đích cá nhân học tập.

### 4.1. Các Tiện Ích

Project bao gồm tất cả các phần học thuật về website mã nguồn mở

### 4.2. Contributing

Hướng dẫn về cách đóng góp vào dự án của bạn và hướng dẫn cách tạo pull request.
```
git remote add origin https://github.com/ADELA-04/aloha-wordpress.git
git branch -M main
git push -u origin main
```

Hướng dẫn cách cập nhật code "pull code về"
```
cd aloha-wordpress
git pull origin main
```

### 4.3. Tác Giả

- Tên Tác Giả : Đỗ Thị Thơm
- Địa Chỉ Gmail : dothom07082004@gmail.com

### Giấy Phép

Không có giấy phép!









