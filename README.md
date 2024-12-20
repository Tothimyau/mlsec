# Máy học trong bảo mật mạng và hệ thống - NT2211.CH180

## Thông tin môn học

- Giờ học bắt đầu từ 18h00
- Môn học có:
    - 7 buổi lý thuyết
    - 2 buổi báo cáo giữa kỳ
    - 3 buổi báo cáo cuối kỳ

- Cơ cấu điểm:
    - 30% giữa kỳ
    - 50% báo cáo đồ án cuối kỳ (không thi)
    - 20% điểm danh (điểm danh bất kỳ)

- Giảng viên: TS Lê Kim Hùng

## Về đồ án giữa kỳ

- Tên đề tài: [MAGIC: Detecting Advanced Persistent Threats via Masked Graph Representation Learning](https://arxiv.org/pdf/2310.09831)
- [Danh sách đăng ký](https://uithcm.sharepoint.com/:x:/r/sites/NT2211-MyhctrongAntonthngtin/_layouts/15/Doc2.aspx?action=edit&sourcedoc=%7B359678e1-f042-4079-91a1-25cabae09052%7D&wdOrigin=TEAMS-WEB.teamsSdk_ns.rwc&wdExp=TEAMS-TREATMENT&wdhostclicktime=1726741014491&web=1)
- Yêu cầu nộp gồm:
    - Slide báo cáo trong 15p
    - Bản tóm tắt tối đa 5 trang về nội dung bài báo
    - Demo nếu có
- Thời gian báo cáo: *16/10/2024*
- Thứ tự báo cáo: ngẫu nhiên vào ngày bào cáo
- Các tài nguyên cho đề tài giữa kỳ nằm trong thư mục [mid](./mid/)

## Về đồ án cuối kỳ

- ~~Được giao khi báo cáo xong giữa kỳ~~ Đã được giao, bao gồm 2 phần
    - Báo cáo về **Transfer Learning Attack**: 60% điểm
        - Báo cáo thuyết trình: 60%
        - Chạy được một demo: 40%
    - Thực hiện xây dựng một mô hình học máy, học sâu dựa trên dữ liệu đã cho sẵn, dữ liệu sử dụng là hai file csv đã chia tập train, test [tại đây](./final/project/src/data/README.md): 40% điểm, không cần slide và báo cáo. Project structure như mô tả

        ```bash
        .
        ├── data/
        │   ├── train.csv
        │   └── test.csv
        ├── requirements.txt
        ├── main.py # For quick running
        ├── project.ipynb # Notebook file for analysis and training, turning
        └── models/
            └── model.pkl # Model file
        ```
- ~~Thời gian thực hiện: 5-6 tuần~~ Thời gian báo cáo: ngày 11 và 18 tháng 12, 2024

Dựa trên yêu cầu, project sẽ được xây dựng trong thư mục `final` với cấu trúc như hiện tại.

## Cách cập nhật vào repo

- Theo hướng dẫn tại [Hướng dẫn đóng góp vào dự án public trên github](https://sonnh.net/dong-gop-vao-du-an-public-tren-github)
- Mỗi thành viên nên tạo một branch riêng ứng với tên của mình. Sau khi hoàn thiện các cập nhật thì request merge vào master branch