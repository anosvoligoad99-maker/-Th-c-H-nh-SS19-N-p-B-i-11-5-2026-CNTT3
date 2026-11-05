# Bài làm – GreenField FC

Họ và tên: Lê Minh Quân 
Lớp:HN-KS26-CNTT03

## 4.2 Thao tác CLI
Lệnh đã chạy:
pwd
ls -Recuse -Force
 mv .\ghi_chu_ban_giao.txt .\docs\
 mkdir backup
  cp .\data\danh_sach_cau_thu.xlsx .\backup
  rm .\temp_002.tmp
   cd .\logs\
   ls
   cd ..
## 4.3 Lọc log
**a) Lệnh lọc status=500:**

Hai dòng đầu của loi_500.txt:
Get-Content .\logs\access.log | Select-String "status=500" >>.\logs\loi_500.txt
(Get-Content .\logs\access.log | Select-String "status=404").Count

**b) Lệnh đếm status=404 và kết quả:4

## 4.4 Script báo cáo
Lệnh chạy script:
 Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
 .\tong_hop.ps1
Nội dung logs/tong_hop.txt:
=== BAO CAO GREENFIELD FC ===

2026-10-28 18:03:25 GET /api/players status=500
2026-10-28 18:05:12 GET /api/players status=500
2026-10-28 18:20:30 GET /api/players status=500



2026-10-28 18:03:22 GET /images/logo-sai.png status=404
2026-10-28 18:07:44 GET /fixtures status=404
2026-10-28 18:13:52 GET /favicon.ico status=404
2026-10-28 18:32:18 GET /api/players status=404
## 4.6 Kiểm tra website và báo cáo lỗi
| Tab | Tên file/thông báo | Cách khắc phục |
|---|---|---|
| Network | | |
| Console | Lỗi data | |

**Context:**

**Expected:**

**Actual:**

**Log:**

Câu tìm kiếm Google:

## Ghi chú Excel
Công thức/khó khăn đã gặp:
