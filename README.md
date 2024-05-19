# DNS RIÊNG TƯ DỰA TRÊN NỀN TẢNG [CLOUDFLARE ZERO TRUST](https://www.cloudflare.com/zero-trust/)
Sử dụng DNS đệ quy từ Cloudflare nên tốc độ rất nhanh và ổn định (chỉ sau Google DNS)
#### DNS tích hợp chức năng lọc dựa trên dữ liệu [Cloudflare](https://www.cloudflare.com/), cập nhật thời gian thực:
- Rủi ro an ninh: phần mềm độc hại, lừa đảo, thư rác, phần mềm gián điệp, khai thác tiền điện tử.
- Nội dung độc hại: Cờ bạc, Lạm dụng trẻ em, Bạo lực, Quảng cáo lừa đảo, Ma tuý, Hacking, Thù hận & chủ nghĩa cực đoan, Thô tục, Gian lận học đường, Tên miền Parked & Để bán, Thông tin không đáng tin cậy
- Chặn địa chỉ IP tại Campuchia, Myanmar, Philipines (nhiều trang web lừa đảo hay đặt máy chủ tại những quốc gia này)
#### Tích hợp thêm bộ lọc chặn bên thứ 3 (cập nhật 3h00 sáng hàng ngày): 
- [Multi Normal - HAGEZI](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#normal): Chặn Quảng cáo, Liên kết, Theo dõi, Số liệu, Dữ liệu đo từ xa, Lừa đảo, Phần mềm độc hại, Lừa đảo, Giả mạo, Tiền xu...
- [Adguard.com](https://github.com/AdguardTeam/AdGuardSDNSFilter): Bộ lọc bao gồm một số bộ lọc khác (bộ lọc Cơ sở AdGuard, bộ lọc Truyền thông xã hội, bộ lọc Chống theo dõi, bộ lọc Quảng cáo trên thiết bị di động, EasyList và EasyPrivacy) và được đơn giản hóa cụ thể để tương thích tốt hơn với chặn quảng cáo cấp DNS
- [HostsVN](https://github.com/bigdargon/hostsVN): Bộ lọc chặn quảng cáo, mã độc, cờ bạc tại Việt Nam
- [Danh sách chặn của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Denylist): Danh sách chặn bổ sung thêm.
#### Danh sách những tên miền được cho phép:
- [NextDNS](https://raw.githubusercontent.com/nextdns/click-tracking-domains/main/domains): Cho phép bấm vào link tiếp thị và theo dõi
- [Bộ lọc của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Allowlist): Bổ sung thêm cho NextDNS
## 1. DNS - BỘ LỌC AN TOÀN:
### - DNS over HTTPS (DoH):
* https://ckzui5o99j.cloudflare-gateway.com/dns-query
* Link tải cấu hình cho IOS: [Link 1](https://1zfnlg.dm.files.1drv.com/y4m8RVBSoHBBKsJTKkuUKrrcN8I6DeDELYiSK5xPWjqnT2lXeuMjPgnj2lEukCRJwkDVCF-S2MSbScqwLiTBF3n0SeKUsNNEydoz4QpnUWZmB9aBCRxhUb_KVKgw_rzST93apAI2IJlgaZi0GVoa9MkmZwWPDQelZYV4_zoQhuRcSlM5Rpwe78SF0x7JnaDbY4Jv2bpTWdi_hoCuK83LqQ88w),  [Link 2](https://1drv.ms/u/s!Al8R__2PmYaUjQWxOwFM7SASk2on?e=ViZ0tk)
### - DNS over TLS (DoT):
* ckzui5o99j.cloudflare-gateway.com
* Linh tải cấu hình cho IOS: [Link 1](https://2dfnlg.dm.files.1drv.com/y4mYR6R1ELgRxu_GrCgqn-yMBuZSGDqYNo-Fz4TPlsbqWlCqc-hNoJucJEIO91se8jYaBBldC7_i3w1HLWENuOwqPyHuuc700V-f_RQQV4DGUes88R5b2zVF8om7QfRJJykWpuuwxLhWFRaBme5-SaLPZOllupbZBmOwF-fQgee339ll7lfRr-la7FSwPcXFAYSBT2DCEeNy2bgbpNLorw8OA), [Link 2](https://1drv.ms/u/s!Al8R__2PmYaUjQQeAGgZjabiKtHb?e=VEHpLd)
### - IPv6: 2a06:98c1:54::14:dec9

## 2. DNS - BỘ LỌC CHO TRẺ EM:
### - DNS over HTTPS (DoH):
* https://r3i5enfsbw.cloudflare-gateway.com/dns-query
* Linh tải cấu hình cho IOS: [Link 1](https://0dcyig.dm.files.1drv.com/y4m6vxJo8t3XR0XcgjS9tKtBvBjJu4SjssfjlCrN91uRn5cKHSjlDctx9w6AkQa2bE9L9ltOtK2hiKSgPaaALn-1yZ4NT8hB71dn5lXfAj5XqwF_05RhmPckxLcK3VFaE0KevLbeAZH-dnyKbhyKmoWqeyaNNKV9lCejlDOD0M07GkDNAeRuLwjxUDG8Kg0HFy5AMqnaBlSpMwB5iGcCkSegA), [Link 2](https://1drv.ms/u/s!Al8R__2PmYaUjQanCbp7HMJHbg9K?e=XKlcjB)
### - DNS over TLS (DoT):
* r3i5enfsbw.cloudflare-gateway.com
* Linh tải cấu hình cho IOS: [Link 1](https://zzcyig.dm.files.1drv.com/y4mqDYDzRHVNF7qHlJo7qZKIpthJvWbOrRn5WnC5XYHFfGD8QP0hSs6IkAJeGBQZ2P-oHBSsazvONfmJTgSHeubvfNCftS7El-DRWx-zls7EaGuU1ZXlvrOZE15WhFY6QWWe2ttJpbgGuucV9uy5YVrFuXacUypkyP_cErzN9kfjghElVI9N0Oflav7e_9xgfI3CFn56Ct4-HKGg4rF6Ja4Zw), [Link 2](https://1drv.ms/u/s!Al8R__2PmYaUjQcoRWDEVAHGlda4?e=qHKxYK)
### - IPv6: 2a06:98c1:54::15:29a5

##### Chức năng chặn nội dung người lớn cho trẻ em:
- Tìm kiếm an toàn: Google, Bing, DuckduckGo Các (nội dung độc hại, từ khóa chứa nội dung đồi trụy...các kết quả phản cảm sẽ không được hiển thị)
- Chế độ hạn chế Youtube: Các nội dung độc hại, từ khóa chứa nội dung đồi trụy...các kết quả phản cảm sẽ không được hiển thị
- Chặn chủ đề khiêu dâm, đồi truỵ dựa trên dữ liệu Cloudflare
- Thêm một số bộ lọc chặn trang web người lớn từ [HostsVN](https://github.com/bigdargon/hostsVN)

### Tự tạo DNS dựa trên nền tảng Cloudflare Zero Trust
[Hướng dẫn - VOZ](https://voz.vn/t/huong-dan-dung-cloudflare-zero-trust.822971/), [Tạo Cấu hình cho IOS](https://dns.notjakob.com/tool.html), [Kiểm tra DNS](https://www.dnscheck.tools/), [Kiểm tra chặn quảng cáo](https://d3ward.github.io/toolz/adblock.html)

## 3. Một số DNS chặn quảng cáo miễn phí:
- [Số 1. Next DNS](https://my.nextdns.io/)
  * Có 4 máy chủ tại Hà Nội và Hồ Chí Minh (không lo đứt cáp quang biển)
  * Phải tạo tài khoản và cấu hình để chặn quảng cáo, nội dung độc hại....
  * Miễn phí 300.000 truy vấn 1 tháng
  * Hoạt động rất nhanh và ổn định (chỉ sau Google DNS và Cloudflare)
  * Hướng dẫn: [Link Github](https://github.com/bigdargon/hostsVN/wiki/NextDNS), [Link VOZ](https://voz.vn/t/tat-tan-tat-ve-dich-vu-nextdns.522718/)
- [Số 2. ControlD](https://controld.com/free-dns)
  * DNS đệ quy, có thể chọn bộ lọc dễ dàng
  * Máy chủ tại Hồng Kông, Singapore, Nhật Bản ...
  * Hoạt động rất nhanh và ổn định (kém hơn NextDNS)
  * Có IPv4 và IPv6
- [Số 3. Rethink](https://rethinkdns.com/configure)
  * Sắp tới sẽ dừng hỗ trợ miễn phí (chưa rõ ngày)
  * Dễ dàng chọn bộ lọc
  * Chuyển tiếp qua Cloudflare DNS
  * Rất nhanh và ổn định do dùng chung nền tảng của Cloudflare
  * Không có IPv4 và IPv6
- [Số 4. Adguard](https://adguard-dns.io/en/public-dns.html)
  * DNS đệ quy nhưng định tuyến chưa tốt tại Việt Nam
  * Chưa có máy chủ tại Hồng Kông
  * Hoạt động kém ổn định so với ControlD
  * Có IPv4 và IPv6
- [Số 5.1 ABPVN](https://private-dns.abpvn.com/)
  * Dùng Adguard Home lọc quảng cáo, máy chủ Anguard Home tại Hà Nội và Singapore
  * Chuyển tiếp qua Google DNS
  * Máy chủ Adguard Home và máy chủ Google DNS xa nhau nên tốc độ không nhanh lắm
  * Có IPv4 và IPv6
- [Số 5.2 VietDNS](https://vietdns.vn/)
  * Máy chủ tại Hà Nội và Hồ Chí Minh
  * chuyển tiếp qua Google DNS
  * Máy chủ VietDNS và máy chủ Google DNS xa nhau nên tốc độ không nhanh lắm
  * Có IPv4 và IPv6

Made with ♥ by o0oS2
