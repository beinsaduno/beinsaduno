```java
package gitHub.todorKrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {
    private static final String ABOUT_ME = """
                Technologies: Java (advanced), JavaScript (advanced), C++ (basics), Python (basics), SQL, HTML, CSS
                Skills: OOP & SOLID, Data Structures & Algorithms
                Education: Software Engineering (studying now), Master of Finance, Bachelor of Economics
                Interests: Data Science, Algorithms and Algorithm Engineering
                """;
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
