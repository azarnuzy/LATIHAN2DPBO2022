# Desain Pemrograman Berorientasi Objek

## Praktikum 
> Muhammad Azar Nuzy 
> 2004191
> Ilmu Komputer - C1
> Universitas Pendidikan Indonesia

Repositori ini dibuat sebagai latihan dari mata kuliah Desain Pemprograman Berorientasi Objek di UPI pada semester 4. Di dalamnya terdapat beberapa implementasi kelas dalam bahasa  **PHP**, **C++**, **Python** dan **Java**.

### Project Description
Terdapat tiga kelas pada project kali ini yaitu kelas Product, Hardware, dan Memory. Product merupakan parent dari Hardware dan Hardware merupakan parent dari Memory. Atribut setiap kelas
<img src="https://github.com/azarnuzy/LATIHAN2DPBO2022/blob/master/classDiagram2.png" style="height:450px;" align="right">  
- Product
  - idProduct 
  - price
- Hardware
  - brand
  - model
- Memory
  - frequency
  - memorySize
  - supportsCuda


Materi latihan dari kode di repositori ini dapat di temukan di file  [Modul 2 - Single and Multilevels Inheritance (Java)](https://github.com/azarnuzy/LATIHAN2DPBO2022.git)

### Tools
- [XAMPP](https://www.apachefriends.org/download.html) : PHP 
- [JDK](https://www.oracle.com/java/technologies/downloads/) : Java
- [Python](https://www.python.org/) : Python
- [MinGW](https://sourceforge.net/projects/mingw-w64/) : C++
- Browser
- Text Editor

### Usage

Untuk menjalankan kode repository di atas dapat dijalankan di terminal pada komputer. Path pada terminal ditujukan ke arah folder yang ingin dijalankan:

#### C++
```
g++ -c *.cpp
g++ main.cpp -o [name].exe
```

#### Java
```
javac *.java
java main
```

#### PHP
- Kode PHP diletakan di dalam folder htdocs yang ada pada folder XAMPP
- Pada PHP kode dijalankan melalui browser
- Aktifkan web server apache pada XAMPP
- Lalu di browser masukan alamat berikut 
  > localhost/[nama-folder]/[nama-file].php

#### Python
```
py [name].py
```

### Result
1. C++<br/>
![CPPResult](https://github.com/azarnuzy/LATIHAN2DPBO2022/blob/master/ScreenShot/CPPResult.jpg)
2. Java<br/>
![javaResult](https://github.com/azarnuzy/LATIHAN2DPBO2022/blob/master/ScreenShot/javaResult.jpg)
3. PHP<br/>
![PHPResult](https://github.com/azarnuzy/LATIHAN2DPBO2022/blob/master/ScreenShot/PHPResult.jpg)
4. Python<br/>
![pythonResult](https://github.com/azarnuzy/LATIHAN2DPBO2022/blob/master/ScreenShot/pythonResult.jpg)