To express n in any base b:

```java
s = empty string
q = n

while q != 0:
	r = q % b
	prepend r to s
	q = truncate(q / b)
```

	
