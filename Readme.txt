http://javastudy.ru/junit/junit-hello-world/

package study;

public class Task1 {
	int[] arr;
	static int sum = 0;
	static int x = 14501;
	
	
	
	public static void main(String[] args) {
		while(x != 0) {
			sum += x%10;
			x /= 10;
		}
		System.out.print(sum);
	}
	
}