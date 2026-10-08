---
applyTo: "src/test/**/*.java"
---
- Gunakan JUnit Jupiter dan AssertJ. Gunakan Mockito jika diperlukan.
- Susun test dengan pola AAA (Arrange-Act-Assert).
- Uji alur sukses, edge case, dan error handling sesuai kontrak fungsi.
- Tinjau kode untuk menemukan potensi bug, lalu buat test untuk mereproduksinya.
- Uji concurrency hanya jika kode menggunakan state bersama atau proses concurrent.
- Jelaskan risiko bug dalam komentar test jika belum jelas dari nama dan isi test.
- Pastikan test independen dan deterministik.
