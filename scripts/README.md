# Công cụ sử dụng trong phần Exploitation

Thư mục này ghi nhận các thành phần công cụ được sử dụng trong phần thử nghiệm Shadow Credentials. Mã của các dự án bên thứ ba không được chép lại vào repository này.

| Công cụ | Vai trò trong báo cáo |
|---|---|
| `pywhisker.py` (pyWhisker) | Tương tác với Key Credential của đối tượng Active Directory |
| `gettgtpkinit.py` (PKINITtools) | Làm việc với luồng xác thực Kerberos PKINIT |
| `getnthash.py` (PKINITtools) | Được dùng ở bước phân tích kết quả xác thực Kerberos trong lab |
| Evil-WinRM | Công cụ quản trị WinRM dùng để kiểm chứng phiên trong môi trường thử nghiệm |

Repository lưu **bằng chứng, diễn giải các giai đoạn và tên công cụ**, không đóng gói mã tự động chiếm quyền tài khoản, khôi phục credential hoặc vô hiệu hóa giám sát.
