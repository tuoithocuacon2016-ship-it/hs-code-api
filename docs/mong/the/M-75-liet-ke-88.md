# M-75 — Vấn đề chỉ liệt kê được — Chương 88

## Tổng quan
- Tổng số bản ghi: **32** (**15** `CHI_LIET_KE`, **17** `BO_QUA`).
- Tỷ lệ phủ câu kích hoạt (ngoài `phan:XVII` đã xử lý tại `XVII.jsonl`): **100%**.
- Số câu `LUAT` rà soát mở rộng (Luật 4): đã kiểm toàn bộ 5 câu `LUAT` trúng mở rộng trong Chương 88; bổ sung trực tiếp `bieu:8804#1`, `bieu:88062#1`, `bieu:880730#1` vào `CHI_LIET_KE`.

## Kiểm tra luật M-75
- Luật 1: Các mục liệt kê minh hoạ và mô tả ứng dụng thông thường (`8804:ct:1#2`, `8805:ct:3#1`, `8807:ct:7#1`, `8807:ct:15#1`) đánh `BO_QUA`; giữ `CHI_LIET_KE` cho điều kiện công dụng/bộ phận luật định (`88.04–88.07`, `8806.2`, `8802:ct:4#1`, `8805:ct:18#1`, `8807:ct:2#1`, `kq:3#1`).
- Luật 2 & 3: Tiêu đề chương (GIR 1), các câu loại trừ M-72 (`8805:ct:19–21`, `8807:ct:3`) và tiêu đề mục có `"có hoặc không người lái"` (`8807:ct:5,13`) đánh `BO_QUA`.

## Kết quả cổng
- `khuon.mjs`: 0 lỗi.
- `cong.mjs` Cổng 3, 4, 5: 0 lỗi.
- `liet-ke-test.mjs`, `test-ho-so-ma.mjs`, `test-ho-so-ma-tra.mjs`, `test-lop-kho.mjs`, `kiem-pham-vi-the.mjs`: ĐẠT.
