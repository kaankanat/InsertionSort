<h3>[22,27,16,2,18,6] -> Insertion Sort <br>
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</h3>
Algoritmanın üyelerinin değişmediği aşamaları yazmadan, sadece değiştiği üyelerin yer değiştirdiği aşamaları yazarsak:

* [22,27,16,2,18,6]
* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,18,22,27]

<h3>2.Big-O gösterimini yazınız.</h3>
Normalde Insertion Sort algoritmasında n<sup>2</sup> yaparak Big-O gösterimini bulabiliriz. Fakat normalde n<sup>2</sup> dominant olduğu için n<sup>2</sup>'yi alırız. Bu örnekte ise sadece 6 tane üyemiz bulunduğu için ((n<sup>2</sup>)+n)/2 ile daha net bir sonuç bulabiliriz.<br>
((6*6)+6)/2=<b>21</b>

<h3>3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.</h3>

* Best Case: 2 
* Average Case: 16, 18 
* Worst Case: 27

<h3>4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.</h3>
Dizinin ortasında bulunduğu için <b>Average Case</b> kapsamına girer.

<h3>[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.</h3>

Algoritmanın üyelerinin değişmediği aşamaları yazmadan, sadece değiştiği üyelerin yer değiştirdiği aşamaları yazarsak:

* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]
* [2,3,4,5,6,9,8,15,7]
