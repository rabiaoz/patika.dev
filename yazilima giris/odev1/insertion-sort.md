# Insertion Sort 
[22,27,16,22,18,6]
##### 1. Insertion'a göre çözümü;
1.[22,27,16,22,18,6] 

2.[2,27,16,22,18,6]

3.[2,6,16,22,18,27]

4.[2,6,16,18,22,27]

##### 2. Big O Gösterimi;
n+(n-1)+(n-2)...+1 = n*(n+1)/2 = (n^2+n)/2
katsayılar önemli değil 
O(n^2)

##### 3. 18 için Time Complexity;
Ararken karşımıza ilk olarak da son olarak da çıkmadığı için best case veya worst case değil. Average case. 

##### 4. [7,3,5,8,2,9,4,15,6]
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
 
