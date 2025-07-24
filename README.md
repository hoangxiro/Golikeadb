🔥 HƯỚNG DẪN CÀI TOOL GOLIKE ADB – Hoangdaixu1.6.py  
👨‍💻 Tác giả: Trần Đình Hoàng – @hoangdaixu

━━━━━━━━━━━━━━━  
📲 BƯỚC 1: CÀI ĐẶT TERMUX + PYTHON  

termux-setup-storage  
pkg update && pkg upgrade -y  
pkg install python php git -y  
pip install --upgrade pip  
hoặc
termux-setup-storage && pkg update && pkg upgrade -y && pkg install python php && pkg install python-pip && pip install --upgrade pip 

🔁 Nếu có hỏi [Y/N] → nhập y

━━━━━━━━━━━━━━━  
🧠 BƯỚC 2: CÀI UBUNTU QUA PROOT-DISTRO  

pkg install proot-distro android-tools -y  
proot-distro install ubuntu  
proot-distro login ubuntu

hoặc 
pkg update -y && pkg upgrade -y && pkg install -y proot-distro android-tools && proot-distro install ubuntu && proot-distro login ubuntu && apt update -y && apt upgrade -y && apt install -y python3 python3-pip android-tools-adb

━━━━━━━━━━━━━━━  
💻 BƯỚC 3: SETUP MÔI TRƯỜNG TRONG UBUNTU  

apt update && apt upgrade -y  
apt install python3 python3-pip git android-tools-adb -y

━━━━━━━━━━━━━━━  
🚀 BƯỚC 4: CÀI TOOL HOANGDAIXU GOLIKE  

cd ~  
git clone https://github.com/deno4908/GOLIKE_TOOL  
cd GOLIKE_TOOL  
pip install -r requirements.txt --break-system-packages --force-reinstall --ignore-installed

━━━━━━━━━━━━━━━  
🎯 BƯỚC 5: CHẠY TOOL  

python3 main.py

━━━━━━━━━━━━━━━  
📶 KẾT NỐI ADB KHÔNG DÂY (WIRELESS)  

🔸 Ghép đôi thiết bị (Pair):  
adb pair IP:PORT  
👉 Nhập mã PIN hiện trên thiết bị

🔸 Kết nối thiết bị:  
adb connect IP:PORT  
📌 IP và PORT lấy trong “ADB Wireless” trong tùy chọn nhà phát triển điện thoại

━━━━━━━━━━━━━━━  
📂 CHẠY TOOL `Hoangdaixu1.6.py` RIÊNG  

🔸 Tải tool:  
cd /sdcard/Download/  
wget https://raw.githubusercontent.com/hoangxiro/Golikeadb/refs/heads/main/Hoangdaixu1.6.py  

🔸 Chạy tool:  
python3 Hoangdaixu1.6.py

━━━━━━━━━━━━━━━  
✨ LƯU Ý:  
🔁 Mỗi lần mở Termux, cần chạy lại:  
proot-distro login ubuntu
xong nhập adb connect ip:port để kết nối 

⚠️ Nếu bị lỗi `adb: command not found`, chạy:  
apt install android-tools-adb -y
