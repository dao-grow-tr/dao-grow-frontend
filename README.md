# dao.grow - Tarımsal Otomasyon Sistemi

dao.grow, blockchain teknolojisi ve NFT'leri kullanarak modern tarım uygulamalarını destekleyen yenilikçi bir platformdur. Bu platform, tarımsal bilgi paylaşımını ve tarımsal NFT'lerin alım-satımını kolaylaştırmayı amaçlamaktadır.

## 🚀 Özellikler

- **Tarımsal NFT Pazar Yeri**: Tarım bilgilerinizi NFT olarak paylaşın ve değer yaratın
- **Reçete Oluşturma**: Özel tarım reçetelerini NFT olarak oluşturun
- **Pazar Yeri**: Tarımsal NFT'lerin alım-satımı için güvenli platform

## 🛠 Teknolojiler

- PHP 8.3
- Nginx
- Docker
- Blockchain Entegrasyonu
- NFT Teknolojisi

## 📋 Gereksinimler

- Docker
- Docker Compose
- Git

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone [repo-url]
cd daogrow-frontend
```

2. Docker container'larını başlatın:
```bash
docker-compose up -d
```

3. Tarayıcınızda aşağıdaki adresi açın:
```
http://localhost:9093
```

## 📁 Proje Yapısı

```
.
├── app/
│   ├── css/          # Stil dosyaları
│   ├── js/           # JavaScript dosyaları
│   ├── img/          # Görseller
│   ├── partials/     # PHP parçaları
│   ├── index.php     # Ana sayfa
│   ├── about.php     # Hakkında sayfası
│   ├── governance.php # Yönetişim sayfası
│   ├── marketplace.php # Pazar yeri
│   └── create-recipe.php # Reçete oluşturma
├── docker-compose.yml
└── nginx.conf
```

## 🔧 Geliştirme

Projeyi geliştirmek için:

1. Docker container'larını başlatın
2. `app` klasöründeki dosyaları düzenleyin
3. Değişiklikler otomatik olarak yansıyacaktır


## 🤝 Katkıda Bulunma

1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun

