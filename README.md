# AI-Assisted Spring Boot Copilot Starter

Starter project untuk membangun aplikasi backend menggunakan Java dan Spring Boot dengan bantuan GitHub Copilot. Repository ini menyediakan panduan agar implementasi yang dibuat tetap mengikuti teknologi, pembagian tanggung jawab, dan standar pengujian yang diharapkan.

## Tujuan Project

Project ini bertujuan untuk:

- Menjadi titik awal pengembangan backend sederhana dengan Java 17 dan Spring Boot.
- Memberikan konteks dan aturan yang konsisten kepada GitHub Copilot saat membantu menulis atau mengubah kode.
- Mendorong kode yang sederhana, mudah dirawat, dan memiliki pengujian yang deterministik.

## Teknologi

Teknologi yang ditetapkan untuk aplikasi ini:

- Java 17
- Spring Boot
- Maven
- Lombok
- JUnit Jupiter

## Panduan di Folder `.github`

Folder `.github` berisi instruksi untuk GitHub Copilot:

| File | Fungsi |
| --- | --- |
| `copilot-instructions.md` | Panduan umum untuk seluruh project: gambaran aplikasi, teknologi, pemisahan tanggung jawab antara controller, service, repository, DTO, dan model, serta prinsip implementasi seperti YAGNI. File ini juga mengatur penggunaan Lombok dan dokumentasi pada class serta fungsi baru. |
| `instructions/test.instructions.md` | Panduan khusus untuk file test di `src/test/**/*.java`. Menentukan penggunaan JUnit Jupiter dan AssertJ (serta Mockito bila diperlukan), pola Arrange-Act-Assert, cakupan kasus yang perlu diuji, dan persyaratan agar test independen serta deterministik. |

## Status Repository

Repository ini saat ini berisi panduan Copilot dan belum menyertakan kode aplikasi maupun konfigurasi Maven. Tambahkan struktur aplikasi dan `pom.xml` saat mulai mengimplementasikan backend.
