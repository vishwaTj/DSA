# DSA
prctc
 Step 1: make a matrix of m[wt.length+1][maxWeight+1]
 step 2: Start a loop to fill it, if i==0 (i.e weights selected is 0 then mat[i][j]=0).
 step 3: if(wt[i-1]<=j) weight is less than j weight of column,take max of( i) without including value dp[i-1][j] and
    ii) with including the value dp[i-1][j-wt[i-1]]+val[i-1].
 step 4: if new wt is more then just copy previos value.
