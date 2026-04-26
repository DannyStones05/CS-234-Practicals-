public class ProfileCard {
   public static void main(String[] args){
    //Student's Name 
    String name = "Daniel Livingstone";
    //Student's ID
    String studentID = "2024-04-04513";
    //Current Year of study
    String study_year = "2nd Year";
    //Prior programming experiance and background
    String background = "I know Html, CS, and JavaScript  \n              have build a small web projects ";
    //Student goal for the course
    String goal = "I want to build a Java app\n              to the end of this course.";
    //Interest Student's fun fact
    String funFact = "I can solve a Sudoku game \n              in few minutes.";

    //Borders
    String heavyLine = "=============================================";
    String lightLine= "---------------------------------------------";

    //Print the profile card
    System.out.println(heavyLine);
    System.out.println("      CS  234  - JAVA PROFILE CARD    ");
    System.out.println(heavyLine);
    System.out.println("Name        : " + name);
    System.out.println("Student ID  : " + studentID);   
    System.out.println("Year        : " + study_year);
    System.out.println(lightLine);
    System.out.println("Background  : " + background);
    System.out.println(lightLine);
    System.out.println("Goal        : " + goal);
    System.out.println(lightLine);
    System.out.println("Fun Fact    : " + funFact);
    System.out.println(heavyLine);

   }
}
