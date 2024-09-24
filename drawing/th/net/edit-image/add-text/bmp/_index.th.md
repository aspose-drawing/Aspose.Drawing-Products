---
title: เพิ่มข้อความไปที่ BMP ผ่าน .NET
weight: 20
url: /th/net/edit-image/add-text/bmp/
description: เพิ่มข้อความลงในไฟล์ภาพ BMP โดยใช้ไลบรารีกราฟิก .NET
keywords: เพิ่มข้อความ to image, เพิ่มข้อความ to BMP, เพิ่มข้อความ to bitmap, เพิ่มข้อความ via C#, 2D graphics, drawing API, edit bitmap C#, Drawing สำหรับ .NET, save bitmap, save BMP image, cross-platform 2D graphic library, Bitmap class, raster graphics drawing, draw text, rendering raster images, BMP image file
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="เพิ่มข้อความลงในไฟล์รูปภาพ BMP โดยใช้ C#" h2="ยกระดับรูปภาพ BMP ของคุณ: การเพิ่มข้อความด้วย API การวาด .NET" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/drawing/headers/aspose_drawing-for-net.svg" pfName="Aspose.Drawing" subTitlepfName="สำหรับ .NET" downloadUrl="https://releases.aspose.com/drawing/net/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Drawing" subTitlepfName="สำหรับ .NET" >}}


{{% blocks/products/pf/agp/content h2="วิธีเพิ่มข้อความลงในไฟล์รูปภาพ BMP ใน C#" %}}

<p align="justify" style="text-indent:50px;font-size:15px;">
ให้ภาพ BMP ของคุณดูเป็นมืออาชีพด้วยการใช้ข้อความ <a href="https://products.aspose.com/drawing/net">Aspose.Drawing สำหรับ .NET</a> เอพีไอ เครื่องมืออเนกประสงค์นี้ช่วยให้คุณสามารถเพิ่มข้อความลงในรูปภาพของคุณได้อย่างราบรื่น ไม่ว่าคุณจะใส่คำอธิบายประกอบ ใส่ป้ายกำกับ หรือใส่ลายน้ำ ด้วย Aspose.Drawing API คุณสามารถวาดข้อความลงบนรูปภาพ BMP ได้อย่างง่ายดายโดยใช้ C# ใช้คลาสบิตแมปและความสามารถในการวาดกราฟิกแรสเตอร์เพื่อให้ได้ผลลัพธ์ที่แม่นยำและปรับแต่งได้ สัมผัสประสบการณ์ความสะดวกสบายและความยืดหยุ่นในการเพิ่มข้อความลงในรูปภาพ BMP ด้วย Drawing API ของ .NET และยกระดับโครงการแก้ไขรูปภาพของคุณไปสู่อีกระดับหนึ่ง เปิด <a href="https://www.nuget.org/packages/aspose.drawing">นูเก็ต</a> ผู้จัดการแพ็คเกจและค้นหา <b>Aspose.Drawing</b> และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console</p>

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}
```cs
PM> Install-Package Aspose.Drawing
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการเพิ่มข้อความลงในรูปภาพ BMP ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

คุณต้องมี [aspose.drawing.dll](https://downloads.aspose.com/drawing/net) เพื่อลองใช้เวิร์กโฟลว์ต่อไปนี้ในสภาพแวดล้อมของคุณเอง

{{% /blocks/products/pf/agp/text %}}

+ สร้างวัตถุบิตแมปจากไฟล์รูปภาพ BMP โดยใช้คลาส 'Bitmap'
+ สร้างวัตถุกราฟิกโดยใช้วิธี `Graphics.FromImage()`
+ กำหนดรูปแบบสตริงข้อความและคุณสมบัติการจัดตำแหน่ง
+ วาดข้อความด้วยวิธี `DrawString()` โดยใช้แบบอักษร สี และพิกัดของข้อความที่ต้องการ
+ บันทึกบิตแมปที่สร้างขึ้นในรูปแบบภาพ BMP

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Drawing สำหรับ .NET รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่รองรับ .NET Framework, .NET Core, Windows Application, ASP.NET Web Application
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Drawing สำหรับ .NET อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="เพิ่มข้อความลงในไฟล์รูปภาพ BMP - C#" offSpacer="" %}}
{{< gist "aspose-com-gists" "8b1dc03ab805ef18eea88d4c442331e9" "Examples-CSharp-Edit-Image-File-Add-Text-BMP.cs" >}}
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Drawing สำหรับ .NET API" %}}

Aspose.Drawing ไลบรารีกราฟิก 2D ข้ามแพลตฟอร์มที่ได้รับการจัดการอย่างเต็มรูปแบบ มีความเป็นเลิศในการวาดข้อความ รูปทรงเรขาคณิต และรูปภาพ มี API ที่เข้ากันได้กับ System.Drawing ซึ่งแปลงโค้ดที่มีอยู่ซึ่งอาศัย System.Drawing ให้เป็นโซลูชันข้ามแพลตฟอร์มได้อย่างง่ายดาย Aspose.Drawing พัฒนาขึ้นโดยเทียบกับ .NET Standard 2.0 โดยค้นหาแอปพลิเคชันบนเว็บ อุปกรณ์เคลื่อนที่ เดสก์ท็อป คลาวด์ และ IoT

เอ็นจิ้นการวาดภาพภายใน Aspose.Drawing ช่วยให้ผู้ใช้สามารถเรนเดอร์กราฟิกแบบเวกเตอร์ รวมถึงเส้น เส้นโค้ง และตัวเลข ควบคู่ไปกับองค์ประกอบข้อความที่หลากหลายในแบบอักษร ขนาด และสไตล์ต่างๆ กระบวนการเรนเดอร์นี้เกิดขึ้นได้อย่างราบรื่นบนภาพแรสเตอร์ โดยรองรับรูปแบบไฟล์กราฟิกที่ใช้กันทั่วไปมากมาย

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ประมวลผล BMP ผ่านแอปออนไลน์ฟรี" sectionDescription="สร้างภาพ BMP รวมถึงเพิ่มข้อความลงในภาพโดยไปที่ [เว็บไซต์สาธิตสด](https://products.aspose.app/drawing) การสาธิตสดมีข้อดีดังต่อไปนี้:" >}}

{{< blocks/products/pf/agp/democard icon="fa-cogs" text="ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
{{< blocks/products/pf/agp/democard icon="fa-edit" text="ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
{{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัปโหลดไฟล์ของคุณและสร้างภาพวาดข้อความบนเว็บเบราว์เซอร์" >}}
{{< blocks/products/pf/agp/democard icon="fa-download" text="รับลิงค์ดาวน์โหลดไฟล์ BMP ที่ได้ทันที" >}}

{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม" >}}

ไฟล์ที่มีนามสกุล .BMP หมายถึงไฟล์ภาพบิตแมปที่ใช้จัดเก็บภาพดิจิทัลบิตแมป รูปแบบรูปภาพเหล่านี้มีจุดประสงค์เพื่อเปิดไฟล์บนหลายแพลตฟอร์ม เช่น Microsoft Windows, Mac และ Linux รูปแบบไฟล์ BMP สามารถจัดเก็บข้อมูลเป็นภาพดิจิตอลสองมิติทั้งในรูปแบบขาวดำและสีที่มีความลึกของสีต่างๆ

{{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->


{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการปรับขนาดอื่น ๆ ที่รองรับ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/bmp/" name="BMP" description="รูปภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/jpeg/" name="JPEG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/tiff/" name="TIFF" description="รูปแบบภาพที่แท็ก" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
