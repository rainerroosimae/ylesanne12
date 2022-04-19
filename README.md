# ylesanne12

public class ylesanne12 {

	public static void main(String[] args) {
		int[] a = { 1,3,5,3,1 }; //korduste arv
		int[] b = {5, 4, 3, 2, 1}; //korduste arv
		int[] c = {1, 2, 3, 4, 5}; //korduste arv
		int[] d = {5, 4, 3, 2, 1, 1, 2, 3, 4, 5}; //korduste arv

		for (int i = 0; i < a.length; i++) { // esimene tsükkel
			System.out.println("*".repeat(a[i])); // väljaprint
		}
		for (int j = 0; j < b.length; j++) { // teine tsükkel
			System.out.println("*".repeat(b[j])); //väljaprint
			}
		for (int k = 0; k < c.length; k++) { //kolmas tsükkel
			System.out.println("*".repeat(c[k])); //väljaprint
			}
		for (int l = 0; l < d.length; l++) { //neljas tsükkel
			System.out.println("*".repeat(d[l])); //väljaprint
			}
		}
}
