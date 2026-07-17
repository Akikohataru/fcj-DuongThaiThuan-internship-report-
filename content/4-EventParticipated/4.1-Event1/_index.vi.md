---
title: "Event 1"
date: 2026-05-23
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài Thu Hoạch: FCAJ Community Day – 23/5/2026

## Thông Tin Nhanh

- **Sự kiện:** FCAJ Community Day – Tháng 5/2026
- **Đơn vị tổ chức:** First Cloud Journey (FCAJ)
- **Thời gian:** Thứ Bảy, ngày 23 tháng 5 năm 2026
- **Địa điểm:** TP. Hồ Chí Minh (trực tiếp)
- **Hình thức:** Bài chia sẻ + Workshop thực hành
- **Chủ đề:** Generative AI trong doanh nghiệp

## Lý Do Tôi Tham Dự

Đây là sự kiện cộng đồng đầu tiên tôi tham gia trong suốt quá trình thực tập. Tôi đến với một câu hỏi rất cụ thể: *các kỹ sư Việt Nam đang ứng dụng AI và AWS vào sản phẩm thật như thế nào?* Tôi tưởng mình sẽ chỉ nghe slide. Nhưng kết quả là tôi được tự tay dựng một phần của hệ thống AI thực tế.

## Điểm Nhấn Chương Trình

Thay vì đi theo lịch trình phẳng, ngày hội được chia thành **ba mảch song song**:

### Mảch 1 — Tầng Kiến Thức

- Tinh Truong (GoTymeX): thực tế vận hành LLM trong một sản phẩm fintech
- Anh Pham (G-AsiaPacific): Amazon Q nằm ở đâu trong vòng đời phát triển phần mềm
- Thinh Nguyen (FCAJ): lý do MCP ra đời và vì sao *context* quan trọng hơn kích thước mô hình

### Mảch 2 — Góc Nhìn Hackathon

Bộ ba UTMorpho đến từ VIB (Uyen Le, Thao Nguyen, Mai Nguyen) kể lại quá trình build sản phẩm trong 18 tiếng. Bài học không nằm ở công nghệ — mà ở **cách họ phân chia việc, cắt giảm phạm vi và dùng AI như một lập trình viên paired dưới áp lực thời gian**.

### Mảch 3 — Sàn Workshop

Duc Dao (Cloud Kinetics) và Vy Lam (VPBank) dẫn dắt năm bài tập liên kết thành một hệ thống hoàn chỉnh:

1. Xác thực Cognito + JWT
2. Bedrock Guardrails kiểm soát đầu ra an toàn
3. IAM Permission Boundaries (quyền tối thiểu)
4. Tích hợp MCP server
5. Stack Terraform triển khai tái lập

## Một Ý Tưởng Tôi Hay Nghĩ Đến

> Guardrail không phải là bộ lọc gắn vào sau cùng. Đó là quyết định thiết kế phải đưa ra trước khi viết prompt đầu tiên.

Câu nói của Duc Dao đã thay đổi cách tôi nghĩ về an toàn trong AI. Permission Boundaries, thiết kế prompt và content filter không phải ba mối quan tâm tách biệt — chúng là **cùng một mối quan tâm nhìn từ ba tầng khác nhau**.

## Sự Kiện Này Thay Đổi Gì Ở Tôi

Trước sự kiện, AI với tôi chỉ là thứ tôi đọc trong tài liệu. Sau sự kiện, tôi có một bản đồ tư duy về cách các mảnh ghép kết nối với nhau, kèm theo một checklist tôi vẫn dùng mỗi khi động đến một tính năng AI:

- Ai được phép gọi tính năng này?
- Những gì được phép rời khỏi endpoint này?
- Model thực sự cần context nào?
- Mình có thể tái triển khai deployment này bằng một `terraform apply` duy nhất không?

## Hình Ảnh

![Tham dự FCAJ Community Day cùng các bạn]({{< baseurl >}}images/4-EventParticipated/event1.jpg)

## Lời Kết

Đây là khởi đầu cho mọi trải nghiệm AI của tôi ngoài giáo trình. Nó đặt nền cho tất cả những gì diễn ra sau đó trong kỳ thực tập — mỗi blog tôi viết, mỗi quyết định kiến trúc trong dự án SmartMenu, mỗi lần tôi chạm vào Bedrock hay MCP, đều có thể truy ngược về những ý tưởng tôi nghe lần đầu trong căn phòng đó ngày 23 tháng 5.
