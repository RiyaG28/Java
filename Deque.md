The **Deque** interface of the Java collections framework provides the functionality of a **double-ended queue**. It extends the **Queue** interface.

**Classes that Implement Deque:**

In order to use the functionalities of the **Deque** interface, we need to use classes that implement it:

-   ArrayDeque
-   LinkedList

In a regular **queue**, elements are added from the rear and removed from the front. However, in a **deque**, we can **insert and remove elements from both front and rear.**

In **Java,** we must import the **java.util.Deque** package to use **Deque**.

**Syntax:**

**Deque<String> names= new ArrayDeque<>();**

Tha above statement creates a **Deque** of Strings, we can now push and remove Strings from this deque easily.

**Methods of Deque:**

-   **offerFirst()**  - Adds the specified element at the beginning of the deque. Returns false if the deque is full.
-   **offerLast()**  - Adds the specified element at the end of the deque. Returns false if the deque is full.
-   **peekFirst()**  - Returns the first element of the deque. Returns null if the deque is empty.
-   **peekLast()**  - Returns the last element of the deque. Returns null if the deque is empty.
-   **pollFirst()**  - Returns and removes the first element of the deque. Returns null if the deque is empty.
-   **pollLast()**  - Returns and removes the last element of the deque. Returns null if the deque is empty.
-   **addFirst()**  - Adds the specified element at the beginning of the deque. Throws an exception if the deque is full.
-   **addLast()**  - Adds the specified element at the end of the deque. Throws an exception if the deque is full.
-   **getFirst()**  - Returns the first element of the deque. Throws an exception if the deque is empty.
-   **getLast()**  - Returns the last element of the deque. Throws an exception if the deque is empty.
-   **removeFirst()**  - Returns and removes the first element of the deque. Throws an exception if the deque is empty.
-   **removeLast()**  - Returns and removes the last element of the deque. Throws an exception if the deque is empty.
-   **size() -** Return an integer denoting the total number of elements in the deque at present.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwOTQ3MjI0NjBdfQ==
-->