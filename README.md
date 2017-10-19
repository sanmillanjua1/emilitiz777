# emilitiz777
import java.util.Scanner;

public class phraseMatic
{
  
  private phraseMatic()
  {
    String[] array1 = { "Cycle", "Test", "Process" , "Estabalize", "Reset", "Change", "Recycle"};
    
    String[] array2 = { "magnesium", "calcium", "phosphate-exporting methods", "nitrate-exporting methods",
      "anaerobic bacterias", "alkalinity", "PH"};
    
    String[] array3 = { "to estabilize nutrient export", "to estabilize nutrient to nutrient interactions", 
      "to buffer the waters acidity", "to promote iodine estability", "to promote bacterial growth"};
    
    int oneLength = array1.length; 
    int twoLength = array2.length; 
    int threeLength = array3.length;
    
    double rand1 = Math.random() * oneLength;
    
    double rand2 = Math.random() * twoLength;
    
    double rand3 = Math.random() * oneLength;
    
    System.out.print( rand1 + " " + rand2 + " " + rand3);
  }
}
