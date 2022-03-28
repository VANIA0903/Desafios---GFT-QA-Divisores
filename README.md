# Desafios---GFT-QA-Divisores
import java.io.IOException;
import java.util.Scanner;

public class DividersI {
  public static void main(String[] args) throws IOException {
    Scanner input = new Scanner(System.in);
    int n;
    n = input.nextInt();
    for (int i = 1; i<=n ; i++) 
      if (n % i == 0) System.out.println(i);
    input.close();
  }
}
