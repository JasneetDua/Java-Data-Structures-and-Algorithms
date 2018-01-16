<!-- section start -->

<!-- attr: {id: 'title', class: 'slide-title', hasScriptWrapper: true} -->

# Linear Data Structures
<div class="signature">
    <p class="signature-course">Java Fundamentals - Part 1</p>
    <p class="signature-initiative">Telerik School Academy</p>
    <a href="http://academy.telerik.com" class="signature-link">http://academy.telerik.com</a>
</div>

<!-- section start -->

<!-- attr: {id: 'table-of-contents'} -->
# Table of Contents

- Linear Data Structures
    - `ArrayList`
    - `LinkedList`
    - `Queue`
    - `Stack`
    - `Deque`

<!-- section start -->

<!-- attr: {class: 'slide-section'} -->

# ArrayList<T>
## Automatically resizable array

# ArrayList<T>

- ArrayList<T> is like a resizable array
    - Elements can be added or removed dynamically
- Usefull methods:
    - `add(value)`
    - `remove(int)`
    - `remove(T)`
    - `removeIf(Predicate<T>)`
    - `contains(T)`
    - `sort(Func<T, T, int>)`
- All methods work with at least O(n) complexity
    -   Except `add()`

<!-- attr: {class: 'slide-section'} -->
# LinkedList<T>
## Fast insert and remove at start and end

<!-- attr: {hasScriptWrapper: true} -->
# LinkedList<T>

- LinkedList<T> in a standard implementation of the <a href="https://en.wikipedia.org/wiki/Linked_list">LinkedList abstract data type</a>
- Usefull methods:
    - `addFirst(value)`, `addLast(value)`
    - `removeFirst(T)`, `removeLast(T)`
    - `removeIf(Predicate<T>)`
    - `sort(Func<T, T, int>)`
- `addFirst()`, `addLast()`, `removeFirst()` and `removeLast()` work with complexity `O(1)`


<!-- attr: {class: 'slide-section'} -->
# Queue<T>
## Fast insert at the back, fast remove from front

<!-- attr: {hasScriptWrapper: true} -->
# Queue<T>

- Queue<T> in a standard implementation of the <a href="https://en.wikipedia.org/wiki/Queue_(abstract_data_type)">Queue abstract data type</a>
    - Just an interface in Java
    - Implementation is in `LinkedList<T>`
- Usefull methods:
    - `offer(value)`
        - same as `add(value)`
    - `peek()`
    - `poll()`
    
- All methods work with `O(1)` complexity


<!-- attr: {class: 'slide-section'} -->
# Stack<T>
## Fast insert at the front, fast remove from front

<!-- attr: {hasScriptWrapper: true} -->
# Stack<T>

- Stack<T> in a standard implementation of the <a href="https://en.wikipedia.org/wiki/Stack_(abstract_data_type)">Stack abstract data type</a>
- Usefull methods:
    - `push(value)`
        - same as `add(value)`
    - `pop()`
    - `peek()`
    
- All methods work with `O(1)` complexity


<!-- attr: {class: 'slide-section'} -->
# Deque<T>
## Fast insert at the front and back, fast remove from front and back

<!-- attr: {hasScriptWrapper: true} -->
# Deque<T>

- Deque is also known as double-ended queue
- Usefull methods:
    - `offerFirst(value)`, `offerLast(value)`
    - `pollFirst()`, `pollLast()`
    - `peek()`
    
- All methods work with `O(1)` complexity

<!-- section start -->

<!-- attr: { class:'slide-section' }
# Linear Data Structures
##  Questions
