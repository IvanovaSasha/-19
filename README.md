# -19
практическая 18
public class Pr1819 { 
    public static void main(String[] args) { 
        Scanner system = new Scanner(System.in); 
        System.out.print("Введите значе6ние х: "); 
        double x = system.nextDouble(); 
        System.out.print("Введитек значение y: "); 
        double y = system.nextDouble(); 
 
if (x>0 & y>0) { 
     System.out.println("I четверть"); 
} else if (x<0 & y>0) { 
     System.out.println("II четверть"); 
} else if (x<0 & y<0) { 
     System.out.println("III четверть"); 
} else if (x>0 & y<0) { 
     System.out.println("IV четверть"); 
