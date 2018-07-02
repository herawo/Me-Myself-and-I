You may also want to see [Developer](Developer.md) [Experience](Experience.md) and [Project](Project.md)

I wrote this in Java because it is one of the most famous and practised langage accross the world, but it's not my speciality.
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