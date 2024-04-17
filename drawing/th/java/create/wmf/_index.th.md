---
title: สร้างไฟล์ภาพ WMF ผ่าน Java
weight: 20
url: /th/java/create/wmf/
description: สร้างไฟล์ภาพ WMF ผ่าน Java
keywords: create WMF via Java, 2D graphics, drawing API, create metafile in Java, Drawing สำหรับ Java, save WMF image file, cross-platform 2D graphic library, Metafile class, vector graphics drawing, draw line, WMF image file, Graphics file formats
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ใช้ Java เพื่อสร้างไฟล์ภาพ WMF" h2="เพิ่มขีดความสามารถของแอปพลิเคชัน Java ของคุณโดยการจัดการไฟล์ภาพเวกเตอร์ WMF" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/drawing/headers/aspose_drawing-for-java.svg" pfName="Aspose.Drawing" subTitlepfName="สำหรับ Java" downloadUrl="https://releases.aspose.com/drawing/java/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Drawing" subTitlepfName="สำหรับ Java" >}}


{{% blocks/products/pf/agp/content h2="วิธีสร้างไฟล์รูปภาพ WMF โดยใช้ Java" %}}

ค้นพบความง่ายในการสร้างไฟล์ภาพเวกเตอร์ WMF โดยใช้ Java คู่มือนี้นำเสนอข้อมูลเชิงลึกและคำแนะนำที่สำคัญซึ่งเหมาะสำหรับนักพัฒนาซอฟต์แวร์ทุกระดับ สำรวจขั้นตอนการผสานรวมที่ราบรื่นสำหรับการสร้างอิมเมจ WMF ซึ่งช่วยเพิ่มความสามารถด้านการเขียนโปรแกรมของคุณ ใช้ไลบรารี [Aspose.Drawing สำหรับ Java](https://products.aspose.com/drawing/java) ซึ่งมีชื่อเสียงในด้าน API การวาดภาพกราฟิก 2 มิติที่มีฟีเจอร์หลากหลาย ทรงพลัง และใช้งานง่ายสำหรับแพลตฟอร์ม Java เข้าถึงเวอร์ชันล่าสุดได้โดยตรงจากที่เก็บ [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-drawing/) และรวมเข้ากับโปรเจ็กต์ที่ใช้ Maven ของคุณโดยใช้การกำหนดค่าที่ระบุกับ ไฟล์ pom.xml

{{% blocks/products/pf/agp/code-block title="พื้นที่เก็บข้อมูล" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://releases.aspose.com/java/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพาอาศัยกัน" offSpacer="true" %}}

```xml
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-drawing</artifactId>
<version>version of aspose-drawing API</version>
<classifier>jdk18</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนการสร้าง WMF ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

คุณต้องมี [aspose-drawing-version-jdk18.jar](https://releases.aspose.com/drawing/java/) เพื่อลองใช้เวิร์กโฟลว์ต่อไปนี้ในสภาพแวดล้อมของคุณเอง

{{% /blocks/products/pf/agp/text %}}

+ สร้างวัตถุไอน้ำหน่วยความจำ
+ สร้างวัตถุ metafile โดยใช้คลาส Metafile
+ สร้างวัตถุกราฟิกโดยใช้วิธี Graphics.FromImage()
+ วาดองค์ประกอบกราฟิก
+ เขียนข้อมูลเป็นรูปแบบไฟล์ WMF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Drawing สำหรับ Java รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- ติดตั้ง JDK 1.8 หรือสูงกว่าแล้ว

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สร้างไฟล์รูปภาพ WMF - Java" offSpacer="" %}}
{{< gist "aspose-com-gists" "3562c2fe053aae0bda46f32abae6062a" "Examples-Java-Create-WMF-Image-File.java" >}}
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Drawing สำหรับ Java API" %}}

Aspose.Drawing ทำหน้าที่เป็นไลบรารีกราฟิก 2D ข้ามแพลตฟอร์มที่มีการจัดการเต็มรูปแบบ อำนวยความสะดวกในการสร้างข้อความ เรขาคณิต และรูปภาพ API ที่เข้ากันได้กับ Java ข้ามแพลตฟอร์มช่วยให้สามารถผสานรวมระบบปฏิบัติการที่หลากหลายได้อย่างง่ายดายเมื่อติดตั้ง Java ออกแบบมาเพื่อเทียบกับ Java 8 ทำให้ Aspose.Drawing ค้นหาแอปพลิเคชันในสภาพแวดล้อมเว็บ มือถือ เดสก์ท็อป และคลาวด์ เครื่องมือวาดภาพช่วยให้ผู้ใช้สามารถเรนเดอร์กราฟิกแบบเวกเตอร์ ซึ่งครอบคลุมเส้น เส้นโค้ง และตัวเลข ควบคู่ไปกับข้อความในแบบอักษร ขนาด และสไตล์ที่หลากหลายบนภาพเวกเตอร์หรือแรสเตอร์ในรูปแบบไฟล์กราฟิกที่แพร่หลาย ความสามารถในการเรนเดอร์นี้รวมอยู่ใน Aspose.Drawing ส่งเสริมการบูรณาการอย่างราบรื่นและความเข้ากันได้กับรูปแบบไฟล์กราฟิกที่ใช้กันทั่วไปมากมาย

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/about-file-text fileFormat="WMF" readMoreLink="https://docs.fileformat.com/image/wmf/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม" >}}

ไฟล์ที่มีนามสกุล .WMF ทำหน้าที่เป็นคอนเทนเนอร์สำหรับจัดเก็บข้อมูลรูปภาพทั้งแบบเวกเตอร์และบิตแมป โดยเฉพาะอย่างยิ่ง WMF อยู่ในหมวดหมู่รูปแบบไฟล์เวกเตอร์ภายในรูปแบบไฟล์กราฟิก ซึ่งนำเสนอการแสดงที่ไม่ขึ้นอยู่กับอุปกรณ์ รูปแบบนี้ให้ความคล่องตัวในการจัดเก็บข้อมูลกราฟิก โดยรองรับแอปพลิเคชันและแพลตฟอร์มที่หลากหลาย

{{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->


{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับในการสร้าง" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/bmp/" name="BMP" description="รูปภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/emf/" name="EMF" description="รูปแบบ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/jpeg/" name="JPEG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/tiff/" name="TIFF" description="รูปแบบภาพที่แท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/java/create/wmf/" name="WMF" description="ไมโครซอฟต์ วินโดวส์ เมตาไฟล์" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
