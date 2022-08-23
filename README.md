## Pseudocode
  
  
  ```python
  
  InsertionSort(int[] arr)

    FOR i = 1 to arr.length

      int j <-- i - 1
      int temp <-- arr[i]

      WHILE j >= 0 AND temp < arr[j]
        arr[j + 1] <-- arr[j]
        j <-- j - 1

      arr[j + 1] <-- temp
      ```
      
      Loop though the array
      
      
Pass 1:
[8,4,23,42,16,15]


Pass 2:
[8,4,23,42,16,15]


Pass 3:


Pass 4:


