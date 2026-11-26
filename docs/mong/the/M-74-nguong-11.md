# M-74 — Ngưỡng số & phân dải anh em — Chương 11

## Tổng quan
- Tổng số bản ghi: **20** (**17** `NGUONG`, **1** `DINH_NGHIA`, **2** `TACH_ANH_EM`, **1** nút nhận `phuDinh`).
- Phạm vi áp dụng: Chương 11 (Sản phẩm xay xát; malt; tinh bột; inulin; gluten lúa mì).

## Đối soát rà soát số + đơn vị & `ranh-gioi` (Luật 1–7)
- Luật 5 & 7 (Chú giải 2 Chương 11): Gắn ngưỡng bảng `ket#3..8` (`tinh bột > 45%`, `tro ≤ 2,5% / 2% / 1,6%`, `tỷ lệ lọt qua sàng 315 micron ≥ 80%` / `500 micron ≥ 90%`) trực tiếp xuống nút biểu (`bieu:1101`, `110220`, `11029010`, `11029020`). Không tạo `NGUONG` riêng cho thông số phép đo `315 micron` / `500 micron` / `2 mm` / `1,25 mm` mà gộp vào `daiLuong` kèm đơn vị `%`.
- Luật 1 & 2: `bieu:11029090` (`Loại khác`) gắn `TACH_ANH_EM` `phuDinh: ["bieu:11029010", "bieu:11029020"]` (và không gộp chồng ngưỡng tro đa loài vào cùng 1 nút).
- Luật 5 (Chú giải 3 Chương 11): `DINH_NGHIA` `"tấm"` trên `chuong:11`; `≥ 95% lọt sàng 2 mm` trên `bieu:110313`; `≥ 95% lọt sàng 1,25 mm` trên `bieu:110311` và `bieu:110319`.
- `bieu:1101001`: hàm lượng gluten bổ sung `≤ 10%` (`nhom:1101:ct:2#2`). `bieu:110320`: chất dính dạng viên `≤ 3%` (`phan:II:cg:1#1`).
- Bỏ qua có căn cứ: `1101:ct:5#1`/`1102:ct:6#1` (cả hai vế ≥40% / <40% cacao đều bị loại khỏi Chương 11 sang 18.06/19.01), `1103:ct:7#1` (lặp lại `phan:II:cg:1#1`), `1108:ct:2#4` (nhiệt độ hồ hoá 60°C mô tả tính chất), `1109:ct:2#1` (tỷ lệ gliadin+glutenin mô tả thành phần tự nhiên 85–95%).

## Kết quả cổng
- `khuon.mjs`: 0 lỗi; `cong.mjs` Cổng 3, 4, 5: 0 lỗi.
