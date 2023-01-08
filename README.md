# Merge-Sort-Project-www.patika.dev
Merge Sort Project
[16,21,11,8,12,22] -> Merge Sort

First, the array is divided into half as follows:
[16,21,11] - [8,12,22]

Then, we divide them into half again:
[16,21] [11] - [8,12] [22]

We do the same again:
[16] [21] [11] - [8] [12] [22]

After, we compare the elements and combine them in a sorted way:
[11,16,21] - [8,12,22]

Lastly, we combine the last two sorted half arrays and combine them again in order:
[8,11,12,16,21,22]

Here is the final product:
[8,11,12,16,21,22]

Big-o notation of this merge sort:
n processes, n/2 processes, n/4 processes, and so on.

Big-o notation = o (n log n)
