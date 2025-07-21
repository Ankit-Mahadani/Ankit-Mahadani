<!-- Animated header with typing effect -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=00F7FF&width=435&lines=Hi+there+👋;I'm+ANKIT+MAHADANI;CSE+Student+@VIT+Bhopal;Python%2FC%2B%2B+Developer;Problem+Solver" alt="Typing SVG" />
</div>

<!-- Wave animation -->
<div align="center">
  <img src="https://github.com/rahuldkjain/github-profile-readme-generator/blob/master/src/images/icons/Social/wave.gif" width="30px">
</div>

# 💫 About Me:
🎯 Passionate CSE student pushing boundaries in coding and problem-solving<br>
🌱 Currently mastering <img src="https://img.shields.io/badge/-Unreal_Engine-0E1128?style=flat&logo=unreal-engine" height="18"> & <img src="https://img.shields.io/badge/-Cybersecurity-3A7D44?style=flat&logo=cybersecurity" height="18"><br>
💡 Fun fact: Came 3rd in a hackathon!<br>
📫 How to reach me: **ankitmahadani181@gmail.com**

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankitmahadani/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ankitmahadani181@gmail.com)
[![GFG](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/user/ankitmahadani/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ankit-Mahadani)

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=plastic&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54)
![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=plastic&logo=unrealengine&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=plastic&logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=plastic&logo=git&logoColor=white)

# 📊 GFG 3D Stats Visualization:
```python
# GFG Stats 3D Visualization (Example)
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D

categories = ['Arrays', 'Strings', 'Trees', 'Graphs', 'DP']
solved = [45, 38, 27, 32, 19]  # Update with your actual GFG stats
colors = ['#FF6B6B', '#4ECDC4', '#45B7D1', '#FFA07A', '#98D8C8']

fig = plt.figure(figsize=(10, 7))
ax = fig.add_subplot(111, projection='3d')

# Create bars
for i, (cat, val, col) in enumerate(zip(categories, solved, colors)):
    ax.bar3d(i, 0, 0, 0.6, 0.6, val, color=col, alpha=0.8)

ax.set_title('My GFG Problem Solving Stats', fontweight='bold')
ax.set_ylabel('')
ax.set_zlabel('Problems Solved')
ax.set_xticks([i + 0.3 for i in range(len(categories))])
ax.set_xticklabels(categories, rotation=20)
ax.view_init(25, -45)

plt.tight_layout()
plt.show()
