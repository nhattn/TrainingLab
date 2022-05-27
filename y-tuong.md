# Ý tưởng với người học lập trình

> Cảm hứng từ một bộ phim về hai anh em say mê tính toán năm con gì của một
> năm bất kỳ người đề xướng một năm nào đó.

## Yêu cầu

Với các ngôn ngữ lập trình `C++`, `Node`, `Python`, `Golang` chúng ta xây
dựng một ứng dụng như sau

\- Nhập vào một năm bất kỳ hay cho ra năm đó là năm con gì `Tý`, `Sửu`, `Dần`
`Mão`, `Thìn`, `Tỵ`, `Ngọ`, `Mùi`, `Thân`, `Dậu`, `Tuất`, `Hợi`

**Ví dụ**: Nhập vào là `1970` thì kết quả là `Tuất`

> **Lưu ý**: Có thể sử dụng ý tưởng bất kỳ mà chúng ta biết để đưa ra một
> thuật toán và có kết quả. hoặc tham khảo trên mạng (**không sao chép mã
> nguồn**)

## Mở rộng thêm

Từ ứng dụng trên hay cho biết năm đó có nhuần hay không áp dụng đơn giản
với lịch tây (_có thể thao khảo thuật toán trên mạng_) (**không sao chép
mã nguồn**)

# Ý tưởng với người học xử lý ngôn ngữ tự nhiên

Với bài học đầu tiên là tiền xử lý dữ liệu thì cho vào một đoạn chữ bất kỳ
hãy làm sạch nó và chuẩn hóa tiếng việt, kiểm tra từ trong đoạn thuộc loại
`chữ việt nam`, `chữ số`, `ký tự`, `viết tắt`, `từ mượn` (_những từ của quốc
gia khác được thêm vào trong đoạn_)

**Có thể xuất ra đơn giản như sau**

*Đầu vào*

> `Liên quan đến sự việc, sáng 4/4 trao đổi với Báo Sức khỏe và Đời sống,
> ông Ddinh Viết Quang (chủ tịch xã Tân Thịnh – huyện Nam Trực – tỉnh Nam
> Định) cho biết, Trần Thị Thanh H. kết hôn cùng anh H. (người tại địa phương)
> từ thasng 10 năm 2016.`

*Đầu ra*

```
Liên    TV
quan    TV
đến     TV
sự      TV
việc    TV
,       KT
sáng    TV
4       NB
/       KT
4       NB
trao    TV
đổi     TV
với     TV
Báo     TV
Sức     TV
khỏe    TV
và      TV
Đời     TV
sống    TV
,       KT
ông     TV
Đinh    TV
Viết    TV
Quang   TV
(       KT
chủ     TV
tịch    TV
xã      TV
Tân     TV
Thịnh   TV
-       KT
huyện   TV
Nam     TV
Trực    TV
-       KT
tỉnh    TV
Nam     TV
Định    TV
)       KT
cho     TV
biết    TV
,       KT
Trần    TV
Thị     TV
Thanh   TV
H.      VT
kết     TV
hôn     TV
cùng    TV
anh     TV
H.      VT
(       KT
người   TV
tại     TV
địa     TV
phương  TV
)       KT
từ      TV
tháng   TV
10      NB
năm     TV
2016    NB
.       KT
```

Trong đó ký tự `UTF-8` là `–` được thay thế bằng `-`, `Ddinh` &rarr; `Đinh`
`thasng` &rarr; `tháng`

Với bài học phân loại chúng ta tìm chủ đề của đoạn chữ gửi vào là gì?

**Ví dụ**

> Chị ơi Em đặt thêm một chai này được không ạ?
>
> Được nha Bé ơi hàng vẫn có sẵn nhé.

**Kết quả**

`Chị ơi Em đặt thêm một chai này được không ạ?` &rarr; `đặt hàng`

`Được nha Bé ơi hàng vẫn có sẵn nhé.` &rarr; `hỗ trợ khách hàng`

Chúc mọi người lập trình vui vẻ, chào trân trọng và hợp tác cùng mọi người.

Đà Lạt 28/05/2022
