📒 Part 7 — Masking, Path & SVG FX

|  No | Nama Efek            | Deskripsi Singkat                           | Teknik / Properti Utama                            | Tool / Library Umum |
| :-: | :------------------- | :------------------------------------------ | :------------------------------------------------- | :------------------ |
|  1  | mask-reveal          | Teks muncul dari balik bentuk/topeng        | `mask-image`, `clip-path`, `@keyframes`            | CSS                 |
|  2  | text-mask-slide      | Garis masker bergerak mengungkap huruf      | linear mask gradient + `background-position`       | CSS                 |
|  3  | gradient-mask        | Gradasi mask sebagai transisi lembut        | `mask-image: linear-gradient`, `opacity`           | CSS                 |
|  4  | stroke-draw          | Garis luar huruf tergambar satu-per-satu    | SVG `stroke-dasharray` + `stroke-dashoffset`       | CSS / SVG           |
|  5  | outline-trace        | Menelusuri outline lalu mengisi isi huruf   | animasi stroke → fill delay                        | CSS / SVG           |
|  6  | reveal-from-path     | Huruf muncul mengikuti jalur SVG            | `clipPathUnits="objectBoundingBox"`, `offset-path` | SVG / CSS           |
|  7  | text-on-path         | Huruf mengikuti jalur melengkung            | `<textPath>` SVG                                   | SVG                 |
|  8  | path-morph-text      | Bentuk huruf berubah jadi bentuk lain       | SVG `path` morph (tween d), GSAP                   | GSAP / anime.js     |
|  9  | wave-mask            | Gelombang membuka teks                      | `mask-image` + SVG sine path                       | CSS / SVG           |
|  10 | circle-reveal        | Lingkaran membesar menampilkan teks         | radial mask + `scale`                              | CSS                 |
|  11 | text-inside-shape    | Teks mengisi bentuk khusus                  | `shape-inside` (eksperimental)                     | CSS                 |
|  12 | gradient-fill-mask   | Isi gradasi bergerak di teks                | `background-clip: text`, mask gradasi              | CSS                 |
|  13 | liquid-reveal        | Cairan naik mengisi huruf                   | `mask-image` + `SVG feTurbulence`                  | CSS / SVG           |
|  14 | sand-reveal          | Butiran pasir turun mengungkap huruf        | noise mask per-frame                               | Canvas / JS         |
|  15 | image-in-text        | Gambar/video dalam bentuk huruf             | `background-clip: text`, `color: transparent`      | CSS                 |
|  16 | video-mask-text      | Video bergerak di isi teks                  | `background-clip: text` + video tag                | CSS                 |
|  17 | texture-fill         | Tekstur (pattern) mengisi teks              | `background-image: url(...)` + clip                | CSS                 |
|  18 | path-follow-cursor   | Huruf bergerak menyusuri jalur cursor       | SVG `pathLength`, JS mousemove                     | JS / SVG            |
|  19 | split-mask-reveal    | Masker membuka setengah-setengah atas/bawah | dua masker berlawanan arah                         | CSS                 |
|  20 | spiral-mask          | Spiral membuka teks                         | `clip-path: polygon` berputar                      | CSS                 |
|  21 | line-reveal          | Garis mendatar melintasi huruf              | `scaleX`, `transform-origin`                       | CSS                 |
|  22 | wipe-reveal          | Efek sapuan horizontal/vertikal             | `clip-path`, `transform: translate`                | CSS                 |
|  23 | grid-mask            | Grid muncul satu-satu                       | multiple mask segments                             | CSS/JS              |
|  24 | shard-mask           | Masker pecah-pecah acak                     | polygon clip-path acak                             | CSS/JS              |
|  25 | checker-reveal       | Kotak-kotak bergantian                      | pattern mask + delay                               | CSS                 |
|  26 | stripe-reveal        | Garis-garis horizontal membuka teks         | `mask-image: repeating-linear-gradient`            | CSS                 |
|  27 | brush-stroke         | Efek sapuan kuas melukis huruf              | texture mask brush                                 | CSS / Canvas        |
|  28 | ink-spread           | Tinta menyebar mengisi teks                 | animated mask blur                                 | CSS                 |
|  29 | flame-mask           | Api membakar munculkan teks                 | turbulence mask api                                | SVG / Canvas        |
|  30 | smoke-mask           | Asap menyapu teks                           | opacity map asap                                   | CSS / Canvas        |
|  31 | light-sweep-mask     | Sorotan cahaya melewati huruf               | linear gradient mask bergerak                      | CSS                 |
|  32 | gradient-stroke-path | Garis luar bergradasi berubah               | `stroke: url(#gradient)` SVG                       | SVG                 |
|  33 | path-dash-pulse      | Garis berdenyut sepanjang jalur             | ubah `stroke-dashoffset` oscillate                 | SVG                 |
|  34 | multi-mask-cascade   | Serangkaian masker berurutan                | beberapa clip ber-delay                            | CSS/JS              |
|  35 | text-path-morph      | Huruf berganti jalur SVG lain               | tween `d` path                                     | GSAP / anime.js     |
|  36 | orbit-path-letters   | Huruf bergerak mengikuti orbit              | `offset-path` + `offset-rotate`                    | CSS                 |
|  37 | circle-text-orbit    | Huruf mengelilingi lingkaran                | `transform: rotate()` berulang                     | CSS/JS              |
|  38 | spiral-text-follow   | Huruf berputar mengikuti spiral             | `textPath` spiral                                  | SVG                 |
|  39 | wave-text-path       | Teks di atas gelombang bergerak             | SVG sinusoid `animateTransform`                    | SVG                 |
|  40 | scroll-mask-sync     | Masker bergerak sinkron scroll              | mask pos ∝ scrollY                                 | CSS / GSAP          |
