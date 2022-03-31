@Component

public class HelloGit👋  {

   private String name = "Nikolay Yakimov";
   
   private short age = 37;
   
   private String address = "Svishtov 3 str., Sofia, Bulgaria";
   
   private String proffesion = "Enthusiast Developer";
   
  
👨‍🎓 public String education() {

    return "Graduate with a master’s degree at University of Forestry";
   }

🖥 public String experience() {

    return "I have many years of experience in various fields";
   }
  
🛠 public String skills() {

    return "Perfectionist, analysing and optimising for the best possible performance and result";
   }

🌎 public List<String> interests() {
   
    return List.of("Java", "Spring", "MySQL", "HTML5", "CSS", "Bootstrap");
   }

ℹ️ public void moreInfo() {
   
    System.out.println("");
   }

   @NotNull
   
📬 public String contactMe() {
   
    return "Love to make new friends and learn new things every day...";
   
   }

   @Override
   
🏡 public String toString() {
   
    return "Thank you!";
   
   }
   
}
   
