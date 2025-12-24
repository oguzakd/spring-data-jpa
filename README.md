# 🚀 SPRING DATA JPA MASTERY
### *Data Access Layer & Enterprise Architecture Study*

---

## 🛠 TEKNOLOJİ YIĞINI (TECH STACK)

* **Dil:** `Java 17`
* **Framework:** `Spring Boot 3.5.6`
* **Veritabanı:** `PostgreSQL`
* **ORM & Veri:** `Spring Data JPA` & `Hibernate`
* **Yardımcı Araçlar:** `Lombok`, `Spring Boot Validation`

---

## 📌 UYGULANAN TEMEL KONULAR

### 🔹 1. Veri Modelleme ve İlişkisel Mantık
* **Entity Mapping:** Veritabanı tablolarının JPA standartlarında haritalanması.
* **İlişki Yönetimi:** `@OneToMany`, `@ManyToOne` ve `@ManyToMany` yapılarının kurulması.
* **Fetch Stratejileri:** Performans odaklı veri çekme operasyonları.

### 🔹 2. Gelişmiş Sorgulama Kabiliyetleri
* **Derived Queries:** Metot isimlerinden otomatik SQL üretimi.
* **Custom JPQL & Native Queries:** `@Query` anotasyonu ile özel iş mantığı sorguları.
* **Pagination & Sorting:** Büyük verilerin sayfalanarak ve sıralanarak yönetilmesi.

### 🔹 3. Veri Güvenliği ve Validasyon
* **Bean Validation:** Katmanlar arası veri doğruluğunun `@NotNull`, `@Size` gibi anotasyonlarla sağlanması.
* **Boilerplate Kod Yönetimi:** `Lombok` ile temiz ve okunabilir kod yapısı.

---

## ⚙️ KURULUM VE YAPILANDIRMA

1️⃣ **Veritabanı Ayarları:**
`src/main/resources/application.properties` dosyasında PostgreSQL bağlantı bilgilerini tanımlayın:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/veritabani_adiniz
spring.datasource.username=postgres
spring.datasource.password=sifreniz

2️⃣ Projeyi Çalıştırma:
mvn clean install
mvn spring-boot:run
