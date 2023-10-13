# Closed loop driving with CARLA and eCAL 🚗

This is a **creativity challenge**. We provide you with the CARLA Simulator and some interface code to Eclipse eCAL. Your task is to **create something cool** with it.

- You can use any programming language you want.
- You can use any sensor data you want.
- You can use any algorithm you want.
- You can use any hardware you want.
- You can use any software you want.
- You can use any library you want.
- You can use any framework you want.
- You can use any cloud service you want.
- You can use any machine learning model you want.
- You can use any data you want.

# 📚 About

[Eclipse eCAL™](http://ecal.io) is a **publish subscribe** Middleware with the main focus on research and development of **autonomous driving** algorithms.

- A Publisher **publishes data** to a topic, identified by a name.
- A Subscriber **subscribes to a topic**, identified by a name. When it received data, it calls a **callback function**.

[CARLA](https://carla.org/) is an open-source **simulator for autonomous driving** research. It provides a realistic environment for testing and developing autonomous driving algorithms.

- It provides a variety of sensors and weather conditions to simulate **real-world scenarios**.
- It also supports different types of **vehicles and pedestrians**.
- We provide you with a **bridge** between CARLA and eCAL.

[![](https://mermaid.ink/img/pako:eNplkMFqwzAMQH_FaJcNUigMCslhkKXH7NLCYMMXJXYag20Fxdkoaf59TrJBtukkpPckoRFqUhoyaCx91i1yEOVJehGjyE9lLna7p9tZ-55YHDGg-DAodJGXN1FiF6i7f6OBRW4vxCa07mF1194iF-QDk_1rL9MhAafZoVHxgnFWJYRWOy0hi2mFfcySTf0V2WBldT8D47pLQsfGIV8LssSredc0eNjvv-UN80ysNG_JND08_iJ7XZNX_-apKk0lzNAk_RQvxyHQ-epryAIPOoGhUxj00eCF0UHWoO1jVSsTiF_WJy-_TqBD_070w0xfENh86A?type=png)](https://mermaid.live/edit#pako:eNplkMFqwzAMQH_FaJcNUigMCslhkKXH7NLCYMMXJXYag20Fxdkoaf59TrJBtukkpPckoRFqUhoyaCx91i1yEOVJehGjyE9lLna7p9tZ-55YHDGg-DAodJGXN1FiF6i7f6OBRW4vxCa07mF1194iF-QDk_1rL9MhAafZoVHxgnFWJYRWOy0hi2mFfcySTf0V2WBldT8D47pLQsfGIV8LssSredc0eNjvv-UN80ysNG_JND08_iJ7XZNX_-apKk0lzNAk_RQvxyHQ-epryAIPOoGhUxj00eCF0UHWoO1jVSsTiF_WJy-_TqBD_070w0xfENh86A)

![](https://i.ytimg.com/vi/AZhzZy57XeU/maxresdefault.jpg)

# 👾 Hack Ideas

- Detect pedestrians from the camera image and **track them**.
- Steer the vehicle to **follow a lane**.
- Use the Google gesture recognition model to **control the vehicle**.


# 💻 Requirements

- A rather **powerful GPU** is required to run CARLA
- **Programming languages**
    - Recommended: Python or C++
    - Other options: C, C#, JavaScript, Rust

*We recommend using Windows or Ubuntu. MacOS may work too, but eCAL is poorly tested on that OS.*

# 👨‍🏫 Hack-Coaches

- Kerstin Keller
- Florian Reimold
- Kristof Hannemann
- Rex Schilasky

# 🛠 Template Setup

1. Download and setup Eclipse eCAL:
    - 🐧 Ubuntu:
        ```bash
        sudo add-apt-repository ppa:ecal/ecal-latest
        sudo apt-get update
        sudo apt-get install ecal
        ```

    - 🪟 Windows:
        - Download the latest release from https://eclipse-ecal.github.io/ecal/_download_archive/download_archive.html

2. Setup CARLA:
    - https://carla.readthedocs.io/en/latest/start_quickstart/

3. Setup CARLA <-> eCAL Bridge
    - TBD

4. Setup Foxglove Studio
    - TBD


# 👀 All necessary links

**Eclipse eCAL**:
- 🏠 Homepage: http://ecal.io
- 👨‍💻 GH Repository: https://github.com/eclipse-ecal/ecal
- 💡 How to compile eCAL: https://eclipse-ecal.github.io/ecal/development/building_ecal_from_source.html

**CARLA**:
- 🏠 Homepage: https://carla.org/

**Foxglove Studio**:
- *= Tool for visualization*
- 🏠 Homepage: https://foxglove.dev/
- 👨‍💻 eCAL Foxglove Bridge: https://github.com/eclipse-ecal/ecal-foxglove-bridge
