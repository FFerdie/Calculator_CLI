# Calculator_CLI
Simple calculator
import java.util.*

    piblic class calculator
{
    public static void
        {
            int num1 = 0;
    int num2 = 0;
    char operator;

    double answer = 0.0;

        Scanner scanObject = new Scanner(System.in);


        Sytem.out.println("Enter a value for the number");
    num1 = scanObject.nextint();

        Sytem.out.println("Enter a value for the  second number");
    num2 = scanObject.nextint();
        Sytem.out.println("Enter the operator");
         operator = scanObject.next().charA(0);
    switch (operator)
        {
        case '+':answer = num1+ num2;
         case '+':answer = num1 - num2;                         
        case '+':answer = num1 * num2;
        case '+':answer = num1 / num2;
        break;
        }

}
}
