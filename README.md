Hi 👋, I'm Mob
Join the Cryptocurrency Market, make money from Airdrop - Retroactive with me
mobonchain Follow

TopAME | Bullish - Cheerful

Hướng Dẫn Cài Đặt Auto Ref - Start Node Dự Án Monad Score
Chức năng: Bao gồm hỗ trợ người dùng Ref cho tài khoản chính, và kích hoạt Node hàng ngày cho tài khoản phụ
Yêu cầu
Proxy và Địa chỉ ví EVM
Cài Node.js nếu chưa có ( Windows ): https://t.me/ToolboxforAirdrop/4
Cấu Trúc File Dữ Liệu
proxy.txt:

Mỗi dòng chứa một proxy theo định dạng:
https://username1:pass@host:port
https://username2:pass@host:port
wallet.txt:

Mỗi dòng chứa một private key của ví Ethereum (không cần kèm địa chỉ ví).
Định dạng:
0xYourWalletAddress1
0xYourWalletAddress1
Cài Đặt Trên Windows
Bước 1: Tải và Giải Nén File
Nhấn vào nút <> Code" màu xanh lá cây, sau đó chọn Download ZIP.
Giải nén file ZIP vào thư mục mà bạn muốn lưu trữ.
Bước 2: Cấu Hình Proxy, Wallet và Token
Mở file proxy.txt và nhâp vào danh sách Proxy theo cấu trúc dữ liệu phía trên
Mở file wallet.txt và nhập vào Địa chỉ ví của các ví EVM bạn muốn sử dụng
Bước 3: Cài Đặt Module
Mở Command Prompt (CMD) hoặc PowerShell trong thư mục chứa mã nguồn.
Cài đặt các module yêu cầu bằng lệnh:
npm install
Bước 4: Chạy Tool
Chạy Ref:
node ref.js
Tự động Start Node
node startNode.js
