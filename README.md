# Merge Sort Projesi
### **[16,21,11,8,12,22]** -> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
>*Birer eleman kalasıya kadar parçalama işlemi* (önce diziyi ikiye böldük, sonra böldüğümüz kısımları da kendi içinde tek eleman kalasıya kadar parçalıyoruz.]

[16, 21, 11, 8, 12, 22]
[16, 21, 11]  ve  [8,12, 22]
[16] [21,11] ve [8, 12] [22]
[16] [21] [11] ve [8] [12] [22]

>*Merging / Geri Birleştirme işlemi* (böldüğümüz kısımları tekrardan **sıraya koyarak** geri birleştiriyoruz.)

[16] [11, 21] ve [8, 12] [22]
[11, 16, 21 ] ve  [8, 12, 22]

>*Son olarak sıralanmış iki dizi birleştirilir ve merge sort sona erer.*
>>**[8, 11, 12, 16, 21, 22]**


- Big-O gösterimini yazınız.
>>**O(nlogn)**

--------------------------------------------------------------

# Binary Search Tree Projesi
### **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
- Root 5'tir.
- 5'in solunda '1', sağında ise '7' bulunur.
- 1'in solunda '0', sağında ise '3' bulunur.
- 7'nin solunda '6', sağında ise '8' bulunur.
- 3'ün solunda '2', sağında ise '4' bulunur.
- 8'in sağında '9' bulunur.

Seviyelere göre ağacın dizili haldeki sırası:
>[5, 1, 7, 0, 3, 6, 8, 2, 4, 9]
  
