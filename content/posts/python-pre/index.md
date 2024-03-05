---
title : 'Başlamadan Önce'
date : 2024-03-05T02:15:06+03:00
categories : ["programlama", "python", "temel kavramlar"]
draft : true
series: ["python-temel"]
series_order: 1

---
# Önbilgiler 

Programlama ve bilgisayarlar hakkında kısa bir bilgi vermeden başlamayalım. Sistemin çalışma mantığını anlamanız adın bu kısa ve zevkli yazıyı okumanızı tavsiye ederim. Dilerseniz son başlığa geçip ide'yi kurduktan sonra ilk derse de geçebilirsiniz. 

![turing](turing.webp)

## Kullanıcı - Bilgisayar Etkileşimi 

Bilgisayarların çalışma mantığı temelde basit bir prensibe dayanır: veri işleme. Bu işlem, bir dizi elektronik bileşen aracılığıyla gerçekleştirilir ve bu bileşenlerin en temeli transistördür. Transistörler, bilgisayarın temel yapı taşlarından biridir ve veri işlemede temel rol oynarlar. İşleyişlerini, transistörlerin iletim (açık) ve kesim (kapalı) durumları üzerinden açıklayarak başlayalım, ardından bu durumların programlama ve makine koduyla nasıl ilişkilendiğini inceleyeceğiz.

## Transistörler ve Mantıksal Kapılar
Transistörler, elektrik akımını kontrol etmek için kullanılan minyatür elektronik bileşenlerdir. Temel olarak, bir transistör bir tür "anahtar" olarak işlev görür ve elektrik akımının geçip geçemeyeceğini kontrol eder. Transistörlerin bu temel işlevi, bilgisayarların temel mantık işlemlerini (AND, OR, NOT gibi) gerçekleştirmesini sağlar. Bu mantık işlemleri, mantıksal kapılar adı verilen devreler kullanılarak yapılır ve bu kapılar, transistörlerin farklı kombinasyonlarından oluşur.

## Programlama ve Makine Kodu
Programlama dilleri, insanların bilgisayarlarla iletişim kurmasını sağlayan araçlardır. Bu diller, yüksek seviyeden (insanların kolayca anlayabileceği) düşük seviyeye (bilgisayarın anlayabileceği) doğru çeşitlilik gösterir. En düşük seviye, makine kodudur; bu, bilgisayarın doğrudan anlayabildiği ve işleyebildiği, 0'lar ve 1'lerden oluşan bir dildir. Her bir 0 veya 1, bir transistörün açık veya kapalı durumunu temsil eder.

Bir programlama diliyle yazılmış bir program, çeşitli aşamalardan geçerek makine koduna dönüştürülür. Bu süreç genellikle derleme olarak adlandırılır. Derlenmiş makine kodu, işlemci tarafından doğrudan yürütülebilir. İşlemci, bu kodu okuyarak transistörlerin ne zaman açılıp kapanacağını belirler, bu da bilgisayarın belirli görevleri yerine getirmesini sağlar.

# 0 ve 1'lerin Hayat Buluşu 

Makine kodunun yazıya, görüntüye, programa ve diğer çıktı türlerine dönüşümü, bilgisayar sistemlerinin temel işlevlerinden biridir ve bu işlemler, veri işleme ve dönüşüm mekanizmaları aracılığıyla gerçekleştirilir. Bu süreç, makine kodunun nasıl daha karmaşık veri yapılarına ve nihayetinde kullanıcıların anlayabileceği formatlara dönüştürüldüğünü kapsar. Bu dönüşüm işlemlerinin temel aşamalarını inceleyelim:

## Makine Kodundan Yüksek Seviye Kodlara

Bir bilgisayarın işlemcisi, makine kodunu doğrudan çalıştırır. Bu kod, çok düşük seviyeli bir dil olduğundan, yalnızca temel işlemleri (örneğin, aritmetik işlemler, mantıksal işlemler ve veri taşıma işlemleri) ifade eder. Yüksek seviye dillerde (örneğin, Python, Java, C++) yazılmış programlar, derleyiciler ve yorumlayıcılar aracılığıyla bu düşük seviyeli makine koduna dönüştürülür. Bu dönüşüm, programın bilgisayarın işlemcisi tarafından anlaşılır hale gelmesini sağlar.

## Veri Yapıları ve Abstraksiyon

Programlar çalışırken, makine kodu, çeşitli veri yapıları ile çalışır. Bu veri yapıları, sayılar, metinler, resimler veya daha karmaşık nesneler olabilir. Programlama dilleri, bu verileri işlemek için abstraksiyon katmanları sağlar. Örneğin, bir metin dizisi veya bir resim, bellekte sayı dizileri olarak saklanır. Bu sayılar, belirli formatlara (örneğin, ASCII kodu veya piksel renk değerleri) uygun olarak yorumlanır ve işlenir.

## Çıktıların Üretilmesi

Bilgisayarlar, makine kodundan elde edilen işlemleri kullanarak çeşitli çıktılar üretebilir. Bu çıktılar arasında yazılı belgeler, grafikler, sesler ve videolar bulunabilir. Örneğin:

- **Metin İşleme:** Makine kodu, metin düzenleyicilerdeki komutları işleyerek yazılı belgeler oluşturabilir. Bu, karakter kodlarının belirli bir format kullanılarak ekranda gösterilmesini içerir.
- **Grafik ve Görüntü İşleme:** Grafik işleme birimleri (GPU'lar) ve özel grafik kütüphaneleri, makine kodunu, ekranda görseller ve animasyonlar oluşturacak şekilde işler. Her bir pikselin rengi, belirli bir sayı dizisiyle temsil edilir ve bu sayılar, GPU tarafından işlenir.
- **Ses ve Video:** Ses ve video dosyaları, örneğin sıkıştırma algoritmaları kullanılarak işlenir ve çözülür. Bu işlemler, sayı dizilerinin ses dalgalarına veya görüntü frame'lerine dönüştürülmesini içerir.

## Kullanıcı Arayüzleri

Kullanıcı arayüzleri, kullanıcıların programlarla etkileşim kurmasını sağlar ve bu etkileşimler sonucunda makine kodu yürütülür. Kullanıcı arayüzleri, metin tabanlı (örneğin, komut satırı arayüzleri) veya grafik tabanlı (Grafik Kullanıcı Arayüzleri, GUI'ler) olabilir. Kullanıcı girdileri (örneğin, fare tıklamaları veya klavye girdileri), programın işleyeceği verilere dönüştürülür ve bu, belirli çıktıların üretilmesine yol açar.

Bu süreçlerin tümü, bilgisayarların çok çeşitli görevleri gerçekleştirebilmesini sağlar. Temelde basit olan makine kodu, karmaşık yazılımların ve kullanıcı dostu arayüzlerin temelini oluşturur. Bu dönüşüm mekanizmaları sayesinde, bilgisayarlar geniş bir yelpazede veri işleme ve görselleştirme yeteneklerine sahiptir.

# Gerekli Çalışma Ortamının Sağlanması 

Temel seviye için hiçbir ide kurulumu yapmayacağız. Tüm programlama işlemleri için online bir ide olan [replit'i](https://replit.com/signup) kullanacağız.
Proje ve ödevlerin çözümlerinide replit üzerinden sağlayacağım. 

# Seri Takibi 

Bu yazının üst ve alt bölümünde de gördüğünüz üzere bir seri yapısı oluşturdum. Bu sayede dersler arasında hızlı ve kolay bir geçiş yapabilirsiniz.
Dilerseniz ilk dersimize başlayalım.