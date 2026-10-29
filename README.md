<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Satyajit%20S&fontSize=70&fontColor=3BA4F2&animation=fadeIn&fontAlignY=38&desc=Robotics%20%E2%80%A2%20Physical%20AI%20%E2%80%A2%20Reinforcement%20Learning&descAlignY=60&descSize=20&descColor=c9d1d9" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=900&color=3BA4F2&center=true&vCenter=true&width=720&lines=Teaching+robots+to+manipulate+the+physical+world;Vision-Language-Action+models+%7C+Imitation+Learning;RL+agents+that+navigate%2C+explore+and+break+games;ROS+2+%E2%80%A2+MoveIt+2+%E2%80%A2+LeRobot+%E2%80%A2+PyTorch" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/Satyajit-147/Satyajit-147/blob/main/Satyajit_S_Resume.pdf">
    <img src="https://img.shields.io/badge/Resume-View%20PDF-3BA4F2?style=for-the-badge&logo=readthedocs&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/satyajit06/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:satyajitgr9@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=Satyajit-147&style=for-the-badge&color=2c5364&label=PROFILE+VIEWS"/>
</p>

<br/>

<!-- ===================== ABOUT ===================== -->
## `> whoami`

```python
class Satyajit:
    def __init__(self):
        self.role       = "B.Tech CSE @ IIITDM Kancheepuram (2024 - 2028)"
        self.cgpa       = 8.90
        self.focus      = ["Robotic Manipulation", "Control & Teleoperation", "Physical AI"]
        self.methods    = ["Reinforcement Learning", "Imitation Learning", "VLA Models"]
        self.robots     = ["SO-101 bimanual arms", "5-DOF rover arm", "Holonomic bot", "TurtleBot3"]
        self.currently  = "Training a PPO + Go-Explore agent that hunts bugs in Doom levels"

    def mission(self):
        return "Robots that learn from demonstration and generalise beyond it."
```

<br/>

<!-- ===================== HIGHLIGHTS ===================== -->
## `> highlights`

<table>
  <tr>
    <td align="center" width="25%">
      <h3>🏛️</h3>
      <b>Research Intern</b><br/>
      <sub>e-Yantra (eYSIP), IIT Bombay</sub>
    </td>
    <td align="center" width="25%">
      <h3>🏆</h3>
      <b>Top 20 / 300+</b><br/>
      <sub>e-Yantra Robotics Competition</sub>
    </td>
    <td align="center" width="25%">
      <h3>🚀</h3>
      <b>10th Worldwide</b><br/>
      <sub>International Rover Challenge</sub>
    </td>
    <td align="center" width="25%">
      <h3>🤖</h3>
      <b>4 VLA Policies</b><br/>
      <sub>ACT • SmolVLA • π0 • GR00T</sub>
    </td>
  </tr>
</table>

<br/>

<!-- ===================== EXPERIENCE ===================== -->
## `> experience`

<details open>
<summary><b>🔬 Robotics Research Intern</b> &nbsp;|&nbsp; e-Yantra, IIT Bombay &nbsp;|&nbsp; <i>May 2026 - Jul 2026</i></summary>
<br/>

- Selected for the **eYSIP** research programme on the strength of a top-20 national finish in e-Yantra
- Trained and benchmarked **four Vision-Language-Action policies** (ACT, SmolVLA, π0, GR00T) on **SO-101 bimanual arms** with **LeRobot**, comparing task success across architectures
- Collected expert demonstration datasets and deployed policies on bimanual stacking, precision pick-and-place, and arranging markers and cups

</details>

<details open>
<summary><b>🛰️ Software Team Member</b> &nbsp;|&nbsp; MaRS Student Rover Society, IIITDM &nbsp;|&nbsp; <i>Jan 2025 - Present</i></summary>
<br/>

- Built a **Cartesian control pipeline** for a custom 5-DOF manipulator with **MoveIt 2**: the operator drives the end-effector directly while IK resolves joint angles
- Used the arm for teleoperated panel tasks (buttons, switches, levers) needing precise end-effector positioning at distance
- Part of the rover software stack that placed **10th at the International Rover Challenge**

</details>

<br/>

<!-- ===================== PROJECTS ===================== -->
## `> projects`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎮 RL-Based QA Tester for Games</h3>
      <sub><i>Research &nbsp;•&nbsp; Oct 2026 - Present &nbsp;•&nbsp; 🟢 in progress</i></sub>
      <p>
        A declarative map spec compiles to a playable UDMF Doom level plus ground-truth JSON. Six game-agnostic oracle families detect injected defects inside ViZDoom, while a <b>PPO</b> agent with <b>count-based curiosity</b> and <b>Go-Explore</b> resets hunts for them, scored on precision and recall.
      </p>
      <img src="https://img.shields.io/badge/ViZDoom-8B0000?style=flat-square"/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/PPO-444?style=flat-square"/>
      <img src="https://img.shields.io/badge/Go--Explore-444?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🧭 TD3-based Autonav</h3>
      <sub><i>RL Navigation &nbsp;•&nbsp; Sep 2026 - Oct 2026</i></sub>
      <p>
        <b>TD3</b> agent for TurtleBot3 maze navigation in Gazebo using LiDAR and relative-goal observations with <b>BFS geodesic reward shaping</b>. Trained on one maze, transfers to unseen layouts without retraining. <b>~98% success</b> on the training map.
      </p>
      <img src="https://img.shields.io/badge/ROS%202%20Humble-22314E?style=flat-square&logo=ros&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gazebo-242938?style=flat-square"/>
      <img src="https://img.shields.io/badge/Stable--Baselines3-444?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🦾 Bimanual VLA Manipulation</h3>
      <sub><i>eYSIP, IIT Bombay &nbsp;•&nbsp; May 2026 - Jul 2026</i></sub>
      <p>
        Imitation learning on <b>SO-101</b> bimanual arms: teleoperated demo collection, then training and head-to-head benchmarking of <b>ACT, SmolVLA, π0 and GR00T</b> on stacking and precision pick-and-place.
      </p>
      <img src="https://img.shields.io/badge/LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
      <img src="https://img.shields.io/badge/VLA-444?style=flat-square"/>
      <img src="https://img.shields.io/badge/Imitation%20Learning-444?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🛞 Autonomous Holonomic Bot</h3>
      <sub><i>e-Yantra Robotics Competition &nbsp;•&nbsp; Sep 2025 - May 2026</i></sub>
      <p>
        <b>Top 20 of 300+ teams</b> after six months of national qualifiers. PID-controlled omnidirectional drive for trajectory tracking and docking, with an <b>ArUco</b> pose-estimation pipeline driving automated pick-and-place of crates.
      </p>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
      <img src="https://img.shields.io/badge/PID-444?style=flat-square"/>
      <img src="https://img.shields.io/badge/ArUco-444?style=flat-square"/>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/Satyajit-147?tab=repositories">
    <img src="https://img.shields.io/badge/See%20all%20repositories-121011?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<br/>

<!-- ===================== TECH STACK ===================== -->
## `> tech_stack`

<p align="center"><b>Robotics & Control</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ros&theme=dark"/>
  <br/>
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nav2-22314E?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MoveIt%202-102230?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Gazebo-242938?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RViz%202-3A3A3A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MuJoCo-0B5394?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/slam__toolbox-3A3A3A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LeRobot-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

<p align="center"><b>ML & Computer Vision</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn&theme=dark"/>
  <br/>
  <img src="https://img.shields.io/badge/Stable--Baselines3-444?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logoColor=black"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

<p align="center"><b>Languages & Tools</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,c,js,linux,docker,git,github&theme=dark"/>
</p>

<p align="center"><b>Also comfortable with</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,postgres,sqlite,html,css&theme=dark&perline=7"/>
</p>

<br/>

<!-- ===================== STATS ===================== -->
## `> activity`

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Satyajit-147&theme=tokyonight&hide_border=true&background=0D1117&ring=3BA4F2&fire=3BA4F2&currStreakLabel=3BA4F2" width="70%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Satyajit-147&bg_color=0D1117&color=c9d1d9&line=3BA4F2&point=ffffff&area=true&area_color=3BA4F2&hide_border=true&custom_title=Contribution%20Graph" width="100%"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Satyajit-147/Satyajit-147/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Satyajit-147/Satyajit-147/output/github-snake.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/Satyajit-147/Satyajit-147/output/github-snake-dark.svg"/>
  </picture>
</p>

<br/>

<!-- ===================== CONNECT ===================== -->
## `> connect`

<p align="center">
  Open to <b>robotics / physical AI research internships</b> and collaborations on manipulation, RL and VLA work.<br/>
  If you are building robots that learn, let's talk.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satyajit06/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:satyajitgr9@gmail.com"><img src="https://img.shields.io/badge/satyajitgr9@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Satyajit-147/Satyajit-147/blob/main/Satyajit_S_Resume.pdf"><img src="https://img.shields.io/badge/Download%20Resume-3BA4F2?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>
</p>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>
</p>
