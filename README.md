Kütüphane Uygulaması - Frontend
Bu proje, Patika+ Frontend Web Developer Programı capstone bitirme projesi kapsamında geliştirilmiş bir Kütüphane Yönetim Uygulamasının frontend kısmını içermektedir. Uygulama, React Router kullanılarak geliştirilmiş ve CRUD işlemleri uygulanabilir hale getirilmiştir.

Özellikler
Giriş Sayfası (Karşılama Sayfası): Uygulama girişinde karşılama sayfası bulunmaktadır.
Yayımcı, Kategori, Kitap, Yazar Sayfaları: Bu sayfalarda CRUD işlemleri (Ekleme, Silme, Güncelleme, Okuma) yapılabilir.
Kitap Alma Sayfası: Kullanıcılar kitapları alabilir ve bu işlem de CRUD operasyonlarıyla yapılabilir.
Veri Manipülasyonu: Her sayfa üzerinde 5 adet veri eklenmiş olup, CRUD işlemleri her sayfa üzerinde denenecektir.
Kullanıcı Bilgilendirme: CRUD işlemleri başarılı ya da başarısız olduğunda kullanıcıya bildirim yapılır.
Tasarım: 1200px genişliğinde ve responsive tasarım uygulanmamıştır. Kullanıcı tasarımı dilediği gibi yapabilir.
Backend Entegrasyonu: Proje, backend ve database ile çalışacak şekilde tasarlanmış olup, gerekli API entegrasyonu yapılmıştır.
Kullanılan Teknolojiler
React: Uygulamanın temel frontend framework'ü.
React Router: SPA (Single Page Application) için yönlendirme işlemleri.
CSS/Material/Bootstrap: Kullanıcı arayüzü için stil seçimleri.
Axios: Backend API'leri ile iletişim için HTTP istemcisi.
Backend API: Canlı veritabanı ve backend ile çalışmaktadır.
Proje Kurulumu
Bu projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Depoyu Klonlayın
bash
Kopyala
Düzenle
git clone <repository-url>
cd <repository-directory>
2. Bağımlılıkları Yükleyin
Proje dizininde aşağıdaki komutu çalıştırarak gerekli npm paketlerini yükleyin:

bash
Kopyala
Düzenle
npm install
3. Uygulamayı Başlatın
Projeyi başlatmak için şu komutu kullanın:

bash
Kopyala
Düzenle
npm run dev
Bu komut uygulamayı geliştirme modunda başlatacak ve tarayıcınızda http://localhost:3000 adresinden erişebilirsiniz.

Kullanıcı İşlemleri
Kullanıcı, aşağıdaki işlemleri gerçekleştirebilir:

1. Yayımcı, Kategori, Kitap, Yazar Sayfalarındaki CRUD İşlemleri:
Okuma: Veritabanından mevcut veriler görüntülenebilir.
Ekleme: Yeni bir öğe (Yayımcı, Kategori, Kitap, Yazar) eklenebilir.
Güncelleme: Mevcut bir öğe güncellenebilir.
Silme: Bir öğe silinebilir.
2. Kitap Alma Sayfası:
Kitaplar listelenebilir.
Kullanıcılar kitap alabilir.
Proje Canlı Linki
Projenizin canlı sürümüne şu linkten ulaşabilirsiniz:

https://libraryappmain.netlify.app/

Katkıda Bulunma
