# Hi, my name's Noè
![](https://github.com/noe-vhh/noe-vhh/blob/main/IMG_8891.gif)
    
    public class GitHubProfile {
        private String username;
    
        public GitHubProfile(String username) {
            this.username = username;
        }
    
        public String bio() {
            return String.format(
                "- Born 🇳🇱 | Raised 🇿🇦%n" +
                "- BCom IT Management student 🎓%n" +
                "- Aspiring Honours & Master's in AI 🚀%n" +
                "- Exploring the binary brilliance of code and management synergy 💾%n" +
                "- A running enthusiast, because coding marathons aren't enough! 🏃‍♀️%n" +
                "- Undercover nerd 🤓%n" +
                "- 😅 OCD level: Perfectly aligned code and logically sorted study notes%n" +
                "- #TechEnthusiast #CodeCrafting #RunningGeek"
            );
        }
    
        public static void main(String[] args) {
            GitHubProfile myProfile = new GitHubProfile("noe-vhh");
            System.out.println(myProfile.bio());
        }
    }
