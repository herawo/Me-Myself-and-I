You may also want to see [Developer](Developer.md) [Main class](MeMyselfAndI.md) and [Project](Project.md)

I wrote this in Java because it is one of the most famous and practised langage accross the world, but it's not my speciality.
```
public class Experience {
    private int length;
    private String group;
    private List<String> missions;
    
    public Experience(int le, String gr){
        length = le;
        group = gr;
        missions = new LinkedList<String>();
    }
    
    public void addMission(String mis){
        missions.add(mis);
    }
}
```