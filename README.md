import java.util.Arrays;
public class Main {
    public static void main(String[] args) {
        int[] a={1,2,3,1,3,2,2,1,2,2,1,3};
        Arrays.sort(a);
        System.out.println(Arrays.toString(a));
        int n=a.length;
        int c=1;
        for(int i=0;i<n-2;i++){
            if(a[i]==a[i+1]){
                c++;
            }
            else{
                 System.out.println(a[i]+"->"+c);
                 c=1;
            }
        }
       
    }
}
