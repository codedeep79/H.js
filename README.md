# H.js
H Language's parser  
## Example:
```js
print_range = ^(a, b) 
                if a <= b {
                  print(a);
                  if a + 1 <= b {
                    print(", ");
                    print_range(a + 1, b);
                  } else 
                      println(""); 
                  }; 
               print_range(1, 10);
```
