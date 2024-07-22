import java.util.Scanner;
import java.lang.*;

public class exp {
    public static void main(String[] args) {
        int length,height,breadth,volume,totalArea;
        
        System.out.println("Enter the height,length and breadth of a cuboid:");
        Scanner sc = new Scanner(System.in);
        length = sc.nextInt();
        breadth = sc.nextInt();
        height = sc.nextInt();
        
        volume = (length*breadth*height);
        totalArea = 2*((length*breadth) + (breadth*height) + (height*length));
        
        System.out.println("The volume of a cuboid: "+volume);
        System.out.println("The Area of a cuboid: "+totalArea);
    }
    
}
