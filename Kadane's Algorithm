

class Solution{

    // arr: input array
    // n: size of array
    //Function to find the sum of contiguous subarray with maximum sum.
    long maxSubarraySum(int arr[], int n){
        
        // Your code here
        int ms = Integer.MIN_VALUE;
        int cs =0;
        for (int i =0; i<n; i++){
            
            cs += arr[i];
            
            
            ms = Math.max(cs, ms);
            if (cs<0){
                cs = 0;
            }
        }
       return ms;
        
    }
    
}
