# Rudder Command Path

Interactive 3D simulation of a ro-ro ship's steering gear. Follow a rudder command from the bridge through the control unit, electrics, hydraulics, rams, tiller and rudder stock until the ship turns.

Static site (HTML, Three.js, GSAP). No build step, no backend.

## Isi situs (Indonesia)

- Perintah kemudi gaya anjungan, misalnya `stbd 20`, `port 15`, `hard a-starboard`, `midships`.
- Tur orang pertama 8 tahap: Bridge, Control, Listrik, Hidrolik, Aktuator, Mekanik, Rudder, Kapal.
- Mesin FSM S0 sampai S4 dengan toleransi ε = ±0,5° dan laju rudder mengikuti SOLAS II-1/29.
- Tiga skenario: normal, pompa 1 gagal, katup bypass terbuka (kasus CMA CGM Puccini).
- Tombol Komponen: nama dan fungsi tiap bagian kapal RoRo.

## Menjalankan

Buka `index.html` di browser, atau deploy folder ini ke Vercel sebagai situs statis.

## Sumber

- ATSB. (2025). Loss of steering control and collision with navigation beacon, CMA CGM Puccini, Melbourne, 25 May 2023 (MO-2023-002).
- Indian Register of Shipping. (2014). Technical Circular No. 022/2014.
- Wagenborg. (n.d.). O-class. https://wagenborg.com/fleetlist/o-class
- Wärtsilä. (n.d.). Ro-ro; Steering gear. Wärtsilä Encyclopedia of Marine and Energy Technology.
