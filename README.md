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

### Penggunaan String Format


