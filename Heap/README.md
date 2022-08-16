- Return the maximum value of (nums[i]-1)*(nums[j]-1). We will use Min Heap for this question. Remember the corresponding STLs -  push, pop,top.

![image](https://user-images.githubusercontent.com/64318469/182067548-99b1656a-dcbd-4363-a356-b3c54e782ccf.png)

- Stone Game, Choose two heaviest stone hit them, if they are of the same weight; both gets destroyed; else the smaller one gets destroyed and takes chunk from larger stone. Return the final stone if any and its weight.

![image](https://user-images.githubusercontent.com/64318469/182120255-d845c719-4025-4eb8-8185-f92ee2c003ba.png)

- Sorting Odd and Even digits of number in place

![image](https://user-images.githubusercontent.com/64318469/182163125-ec368e9f-c8d3-44a0-bd50-eac21a73f773.png)

- Assign rank based on score

![image](https://user-images.githubusercontent.com/64318469/182188705-3696f6bc-a154-43ee-8877-564778f49456.png)

- K weakest row

![image](https://user-images.githubusercontent.com/64318469/182280473-3fc71404-1cb1-4382-b8e5-92ec826c8d16.png)

The above approach can be improved by using binary search to find number of leading ones

![image](https://user-images.githubusercontent.com/64318469/182282589-8d9585c2-630f-4789-9a88-33574231d891.png)

- Filling cups problem. My heap solution

![image](https://user-images.githubusercontent.com/64318469/182291297-711d7422-5a25-4be2-bec9-e9eeb875863d.png)

Alternatively I found this logic very interesting

![image](https://user-images.githubusercontent.com/64318469/182291401-11f2a427-b4c7-4ba7-b44a-0e6405cbb13f.png)
![image](https://user-images.githubusercontent.com/64318469/182291416-c3df5b73-accf-478a-ac35-66f9ac57685e.png)

- K closest point to the origin

![image](https://user-images.githubusercontent.com/64318469/182343146-ef1f1d51-2641-450f-9e47-1b43638cf24f.png)

A good alternate solution will be using partial sort and a homemade comparator function

![image](https://user-images.githubusercontent.com/64318469/182344167-9f0bac5d-34c6-43b4-9a08-b9b227b6bff2.png)

- K most frequent elements. 
We can do bucket sort or use min heap. Below are both of the solutions.

![image](https://user-images.githubusercontent.com/64318469/184776899-9b84b239-2fba-4224-89ed-04de58d378d1.png)

![image](https://user-images.githubusercontent.com/64318469/184779198-ff2d897d-93d7-4b0c-b01f-aa93b24253b9.png)



