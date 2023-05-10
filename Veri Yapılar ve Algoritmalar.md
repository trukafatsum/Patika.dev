
#	Insertion (Selection) Sort Proje

## Proje 1

> [22,27,16,2,18,6] -> Insertion Sort
>>	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

*	[22,27,16,2,18,6] n
*	[2,27,16,22,18,6] n-1
*	[2,6,16,22,18,27] n-2
*	[2,6,16,22,18,27] n-3
*	[2,6,16,18,22,27] n-4
*	[2,6,16,18,22,27] 1


> __Big-O gösterimini yazınız.__

n+(n-1)+(n-2)+(n-3)+(n-4)+1 = [n.(n+1)]2 = (n^2+n)/2

O(n^2)

> Time Complexity: Dizi sıralandıktan sonra __18__ sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Sıralandıktan sonra : __18 -> Avarage Case__ | 27 -> Worst Case | 2 -> Best Case

> [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

* __[7,3,5,8,2,9,4,15,6]__

* [2,3,5,8,7,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]

#	Merge Sort Proje

## Proje 2

> [16,21,11,8,12,22] -> Merge Sort
>> Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

*	[16,21,11] [8,12,22]
*	[16] [21,11] [8,12] [22]
*	[16] [21] [11] [8] [12] [22]
*	[16] [11,21] [8,12] [22]
*	[11,16,21] [8,12,22]
*	[8,11,12,16,21,22]

> Big-O gösterimini yazınız.

2^x = n

x = logn

__O(nlogn)__
