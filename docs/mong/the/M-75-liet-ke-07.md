# M-75 — Vấn đề chỉ liệt kê được — Chương 07

## Tổng quan
- Tổng số bản ghi: **28** (**17** `CHI_LIET_KE`, **11** `BO_QUA`).
- Tỷ lệ phủ câu kích hoạt: **100%** (25/25).
- Dò mở rộng `LUAT` (Luật 4 + regex mục đích/gieo trồng): trúng **17** câu, đã có trong `07.jsonl`: **17**, chưa ghi: **0**.

## Kiểm tra luật M-75
- Luật 1 & 4: Giữ `CHI_LIET_KE` cho `0701.10` (làm giống), `0701.90.10` (khoai tây chiên SEN + điều kiện giống `sen:07019010:1#4`), `07.11` + `cg:5#1` (không phù hợp dùng ngay được), và 10 dòng đậu khô `Phù hợp để gieo trồng` (`0713.10.10–0713.90.10`).
- Luật 1 & 3: Đánh `BO_QUA` cho `bieu:0712#1` (trúng nhầm mẫu "ở dạng bột"), mô tả thực vật học/công dụng minh hoạ, và các câu loại trừ M-72 sang `12.11`, `12.14`.

## Kết quả cổng
- `khuon.mjs`: 0 lỗi; `cong.mjs` Cổng 3, 4, 5: 0 lỗi; `liet-ke-test.mjs`: ĐẠT.
