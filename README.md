# Desktop pets( LuoXiaohei & Biu )

Desktop pets are computer programs that simulate the presence and behavior of real-life pets, such as dogs, cats, or other animals. Desktop pets can provide entertainment and companionship for computer users who spend a lot of time at their desk, and they can often be customized with different colors, accessories, and personalities. We can interact whit them by clicking the mouse.

## Table of Content

+ [Introduction](https://github.com/JackLam99/DeskPets#desktop-pets-luoxiaohei--biu-)
+ [Table of Content](https://github.com/JackLam99/DeskPets#table-of-content)
+ [Graphical Abstract](https://github.com/JackLam99/DeskPets#graphical-abstract)
+ [Purpose of the software](https://github.com/JackLam99/DeskPets#purpose-of-the-software)
  - [Software development process](https://github.com/JackLam99/DeskPets#software-development-process)
  - [Reason why chose this](https://github.com/JackLam99/DeskPets#reason-why-chose-this)
  - [Target market ](https://github.com/JackLam99/DeskPets#target-market)
+ [Software development plan](https://github.com/JackLam99/DeskPets#software-development-plan)
  - [Development Process](https://github.com/JackLam99/DeskPets#development-process)
  - [Members (Roles & Responsibilities)](https://github.com/JackLam99/DeskPets#members-roles--responsibilities)
  - [Schedule](https://github.com/JackLam99/DeskPets#schedule)
  - [Algorithm](https://github.com/JackLam99/DeskPets#algorithm)
  - [Current status of software](https://github.com/JackLam99/DeskPets#current-status-of-software)
  - [Future plan](https://github.com/JackLam99/DeskPets#future-plan)
+ [Demo](https://github.com/JackLam99/DeskPets#demo)
+ [Environments of the software development and running](https://github.com/JackLam99/DeskPets#environments-of-the-software-development-and-running)
  - [Programming language](https://github.com/JackLam99/DeskPets#programming-language)
  - [Minimum Hardware requirements](https://github.com/JackLam99/DeskPets#minimum-hardware-requirements)
  - [Minimum Software requirements](https://github.com/JackLam99/DeskPets#minimum-software-requirements)

## Graphical Abstract

![Desktop pets](https://raw.githubusercontent.com/JackLam99/DeskPets/main/Pet/bin/lxh/%E7%BD%97%E5%B0%8F%E9%BB%910.gif)
![Desktop pets](https://raw.githubusercontent.com/JackLam99/DeskPets/main/Pet/bin/biu/biu0.gif)
![Desktop pets](https://raw.githubusercontent.com/JackLam99/DeskPets/main/Graphical%20Abstract/system%20tray.png)

## Purpose of the software

### Software development process

In this software, the software development process we applied is **agile**.

### Reason why chose this

The reason why we choose the agile software development process is because agile is **shorter** than the traditional waterfall **development time**, which allows the team to **quickly adapt to changes** according to customer needs during the development process, make changes to meet customer needs and **obtain greater customer satisfaction**. Due to the relatively short development time of the agile software development process, it can be **brought to market faster**, giving our software a **competitive advantage**. In addition, agile software development processes are **more collaborative**.

### Target market

Our target market is **all computer users**

## Software development plan

### Development Process

#### Feasibility analysis

1. Investment feasibility : Desktop pets occupy less memory and can be sold on any platform, so it has a good investment value.

2. Funding Feasibility : From the perspective of stakeholders, the funding for developing Desktop Pets is relatively low.

3. Organizational feasibility : Planning complete project planning, staffing of the development team, holding regular meetings for discussion, allowing team members to have good communication, so as to promote the goal of parallel cooperation among team members, and ultimately ensure that the project can be delivered on time.

4. Economic feasibility : Many people want to have a small pet to relieve boredom when they are bored, which can provide people with a happiness index in life. At the same time, it increases the selling point of the software and is more profitable.

5. Legal feasibility : The research and development of desktop pets did not violate any laws, and the research and development of desktop pets did not infringe anyone's interests.

6. Technical feasibility : The development of desktop pets is relatively simple, so the technical requirements for developers are not high, and the development can be easily completed. It is mainly necessary to design how to have more functions that can be implemented on desktop pets, so that users can get a better experience.

#### Design

1. start()
Create the initial diagram.
Sets the initial position of the transparent form.
Modify the taskbar icon.

2. handle()
The Settings click generates an action.
If an action is not completed, no new action is allowed.

3. lxhBehavior()
Corresponding to the relative coordinates of the click Luo Xiaohei.

4. biuBehavior()
The relative coordinates of the clicked biou.

5. loadImg()
Click on the site to load the image.

6. mainImg()
The main diagram, which is responsible for the default state and exit actions.

7. run()
Click to interrupt other actions.

8. setTray(Stage stage)
Add the system tray.

9. switchPet()
Switch pets.

10. end()
Show the animation when exiting the program.

11. addMessageBox()
Add a chat bubble.

12. run()
Use multithreading to implement the function of "automatic walking", "self-amusement" and "broken thoughts" through random time intervals.

![Desktop pets](https://raw.githubusercontent.com/JackLam99/DeskPets/main/Graphical%20Abstract/operation%20flow%20chart.jpg)

#### Process Planing

Double click to start, there is no set rule. You can do whatever you want, and the whole point of Luo Xiaohei and Petius is to keep the player entertained. Switching pets, automatic walking, and other functions need to open the system tray to achieve.

### Members (Roles & Responsibilities)

#### Contributors

@JackLam99

@DCarchimonde

@

@

@

#### Roles

Jack : **Product Manager**

Aaron : **Engineering Manager**

Wain : **Software Developers**

Haley : **Testers**

Elliott : **Testers**

#### Responsibilities

Jack : Responsible for developing implementation strategies, keeping an eye on competitors and doing in-depth market research, managing pricing policies and controlling planning tasks. Work closely with developers and stakeholders. Responsible for running and coordinating meetings, accepting and rejecting ideas, facilitating technical implementation, documentation and maintenance, etc.

Aaron : Responsible for working face-to-face with each team member to understand the team's performance dynamics. Optimize the software development team structure and participate in coaching. Choose the best engineering solution to realize the product. Responsible for analyzing potential challenges and avoiding them with the help of technical tools.

Wain : Responsible for writing software code using various programming languages, frameworks and libraries. Work in parallel with other team members.

Haley : Responsible for testing the software to ensure the quality of the product. Work in parallel with other team members.

Elliott : Responsible for testing the software to ensure the quality of the product. Work in parallel with other team members.

### Schedule

Week 1 & Week 2 : Plan and collect data, analyze software requirements, and possible difficulties in the development process. Define the software market, target customers, project success rate, and current public needs. Consider time, cost and performance etc.

Week 3 to Week 6 : The design and development officially started. During the development process, everyone held meetings to discuss how to cooperate with each other and work in parallel. Design user interface, write software code, etc.

Week 7 & Week 8 : Conduct user testing and collect feedback for improvement to ensure the best quality of the software and fix known bugs and issues

### Algorithm

1. Automatic walking
Perform the "walk by yourself" function -- walk horizontally. It is not enabled by default because users may only want their pets to be left in peace. Stop if you're about to reach the edge of the screen.

2. Entertain yourself
Perform the "amuse yourself" function -- do random actions in your spare time. So you don't have to be limited by the number of parts, and you don't have to make your pet look stiff. It is not enabled by default because users may only want their pets to be left in peace. gifID is determined by the number of images in an image folder with an undefined purpose and the number of actions that have been set.

3. Switch pets
Users can freely switch between Luo Xiaohei and Biu according to their own desire. The pictures will switch, but the pet action will not stop. And after the completion of the action to restore the main picture is still the previous pet, until the next action to perform normal. The reason is that those three functions pass old petID when they call listn.loadimg().

4. broken thoughts
Display a conversation bubble above the pet. It is not enabled by default because users may not want to be disturbed. Choose what to say at random. Since there are currently only two pets, you can use the triadic operator.

5. Execute at random time
Use multithreading to implement the function of "automatic walking", "self-amusement" and "broken thoughts" through random time intervals.

### Current status of software

The current state of our software is very good, we have completed the development, and the software can also meet the needs of the current market and users.

### Future plan

In the future, we will continue to **maintain** and **improve** our software so that the software can meet the **current market goals and needs**.

## Demo

[Demo](https://youtu.be/TGDG7L3Jc34/)

## Environments of the software development and running

### Programming language

The programming language of our software is **Java**

### Minimum Hardware requirements

Operating system : Windows® 7 or later

Network : Broadband Internet connection

Storage : 1GB available space

### Minimum Software requirements

Software requirement : JavaFX

## Back to top
[Back to top](#top)