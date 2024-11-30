# Integrate LLMs with applications

# Ringkasan

Kode ini menggunakan Watsonx.ai untuk menghasilkan poin-poin penting dari ulasan yang diberikan. Ini menggunakan model `google/flan-ul2` dan beberapa parameter untuk menghasilkan teks.

# Prasyarat

Sebelum menjalankan kode ini, Anda harus menginstal pustaka dan Anda juga harus memiliki kunci API IBM Cloud dan ID proyek. Anda dapat memperolehnya dengan membuat akun di IBM Cloud.

# Bagaimana cara menjalankan kode

1. Instal pustaka yang diperlukan seperti yang disebutkan di bagian Prasyarat.
2. Dapatkan kunci API IBM Cloud Anda dan atur variabel lingkungan seperti yang dijelaskan dalam kode.
3. Masukkan ID proyek Anda dalam variabel `project_id`.
4. Jalankan kode tersebut.

# Output

Kode tersebut akan mencetak poin-poin penting yang dihasilkan ke konsol. Poin-poin penting tersebut juga akan disimpan dalam variabel `response`.


# Catatan

* Anda dapat mengubah model dan parameter yang digunakan untuk menghasilkan teks dengan memodifikasi variabel `model_id` dan `parameters`.
* Anda dapat mengubah input yang diberikan ke model dengan memodifikasi variabel `prompt_input`.