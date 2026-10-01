# HMPS TI UIN Salatiga — V8

Perubahan V8:
- Interaksi Struktur Organisasi mendapat particle trail saat swipe/drag.
- Klik divisi, next/previous, dan pencarian memicu particle burst yang halus.
- Animasi perpindahan member memakai arah swipe.
- Quick navigation tidak lagi memakai angka 01/02/03/04; langsung menggunakan Tentang, Struktur, Kegiatan, Kontak.
- Bottom navigation mobile juga menggunakan label fitur langsung: Beranda, Tentang, Struktur, Kegiatan, Kontak.
- Bottom navigation mengikuti section aktif saat scroll.
- Efek partikel menghormati prefers-reduced-motion.


V10 revision: organization carousel controls use a dedicated desktop/mobile layout; interactive particles are scoped to the organization section; carousel transitions are simultaneous and direction-aware.


V17: Removed numeric section/point labels (01, 02, 03, 04, etc.) from visible UI headings.


V18 asset configuration:
- assets/members/ berisi 31 placeholder JPG dengan nama file sesuai nama anggota. Tim tinggal mengganti/overwrite file tersebut dengan foto asli tanpa mengubah data/mengedit HTML.
- assets/activities/ berisi placeholder JPG untuk setiap kegiatan yang sudah didaftarkan. Tinggal overwrite file dengan dokumentasi asli.
- assets/icons/icon-placeholder.png menggantikan file .gitkeep pada folder icons.
- Semua path foto anggota dan dokumentasi kegiatan sudah dikonfigurasi di data/members.js dan data/activities.js.
## Welcome sound

Tempat audio welcome ada di `assets/audio/welcome.mp3`.
Cukup ganti file tersebut dengan MP3 milikmu menggunakan **nama file yang sama**. Tidak perlu mengubah HTML atau JavaScript.

Catatan: browser dapat memblokir autoplay bersuara. Website sudah mencoba memutar audio saat welcome dimulai; jika autoplay diblokir, audio akan dipicu pada interaksi pertama pengguna (klik/tap/tekan tombol).
