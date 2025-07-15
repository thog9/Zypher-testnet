# Zypher Testnet Scripts 🚀

Một bộ sưu tập các tập lệnh Python giúp tương tác dễ dàng hơn với Zypher Testnet, bao gồm đăng nhập, kiểm tra danh sách trắng, tạo NFT và các hoạt động liên quan khác. Được xây dựng với asyncio, aiohttp, web3.py và được thiết kế cho hoạt động đa ví với hỗ trợ đa ngôn ngữ.

🔗 Register: [Zypher Testnet](https://ai.zypher.network/airdrop)

## ✨ Tính năng

### Tính năng chung

- **Hỗ trợ đa tài khoản**: Thực hiện các thao tác trên nhiều ví bằng khóa riêng từ file `pvkey.txt`.
- **Giao diện CLI màu sắc**: Sử dụng `colorama` để tạo đầu ra sinh động với viền và màu sắc.
- **Thực thi không đồng bộ**: Tận dụng `asyncio` để tương tác blockchain hiệu quả.
- **Xử lý lỗi mạnh mẽ**: Phát hiện và báo cáo lỗi giao dịch blockchain và RPC.
- **Hỗ trợ song ngữ**: Hỗ trợ đầu ra bằng tiếng Anh và tiếng Việt tùy theo lựa chọn người dùng.
- **Hỗ trợ proxy**: Tùy chọn sử dụng proxy qua file `proxies.txt` cho các yêu cầu mạng.

### Các Script Bao Gồm

1. **Mint NFT SBT | Shard | OG - G NFT**: Mint NFT [ Bao gồm SBT, Shard, OG-G NFT ] trên Zypher Testnet.
	-  Auto Check WL
	-  Auto Register Subscribe | Galaxe
	-  Auto Mint SBT
	-  Auto Mint Shard
	-  Auto Mint OG - G NFT [ Whitelist ]



## 🛠️ Yêu cầu trước khi sử dụng

Đảm bảo các yêu cầu sau được cài đặt và cấu hình:

- **Python**: Phiên bản 3.8 trở lên.
- **pip**: Trình quản lý gói Python.
- **Các gói phụ thuộc**: Cài đặt qua `pip install -r requirements.txt`. Các gói cần thiết bao gồm: ( `web3.py`, `colorama`, `asyncio`, `eth-account`, `aiohttp_socks` and `inquirer` ).
- **pvkey.txt**: File chứa khóa riêng (mỗi dòng một khóa) để tự động hóa ví.
- **proxies.txt** (tùy chọn): Địa chỉ proxy cho các yêu cầu mạng.


## 📦 Cài đặt


Thực hiện các bước sau để thiết lập dự án:

1. **Clone this repository:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
git clone https://github.com/thog9/Zypher-testnet.git
```
```sh
cd Zypher-testnet
```
2. **Install Dependencies:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
pip install -r requirements.txt
```
3. **Prepare Input Files:**
- Mở `pvkey.txt`: Thêm khóa riêng của bạn (mỗi dòng một khóa) vào thư mục gốc.
```sh
nano pvkey.txt
```

- Tạo các file `proxies.txt` cho các thao tác cụ thể:
```sh
nano proxies.txt
```
4. **Run:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
python main.py
```
- Chọn ngôn ngữ (Tiếng Việt/Tiếng Anh).

## 📬 Liên hệ

Kết nối với chúng tôi để được hỗ trợ hoặc cập nhật:

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099) 

----

## ☕ Hỗ trợ chúng tôi:
Yêu thích các script này? Hãy mời chúng tôi một ly cà phê!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)
