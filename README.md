# Titanic-Survival

Titanic Yolcu Verileri Analizi
Bu proje, ünlü Titanic gemisindeki yolcuların verilerini kullanarak hayatta kalma olasılıklarını tahmin etmektedir. Veri seti, Kaggle'da bulunan Titanic: Machine Learning from Disaster yarışması için hazırlanmıştır.

Veri Seti
Veri seti, 891 satır ve 12 öznitelikten oluşmaktadır. Öznitelikler şöyledir:

PassengerId: Yolcu numarası
Survived: Hayatta kalma durumu (0: Öldü, 1: Hayatta kaldı)
Pclass: Bilet sınıfı (1: 1. sınıf, 2: 2. sınıf, 3: 3. sınıf)
Name: Yolcunun adı
Sex: Yolcunun cinsiyeti
Age: Yolcunun yaşı
SibSp: Yolcunun kardeş/eş sayısı
Parch: Yolcunun ebeveyn/çocuk sayısı
Ticket: Bilet numarası
Fare: Bilet fiyatı
Cabin: Kabin numarası
Embarked: Liman (C: Cherbourg, Q: Queenstown, S: Southampton)
Proje Aşamaları
Bu projede, aşağıdaki adımlar takip edilmiştir:

Veri setinin yüklenmesi ve incelenmesi
Veri ön işleme adımları: eksik verilerin doldurulması, kategorik verilerin sayısallaştırılması, özellik seçimi
Eğitim ve test verilerinin hazırlanması
Random Forest sınıflandırma algoritmasının kullanılması
Modelin performansının ölçülmesi ve geliştirilmesi
Yeni bir yolcunun hayatta kalma olasılığının tahmin edilmesi
Kurulum
Bu projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

Bu repository'yi kendi bilgisayarınıza klonlayın.

Projenin bağımlılıklarını yüklemek için aşağıdaki komutu terminalde çalıştırın:

basic
Copy
pip install -r requirements.txt
Jupyter Notebook veya benzeri bir araçla titanic_survival_prediction.ipynb dosyasını açın.

Notebook'u sırayla çalıştırın.

Katkıda Bulunma
Bu proje açık kaynaklıdır ve herkese açıktır. Herhangi bir hata veya öneri için issues sayfasına başvurabilir veya doğrudan bir pull request gönderebilirsiniz.
