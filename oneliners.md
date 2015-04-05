## Oneliners - Phong cách một phát một

### MỤC LỤC

* [AWK - Oneliners](#awk-oneliners)
* [SED - Oneliners](#sed-oneliners)
* [GREP - Oneliners](#grep-oneliners)
* [TẠP NHAM - Oneliners](#tapnham-oneliners)


<a name="awk-oneliners"></a>
### AWK - Oneliners
#### In ra các dòng chẵn hoặc dòng lẻ trong 1 file.
    ```sh
    # Dòng chẵn, chia 2 = 0
    awk '(NR%2==0)' file.txt

    # Dòng lẻ, chia 2 khác 0
    awk '(NR%2!=0)' file.txt

    ```
- Trong đó: 
  - NR là số thứ tự của dòng.
  - NF là số trường (field) - số cột ???? <== Xem lại nhé !

<a name="sed-oneliners"></a>
### SED - Oneliners

<a name="grep-oneliners"></a>
### GREP - Oneliners


<a name="tapnham-oneliners"></a>
### TẠP NHAM - Oneliners


  
