Proje: Plantis Flutter TodoList Uygulaması
Bu proje, kullanıcıların görevlerini yönetmelerine yardımcı olan bir Flutter uygulamasıdır. Uygulama, kullanıcıların yeni görevler eklemelerine, mevcut görevleri görüntülemelerine ve yönetmelerine olanak tanır. Ayrıca, kullanıcıların giriş yapabileceği ve yeni hesap oluşturabileceği ekranlar da mevcuttur.

Özellikler
Ana Sayfa (HomePage): Uygulamanın ana sayfasıdır. Kullanıcılar buradan mevcut görevlerini görüntüleyebilirler.
Yeni Görev Ekleme (newTodoScreen): Kullanıcılar yeni görevler ekleyebilir, görev başlığı, açıklaması, tarihi ve önceliğini belirleyebilirler.
Giriş Yapma (SigninScreen): Kullanıcılar mevcut hesaplarıyla uygulamaya giriş yapabilirler.
Kayıt Olma (SignUpScreen): Yeni kullanıcılar hesap oluşturabilirler.
Görev Detayları (TodoScreen): Kullanıcılar görevlerin detaylarını görüntüleyebilir ve yönetebilirler.

Dosyalar


HomePage.dart
Ana sayfa ekranı. Kullanıcıların mevcut görevlerini görüntülediği ekrandır.
class HomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // Kod içeriği
  }
}


newTodoScreen.dart
Yeni görev ekleme ekranı. Kullanıcıların yeni bir görev oluşturabileceği ekrandır.
class NewTodoScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // Kod içeriği
  }
}


SigninScreen.dart
Kullanıcı giriş ekranı. Kullanıcıların mevcut hesaplarıyla giriş yapabileceği ekrandır.
class SigninScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // Kod içeriği
  }
}


SignUpScreen.dart
Yeni kullanıcı kayıt ekranı. Kullanıcıların yeni bir hesap oluşturabileceği ekrandır.
class SignUpScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // Kod içeriği
  }
}


TodoScreen.dart
Görev detayları ekranı. Kullanıcıların belirli bir görevi görüntüleyip yönetebileceği ekrandır.
class TodoScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // Kod içeriği
  }
}


Kurulum
Projeyi kendi makinenizde çalıştırmak için aşağıdaki adımları takip edin:

Depoyu klonlayın:
git clone https://github.com/CanCengiz1/flutter-task-manager.git

flutter-task-manager
Gerekli bağımlılıkları yükleyin, gerekli dependenciesler; 
get: ^4.6.6
  firebase_core: ^2.31.1
  firebase_auth: ^4.19.6
  firebase_storage: ^11.7.6
  cloud_firestore: ^4.17.4
  flutter_slidable: ^3.1.0
  image_picker: ^1.1.1
  flutter_local_notifications: ^17.1.2
  local_auth: ^2.2.0
  provider: ^6.1.2
  uuid: ^4.4.0
  flutter_datetime_picker_plus: ^2.2.0 

  bazı dependenciesler güncellenmediği için elle güncellemek adına dependency_overrides ve sürümleri;
  eak_tracker: ^10.0.5
  leak_tracker_flutter_testing: ^3.0.5
  material_color_utilities: ^0.11.1
  meta: ^1.15.0
  test_api: ^0.7.1
  vm_service: ^14.2.2
  


flutter pub get


Uygulamayı çalıştırın:
flutter run


Katkıda Bulunma
Her türlü katkı memnuniyetle karşılanır!
