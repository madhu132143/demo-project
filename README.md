# demo-madhu-akhia
import java.util.Scanner;

if>public class LoginModule {
    public static void main(String[] args) {
        String username, password;
        
        // Predefined credentials
        String correctUsername = "myusername";
        String correctPassword = "mypassword";
        
        // Prompt the user for input
        Scanner input = new Scanner(System.in);
        System.out.print("Username: ");
        username = input.nextLine();
        System.out.print("Password: ");
        password = input.nextLine();
        
        // Check if the input matches the predefined credentials
        if (username.equals(correctUsername) && password.equals(correctPassword)) {
            System.out.println("Login successful!");
        } else {
            System.out.println("Incorrect username or password.");
        }
    }
}
