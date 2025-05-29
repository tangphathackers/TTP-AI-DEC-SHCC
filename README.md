# 🔓 TTP-AI-IEE SHC/SCC Decrypt Tool

**Một công cụ Termux/Shell script mạnh mẽ để giải mã các file mã hóa `.sh` thông qua kỹ thuật ngắt tiến trình `SHC`, `SCC`, hoặc các biến thể tương tự.**

---

## 🧠 Thông tin
- 📌 **Tên công cụ:** TTP-AI-IEE DEC (SHC & SCC Decryptor)
- 📅 **Phiên bản:** 1.0
- 👤 **Tác giả:** [@ttp_ai_iee_tangphat](https://t.me/ttp_ai_iee_tangphat)
- 🌐 **GitHub Support:** [https://github.com/kawaii-ghost](https://github.com/kawaii-ghost)

---

## ⚙️ Chức năng

- Giải mã các shell script bị mã hóa bằng `shc`, `scc` hoặc kỹ thuật tương tự.
- Tự động xử lý quyền thực thi, tạo bản sao script, giải mã từ `/proc`, và lưu kết quả.
- Tùy chỉnh sleep ngẫu nhiên để đảm bảo giải mã chính xác nhất.
- Xuất kết quả ra file `.ttp.dec.sh` tại thư mục chứa script gốc.

---

## 📦 Cài đặt

```bash
pkg install git -y
spath=$(echo $PATH | cut -d: -f1)
curl -sLo $spath/TTP-AI-DEC-SHCC https://github.com/tangphathackers/TTP-AI-DEC-SHCC/raw/main/TTP-AI-DEC-SHCC
chmod +x $spath/TTP-AI-DEC-SHCC 
