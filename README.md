# Prism Aurora

**Prism Crew** tarafından hazırlanan, kuzey ışıklarından ve derin okyanus tonlarından ilham alan koyu VS Code teması.

> **Beyond The Spectrum.**

## Öne çıkanlar

- Derin okyanus tonlarında koyu arayüz
- Turkuaz ve buz mavisi vurgular
- Nane yeşili, lavanta, mercan ve altın syntax renkleri
- Editör, terminal, sekmeler, yan paneller ve Git durumları için uyumlu renkler

## Kurulum

1. `Prism-Aurora` klasörünü VS Code'da aç.
2. Terminalde `npm install -g @vscode/vsce` komutunu bir kez çalıştır.
3. Proje klasöründe `vsce package` komutunu çalıştır.
4. Oluşan `prism-aurora-1.0.0.vsix` dosyasını VS Code'a yükle:
   ```powershell
   code --install-extension .\prism-aurora-1.0.0.vsix
   ```
5. `Ctrl+Shift+P` → **Preferences: Color Theme** → **Prism Aurora**.

## Geliştirme

- `F5` ile Extension Development Host açıp temayı test edebilirsin.
- Tema renkleri `themes/prism-aurora-color-theme.json` içindedir.
- Paket listesi kontrolü: `npm run check`
- VSIX oluşturma: `npm run package`

## Proje

- Yayıncı: PrismCrew
- Sürüm: 1.0.0
- Lisans: MIT

Prism Aurora bağımsız bir topluluk projesidir; Visual Studio Code veya Microsoft tarafından resmî olarak desteklendiği anlamına gelmez.
