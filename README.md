# Agoda Recommender System
## Giới thiệu
Agoda Recommender System là một hệ thống đề xuất giúp người dùng tìm thấy những khách sạn và resort phù hợp nhất dựa trên sở thích cá nhân và hành vi của họ. Hệ thống sử dụng hai phương pháp chính:
* Content-Based Filtering: Đề xuất khách sạn dựa trên các thuộc tính của khách sạn mà người dùng đã tương tác hoặc thể hiện sự quan tâm. Ví dụ, nếu bạn thích các bộ phim hành động, hệ thống sẽ gợi ý các bộ phim hành động khác có nội dung tương tự.
* Collaborative Filtering: Đề xuất khách sạn dựa trên những người dùng khác có sở thích tương tự. Ví dụ, nếu người dùng A và B đều thích một nhóm sản phẩm giống nhau, và A thích một sản phẩm mới, thì sản phẩm đó có thể được đề xuất cho B.
## Đề xuất khách sạn
### Content-Based
Ví dụ khi chọn 1 khách sạn, giả sử chọn 'Khách sạn Mường Thanh Luxury Nha Trang (Muong Thanh Luxury Nha Trang Hotel)'
<p align="center">
  <img src="demo/content_based/choose_hotel.png" width=500><br/>
  <i>Thông tin khách sạn</i>
</p>

Đề xuất dựa trên thông tin chi tiết, địa chỉ của khách sạn đã chọn
<p align="center">
  <img src="demo/content_based/show_re_1.png" width=500><br/>
  <i></i>
</p>
<p align="center">
  <img src="demo/content_based/show_re_2.png" width=500><br/>
  <i>Thông tin chi tiết, địa chỉ của khách sạn được đề xuất</i>
</p>

### Collaborative Filtering
