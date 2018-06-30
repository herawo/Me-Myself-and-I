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