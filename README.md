# question_ONE

public class employee {
   double Salary;
    String Position;
    String employee_Type;
    String Name;
   
    
    int Experience;
    String Educational_Level;
    public employee(String employeeType,String Name,String Position, double Salary,
    int Experience,String Educational_Level)
    {
    Salary = Salary+(Salary*0.5*Experience);
    if(Educational_Level =="Bachelor" ){
           Salary=Salary+500;
    }
         else if(Educational_Level == "diploma")   {


          Salary=Salary+250;
         }
                        
     if(employeeType== "Full time"){
            c Salary=Salary+(Salary*0.03);
     }
          else if(employeeType==  "Part Time") {
           Salary=Salary+(Salary*0.015);
                        }
  }
    
}
