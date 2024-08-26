# DNS RIÊNG TƯ DỰA TRÊN NỀN TẢNG [CLOUDFLARE ZERO TRUST](https://www.cloudflare.com/zero-trust/)
Sử dụng DNS đệ quy từ Cloudflare nên tốc độ rất nhanh và ổn định (chỉ sau Google DNS). Chức năng: Chặn quảng cáo, theo dõi, trang web độc hại, cờ bạc...
### - DNS over HTTPS (DoH):
* https://ckzui5o99j.cloudflare-gateway.com/dns-query
* Link tải cấu hình cho IOS: [Link](https://app.box.com/s/ecz35292kaimiuw1njtn9y34mieqnc7z)
### - DNS over TLS (DoT):
* ckzui5o99j.cloudflare-gateway.com
* Linh tải cấu hình cho IOS: [Link](https://app.box.com/s/dnqyazkux2av1cc1tr0zsxq9w7er5o0l)
### - IPv6: 2a06:98c1:54::14:dec9

### DNS tích hợp chức năng lọc dựa trên dữ liệu Cloudflare, cập nhật thời gian thực:
- Rủi ro an ninh: phần mềm độc hại, lừa đảo, thư rác, phần mềm gián điệp, khai thác tiền điện tử.
- Nội dung độc hại: Cờ bạc, Lạm dụng trẻ em, Bạo lực, Quảng cáo lừa đảo, Ma tuý, Hacking, Thù hận & chủ nghĩa cực đoan, Thô tục, Gian lận học đường, Tên miền Parked & Để bán, Thông tin không đáng tin cậy.
- Chặn địa chỉ IP tại Campuchia, Myanmar, Philipines (nhiều trang web lừa đảo hay đặt máy chủ tại những quốc gia này).

### Tích hợp bộ lọc chặn quảng cáo, theo dõi bên thứ 3 (cập nhật 3h00 sáng thứ bảy hàng tuần): 
- [Adguard DNS Filter](https://github.com/AdguardTeam/AdGuardSDNSFilter): Bộ lọc bao gồm một số bộ lọc khác (bộ lọc Cơ sở AdGuard, bộ lọc Truyền thông xã hội, bộ lọc Chống theo dõi, bộ lọc Quảng cáo trên thiết bị di động, EasyList và EasyPrivacy) và được đơn giản hóa cụ thể để tương thích tốt hơn với chặn quảng cáo cấp DNS.
- [HostsVN](https://github.com/bigdargon/hostsVN): Bộ lọc chặn quảng cáo, mã độc, lừa đảo, cờ bạc tại Việt Nam.
- [Danh sách chặn của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Denylist): Danh sách chặn bổ sung thêm (chặn quảng cáo, cờ bạc, lừa đảo).
### Danh sách những tên miền được cho phép (sửa lỗi bộ lọc bên thứ 3 chặn nhầm):
- [NextDNS](https://raw.githubusercontent.com/nextdns/click-tracking-domains/main/domains): Cho phép bấm vào link tiếp thị và theo dõi.
- [Danh sách cho phép của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Allowlist): Bổ sung thêm cho NextDNS.

## Tự tạo DNS dựa trên nền tảng Cloudflare Zero Trust
[Hướng dẫn - VOZ](https://voz.vn/t/huong-dan-dung-cloudflare-zero-trust.822971/), [Tạo Cấu hình cho IOS](https://dns.notjakob.com/tool.html), [Kiểm tra DNS](https://www.dnscheck.tools/), [Kiểm tra chặn quảng cáo](https://d3ward.github.io/toolz/adblock.html)

Made with ♥ by o0oS2
