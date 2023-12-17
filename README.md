# Patika_Dev_Merge_Sort
Patika.dev Data Structures and Algorithms course Merge Sort assignment

Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Solution:

	Data Set: [16,21,11,8,12,22]

	Sorting Algorithm: Merge Sort

	Step 1: Divide the list into two halves.

	[16, 21, 11], [8, 12, 22]

	Step 2: Recursively apply the same process to each half until we have lists of size 1 or less.

	[16], [21, 11], [8], [12, 22]

	Step 3: Combine the sorted sublists from Step 2 in a way that results in a sorted list.

	[8, 11, 16, 21, 22]

	The final result is a sorted version of the original list.

	Big O: O(n*log n)
