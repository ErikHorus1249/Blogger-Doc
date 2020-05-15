

By **[Erik Horus](https://github.com/ErikHorus1249)**
Date : 14/05/2020 
![Top 10 trang web cho tạo blog đơn giản miễn phí tốt nhất. - WEBICO ...](https://blog.webico.vn/wp-content/uploads/2016/04/Blogger-blogging-platform.jpg)
# Bài tập số 1 : Xây dựng một website đơn giản bằng Blogger 

##  I . Mục đích : 
- Tạo ra một trang web có tính hữu dụng và dễ dàng khởi tạo cũng như vận hành
- Sử dụng các template có sẵn đảm bảo tính an toàn cho trang blog.
- Ứng dụng các kiến thức cơ bản của môn lập trình web như html/css , javascript để tùy biến sâu trên trang khởi tạo.

## II. Khởi tạo
**1. Tạo một tài khoản để sử dụng** **[Blogger](https://www.blogger.com/about/?r=1-null_user)** qua các bước đơn giản, quan trọng là bạn phải có một tài khoản **Google** .
**2. Tạo một blogspot** 
Chọn vào mục `blog mới` để tạo . Điền thông tin cơ bản như tên của blog và địa chỉ truy cập.

![](https://i.imgur.com/WOqPHf3.png)

**3. Tìm một template có sẵn để sử dụng cho blog**
Có rất nhiều trang cung cấp sẵn các template đa dạng về hình thức và mục đích sử dụng mà bạn có thể tìm thấy trên Google như : 
	- **[Way2themes](https://www.way2themes.com/)**
	- ![Way2themes | Free Blogger Templates](https://1.bp.blogspot.com/-Ix3jJT7n6LM/WNd2dr5hJcI/AAAAAAAACw8/FQ1ryBsMNdYfqbQCDpnZHi9RHtvQIquOwCK4B/s1600/logo.png)
	- [**Btemplates**](https://btemplates.com/)
	- ![](https://btemplates.com/wp-content/themes/peualiztli/images/blogger-templates-btemplates.png

Ở blog hiện tại thì mình sử dụng template **Celfie** của Way2themes

**4. Giải nén file zip và tùy chỉnh trang**

![](https://i.imgur.com/4nk4u0M.png)



 Mở file `.xml` bằng một trình soạn thảo bất kì và `copy` nội dung của nó 
 Quay lại trang **blogger** vào mục `Chủ đề` chọn `Sao lưu/khôi phục`
 sau đó paste code vào khung `Chỉnh sửa html`.
 
 

![](https://i.imgur.com/uimWsQq.png)

## III. Tùy chỉnh
### 1. Bố cục 
Bố cục có thể tùy chỉnh một cách dễ dàng như thay đổi vị trí các phần của trang thêm các tính năng như **bản đồ**, **khung chat messenger**, . . .

![](https://i.imgur.com/T8ONO5n.png)
**a. Chèn logo cho trang** 
Hãy tạo trước một logo bạn có thể tạo logo từ [**hatchful**](https://hatchful.shopify.com/)
![Hatchful](https://cdn.shopify.com/shopifycloud/hatchful-web/assets/5332ffcb554a06a5ecd7351a5309f011.svg)
Sau đó vào phần `header logo` được tạo từ phần thêm tiện ích sau đó post ảnh từ máy tính lên là xong.

![](https://i.imgur.com/cTUQsyz.png)
![](https://i.imgur.com/4uFqH2h.png)


**b.Thêm khung chat** : chọn `Thêm tiện ích` -> `HTML/JavaScipt`


![](https://i.imgur.com/9GuPrFZ.png)

paste đoạn code sau vào :

    <style>.fb-livechat,.fb-widget{display:none}.ctrlq.fb-button,.ctrlq.fb-close{position:fixed;right:25px;cursor:pointer}.ctrlq.fb-button{z-index:1;background:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjwhRE9DVFlQRSBzdmcgIFBVQkxJQyAnLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4nICAnaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQvc3ZnMTEuZHRkJz48c3ZnIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDEyOCAxMjgiIGhlaWdodD0iMTI4cHgiIGlkPSJMYXllcl8xIiB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCAxMjggMTI4IiB3aWR0aD0iMTI4cHgiIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxnPjxyZWN0IGZpbGw9IiMwMDg0RkYiIGhlaWdodD0iMTI4IiB3aWR0aD0iMTI4Ii8+PC9nPjxwYXRoIGQ9Ik02NCwxNy41MzFjLTI1LjQwNSwwLTQ2LDE5LjI1OS00Niw0My4wMTVjMCwxMy41MTUsNi42NjUsMjUuNTc0LDE3LjA4OSwzMy40NnYxNi40NjIgIGwxNS42OTgtOC43MDdjNC4xODYsMS4xNzEsOC42MjEsMS44LDEzLjIxMywxLjhjMjUuNDA1LDAsNDYtMTkuMjU4LDQ2LTQzLjAxNUMxMTAsMzYuNzksODkuNDA1LDE3LjUzMSw2NCwxNy41MzF6IE02OC44NDUsNzUuMjE0ICBMNTYuOTQ3LDYyLjg1NUwzNC4wMzUsNzUuNTI0bDI1LjEyLTI2LjY1N2wxMS44OTgsMTIuMzU5bDIyLjkxLTEyLjY3TDY4Ljg0NSw3NS4yMTR6IiBmaWxsPSIjRkZGRkZGIiBpZD0iQnViYmxlX1NoYXBlIi8+PC9zdmc+) center no-repeat #0084ff;width:35px;height:35px;text-align:center;bottom:65px;border:0;outline:0;border-radius:60px;-webkit-border-radius:60px;-moz-border-radius:60px;-ms-border-radius:60px;-o-border-radius:60px;box-shadow:0 1px 6px rgba(0,0,0,.06),0 2px 32px rgba(0,0,0,.16);-webkit-transition:box-shadow .2s ease;background-size:80%;transition:all .2s ease-in-out}.ctrlq.fb-button:focus,.ctrlq.fb-button:hover{transform:scale(1.1);box-shadow:0 2px 8px rgba(0,0,0,.09),0 4px 40px rgba(0,0,0,.24)}.fb-widget{background:#fff;z-index:2;position:fixed;width:280px;height:320px;overflow:hidden;opacity:0;bottom:0;right:24px;border-radius:6px;-o-border-radius:6px;-webkit-border-radius:6px;box-shadow:0 5px 40px rgba(0,0,0,.16);-webkit-box-shadow:0 5px 40px rgba(0,0,0,.16);-moz-box-shadow:0 5px 40px rgba(0,0,0,.16);-o-box-shadow:0 5px 40px rgba(0,0,0,.16)}.fb-credit{text-align:center;margin-top:8px}.fb-credit a{transition:none;color:#bec2c9;font-family:Helvetica,Arial,sans-serif;font-size:12px;text-decoration:none;border:0;font-weight:400}.ctrlq.fb-overlay{z-index:0;position:fixed;height:100vh;width:100vw;-webkit-transition:opacity .4s,visibility .4s;transition:opacity .4s,visibility .4s;top:0;left:0;background:rgba(0,0,0,.05);display:none}.ctrlq.fb-close{z-index:4;padding:0 6px;background:#365899;font-weight:700;font-size:11px;color:#fff;margin:8px;border-radius:3px}.ctrlq.fb-close::after{content:'x';font-family:sans-serif}</style>
    
    <div class="fb-livechat">
      <div class="ctrlq fb-overlay"></div>
      <div class="fb-widget">
        <div class="ctrlq fb-close"></div>
        <div class="fb-page" data-href="https://www.facebook.com/kungfuexcel/" data-tabs="messages" data-width="245" data-height="285" data-small-header="true" data-hide-cover="true" data-show-facepile="false">
          <blockquote cite="https://www.facebook.com/kungfuexcel/" class="fb-xfbml-parse-ignore"> </blockquote>
        </div>
        
      </div>
      <a href="https://m.me/kungfuexcel" title="Send us a message on Facebook" class="ctrlq fb-button"></a> 
    </div>
    	
    <script src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.9"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <script>$(document).ready(function(){var t={delay:125,overlay:$(".fb-overlay"),widget:$(".fb-widget"),button:$(".fb-button")};setTimeout(function(){$("div.fb-livechat").fadeIn()},8*t.delay),$(".ctrlq").on("click",function(e){e.preventDefault(),t.overlay.is(":visible")?(t.overlay.fadeOut(t.delay),t.widget.stop().animate({bottom:0,opacity:0},2*t.delay,function(){$(this).hide("slow"),t.button.show()})):t.button.fadeOut("medium",function(){t.widget.stop().show().animate({bottom:"30px",opacity:1},2*t.delay),t.overlay.fadeIn(t.delay)})})});</script>

Sau đó thay đường dẫn : 

    https://www.facebook.com/kungfuexcel/  
    https://m.me/kungfuexcel/
bằng đường dẫn tới page facebook của bạn.

![](https://i.imgur.com/RT9h8bg.png)
**c. Chèn trang Facebook liên hệ và khung video** 

Tạo mục hiển thị trang facebook trong phần `chỉnh sửa bố cục` chọn `HTML/JavaScript` 
Thêm đoạn code sau :

    <center><div class="fb-page" data-href="https://www.facebook.com/AdobeIllustrator" data-width="360" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"></div></center>

Thay đổi link tại `href` bằng link trang facebook của bạn để hoàn thành.

![](https://i.imgur.com/NBlmPEE.png)

Tạo mục hiển thị video bằng cách truy cập **[Youtube](youtube.com)** tại video bạn muốn hiển thị chọn `share` -> `Nhúng`

![](https://i.imgur.com/L3SGM4H.png)

sau đó sao chép link vào phần tạo tiện ích ở trên.

![](https://i.imgur.com/V9clZkz.png)
**d. Chèn trang Google map** 
Trước tiên truy cập vào trang [**Google Maps**](https://www.google.com/maps/@9.779349,105.6189045,11z?hl=vi-VN) Xác định vị trí của bạn sau đó chọn  `chia sẻ hoặc nhúng bản đồ`  

![](https://i.imgur.com/gN16hdm.png)![](https://i.imgur.com/aGbmdo1.png)

chọn `Thêm tiện ích` -> `HTML/JavaScipt` -> paste link nhúng bản đồ vào.



![](https://i.imgur.com/9GuPrFZ.png)
### 2. Sửa các mục bằng tiếng anh có sẵn của template

Khi sử dụng template thì sẽ có những phần không cần thiết, màu sắc không ưng ý hoặc các đề nục bằng tiếng anh thì  có thể chỉnh sửa trực tiếp trên code của blog. 
Hãy sử dụng `inspect element` của trình duyệt và một trình soạn thảo nào đó để sửa lại mã nguồn chủ yếu là **CSS**.

![](https://i.imgur.com/8rDAv0i.png)

### 3. Thêm bài viết cho blog 

Để thêm một bài đăng vào trang thì hãy vào mục bài đăng mới sau đó thêm tên của bài đăng, nội dung và ảnh kèm theo.

![](https://i.imgur.com/vcqjsl6.png)



