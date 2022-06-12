- 👋 Hi, I’m @DecodeHimanshu
- 👀 I’m interested in ... coding
- 🌱 I’m currently learning ... DSA

public class Main
{
	public static void main(String[] args) {
		System.out.println("Maxmum sub Arrays :: ");
	  int a[] = new int[]{1,2,3};
	  int n = a.length;
    //method 1st O(n^3)
	  for(int i=0;i<n;i++){
	      for(int j=i;j<n;j++){
	          for(int k=i;k<=j;k++){
	              System.out.print(a[k]+" ");
	          }
	          System.out.println();
	      }
	  }
	}
}

