# Youngstown State University NASA Lunabotics - 2020/2021
YSU NASA Lunabotics Rover - VHDL

[Lunabotics Final Report - Rev. 2.0.pdf](https://github.com/DeeJay2545/YSU-NASA-Lunabotics/files/8238770/Lunabotics.Final.Report.-.Rev.2.0.pdf)

[NASA Lunabotics - Final Presentation.pdf](https://github.com/DeeJay2545/YSU-NASA-Lunabotics/files/8238847/NASA.Lunabotics.-.Final.Presentation.pdf)

Executive Summary

The NASA Lunabotics Competition tasks collegiate teams with designing, building, and programming a rover that must traverse a simulated lunar surface to mine icy regolith (gravel) at a secondary ground layer 30 cm below the surface. This rover must meet specified design constraints, including an initial volume of 1 m long, 0.5 m wide, and 0.5 m tall, and a maximum mass of 60 kg. Additionally, the rover must be capable of avoiding or crossing boulders and craters upwards of 50 cm in diameter and depth. Teams are incentivized to optimize the rover’s mass, energy usage, communication bandwidth, and dust tolerance to accurately mimic the requirements for a real lunar rover. By providing a rover with these capabilities, teams will aid in the development of ideas used for NASA’s Artemis autonomous lunar rover that will be sent to the moon as part of the strategic goal to have a man and woman on the moon by 2024. Before sending people back to the moon, preparing for the arrival and exploration will be done using these unmanned objects. By participating in this competition, teams will be preparing future engineers to be ready for the design and development that is occurring for these missions. Additionally, the ideas brought forth can potentially be used for future concepts and rover developments that will aid in exploration.

The lunar rover was designed by a team of multidisciplinary, Youngstown State University students. This team included individuals from both the mechanical and electrical engineering programs, as well as the computer science program. In order to fully realize the major target specifications, a lightweight rover that was autonomous, dust free, and capable of mining sufficient icy regolith was designed. In general, the mechanical aspect of the rover was divided into four primary mechanical subsystems: the frame, drivetrain, digging system, and dumping system. The frame is constructed from a high strength aluminum, allowing for optimization of the cross-section and overall design so as to be molded around the existing components. This includes the in-hub wheels, which are designed specifically to maximize the space inside the perimeter of the frame. The grousers on these wheels are to be 3D printed out of continuous carbon fiber reinforced plastic to be both rigid and as lightweight as possible. Furthermore, the kinematically actuated, double auger digging system is designed to dig for the icy regolith at its lowest depths while still being packaged to meet within the volume requirements. Using an auger-type design may reduce the amount of regolith that can be mined, but it provides significantly more dust prevention and minimizes the dust being expelled into the air. Dust prevention was also kept in mind in the design of the pivoting bucket dumping system that will deposit the obtained regolith in the collection bin.

The electrical aspects of the rover were divided into four primary subsystems: physical hardware, controls, communication, and autonomy. The batteries – which are typically used in RC helicopters – were chosen to reduce the passive mass on the rover while still allowing for sufficient power to run all onboard subsystems during a competition run. Furthermore, significant points can be earned in the competition for autonomous control; with the use of an IR beacon system, the team is planning to have the rover examine the terrain of its environment and identify obstacles to avoid as it traverses the simulated lunar surface autonomously. This autonomous computation is handled by a Jetson Nano computer that will interface with an FPGA control system on the rover to safely navigate and control the individual movements of the bucket, augers, and wheels. Combining all these individual subsystems into one complete package, the team was able to fully meet its design goals and make an optimized system for the competition.
