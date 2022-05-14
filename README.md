# Wiper Control System
![image](https://i0.wp.com/gomechanic.in/blog/wp-content/uploads/2020/06/Car-Wipers.jpg?w=874&ssl=1)

 In this project  STM32F407vg arm microcontroller has been used. Considering the 4 leds as wiper and through switch present in STM32 board we are going to control wiper actions.

RED led as ignition key.
BLUE , GREEN , ORANGE leds as wiper.
When switch is long pressed for 2s, Ignition Key Position will be at ACC (i.e.) Red led will be ON. On press of the user input, Blue, Green and Orange leds come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz. On the 4th press of the switch, led glow pattern gets stopped. When again switch is long pressed for 2s , Ignition Key Position will be at Lock (i.e.) Red led will be OFF.

# Guide Manual<br />
1.Press user button for 2 seconds >>> wiper is in on state<br />
2.Click user button once          >>> wiper will start working at freq=1Hz<br />
3.Click user button 2nd time      >>> wiper will start working at freq=4Hz<br />
4.Click user button 3rd time      >>> wiper will start working at freq=8Hz<br />
5.At any stage if the user button will be pressed for 2 sec then the wiper will shutdown<br />

# SWOT Analysis 
## Strength
* Visibility
* speed control

## Weakness 
* No automation
* Costly

## Opportunity
* Can be automated 
* Sensors can be used to help detect rain

## Threats 
* Once the board repaired cannot be replaced quickly

# Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`0_Abstract`       | Documents detailing about the project
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_TestPlanAndOutput`      | Documents with test plans and output
`5_Report`  | Document consisting of all details
`6_OutputImagesAndVideo` | Document holding output images and video
# Integrated Tools to GitHub
* [Codacy](https://www.codacy.com/)
* [Codiga](https://www.codiga.io/)
# GitHub Actions
* Build using Make for CI
* Unit tests with Cunit
* Static code analysis using cppcheck
* Dynamic Code analysis using Valgrind
# Learning Resources
1. [markdownCheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [markdownBasics](https://guides.github.com/features/mastering-markdown/)
3. [gcc makefile](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html#zz-2.1)
4. [git inspector](https://github.com/ejwa/gitinspector.git)
