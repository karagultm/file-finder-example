# 📂 Empty File Finder (Go)

Bu küçük CLI aracı, verilen bir klasördeki **boş dosyaları** (0 byte
boyutunda) bulur.\
Bulunan dosya adlarını `out.txt` dosyasına yazar ve aynı zamanda
terminale basar.

------------------------------------------------------------------------

## 🚀 Nasıl Çalıştırılır?

### Gereksinimler

-   [Go](https://go.dev/dl/) kurulu olmalı.

### Adımlar

``` bash
# Depoyu klonla
git clone https://github.com/karagultm/file-finder-example.git
cd file-finder-example

# Programı çalıştır
go run main.go <klasör_yolu>
```

Örnek:

``` bash
go run main.go ./test-folder
```

------------------------------------------------------------------------

## 📄 Örnek Çıktı

Diyelim ki klasörde 3 tane boş dosya var: `a.txt`, `b.log`, `c.csv`

Terminal çıktısı:

    Total required space: 18 bytes
    a.txt
    b.log
    c.csv

`out.txt` dosyası:

    a.txt
    b.log
    c.csv

------------------------------------------------------------------------

## 🛠 Özellikler

-   0 byte boyutundaki dosyaları bulur.\
-   Dosya isimlerini `out.txt` dosyasına kaydeder.\
-   Terminalde aynı bilgiyi gösterir.

------------------------------------------------------------------------

## 📌 Kullanım Senaryoları

-   Büyük projelerde boş (içeriği olmayan) log veya konfigürasyon
    dosyalarını tespit etmek.\
-   Temizlik yapmak için kullanılabilir.
