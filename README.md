import java.util.Scanner;
class Main {
  public void read(){
    Scanner object = new Scanner(System.in);
    Int year = object.nextLine();
  }
  public void bResut_ActionPerformed(Action evt){
    read();
    if (year%4==0){
      if (year%100==0){
        if (year%400==0){
          System.out.println("The year " + year + " ist a leap year);
        } else {
          System.out.println("The year " + year + " ist not a leap year);
        }
      } else {
        System.out.println("The year " + year + " ist a leap year);
      }
    } else {
       System.out.println("The year " + year + " ist not a leap year);
    }
  }
}
          
          
