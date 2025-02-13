**Key point**:
Binary Search + 2D array

**Tips**:

1. Edge case:
   if (matrix == null || matrix[0].length == 0 || matrix.length == 0) return false;

2. int end = m \* n **- 1**;

3. Get the mid number:
   int m = matrix[0].length;

int mid = matrix[mid / m][mid % m]

**Similar problem**: 704. Binary Search
