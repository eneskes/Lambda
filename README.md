# Lambda
import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;

public class Lambda {
    public static void main(String[] args) {
     List<Integer> sayi = new ArrayList<>(Arrays.asList(34, 22, 16, 11, 35, 20, 63, 21, 65, 44, 66, 64, 81, 38, 15));

        printElStuructured(sayi);
        System.out.println("\n   ***   ");
        printElFunctional(sayi);}
  public static void printElStuructured(List<Integer> sayi) {
        for (Integer w : sayi) {
            System.out.print(w + " ");
        }
    }
   public static void printElFunctional(List<Integer> sayi) {
        sayi.stream().forEach(t -> System.out.print(t + " "));
    }}
