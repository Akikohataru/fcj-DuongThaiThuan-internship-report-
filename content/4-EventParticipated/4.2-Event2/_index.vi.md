---
title: "Event 2"
date: 2026-06-27
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài Thu Hoạch: FCAJ Community Day – 27/6/2026

## Thông Tin Nhanh

- **Sự kiện:** FCAJ Community Day – Tháng 6/2026
- **Đơn vị tổ chức:** First Cloud Journey (FCAJ)
- **Thời gian:** Thứ Bảy, ngày 27 tháng 6 năm 2026
- **Địa điểm:** TP. Hồ Chí Minh (trực tiếp)
- **Hình thức:** Bài chia sẻ + Demo sản phẩm trực tiếp
- **Chủ đề:** AI vận hành thật thay vì trên slide

## Vì Sao Lần Này Nặng Ký Hơn

FCAJ Community Day lần đầu (tháng 5) cho tôi *từ vựng*. Lần thứ hai này cho tôi *bảng liệt kê vật tư*. Ngày tháng 5 thiên về lý thuyết và lab; ngày tháng 6 được dựng quanh **bốn demo sản phẩm chạy thật, không cắt cảnh** — Voice AI, AgenticOps, Amazon Q cho HR, và một stack Amazon Q + MCP được gia cố bằng VPC và IAM.

Tôi vào cửa với sự tò mò. Tôi ra cửa với một cuốn sổ đầy sơ đồ mà trước đó tôi chưa từng thấy.

## Bốn Demo Trực Tiếp, Bốn Tư Duy Mới

### 1. Voice AI — Khi mô hình *nói* lại

Trung Vu (Revve AI) mang một voice agent lên sân khấu và bắt nó nghe cuộc gọi thật từ khán giả. Điều làm tôi ngạc nhiên không phải là nó chạy được — mà là **màn hình dành cho model chỉ chiếm một phần rất nhỏ**. Gần như toàn bộ ngân sách độ trễ được dùng cho nhận dạng giọng nói, định tuyến ý định và thực thi công cụ *xung quanh* LLM. Phần model mới là phần dễ nhất.

### 2. AgenticOps — AI là đồng đội, không phải công cụ

Anh Trường và Minh Anh Đặng Cao (Noventiq Vietnam) demo một pipeline E-shop trong đó DevOps Agent theo dõi build, mở ticket và rollback các lần deploy lỗi mà không cần con người. Điểm nhấn của họ rất rõ: giá trị của AgenticOps không phải *thay thế* vận hành viên — mà là **mua lại sự tập trung** của họ cho những sự cố thực sự quan trọng.

### 3. Amazon Q cho HR — Truy xuất quan trọng hơn suy luận

Bao Phan Kim và Minh Nguyen Nguyen đi qua một trợ lý HR kết nối với tài liệu nội bộ. Điều hữu ích nhất tôi rút ra là cách họ đóng khung: Amazon Q không *sinh* câu trả lời, nó **truy xuất các đoạn policy và ghép lại bằng trích dẫn**. Người recruiter trong demo có thể nhìn thấy chính xác mỗi câu đến từ tài liệu nào.

### 4. Amazon Q + MCP + VPC — Câu chuyện bảo mật đội lốt demo tính năng

Đức Toàn Nguyễn (AWS Security Builder) chốt ngày hội bằng việc kết nối Amazon Q với một MCP server nội bộ — rồi đặt toàn bộ vào trong một VPC riêng. Bản thân demo đã là một bài giảng về bảo mật. Bài học: *Amazon Q không nhất thiết phải là khâu yếu nhất trong mạng của bạn.*

## Hai Cuộc Trò Chuyện Tôi Không Quên

Giữa các phiên, tôi có hai cuộc trò chuyện ngắn đã định hình cách tôi lên kế hoạch học tiếp theo.

- **Nhat Tran (CloudThinker)** kể về việc lấy chứng chỉ AWS đầu tiên vào 2020–2021 — và sau đó *không làm gì với nó* suốt một năm để xây tiếp phần còn lại của bức tranh. Câu đó đã giúp tôi bớt ám ảnh với chứng chỉ và nhìn vào điều thực sự quan trọng.
- **Nghị Danh Hoàng Hiếu (Renova Cloud)** nói rằng kỹ năng bị đánh giá thấp nhất của kỹ sư cloud bây giờ là biết *nói không* với những tính năng trông ngon trên demo nhưng hại kiến trúc về lâu dài. Tôi sẽ viết câu đó lên tường.

## Tôi Mang Gì Về Dự Án SmartMenu

- Tôi vẽ lại kiến trúc SmartMenu với một *ranh giới ngữ cảnh* rõ ràng — một VPC riêng, một MCP server và một lớp Amazon Q phục vụ tra cứu tài liệu nội bộ. Cùng một sản phẩm, nhưng giờ có các vùng tin cậy rõ ràng.
- Tôi thêm một cột *"dữ liệu này đến từ đâu?"* vào bảng đánh giá truy xuất của nhóm — lấy cảm hứng thẳng từ demo HR.

## Hình Ảnh

![Chụp ảnh cùng các bạn tại FCAJ Community Day 27/6/2026]({{< baseurl >}}images/4-EventParticipated/event2.jpg)

![Hội trường sự kiện – phần trình bày về Revve AI]({{< baseurl >}}images/4-EventParticipated/event_2_3.jpg)

## Lời Kết

Nếu ngày tháng 5 cho tôi *từ vựng* của AI doanh nghiệp, ngày tháng 6 cho tôi *bảng kiểm*. Mỗi demo đều ẩn theo cùng một khuôn mẫu — guardrails, context có thể truy xuất, một ranh giới tin cậy rõ ràng và con người trong vòng lặp ở chỗ thật sự cần. Tôi đoán khuôn mẫn này sẽ cứ lặp lại trong mọi thứ tôi xây đến hết kỳ thực tập này.
