# sort-o_CrabbyChips

* Crabby Chips: Lauren Lee and Diana Akhmedova
* APCS pd8
* Lab 04
* 2022-01-10
* Time Spent: 1.0 hrs
* SOTW: Are You Bored Yet? by Wallows

## Best and Worst Case Scenario for Each
### Bubble Sort:
* Best: [1, 1, 1, 1, 1]
        [1, 2, 3, 4, 5]
* Total Swaps: 0

* Worst: [5, 4, 3, 2, 1]
* Total Swaps: 10
### Selection Sort:
* Best: [1, 2, 3, 4, 5]
* Total Swaps: 0
* Total Comparisons: 15

* Worst: [5, 4, 3, 2, 1]
         [1, 1, 1, 1, 1]
* Total Comparisons: 15
* Total Swaps: 4
### Insertion Sort:
* Best: [1, 1, 1, 1, 1]
        [1, 2, 3, 4, 5]
* Total Comparisons: 10
* Total Swaps: 0

* Worst: [5, 4, 3, 2, 1]
* Total Comparisons: 10
* Total Swaps: 10

## Conclusions
### Arrays Populated of the Same Element
* Bubble Sort and Insertion Sort are more efficient, because they do not require any swaps.
* While in Selection Sort, it requires swaps even though it would not need swaps theoretically.
### Arrays Populated in Ascending Order
* This is the best case scenario for all three sort types, as no swaps are necessary.
* However, Selection Sort the least efficient because it requires the most comparisons.
### Arrays Populated in Descending Order
* This is the worst case scenario for all three sort types, as it requires the most swaps.
* However, Selection Sort is the most efficient because it requires the least swaps, although it does require the most comparisons.
### Final Conclusions
* The most efficient sorts for the best case scenarios were Bubble Sort and Insertion Sort because they required no swaps and fewer comparisons.
* Selection Sort is the most efficient in the worst case scenario because it requires less swaps, but in the best case scenarios it requires more comparisons and sometimes more swaps than necessary.
