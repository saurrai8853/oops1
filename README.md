# oops1
package mypackage;
class Majdur {
	String name;
	String role;
	double Salary;
  
	void display(String name) {
		System.out.println(name);
	}
	void display1(String role) {
		System.out.println(role);
	}
	void display2(double Salary) {
		System.out.println(Salary);
	}
}class majdur2 {
	String name;
	String role;
	double Salary;
  
	void display(String name) {
		System.out.println(name);
	}
	void display1(String role) {
		System.out.println(role);
	}
	void display2(double Salary) {
		System.out.println(Salary);
	}
}
public class Oops{
	public static void main(String args[]) {
		Majdur majdur=new Majdur();
		majdur.display("rahul");
		majdur.display("painting");
		majdur.display2(14000);
		Majdur majdur2=new Majdur();
		majdur2.display("aman");
		majdur2.display("carpainting");
		majdur2.display2(12000);
	}
}
