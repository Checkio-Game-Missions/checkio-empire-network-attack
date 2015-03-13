**Optional Goals**

**Rank 2**: Channels are secured too. If `matrix[i][j] == matrix[j][i] == N` and `N > 1`, 
then the virus need N-1 minutes to use this channel.

_Precondition Rank 2_:

```
all(0 <= matrix[i][j] < 10 for i in range(len(matrix)) for j in range(len(matrix)) if i != j)
```
