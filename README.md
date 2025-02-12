# Weather App

Bu proje, **Weather App**, kullanıcıların istedikleri şehirlerin hava durumu bilgilerini öğrenebileceği bir uygulamadır. Uygulama, şehir adı girilerek anlık hava durumu, sıcaklık, nem oranı ve rüzgar hızı gibi bilgileri gösterir. OpenWeather API'si kullanılarak hava durumu verileri alınır ve kullanıcı arayüzü, JavaScript, HTML ve CSS ile oluşturulmuştur.

## Proje Ekran Görüntüleri

### Web Görünümü
Aşağıda web versiyonunun görünümü yer almaktadır.  
![image](https://github.com/user-attachments/assets/e5601d4c-dc49-42a4-b1ba-3fbe3b6a0158)


## Kullanılan Teknolojiler

Bu projede kullanılan ana teknolojiler:

- **HTML5**: Sayfa yapısı ve içerik düzeni
- **CSS3**: Tasarım ve stil
- **JavaScript**: Dinamik özellikler ve etkileşim
- **OpenWeather API**: Hava durumu verisi almak için API kullanımı

## Derinlemesine Öğrendiğim Konular

Bu projede geliştirdiğim bazı teknikler ve pekiştirdiğim konular şunlardır:

### 1. **HTML5 ve Sayfa Yapısı**
- **HTML5** kullanarak, sayfa yapısını oluşturmayı ve temel HTML elemanlarıyla etkileşimde bulunmayı pekiştirdim. Uygulama arayüzünde input, butonlar ve görseller gibi HTML öğeleri kullanarak etkili bir yapı kurdum.

### 2. **CSS ile Görsel Tasarım**
- **CSS Flexbox** ve **CSS Animasyonları** kullanarak, hava durumu kutularını yerleştirdim ve dinamik görseller ekledim. Sayfa elementlerinin düzenini sağlarken, kullanıcı dostu bir arayüz oluşturdum.

### 3. **JavaScript ile Dinamik Özellikler**
- **JavaScript** kullanarak, kullanıcının girdiği şehir adına göre hava durumu verilerini çekip sayfada güncellenmesini sağladım. Ayrıca, API'den alınan verilere göre dinamik olarak hava durumu simgeleri ve verilerini gösterdim.

### 4. **Olay Dinleyicileri (Event Listeners)**
- Kullanıcının "arama" butonuna tıklamasıyla, hava durumu sorgulamasını gerçekleştirecek şekilde **event listeners** ekledim. Bu sayede, butona tıklama ile veri alındı ve görsel güncellemeler yapıldı.

## Öğrendiğim Konular

Bu projeyi geliştirirken öğrendiğim konular:

### 1. **Fetch API ile Veri Çekme**
- **fetch()** fonksiyonu ile dış bir API'den veri çekmeyi öğrendim. OpenWeather API'den JSON formatında hava durumu verilerini alarak, bu veriyi uygulamaya entegre ettim.

### 2. **API Entegrasyonu**
- **OpenWeather API** entegrasyonu ile, dış bir kaynaktan hava durumu verisi çekmenin nasıl yapılacağını öğrendim. API'den alınan şehir verilerine göre, hava durumu simgeleri, sıcaklık, nem oranı ve rüzgar hızını dinamik olarak güncelledim.

### 3. **Hata Yönetimi ve Kullanıcı Bilgilendirme**
- API'den gelen hata mesajlarıyla, geçersiz şehir isimleri için hata mesajları gösterilmeyi sağladım. Hava durumu bulunamadığında, kullanıcıya 404 hata mesajı sunan bir hata yönetimi ekledim.

### 4. **CSS Animasyonları**
- Sayfa yüklendikçe hava durumu kutularının **fade-in** animasyonuyla görünür hale gelmesini sağladım. Kullanıcı deneyimini iyileştirmek için görsel geçişler ekledim.

### 5. **Responsive Tasarım**
- Tasarımın farklı ekran boyutlarına uyum sağlamasını sağlamak için **responsive design** prensiplerini kullandım. Kullanıcıların farklı cihazlarda da rahatlıkla kullanabilmesi için ekran düzenlemelerini optimize ettim.
