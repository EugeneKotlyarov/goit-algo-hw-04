Нижче наведено порівняльні показники швидкості троьх алгоритмів на різних об'ємах даних.
Очевидно, що для 10 елементів, будь-який алгоритм впорається дуже швидко, 
але вже починаючі зі 100 елементів Timsort працює на 1 порядок швидше ніж сортування "Злиттям", 
та на 2 і більше порядків ніж "Вставками"

Array size: 10
├──Insertion sort time: 0.000005 seconds
├──Merge sort time:     0.000012 seconds
└──Timsort time:        0.000001 seconds

Array size: 100
├──Insertion sort time: 0.000100 seconds
├──Merge sort time:     0.000070 seconds
└──Timsort time:        0.000008 seconds

Array size: 1000
├──Insertion sort time: 0.011966 seconds
├──Merge sort time:     0.000888 seconds
└──Timsort time:        0.000076 seconds

Array size: 5000
├──Insertion sort time: 0.301811 seconds
├──Merge sort time:     0.005671 seconds
└──Timsort time:        0.000523 seconds