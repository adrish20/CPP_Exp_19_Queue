<h1>Aim</h1>
<p>To study and implement queue using array.</p>
<hr>
<h1>Software Used</h1>
<p>VS code</p>
<hr>
<h1>Theory</h1>
<p>A queue in C++ can be implemented using an array and follows the First In, First Out (FIFO) principle. It has two key operations: <code>enqueue</code> (inserting an element at the rear) and <code>dequeue</code> (removing an element from the front). The array stores the elements, and two index variables, <code>front</code> and <code>rear</code>, are used to track the front and rear positions of the queue. When an element is enqueued, it's added to the rear, and when dequeued, the element is removed from the front. To avoid overflow (if the queue is full) and underflow (if the queue is empty), proper checks are implemented. Circular queues can also be used to optimize space.</p>
<hr>
<h1>Algorithms</h1>
<h2>Queue using STL</h2>
<ol>
        <li><b>Start</b></li>
        <li>Initialize an empty queue <code>q</code> of integers.</li>
        <li>Push the value <code>30</code> onto the queue.</li>
        <li>Push the value <code>20</code> onto the queue.</li>
        <li>Push the value <code>10</code> onto the queue.</li>
        <li>Print the front element of the queue before pop (Output: 30).</li>
        <li>Remove the front element from the queue using <code>pop()</code>.</li>
        <li>Print the new front element after pop (Output: 20).</li>
        <li><b>End</b></li>
</ol>
<hr>
<h2>Queue Implementation in Array</h2>
<ol>
        <li><b>Start</b></li>
        <li>Define the <b>Queue</b> class with attributes <code>capacity</code>, <code>front</code>, <code>rear</code>, and a dynamic array <code>arr</code>.</li>
        <li>Initialize the queue with a constructor that sets <code>front</code> and <code>rear</code> to -1 and allocates memory based on the capacity.</li>
        <li>Define the following methods:
            <ul>
                <li><b>push()</b>: Add an element to the queue if it's not full; initialize <code>front</code> if the queue was empty.</li>
                <li><b>pop()</b>: Remove the front element from the queue if it's not empty; reset <code>front</code> and <code>rear</code> if there's only one element left.</li>
                <li><b>peek()</b>: Return the front element of the queue if it's not empty; otherwise, return -1.</li>
            </ul>
        </li>
        <li>In the main function, create a queue <code>q</code> with a capacity of 5.</li>
        <li>Push the elements 10, 20, and 30 onto the queue.</li>
        <li>Print the front element using <b>peek()</b> (Output: 10).</li>
        <li>Remove the front element using <b>pop()</b>.</li>
        <li>Print the new front element after pop (Output: 20).</li>
        <li><b>End</b></li>
</ol>
<hr>
<h1>Conclusion</h1>
<p>In conclusion, C++ codes to implement queue using STL and in array was successfully written and executed.</p>
