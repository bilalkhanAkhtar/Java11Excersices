**Java 11 Features**

* Can directly run java file using single command**  
Example : java Example.java  
(No need to first compile file using javac command)  

* New methods to String
  1) isBlank()  - check if string is empty or only whitespaces  
   String test1 = "Ganesh";  
   System.out.println(test1.isBlank()); //returns false  

     String test2 = "";    
     System.out.println(test2.isBlank()); //returns true   
   
   2) lines()  - get lines from a file/paragraph  
    String test3 = "Ganesh is Java Developer.\n He also has experience on UI technologies.";     
    ArrayList<String> linesList = test3.lines().collect(Collectors.toList()));  
    System.out.println(lineList.size());  // returns 2  
    Systm.out.println(linesList);   
    
      //prints  
      Ganesh is Java Developer.  
      He also has experience on UI technologies.  
      
   3) strip(), stripLeading(), stripTrailing()   – removes whitespaces from respective or both ends  
      Examples  
      
      String test4 = " Ganesh is Developer "  
      
      System.out.println(test4.strip()); //prints "GaneshisDeveloper"  
      System.out.println(test4.strip()); //prints "GaneshisDeveloper "     
      System.out.println(test4.strip()); //prints " GaneshisDeveloper"   
     
     
   4) repeat(int)  - repeats string given number of times  
    String test4 = "Ganesh"
    System.out.println(tet4.repeat(2));  
    //prints - Ganesh Ganesh  
    
* Local varibale type declaration in Lambda functions  
Example - (var s1, var s2) -> s1 + s2  
This is useful to be used with annotations.
    
   

