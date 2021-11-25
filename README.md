import java.util.Scanner;

public class Euclid {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		int a,b;
		
		a = sc.nextInt();
		b = sc.nextInt();
		
		while(a != b) {
			if(a > b) {
				a -= b;
			}else {
				b -= a; 
			}
		}
		sc.close();
		System.out.println(a);
	}

}
