## Lab 1

### Penggunaan end
Di dalam bahasa Python, pengunaan "**end**" merupakan salah satu fungsi bawaan untuk melakukan operasi output yaitu fungsi `print()`.  "**end**" adalah karakter yang dicetak diakhir baris. Defaultnya adalah tanda _newline_ (baris baru).

    # penggunaan end  
    print('A', end='')  
    print('B', end='')  
    print('C', end='')  
    print()  
    print('X')  
    print('Y')  
    print('Z')
   
   dan akan muncul outputnya seperti di bawah ini:
   
   ![enter image description here](https://github.com/kameliacindy/Tugas_2/blob/master/img/end.PNG)
   
   ### Penggunaan separator
   Selain penggunaan "**end**" , di dalam sintaks fungsi `print()` juga terdapat penggunaan "**separator**" yang merupakan pemisah (separator) yang berfungsi sebagai pemisah antar objek yang dicetak. Defaultnya adalah tanda spasi.

    # penggunaan separator  
    w, x, y, z = 10, 15, 20, 25  
    print(w, x, y, z)  
    print(w, x, y, z, sep=',')  
    print(w, x, y, z, sep='')  
    print(w, x, y, z, sep=':')  
    print(w, x, y, z, sep='-----')
   yang outputnya seperti di bawah ini:
   
   ![enter image description here](https://github.com/kameliacindy/Tugas_2/blob/master/img/sep.PNG)

### Penggunaan String Format
String format digunakan ketika kita ingin mengatur dan memposiskan print output menjadi sedemikian rupa.  
**Contoh kode :**

    # String yang sebelum di format
    print(0, 10 ** 0)  
    print(1, 10 ** 1)  
    print(2, 10 ** 2)  
    print(3, 10 ** 3)  
    print(4, 10 ** 4)  
    print(5, 10 ** 5)  
    print(6, 10 ** 6)  
    print(7, 10 ** 7)  
    print(8, 10 ** 8)  
    print(9, 10 ** 9)  
    print(10, 10 ** 10)
    
Hasil outputnya:

![enter image description here](https://github.com/kameliacindy/Tugas_2/blob/master/img/string%20format%201.PNG)

Dan kita akan mengubah outputnya menjadi seperti ini:

![enter image description here](https://github.com/kameliacindy/Tugas_2/blob/master/img/string%20format%202.PNG)

Dengan kodenya seperti di bawah ini:

    print('{0:>3} {1:>16}'.format(0, 10 ** 0))  
    print('{0:>3} {1:>16}'.format(1, 10 ** 1))  
    print('{0:>3} {1:>16}'.format(2, 10 ** 2))  
    print('{0:>3} {1:>16}'.format(3, 10 ** 3))  
    print('{0:>3} {1:>16}'.format(4, 10 ** 4))  
    print('{0:>3} {1:>16}'.format(5, 10 ** 5))  
    print('{0:>3} {1:>16}'.format(6, 10 ** 6))  
    print('{0:>3} {1:>16}'.format(7, 10 ** 7))  
    print('{0:>3} {1:>16}'.format(8, 10 ** 8))  
    print('{0:>3} {1:>16}'.format(9, 10 ** 9))  
    print('{0:>3} {1:>16}'.format(10, 10 ** 10))
    
Dalam contoh di atas terdapat **{ }** yang berfungsi sebagai _**placeholder**_ atau penempat **arguments**. Argument secara default urutannya adalah **berurutan**.

![enter image description here](https://github.com/antonmartinus72/Labo_1-2/blob/master/img/6_Output_String-f.png)

Misalnya _**placeholder**_ pada urutan pertama yaitu "{**0**:>3}" dan kita ingin mengganti menjadi "**1**" maka yang akan dicetak di _**placeholder**_ pertama adalah output dari "**10 ** 0**".
 **Contoh kode :**
 
 print('{1:>3} {0:>16}'.format(0, 10 ** 0))

Hasil outputnya:

![enter image description here](https://github.com/kameliacindy/Tugas_2/blob/master/img/string.PNG)




