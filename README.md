
## Find Pairs API

### ​Endpoint: /find-pairs

```
​- Method: POST
​- Accepts a JSON object
```
 
Request Body
```
{
 "numbers": [1, 2, 3, 4, 5],
 "target": 6
}
```

Response Body
```
{
 "solutions": [
   [0, 4],
   [1, 3]
 ]
}
```

### ​Edge Cases:

- The array might contain duplicate numbers.
- The target might not match the sum of any two elements in the array.
- ​The array might be empty.
​
## ​Validation:

- ​The API should validate the input to ensure that the numbers array contains only integers and the target is an integer.
- ​If the input is invalid, the API should return an appropriate error message with a 400 status code.
