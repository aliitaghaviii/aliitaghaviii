# Hi there, I'm Ali Taghavi! 👋

- 👀 I’m interested in technology, digital marketing, and Coding.
- 🌱 I’m currently learning Python, script development, and diving deeper into automation.
- 💞️ I’m looking to collaborate on exciting digital projects and innovative marketing campaigns.
- 📫 How to reach me: Connect with me on [**LinkedIn**](https://www.linkedin.com/in/alii-taghaviii/) or drop me an email at [Biztaghavi@outlook.com](mailto:Biztaghavi@outlook.com).


# or

profile_data = {
    "name": "Ali Taghavi",
    "who_i_am": ['Digital Marketer', 'Tech Enthusiast', 'Entrepreneur'],
    "age": 21,
    "nationality": "🇮🇷",
    "contact_info": {
        "linkedin": "https://www.linkedin.com/in/alii-taghaviii/",
        "email": "Biztaghavi@outlook.com"
    }
}

introduction = (
    f"Hi, I'm {profile_data['name']}! 👋\n"
    f"I am a {', '.join(profile_data['who_i_am'])} from {profile_data['nationality']}.\n"
    f"At {profile_data['age']} years old, I'm passionate about technology, digital marketing, and travel.\n"
    f"Let's connect and collaborate on exciting projects! 🚀\n"
    f"How to reach me: Connect with me on [**LinkedIn**]({profile_data['contact_info']['linkedin']}) or drop me an email at [Biztaghavi@outlook.com](mailto:{profile_data['contact_info']['email']})."
)

print(introduction)
