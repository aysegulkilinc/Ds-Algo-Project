# Ds-Algo-Project


**Proje 1**

[22,27,16,2,18,6]

*1- Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.*

 *Answer:*

   Step 1: [22,27,16,2,18,6] <br>
   Step 2: [16,22,27,2,18,6] &nbsp; *n+(n-1)* <br>
   Step 3: [2,16,22,27,18,6] &nbsp; *n+(n-1)+(n-2)*<br>
   Step 4: [2,16,18,22,27,6] &nbsp; *n+(n-1)+(n-2)+(n-3)*<br>
   Step 5: [2,6,16,18,22,27] &nbsp; *1* <br>

<br>


*2- Big-O gösterimini yazınız.*

*Answer:* n+(n-1)+(n-2)...+1 = n.(n+1)/2 = n^2+n/2 = o(n^2)


<br>

*3- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.*

1. Average Case: Aranan sayının ortada olması
2. Worst Case: Aranan sayının sonda olması
3. Best Case: Aranan sayının dizinin en başında olması

*Answer:* 1. Average Case

*4- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.*

    Step 1: [2,3,5,8,7,9,4,15,6] 
    Step 2: [2,3,4,8,7,9,5,15,6] 
    Step 3: [2,3,4,5,7,9,8,15,6] 
    Step 4: [2,3,4,5,6,9,8,15,7] 

<br>
<br>

**Proje 2**

[16,21,11,8,12,22] -> Merge Sort

*1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.*

Step 1: [16,21,11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,12,22] <br>
Step 2: [16,21] - [11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,12] - [22] <br>
Step 3: [16] - [21] - [11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8] - [12] - [22] <br>
Step 4: [16,21] - [11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,12] - [22] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *o(n)* <br>
Step 5: [11,16,21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,12,22] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *o(n)* <br>
Step 6: [8,11,12,16,21,22]
<br>

*2- Big-O gösterimini yazınız.*

2^x = n <br>
x = log n
o(n) &nbsp;&nbsp;&nbsp; *time complexity* <br>
O(n log n)

