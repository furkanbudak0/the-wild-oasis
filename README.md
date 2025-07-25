# The Wild Oasis

Bu proje, modern bir otel/yazlık rezervasyon ve yönetim uygulamasıdır. React ve Vite ile geliştirilmiş, kullanıcı dostu bir arayüze ve güçlü yönetim özelliklerine sahiptir.

## Özellikler

- Kullanıcı girişi ve kayıt (authentication)
- Rezervasyon oluşturma, görüntüleme ve silme
- Kabin (oda) ekleme, düzenleme ve silme
- Dashboard ile istatistikler ve analizler
- Karanlık/aydınlık tema desteği
- Modern ve responsive tasarım

## Kullanılan Teknolojiler

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Supabase](https://supabase.com/) (Backend ve Auth için)
- [Styled Components](https://styled-components.com/) (Stil yönetimi için)

## Klasör Yapısı (Özet)

```
final/
├── public/           # Statik dosyalar
├── src/
│   ├── features/     # Uygulama modülleri (auth, bookings, cabins, vs.)
│   ├── pages/        # Sayfa bileşenleri
│   ├── services/     # API ve yardımcı servisler
│   ├── ui/           # Ortak arayüz bileşenleri
│   └── ...
├── package.json      # Proje bağımlılıkları
└── ...
```
