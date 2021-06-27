# Deque

![](image.png)

* Deque or Double Ended Queue is a type of [queue](https://www.programiz.com/dsa/queue) in which insertion and removal of elements can either be performed from the front or the rear. Thus, it does not follow FIFO rule (First In First Out).
* types of deques

  * **Input Restricted Deque** : In this deque, input is restricted at a single end but allows deletion at both the ends.
  * **Output Restricted Deque** : In this deque, output is restricted at a single end but allows insertion at both the ends.
* operations:

  * insert
    * at front
    * at rear
  * delete
    * from front
    * from rear
  * isEmpty
  * isFull
* The time complexity of all the above operations is constant i.e. `O(1)`.
* applications

  * In undo operations on software.
  * To store history in browsers.
  * For implementing both [stacks](https://www.programiz.com/dsa/stack) and [queues](https://www.programiz.com/dsa/queue).
