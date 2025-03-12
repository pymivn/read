# read - Tổng hợp các link hữu ích cho lập trình viên

Hàng ngày, các lập trình viên vẫn lên mạng tìm kiếm những tài liệu để mở rộng hiểu biết, nâng cao trình độ.

Các tài liệu tổng hợp tại đây chọn lọc các tài liệu chất lượng
nhằm giảm bớt thời gian tìm kiếm của các lập trình viên.

Các tài liệu này được chọn lọc với tiêu chí thực tế, cần thiết, thay vì các giáo trình của các trường đại học thường ít tính thực tê.

## Phân loại độ khó
- Starter: đơn giản, gần như không yêu cầu kiến thức gì.
- Inmermediate: nhiều kiến thức, nhiều chỗ khó hiểu, có lợi cho lập trình viên muốn đạt trình độ senior. Người mới code vẫn khuyến khích đọc, hiểu được thì tốt.
- Advanced: chuyên sâu.
- Hacker: rất không bình thường.

### OS
- en, intermediate, [Putting the “You” in CPU](https://github.com/hackclub/putting-the-you-in-cpu/), giải thích cách hệ điều hành chạy 1 chương trình, từ CPU, register, assembly, machine code, ELF, process, virtual memory, syscall, paging, linking tới Linux fork & COW.

### Code design
- en, intermediate, ["A Philosophy of Software Design" and "Clean Code"](https://github.com/johnousterhout/aposd-vs-clean-code), so sách sự giống và khác giữa triết lý design code trong 2 cuốn sách "A Philosophy of Software Design" và "Clean Code". Nên mua và đọc "A Philosophy of Software Design" để bíết thêm chi tiết.
- en, intermediate, [Chapter 1 - 99 Bottles of OOP by Sandi Metz](https://sandimetz.com/99bottles-sample-python) - giải bài "99 bottles of beer", 1 bài code đơn giản nhưng có thể giải theo nhiều cách khác nhau, từ đó rút ra kết luận code thế nào là "tốt"/"xấu" dựa trên metric đo được thay vì cảm tính cá nhân. Nên mua và đọc "99 Bottles of OOP" để biết thêm chi tiết.

### Database
- en, intermediate, [SQLite query planning](https://sqlite.org/queryplanner.html), giới thiệu cách hoạt động của index, cách sử dụng index để tăng tốc độ truy cập database. Kiến thưcs hữu ý với mọi SQL database.

### Network
- en, intermediate, [network protocols](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147), bài viết ngắn giới thiệu về các khái niệm network cần thiết cho lập trình viên, bất kỳ ngôn ngữ nào.
- en, intermediate, [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/html/), tài liệu giới thiệu các khái niệm về network cho lập trình viên, nửa cuôi có ví dụ viết bằng ngôn ngữ C lập trình socket để viết server và client. Nếu không biết/muốn đọc code C, hoàn toàn vẫn hữu ích khi đọc phần trước đó. Hoàn toàn có thể follow theo ví dụ C thay băng code Python, dùng stdlib: [`socket`](https://docs.python.org/3/howto/sockets.html). Chi tiết hơn `network-protocols` trong list này, nhưng các kiến thức là tương tự. Kiến thức này đủ thực tế, hoàn toàn ăn đứt các môn "lập trình mạng" tại các trường đại học tại Việt Nam.
- en, intermediate, [what happens when](https://github.com/alex/what-happens-when), giải thích chi tiết chuyện gì xả ra khi người dùng gõ chữ google.com rồi enter trên thanh trình duyệt web. Từ phần cứng cho tới hệ điều hành, mạng, chi tiết tới HTTP, DNS, ARP... tài liệu này đưa ra câu trả lời chi tiết hết mức có thể. Rất hữu dụng cho các cuộc phỏng vấn, cũng là tài lieẹu tham khảo để các lập trình viên web (thường chỉ biết HTTP request) hiểu đầy đủ vòng đời của 1 request từ browser của ngưoừi dùng.

### Phỏng vấn, quan hệ với công ty
- vi, Starter, [phỏng vấn](https://pp.pymi.vn/article/phongvan/), hướng dẫn phỏng vấn xin việc, hiểu về lý do quyết định lương cao/thấp...

## Đóng góp
Tạo pull request, format:

```
- language, [name](link), review bằng tiếng Việt (bắt buộc).
```
