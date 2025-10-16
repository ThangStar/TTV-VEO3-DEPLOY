# TTV-VEO3 - AI Video Generation Tool

Công cụ tạo video AI tự động từ hình ảnh sử dụng VEO3 API với giao diện đồ họa.

![Whisk_2574534f37ab9eca6664168ee35c2f72dr](https://github.com/user-attachments/assets/87ed786d-4683-4318-8b24-45fefabe9f92)

## ⚙️ Cấu hình

### Cấu hình License
- Nhập license key vào ô "License Key"
- Nhấn "Verify License" để xác minh
- License hợp lệ sẽ được lưu tự động

### Tạo video từ hình ảnh
1. **Chọn hình ảnh**: Nhấn "Browse" để chọn file ảnh
2. **Nhập prompt**: Mô tả video muốn tạo (tiếng Anh)
3. **Tạo video**: Nhấn "Generate Video"
4. **Theo dõi tiến trình**: Xem trạng thái trong cửa sổ log
5. **Tải video**: Video hoàn thành sẽ tự động tải về thư mục `temp/videos/`

### Tạo hàng loạt từ Excel
1. **Import Excel**: Nhấn "Import Scenes from Excel" để chọn file Excel
2. **Xem trước**: Kiểm tra danh sách scenes đã import
3. **Tạo hàng loạt**: Nhấn "Batch Generate" để tạo tất cả video
4. **Theo dõi**: Xem tiến trình của từng video trong danh sách

### File cấu hình chính:
- `config.py`: Cài đặt API và authorization
- `temp/json/setting.json`: Cài đặt ứng dụng
- `temp/json/scene.json`: Danh sách scenes

### File Excel template:
- Cột A: Tên scene
- Cột B: Đường dẫn hình ảnh
- Cột C: Prompt mô tả video
- Cột D: Trạng thái (tự động cập nhật)

## 🔧 Troubleshooting

### Lỗi thường gặp:
1. **"License không hợp lệ"**: Kiểm tra lại license key
2. **"Không kết nối được Discord"**: Kiểm tra internet và bot token
3. **"Lỗi upload ảnh"**: Kiểm tra định dạng ảnh (JPG/PNG)
4. **"Video generation failed"**: Kiểm tra prompt và thử lại

### Log và Debug:
- Xem log chi tiết trong cửa sổ ứng dụng
- Kiểm tra file `temp/json/` để debug
- Restart ứng dụng nếu gặp lỗi

## 📞 Hỗ trợ

- Facebook: https://www.facebook.com/mt.meow.meow/
- Discord: Sử dụng bot tích hợp trong ứng dụng

---
**Lưu ý**: Đảm bảo có license hợp lệ và kết nối internet ổn định để sử dụng ứng dụng.
