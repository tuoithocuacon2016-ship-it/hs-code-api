# M-74 — Ngưỡng số & phân dải anh em — Chương 91

## Tổng quan
- Tổng số bản ghi: **5** (1 `DINH_NGHIA`, 4 `NGUONG`, 0 `TACH_ANH_EM`).
- Phạm vi áp dụng: Chương 91 (Đồng hồ thời gian, đồng hồ cá nhân và bộ phận).

## Đối soát rà soát số + đơn vị (Luật 3, 5, 6, 7)
- Tổng số câu trúng số + đơn vị: **8** câu (`chuong:91:cg:3#2`, `nhom:9103:ct:1#3`, `9103:ct:4#1`, `9105:ct:2#3`, `9106:ct:19#2`, `9108:ct:9#2`, `9109:ct:6#1`, `9114:ct:31#3`; `ranh-gioi`: 0 điều kiện số).
- Đã tách `DINH_NGHIA` ở `chuong:91` và gắn 2 `NGUONG` kích thước (`≤ 12 mm`, `≤ 50 mm`) trực tiếp lên `bieu:9108` theo Luật 5 + Luật 7 (không gắn `chuong:91`); tách 2 nhánh HOẶC (`> 12 mm` hoặc `> 50 mm`) lên `bieu:9109` từ `nhom:9109:ct:6#1` theo Luật 3.
- Bỏ qua hợp lệ: `nhom:9103:ct:1#3`, `4#1`, `9108:ct:9#2` (diễn giải lại ngưỡng 12 mm / 50 mm đã gắn lên `91.08–91.09`), `9105:ct:2#3`, `9106:ct:19#2`, `9114:ct:31#3` (số liệu minh hoạ có từ `"thường"` / `"hiếm khi"`).

## Kết quả cổng
- `khuon.mjs`: 0 lỗi; `cong.mjs` Cổng 3, 4, 5: 0 lỗi.
