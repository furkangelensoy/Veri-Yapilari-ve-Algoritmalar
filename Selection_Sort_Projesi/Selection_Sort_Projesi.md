### **[22,27,16,2,18,6]** -> Insertion Sort

### **Soru 1)** Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

### **Cevap 1)**

- [2,27,16,22,18,6] **n**
- [2,6,16,22,18,27] **n-1**
- [2,6,16,22,18,27] **n-2**
- [2,6,16,18,22,27] **n-3**
- [2,6,16,18,22,27] **n-4**
- [2,6,16,18,22,27] **1**

### **Soru 2)** Big-O gösterimini yazınız.

### **Cevap 2)**

1'den n'e kadar olan sayıların toplamı = [n.(n+1)]/2 = (n^2+n)/2

Big-O gösterimi = **O(n^2)**

### **Soru 3)** Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

- a) Average case: Aradığımız sayının ortada olması
- b) Worst case: Aradığımız sayının dizinin en sonunda olması
- c) Best case: Aradığımız sayının dizinin en başında olması

### **Cevap 3)**

Sıralı dizi;  **[2,6,16,18,22,27]**
Aradığımız sayı olan 18, dizinin en başında veya en sonunda değildir. Dizinin ortalarında yer aldığından **Average case** kapmasına girer.

### **Soru 4)** **[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### **Cevap 4)**

- **[2,3,5,8,7,9,4,15,6]**
- **[2,3,5,8,7,9,4,15,6]**
- **[2,3,4,8,7,9,5,15,6]**
- **[2,3,4,5,7,9,8,15,6]**