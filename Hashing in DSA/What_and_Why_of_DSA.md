### So, Hashing is a type of Data Structure widely used for storage, retreival and sorting of data as fast as possible.


<br>

# What is Hashing??
The process of taking any size of data and then converting that into smaller data value which can be named as hash value. This hash vHashing is the process of transforming any given key or a string of characters into another value. This is usually represented by a shorter, fixed-length value or key that represents and makes it easier to find or employ the original string.
The most popular use for hashing is the implementation of hash tables. A hash table stores key and value pairs in a list that is accessible through its index. Because key and value pairs are unlimited, the hash function will map the keys to the table size. A hash value then becomes the index for a specific element.

A hash function generates new values according to a mathematical hashing algorithm, known as a hash value or simply a hash. To prevent the conversion of hash back into the original key, a good hash always uses a one-way hashing algorithm.
Hashing is relevant to -- but not limited to -- data indexing and retrieval, digital signatures, cybersecurity and cryptography. alue can be used in an index accessible in hash table. This process define hashing in data structure.


<br>


# Why Hashing is used??
One can oberve sthat the time complexity for searching, inserting, or deleting any element in a balanced binary search tree is O. (logn). There may come a time when our programmes wish to perform the same tasks faster, that is, more efficiently, and this is where hashing comes into play. All of the aforementioned operations in hashing may be completed in O(1), or constant time. It's crucial to realise that while the average case time complexity for hashing is O(1), the worst case time complexity is still O(n).

<br>

# Basic Components of Hashing ??
1) Hash Table: An array that holds indices to records linked to a certain phone number. If no existing phone number has a hash function value equal to the entry's index, the item in the hash table is NIL. Simply put, we might argue that an array is a generalisation of a hash table. A hash table provides the ability to store a group of data in a form that makes it simple to locate those things later, if necessary. As a result, searching for an element is quite effective.

2) A hash function transforms a large phone number into a tiny, usable integer value. In a hash table, the mapped integer value serves as an index. So, to put it simply, a hash function is utilised to convert a given key into a certain slot index. Its major task is to convert each and every key into a distinct slot index. The hash function is referred to as a perfect hash function if each key maps to a distinct slot index.


