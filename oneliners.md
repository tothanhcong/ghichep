## Oneliners - Phong cách một phát một

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