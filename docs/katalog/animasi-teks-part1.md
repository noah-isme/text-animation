| No | Nama Efek          | Kategori Utama      | Deskripsi Fungsi                     | Properti / Teknik Umum                                  | Cocok Dipicu oleh | Biasanya Dibuat Dengan  |
| -- | ------------------ | ------------------- | ------------------------------------ | ------------------------------------------------------- | ----------------- | ----------------------- |
| 1  | fade-in            | Entrance / Reveal   | Teks muncul perlahan                 | `opacity`, `@keyframes`, `transition`                   | on load, scroll   | CSS                     |
| 2  | fade-out           | Exit                | Teks hilang perlahan                 | `opacity`, `transition`                                 | setelah delay     | CSS                     |
| 3  | slide-in-left      | Entrance            | Masuk dari sisi kiri                 | `transform: translateX()`, `opacity`                    | on load, scroll   | CSS                     |
| 4  | slide-in-right     | Entrance            | Masuk dari kanan                     | `transform`, `opacity`                                  | on load           | CSS                     |
| 5  | zoom-in            | Entrance            | Teks membesar dari kecil             | `transform: scale()`, `opacity`                         | load, hover       | CSS                     |
| 6  | zoom-out           | Exit                | Mengecil sambil hilang               | `transform`, `opacity`                                  | exit              | CSS                     |
| 7  | rotate-in          | Transform           | Rotasi sambil muncul                 | `transform: rotate()`, `opacity`                        | load              | CSS                     |
| 8  | rotate-out         | Transform           | Rotasi keluar                        | `transform`, `opacity`                                  | exit              | CSS                     |
| 9  | flip-in-x          | 3D Transform        | Rotasi 3D sumbu X                    | `transform: rotateX()`, `perspective`                   | scroll, load      | CSS / GSAP              |
| 10 | flip-in-y          | 3D Transform        | Rotasi 3D sumbu Y                    | `rotateY()`, `perspective`                              | hover             | CSS / GSAP              |
| 11 | roll-in            | Motion              | Huruf bergulir masuk                 | `transform: rotate()`, `translateX()`                   | load              | CSS                     |
| 12 | color-shift        | Color / Visual      | Warna teks berganti perlahan         | `color`, `hsl()`, `animation`                           | continuous        | CSS                     |
| 13 | gradient-text      | Color / Visual      | Gradasi warna bergerak               | `background-clip: text`, `linear-gradient`, `animation` | continuous        | CSS                     |
| 14 | shimmer            | Light Effect        | Cahaya bergerak di atas teks         | `background-position`, `mask-image`                     | continuous        | CSS                     |
| 15 | neon-glow          | Light Effect        | Efek cahaya luar teks                | `text-shadow`, `filter: blur()`                         | hover             | CSS                     |
| 16 | flicker-text       | Light Effect        | Kedipan lampu acak                   | `opacity`, `animation-timing`                           | continuous        | CSS                     |
| 17 | typing-effect      | Sequential          | Huruf muncul satu per satu           | JS loop, `substring()`, `setTimeout()`                  | load              | JS (Typed.js)           |
| 18 | deleting-effect    | Sequential          | Huruf dihapus satu per satu          | JS loop                                                 | typing cycle      | JS                      |
| 19 | scramble-text      | Sequential / Random | Huruf acak jadi benar                | random chars, GSAP plugin                               | load              | JS / GSAP               |
| 20 | wave-text          | Letter Animation    | Huruf naik turun bergelombang        | `transform: translateY()`, `delay` per huruf            | continuous        | CSS / JS                |
| 21 | bounce-text        | Letter Animation    | Huruf memantul                       | `transform: translateY()`, `ease-out`                   | load / hover      | CSS                     |
| 22 | swing-text         | Letter Animation    | Huruf berayun kiri kanan             | `transform-origin`, `rotate()`                          | continuous        | CSS                     |
| 23 | float-text         | Motion              | Huruf melayang lembut                | `translateY()`, `ease-in-out`, `alternate`              | continuous        | CSS                     |
| 24 | pop-text           | Entrance            | Huruf muncul cepat membesar          | `scale()`, `opacity`                                    | load              | CSS                     |
| 25 | stagger-fade       | Stagger             | Huruf muncul bergantian              | `animation-delay`, `nth-child()`                        | load              | CSS / JS                |
| 26 | scroll-reveal      | Scroll-triggered    | Muncul saat disorot viewport         | Intersection Observer                                   | scroll            | JS (AOS, ScrollTrigger) |
| 27 | parallax-text      | Scroll Motion       | Bergerak berbeda dari latar belakang | `transform`, scroll offset                              | scroll            | JS (Lax.js, GSAP)       |
| 28 | hover-glow         | Hover               | Cahaya muncul di hover               | `text-shadow`, `transition`                             | hover             | CSS                     |
| 29 | hover-underline    | Hover               | Garis bawah geser                    | `::after`, `width`, `transition`                        | hover             | CSS                     |
| 30 | click-pop          | Interaction         | Efek pop saat klik                   | `scale()`, event listener                               | click             | JS                      |
| 31 | text-depth         | 3D                  | Bayangan dalam teks                  | `text-shadow` multiple                                  | load              | CSS                     |
| 32 | 3d-rotate-text     | 3D                  | Teks berputar di ruang               | `rotateX/Y/Z`, `perspective`                            | hover             | CSS / JS                |
| 33 | orbit-text         | 3D Motion           | Teks mengelilingi lingkaran          | `rotate()` + position                                   | continuous        | CSS / GSAP              |
| 34 | holographic-text   | 3D / Light          | Efek warna hologram                  | `mix-blend-mode`, `gradient`                            | continuous        | CSS                     |
| 35 | glitch-effect      | Distortion          | Efek gangguan digital                | `clip-path`, `skew`, `filter`, duplicate layers         | continuous        | CSS                     |
| 36 | pixel-fade         | Distortion          | Huruf larut menjadi piksel           | canvas / particle                                       | exit              | JS                      |
| 37 | liquid-text        | Distortion          | Efek gelombang seperti air           | `filter: blur`, `SVG turbulence`                        | continuous        | CSS / SVG               |
| 38 | fire-text          | Visual              | Efek api di huruf                    | canvas particle / blend                                 | continuous        | JS                      |
| 39 | smoke-text         | Visual              | Efek asap dari teks                  | particle / alpha fade                                   | exit              | JS                      |
| 40 | dissolve-text      | Exit                | Teks larut perlahan                  | opacity + mask noise                                    | exit              | CSS                     |
| 41 | text-morphing      | Morph               | Ubah teks ke kata lain               | interpolate char / path morph                           | timed loop        | JS (anime.js, GSAP)     |
| 42 | particle-text      | Advanced            | Huruf berubah jadi partikel          | canvas / WebGL                                          | scroll / click    | JS                      |
| 43 | text-path-follow   | Advanced            | Huruf mengikuti jalur SVG            | `textPath` SVG                                          | continuous        | CSS / SVG               |
| 44 | liquid-fill-text   | Masking             | Cairan mengisi teks dari bawah       | `mask`, `background-position`                           | load              | CSS / SVG               |
| 45 | gradient-scroll    | Motion              | Gradasi bergerak dengan scroll       | `background-position`                                   | scroll            | CSS                     |
| 46 | infinite-loop-text | Loop                | Teks berjalan terus                  | `translateX()`, `animation: infinite`                   | continuous        | CSS                     |
| 47 | marquee-modern     | Loop                | Versi modern teks bergulir           | `animation`, `white-space: nowrap`                      | continuous        | CSS                     |
| 48 | clip-text          | Masking             | Gambar/video muncul dalam teks       | `background-clip: text`                                 | load              | CSS                     |
| 49 | stroke-animation   | Outline             | Garis teks digambar perlahan         | `stroke-dasharray` SVG                                  | load              | CSS / SVG               |
| 50 | highlight-swipe    | Emphasis            | Warna highlight menyapu teks         | `::before`, `transform: scaleX`                         | load / hover      | CSS                     |
