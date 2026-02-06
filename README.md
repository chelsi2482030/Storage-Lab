Nama : CHelsi Enatalia N PArhusip
NIM : 2482030
**LATIHAN 3**

**Eksperimen 1: Persistence Test**
- Cookies: masih ada
- LocalStorage: masih ada
- SessionStorage: hilang

**Eksperimen 2: Tab Isolation**
Berapa nilai counter di tab baru?
Nilai counter di tab baru ada 0

Berapa nilai counter di tab lama?
Nilai counter di tab lama ada 5

SessionStorage adalah tab-isolated

**Eksperimen 3: Storage Size Comparison**
- Cookies: 4 KB
- LocalStorage: 5-10 MB
- SessionStorage: 5-10 MB

**Eksperimen 4: Decision Quiz**
Screenshots ada di folder ini.

**Pertanyaan Refleksi**
1. **Mengapa session token TIDAK boleh disimpan di LocalStorage?**
Session token tidak boleh disimpan di LocalStorage karena LocalStorage dapat diakses oleh JavaScript.

2. **Apa keuntungan SessionStorage untuk multi-step form dibanding LocalStorage?**
Menjaga privasi pengguna, menghindari data lama mucul saat membuka ulang halaman, memberikan pengalaman fresh start.

3. **Jika kamu membuat aplikasi todo list offline-first, storage mana yang akan kamu gunakan dan mengapa?**
Menggunakan LocalStorage, karena LocalStorage menyediakan penyimpanan client-side yang cukup besar, sehingga cocok untuk kebutuhan tersebut.

**Summary:**
Cookie digunakan ketika data perlu dikirim ke server secara otomatis dan membutuhkan keamanan lebih. LocalStorage digunakan ketika data harus tersimpan secara permanen di sisi client, tetap ada meskipun browser ditutup, dan tidak perlu kirim ke server. Dan SessionStorage digunakan untuk data yang bersifat sementara dan spesifik pada satu tab.