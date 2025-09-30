

# XRP Demo: WCRJ Programming Introduction

Welcome! This guide will walk you through assembling your XRP kit, setting up WPILib 2025 for development, and running the sample `xrp-demo` project on your robot. If you get stuck, don't worry—there are links to official documentation, videos, and if all else fails, we can help at the shop as well.

This guide is designed to familiarize students with the software and fundamentals of programming in FRC (FIRST Robotics Competition). The XRP (Experiential Robotics Platform) serves as a hands-on, approachable way to learn the basics of robot programming. Many of the concepts and tools you'll use here are directly applicable to programming a full-size FRC robot. Think of the XRP as a mini version of an FRC robot, letting you experiment and learn in a safe, accessible environment.

The intended audience for this guide are team members interested in joining the programming team. Whether you're brand new to coding or looking to build on your experience, these steps will help you get started and build confidence in robotics programming in FRC.

---

## 1. Assemble Your XRP Kit

Before you start coding, let's build your robot!

- **Official XRP Assembly Guide:** [XRP Assembly Instructions](https://xrpusersguide.readthedocs.io/en/latest/course/building.html)
    
    > Note: These instructions seem to reference an older model than the ones we have at the shop. Placing of some of the ports may be different on some of the boards, but labels should be the same.

- **Video Walkthrough:** [YouTube: XRP Kit Assembly](https://www.youtube.com/watch?v=D6m1FcjIfis)

> Note: Be mindful of the connections when wiring the robot to ensure pings do not get bent. Take your time and do not over apply force when making a connection.

**Questions to consider:**
- What sensors and motors do you see on the XRP kit?
- How do you connect the battery and main board?


Take your time and make sure everything matches the diagrams. If something doesn't look right, check the documentation or ask a teammate!

---

## 2. Image Your XRP

Now that your XRP kit is assembled, it's time to prepare the robot's onboard computer by "imaging" it. Imaging loads the necessary software so your XRP can run code you deploy from WPILib.

- **Imaging Guide:** [Imaging Your XRP (WPILib Docs)](https://docs.wpilib.org/en/stable/docs/xrp-robot/hardware-and-imaging.html#imaging-your-xrp)

Follow the instructions in the official documentation to download and flash the correct image onto your XRP. Make sure your robot is connected to your computer and powered on before starting.

> Note: If you run into trouble, double-check your USB connections and make sure you're using the correct image file for your board (at the time of writing: xrp-wpilib-firmware-2.0.1-71a2f5a.uf2
).

**Questions to consider:**
- What does "imaging" mean in the context of robotics?
- How do you know the imaging process was successful?

Once your XRP is imaged, you're ready to set up your programming environment!

---

## 3. Install WPILib 2025

WPILib is the software you'll use to program your robot. Follow these steps:

1. **Download WPILib:**
	- [WPILib Installation Guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html#downloading)
	- Make sure you download version 2025.x.x or newer.
2. **Install WPILib:**
	- Follow the instructions for your operating system (Windows, Mac, Linux).
	- If you run into issues, check the [Troubleshooting Section](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html#extracting-the-installer).
    > Note: You do not need to do the steps for Additional C++ Installation for Simulation.

**Questions to consider:**
- What is WPILib used for?
- Can you find the WPILib icon on your computer after installation?

---

## 3. Create and Open the XRP Demo Project

Let's get coding! From here, you have two options: You can leverage the existing code on this repo, or if you'd like to set up the example project yourself, follow the following instructions:

1. Press `Ctrl + Alt + P` to open the command dropdown.
1. Type `WPILib: Create Project` and select it.
1. Choose:
	- Project Type: Example
	- Language: Java
	- Example: XRP Reference
1. Select a folder and name your project (e.g., `xrp-demo`).
1. Set your team number to `5492`.

**Questions to consider:**
- What files do you see in your new project?
- Can you find the `Robot.java` file?

---


## 4. Simulate and Run the Robot Code (Emulation)

> Note: This section is still being refined and will take some trial and error. If you run into any issues feel free to ask a mentor for help.

Want to run the reference program without deploying to the robot? You can use WPILib's built-in robot simulation/emulation:

1. **Open VS Code and make sure your reference project is loaded.**
2. **Open the command palette (`Ctrl+Shift+P`) and select `WPILib: Simulate Robot Code`.**
3. **Choose the simulation type (Java, Desktop, etc.) if prompted.**
4. **Wait for the simulation to start.**
	- The simulation window will appear, showing your robot's behavior.
5. **Interact with the simulated robot using the provided controls.**

This lets you test your code and see how the robot would behave, all without needing to deploy to hardware.

For a visual walkthrough, see this video: [Running XRP Reference Program](https://www.youtube.com/watch?v=fjSQFVKx2Fg)

---

## 5. Learn More & Explore

- [WPILib XRP Documentation](https://docs.wpilib.org/en/stable/docs/xrp/index.html)
- [WPILib YouTube Channel](https://www.youtube.com/@wpilib)
- [XRP Troubleshooting](https://docs.wpilib.org/en/stable/docs/xrp/troubleshooting.html)

**Challenge:** Try modifying the sample code to make the robot drive in a different pattern. What happens?

---

If you have questions, ask your mentor or check the documentation. Good luck, and have fun building and programming your XRP robot!

