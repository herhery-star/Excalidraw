# Excalidraw Tablet PWA

PWA shell/launcher untuk penggunaan Excalidraw pada tablet Huawei.

## Isi
- `index.html` — launcher tablet-first
- `manifest.webmanifest` — identitas PWA
- `sw.js` — service worker untuk app shell
- `icons/` — ikon 192px dan 512px

## Cara pakai
1. Upload seluruh isi folder ini ke repository GitHub.
2. Aktifkan GitHub Pages.
3. Buka URL Pages tersebut di Chrome pada Huawei MatePad.
4. Pilih **Add to Home screen / Install app** jika tersedia.
5. Setelah terpasang, aplikasi akan tampil dalam mode `standalone`.

## Catatan penting
Shell ini tidak menyalin mesin Excalidraw ke dalam aplikasi. Ia menyediakan pengalaman PWA dan launcher untuk Excalidraw.
Jika browser menolak embedding Excalidraw di iframe, tombol **Buka Excalidraw** membuka Excalidraw penuh.

Untuk versi berikutnya, Excalidraw dapat diintegrasikan sebagai library ke dalam aplikasi My Drive Notebook sehingga canvas menjadi modul lokal dan dapat dihubungkan langsung ke Workspace/Google Drive.
