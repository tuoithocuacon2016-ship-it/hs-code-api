# M-75 — Vấn đề chỉ liệt kê được — Chương 06

## Tổng quan
- Tổng số bản ghi: **8** (**6** `CHI_LIET_KE`, **2** `BO_QUA`).
- Tỷ lệ phủ câu kích hoạt: **100%** (7/7).
- Dò mở rộng `LUAT` (Luật 4 + regex mục đích/nhân giống): trúng **3** câu, đã có trong `06.jsonl`: **3**, chưa ghi: **0**.

## Kiểm tra luật M-75
- Luật 1 & 4: Giữ `CHI_LIET_KE` cho `06.03`/`06.04` (lời biểu), `chuong:06:cg:1#1` (để trồng hoặc trang trí), `chuong:06:kq:2#3` (ranh giới củ dùng để trồng vs thực phẩm) và tiêu chí giữ đặc tính cơ bản (`0603:ct:1#2`, `0604:ct:1#2`).
- Luật 3: `chuong:06:kq:2#1` (lặp lại) và `nhom:0604:ct:4#1` (loại trừ M-72 sang 12.11/14.01) đánh `BO_QUA`.

## Kết quả cổng
- `khuon.mjs`: 0 lỗi; `cong.mjs` Cổng 3, 4, 5: 0 lỗi; `liet-ke-test.mjs`: ĐẠT.
