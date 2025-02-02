# DNS RIÊNG TƯ DỰA TRÊN NỀN TẢNG [CLOUDFLARE ZERO TRUST](https://www.cloudflare.com/zero-trust/)
Sử dụng DNS đệ quy từ Cloudflare nên tốc độ rất nhanh và ổn định (chỉ sau Google DNS)
## 1.1 DNS - BỘ LỌC AN TOÀN
Chức năng: Chặn quảng cáo, theo dõi, trang web độc hại, cờ bạc...
### - DNS over HTTPS (DoH):
```
https://ckzui5o99j.cloudflare-gateway.com/dns-query
```
* Link tải cấu hình cho IOS: [Link](https://app.box.com/s/ecz35292kaimiuw1njtn9y34mieqnc7z)
### - DNS over TLS (DoT):
```
ckzui5o99j.cloudflare-gateway.com
```
* Linh tải cấu hình cho IOS: [Link](https://app.box.com/s/dnqyazkux2av1cc1tr0zsxq9w7er5o0l)
### - IPv6: 
```
2a06:98c1:54::14:dec9
```

## 1.2 DNS - CHO TRẺ EM
DNS - BỘ LỌC AN TOÀN + chế độ hạn chế Youtube + Tìm kiếm an toàn + Chặn trang web có nội dung không phù hợp với trẻ em
### - DNS over HTTPS (DoH):
```
https://0ng9sksd6v.cloudflare-gateway.com/dns-query
```
* Link tải cấu hình cho IOS: [Link](https://app.box.com/s/v4bzil3wvzagkdolh4swmcifnxe137u2)
### - DNS over TLS (DoT):
```
0ng9sksd6v.cloudflare-gateway.com
```
* Linh tải cấu hình cho IOS: [Link](https://app.box.com/s/pffloolmgvkcezx9yopyn8ockomu9ddz)
### - IPv6: 
```
2a06:98c1:54::18:ffe
```
## TÍNH NĂNG BỘ LỌC DNS:
### a, DNS tích hợp chức năng lọc dựa trên dữ liệu Cloudflare, cập nhật thời gian thực:
- Rủi ro an ninh: phần mềm độc hại, lừa đảo, thư rác, phần mềm gián điệp, khai thác tiền điện tử.
- Nội dung độc hại: Cờ bạc, Lạm dụng trẻ em, Bạo lực, Quảng cáo lừa đảo, Ma tuý, Hacking, Thù hận & chủ nghĩa cực đoan, Thô tục, Gian lận học đường, Tên miền Parked & Để bán, Thông tin không đáng tin cậy.
- Chặn địa chỉ IP tại Campuchia, Myanmar, Philipines (nhiều trang web lừa đảo hay đặt máy chủ tại những quốc gia này).

### b, Tích hợp bộ lọc chặn quảng cáo, theo dõi bên thứ 3 (cập nhật 3h00 sáng hàng ngày):
- [HostsVN](https://github.com/bigdargon/hostsVN): Bộ lọc chặn quảng cáo, mã độc, lừa đảo, cờ bạc tại Việt Nam.
- [Danh sách chặn của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Denylist): Danh sách chặn bổ sung thêm (chặn quảng cáo, cờ bạc, lừa đảo).
### c, Danh sách những tên miền được cho phép (sửa lỗi bộ lọc bên thứ 3 chặn nhầm):
- [NextDNS](https://raw.githubusercontent.com/nextdns/click-tracking-domains/main/domains): Cho phép bấm vào link tiếp thị và theo dõi.
- [Danh sách cho phép của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Allowlist): Bổ sung thêm cho NextDNS.


## Tự tạo DNS dựa trên nền tảng Cloudflare Zero Trust
[Hướng dẫn - VOZ](https://voz.vn/t/huong-dan-dung-cloudflare-zero-trust.822971/), [Tạo Cấu hình cho IOS](https://dns.notjakob.com/tool.html), [Kiểm tra DNS](https://www.dnscheck.tools/), [Kiểm tra chặn quảng cáo](https://d3ward.github.io/toolz/adblock.html)

## NextDNS tài khoản Pro Education
### - DNS over HTTPS (DoH):
```
https://dns.nextdns.io/527e31
```
* Link tải cấu hình cho IOS: [Link](https://apple.nextdns.io/?profile=527e31)
### - DNS over TLS (DoT):
```
527e31.dns.nextdns.io
```
### - IPv6: 
```
2a07:a8c0::52:7e31
2a07:a8c1::52:7e31
```

Made with ♥ by o0oS2
