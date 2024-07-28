![siggraph-logo](https://github.com/user-attachments/assets/5f4ddad6-7c64-48a4-ab32-af4ef95a4948)
# Experimenting With Artificial Intelligence: Programming Pathfinding Algorithms in C++ With Unreal Engine 5
## Description
Let’s make something to take back home as a souvenir! Join us in a beginner-friendly lab session on pathfinding algorithms for AI gameplay mechanics. Together, we will visually compare pathfinding algorithms and see them in action as an open-world game.

## Abstract
This hands-on lab session focuses on sharing the art and value of decision-making systems and pathfinding algorithms for machine learning applications. Understanding theoretical frameworks and heuristic strategies is necessary to build a foundational understanding of AI for research, games, and beyond. Through game development, we experience a snippet of AI by visualizing pathfinding algorithms, an entry point to exploring any AI domain.

Together, we visualize the applications and influence of real-time pathfinding through programmatically modeling with Metahumans in Unreal Engine 5 (UE5). This comes together as an open-world game compatible with their preferred platform including WebGL, iOS/Android, and VR headsets. Personal hardware is not required for participation but is recommended for playtesting.

**Links:**
| Name  | Description | Link | 
| ------------- | ------------- | ---- |
| SIGGRAPH Labs Program | Lab session details and information | [SIGGRAPH 2024](https://s2024.conference-program.org/presentation/?id=gensub_250&sess=sess268) |
| Labs Paper | Paper publication link | [ACM DL](https://dl.acm.org/doi/10.1145/3641236.3664419) |
| Course Website | Course website and information | [Webiste](https://makers-of-siggraph24.vercel.app/) |
| Lecture Slides | Tuesday's presentatioin | [Keynote Presentation](https://www.icloud.com/keynote/096aiWD4gmMaO3H6UcYWgKElg#SIGGRAPH%5FFinal} |

## Requirements
  * Unreal Engine:
       * [Unreal Engine 5.4.3](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-5.4-release-notes)
       * [Unreal Neural Network Engine (NNE)](https://dev.epicgames.com/community/learning/courses/e7w/unreal-engine-neural-network-engine-nne/G3rx/unreal-engine-nne-overview-5-3)
       * [MetaHuman Plugin](https://www.unrealengine.com/marketplace/en-US/product/metahuman-plugin)
       * [MetaHuman Creator](https://www.unrealengine.com/en-US/metahuman)
       * [Environment Query System](https://dev.epicgames.com/documentation/en-us/unreal-engine/environment-query-system-overview-in-unreal-engine?application_version=5.4)
  * Other:
       * [Git Large File Storage](https://git-lfs.com/)
       * [Kenny Assets: Survival Kit](https://kenney.nl/assets/survival-kit)
         
## Set Up

Fork or clone the entire repo
```bash
$ git clone https://github.com/debbieyuen/vscode-unityscripting
```

Make sure you have Git and Node.js. Then, install Yeoman and VS Code Extension Generator
```bash
$ npm install -g yo generator-code
```

Install the Axios API for the VSCode Extension
```bash
$ npm install axios
```

Install Fast XML Parser for the VSCode Extension
```bash
$ npm install fast-xml-parser
```

For the Unity project, install Git LFS
```bash
$ git lfs install
```

Within the Unity **Package Manager**, install `Unity Render Streaming` and `WebRTC` via git URL
```bash
com.unity.webrtc@2.4.0-exp.8
com.unity.renderstreaming@3.1.0-exp.6
```

Within the Unity **Render Streaming/ Render Streaming Wizard**, click on the **Download latest version of web app.** button. If you are on a Mac, run the following commands in terminal. 
```bash
chmod +x webserver_mac
./webserver_mac -p 3030
```

Create a new settings asset for Render Streaming and input the signaling type and URL.
<img width="1280" alt="Screenshot 2023-11-05 at 4 39 16 PM" src="https://github.com/debbieyuen/vscode-unityscripting/assets/31296177/6e6b18f0-69f9-4890-87a9-0e3077e79e98">
## Credits and References 
