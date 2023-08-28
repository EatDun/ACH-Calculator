import java.lang.Math;
import java.util.Scanner;

class HelloWorld {
    
    public static double achCalc(double cfmI, double hcvI) {
        return (cfmI * 60) / hcvI;
    }
    
    public static void main(String[] args) {
        
        Scanner cfmInput = new Scanner(System.in);
        
        System.out.println("Please enter CFM");
        
        double cfm = cfmInput.nextDouble();
        
        Scanner hcvInput = new Scanner(System.in);
        
        System.out.println("\nPlease enter HCV");
        
        double hcv = hcvInput.nextDouble();
        
        double ach = achCalc(cfm, hcv);
        
        System.out.println("\nAir changes per hour at 50 pascal pressure differential is " + ach);
    }
}
