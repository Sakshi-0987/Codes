# Codes


    /*
    Electricity bill problem
    Given an integer input A which represents units of elctricity consumed at your house.
    calculate and print the bill amount
    
    unit <= 100 : price per unit is 1
    unit > 100 : price per unit is 2

    Example: 
    input : 50
    output : 50 * 1 = 50

    input : 200 
    output : 200 * 2 = 400
    */

    /* 
    If units are <= 100 print (unit * 1)
    if units are > 100 print ( 100*1 + (unit-100)*2)
    */
    
    import java.util.*;

    class Main {

    public static void main(String[] args) {

    Scanner scn = new Scanner (System.in);
    int units = scn.nextInt();
    if (units <= 100) {
        System.out.print(units*1);
    }
    else {
        System.out.print(100*1 + (units-100)*2 );
    }
    }
    }
    
