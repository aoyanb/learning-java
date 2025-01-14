# Quick Notes
1. ArrayList is not thread-safe as it is not synchronized. Vector list is thread-safe as its every method is synchronized.
1. ArrayList is better to store and fetch data. LinkedList is better to manipulate data.
1. Set contains unique values whereas Map can contain unique Keys with duplicate values. Set holds a single number of null value whereas Map can include a single null key with n number of null values.
1. HashMap is not synchronized, hence not thread-safe but fast. Hashtable is synchronized, that means thread-safe but slow.

1. The List interface extends the Collection interface and provides additional methods for working with ordered collections, such as getting and setting elements by index.
1. The Set interface extends the Collection interface and provides methods for working with unordered collections that do not allow duplicates.
1. The Map interface represents a collection of key-value pairs and provides methods for working with mappings, such as getting and setting values by key.
1. The Queue interface represents a collection of elements that can be accessed in a specific order, such as a first-in, first-out (FIFO) queue.
1. A Set is an unordered collection that does not allow duplicates, while a List is an ordered collection that allows duplicates. Sets are typically used when uniqueness is important, while Lists are used when the order of elements is important.
1. We can obtain java ArrayList Read-only by calling the Collections.unmodifiableCollection() method. When we define an ArrayList as Read-only then we cannot perform any modification in the collection through  add(), remove() or set() method.