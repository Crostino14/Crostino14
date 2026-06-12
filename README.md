<p align="center">
  <img src="https://capsule-render.vercel.app/api?font=JetBrains+Mono&type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Agostino%20Cardamone&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer&descAlignY=58&descSize=18&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&multiline=false&repeat=true&width=720&lines=MSc+Computer+Engineering+%E2%80%94+AI+%26+Intelligent+Robotics" alt="Typing SVG" />
  </a>
</p>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People%20with%20professions/Man%20Technologist%20Light%20Skin%20Tone.png" width="28" /> About me

I am a **Artificial Intelligence Engineer** with a Master of Science in Computer Engineering (AI & Intelligent Robotics) from the **University of Salerno**. I'm passionate about **automotive technologies** and **robotics**.

<p align="center">
  📌 Based in Cava de Tirreni, Campania, Italy
</p>


## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="26" /> Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cs,java,postgresql,matlab&theme=dark&perline=6" /><br/>
  <sub><b>Languages</b></sub>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark&perline=6" /><br/>
  <sub><b>Machine Learning / Computer Vision Frameworks</b></sub>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,ros,docker,git,vscode,visualstudio&theme=dark&perline=6" /><br/>
  <sub><b>Robotics, DevOps & Tooling</b></sub>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgresql,latex,bash&theme=dark&perline=6" /><br/>
  <sub><b>Data, Databases & Scientific Computing</b></sub>
</p>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="26" /> Main Projects

<details>
<summary><b>🤖 Zero-Shot Generalization Evaluation of State-of-the-Art VLA Models</b> &nbsp;·&nbsp; <i>MSc Thesis — 2025/2026</i></summary>
<br/>

Controlled and reproducible evaluation framework developed as part of the Master's thesis
(University of Salerno), designed to assess zero-shot generalization of
Vision-Language-Action (VLA) models on robotic manipulation tasks. The benchmark covers
two generalization axes: **Syntactic Generalization** (verb substitution, syntactic
restructuring, compositional spatial reference) and **Task-Level Generalization**
(cross-object skill transfer, novel task composition), structured into levels of
increasing difficulty on the LIBERO-Goal suite. Three state-of-the-art VLA models with
distinct pre-training paradigms were evaluated: **OpenVLA-OFT**, **TinyVLA**, and
**InternVLA-M1**, with targeted fine-tuning of InternVLA-M1 to mitigate catastrophic
forgetting at the hardest compositional spatial reference level.

| Attribute | Details |
|---|---|
| **Stack** | Python · PyTorch · LIBERO · LeRobot · OpenVLA-OFT · TinyVLA · InternVLA-M1 (Qwen2.5-VL + DiT-B) · LoRA · SLURM (HPC) |
| **Scale** | Multi-GPU HPC (H100) · SLURM cluster · 3 VLA models benchmarked |
| **Methodology** | Zero-shot evaluation · 2-axis generalization taxonomy · 6 difficulty levels · controlled episode testing |
| **Fine-Tuning** | Selective parameter freeze · LoRA · DDP with `find_unused_parameters=True` |
| **Repository** | [github.com/Crostino14/Evaluating-Generalization-of-Sota-VLA](https://github.com/Crostino14/Evaluating-Generalization-of-Sota-VLA) |

</details>


<details>
<summary><b>🚗 Cone-Guided Autonomous Navigation via ROS 2 and TurtleBot 4</b> &nbsp;·&nbsp; <i>Jul–Sep 2025</i></summary>
<br/>

Autonomous indoor navigation system developed in ROS 2 on a TurtleBot 4 platform, as
part of the Mobile Robots for Critical Missions course. The robot is tasked with reaching
a target location via the shortest feasible path, complying with directional constraints
imposed by colour-coded cones, and recovering from the kidnapped robot problem.

| Attribute | Details |
|---|---|
| **Stack** | ROS 2 Humble · TurtleBot 4 · YOLOv8 · OpenCV · Nav2 · Python |
| **Deployment** | Real hardware (TurtleBot 4) · structured indoor environment |
| **Features** | Shortest-path planning · cone-rule enforcement · kidnapped robot recovery |
| **Repository** | [github.com/Crostino14/Mobile-Robots-For-Critical-Mission-Project](https://github.com/Crostino14/Mobile-Robots-For-Critical-Mission-Project) |

</details>


<details>
<summary><b>🧠 AI-Assisted Robotic Retail Assistant on Pepper Platform</b> &nbsp;·&nbsp; <i>Feb–Mar 2025</i></summary>
<br/>

AI-assisted robotic system built on the Pepper platform for the Cognitive Robotics
course, designed to enhance visitor experience in shopping mall environments. The system
integrates a real-time video analytics module for face detection and tracking, a
speech-to-text module based on Whisper (Azure OpenAI), and a conversational chatbot
powered by OpenAI's Assistant API (GPT-4o) for multi-turn dialogue management.
Quantitative evaluation of the chatbot yielded a **Factual Accuracy of 0.92** on a
dataset of 50 structured queries.

| Attribute | Details |
|---|---|
| **Stack** | ROS 1 · Pepper (NAOqi) · OpenCV DNN · OpenAI Whisper · GPT-4o Assistant API · Azure OpenAI · Python |
| **Performance** | Factual Accuracy: 0.92 · real-time face tracking at inference |
| **Architecture** | Modular ROS 1 node graph · video analytics · STT · LLM dialogue loop |
| **Repository** | [github.com/Crostino14/Cognitive-Robotics-Project](https://github.com/Crostino14/Cognitive-Robotics-Project) |

</details>


<details>
<summary><b>👁️ Person Detection, Tracking & Behavioural Analysis — Artificial Vision Contest 2025</b> &nbsp;·&nbsp; <i>Dec 2024–Jan 2025</i></summary>
<br/>

Computer vision system developed for the Artificial Vision Contest 2025 (University of
Salerno), as part of a four-person team. The pipeline integrates YOLOv8-based person
detection, multi-object tracking via BoT-SORT, individual attribute classification
(gender, hat, and bag) using a trained MNAT classifier, and behaviour analysis based on
crossings over configurable virtual lines.

| Attribute | Details |
|---|---|
| **Stack** | Python · YOLOv8 · BoT-SORT · OpenCV · PyTorch (MNAT) |
| **Features** | Multi-object tracking · attribute classification · virtual-line crossing behavioural analysis |
| **Repository** | [github.com/Crostino14/Artificial-Vision-Project](https://github.com/Crostino14/Artificial-Vision-Project) |

</details>


<details>
<summary><b>🏓 Neural Robotic Arm Control for Ping-Pong via Reinforcement Learning</b> &nbsp;·&nbsp; <i>Oct–Dec 2024</i></summary>
<br/>

Design and implementation of a hierarchical control system for a robotic arm trained to
play ping-pong in a physics simulation, developed for the Machine Learning course
(University of Salerno). The agent combines supervised pre-training of MLP-based inverse
kinematics models (BaseMLP and ArmMLP) for long-range positioning with a **DDPG (Deep
Deterministic Policy Gradient)** agent featuring a twin-critic actor-critic architecture
(TD3-style) for fine-grained paddle control in the ball's proximity zone. Ball trajectory
is predicted via quadratic ballistic equations; exploration is driven by Ornstein-Uhlenbeck
noise with exponential sigma decay. The simulation environment runs in PyBullet with a
decoupled client-server TCP architecture.

| Attribute | Details |
|---|---|
| **Stack** | Python · PyTorch · PyBullet · DDPG/TD3 · TensorBoard · NumPy |
| **Architecture** | Hierarchical: supervised IK (MLP) + RL fine control (DDPG/TD3) |
| **Exploration** | Ornstein-Uhlenbeck noise with exponential decay |
| **Repository** | [github.com/Crostino14/Machine-Learning-Project](https://github.com/Crostino14/Machine-Learning-Project) |

</details>


<details>
<summary><b>🚘 Modular Autonomous Driving Agent in CARLA Simulator</b> &nbsp;·&nbsp; <i>May–Jun 2025</i></summary>
<br/>

Systematic extension and improvement of an autonomous driving agent (BehaviorAgent)
within the CARLA simulation environment, developed for the Autonomous Vehicle Driving
course. The project addressed the key limitations of the baseline agent through dedicated
modules for: lane change and safe overtaking with oncoming traffic detection, adaptive
management of slow vehicles and cyclists, pedestrian and static obstacle detection and
response, curve stability control, complex intersection handling, and stop sign
recognition. The developed modules were validated on two predefined urban routes through
quantitative comparison against the baseline agent.

| Attribute | Details |
|---|---|
| **Stack** | Python · CARLA Simulator · Docker |
| **Modules** | Lane change · overtaking · pedestrian avoidance · curve stability · intersection · stop sign |
| **Validation** | Quantitative comparison on 2 urban routes vs. baseline BehaviorAgent |
| **Repository** | [github.com/Crostino14/Autonomous-Vehicle-Driving-Project](https://github.com/Crostino14/Autonomous-Vehicle-Driving-Project) |

</details>


<details>
<summary><b>🔐 Adversarial Robustness Evaluation of a Face Recognition System</b> &nbsp;·&nbsp; <i>May–Jun 2025</i></summary>
<br/>

Systematic analysis of the vulnerability of a face recognition system to adversarial
attacks, carried out for the AI for Cybersecurity course. The baseline system
(Inception ResNet V1 pre-trained on VGGFace2, 98.6% accuracy) was evaluated against
five attack families in both error-generic and error-specific modes: **FGSM**, **BIM**,
**PGD**, **DeepFool**, and **Carlini & Wagner L∞**. Attack transferability to a second
model (ResNet-50) was assessed in a grey-box scenario, and two defence strategies were
designed and evaluated: preprocessing-based defences (JPEG compression, feature
squeezing, spatial smoothing) and explicit adversarial sample detection using a
fine-tuned ResNet-50 detector.

| Attribute | Details |
|---|---|
| **Stack** | Python · PyTorch · facenet-pytorch · ART · MTCNN · VGGFace2 · NumPy · Matplotlib |
| **Attacks** | FGSM · BIM · PGD · DeepFool · C&W L∞ |
| **Defenses** | Pre-processing pipeline · fine-tuned adversarial detector (ResNet-50) |
| **Transfer** | Grey-box transferability analysis (Inception ResNet V1 → ResNet-50) |
| **Repository** | [github.com/Crostino14/AI-For-Cybersecurity-Project](https://github.com/Crostino14/AI-For-Cybersecurity-Project) |

</details>


<details>
<summary><b>⚙️ Model-Based Firmware for a Dual-Leaf Electronic Gate</b> &nbsp;·&nbsp; <i>Apr–Jun 2024</i></summary>
<br/>

Design and implementation of a firmware for a dual-leaf electronic gate, developed for
the Embedded Systems course using a model-based development approach. The control logic
is modelled as a hierarchical state machine in **MATLAB Stateflow**, handling gate
opening and closing, obstacle detection via proximity sensors, hardware button
debouncing, configurable movement and auto-close timers, LED feedback, and error state
management. C code was automatically generated via **Embedded Coder** and validated
against 19 test scenarios using MATLAB Test Harness before deployment on the
**STM32 NUCLEO-G474RE** board.

| Attribute | Details |
|---|---|
| **Stack** | C · MATLAB · Simulink · Stateflow · Embedded Coder · STM32 NUCLEO-G474RE |
| **Methodology** | Model-based design · HSM · auto-code generation · 19-scenario test harness |
| **Repository** | [github.com/Crostino14/Embedded-System-Project](https://github.com/Crostino14/Embedded-System-Project) |

</details>

---



## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" width="26" /> Education & Certifications

<p align="center">
  <img src="https://img.shields.io/badge/MSc-AI%20%26%20Intelligent%20Robotics-7C3AED?style=for-the-badge&logo=university&logoColor=white" />
  <img src="https://img.shields.io/badge/BSc-Computer%20Engineering-6D28D9?style=for-the-badge&logo=university&logoColor=white" />
  <img src="https://img.shields.io/badge/Cambridge-B2%20English-5B21B6?style=for-the-badge&logo=cambridge&logoColor=white" />
</p>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="26" /> GitHub Analytics

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=Crostino14&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=7C3AED&icon_color=A78BFA&text_color=C4B5FD&rank_icon=github&include_all_commits=true&count_private=true" />
  &nbsp;
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Crostino14&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=7C3AED&text_color=C4B5FD&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Crostino14&theme=midnight-purple&hide_border=true&background=0D0D0D&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD&sideLabels=C4B5FD&dates=6D28D9&currStreakNum=ffffff&sideNums=ffffff" />
</p>

---



<p align="center">
  <img src="https://mymadreams.com/wp-content/uploads/2020/11/https___bucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com_public_images_32f1fc1b-c9dd-42a3-b788-0b16629301b9_2048x1336.jpeg" alt="Inspirational Quote" width="500" />
  <br />
  <sub><i>"You got the makings of greatness in you, but you got to take the helm and chart your own course. Stick to it, no matter the squalls! And when the time comes you get the chance to really test the cut of your sails, and show what you're made of..."</i></sub>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=fadeIn" />
</p>
