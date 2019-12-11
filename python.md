### [heapq - heap queue algorithm](https://docs.python.org/3.0/library/heapq.html)
Heaps are arrarys for which heap[k] <= heap[2*k+1] and heap[k] <= heap[2*k+2] for all k, counting elements from zero. For the sake of comparison, non-existing elements are considered to be infinite. The interesting property of a heap is that heap[0] is always its smallest element.

Functions:<br>
```python
#Push the item onto the heap
heapq.heappush(heap, item)

#Pop and return the smallest item from the heap
heapq.heappop(heap)
```
