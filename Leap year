public class LeapYearCalculator
{
    public static void main(String args[])
    {
 
        /*Give the year here which needs to be checked for leap year
         * (Assuming that year given here  >= 1582 and corresponds to a year in Gregorian calendar)
         */
        int year = 2000;
 
        //Flag to store the test result
        boolean isLeapYear = false;
 
        if(year % 400 == 0)
        {
            isLeapYear = true;
        }
        else if (year % 100 == 0)
        {
            isLeapYear = false;
        }
        else if(year % 4 == 0)
        {
            isLeapYear = true;
        }
        else
        {
            isLeapYear = false;
        }
 
        //Output the test result
        if(isLeapYear)
        {
            System.out.println("Year "+year+" is a Leap Year");
        }
        else
        {
            System.out.println("Year "+year+" is not a Leap Year");
        }
 
    }
}
