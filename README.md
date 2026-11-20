# PDF Ara: OCR Destekli PDF Arama

PDF dosyalarında metin arayan masaüstü araç. Dijital PDF'lerde gömülü metin katmanını kullanır. **Taranmış veya görüntü tabanlı PDF'lerde ise otomatik olarak OCR'a geçer.**

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Özellikler

- Aynı komutla hem dijital hem taranmış PDF'lerde arama
- Her sayfa için hangi kaynağın kullanıldığını gösterir (`metin` / `ocr`)
- **Türkçeye uygun harf duyarsız arama.** Python'un standart `IGNORECASE` seçeneği `İ/I/ı/i` harflerinde hatalı sonuç verir, bu araç bunu düzeltir.
- Düzenli ifade (regex) desteği
- Sayfa aralığı seçimi (`1-3,5,8-10`)
- Eşleşmeleri PDF üzerinde sarıyla işaretleyip yeni dosya olarak kaydetme
- Alt klasörler dahil toplu tarama, JSON dışa aktarma
- Komut satırı ve grafik arayüz aynı motoru kullanır
- **Tek dosyalık Windows kurulum paketi** (Inno Setup). Hedef bilgisayarda Python gerekmez.

## Teknolojiler

`Python` · `PyMuPDF` · `Tesseract OCR` · `Tkinter` · `PyInstaller` · `Inno Setup`
