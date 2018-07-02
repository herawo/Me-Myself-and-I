You may also want to see [Main class](MeMyselfAndI.md) [Experience](Experience.md) and [Project](Project.md)

I wrote this in Java because it is one of the most famous and practised langage accross the world, but it's not my speciality.
```
public class Developer{
	private String last_name;
	private String first_name;
	private String username;
	private Date born;
	private String country;
	private String city;
	private String actualjob;
	private List<Experience> experiences;
	private List<Project> projects;

	public Developer(String ln, String fn, String un, Date bd, String co, String ct, String aj){
            last_name = ln;
            first_name = fn;
            username = un;
            born = bd;
            country = co;
            city = ct;
            actualjob = aj;
            experiences = new LinkedList<Experience>();
            projects = new LinkedList<Project>();
	}
        
        public void addExperience(Experience exp){
            experiences.add(exp);
        }
        
        public void addProject(Project pro){
            projects.add(pro);
        }
} 
```