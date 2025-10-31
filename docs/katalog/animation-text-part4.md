📗 Part 4 — Scroll & Interaction FX

| No | Nama Efek                  | Trigger          | Deskripsi                             | Teknik / Properti Utama                      | Tool/Library Umum        |
| -- | -------------------------- | ---------------- | ------------------------------------- | -------------------------------------------- | ------------------------ |
| 1  | scroll-reveal              | Scroll (in-view) | Teks muncul saat masuk viewport       | IntersectionObserver, `opacity`, `translate` | AOS / GSAP ScrollTrigger |
| 2  | scroll-fade                | Scroll           | Transparansi bertambah seiring scroll | `opacity` vs scroll progress                 | GSAP                     |
| 3  | scroll-slide-up            | Scroll           | Geser naik + fade saat in-view        | `translateY`, `opacity`, stagger             | AOS / CSS                |
| 4  | scroll-slide-left          | Scroll           | Masuk dari kiri saat terlihat         | `translateX`, `opacity`                      | AOS / CSS                |
| 5  | scroll-parallax            | Scroll           | Teks bergerak beda kecepatan          | `transform: translateY`, factor              | Lax.js / GSAP            |
| 6  | scroll-speed-lines         | Scroll           | Motion blur saat geser                | `filter: blur` dinamis                       | GSAP                     |
| 7  | scroll-rotate              | Scroll           | Rotasi proporsional jarak scroll      | `rotate`, progress mapping                   | GSAP                     |
| 8  | scroll-scale               | Scroll           | Membesar/mengecil saat mendekat       | `scale`, easing                              | GSAP                     |
| 9  | scroll-pin                 | Scroll           | Teks “terkunci” sementara             | pinning section                              | GSAP ScrollTrigger       |
| 10 | scroll-scrub-typing        | Scroll           | Efek mengetik digerakkan scroll       | substring by progress                        | GSAP / custom JS         |
| 11 | scroll-gradient-reveal     | Scroll           | Mask/gradient buka teks               | `mask-image`, pos. mask vs scroll            | CSS/GSAP                 |
| 12 | scroll-split-stagger       | Scroll           | Kata/huruf muncul bertahap            | split + stagger + IO                         | GSAP SplitText           |
| 13 | scroll-color-shift         | Scroll           | Warna berubah by section              | `color`, CSS variables                       | GSAP                     |
| 14 | scroll-fixed-headline      | Scroll           | Headline fixed, konten berganti       | position sticky, opacity swap                | CSS / JS                 |
| 15 | scroll-marquee-sync        | Scroll           | Marquee dipercepat saat scroll        | `translateX` += delta                        | JS                       |
| 16 | hover-underline-swipe      | Hover            | Garis bawah meluncur                  | `::after` width/transform                    | CSS                      |
| 17 | hover-glow                 | Hover            | Glow halus saat diarahkan             | `text-shadow`, transition                    | CSS                      |
| 18 | hover-split                | Hover            | Teks terbelah tipis                   | `clip-path`, pseudo elements                 | CSS                      |
| 19 | hover-lift                 | Hover            | Naik sedikit + shadow                 | `translateY(-)`, `filter`                    | CSS                      |
| 20 | hover-wiggle               | Hover            | Goyang ringan                         | small `rotate` oscillation                   | CSS                      |
| 21 | hover-scramble             | Hover            | Scramble sementara                    | random chars loop                            | JS                       |
| 22 | hover-gradient-shift       | Hover            | Gradasi bergerak saat hover           | `background-position`                        | CSS                      |
| 23 | hover-letter-bounce        | Hover            | Huruf memantul satu-satu              | per-letter transform                         | CSS/JS                   |
| 24 | hover-reveal-mask          | Hover            | Mask membuka highlight                | `mask`, `clip-path`                          | CSS                      |
| 25 | click-pop                  | Click            | Tekan → pop & kembali                 | `scale(0.92→1.06→1)`                         | CSS/JS                   |
| 26 | click-ripple               | Click            | Riak dari titik klik                  | pseudo ripple + opacity                      | JS                       |
| 27 | click-spark                | Click            | Percikan kecil di sekitar teks        | particles, fade                              | JS                       |
| 28 | click-magnet               | Click/Drag       | Teks “ketarik” kursor                 | spring physics ke cursor                     | JS                       |
| 29 | press-depth                | Active           | Efek menekan (emboss)                 | `translateY`, shadow invert                  | CSS                      |
| 30 | focus-highlight            | Focus            | Sorotan saat fokus keyboard           | `outline`, bg sweep                          | CSS                      |
| 31 | focus-type                 | Focus            | Ketik hanya saat fokus                | caret + input binding                        | JS                       |
| 32 | in-view-counter            | In-view          | Angka menghitung naik                 | tween angka                                  | GSAP/JS                  |
| 33 | visibility-swap            | In/Out           | Ganti teks saat keluar/masuk          | IO callbacks, fade swap                      | JS                       |
| 34 | direction-aware-hover      | Hover            | Efek tergantung arah masuk            | mouse vector → mask                          | JS                       |
| 35 | gyro-parallax-text         | Device motion    | Bergerak sesuai giroskop              | `translate` by devicemotion                  | JS                       |
| 36 | audio-reactive-text        | Audio            | Vibrasi/scale ikuti audio             | WebAudio FFT → transform                     | JS                       |
| 37 | scroll-section-steps       | Scroll (step)    | Per langkah paragraf aktif            | “stepper” highlight                          | JS                       |
| 38 | sticky-progress-headline   | Scroll           | Headline + progres bar                | sticky + width progress                      | CSS/JS                   |
| 39 | hover-reveal-image-in-text | Hover            | Gambar muncul dalam teks              | `background-clip: text` swap                 | CSS                      |
| 40 | scroll-3d-perspective      | Scroll           | Perspective berubah saat scroll       | `perspective`, `rotateX`                     | GSAP                     |
| 41 | keypress-typing            | Keyboard         | Ketik nyata sesuai input              | event keydown → append                       | JS                       |
| 42 | long-press-glow            | Long press       | Glow makin kuat saat ditekan          | press duration → shadow                      | JS                       |
| 43 | drag-to-reveal             | Drag             | Geser untuk buka teks                 | mask position via drag                       | JS                       |
| 44 | hover-sound-typing         | Hover            | Suara klik mesin tik                  | audio sprite + hover                         | JS                       |
| 45 | scroll-snap-quotes         | Scroll-snap      | Quote per layar dengan transisi       | CSS scroll-snap + fade                       | CSS/JS                   |
