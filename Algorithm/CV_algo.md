import [Developer](Developer.md);
import [Experience](Experience.md);
import [Project](Project.md);

```
public class MeMyselfAndI {

    public static void main(String[] args) {
        Developer me = new Developer("Clément", "Alexis", "Herawo", new Date(1997,9,5), "France", "Grenoble", "Web app Developer");
        
        Experience exp1 = new Experience(16, "GFI");
        exp1.addMission("Developement on e-Exam");
        exp1.addMission("Developement on e-Exam Kiosk");
        exp1.addMission("Virtual Machine deployment");
        
        me.addExperience(exp1);
        
        Experience exp2 = new Experience(12, "Algoo");
        exp2.addMission("Developement on Tracim");
        exp2.addMission("Collaboration on Preview-generator");
        exp2.addMission("Continuous Integration on Preview-generator free library");
        
        me.addExperience(exp2);
        
        Experience exp3 = new Experience(4, "RemadeInFrance");
        exp2.addMission("IOS Screen testing");
        
        me.addExperience(exp3);
                
    }
    
}
```