# API Testing - Folkatech

## 📌 Setup & Installation

1. **Clone Repository**
   ```sh
   git clone https://github.com/An-Ra/Fkt-api.git
   cd Fkt-api
   ```

2. **Install Postman** (Jika belum terpasang)
   - [Download Postman](https://www.postman.com/downloads/)

3. **Import Collection & Environment**
   - Buka Postman
   - Pilih **File** > **Import**
   - Pilih file berikut:
     - `Folkatech - API Automation.postman_collection.json`
     - `FolkatechCollection.postman_environment.json`

## 🚀 Menjalankan Pengujian

1. **Jalankan Collection Secara Manual**
   - Pilih Collection `Folkatech - API Automation`
   - Klik **Send** pada setiap request

2. **Jalankan Collection Secara Otomatis**
   - Pilih Collection
   - Klik **Run Collection** (Runner)
   - Pastikan environment `FolkatechCollection` sudah dipilih
   - Klik **Run Folkatech - API Automation**

## ✅ Test Case

| #  | Scenario                      | Expected Response     |
|----|--------------------------------|----------------------|
| ✅ 1 | Submit valid report           | `2xx`                |
| ❌ 2 | Missing required fields       | `4xx`                |
| ❌ 3 | Invalid data type             | `4xx`                |
| ❌ 4 | Missing token                 | `4xx`                |
| ❌ 5 | Invalid category              | `4xx`                |


```

## 📝 Catatan
- API yang di test pada collection ini sebagian besar tidak ada error handling dari sisi server , akibatnya banyak criteria yang tidak sesuai
```

**Result**
![image](https://github.com/user-attachments/assets/bd4cc325-c66f-4cd9-8600-687543dcc056)


