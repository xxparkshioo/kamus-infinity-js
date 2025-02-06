# kamus-infinity-js

Infitinity adalah properti dari objek global. Dengan kata lain, ini adalah variabel global.

- 2 Jenis:

1. Infinity adalah angka yang mewakili tak terhingga positif.

2. -Infinity mewakili tak terbatas negatif.

Tipe data dari Infinity adalah _Number_.

const result = typeof (Infinity);

console.log(result); // number

---------------------------------------------------------------------------------------
**** Memeriksa Infinity ****

JavaScript menyediakan Number.isFinite() yang memeriksa apakah suatu nilai terbatas:

Number.isFinite(value);

Ini kembali jika terbatas; Jika tidak terbatas, pengembalian

console.log(Number.isFinite(100)); // true

console.log(Number.isFinite(Infinity)); // false

console.log(Number.isFinite(-Infinity)); // false

Selain itu, Anda dapat membandingkan nilai dengan seperti ini:Infinity

let counter = 100;

console.log(counter === Infinity); // false    

Dan bilangan tak terbatas sama dengan bilangan tak terbatas lainnya:

console.log(Infinity === Infinity); // true
