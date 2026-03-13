# Umay Uslu — Ben Geldim

Dünyaya gelen Umay bebek için doğum davetiyesi.

## Davetiyeyi düzenlemek

`index.html` dosyasının **en üstündeki** `<script>` bloğunda şu üç değeri kendi bilgilerinizle değiştirin:

- **hospitalMapsQuery**: Hastane adresi (Haritalar’da aranacak metin). Örn: `"Özel ABC Hastanesi, Kadıköy, İstanbul"`
- **anneWhatsApp**: Annenin WhatsApp numarası, sadece rakam. Örn: `"905321234567"` (0 yerine 90, başında + yok)
- **babaWhatsApp**: Babanın WhatsApp numarası, aynı formatta. Örn: `"905551234567"`

## Linki almak (GitHub Pages)

1. Bu klasörde terminal açın.
2. `git init`
3. `git add index.html README.md`
4. `git commit -m "Umay doğum davetiyesi"`
5. GitHub’da https://github.com/06mehmetari-lgtm/umaybebek repo’suna gidin, “upload files” veya mevcut repoya bağlanın:
   - `git remote add origin https://github.com/06mehmetari-lgtm/umaybebek.git`
   - `git branch -M main`
   - `git push -u origin main`
6. Repo ayarlarından **Settings → Pages → Source: Deploy from branch** → branch: **main**, folder: **/ (root)** → Save.
7. Birkaç dakika sonra davetiyenizin linki: **https://06mehmetari-lgtm.github.io/umaybebek/** olacak. Bu linki paylaşabilirsiniz.

Telefonda bu linke tıklayan herkes davetiyeyi görür; Hastane butonu Haritalar’ı, Anne/Baba butonları WhatsApp’ı açar.
