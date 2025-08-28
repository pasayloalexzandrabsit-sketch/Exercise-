# Exercise-

public class Main {
    public static void main(String[] args) {
    int Num1 = 30;
    int Num2 = 20;
    int result;

    if (Num1 > Num2) {  
    result = Num1 - Num2;
    System.out.println("Num1 is greater, we subtract: " + result);
  
  } else if (Num1 < Num2) {  
    result = Num1 + Num2;
    System.out.println("Num2 is greater, we add: " + result);
  
  } else {  
    result = Num1 * Num2;
    System.out.println("Num1 and Num2 are equal, we multiply: " + result);
    }
  }
}