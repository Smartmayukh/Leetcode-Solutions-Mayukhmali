## Vector 

- Simple Binary to Decimal Conversion
 ![image](https://user-images.githubusercontent.com/64318469/181866456-57ed3a26-f6f0-407e-9306-b3e6b0697173.png)
- Remember about the difference between erase and remove in vector stl.
   - remove(vec.begin(), vec.end(), 20); -------------- removes all elements of value 20
   - erase returns a iterator and is useful to remove single elements
- Merging two sorted arrays
   - Watch this video https://www.youtube.com/watch?v=P1Ic85RarKY
   ![image](https://user-images.githubusercontent.com/64318469/181933747-ff1e281f-59e0-45d6-a4ef-e32d92788b6f.png)
- BuildIn functions
  - __builtin_popcount(x) //number of ones
  - __builtin_parity(x)
  - __builtin_clz(n)) //for leading zeroes
- We can use this trick also to find out number of ones
  ![image](https://user-images.githubusercontent.com/64318469/182005134-d0049a95-5858-497a-84f1-d77652afa441.png)
  ![image](https://user-images.githubusercontent.com/64318469/182005176-0219f25a-17f5-4e0d-9de9-64a21683008c.png)
- Finding non duplicate element using Bitwise Xor (Question asked in Analog Device Interview to me)
 ![image](https://user-images.githubusercontent.com/64318469/182005024-2dd800cd-36fa-4870-94e9-9051b6d5522f.png)
- std::back_inserter constructs a back-insert iterator that inserts new elements at the end of the container to which it is applied. It is defined inside the header file 
![image](https://user-images.githubusercontent.com/64318469/184277719-f88d8bf1-a732-478c-b96d-efc28f50c745.png)

- Finding missing element in an array when the size of the array indicates the maximum value.
This is a very interesting problem. What we will do is that we will negate the values contained in the index, index representing the number present. So finally all the positive indexes will give us which number is absent. Very cool problem.

![image](https://user-images.githubusercontent.com/64318469/184497529-0843f03e-662e-4730-a957-30c150d4655b.png)
