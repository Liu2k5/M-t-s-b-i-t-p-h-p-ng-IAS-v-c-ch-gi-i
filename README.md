# Một số bài tập hợp ngữ và cách giải
Lưu lại đáp án những bài tập lập trình cho máy IAS thầy giao cho

- Đếm số lượng số nguyên tố trong 20 ô nhớ liên tiếp :
  
  https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/8af8479da53fc208015e6b2c0cc96db82c9ab8c3/demsnt.txt
  
- Cho 1 số nguyên dương tại 0x100. Xác định số đó là Lẻ thì lưu vào 0x101, Chẵn thì lưu vào 0x102 :

  https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/0e89cc3ea4e13ccedfaed2fce03b89d22595f52f/chanhayle.txt

- Cho 3 số nguyên bất kỳ lưu trên bộ nhớ từ địa chỉ 0x100. Sắp xếp các số đó theo thứ tự tăng dần từ địa chỉ 0x100 :

  https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/cfa59407c4152ca1071e2421e3bc1e6b494d4454/sapxep3so.txt

- Cho số nguyên (có thể âm, dương) a tại 0x020. Nếu a là số nguyên tố hãy lưu nó vào 0x01f :

  https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/0416ff4c228df5cd8059fe92dc702510aa2e91ce/ktrasnt.txt

- Cho 3 số nguyên dương bất kỳ lưu liên tục từ 0x100.

Tính thương biểu thức D=| [(a+b)c]/(c-a) |. (1đ)

Nếu mẫu bằng 0 thì D = -1. (0.5đ)

Kết quả D lưu vào word nhớ có địa chỉ 0x1XY (0.5đ)

(XY là giá trị hexa số thứ tự danh sách) main memory.

  https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/cd060672bab8988b70ad2929fd19844fb1496a37/tinhtoan.txt

- Cho mảng dữ liệu như dưới . Với XY là giá trị số thứ tự danh sách hãy thực hiện:

  Tính tổng các phần tử trong mảng từ a[XY]  đến a39. (1.5đ)
  
  Kết quả lưu vào word nhớ M(0x030 + XY). (0.5đ)

.org 0x100

a0: .word 0x0000000001

a1: .word 0x0000000003

a2: .word 0x0000000022

a3: .word 0x0000000005

a4: .word 0x0000100030

a5: .word 0x0000000012

a6: .word 0x0000005000

a7: .word 0x0000000010

a8: .word 0x0000000088

a9: .word 0x0000000016

a10: .word 0x0000000105

a11: .word 0x0000100103

a12: .word 0x0000000109

a13: .word 0x0000001000

a14: .word 0x0000005000

a15: .word 0x0000000090

a16: .word 0x0000000330

a17: .word 0x0000002000

a18: .word 0x0000000045

a19: .word 0x0000000310

a20: .word 0x0000001005

a21: .word 0x0000010002

a22: .word 0x0000000022

a23: .word 0x0000000005

a24: .word 0x0000000030

a25: .word 0x0000000200

a26: .word 0x0000005000

a27: .word 0x0000000010

a28: .word 0x0000000088

a29: .word 0x0000000016

a30: .word 0x0000000105

a31: .word 0x0000001003

a32: .word 0x0000000109

a33: .word 0x0000000032

a34: .word 0x0000000054

a35: .word 0x0000000400

a36: .word 0x0000000300

a37: .word 0x0000005000

a38: .word 0x0000000034

a39: .word 0x0000000710

  https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/185acc647c625513ef510f7153d28f30ac0834af/tinhtong.txt

- Cho mảng dữ liệu như Câu 2 . Với XY là giá trị số thứ tự danh sách hãy thực hiện:

Tìm số lẻ lớn nhất trong mảng từ a[XY]  đến a39. (2đ)

 Kết quả lưu vào word nhớ M(0x030 + XY + 1). (1đ)

 https://github.com/Liu2k5/Mot_so_bai_tap_hop_ngu_IAS_va_cach_giai/blob/185acc647c625513ef510f7153d28f30ac0834af/lelonnhat.txt

  
