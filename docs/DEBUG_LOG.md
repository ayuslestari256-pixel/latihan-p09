# Debug Log - BubuList

Dokumentasi perbaikan bug dan penyesuaian kode pada proyek akhir BubuList.

---

## 1. Perbaikan Duplikat Kode pada `style.css`

* **Gejala / Masalah:** 
  File `style.css` sempat ada duplikat blok kode yang menumpuk di bagian bawah, bikin file jadi kepanjangan dan kurang rapi buat dibaca atau dipelihara ke depannya.
* **Alat DevTools:** 
  VS Code Editor / CSS Syntax Checker
* **Penyebab (Berkas : Baris):** 
  `style.css` (terdapat blok aturan yang ter-copy dua kali secara utuh di bagian bawah file).
* **Solusi Perbaikan:** 
  Membersihkan dan menghapus blok kode duplikat yang menumpuk di bagian bawah sehingga file CSS kembali bersih dan efisien tanpa mengubah tampilan visual antarmuka.
* **Hash Commit:** *(diisi nanti setelah commit)*