---
title: .NET के माध्यम से GIF में टेक्स्ट जोड़ें
weight: 20
url: /hi/net/edit-image/add-text/gif/
description: .NET ग्राफ़िक लाइब्रेरी का उपयोग करके GIF छवि फ़ाइल में टेक्स्ट जोड़ें
keywords: लेख जोड़ें to image, लेख जोड़ें to GIF, लेख जोड़ें to bitmap, लेख जोड़ें via C#, 2D graphics, drawing API, edit bitmap C#, Drawing .NET के लिए, save bitmap, save GIF image, cross-platform 2D graphic library, Bitmap class, raster graphics drawing, draw text, rendering raster images, GIF image file
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# का उपयोग करके GIF छवि फ़ाइलों में टेक्स्ट जोड़ें" h2="अपनी GIF छवियाँ उन्नत करें: .NET ड्रॉइंग एपीआई के साथ टेक्स्ट जोड़ना" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/drawing/headers/aspose_drawing-for-net.svg" pfName="Aspose.Drawing" subTitlepfName=".NET के लिए" downloadUrl="https://releases.aspose.com/drawing/net/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Drawing" subTitlepfName=".NET के लिए" >}}


{{% blocks/products/pf/agp/content h2="C# में GIF छवि फ़ाइल में टेक्स्ट कैसे जोड़ें" %}}

<p align="justify" style="text-indent:50px;font-size:15px;">
टेक्स्ट का उपयोग करके अपनी GIF छवियों को एक पेशेवर स्पर्श दें <a href="https://products.aspose.com/drawing/net">.NET के लिए Aspose.Drawing</a> एपीआई. यह बहुमुखी उपकरण आपको अपनी छवियों में निर्बाध रूप से टेक्स्ट जोड़ने की अनुमति देता है, चाहे आप एनोटेट कर रहे हों, लेबल कर रहे हों या वॉटरमार्क कर रहे हों। Aspose.Drawing API के साथ, आप C# का उपयोग करके आसानी से GIF छवियों पर टेक्स्ट बना सकते हैं। सटीक और अनुकूलित परिणाम प्राप्त करने के लिए बिटमैप क्लास और रैस्टर ग्राफिक्स ड्राइंग क्षमताओं का उपयोग करें। .NET के ड्रॉइंग एपीआई के साथ GIF छवियों में टेक्स्ट जोड़ने की सुविधा और लचीलेपन का अनुभव करें, और अपनी छवि संपादन परियोजनाओं को नई ऊंचाइयों तक ले जाएं। खुला <a href="https://www.nuget.org/packages/aspose.drawing">नुगेट</a> पैकेज मैनेजर, और खोजें <b>Aspose.Drawing</b> और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।</p>

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}
```cs
PM> Install-Package Aspose.Drawing
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से GIF छवि में टेक्स्ट जोड़ने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

आपको अपने परिवेश में निम्नलिखित वर्कफ़्लो आज़माने के लिए [aspose.drawing.dll](https://downloads.aspose.com/drawing/net) की आवश्यकता है।

{{% /blocks/products/pf/agp/text %}}

+ 'बिटमैप' क्लास का उपयोग करके GIF छवि फ़ाइल से एक बिटमैप ऑब्जेक्ट बनाएं।
+ `Graphics.FromImage()` विधि का उपयोग करके एक ग्राफ़िक्स ऑब्जेक्ट बनाएं।
+ टेक्स्ट स्ट्रिंग प्रारूप और संरेखण गुणों को परिभाषित करें।
+ वांछित टेक्स्ट फ़ॉन्ट, रंग और निर्देशांक का उपयोग करके `DrawString()` विधि से टेक्स्ट बनाएं।
+ बनाए गए बिटमैप को GIF छवि प्रारूप में सहेजें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

.NET के लिए Aspose.Drawing सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस यह सुनिश्चित करें कि आपके पास निम्नलिखित आवश्यकताएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज या .NET Framework, .NET Core, विंडोज एप्लिकेशन, ASP.NET वेब एप्लिकेशन के साथ संगत ओएस।
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसा विकास वातावरण।
- .NET के लिए Aspose.Drawing आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="GIF छवि फ़ाइल - C# में टेक्स्ट जोड़ें" offSpacer="" %}}
{{< gist "aspose-com-gists" "8b1dc03ab805ef18eea88d4c442331e9" "Examples-CSharp-Edit-Image-File-Add-Text-GIF.cs" >}}
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2=".NET एपीआई के लिए Aspose.Drawing के बारे में" %}}

Aspose.Drawing, एक पूरी तरह से प्रबंधित, क्रॉस-प्लेटफॉर्म 2डी ग्राफिक लाइब्रेरी, टेक्स्ट, ज्यामिति और छवियों को चित्रित करने में उत्कृष्ट है। यह एक System.Drawing संगत एपीआई प्रदान करता है, जो आपके मौजूदा कोड को आसानी से बदल देता है जो System.Drawing पर निर्भर करता है, वास्तव में क्रॉस-प्लेटफ़ॉर्म समाधान में। .NET Standard 2.0 के विरुद्ध विकसित, Aspose.Drawing वेब, मोबाइल, डेस्कटॉप, क्लाउड और IoT परिदृश्यों में एप्लिकेशन ढूंढता है।

Aspose.Drawing के भीतर ड्राइंग इंजन उपयोगकर्ताओं को विभिन्न फ़ॉन्ट, आकार और शैलियों में विविध पाठ तत्वों के साथ-साथ रेखाओं, वक्रों और आकृतियों सहित वेक्टर ग्राफिक्स प्रस्तुत करने का अधिकार देता है। यह रेंडरिंग प्रक्रिया रेखापुंज छवियों पर निर्बाध रूप से होती है, जो आमतौर पर उपयोग किए जाने वाले ग्राफिक्स फ़ाइल स्वरूपों की एक विस्तृत श्रृंखला का समर्थन करती है।

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="निःशुल्क ऑनलाइन ऐप के माध्यम से GIF प्रक्रिया करें" sectionDescription="हमारी [लाइव डेमो वेबसाइट](https://products.aspose.app/drawing) पर जाकर GIF छवियां बनाएं, साथ ही छवियों में टेक्स्ट जोड़ें। लाइव डेमो के निम्नलिखित लाभ हैं:" >}}

{{< blocks/products/pf/agp/democard icon="fa-cogs" text="कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
{{< blocks/products/pf/agp/democard icon="fa-edit" text="कोई कोड लिखने की जरूरत नहीं" >}}
{{< blocks/products/pf/agp/democard icon="fa-file-text" text="बस अपनी फ़ाइलें अपलोड करें और वेब-ब्राउज़र में टेक्स्ट ड्राइंग बनाएं" >}}
{{< blocks/products/pf/agp/democard icon="fa-download" text="परिणामी GIF फ़ाइल के लिए तुरंत डाउनलोड लिंक प्राप्त करें" >}}

{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" whatIsFormat1="क्या है" whatIsFormat2="फ़ाइल फ़ारमैट" readMoreFormat="और पढ़ें" >}}

.GIF एक्सटेंशन वाली फ़ाइलें बिटमैप छवि फ़ाइलों का प्रतिनिधित्व करती हैं जिनका उपयोग बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। ये छवि प्रारूप माइक्रोसॉफ्ट विंडोज, मैक और लिनक्स जैसे कई प्लेटफार्मों पर फ़ाइल खोलने के उद्देश्य से कार्य करता है। GIF फ़ाइल प्रारूप डेटा को मोनोक्रोम और साथ ही विभिन्न रंग गहराई के साथ रंग प्रारूप दोनों में दो-आयामी डिजिटल छवियों के रूप में संग्रहीत कर सकता है।

{{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->


{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित आकार परिवर्तन प्रारूप" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/bmp/" name="BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/gif/" name="GIF" description="ग्राफ़िकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/jpeg/" name="JPEG" description="फ़ोटोग्राफ़ी संबंधी विशेषज्ञों का संयुक्त समूह" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/png/" name="PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/drawing/net/edit-image/add-text/tiff/" name="TIFF" description="टैग किया गया छवि प्रारूप" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
