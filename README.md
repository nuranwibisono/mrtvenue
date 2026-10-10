# Gigmap Jaksel

Peta venue musik di Jakarta Selatan dan sekitarnya, lengkap dengan MRT dan bus terdekat.

**Demo:** https://nuranwibisono.github.io/mrtvenue/

## Fitur
- Peta venue musik, stasiun MRT, dan halte bus
- Cari venue atau area, filter MRT / Bus
- MRT dan bus terdekat beserta estimasi jalan kaki
- Tombol "Dekat saya" dan tautan rute transportasi umum ke Google Maps

## Embed di website
```html
<iframe src="[https://USERNAME.github.io/gigmap-jaksel/](https://nuranwibisono.github.io/mrtvenue/)"
  width="100%" height="640" style="border:0;border-radius:12px"
  loading="lazy" allow="geolocation" title="Gigmap Jaksel"></iframe>
```

## Mengubah data
Buka `index.html`, lalu edit blok `VENUES` dan `STOPS` di bagian atas script.

## Sumber data
- Venue dan stasiun MRT: file GeoJSON buatan sendiri (koordinat, jarak, dan waktu jalan kaki ke MRT mengikuti file).
- Halte bus: titik contoh, koordinat perkiraan.
- Jadwal gigs belum tersedia.

## Kredit
Peta: [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors. Library: [Leaflet](https://leafletjs.com).
