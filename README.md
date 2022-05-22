# Sorting_Egitim_Patika
patika.dev sıralama (Insertion - Merge - Binary) ödevleri

# Insertion Sort
## Array -> [22,27,16,2,18,6]
- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]

Big O -> O(n^2)

## Linear Search ->
Best Case: O(n)
Average Case: O(n^2)
Worst Case: O(n^2)

18 in Average Case

## Array -> [7,3,5,8,2,9,4,15,6]
- [2,3,5,8,7,9,4,15,6]
- [2,3,5,8,7,9,4,15,6] (any number which smaller than 3 no change)
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,8,7,9,5,15,6] (any number which smaller than 4 no change)
- [2,3,4,5,7,9,8,15,6]

# Merge Sort

## Array -> [16,21,11,8,12,22]
- [16,21,11] [8,12,22]
- [16,21] [11] [8,12] [22]
- [16] [21] [11] [8] [12] [22]
- [16,21] [11] [8,12] [22]
- [11,16,21] [8,12,22]
- [8,11,12,16,21,22]

Each step -> O(n)
Step count -> O(logn)
Big O -> O(nlogn)

# Binary Search

## Array -> [7,5,1,8,3,6,0,9,4,2]
Sorted -> [1,2,3,4,5,6,7,8,9]
[Tree's Root]
      5
   3  |  7
  2 4 | 6 8
 1         9

