# ORİTEQ BC410 PRO — Siber Güvenlik Laboratuvar Föyleri

**Safety 4.0 Bootcamp** kapsamında hazırlanan, bir **kutu kapama (koli bantlama) makinesi** üzerinden işlenen ilk 5 laboratuvar föyü.

- **Örnek makine (vaka):** Orimak Makina — **ORİTEQ BC410 PRO** Kutu Kapama Makinesi
- **Çerçeve:** İzinli / **varsayımsal** lab senaryosu — makine yalnızca eğitim amaçlı bir vaka incelemesi olarak kullanılmıştır
- **Yaklaşım:** Savunma (koruyucu mühendislik) perspektifi — IEC 62443, fonksiyonel emniyet, risk değerlendirme ve yama yönetimi *metodolojisi*
- **Hazırlayan:** Beyda Kızıldağ — Gündüz 4B — 23/10/2026

---

## Föyler

| # | Lab | Çıktı |
|---|-----|-------|
| 1 | **Safety Architecture** | Safety Function Map |
| 2 | **IEC 62443 Mini Workshop** | Zone / Conduit Diagram |
| 3 | **Threat & Risk + Risk Matrix** | Risk Register |
| 4 | **Secure Remote Access** | Secure Architecture |
| 5 | **SBOM / CVE / Patch** | Vulnerability Decision |

Her föy; bir **Kavram** özeti, makineye özel şema/varlık listesi, numaralı **Görev** soruları ve örnek cevaplar (mavi) içerir.

**Ek — SWOT Analizi:** Makinenin siber güvenlik duruşu dört pencerede özetlenir — Güçlü Yönler (S), Zayıf Yönler (W), Fırsatlar (O), Tehditler (T).

## Canlı Föyler

🔗 **https://beyda-kizildag.github.io/yazilim-muhendisligi-guncel-konular-beyda-kizildag/**

(GitHub Pages ile yayınlanır — indirmeden tarayıcıda açılır.)

## Görüntüleme

- `index.html` dosyasını bir tarayıcıda aç — beş föy tek sayfada, A4 baskıya uygun.
- Baskı/PDF için tarayıcıdan **Yazdır → PDF olarak kaydet** yeterli.
- İstenirse GitHub Pages ile de yayınlanabilir (Settings → Pages → `main` / root).

## İçerik Notları

- **Lab 3** senaryoları *kategori düzeyinde, varsayımsal tehlike tanımlarıdır* — saldırı yöntemi/adımı içermez. Amaç, `kim → kapı → zincir → fiziksel sonuç` kalıbıyla senaryoları **puanlayıp önceliklendirmektir** (L × S × E, her biri 1–3).
- **Lab 5**'teki zafiyet kaydı (`Component X`, `CVE-XXXX-XXXX`) bilinçli olarak **placeholder**'dır; gerçek bir ürüne atfedilmiş bir açık değildir.

---

## ⚠️ Uyarı

Bu föyler bir **eğitim çıktısıdır**; resmî denetim, uygunluk değerlendirmesi veya belgelendirme **değildir** ve CE / mevzuat uygunluğu garantisi vermez. Örnek makine, üreticiyle bağlantılı gerçek bir güvenlik değerlendirmesi kapsamında **incelenmemiştir**; üretici tarafından sağlanan/onaylanan bir bilgi içermez. Herhangi bir gerçek sistemde yetkisiz güvenlik testi yapılmasını önermez.
