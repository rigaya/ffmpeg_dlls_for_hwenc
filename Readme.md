# ffmpeg_lgpl_dll

QSVEnc/NVENC/VCEEncの画質や速度といった性能の実験を目的とするサブモジュールです。

ビルド方法は下記を参照。

- [ffmpeg_dll](https://github.com/rigaya/build_scripts/tree/master/ffmpeg_dll)
- [dovi_hdr10plus](https://github.com/rigaya/build_scripts/tree/master/dovi_hdr10plus)

## 更新履歴

### 20250830
  - libass 0.9.0 -> 0.17.4 (x64), 0.14.0 (x86)
  - harfbuzz 11.4.4 (new)
  - libunibreak 6.1 (new)

### 20250825
  - ffmpeg 7.1+ (20240822) -> 8.0
  - libpng 1.6.44 -> 1.6.50
  - expat  2.6.2  -> 2.7.1
  - fribidi 1.0.11 -> 1.0.16
  - libogg 1.3.5 -> 1.3.6
  - libxml2 2.12.6 -> 2.14.5
  - libvpl 2.13.0 -> 2.15.0
  - libvpx 1.14.1 -> 1.15.2
  - dav1d  1.4.3  -> 1.5.1
  - libxxhash 0.8.2 -> 0.8.3
  - glslang  15.0.0 -> 15.4.0
  - dovi_tool 2.1.2 -> 2.3.1
  - libjpeg-turbo 2.1.0 -> 3.1.1
  - lcms2 2.16 -> 2.17
  - zimg 3.0.5 -> 3.0.6
  - libplacebo 7.349.0 -> 7.351.0
  - libsvtav1 3.1.0 (new!) x64 only
  - libvvenc 1.13.1 (new!) x64 only
  - mmt/tlv patchを削除

### 20241102
  - libhdr10plusを追加。

### 20240929
  - libdoviを追加。
  - x86用のlibplaceboのdllを追加。

### 20240921
  - libplaceboのdllを追加。(x64のみ)

### 20240902
  - mmt/tlv patchを改良

### 20240822
  - ffmpeg     7.0    -> 20240822 (9d15fe77e33b757c75a4186fa049857462737713)
  - dav1d      1.4.1  -> 1.4.3
  - libvpl     2.11.0 -> 2.12.0
  - libvpx     1.14.1 (new!)
  - Add mmt/tlv patch (https://github.com/superfashi/FFmpeg/commit/b5816cfeb3cba7ecd230d18192ac1cb401e22a54)

### 20240511
  - ffmpeg     6.1    -> 7.0
  - libpng     1.4.0  -> 1.4.3
  - expat      2.5.0  -> 2.6.2
  - opus       1.4    -> 1.5.2
  - libxml2    2.12.0 -> 2.12.6
  - dav1d      1.3.0  -> 1.4.1
  - libvpl     2.11.0 (new!)
  - nv-codec-headers 12.2.72.0 (new!)

### 20231123
  - ffmpeg     5.1    -> 6.1
  - libpng     1.3.9  -> 1.4.0
  - opus       1.3.1  -> 1.4
  - libsndfile 1.2.0  -> 1.2.2
  - libxml2    2.10.3 -> 2.12.0
  - dav1d      1.0.0  -> 1.3.0
  - libaribcaption       1.1.1 (new!)

### 20230204
  - ffmpeg     5.0    -> 5.1
  - libpng     1.3.8  -> 1.3.9
  - expat      2.4.4  -> 2.5.0
  - libsndfile 1.0.31 -> 1.2.0
  - libxml2    2.9.12 -> 2.10.3
  - libbluray  1.3.0  -> 1.3.4
  - dav1d      0.9.2  -> 1.0.0

### 20220302
  - ffmpeg     4.x    -> 5.0
  - expat      2.2.5  -> 2.4.4
  - fribidi    1.0.1  -> 1.0.11
  - libogg     1.3.4  -> 1.3.5
  - libvorbis  1.3.6  -> 1.3.7
  - libsndfile 1.0.28 -> 1.0.31
  - libxml2    2.9.10 -> 2.9.12
  - libbluray  1.1.2  -> 1.3.0
  - dav1d      0.6.0  -> 0.9.2

### 20220202

### 20200728

### 20200321

### 20200110

  - libogg  1.3.3  -> 1.3.4
  - twolame 0.3.13 -> 0.4.0
  - wavpack 5.1.0  -> 5.2.0
  - libxml2 2.9.9  -> 2.9.10
  - dav1d   0.5.2 (new)

### 20190613

  - libpng    1.6.34 -> 1.6.37
  - libvorbis 1.3.5  -> 1.3.6
  - opus      1.2.1  -> 1.3.1
  - soxr      0.1.2  -> 0.1.3
  - libxml2   2.9.9 (new)
  - libbluray 1.1.2 (new)
  - aribb24   rev85 (new)

### 20180520

- 初版