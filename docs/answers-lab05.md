## Lab 05
**1. Ưu, nhược điểm upstream first vs release first?**
- **Upstream first**: Ưu điểm là triệt tiêu lỗi tận gốc trên master. Nhược điểm là lúc cherry-pick về nhánh release cũ dễ dính conflict.
- **Release first**: Ưu điểm là cứu bản release nhanh nhất. Nhược điểm là dễ quên cherry-pick ngược về master.
**2. Lệnh nào phát hiện quên lan truyền?**
Lệnh `git cherry -v origin/master origin/release/lab05` liệt kê các commit chưa được đồng bộ.
