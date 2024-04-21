# Tutorial 8 - Crosstown Bus Poc Subscriber
AdvPro B - Marvel Martin Everthard - 2206081345

---

## Reflection
1. what is amqp?
> **Advanced Message Queuing Protocol (AMQP)** adalah protokol komunikasi yang **memungkinkan berbagai aplikasi** untuk **berkomunikasi secara asinkronus** dengan cara _passing message_ melalui _message broker_.

2. what it means? guest:guest@localhost:5672 , what is the first guest, and what is
the second guest, and what is localhost:5672 is for?
> `guest:guest@localhost:5672` merupakan bagian dari **URL** yang digunakan untuk mengonfigurasi **koneksi ke AMQP**.
> - `guest:guest` merupakan username dan password yang digunakan untuk terhubung ke AMQP. `guest` pertama merujuk ke **username**, sedangkan `guest` kedua merujuk ke **password**.
> - `localhost:5672` merupakan alamat host dan nomor port server AMQP. `localhost` mengacu pada **_local machine_** tempat kode dijalankan dan `5672` adalah **nomor port default** untuk komunikasi AMQP.
