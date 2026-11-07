## Lab 02
**1. Vì sao phải đồng bộ master trước khi PR?**
Để giải quyết xung đột (conflict) ở local trước, giúp PR merge an toàn.
**2. Khi nào không được rebase?**
Không rebase trên các commit đã được push và chia sẻ, vì nó viết lại lịch sử (tạo SHA mới), gây lỗi đồng bộ cho người khác.
**3. `feature/*` khác `topic/*` ra sao?**
`feature/*` dùng cho chức năng mới của phần mềm. `topic/*` dùng cho tài liệu, cấu hình, refactor.
