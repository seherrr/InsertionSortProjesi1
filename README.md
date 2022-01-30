# Insertion Sort Projesi
## [22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
+ İlk olarak sayı öbeğimin en küçük elemanını arıyoruz(2) ve en küçük elemanı bulduktan sonra en başa yazıyoruz.En başta olan 22 ile 2'nin yerini değiştiriyoruz.  
[2,27,16,22,18,6]
+ En küçüğü sabit tutup ikinci eleman için kalan sayı öbeğinden en küçük elemanı yazıyoruz.  
[2,6,16,22,18,27]
+ Bundan sonraki aşamalarda da aynı şekilde devam ediyoruz.  
[2,6,16,18,22,27]

2. Big-O gösterimi
+ [22,27,16,2,18,6] ->n
+ [2,27,16,22,18,6] ->n-1
+ [2,6,16,22,18,27] ->n-2
+ [2,6,16,18,22,27] ->1

3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
+ Aradığımız sayı ortada olduğu için Average case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
