1.) Also try with a LinkedList – does it make any difference?
by behavior wise both are same here,but linkedlist is slower

2.)What happens if you use list.remove(Integer.valueOf(77)) instead of i.remove()?
Using list.remove(Integer.valueOf(77)) removes the first occurrence of 77 by value.
Using i.remove() removes the current element from the iterator’s perspective during iteration.

3.) Does containsAll() check order or just content?
containsAll() only checks for the presence of all elements, not their order.

