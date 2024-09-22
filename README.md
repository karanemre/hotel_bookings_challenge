# Otel Rezervasyon Verileri Analizi

Bu proje, otel rezervasyon verilerini analiz etmek ve farklı kriterlere göre değerlendirmek amacıyla oluşturulmuştur. Aşağıda veri setindeki sütunların açıklamaları bulunmaktadır.

## Sütunlar

| Sütun Adı                             | Açıklama                                                                                 |
|---------------------------------------|------------------------------------------------------------------------------------------|
| `hotel`                               | Otel ismi veya türü                                                                     |
| `is_canceled`                         | Rezervasyonun iptal edilip edilmediğini gösterir (0: iptal edilmedi, 1: iptal edildi)  |
| `lead_time`                           | Rezervasyonun yapıldığı tarihle otelin rezervasyon tarihleri arasındaki gün sayısı     |
| `arrival_date_year`                  | Müşterinin otele geldiği yıl                                                             |
| `arrival_date_month`                 | Müşterinin otele geldiği ay (metin formatında)                                          |
| `arrival_date_week_number`           | Müşterinin otele geldiği haftanın numarası                                               |
| `arrival_date_day_of_month`          | Müşterinin otele geldiği ayın günü                                                      |
| `stays_in_weekend_nights`            | Müşterinin kaldığı hafta sonu geceleri sayısı                                            |
| `stays_in_week_nights`               | Müşterinin kaldığı hafta içi geceleri sayısı                                             |
| `adults`                              | Rezervasyona dahil olan yetişkin sayısı                                                  |
| `children`                            | Rezervasyona dahil olan çocuk sayısı                                                    |
| `babies`                              | Rezervasyona dahil olan bebek sayısı                                                    |
| `text_formatmeal`                    | Müşterinin seçtiği yemek planı (metin formatında)                                       |
| `text_formatcountry`                 | Müşterinin geldiği ülke (metin formatında)                                              |
| `text_formatmarket_segment`          | Rezervasyonun yapıldığı pazar segmenti (örneğin, bireysel, grup vb.)                    |
| `text_formatdistribution_channel`     | Rezervasyonun yapıldığı dağıtım kanalı (örneğin, doğrudan, çevrimiçi ajans)            |
| `is_repeated_guest`                  | Müşterinin daha önce otelde kalıp kalmadığını gösterir (0: hayır, 1: evet)             |
| `previous_cancellations`             | Müşterinin geçmişte yaptığı iptallerin sayısı                                            |
| `previous_bookings_not_canceled`    | Müşterinin geçmişte yaptığı iptallerin sayısı dışındaki rezervasyonlar                   |
| `text_formatreserved_room_type`      | Müşterinin rezervasyon yaptığı oda türü (metin formatında)                              |
| `text_formatassigned_room_type`      | Müşteriye atanan oda türü (metin formatında)                                           |
| `booking_changes`                    | Rezervasyon üzerinde yapılan değişiklik sayısı                                            |
| `text_formatdeposit_type`            | Müşterinin yaptığı depozito türü (örneğin, ön ödeme, garanti)                          |
| `text_formatagent`                   | Rezervasyonu yapan acente veya aracının ismi                                           |
| `text_formatcompany`                 | Rezervasyonu yapan şirketin ismi (varsa)                                               |
| `days_in_waiting_list`               | Müşterinin bekleme listesinde geçirdiği gün sayısı                                      |
| `text_formatcustomer_type`           | Müşteri tipi (örneğin, bireysel, şirket)                                                |
| `adr`                                 | Ortalama günlük gelir (Average Daily Rate)                                               |
| `required_car_parking_spaces`        | Gerekli araç park yeri sayısı                                                            |
| `total_of_special_requests`           | Müşterinin yaptığı özel taleplerin toplam sayısı                                         |
| `text_formatreservation_status`      | Rezervasyonun durumu (örneğin, onaylı, iptal)                                          |
| `calendar_todayreservation_status_date` | Rezervasyon durumu gününün tarihi                                                       |

## Proje Amacı

Bu proje, otel rezervasyon verilerini analiz ederek, iptallerin nedenlerini, müşteri davranışlarını ve otel performansını değerlendirmeyi amaçlamaktadır. Veriler, istatistiksel analiz ve görselleştirmeler ile desteklenecektir.
# Power BI Dashboard Projesi

Bu proje, Power BI kullanarak otel rezervasyon verilerini analiz etmek ve görselleştirmek amacıyla hazırlanmıştır. Aşağıda oluşturulan dashboardların ana başlıkları ve içerikleri yer almaktadır.

## Dashboardlar

### 1. Genel Bakış
- **Açıklama**: Tüm rezervasyon verilerinin genel bir görünümünü sunar. 
- **Öne Çıkan Veriler**:
  - Toplam rezervasyon sayısı
  - İptal oranları
  - Müşteri dağılımı

### 2. Müşteri Edinme Analizi
- **Açıklama**: Yeni müşterilerin kazanılması sürecini ve etkililiğini analiz eder.
- **Öne Çıkan Veriler**:
  - Müşteri edinme kaynakları
  - Segment bazında yeni müşteri sayıları
  - Müşteri edinme maliyeti

### 3. Müşteri Elde Tutma Analizi
- **Açıklama**: Mevcut müşterilerin elde tutulma oranlarını ve nedenlerini inceler.
- **Öne Çıkan Veriler**:
  - Müşteri sadakat oranları
  - İptal eden müşterilerin analizi
  - Tekrar eden müşteri oranları

### 4. Gelir Analizi
- **Açıklama**: Otelin toplam gelirlerini ve bu gelirlerin nasıl oluştuğunu gösterir.
- **Öne Çıkan Veriler**:
  - Aylık ve yıllık gelir trendleri
  - Oda türlerine göre gelir dağılımı
  - Özel taleplerin gelir üzerindeki etkisi

## Kullanım

Dashboardlar, kullanıcıların otel rezervasyon verilerini daha iyi anlamalarına ve stratejik kararlar almalarına yardımcı olmak için tasarlanmıştır. Power BI Desktop veya Power BI Service kullanarak bu dashboardları görüntüleyebilir ve etkileşimde bulunabilirsiniz.

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, pull request oluşturarak değişikliklerinizi gönderebilirsiniz.
