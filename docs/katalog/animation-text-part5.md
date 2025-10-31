📙 Part 5 — 3D & Depth FX

| No | Nama Efek             | Deskripsi Singkat                   | Teknik / Properti Utama                           | Tool/Library Umum       |
| -: | --------------------- | ----------------------------------- | ------------------------------------------------- | ----------------------- |
|  1 | perspective-rotate-x  | Rotasi 3D sumbu X dengan perspektif | `perspective`, `transform: rotateX()`             | CSS / GSAP              |
|  2 | perspective-rotate-y  | Rotasi 3D sumbu Y                   | `perspective`, `rotateY()`                        | CSS / GSAP              |
|  3 | perspective-rotate-z  | Rotasi 3D sumbu Z (tilt)            | `rotateZ()` + depth cues                          | CSS                     |
|  4 | 3d-flip-card          | Flip depan–belakang (seperti kartu) | `transform-style: preserve-3d`, `rotateY(180deg)` | CSS / GSAP              |
|  5 | 3d-flip-text          | Tiap huruf “membalik” 3D            | split letters + `rotateX/Y`                       | CSS / GSAP SplitText    |
|  6 | coverflow-text        | Carousel 3D ala CoverFlow           | translateX + `rotateY` + depth                    | CSS / GSAP              |
|  7 | hinge-drop            | Teks “tergantung” lalu jatuh        | `transform-origin`, `rotateZ`, `translateY`       | CSS / GSAP              |
|  8 | fold-unfold           | Lipat–buka seperti kertas           | multiple planes, `rotateX`                        | CSS / GSAP              |
|  9 | accordion-3d          | Lembaran teks lipat berlapis        | stacked panels + `preserve-3d`                    | CSS                     |
| 10 | cube-text             | Teks pada sisi kubus berputar       | 6 faces div + `rotate3d`                          | CSS / GSAP              |
| 11 | cylinder-text         | Teks melingkar seperti silinder     | distribusi sudut + `rotateY`                      | CSS / GSAP              |
| 12 | ring-orbit-text       | Huruf mengorbit membentuk cincin    | polar transform + `rotate`                        | CSS / GSAP              |
| 13 | sphere-text (path)    | Teks mengikuti permukaan bola       | projected coordinates / shaders                   | Three.js                |
| 14 | isometric-tilt        | Sudut isometrik (pseudo 3D)         | `skew`, `rotate`, shadows                         | CSS                     |
| 15 | parallax-depth-layers | Layer teks bertingkat kedalaman     | beberapa layer `translateZ`                       | CSS / GSAP              |
| 16 | scroll-3d-parallax    | Depth bergerak saat scroll          | ScrollTrigger → `translateZ`                      | GSAP                    |
| 17 | depth-of-field        | Fokus di depan, blur di belakang    | `filter: blur` vs z-order                         | CSS / GSAP              |
| 18 | volumetric-light      | “Shaft” cahaya 3D lewat teks        | cone gradients, blend modes                       | CSS / Canvas            |
| 19 | extrusion-shadow      | Ilusi ekstrusi tebal                | multiple `text-shadow` bertumpuk                  | CSS                     |
| 20 | 3d-extruded-geo       | Geometri teks tebal sungguhan       | 3D TextGeometry + lights                          | Three.js                |
| 21 | hologram-3d           | Teks holografik berpendar           | `mix-blend-mode`, scanline                        | CSS / Three.js (postFX) |
| 22 | glass-depth           | Teks kaca transparan berlapis       | `backdrop-filter`, parallax                       | CSS                     |
| 23 | metal-specular        | Logam dengan specular highlight     | gradient animated + glare                         | CSS / Three.js (PBR)    |
| 24 | page-turn-title       | Judul “membalik halaman”            | perspective + `rotateY`                           | CSS / GSAP              |
| 25 | stair-steps           | Huruf pada anak tangga 3D           | offset Z per huruf                                | CSS / GSAP              |
| 26 | tunnel-zoom           | Zoom masuk lorong/bilah 3D          | scale + `translateZ` loop                         | CSS / GSAP              |
| 27 | orbital-camera-text   | Kamera mengitari teks 3D            | camera orbit controls                             | Three.js                |
| 28 | fly-through           | Kamera “menembus” kata              | camera forward + DOF                              | Three.js / GSAP         |
| 29 | shadow-caster         | Bayangan realistis ke bidang        | shadow plane + light dir                          | Three.js                |
| 30 | occlusion-reveal      | Teks muncul dari balik objek        | z-order / depth test                              | CSS (layers) / WebGL    |
| 31 | tilt-on-hover         | Kemiringan 3D responsif cursor      | pointer → `rotateX/Y`                             | CSS / Vanilla JS        |
| 32 | gyro-depth            | Bergerak sesuai giroskop            | DeviceMotion → `rotate`                           | JS                      |
| 33 | 3d-carousel-letters   | Huruf berputar seperti karusel      | circular layout + `rotateY`                       | CSS / GSAP              |
| 34 | folding-banner        | Banner judul lipat-lipat            | segmented planes + pivot                          | CSS / GSAP              |
| 35 | vaulted-arch-text     | Teks mengikuti lengkung kubah       | SVG path + depth shading                          | SVG / CSS               |
| 36 | bevel-emboss          | Timbul–tertekan ala UI 3D           | multi shadow + light dir                          | CSS                     |
| 37 | anaglyph-3d           | RGB shift anaglyph (depth cue)      | red/cyan offsets                                  | CSS                     |
| 38 | layer-fog-depth       | Kabut jarak (depth fog)             | overlay gradient noise                            | CSS / Canvas            |
| 39 | 3d-marquee-ring       | Marquee mengelilingi ring 3D        | text on ring + rotate                             | CSS / GSAP              |
| 40 | warp-perspective      | Warping perspektif dinamis          | `matrix3d()` / shader                             | CSS (advanced) / WebGL  |
| 41 | voxel-text            | Teks dari “kubus voxel”             | instanced boxes                                   | Three.js                |
| 42 | particles-depth       | Teks partikel dengan Z nyata        | point cloud + depth                               | Three.js                |
| 43 | cloth-text            | Kain bertuliskan teks (simulasi)    | verlet/physx + texture                            | Three.js / physics      |
| 44 | liquid-3d-text        | Cairan 3D di dalam huruf            | metaballs / fluid sim                             | Three.js / shaders      |
| 45 | portal-reveal         | Teks muncul dari portal 3D          | radial mask + depth fx                            | CSS / Three.js          |
| 46 | staircase-reveal      | Ungkap per anak tangga Z            | stepped Z + masks                                 | CSS / GSAP              |
| 47 | camera-rack-focus     | Pindah fokus depan–belakang         | DOF post-processing                               | Three.js                |
| 48 | mirage-reflection     | Refleksi lantai perspektif          | plane reflection + blur                           | CSS (fake) / Three.js   |
| 49 | shadow-parallax       | Bayangan bergerak vs mouse          | shadow offset by depth                            | CSS / JS                |
| 50 | depth-scan            | “Scanner” 3D melintasi teks         | moving plane + glow                               | CSS / GSAP / WebGL      |
