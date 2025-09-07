    import java.util.Scanner;


    public class Debug {
   
        public static void main(String[] args) {
        
            Scanner sc = new Scanner(System.in); //The scanner was named sc and used to capture the users input
            System.out.println("How old are you"); 
            String input = sc.nextLine(); //I stored the user’s age in a string variable called input
            System.out.println("I am " + input + " years old."); // This prints out the users age back to them
        
            int num1 = 55;
            int num2 = 81;
            System.out.println(num1 + num2);
            //Comment: I learned how to use a Scanner to take user input, store values inside variables, and then print them back out.  I also learned how to perform addition in Java.
        
        }  
       
    }
