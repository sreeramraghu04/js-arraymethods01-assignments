# JavaScript Array Methods 01

## assignment

1. Write short notes on Array methods with code examples.

   - push()
    - push method adds a new element at the end of the array
    - push method modifies the original array

    ```js
    const arr = [1, 2, 3];
    arr.push(4);
    console.log(arr); // Output: [1, 2, 3, 4]
    ```
    ---
- pop()
    - pop method removes the last element from the array
    - pop method modifies the original array

    ```js
    const arr = [1, 2, 3];
    arr.pop();
    console.log(arr); // Output: [1, 2]
    ```
    ---
- shift()
    - shift method removes the first element from the array
    - shift method modifies the original array

    ```js
    const arr = [1, 2, 3];
    arr.shift();
    console.log(arr); // Output: [2, 3]
    ```
    ---
- unshift()
    - unshift method adds a new element at the beginning of the array
    - unshift method modifies the original array

    ```js
    const arr = [1, 2, 3];
    arr.unshift(0);
    console.log(arr); // Output: [0, 1, 2, 3]
    ```
    ---
- includes()
    - includes method returns true if the array contains the specified element
    - includes method returns false if the array does not contain the specified element

    ```js
    const arr = [1, 2, 3];
    console.log(arr.includes(2)); // Output: true
    console.log(arr.includes(4)); // Output: false
    ```
    ---
- toString()
    - toString method returns a string representation of the array 
    - toString method returns a comma-separated list of the elements in the array

    ```js
    const arr = [1, 2, 3];
    console.log(arr.toString()); // Output: "1,2,3"
    ```
    ---
- reverse()
    - reverse method reverses the order of the elements in the array
    - reverse method modifies the original array

    ```js
    const arr = [1, 2, 3];
    arr.reverse();
    console.log(arr); // Output: [3, 2, 1]
    ```
    ---
- join()
    - join method returns a string representation of the array
    - join method returns a comma-separated list of the elements in the array

    ```js
    const arr = [1, 2, 3];
    console.log(arr.join()); // Output: "1,2,3"
    console.log(arr.join("-")); // Output: "1-2-3"
    ```
    ---
- concat()
    - concat method returns a new array containing the elements of the original array followed by the elements of the specified array
    - concat method does not modify the original array

    ```js
    const arr1 = [1, 2, 3];
    const arr2 = [4, 5, 6];
    console.log(arr1.concat(arr2)); // Output: [1, 2, 3, 4, 5, 6]
    ```
    ---
- flat()
    - flat method returns a new array with all sub-array elements concatenated into it recursively up to the specified depth
    - flat method does not modify the original array

    ```js
    const arr = [1, 2, [3, 4], [5, [6, 7]]];
    console.log(arr.flat()); // Output: [1, 2, 3, 4, 5, 6, 7]
    ```
    ---
- slice()
    - slice method returns a new array containing the elements of the original array from the start index up to but not including the end index
    - slice method does not modify the original array

    ```js
    const arr = [1, 2, 3, 4, 5];
    console.log(arr.slice(1, 4)); // Output: [2, 3, 4]
    ```
    ---
- splice()
    - splice method modifies the original array by removing or replacing elements
    - splice method returns an array containing the removed elements

    ```js
    const arr = [1, 2, 3, 4, 5];
    console.log(arr.splice(1, 3)); // Output: [2, 3, 4]
    ```
    ---
- sort()
    - sort method sorts the elements of the array in place and returns the array
    - sort method modifies the original array

    ```js
    const arr = [4, 2, 1, 3];
    console.log(arr.sort()); // Output: [1, 2, 3, 4]
    ```
    ---
- fill()
    - fill method modifies the original array by filling it with a specified value
    - fill method returns the original array

    ```js
    const arr = [1, 2, 3];
    console.log(arr.fill(0)); // Output: [0, 0, 0]
    console.log(arr.fill(10,1,2)); // Output: [0, 10, 0]
    ```
    ---
