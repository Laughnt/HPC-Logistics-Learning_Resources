Bất kỳ DN nào muốn nhắm được nhu cầu KD thì cần nhắm được nhu cầu của Thị trường - yêu cầu.
	Là khối lượng hàng hoá hoặc số lượng hành khách mà khácch hàng yêu cầ nhà vận tải chuyên chở trong kỳ.
## Nguồn gốc phát sinh
SỰ phân bổ tài nguyên thiên nhiên không đều
	Trên thế giới tài nguyên thiên nhiên rất đa dạng, và phân bố không đồng đều (dầu mỏ, quặng, khoáng sản), giới hạn nên vận chuyển tài nguyên thiên nhiên tới nơi sản xuất.
	Sau khi sản xuất xong, sản phẩm lại được chuyển đến người tiêu dùng.

SỰ phân bổ lực lượng sản xuất không đều
	Con người thường ở nơi Thiên nhiên ưu đãi -> trên thế giới xuất hiện các quần thể cư dân, tạo nên sự cách biệt với nơi sản xuất -> vận chuyển con người từ nơi ở đến nơi sản xuất
SỰ phân bố cơ sở văn hoá không đều
	Cơ sở văn hoá bao gồm danh lam thắng cảnh, di tích lịch sử -> con người cần thoả mãn nhu cầu giải trí
SỰ chuyên môn hoá sản xuất.
	- Chuyên môn hoá là khả năng của riêng bên sản xuất.
	//Công ty sản xuất nhiên liệu và bên chuyên về lắp ráp, phân phối -> chuyển công cụ sản xuất và nhiên liệu qua 2 bên - Thế giới di động.
	1 sản phẩm bán ra trên thị trường có sự xuất hiện của nhiều DN tham gia, mỗi DN sản xuất 1 bộ phận theo năng lực chuyên môn của mình.
		Mình đưa các chi tiết phụ tùng về nơi sản xuất chính -> SP cuối cùng.
//Viettel để ý người dùng.


#### Biến động của nhu cầu vận chuyển 
- Thời gian
	- Có những tuần trong năm, nhu cầu vận chuyển tăng rất cao hoặc thấp. Biến động của nhu cầu vận chuyển thường có tính quy luật.
	- Những ngày lễ Tết, DN nông lâm ngư nghiệp thay đổi/người dân có nhu cầu vận chuyển tăng cao. Những tuần có nhu cầu vận chuyển tăng, các DN vận tải tập trung toàn bộ phương tiện và nhân lực để đáp ứng nhu cầu thị trường. 
	- Những khoản thời gian mà nhu cầu vận chuyển giảm mạnh, DN chủ động cho thuê phương tiện - tránh dư thừa năng lực vận tải, ảnh hưởng xấu đến kết quả kinh doanh
//Viettel thuê sẽ giảm đi chi phí thay vì mua, nó sẽ liên quan đến vận chuyển ít. DƯ THỪA phương tiện -> chi phí.
- Không gian
	- Biểu hiện trên cùng một tuyến vận tải, quá trình nhập lại thì nhu cầu vận chuyển của hàng hoá đó lại giảm.
	- 1 chặng/quá trình -> tăng/giảm (hàng nông sản VN [[Study/HPC/02_Nhập môn Logistics/xuất nhập khẩu]] sang Châu Âu, nhưng không ngược lại)
	- Để nâng cao:
	  Các nhà vận tải thường đa dạng mặt hàng bằng cách container hoá hàng hoá vận tải

## Phương pháp dự báo nhu cầu vận chuyển
//Viettel sẽ huy động thêm vài đội xe, dựa trên nhu cầu dự báo (3 phương pháp nhu cầu vận chuyển)
	[Ngoại suy](https://vi.wikipedia.org/wiki/Ngoại_suy)
		Dựa trên những dữ liệu từ quá khứ, chúng ta đưa ra mức dự báo trong tương lai. Phương pháp này thường được dự báo nhu cầu vận chuyển theo quý hàng năm.   
		**Nhược điểm:** Định tính được, nhưng số liệu sai.
	[Hệ số vận tải](https://en.wikipedia.org/wiki/Transport_coefficient)
		Cho biết hàm lượng, tỉ trọng của giá trị sản phẩm quốc dân phải trải qua quá trình vận tải. Giả sử hệ số vận tải của QG là 0,02 - ứng với 100 đơn vị GDP, sẽ có 2 đơn vị trải qua hoạt động vận tải -> nhu cầu vận chuyển GDP và hệ số vận tải.
				${\mathbf {Q}=\mathbf{k}. \mathbf{GDP}}$ hay ${\displaystyle \mathbf {J} _{k}=\gamma _{k}. \mathbf {X} _{k}}$
			Q: Nhu cầu vận tải
			K: Hệ số vận tải
			GDP: Tổng sản phẩm cung ứng
		Phương pháp này cho độ tin cậy khá cao thông qua việc xác định các nhân tố ảnh hưởng -> tác động đến thế giới.
	[[Phân tích hồi qui logistic.pdf]] (Xem thêm [Phân tích số liệu bằng biểu đồ R](http://vietsciences.free.fr/khaocuu/nguyenvantuan/bieudoR/ch8-phantichsolieu.htm) )
		Hàm số toán học - Liên hệ các nhân tố ảnh hưởng - mùa vụ/giá xăng.
		Thời gian chúng ta ra khỏi nhà, cuối tuần hay đầu tuần, liệt kê qua một cái bảng.
%%Đại học sẽ sử dụng phần mềm, không tính toán tay được. Thời tiết, dự báo của trời trong những ngày tiếp theo. Dữ kiện quá khứ -> tương lai%%
## Chỉ tiêu đánh giá chất lượng dự báo
Dự báo là phỏng đoán sự việc nào đó trong tương lai. Dự báo nhu cầu vận chuyển nhằm nhận biết độ lớn của nhu cầu vận chuyển để đưa ra các quyết đinh đầu tư:
	Tiền vốn
	Phương tiện
	Con người
Để đánh giá độ chính xác của dự báo, chúng ta thông qua các chỉ tiêu sau:
#### Độ lệch tuyệt đối
	Độ lệch tuyệt đối = giá trị dự báo - giá trị thực tế.
	//Thời tiết hôm nay 14 độ, lệch 4 độ với hôm nay
Dự báo nhu cầu vận tải của năm 2024 là 20 tỉ đô. Nhu cầu vận tải thực tế, 18 tỷ đô.
#### Độ lệch tương đối
	Độ lệch tương đối = độ lệch tuyệt đối / giá trị thực tế.
// Nhu cần vận tải thực tế (giá trị thực tế) khác với nhu cầu vận chuyển.
Ví dụ:
1) 21.5 tỷ và 22.575 tỷ
2) Độ lệch tuyệt đối = 902 - 930 = -68 -> Độ lệch tương đối = 0,07
__
1) KN nhu cầu vận chuyển 
2) Biến động của nhu cầu vận chuyển.
	1) Nguyên nhân, giải pháp nhằm hạn chế ảnh hưởng biến động
3) Nêu các phương pháp dự báo nhu cầu vận chuyển.
4) Các chỉ tiêu đánh giá nhu cầu dự báo.