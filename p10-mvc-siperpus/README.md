# p10-mvc-siperpus

Praktikum PBO 2 Pertemuan 10: data buku dengan pola MVC dan DAO di memori.

## Struktur paket
- `model`        : Buku (record)
- `dao`          : BukuDao (interface)
- `dao.memori`   : BukuDaoMemori
- `view`         : PanelBuku, DialogBuku, JendelaBuku, BukuTableModel
- `controller`   : BukuController
- (akar)         : AplikasiBuku (main)

## Cara menjalankan
Buka di Apache NetBeans, Clean and Build, lalu Run `AplikasiBuku`.
Atau lewat terminal (JDK 21 + Maven):

    mvn compile exec:java -Dexec.mainClass=id.ac.uniska.pbo2.siperpus.AplikasiBuku
