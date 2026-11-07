## Lab 04
**1. Vì sao `release/*` không merge vào master?**
`release/*` dùng để bảo trì phiên bản. Merge ngược vào `master` gây loạn tiến trình phát triển. Chỉ cherry-pick các hotfix.
**2. So sánh với GitFlow?**
Release Flow đơn giản hơn, không duy trì cả `master` và `develop` dài hạn, chỉ có một luồng tích hợp và các nhánh release khi cần.
**3. Vì sao lên 1.0.0 mà không phải 0.4.0?**
Vì 1.0.0 đánh dấu bản phát hành chính thức ổn định đầu tiên, trong khi 0.x.x chỉ là giai đoạn phát triển ban đầu chưa hoàn thiện.
