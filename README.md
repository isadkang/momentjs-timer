# Dokumentasi Moment.js by IrsyadNat

![Moment.js Logo]([https://momentjs.com/downloads/moment-logo.png](https://avatars.githubusercontent.com/u/4129662?s=200&v=4))

Moment.js adalah sebuah pustaka JavaScript yang kuat untuk manipulasi waktu dan tanggal. Pustaka ini memudahkan pengolahan tanggal dan waktu dalam berbagai format.

## Instalasi

Anda dapat menginstal Moment.js melalui npm dengan perintah berikut:

```shell
npm install moment
```

Atau bisa juga dengan menggunakan CDN: 
```html
<script src="https://cdn.jsdelivr.net/momentjs/latest/moment.min.js"></script>
```

## Penggunaan Dasar 

```javascript
// Mendapatkan tanggal dan waktu saat ini
const now = moment();

// Mendapatkan tanggal dan waktu 7 hari yang lalu
const sevenDaysAgo = moment().subtract(7, 'days');

// Memformat tanggal
const formattedDate = now.format('YYYY-MM-DD');

// Menambahkan waktu
const futureDate = now.add(3, 'hours');

// Menghitung selisih waktu
const duration = moment.duration(futureDate.diff(now));
```

## Dokumentasi lengkap
Untuk informasi lebih lanjut tentang cara menggunakan Moment.js dan semua fungsionalitas yang ditawarkan, silakan lihat dokumentasi resmi di [https://momentjs.com/]
