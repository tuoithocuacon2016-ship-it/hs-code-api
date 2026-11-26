# M-74 (#1966) — Ngưỡng số và phân dải anh em — Chương 74

- **Khuôn áp dụng:** `ho-so-ma@1` ([`docs/mong/khuon-ho-so-ma.md`](../khuon-ho-so-ma.md), [`docs/decisions/0006-ho-so-van-de-ma-8-so.md`](../../decisions/0006-ho-so-van-de-ma-8-so.md))
- **Kho dữ liệu (`RUT_TU_LUAT`, theo `data/lop-kho.json` trên `main`):**
  - `data/ho-so-ma/nguong/74.jsonl`: **29 bản ghi** (**22 `NGUONG`**, **7 `DINH_NGHIA`**, **3** bản ghi "Loại khác" gắn mảng `phuDinh`: `740819`, `74081190`, `7413009`; dòng `74198090` giữ `TACH_ANH_EM` phủ định theo Luật 2 đã có ở M-76).
- **Đối soát số + đơn vị & `ranh-gioi` (Luật 6):**
  - Tổng câu trúng số+đơn vị (Phần XV + Chương 74 + dòng biểu): **17** (`phan:XV:cg:8:b#1` đã có trong `nguong/XV.jsonl`; **16/16** câu Chương 74 + dòng biểu đã rút thành bản ghi, **0** câu bị bỏ sót; bổ sung thêm `bieu:74198080#1` `300 lít` và `sen:74081910:1#2` phủ `ranh-gioi/740819.json` & `741300.json`; bỏ qua hợp lệ các câu mô tả khoảng tham khảo "thường"/"thông thường" trong chú giải chi tiết/SEN).
- **Tuân thủ quy tắc QT:**
  - Không lấy thông số ví dụ, bảng mẫu hay ước lượng; trích đúng câu của chính nút; không gắn `gir:`, `wco:`, `tb:`; dùng bộ kiểm chung [`scripts/ho-so-ma/nguong-test.mjs`](../../../scripts/ho-so-ma/nguong-test.mjs) và [`scripts/ho-so-ma/cong.mjs`](../../../scripts/ho-so-ma/cong.mjs).
