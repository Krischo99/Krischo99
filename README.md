class Programmer {

    public static void main(String[] args){
        // Personal data
        String name = "Kristiyan Nikolov";
        int bornYear = 1999;
        String residence = "Plovdiv";

        // Education
        String[] education = {
            "SoftUni Java Fundamentals - Grade: 6",
            "SoftUni Java Advanced - Grade: 6",
            "Current course: SoftUni Java Advanced"
        };
        int experienceInYears = 1;

        // Technical skills
        String[] technicalSkills = {
            "Java", "Spring Boot", "Swing", "JavaFX", "Maven",
            "HTTP Requests", "Python", "Tkinter", "JavaScript"
        };

        // Tools
        String[] tools = {
            "IntelliJ IDEA","VSCode"
        };

        // Future Goals
        String[] futureGoals = {
            "Gain experience working with databases, mobile applications and and build on my previous knowledge"
        };

        // Display the information
        System.out.println("Resume of " + name);
        System.out.println("Year of birth: " + bornYear);
        System.out.println("Residence: " + residence);
        System.out.println("Education:");
        for (String edu : education) {
            System.out.println("- " + edu);
        }
        System.out.println("Accumulation of knowledge and experience in years: " + experienceInYears);

        // Formating all informaction
        System.out.println("Technical skills:");
        for (String skill : technicalSkills) {
            System.out.println("- " + skill);
        }
        System.out.println("Tools: ");
        for (String tool : tools) {
            System.out.println("- " + tool);
        }
        System.out.println("Current goals: ");
        for (String goal : futureGoals) {
            System.out.println("- " + goal);
        }
    }
}
