# PetStore_API_Test_CRUD

# About 

This project uses Rest-Assured API to test the following API - https://petstore.swagger.io/#/pet

The below tests are created to demonstrate

1. Create a new pet using POST method and verifying if the created pet is in line with the supplied details
2. Retrieve the pet details using petID through GET method
3. Update the pet name using POST method
4. Delete the pet details using DELETE method

5. For Negative Scenario Retrieve pet from petStore with invalid ID
6. For Negative Scenario Delete pet from petStore with invalid ID

# Hakkında
Bu projede, aşağıdaki API'yi test etmek için Rest-Assured API kullanıldı.
 - https://petstore.swagger.io/#/pet

Aşağıdaki testler oluşturuldu.
1. POST yöntemini kullanarak ve oluşturulan evcil hayvanın sağlanan ayrıntılarla uyumlu olup olmadığını doğrulayarak yeni bir evcil hayvan oluşturuldu.
2. GET yöntemiyle petID kullanarak evcil hayvan ayrıntılarını alındı.
3. POST yöntemini kullanarak evcil hayvan adı güncellendi.
4. DELETE yöntemini kullanarak evcil hayvan ayrıntılarını silindi.
5. Olumsuz Senaryo için geçersiz bir petID ile GET yöntemini  kullanarak evcil hayvan ayrıntılarını alınmaya çalışıldı.
6. Olumsuz Senaryo için geçersiz bir petID ile DELETE yöntemini kullanarak evcil hayvan ayrıntılarını silinmeye çalışıldı.

### Gerekli Yazılım ve Araçlar

Bu kod IntelliJ IDEA IDE'sinde hazırlanmıştır.
Ayrıca kullanılan dil JAVA 8 ve üzeridir.
Maven 11 Build tool kullanılmıştır.

### Programın yüklenmesi

Githup ta açılan program sayfasında yeşil renkteki code bölümünden HTTPS kopyalanır.
IntelliJ programında
File<New<Project from Version Control seçilir. Açılan sayfada URL kısmına kopyalanan HTTPS yapıştırılır.
Clone düğmesine basılarak proje IntelliJ programına yüklenir.
Proje yüklendikten sonra açılan sayfada en sağ köşede bulunan maven sekmesinden Download Sources and/or Documents (Altı çizili Aşağı Ok simgesi) basılarak güncellemeler indirilir.


## Testin Çalıştırılması

Projenin çalıştırılıp HTML raporu oluşturulması için yine en sağ köşede bulunan Maven sekmesinden 
Lifecycle<clean seçilir.
Takiben
Lifecycle<install seçilir.
Son olarak
Lifecycle<verify seçilerek proje çalıştırılır.
Proje tamamlandıktan sonra en sol köşede bulunan Project sekmesinin altında
PetStore_API_Test_CRUD<target<cucumber-html-repots<overview-features.html bölümüne sağ tık yapılarak Open In < Browsers < Chrome (Firefox, Safari,..) seçilir. 
Browser da HTML olarak projenin screnshotları dahil tüm görünümü rapor halinde yer almaktadır.


Rapor almadan projeyi çalıştırmak için en sol köşede bulunan Project sekmesinin altında
PetStore_API_Test_CRUD<src<test<java<com.PetStore<runners<CukesRunner sayfası ana ekranda açılır. 
Açılan sayfada public class ın yanında yer alan yeşil run kısmına basılarak program çalıştırılır.

Test senoryaları PetStore_API_Test_CRUD<src<test<resources<features<petStore.feature ayrıntılı görülebilir.


## Authors

* **Mustafa Özartan** - *Initial work* - [mozartan](https://github.com/mozartan)
