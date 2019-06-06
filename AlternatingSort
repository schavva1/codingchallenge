public class HelloWorld{

     public static void main(String []args){
       int a[] = {1,3,5,6,4,2};
       int[] temp = new int[a.length];
       //System.out.println("temp length:"+temp.length);
       int low = 0; 
       int high = a.length -1;
       int len = a.length;
       boolean z = true;
       for(int i=0; i < len;i++)
       {
           if(z)
           {
               temp[i] = a[low++];
           }
           else
           {
               temp[i] = a[high--];
           }
           z = !z;
          // System.out.println("low value:"+low);
           //System.out.println("high value:"+high);
           
       }
       
        for(int i=0;i< len-1;i++)
        {
            //System.out.println(temp[i]);
            if( temp[i] > temp[i+1] )
            {
                System.out.println("false");
                break;
            }
            else  if(i != len -2)
            {
                ;
            }
            else
            {
                System.out.println("true");
            }
        }
        
        
        
     }
}
