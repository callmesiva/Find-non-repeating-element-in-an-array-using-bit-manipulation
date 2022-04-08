# Find-non-repeating-element-in-array-using-bit-manipulation

     int arr[]  ={2,3,4,5,2,3,4};
     int rep =0;
     
     for(int i=0; i<arr.length; i++)
     {
       rep = rep^arr[i];
     }
     System.out.println(rep);
       
