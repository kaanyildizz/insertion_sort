# insertion_sort
Insertion_Selection_sort_projesi


Q1-) [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

	1.adım :
		Başlangıçta, ilk iki öğe  karşılaştırılır ve küçük olan başa yazılır. Bu örnek için 22, 27'den küçük olduğu için yerinde kalır. Array'de herhangi bir değişiklik olmaz.
		[22,27,16,2,18,6] --> [22,27,16,2,18,6]
	2.adım :
		Bu adımda bir sonraki ikili olan 27 ve 16 karşılaştırılır ve 16, 27 den küçük olduğu için bu ikili arasında swap gerçekleşir.
		[22,27,16,2,18,6] --> [22,16,27,2,18,6]
		Daha sonra 16 ile 22 karşılaştırılır ve 16, 22 den de küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[22,16,27,2,18,6] --> [16,22,27,2,18,6]
	3.adım : 
		Bu adımda ise yine bir sonraki ikili olan 27 ve 2 karşılaştırılır ve 2, 27 den küçük olduğu için bu ikili arasında swap gerçekleşir.
		[16,22,27,2,18,6] --> [16,22,2,27,18,6]
		Daha sonra 22 ile 2 karşılaştırılır ve 2, 22 den küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[16,22,2,27,18,6] --> [16,2,22,27,18,6]
		Daha sonra 16 ile 2 karşılaştırılır ve 2, 16 dan küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[16,2,22,27,18,6] --> [2,16,22,27,18,6]
	4.adım :
		Bu adımda ise yine bir sonraki ikili olan 27 ve 18 karşılaştırılır ve 18, 27 den küçük olduğu için bu ikili arasında swap gerçekleşir.
		[2,16,22,27,18,6] --> [2,16,22,18,27,6]
		Daha sonra 22 ile 18 karşılaştırılır ve 18, 22 den küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[2,16,22,18,27,6] --> [2,16,18,22,27,6]
	5.adım :
		Son adımda ise son ikili olan 27 ve 6 karşılaştırılır ve 6, 27 den küçük olduğu için bu ikili arasında swap gerçekleşir.
		[2,16,18,22,27,6] ---> [2,16,18,22,6,27]
		Daha sonra 22 ile 6 karşılaştırılır ve 6, 22 den küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[2,16,18,22,6,27] --> [2,16,18,6,22,27]
		Daha sonra 18 ile 6 karşılaştırılır ve 6, 18 den küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[2,16,18,6,22,27] --> [2,16,6,18,22,27]
		Daha sonra 16 ile 6 karşılaştırılır ve 6, 16 den küçük olduğu için bu ikili arasında da swap gerçekleşir.
		[2,16,6,18,22,27] --> [2,6,16,18,22,27]
		
		Insertion Sort sonrası arrayin son hali : [2,6,16,18,22,27]
	
Q2 -)Big-O gösterimini yazınız.

	 Big-O notation: O(n2)

Q3-)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

	1.Average case: Aradığımız sayının ortada olması
	2.Worst case: Aradığımız sayının sonda olması
	3.Best case: Aradığımız sayının dizinin en başında olması.

	Arrayin son hali : 	[2,6,16,18,22,27]
	18 elemanı ortada yer aldığı için sorudaki 1.duruma yani average case durumuna girer.



Q4-)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

	1.adım : [7,3,5,8,2,9,4,15,6]		(n)

	2.adım : [2,3,5,8,7,9,4,15,6]		(n-1)

	3.adım : [2,3,4,8,7,9,5,15,6]		(n-2)

	4.adım : [2,3,4,5,7,9,8,15,6]		(1)


www.patika.dev
