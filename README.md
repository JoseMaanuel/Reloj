# Reloj
package reloj;


public class Reloj {

   
    public static void main(String[] args) {
        int hr=0, m=0, s=0;
        
        while(hr<=22){
          System.out.println(hr+":"+m+":"+s);
            hr++; m=0;
  
        while(m<=58){
          System.out.println(hr+":"+m+":"+s);
            m++;  s=0;
 
        while(s<=59){
          System.out.println(hr+":"+m+":"+s);
            s++;
        
    }
   }  
  }
          
    }
    
}
