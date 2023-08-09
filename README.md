# question_one


public class employee {
    String empType;
    String Name;
    String Position;
    int Experience;
    String Edu_Level;
    float Salary;
   
    public employee(double s)
    {
    Salary = s+(s*0.5*Experience);
    
     switch(empType){
            case"Full time":
             Salary=Salary+(Salary*0.03);
             break;

            case "Part Time":
              Salary=Salary+(Salary*0.015);
              break;
                        }
        switch(Edu_Level){
            case"Bachelor" :
             Salary=Salary+500;
             break;
            case "diploma":
            Salary=Salary+250;
            break;
                        }
  }
    
}
