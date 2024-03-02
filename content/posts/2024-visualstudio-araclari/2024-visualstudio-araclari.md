+++
title = "2024'te Üretkenliğinizi Artıracak Visual Studio Kod Eklentileri Bölüm : 1"
date = 2024-02-14
draft = true
featured_image = '2024-visualstudio-araclari/featured.png'
tags = ["vscode", "ide", "programlama","araçlar"]
+++


aa

2023 Stack Overflow Geliştirici Anketi'ne göre, Visual Studio Code (VSCode olarak da bilinir) en çok tercih edilen tümleşik geliştirici ortamı (IDE) aracı olarak sıralandı.

Visual Studio Code, kutudan çıktığı gibi birçok harika özelliğe sahip olup, gelişmiş işlevsellik eklemek için geniş bir uzantı topluluğunu destekler.

![Visual-studio](2024-visualstudio-araclari/visual-studio.png)

VSCode'un popülaritesini gösteren Stack Overflow anketi ekran görüntüsü (%73.71 katılımcı tarafından kullanılıyor)

Uzantılar kullanarak VSCode'un kullanılabilir özelliklerini ve araçlarını genişletebilirsiniz. Birçok aracı tek bir yerde toplaması, üretkenliği öldüren bağlam değişikliklerini azaltır.

# **Better Comments**

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments), kod içindeki yorumları güçlendirmenize yardımcı olur. Kod yorumları, okunabilirlik için faydalıdır ve gelecekte başvuru için açıklamalar veya bağlam sağlar. İyi kod yorumları bırakmak, gelecekte başkalarına ve size zaman kazandırabilir.

Desteklenen özellikler arasında uyarıları kategorize etme, sorgular yazma, bir TODO listesi oluşturma ve vurguları gösterme bulunmaktadır. Desteklenen diller için kapsamlı bir liste bulunmaktadır.

Yorum satırları, dışarıda bırakılmalarını vurgulayarak ve kaldırılmaları gerektiğini belirterek koyu gri renkte ve metin üstü çizgili olarak biçimlendirilmiştir.

!https://www.freecodecamp.org/news/content/images/2024/01/better-comments.png

Better Comments ile biçimlendirilmiş kod yorumları:

# **Bookmarks**

hugo da bu şekilde gönderi oluşturdum ancak ne featured image gözüküyor nede article içine koyduğum visual-studio.png dosyası



[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks), kodunuzdaki pozisyonlara yer işareti eklemenizi sağlar. Bu satırlar mavi bir yer işareti simgesi ile belirtilir. Yer işaretleri hızlı referans için düzenlenebilir ve adlandırılabilir.

Tüm yer işaretleri, ayrılmış bir kenar çubuğu bölümünde bulunabilir. Bu, gezinmeyi geliştirmek ve başvuruları aramak için daha az zaman harcamanıza yardımcı olacak harika bir araçtır.

!https://www.freecodecamp.org/news/content/images/2024/01/printscreen-toggle.png

Bookmarks, satır numarasının yanında yer işareti simgesi ile birlikte mavi renkte görüntülenir.

# **Code Spell Checker**

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker), adını hakkıyla taşır. Kod tabanınız boyunca yazım hatalarını bulup düzeltmek için temel bir yazım denetleyicisi sağlar. Yanlış yazılmış kelimeler, dalgalı bir çizgi altı ile belirtilir. Birçok dilde kullanılabilir.

Bu benim kişisel favori uzantılarımdan biridir. Bu sayede birçok yazım hatasını tespit edip düzelttim.

!https://www.freecodecamp.org/news/content/images/2024/01/example.gif

Bu görüntü, Yazım Denetleyicisi'nin yazım hatalarını nasıl algıladığını ve düzelttiğini gösterir.

# **CodeSnap**

[CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap), kodun ekran görüntülerini almak için kullanılır. Kod parçacıklarını kolayca paylaşmak için kullanışlı olabilir.

Kodunuzun bir ekran görüntüsünü almak için (Windows ve Linux'ta Ctrl+Shift+P, OS X'te Cmd+Shift+P) tuşlarına basın ve `CodeSnap`i arayın. Ardından kodunuzu ekran görüntüsü almak istediğiniz alanı seçin, genişliği ayarlayın ve deklanşör düğmesine tıklayın. Ayrıca kodu seçerek, sağ tıklayıp CodeSnap'i seçerek de bir anlık görüntü alabilirsiniz.

Bunu yapabilen web siteleri de bulunsa da, bu tür araçların düzenleyicinizde bulunması, üretkenliği artırmak için daha az bağlam değiştirmeye izin verir.

!https://www.freecodecamp.org/news/content/images/2024/01/material_operator-mono.png

CodeSnap ile oluşturulmuş örnek React kod parçacığı.

# **CodiumAI**

[CodiumAI](https://marketplace.visualstudio.com/items?itemName=Codium.codium) ücretsiz bir yapay zeka destekli kod araç setidir. Kod otomatik tamamlama, sohbet, gelişmiş arama ve öneriler gibi özellikleri destekler.

Yapay zeka, geliştirici verimliliğini artırmada önemli bir oyuncu haline geldi. Test yazma süresinin yarısını harcadığınızı ve böylece diğer önemli, yaratıcı görevlere daha fazla zaman ayırabildiğinizi hayal edin.

Test söz konusu olduğunda, CodiumAI üstündür. Kodu analiz edebilir ve anlamlı testler ve kapsamlı test paketleri oluşturabilir.

!https://www.freecodecamp.org/news/content/images/2024/01/Tests-Gif.gif

CodiumAI, Python kodunun bir bölümüne dayalı bir test paketi oluşturur.

Bu nispeten yeni bir uzantıdır ve hızla popülerlik kazanmaktadır. Desteklenen diller Python, JavaScript, TypeScript, Java, Go ve diğerleridir.

!https://www.freecodecamp.org/news/content/images/2024/01/g_python_random_gen_with_logo.gif

CodiumAI'nin otomatik tamamlama işlevi, doğal dil istemlerine dayalı işlevler oluşturmak için kullanılır.

# **Error Lens**

[Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) improves highlighting of errors, warnings, and other language diagnostics. This is a great debugging and error-prevention tool to have.

Errors will not go unnoticed with this extension. Error and warnings are made prominent by highlighting the entire line, along with the related message printed inline.

[Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) hataların, uyarıların ve diğer dil tanılamalarının vurgulanmasını geliştirir. Bu, sahip olunması gereken harika bir hata ayıklama ve hata önleme aracıdır.

Bu eklenti ile hatalar fark edilmeyecektir. Hata ve uyarılar, satır içinde yazdırılan ilgili mesajla birlikte tüm satır vurgulanarak belirgin hale getirilir

!https://www.freecodecamp.org/news/content/images/2024/01/demo.png

Error Lens bir hatayı tanımlayarak eksik noktalı virgül ve sözdizimi hatası olduğunu bildirir.

Bir ek açıklamaya tıklamak sizi doğrudan ilgili kod satırına yönlendirdiğinden, hataları bulmak için daha az zaman harcayın.

Farklı dillerdeki projelerde çalışan geliştiriciler için değerli kılan birden fazla dil desteği vardır. Ayrıca hataların ve uyarıların görünümünü ve davranışını da yapılandırabilirsiniz.

# **Git History**

[Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory), Git ile sürüm kontrolü için son derece kullanışlı bir uzantıdır (uzantının 10 milyon yüklemesi vardır, bu nedenle popüler olduğu açıktır). Bu uzantı, Git deponuzun ayrıntılı geçmişini doğrudan VSCode arayüzünden keşfetmenizi sağlar. Dosya geçmişini, git günlüğünü görüntüleyebilir ve karşılaştırmalar yapabilirsiniz.

Taahhüt günlüklerinin, dalların ve zaman içindeki dosya değişikliklerinin etkileşimli ve görsel bir temsilini sağlar. Bu uzantı, sürüm kontrollü projeler üzerinde çalışırken daha erişilebilir ve karmaşık olmayan bir deneyim sağlar.

!https://www.freecodecamp.org/news/content/images/2024/01/gitLogv3--1-.gif

Git Geçmişi burada belirli bir commit üzerinde bir etiket oluşturmak için kullanılmaktadır.

# **GitLens**

[GitLens] (https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens), tek bir uzantıda bir araya getirilmiş pek çok özelliği ile en sağlam Git aracıdır. Güçlü bir açık kaynak topluluğuna sahiptir ve sık güncellemelerle aktif desteğe sahip olmaya devam etmektedir.

GitLens ile, doğrudan VSCode'da depolarınız hakkında güçlü bilgiler edinebilirsiniz. Ek açıklamalar, tonlarca Git bilgisini görüntüleyerek editör boyunca entegre edilmiştir.

GitLens'in en kullanışlı özelliklerinden biri suçlama ek açıklamasıdır. Bu, kodu kimin ve ne kadar süre önce yazdığını görmenizi sağlar.

!https://www.freecodecamp.org/news/content/images/2024/01/current-line-blame.png

GitLens, kod satırını kullanıcının (Siz) 4 yıl önce oluşturduğu bir commit'e kadar izliyor.

Kullanışlı bulduğum bir diğer özellik ise interaktif yeniden düzenleme editörü. Bu, yeniden düzenlemeler gerçekleştirirken güzel bir kullanıcı deneyimi sağlıyor.

!https://www.freecodecamp.org/news/content/images/2024/01/rebase.gif

GitLens'in etkileşimli rebase örneği. Komiteler seçilebilir, düzenlenebilir, bırakılabilir, ezilebilir ve daha fazlası yapılabilir.

# **GitHub Copilot**

[GitHub Copilot] (https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) son iki yılda büyük ilgi gördü. Bu ürün, gelişmiş yapay zeka yeteneklerinden yararlanarak kodlama deneyiminde devrim yarattı. Yalnızca kod parçacıklarının tamamlanmasına yardımcı olmakla kalmıyor, aynı zamanda tüm kod satırları veya blokları için akıllı öneriler sunan bir AI çift programlama yardımcı pilotu görevi görüyor.

GitHub Copilot'un gücü, OpenAI ile entegrasyonunda yatıyor ve bağlamsal olarak alakalı ve pratik öneriler sunmak için geniş bir açık kaynak kod havuzundan yararlanıyor. Bu sadece kodlama hızını artırmakla kalmaz, aynı zamanda sizi çeşitli kodlama modellerine ve en iyi uygulamalara maruz bırakarak değerli bir öğrenme aracı olarak da hizmet eder.

Bu ücretsiz bir araç değildir. Bir abonelik size bireysel olarak ayda 10 dolara mal olabilir veya ekipler için indirimli bir fiyattan satın alınabilir. GitHub Copilot'u denemek isterseniz, şu anda 30 günlük bir deneme teklifi var.

!https://www.freecodecamp.org/news/content/images/2024/01/212964557-8d832278-61bb-4288-a8a7-47f35859e868.gif

Bir fonksiyon üzerinde akıllı otomatik tamamlama kullanan GitHub Copilot.

Ayrıca [buradan daha fazlasını okuyabileceğiniz] (https://www.freecodecamp.org/news/ai-tools-to-use-in-vs-code/) bazı ücretsiz alternatifler de var (ve aşağıda Tabnine'den de bahsediyorum).

# **Icon Themes**

VSCode varsayılan simgeler içerse de, simge paketlerini kullanmak üretkenliği artırmak ve düzenleyiciye görsel olarak çekici bir estetik katmak için mükemmel bir yol sağlar.

Simge paketleri, varsayılanlara kıyasla daha kapsamlı ve görsel olarak tanınabilir bir simge seti sağlar. Bu, dosya türleri ve klasörler arasındaki görsel ayrımı kolaylaştırabilir. Sezgisel tanıma oluşturabilir ve dosyalar arasında gezinirken bilişsel yükü azaltabilir.

Bir simge paketi seçmek söz konusu olduğunda pek çok seçenek vardır. Üç popüler seçenek [Material Theme Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme-icons), [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) ve [file-icons](https://marketplace.visualstudio.com/items?itemName=file-icons.file-icons).

İyi bir simge setinin dosya gezgininin genel okunabilirliğini artırdığını düşünüyorum. Geliştirilmiş görsel deneyimin ek faydalarından keyif alıyorum.

!https://www.freecodecamp.org/news/content/images/2024/01/Group-2.png

vscode-ikonları (solda) ve Materyal Simge Teması (sağda) etkinken editörümün yan yana karşılaştırması. Dosya türleri ve klasörler için ne içerdiklerini gösteren simgeler var.
