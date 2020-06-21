# BS\_Notes

**High Level:**

1\) Search in a **sorted** sequence for a target;

2\) Time: O\(logn\);

3）Space: O\(1\)

**Method:**

1\) Corner case checking;

2\) Set two pointers:

```text
  left = 0
  right = len(array) - 1
```

3\) Set a while loop:

```text
Three kinds:
  i)   left <= right:     check every single elements;
  ii)  left < right - 1:  remain 2 elements; 
  iii) left < right :     remain 1 element.
```

4\) mid = \(left + right\) // 2;

5\) post-processing if needed 

