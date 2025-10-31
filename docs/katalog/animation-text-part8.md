📔 Part 8 — Advanced Programmatic FX (GSAP / Canvas / WebGL / Audio / Physics)

| No | Nama Efek                   | Deskripsi Singkat                             | Teknik / Properti Utama                   | Tool / Library Umum  |
| -- | --------------------------- | --------------------------------------------- | ----------------------------------------- | -------------------- |
| 1  | text-morph-sequence         | Huruf berganti bentuk antar kata (path morph) | tween `SVG d` path, easing cubic          | GSAP / anime.js      |
| 2  | particle-text               | Huruf tersusun dari partikel dinamis          | particle system, canvas drawText → points | Canvas / Three.js    |
| 3  | particle-explosion          | Teks meledak jadi partikel                    | velocity physics + fade                   | GSAP / Canvas        |
| 4  | particle-assemble           | Partikel menyatu membentuk teks               | inverted explosion (seek center)          | GSAP / Canvas        |
| 5  | fluid-text                  | Cairan membentuk huruf bergerak               | fluid sim shader / metaballs              | WebGL / Three.js     |
| 6  | smoke-reveal                | Asap membentuk teks                           | noise field + alpha mask                  | Canvas / WebGL       |
| 7  | sand-fall-text              | Butiran jatuh dan menumpuk jadi huruf         | physics particles (gravity + collision)   | JS / Matter.js       |
| 8  | ribbon-text                 | Pita bergerak mengikuti jalur huruf           | spline curve + width grad                 | Canvas / Three.js    |
| 9  | laser-beam-reveal           | Sinar laser menulis teks                      | line draw + glow blur                     | Canvas / GSAP        |
| 10 | matrix-rain-3D              | Efek hujan huruf 3D                           | 3D instancing, random char                | Three.js             |
| 11 | text-trail                  | Jejak teks mengikuti kursor                   | mouse tracking, easing trail              | JS / GSAP            |
| 12 | interactive-particles       | Partikel huruf bereaksi pada mouse/audio      | force field, repel attract                | Canvas / GSAP        |
| 13 | liquid-fill-canvas          | Cairan “mengisi” teks secara real             | per-pixel mask + wave sim                 | Canvas               |
| 14 | dynamic-gradient-text       | Gradasi warna berubah oleh audio atau data    | hue shift map                             | GSAP / WebAudio      |
| 15 | audio-spectrum-text         | Teks bergetar mengikuti suara                 | FFT → `scaleY` / color                    | WebAudio / GSAP      |
| 16 | beat-sync-glow              | Cahaya berkedip sinkron beat musik            | FFT peak → glow intensity                 | WebAudio             |
| 17 | real-time-typing            | Efek mengetik input user secara animatif      | key event → GSAP timeline                 | JS                   |
| 18 | speech-reactive-text        | Ukuran huruf berdasarkan volume mic           | WebAudio mic → transform scale            | JS                   |
| 19 | text-physics-fall           | Teks jatuh & bertumpuk realistis              | physics engine (Matter.js)                | JS                   |
| 20 | text-cloth-simulation       | Huruf seperti kain berayun                    | verlet physics, spring network            | Three.js / physics   |
| 21 | text-fluid-interaction      | Teks bereaksi seperti cairan saat disentuh    | fluid field solver                        | WebGL                |
| 22 | text-wind-flow              | Angin meniup huruf ke arah tertentu           | vector field simulation                   | Canvas               |
| 23 | shader-distortion-text      | Shader mendistorsi huruf dinamis              | GLSL displacement map                     | Three.js / WebGL     |
| 24 | hologram-scan               | Garis pemindai hologram menulis teks          | scanning shader + flicker                 | Three.js             |
| 25 | voxel-text                  | Huruf dari voxel (blok 3D)                    | instanced boxes + lighting                | Three.js             |
| 26 | depth-scan-text             | Sinar menelusuri teks 3D                      | camera scan animation                     | Three.js             |
| 27 | AI-noise-morph              | Huruf berubah organik via noise generatif     | simplex noise field                       | WebGL / ShaderToy    |
| 28 | line-particles-draw         | Garis partikel menggambar kontur huruf        | particle path following                   | GSAP / Canvas        |
| 29 | metaball-merge              | Huruf menyatu seperti bola cair               | metaball render                           | WebGL                |
| 30 | procedural-fire-text        | Api procedural di huruf                       | Perlin noise + gradient                   | ShaderToy / Three.js |
| 31 | text-in-mirror              | Teks 3D dengan pantulan realistis             | planar reflection + camera                | Three.js             |
| 32 | holographic-3D-projection   | Teks berkilau hologram dengan DOF             | post-processing + bloom                   | Three.js             |
| 33 | particle-disintegration     | Teks terurai jadi debu                        | per-pixel sampling + velocity noise       | Canvas / GSAP        |
| 34 | text-reconstruct            | Debu kembali membentuk huruf                  | reverse disintegration                    | GSAP                 |
| 35 | realtime-shader-typing      | Shader menulis teks frame-by-frame            | fragment shader drawText                  | WebGL                |
| 36 | physics-chain-letters       | Huruf saling terhubung dengan rantai          | constraint solver                         | Matter.js            |
| 37 | magnet-text                 | Huruf tertarik oleh magnet virtual            | distance falloff → force                  | JS / GSAP            |
| 38 | floating-3D-text-field      | Banyak huruf melayang acak di ruang 3D        | random motion + perspective               | Three.js             |
| 39 | scroll-trigger-timeline     | Scroll mengontrol adegan 3D teks              | timeline sync scroll                      | GSAP ScrollTrigger   |
| 40 | reactive-emoji-text         | Emoji muncul berdasar emosi pengguna          | sentiment analysis → replace              | JS / AI              |
| 41 | AI-generated-morph-font     | Huruf berubah gaya dengan model ML            | model style morph / Canvas                | TensorFlow.js        |
| 42 | dynamic-theme-text          | Warna & gaya berganti sesuai waktu/data       | live variable binding                     | CSS vars / JS        |
| 43 | camera-flythrough-text      | Kamera “terbang” melewati teks 3D             | camera path tween                         | Three.js             |
| 44 | aurora-particles            | Partikel bercahaya mengikuti garis huruf      | additive blend particles                  | Three.js             |
| 45 | galaxy-text                 | Huruf tersusun dari bintang 3D                | star field particle system                | Three.js             |
| 46 | ripple-field-text           | Riak air melintasi huruf                      | ripple solver + normal map                | WebGL                |
| 47 | typography-physics-explode  | Seluruh kalimat meledak & jatuh               | physics per glyph                         | Matter.js / GSAP     |
| 48 | ai-voice-to-text-effect     | Efek teks muncul saat bicara                  | SpeechRecognition API                     | JS                   |
| 49 | realtime-data-text          | Data real-time mengganti isi teks             | WebSocket / API stream                    | JS                   |
| 50 | combined-timeline-cinematic | Adegan multi-efek sinkron timeline            | GSAP master timeline                      | GSAP / Three.js      |
