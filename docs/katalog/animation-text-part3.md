📘 Part 3 — Letter-Level & Typing FX

| No | Nama Efek               | Deskripsi Singkat                                | Teknik / Properti Utama                         | Biasanya Dibuat Dengan         |
| -- | ----------------------- | ------------------------------------------------ | ----------------------------------------------- | ------------------------------ |
| 1  | typewriter              | Mengetik huruf demi huruf dengan kursor berkedip | JS loop `substring`, caret `::after`, `opacity` | Typed.js / TypeIt / Vanilla JS |
| 2  | typing-loop             | Mengetik → pause → hapus → ketik lagi (loop)     | Timing queue, `setTimeout`, delete backspace    | Typed.js / TypeIt              |
| 3  | backspace               | Efek menghapus huruf per karakter                | Reverse substring, `setInterval`                | Typed.js / Vanilla JS          |
| 4  | caret-blink             | Kursor teks berkedip                             | `::after`, `animation: blink`, `opacity`        | CSS                            |
| 5  | multi-word-rotate       | Ganti kata secara bergiliran                     | Array kata + swap text node                     | JS (setInterval)               |
| 6  | per-letter-fade         | Setiap huruf fade-in berurutan                   | Split text → `animation-delay` bertahap         | CSS / GSAP                     |
| 7  | per-letter-slide        | Huruf masuk dari arah berbeda                    | `transform: translate`, stagger                 | CSS / GSAP                     |
| 8  | per-letter-pop          | Huruf “pop” (scale) satu-satu                    | `scale`, `opacity`, easing                      | CSS / GSAP                     |
| 9  | stagger-wave            | Gelombang vertikal berantai                      | `translateY`, sin/cycle delay                   | CSS / GSAP                     |
| 10 | stagger-rotate          | Rotasi tiap huruf berantai                       | `rotate`, transform-origin                      | CSS / GSAP                     |
| 11 | bounce-letters          | Huruf memantul bergantian                        | `translateY`, `cubic-bezier` bounce             | CSS                            |
| 12 | swing-letters           | Huruf berayun kiri-kanan                         | `rotate`, `transform-origin: top`               | CSS                            |
| 13 | flip-letters-x          | Flip 3D sumbu X per huruf                        | `rotateX`, `perspective`, stagger               | CSS / GSAP                     |
| 14 | flip-letters-y          | Flip 3D sumbu Y per huruf                        | `rotateY`, `perspective`                        | CSS / GSAP                     |
| 15 | scramble-text           | Acak karakter lalu converge ke huruf benar       | Random map + easing; GSAP Scramble              | JS / GSAP                      |
| 16 | decode-effect           | “Didekripsi” dari simbol acak                    | Lookup table, time window                       | JS                             |
| 17 | slot-machine            | Tiap huruf berputar seperti slot                 | Rolling list per posisi                         | JS / CSS                       |
| 18 | ticker-per-char         | Teks berjalan karakter per karakter              | `translateX`, monospace spacing                 | CSS                            |
| 19 | morph-letters           | Huruf berubah bentuk (SVG glyph)                 | SVG `path` morph, `stroke-dash`                 | GSAP / anime.js / SVG          |
| 20 | blur-reveal-letters     | Muncul dari blur ke tajam                        | `filter: blur`, `opacity`                       | CSS                            |
| 21 | outline-draw            | Outline huruf “digambar”                         | SVG stroke, `stroke-dashoffset`                 | CSS / SVG                      |
| 22 | fill-after-stroke       | Garis luar dulu, lalu isi huruf                  | SVG stroke → `fill` delay                       | CSS / SVG                      |
| 23 | neon-per-letter         | Glow neon tiap huruf staggered                   | `text-shadow` per span                          | CSS                            |
| 24 | gradient-sweep-letters  | Gradasi menyapu huruf per huruf                  | `background-clip: text`, offset per span        | CSS                            |
| 25 | hover-split-letter      | Huruf terbelah saat hover                        | `::before/::after`, `clip-path`                 | CSS                            |
| 26 | hover-wiggle-letter     | Goyang cepat saat hover                          | small `rotate` jitter                           | CSS                            |
| 27 | press-pop               | Klik → huruf “memantul”                          | `scale(0.9)→1.1→1`                              | CSS / JS                       |
| 28 | letter-fall             | Huruf jatuh dari atas dengan gravitasi halus     | `translateY`, delay bertingkat                  | CSS / GSAP                     |
| 29 | letter-rise             | Huruf naik dari bawah                            | `translateY`, `opacity`                         | CSS                            |
| 30 | letter-shatter          | Huruf “pecah” jadi fragmen                       | duplicate spans + offset random                 | GSAP / Canvas                  |
| 31 | letter-implode          | Huruf berkumpul dari posisi acak                 | random start → converge                         | GSAP                           |
| 32 | letter-orbit            | Huruf mengorbit titik pusat                      | `rotate` + translate polar                      | CSS / GSAP                     |
| 33 | per-letter-color-cycle  | Warna tiap huruf berganti                        | `color`/`hue-rotate` dengan offset              | CSS                            |
| 34 | per-letter-shadow-pulse | Bayangan tiap huruf berdenyut                    | `text-shadow` animated                          | CSS                            |
| 35 | highlight-swipe-letters | Sorotan bergerak per huruf                       | `background-size/position`                      | CSS                            |
| 36 | mask-reveal-letters     | Masker membuka huruf satu-satu                   | `clip-path`/`mask-image`                        | CSS                            |
| 37 | glitch-letters          | Glitch per huruf (RGB offset)                    | layered spans, skew/clip                        | CSS                            |
| 38 | noise-jitter            | Huruf bergemetar ringan                          | small `translate` noise                         | CSS                            |
| 39 | pixel-snap              | Huruf “snap” ke grid pixel                       | `step()` easing, translate                      | CSS                            |
| 40 | elastic-letters         | Efek elastis saat masuk                          | `scale` overshoot, spring easing                | GSAP                           |
| 41 | rubber-letter           | Melar saat hover lalu kembali                    | `scaleX/scaleY` alt                             | CSS                            |
| 42 | ripple-on-letter        | Riak muncul dari sebuah huruf                    | pseudo ripple + opacity                         | CSS / JS                       |
| 43 | focus-type              | Ketik hanya pada kata yang difokus               | caret + substring per span                      | JS                             |
| 44 | word-stagger            | Per kata muncul berantai                         | split by word + delay                           | CSS / GSAP / Splitting.js      |
| 45 | line-stagger            | Per baris muncul berantai                        | split by line (ResizeObserver)                  | JS / GSAP                      |
| 46 | random-stagger          | Urutan kemunculan acak                           | shuffle index + delay                           | JS / GSAP                      |
| 47 | per-letter-parallax     | Offset huruf saat scroll                         | scrollY × factor per span                       | JS (ScrollTrigger/Lax.js)      |
| 48 | magnetic-letters        | Huruf mengikuti kursor lembut                    | mouse spring physics                            | JS                             |
| 49 | per-letter-3d-depth     | Kedalaman berbeda per huruf                      | `translateZ`, `perspective`                     | CSS / GSAP                     |
| 50 | letter-path-follow      | Huruf mengikuti path melengkung                  | SVG `<textPath>` / motion                       | SVG / GSAP                     |
| 51 | type-on-scroll          | Mengetik hanya saat di-scroll                    | IntersectionObserver + type loop                | JS                             |
| 52 | progressive-reveal      | Ungkap huruf sesuai progress                     | progress → index                                | JS                             |
| 53 | countdown-digits        | Angka menurun per digit                          | tween angka, monospace                          | JS                             |
| 54 | superscript-pop         | Karakter tertentu “pop” (emoji/simbol)           | target class → scale                            | CSS                            |
| 55 | accent-bounce           | Huruf vokal memantul                             | regex select + bounce                           | JS / CSS                       |
| 56 | punctuation-flash       | Tanda baca berkilau                              | select punctuation + glow                       | CSS                            |
| 57 | per-letter-tilt         | Tilt kecil acak per huruf                        | `rotate` kecil + jitter                         | CSS                            |
| 58 | fade-swap-letter        | Huruf swap dengan fade silang                    | two layers per index                            | JS                             |
| 59 | scramble-on-hover       | Scramble hanya saat hover                        | hover trigger + randomize                       | JS                             |
| 60 | per-letter-clip-slice   | Potong huruf diagonal                            | `clip-path: polygon`                            | CSS                            |
