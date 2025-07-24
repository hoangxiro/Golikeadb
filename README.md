#HELU MẤY MOM 
HD MẤY NÍ CHẠY TOOL GOLIKE NÈ 
B1 : SETUP MÔI TRƯỜNG TERMUX PYTHON
termux-setup-storage && pkg update && pkg upgrade -y && pkg install python php && pkg install python-pip && pip install --upgrade pip 
CỨ HỎI [Y/N] NHẬP Y
SETUP XONG VUỐT BÊN TAY TRÁI NEW CMD TERMUX
pkg update -y && pkg upgrade -y && pkg install -y proot-distro android-tools && proot-distro install ubuntu && proot-distro login ubuntu && apt update -y && apt upgrade -y && apt install -y python3 python3-pip android-tools-adb
CỨ CÓ Y/N CHỌN Y
proot-distro(termux)

Cập nhật hệ thống pkg : pkg update && pkg upgrade
Cho phép truy cập file trong máy : termux-setup-storage
cài proot-distro : pkg install proot-distro
cài Ubuntu : proot-distro install ubuntu
Login ubuntu local : proot-distro login ubuntu
Cập nhật hệ thống : apt update && apt upgrade -y
Cài Python : apt install python3 python3-pip -y
Cài ADB : apt install android-tools-adb 
Cài GIT : apt install git -y 
clone TOOL : git clone https://github.com/deno4908/GOLIKE_TOOL
cd : cd GOLIKE_TOOL
Cài packages : pip install -r requirements.txt --break-system-packages --force-reinstall --ignore-installed
Run TOOL : python3 main.py
ADB(wireless)

pair(ghép đôi) : adb pair {IP}:{PORT} sau đó nhập mã ghép đôi là được
connect(kết nối) : adb connect {IP}:{PORT}
 BẠN CÀI XONG R THÌ  proot-distro login ubuntu
 pair(ghép đôi) : adb pair {IP}:{PORT} sau đó nhập mã ghép đôi là được
connect(kết nối) : adb connect {IP}:{PORT} 
VẬY LÀ LOGIN XONG GIỜ QUAY LẠI TAB 1 TERMUX NHẬP cd /sdcard/Download/ && python Hoangdaixu1.6.py
