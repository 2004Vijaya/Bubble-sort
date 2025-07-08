# Bubble-sort

'''
5 3 8 4 6
3 5 8 4 6
3 5 8 4 6
3 5 4 8 6
3 5 4 6 8 
3 5 4 6 8

3 4 5 6 8
3 4 5 6 8
3 4 5 6 8

*****Algorithm*****
1.start from the beginning of the array
2.compare each pair to adjacent number
3.if adjacent number is grater than first element then  perform swap with it
4.repeat the process till n-1 elements
5.after each cycle/pass largest unsorted element would be in correct position
6. repeat passes till all the elements are sorted


#pseudocode
for i=0 to n-1:
for j=0 to n-i-2:
if a[j]>a[j+1]
swap(a[j],a[j+1])

'''
