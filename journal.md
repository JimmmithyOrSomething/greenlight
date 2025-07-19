
---
title: "Greenlight"
author: "Eamonn"
description: "A quantum random number generator"
created_at: "2025-07-15"
---



(please disregard spelling, I write most of these late at night)

Total time spent: 9.75h

July 19th:
Today I worked on my CAD Model for the dark box to hold the whole project I made cutouts for both pcbs as well as a spot for the filter and the 5050 reflector And for the laser diode then I made a little box for the microcontroller sit inside with holes that I can later cover up and just run wires through to avoid any light from the microcontroller or from outside when I run power and data inside the box. That I got my project already to submit because I'm pretty much done I put all my files inside my Github.


<img width="1455" height="1092" alt="Screenshot 2025-07-19 133352" src="https://github.com/user-attachments/assets/8894f90d-c1c4-4645-8d83-0af19a1574f1" />



Total time spent: 1.5h


July 18th:
So I started today by updating my tinker cad version i'm still using that because I don't have the parts I need and it works pretty well to just write some test code and that went pretty well I added in a button functionality and wrote a couple more lines of code. Then I switched over to starting my schematic which was a little more complicated than I thought it would be but I found a pretty good way to do it and did it to an ability I'm confident with. I was initially going to have two photo diodes on one PCB and just have extra but I figured because I'm getting sent 5 it doesn't make sense to make one giant pcb that spans the whole space I need and I'll just make two small pcbs that I can place as necessary and I can just wire them into the board I use. Then I decided to just keep going and I did the whole routing of the PCB I used a copper port just because I wanted to have more confidence that my signal would be strong and good. I wrote it into a small rectangle and everything seems fine.

<img width="1778" height="825" alt="image" src="https://github.com/user-attachments/assets/d0d9356d-297f-42f4-99fd-f333f8d1a8b6" />




Total time spent 4h



July 16th:
Today I got a lot done, I first did a lot of research on how a machine like ethis works while figuring out how I would make this on a small budget. Then I did the math behind the amount of photons in a beam of light which ended up being a lot. After that I worked on how to bring that number down. Then I researched the parts I would need to build this and found some good options that should fit into my budget. I found a good light filter that can remove 2^20 times the light as well as a few other tricks that should be helpful. Then I made a circut desigh and wrote a tiny bit of code for it. Normaly I would make a physical version but I didn't have some of the parts so I used tinker cad (which is actualy really good at this type of thing) and it's working fine so far. The code required for this is only a few lines for now beucase it's bascialy just checking for light. For everything is working but I will deffinely need some changees once I have the actual parts.


<img width="2433" height="1033" alt="Screenshot 2025-07-16 220408" src="https://github.com/user-attachments/assets/3d4e187f-a982-47bb-bff9-a73f46d14e51" />


toatl time spent 3.25h





July 15th:

I have this idea, I wan't to build a quantum random number generator and I think I can do it with an ESP 32 and some off the shelf parts and a PCB. I've always been so interested in the fact that nothing in our world is random and everything is dictated by something so no coin flip can be random. And yet quantum particals don't follow the same rules we have to. So a photon can be in two places at once and that's what this project is going to look at. It's going to work by firing a lazer that is dimmmed to an extream degree at a 50/50 photon splitter which means that every photon has a equal chance of bouncing off or going through. So when one photon hits it it both bounces off and goes though at the same time existing in a superposion. Then when I track what happens with a photo resitor one of those becomes real. On top of this I will make a little coin flip demonstration that shows the result of if it bounced off or not. Making a fully random coin flip.

I named this project greenlight beucause it is a light bassed project (even thought the light will probably be red) And this reminds me of Gatsby looking at the green light across the water. But for me I'm looking at a little glimps of what lies outside our world and how diffrent everything is from how it seems.

For today I just plained out my design and set up my github and named my project

total time spent 1h
