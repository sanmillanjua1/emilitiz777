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
    
    int rand1 = Math.random(array1);
    
    int rand2 = Math.random(array2);
    
    int rand2 = Math.random(array3);
    
    System.out.print( rand1 + " " + rand2 + " " + rand3);
  }
}
