# DNS RIÊNG TƯ DỰA TRÊN NỀN TẢNG CLOUDFLARE ZERO TRUST
## 1. DNS - BỘ LỌC AN TOÀN:
### 1.1 DNS over HTTPS (DoH):
https://ckzui5o99j.cloudflare-gateway.com/dns-query
#### Link tải cấu hình cho IOS:
https://1drv.ms/u/s!Al8R__2PmYaUjQWxOwFM7SASk2on?e=ViZ0tk
#### DNS over HTTPS (DoH) chuyển tiếp qua Vercel:
https://abpvn.vercel.app
### 1.2 DNS over TLS (DoT):
ckzui5o99j.cloudflare-gateway.com
#### Linh tải cấu hình cho IOS:
https://1drv.ms/u/s!Al8R__2PmYaUjQQeAGgZjabiKtHb?e=VEHpLd
### 1.3 IPv6
2a06:98c1:54::14:dec9

## 2. DNS - BỘ LỌC CHO TRẺ EM:
### 2.1 DNS over HTTPS (DoH):
https://r3i5enfsbw.cloudflare-gateway.com/dns-query
#### Linh tải cấu hình cho IOS:
https://1drv.ms/u/s!Al8R__2PmYaUjQanCbp7HMJHbg9K?e=XKlcjB
### 2.2 DNS over TLS (DoT):
r3i5enfsbw.cloudflare-gateway.com
#### Linh tải cấu hình cho IOS:
https://1drv.ms/u/s!Al8R__2PmYaUjQcoRWDEVAHGlda4?e=qHKxYK
### 2.3 IPv6
2a06:98c1:54::15:29a5

#### Cả hai bộ lọc DNS đều tích hợp chức năng lọc từ Cloudflare bao gồm:
- Rủi ro an ninh: phần mềm độc hại, lừa đảo, thư rác, phần mềm gián điệp, khai thác tiền điện tử.
- Nội dung độc hại: Cờ bạc, Lạm dụng trẻ em, Bạo lực, Quảng cáo lừa đảo, Ma tuý, Hacking, Thù hận & chủ nghĩa cực đoan, Thô tục, Gian lận học đường, Tên miền Parked & Để bán, Thông tin không đáng tin cậy
- Chặn địa chỉ IP tại Campuchia, Myanmar, Philipines
- Tích hợp bộ lọc chặn từ nguồn:
  * Bộ lọc chặn quảng cáo từ Adguard.com: https://github.com/AdguardTeam/AdGuardSDNSFilter
  * Bộ lọc chặn quảng cáo, bài bạc, mối đe doạ tại Việt Nam từ HostsVN: https://github.com/bigdargon/hostsVN
  * Bộ lọc Multi PRO từ HAGEZI: https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro-onlydomains.txt
##### Chức năng chặn nội dung người lớn cho trẻ em (DNS - BỘ LỌC CHO TRẺ EM):
- Tìm kiếm an toàn: Google, Bing, DuckduckGo Các (nội dung độc hại, từ khóa chứa nội dung đồi trụy...các kết quả phản cảm sẽ không được hiển thị)
- Chế độ hạn chế Youtube: Các nội dung độc hại, từ khóa chứa nội dung đồi trụy...các kết quả phản cảm sẽ không được hiển thị
- Chặn chủ đề khiêu dâm, đồi truỵ dựa trên dữ liệu Cloudflare
- Thêm một số bộ lọc chặn trang web người lớn từ HostsVN
  
## 3. Serverless-DNS (Rethink DNS):
### Link cài đặt bộ lọc cho Serverless-DNS (Rethink DNS):
https://serverless-dns.abpvn.workers.dev/
#### DNS over HTTPS (DoH) chặn quảng cáo (ABVN List):
https://serverless-dns.abpvn.workers.dev/1:AAIAEA==
#### Thông tin
Serverless-DNS (Rethink DNS) sử dụng nên tảng Cloudflare Workers, tối đa 100.000 truy vấn/1 ngày, CPU time max 10 ms, chuyển tiếp qua Google DNS

## 4. Danh sách lọc của tôi
### 4.1 Danh sách cho phép bỏ qua quảng cáo:
https://raw.githubusercontent.com/o0oS2/Filter-List/main/Allowlist
### 4.2 Danh sách chặn từ ABPVN.com, Chongluadao.vn, theo dõi từ nền tảng:
https://raw.githubusercontent.com/o0oS2/Filter-List/main/Denylist
### 4.3 Danh sách chặn khác:
https://raw.githubusercontent.com/o0oS2/Filter-List/main/Denylist_Me

## 5. Một số DNS chặn quảng cáo miễn phí:
- ControlD: https://controld.com/free-dns
  * DNS đệ quy, có thể chọn bộ lọc dễ dàng
  * Máy chủ tại Hồng Kông, Singapore, Nhật Bản ...
  * Hoạt động rất nhanh và ổn định
  * Có IPv4 và IPv6
- Adguard: https://adguard-dns.io/en/public-dns.html
  * Chưa có máy chủ tại Hồng Kông
  * Hoạt động kém ổn định so với ControlD
  * Có IPv4 và IPv6
- Rethink: https://rethinkdns.com/configure
  * Sắp tới sẽ dừng hỗ trợ miễn phí (chưa rõ ngày)
  * Dễ dàng chọn bộ lọc
  * Chuyển tiếp qua Cloudflare DNS
  * Rất nhanh và ổn định do dùng nền tảng của Cloudflare
  * Không có IPv4 và IPv6
- ABPVN: https://private-dns.abpvn.com/
  * Dùng Adguard Home lọc quảng cáo, máy chủ Anguard Home tại Hà Nội và Singapore
  * Chuyển tiếp qua Google DNS
  * Không được ổn định lắm
  * Có IPv4 và IPv6
- VietDNS: https://vietdns.vn/
  * Máy chủ tại Hà Nội và Hồ Chí Minh
  * chuyển tiếp qua Google DNS
  * Không được ổn định lắm
  * Có IPv4 và IPv6
- Next DNS: https://my.nextdns.io/
  * Có 4 máy chủ tại Hà Nội và Hồ Chí Minh
  * Phải tạo tài khoản và cấu hình để chặn quảng cáo, nội dung độc hại....
  * Miễn phí 300.000 truy vấn 1 tháng
  * Hoạt động rất nhanh và ổn định (chỉ kém Google DNS và Cloudflare)
  * Hướng dẫn: https://voz.vn/t/tat-tan-tat-ve-dich-vu-nextdns.522718/
  * 
Made with ♥ by o0oS2
