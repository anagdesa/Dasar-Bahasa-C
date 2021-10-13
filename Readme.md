# Proses installasi C pada Visual Studio Code

1. Download C Compiler yaitu MinGW (https://nuwen.net/mingw.html)
2. Install Compiler MinGW pada C:\
3. Setelah terinstall, cari lokasi bin pada direktory MinGW (C:\MinGW\bin)
4. Kemudian create new path in environtment variable sesuai dengan direktory bin
5. Cek apakah compiler sudah terinstall dengan cara, buka CMD kemudan tulis gcc --version (jika tampil makan instalasi sukses)
6. Download dan Install Visual Studio Code (https://code.visualstudio.com/)
7. Buka Visual Studio Code yang sudah terinstall 
8. pilih menu Ekstentions > install C/C++ dan Code Runner

# Membuat program baru

Buka Visual Studio Code > New File > simpan dengan format namafile.c

Contoh code
```c
#include <stdio.h>
int main(){
    printf("Halo dunia");
    return 0;
}
```
Output
```
Halo dunia
```

# Pengantar Bahasa C
Bahasa C merupakan general-purpose, procedural, imperative computier programming language yang di develop pada tahun 1973 oleh Dennis M. Ritchie di Bell Telephone Laboratories untuk operator sistem UNIX

Keuntungan menggunakan bahasa C, yaitu:
 - Mudah dipelajari dan dipahami
 - Bahasa yang terstruktur
 - Poduk program yang efisien
 - Menghendel pada aktivitas di low-level
 - Banyak komputer platform yang support
