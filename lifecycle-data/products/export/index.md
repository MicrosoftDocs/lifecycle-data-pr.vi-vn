---
title: Xuất dữ liệu vòng đời sản phẩm
description: Xuất dữ liệu về thông tin vòng đời sản phẩm
ms.date: 11/01/2021
layout: ContentPage
ms.openlocfilehash: be7a11f46a034a396e6e74877834d847557cc708
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 11/02/2021
ms.locfileid: "3547000"
---
# <a name="lifecycle-data-export"></a>Xuất dữ liệu vòng đời sản phẩm

## <a name="export-all-products"></a>Xuất dữ liệu toàn bộ sản phẩm
Xuất dữ liệu vòng đời của tất cả sản phẩm bằng cách nhấp vào bên dưới:

> [!div class="nextstepaction"]
> [Xuất dữ liệu toàn bộ sản phẩm](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a>Xuất dữ liệu sản phẩm theo Nhánh và Nhóm
Chọn một Nhánh và sau đó là một Nhóm sản phẩm để xuất dữ liệu. Lưu ý: Quá trình xuất dữ liệu sẽ bắt đầu khi chọn giá trị Nhóm. 

> [!div class="op_multi_selector" title1="Nhánh" title2="Nhóm"]
> - [(.NET | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET'))
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET',group='.NET'))
> - [(Azure | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure'))
> - [Azure | AI](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='AI'))
> - [(Azure | Azure)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Azure'))
> - [(Azure | Cơ sở dữ liệu)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Databases'))
> - [(Azure | Khác)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Other'))
> - [(Dynamics | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics'))
> - [(Dynamics | Dynamics)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics'))
> - [(Dynamics | Dynamics 365](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20365'))
> - [(Dynamics | Dynamics AX)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20AX'))
> - [(Dynamics | Dynamics C5)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20C5'))
> - [(Dynamics | Dynamics CRM)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20CRM'))
> - [(Dynamics | Dynamics GP)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20GP'))
> - [(Dynamics | Dynamics NAV)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20NAV'))
> - [(Dynamics | Dynamics POS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20POS'))
> - [(Dynamics | Dynamics RMS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20RMS'))
> - [(Dynamics | Dynamics SL)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20SL'))
> - [(Dynamics | Khác)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Other'))
> - [(Expression | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression'))
> - [(Expression | Expression)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression',group='Expression'))
> - [Microsoft 365 | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365'))
> - [(Microsoft 365 | Enterprise Mobility + Bảo mật)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Enterprise%20Mobility%20%2B%20Security'))
> - [(Microsoft 365 | Trình quản lý Danh tính)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Identity%20Management'))
> - [Microsoft Connected Services Framework | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework'))
> - [(Microsoft Connected Services Framework | Khung Dịch vụ Kết nối)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework',group='Connected%20Services%20Framework'))
> - [(Microsoft Customer Care Framework | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework'))
> - [(Microsoft Customer Care Framework | Khung Chăm sóc Khách hàng)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework',group='Customer%20Care%20Framework'))
> - [(Microsoft Edge | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge'))
> - [(Microsoft Edge | Edge)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge',group='Edge'))
> - [(Microsoft Internet Explorer | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer'))
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer',group='Internet%20Explorer'))
> - [(Microsoft Office | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office'))
> - [(Microsoft Office | Máy khách)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Client'))
> - [(Microsoft Office | Bảo mật)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Security'))
> - [(Microsoft Office | Máy chủ)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Server'))
> - [(Microsoft Servers | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers'))
> - [(Microsoft Servers | Máy chủ BizTalk)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='BizTalk%20Server'))
> - [(Microsoft Servers | Máy chủ Thương mại)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Commerce%20Server'))
> - [(Microsoft Servers | Máy chủ Quản lý Nội dung)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Content%20Management%20Server'))
> - [(Microsoft Servers | Máy chủ Tích hợp Lưu trữ)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Host%20Integration%20Server'))
> - [(Microsoft Servers | Cổng ứng dụng thông minh)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Intelligent%20Application%20Gateway'))
> - [(Microsoft Servers | Bảo mật)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Security'))
> - [(Microsoft System Center | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center'))
> - [(Microsoft System Center | Trung tâm Hệ thống)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center',group='System%20Center'))
> - [(Silverlight | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight'))
> - [(Silverlight| Silverlight)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight',group='Silverlight'))
> - [(SQL Server | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server'))
> - [(SQL Server | Nguồn BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='Power%20BI'))
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='SQL%20Server'))
> - [(Visual Studio | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio'))
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio',group='Visual%20Studio'))
> - [(Windows | Tất cả)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows'))
> - [(Windows | Máy khách)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Client'))
> - [(Windows | IoT)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='IoT'))
> - [(Windows | Mobile)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Mobile'))
> - [(Windows | Bảo mật)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Security'))
> - [(Windows | Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Server'))

## <a name="export-products-by-end-of-support-date"></a>Xuất sản phẩm vào cuối ngày hỗ trợ
Chọn một năm để xem sản phẩm kết thúc hỗ trợ. Lưu ý: Xuất sẽ bắt đầu khi giá trị Năm được chọn.

> [!div class="op_single_selector"]
> - [12 Tháng Tiếp theo](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=12))
> - [6 Tháng Tiếp theo](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=6))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
> - [2031](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2031))
