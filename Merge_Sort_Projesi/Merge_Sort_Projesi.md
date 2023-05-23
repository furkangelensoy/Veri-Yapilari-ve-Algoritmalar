### **[16,21,11,8,12,22]** -> Merge Sort

### **Soru 1)** Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

### **Cevap 1)** 

[16,21,11] ---- [8,12,22]

[16] --- [21,11] --- [8,12] --- [22]

[16] --- [21] --- [11] --- [8] --- [12] --- [22]

[16] --- [11,21] --- [8,12] --- [22]

[11,16,21] --- [8,12,22]

[8,11,12,16,21,22]

### **Soru 2)** Big-O gösterimini yazınız.

### **Cevap2)**
 Her satırda n-1 sorgu yapıyoruz bu yüzden time complexityde O(n)'dir. 
 
 Bu O(n) işlemi;
 
 Her satırda dizimizi 2 ye böldüğümüzden;
 
  2^x = n
  
   x = log(n) defa O(n) işlemi yapılıyor dolayısıyla;

   Big-O gösterimi = **nlog(n)**

