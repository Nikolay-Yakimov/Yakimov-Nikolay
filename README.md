@Component

public class ItIsMyStory {

    private final String name = "Nikolay Yakimov";
    private int age = 39;
    private final String address = "Svishtov 3 str., Sofia, Bulgaria";
    private final String hobby = "Enthusiast Developer";

    public String education() {
        return "Graduate with a master’s degree at University of Forestry";
    }

    public String experience() {
        return "I have many years of experience in various fields";

    }


    public String skills() {
        return "Perfectionist, analysing and optimising for the best possible performance and result";

    }


    public List interests() {
        return List.of("Java", "Spring", "Spring Security", "MySQL", "Thymeleaf" "HTML5", "CSS", "Bootstrap");
    }

    @NotNull
    public String contactWithMe() {
        return "yakimov099@gmail.com";
    }

    @Override
    public String toString() {
        return "Thank you!";
    }
}
   
