# Blockchain Tabanlı Elektronik Oylama Sistemi

Merhaba! Biz, güvenli, şeffaf ve modern bir oylama deneyimi sunmayı amaçlayan bir ekibiz. Geliştirilen bu proje, blockchain teknolojisi ile desteklenmiş bir **elektronik oylama sistemi**dir.

## Proje Hakkında

Bu sistem, oyların güvenli bir şekilde kaydedilmesini ve oylama işlemi tamamlandıktan sonra doğrulanabilir olmasını sağlar. Blockchain teknolojisi sayesinde her oy değiştirilemez şekilde kayıt altına alınır ve gerektiğinde bağımsız denetçilere veya kullanıcıya şeffaflık sunar. Projemiz, oy süreçlerinin dijitalleştirilmesi yoluyla, geleneksel sistemlerin yavaşlığına ve manipülasyona açık yapısına çözüm sunar.

## Ana Repo

Kodlarımız, `i-vote-app` isimli private repository'de barındırılmaktadır.

## Teknik Detaylar

- **Backend**: Node.js & PostgreSQL
- **Altyapı (Infra)**:  
  - AWS üzerinde:
    - RDS (veritabanı)
    - ALB (Application Load Balancer)
    - ECS + EC2 (container orkestrasyonu)
  - Terraform ile altyapı kod olarak yönetiliyor (IaC)
- **CI/CD**:  
  - `.github/workflows` altında yapılandırılmış GitHub Actions pipeline’ları ile sürekli entegrasyon ve dağıtım (CI/CD) süreçleri

## Hedeflerimiz

- Seçim süreçlerine dijital güven kazandırmak  
- Blockchain ile şeffaf, değiştirilemez bir kayıt sistemi sunmak  
- Kullanıcı dostu, hızlı ve erişilebilir bir oylama platformu geliştirmek

## Katkı Sağlayanlar

- [Eren Kara](https://github.com/EreenKara)
- [Ali Eren Yiğit](https://github.com/AliErenYigit)
- [Vedat Öztürk](https://github.com/OzturkVedat)
- [Samed Değer](https://github.com/BuYKMan)

---

> Daha fazla bilgi almak için bizimle iletişime geçebilirsiniz: [meas.kydo@gmail.com](mailto:meas.kydo@gmail.com)
