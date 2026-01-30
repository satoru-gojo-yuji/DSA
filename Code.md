
Q.1 Pallindrome 

Input: s = "abba"
Output: 1
Explanation: s is a palindrome

Input: s = "abc" 
Output: 0
Explanation: s is not a palindrome


Solve: 

class Main {
    public static void main(String[] args) {
        
        String s ="abbesa" ;
        int left = 0 ;
        int right =s.length()-1;
        int count = 0 ;
        boolean f = true ;
        System.out.print(right);
        
      while(left < right)
      {
        // int  count = 0 ;
          if(s.charAt(left) != s.charAt(right)){
            f = f ;
             break ; 
          }
          left++;
          right--;
          
      }
      if(f)
      System.out.print("palindrom");
      else
      System.out.print("not palindrom");
    }


Q.2 