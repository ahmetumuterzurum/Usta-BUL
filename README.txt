USTA BUL - Supabase bağlantılı başlangıç sürümü

Bu sürüm, Usta ol formunu Supabase projesindeki public.usta_basvurulari tablosuna gönderir.
Tarayıcıda yalnızca Supabase publishable anahtarı kullanılır. Secret/service_role anahtarını asla web sayfasına koymayın.

Önemli:
- Tablo adı: usta_basvurulari
- Gönderilen alanlar: ad_soyad, telefon, kategori, sehir, ilce, aciklama
- durum ve created_at alanları veritabanı varsayılanlarıyla doldurulur.
- RLS INSERT politikası anon rolüne izin vermelidir; SELECT izni vermek zorunda değilsiniz.
- Bu sürüm başvuruları toplar. Henüz üyelik, doğrulama, yönetici paneli, ödeme veya onaylı usta listeleme sistemi değildir.
- Canlıya almadan önce spam koruması, telefon doğrulaması, gizlilik metni ve yönetici onay akışı eklenmelidir.
