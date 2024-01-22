##Hey, I'm Noè (pronounced No-way 😉)

class GitHubProfile:
    def __init__(self, username="noe-vhh"):
        self.username = username

    def bio(self):
        return f"""
        👩‍💻 {self.username} | BCom IT Management student
        🎓 Aspiring Honours & Master's in AI
        💾 Exploring the binary brilliance of code and management synergy
        🏃‍♀️ Secretly a running enthusiast, because coding marathons aren't enough!
        🤓 Undercover nerd
        😅 OCD level: Perfectly aligned code and logically sorted study notes
        #TechEnthusiast #CodeCrafting #RunningGeek
        """
# Instantiate your GitHub profile
myProfile = GitHubProfile(username="noe-vhh")
# Display the bio
print(myProfile.bio())
