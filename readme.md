import requests
from bs4 import BeautifulSoup

# LeetCode user profile URL
profile_url = "https://leetcode.com/u/vivek_bhurke/"

# Fetch the profile page
response = requests.get(profile_url)
soup = BeautifulSoup(response.text, 'html.parser')

# Extract rating and badges (example)
rating = soup.find('div', {'class': 'rating'}).text.strip()
badges = [badge.text.strip() for badge in soup.find_all('div', {'class': 'badge'})]

# Update the README.md file
readme_content = f"""
![header](https://user-images.githubusercontent.com/67046306/213246080-9240fb6d-95ab-44a6-ac9e-67fd5d277812.gif)

# Hi there! <img src="https://media.tenor.com/nebZyl8oN7IAAAAj/wave-hello.gif" alt="wave" width="30" height="30" />, I'm Vivek Bhurke
### A passionate Photographer 📸 and Computer Science Student 💻

![camera](https://media.tenor.com/PChygsZkPmMAAAAi/tkthao219-bubududu.gif)

## About Me
I'm a creative soul who loves capturing moments and turning them into art. My passion for photography drives me to explore new techniques and continuously improve my skills. Besides photography, I'm a computer science student who loves diving into new technologies and programming languages.

## 📚 What I'm Currently Learning
🌱 Currently diving into **Java** to expand my technical skillset and explore the world of programming.

## 📫 How to Reach Me
Feel free to reach out via email at: [**vivek_bhurke**](mailto:vivekbhurke863@gmail.com)

## 🌐 Connect With Me
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/vivek__bhurke/)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vivek-bhurke/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourprofile)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/vivek_bhurke/)
[![Facebook](https://img.shields.io/badge/-Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/vivek.bhurke.58)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VivekBhurke)

## 🎨 My Photography Portfolio
[![Portfolio](https://img.shields.io/badge/-Visit%20My%20Portfolio-000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://vivekbhurke.github.io/photographs/)

## ⚙️ Tools & Technologies
![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Photoshop](https://img.shields.io/badge/-Photoshop-31A8FF?style=for-the-badge&logo=adobe-photoshop&logoColor=white)
![Lightroom](https://img.shields.io/badge/-Lightroom-31A8FF?style=for-the-badge&logo=adobe-lightroom&logoColor=white)
![Illustrator](https://img.shields.io/badge/-Illustrator-FF9A00?style=for-the-badge&logo=adobe-illustrator&logoColor=white)

## 📊 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=VivekBhurke&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=VivekBhurke&layout=compact&theme=radical)

## 💡 LeetCode Profile
[![LeetCode Profile](https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/vivek_bhurke/)

### My LeetCode Stats
- **Rating**: {rating}
- **Badges**:
"""

for badge in badges:
    readme_content += f"  - ![Badge](https://via.placeholder.com/20/FFA116/FFFFFF?text={badge})\n"

readme_content += """
## 🎉 Fun Fact
Did you know? The world's oldest known photograph was taken by Joseph Nicéphore Niépce in 1826, and it took 8 hours to expose!

## 📸 My Photographs
<div align="center">
  <a href="https://66689af97dad032680682fa4--vbphotography.netlify.app/" target="_blank"><img src="https://via.placeholder.com/800x400?text=Photo+1" alt="Photo 1" width="400"></a>
  <a href="https://66689af97dad032680682fa4--vbphotography.netlify.app/" target="_blank"><img src="https://via.placeholder.com/800x400?text=Photo+2" alt="Photo 2" width="400"></a>
  <a href="https://66689af97dad032680682fa4--vbphotography.netlify.app/" target="_blank"><img src="https://via.placeholder.com/800x400?text=Photo+3" alt="Photo 3" width="400"></a>
  <a href="https://66689af97dad032680682fa4--vbphotography.netlify.app/" target="_blank"><img src="https://via.placeholder.com/800x400?text=Photo+4" alt="Photo 4" width="400"></a>
</div>
"""

# Write to README.md
with open('README.md', 'w') as f:
    f.write(readme_content)
