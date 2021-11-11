---
title: Hướng dẫn xuất dữ liệu vòng đời sản phẩm
description: Hướng dẫn xuất dữ liệu về thông tin vòng đời sản phẩm
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546990"
---
# <a name="lifecycle-data-export-guidance"></a>Hướng dẫn xuất dữ liệu vòng đời sản phẩm
Tài liệu này mô tả cách sử dụng tệp xuất sản phẩm.

## <a name="query-information"></a>Thông tin ruy vấn
Trong văn bản Excel, có các trường để giúp xác định dữ liệu nằm trong bảng sản phẩm.

### <a name="end-of-support"></a>Kết thúc Hỗ trợ
Giá trị kết thúc hỗ trợ sẽ lọc các sản phẩm theo ngày kết thúc hỗ trợ hoặc ngày kết thúc phát hành sản phẩm.

Các giá trị có khả năng xảy : Tất cả (không áp dụng bộ lọc), Năm và Phạm vi.

### <a name="family"></a>Nhánh
Giá trị Nhánh lọc các sản phẩm theo cấp độ phân nhánh trong hệ thống phân cấp được biết đến như một Nhánh.

Các giá trị có khả năng xảy : Tất cả (không áp dụng bộ lọc), Tên Gia đình

### <a name="group"></a>Nhóm
Giá trị nhóm sẽ lọc các sản phẩm trong mức phân cấp (nhánh) của nhóm đó đến một nhóm cụ thể.

Các giá trị có khả năng xảy : Tất cả (không áp dụng bộ lọc), Tên Nhóm

## <a name="table-columns"></a>Các cột trong Bảng
Bảng sản phẩm bao gồm các cột xác định sản phẩm, phiên bản, bản phát hành, và ngày hỗ trợ tương ứng.

> [!NOTE]
> Mỗi sản phẩm, phiên bản và bản phát hành sẽ có một tổ hợp hàng tương .

### <a name="product"></a>Sản phẩm
Tên sản phẩm.

### <a name="edition"></a>Phiên bản
Cột phiên bản sẽ được cấp tự động khi sản phẩm có phiên bản. Khi không có phiên bản sản phẩm, trường này sẽ được để trống.

### <a name="release"></a>Bản phát hành
Cột bản phát hành sẽ được cấp tự động khi sản phẩm có nhiều bản phát hành.
Khi sản phẩm chỉ có một bản phát hành, trường này sẽ trống.

### <a name="support-policy"></a>Chính sách Hỗ trợ
Trường này xác định chính sách hỗ trợ mà sản phẩm tuân theo.

Các giá trị có khả năng xảy ra: [Cố định](/lifecycle/policies/fixed), [Hiện đại](/lifecycle/policies/modern), Cấu phần

### <a name="start-date"></a>Ngày Bắt đầu Vòng đời
Ngày bắt đầu hỗ trợ sản phẩm.

### <a name="mainstream-date"></a>Ngày Chính
Khi Chính sách hỗ trợ là **Cố định** hoặc **Cấu phần**, đây là ngày kết thúc chính thức của sản phẩm.
  
Khi Chính sách hỗ trợ là **Hiện đại**, phần này sẽ trống.

### <a name="extended-end-date"></a>Ngày Kết thúc Hỗ trợ Mở rộng
Khi Chính sách Hỗ trợ là **Cố định** hoặc là **Cấu phần** thì đây là ngày kết thúc đã được mở rộng của sản phẩm.

Khi Chính sách hỗ trợ là **Hiện đại**, phần này sẽ trống.

### <a name="retirement-date"></a>Ngày Ngưng hoạt 
Khi Chính sách hỗ trợ là **Cố định** hoặc **Cấu phần**, phần này sẽ trống.

Khi Chính sách hỗ trợ là **Hiện đại**, đây sẽ là ngày ngưng hoạt động của sản phẩm.

### <a name="release-start-date"></a>Ngày Bắt đầu Bản phát hành
Ngày bắt đầu hỗ trợ cho bản phát hành. Khi sản phẩm chỉ có một bản phát hành, trường này sẽ trống.
 
### <a name="release-end-date"></a>Ngày Kết thúc Bản 
Ngày kết thúc hỗ trợ cho bản phát hành.
Khi sản phẩm chỉ có một bản phát hành, trường này sẽ trống.

### <a name="docs-url"></a>Đường tài liệu
Đường đến tài liệu mở rộng.
