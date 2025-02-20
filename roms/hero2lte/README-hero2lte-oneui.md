Tính Năng:
### Cảnh Báo Quan Trọng: ROM này đã được mod và tối ưu, có thể ảnh hưởng đến bảo hành nếu không thực hiện đúng cách

### Tổng quan
- Android 12 rom gốc Samsung
- Adb tự động
- TCPIP 5555 bật sẵn
- Tự khởi động khi ghim nguồn

Hướng Dẫn Cài Đặt:
### Cảnh Báo Quan Trọng: Vui lòng sao lưu dữ liệu trước khi thực hiện. Không tắt máy trong quá trình cài đặt

### Bước 1: Chuẩn bị
- Boot into TWRP recovery

### Bước 2: Flash Vendor Patch
- Create vendor partition by flashing Create_Vendor zip

### Bước 3: Reboot TWRP
- Reboot into TWRP once Create_Vendor zip if flashed

### Bước 4: Wipe
- Wipe system, data, vendor, cache and dalvik cache

### Bước 5: Install ROM
- Install Port ROM.

### Lưu Ý Quan Trọng: Nếu gặp lỗi bootloop, hãy wipe data và thử cài đặt lại

Yêu Cầu:
### Thiết bị hỗ trợ
- Tất cả models Samsung Galaxy S7E

### Firmware yêu cầu
- Baseband mới nhất
- Bootloader mới nhất

### Công cụ cần thiết
- TWRP mod tại [tại đây](https://github.com/ananjaser1211/android_device_samsung_hero/releases/tag/3.7.0_9-hero2lte-20231231)
- Create Vendor zip [tại đây](https://drive.google.com/drive/folders/1VdET4yjVvHdWxlDIXobgxaEyWoz_WJju)
- Bootloader đã mở khóa
- Windows 10/11
- Samsung USB Driver
- Odin v3.14.4
- WinRAR hoặc 7-Zip