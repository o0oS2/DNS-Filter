# [DNS PRIVATE AND VPN 1.1.1.1 WARP+ BY CLOUDFLARE](https://www.cloudflare.com/)
**DNS Riêng tư**, **VPN 1.1.1.1 Warp+** dựa trên nền tảng [Cloudflare Zero Trust](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/). Chặn quảng cáo, mã độc, lừa đảo, cờ bạc...
#### 1. HƯỚNG DẪN CÀI ĐẶT
##### a. DNS - Private (nhẹ, tiết kiệm pin hơn VPN, vào trang có máy chủ trong nước nhanh hơn)
* **Android:** Cài đặt → Kết nối → DNS Riêng tư → DNS tuỳ chỉnh → dán link DNS over TLS (DOT).
* **Iphone:** [Link tải cấu hình Ios](https://www.icloud.com/iclouddrive/012-bKO4sf4Rt4ge8ysNcYfkg#DNS-Mobileconfig) → bấm vào 1 trong 4 file cấu hình → vào cài đặt → đã tải về hồ sơ → cài đặt DNS → nhập mật khẩu điện thoại...
* **Trình duyệt:** Cài đặt → Quyền riêng tư và bảo mật → Bảo mật → Sử dụng nhà cung cấp DNS → DNS tuỳ chỉnh → dán link DNS over HTTPS (DOH).
##### b. VPN 1.1.1.1 Warp+ (vượt web bị chặn, fake địa chỉ IP, vào trang có máy chủ tại nước ngoài nhanh hơn)
* Vào Appstore hoặc CH Play cài và mở ứng dụng: **Cloudflare One Agent** → Next → Accept→ nhập: tdt93 → Next → Tiếp tục → nhập địa chỉ Email của bạn → Send me a Code → nhập code từ email gửi đến → Sign in → tiến hành cài đặt VPN như VPN 1.1.1.1.
* Do Fake địa chỉ IP (Fake ra nước ngoài) nên có thể không truy cập vào một số trang Web của **Bộ Công An**, **VNEID** (**VNEID** chặn IP từ nước ngoài), tắt VPN có thể truy cập bình thường.
***
##### Level 1. DNS - BỘ LỌC AN TOÀN
Chặn mã độc, theo dõi, trang web độc hại, cờ bạc...

##### _a. DNS over HTTPS (DoH):_
```
https://nq5rum5udh.cloudflare-gateway.com/dns-query
```
##### _b. DNS over TLS (DoT):_
```
nq5rum5udh.cloudflare-gateway.com
```
***
##### Level 2. DNS - Chặn quảng cáo
Level 1 + Chặn quảng cáo

##### _a. DNS over HTTPS (DoH):_
```
https://ckzui5o99j.cloudflare-gateway.com/dns-query
```
##### _b. DNS over TLS (DoT):_
```
ckzui5o99j.cloudflare-gateway.com
```
***
##### Level 3. DNS - Chặn quảng cáo, 18+
Level 2 + chế độ hạn chế Youtube + Tìm kiếm an toàn + Chặn trang web có nội dung không phù hợp với trẻ em.
##### _a. DNS over HTTPS (DoH):_
```
https://0ng9sksd6v.cloudflare-gateway.com/dns-query
```
##### _b. DNS over TLS (DoT):_
```
0ng9sksd6v.cloudflare-gateway.com
```
***
#### 4. TÍNH NĂNG BỘ LỌC DNS - VPN 1.1.1.1 Warp+:
##### _a. DNS tích hợp chức năng lọc dựa trên dữ liệu [Cloudflare](https://www.cloudflare.com/), cập nhật thời gian thực:_
* Rủi ro an ninh: phần mềm độc hại, lừa đảo, thư rác, phần mềm gián điệp, khai thác tiền điện tử.
* Nội dung độc hại: Cờ bạc, Lạm dụng trẻ em, Bạo lực, Quảng cáo lừa đảo, Ma tuý, Hacking, Thù hận & chủ nghĩa cực đoan, Thô tục, Gian lận học đường, Tên miền Parked & Để bán, Thông tin không đáng tin cậy.

##### _b. Tích hợp bộ lọc chặn quảng cáo, theo dõi bên thứ 3 (cập nhật 3h00 sáng hàng ngày):_
* [HostsVN](https://github.com/bigdargon/hostsVN): Bộ lọc chặn quảng cáo, mã độc, lừa đảo, cờ bạc tại Việt Nam.
* [AdGuard DNS filter](https://github.com/AdguardTeam/AdGuardSDNSFilter): Một bộ lọc bao gồm một số bộ lọc khác (bộ lọc AdGuard Base, bộ lọc phương tiện truyền thông xã hội, bộ lọc Bảo vệ theo dõi, bộ lọc Quảng cáo trên thiết bị di động, EasyList và EasyPrivacy) và được đơn giản hóa cụ thể để tương thích tốt hơn với tính năng chặn quảng cáo cấp DNS.
* [Danh sách chặn của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Denylist): Danh sách chặn bổ sung thêm (chặn quảng cáo, cờ bạc, lừa đảo).

##### _c. Danh sách những tên miền được cho phép (sửa lỗi bộ lọc bên thứ 3 chặn nhầm):_
* [NextDNS](https://raw.githubusercontent.com/nextdns/click-tracking-domains/main/domains): Cho phép bấm vào link tiếp thị và theo dõi.
* [Danh sách cho phép của tôi](https://raw.githubusercontent.com/o0oS2/DNS-Filter/main/Allowlist): Bổ sung thêm cho NextDNS.
***
#### 5. Tự tạo DNS dựa trên nền tảng Cloudflare Zero Trust
* [Hướng dẫn tạo DNS từ VOZ](https://voz.vn/t/huong-dan-dung-cloudflare-zero-trust.822971/)
* [Tạo Cấu hình cho IOS](https://dns.notjakob.com/tool.html)
* [Kiểm tra DNS](https://www.dnscheck.tools/)
Liên hệ: Zalo: [Đức Trung](http://zalo.me/trungpl)
