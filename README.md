def generate_github_profile_readme():
    name = input("Enter your name: ")
    username = input("Enter your GitHub username: ")
    current_position = input("Enter your current position/title: ")
    bio = input("Enter a short bio about yourself: ")

    readme_content = f"""# Hi there, I'm {name}! 👋

I'm a {current_position} passionate about {your_interests}.

- 🌱 I’m currently learning {your_learning_focus}.
- 👯 I’m looking to collaborate on {projects_you_want_to_collaborate_on}.
- 💬 Ask me about {topics_you_can_help_with}.
- 📫 How to reach me: {your_contact_information}.

Connect with me:
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link={your_linkedin_profile_link})]({your_linkedin_profile_link})
[![Twitter](https://img.shields.io/badge/-Twitter-blue?style=flat-square&logo=Twitter&logoColor=white&link={your_twitter_profile_link})]({your_twitter_profile_link})

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id={username}.{username})
"""

    # Save the generated content to README.md
    with open("README.md", "w") as readme_file:
        readme_file.write(readme_content)

    print("GitHub profile README.md generated successfully.")

if __name__ == "__main__":
    generate_github_profile_readme()
# 0mm7.readmegenrator
