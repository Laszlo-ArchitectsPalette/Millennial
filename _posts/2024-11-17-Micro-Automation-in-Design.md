---
layout: post
title: "Micro Automating Simulation in Architecture with Splash"
author: "Laszlo Andrasi"
categories: Posts
tags: [posts]
image: Micro-Automation-in-Design/Splash!.jpg
---

# Enhancing Early Phase Design Collaboration with Automation in Speckle

In recent developments at the intersection of computational design and automation, engineers and architects have collaborated to address key inefficiencies in early phase design workflows. The goal was to tackle redundancies and improve collaboration, aiming to overcome the traditional, static approaches that limit effective feedback.

## Streamlining the Design Process

The core idea was to remove redundant, static collaboration and integrate analysis processes early on. Typically, engineers and architects meet with separate analysis reports, resulting in static drawings that each team member must explain and interpret independently. This fragmented approach slows the design process and impedes fluid communication.

By utilizing **Speckle Automate** and various integrated tools, the team aimed to break these isolated feedback loops and speed up updates. With this approach, they could capture design changes in real time and instantly reflect them across analyses. This strategy significantly reduces hidden analysis work and redundant meetings, allowing for faster adjustments and improved understanding among team members.

## Tackling Computational Bottlenecks

One particular bottleneck in computational design was the manual setup required to run analysis scripts for every design iteration. For example, Mario, the team’s computational designer, was tasked with importing models, connecting them to Grasshopper scripts, and running complex analysis workflows. By automating routine tasks, Mario’s role could shift toward higher-level design challenges, enhancing his productivity and democratizing access to these automated analyses for the entire team.

## Real-Time Analysis Demonstration

Using the example of **Villa Siva**, a demonstration illustrated how automated updates on Speckle could instantly reflect design adjustments. For instance, if a new overhang was added over ribbon windows, the radiation analysis and structural load information updated almost immediately. 

This allowed architects and structural engineers to see the impact of their changes in real time, encouraging more meaningful design discussions. For example, an architect focused on daylighting could see the structural engineer's concerns about load distribution and deflection, leading to a collaborative dialogue about balancing aesthetics and functionality.

## Technical Workflow: Speckle, Grasshopper, and Automation

The technical setup leverages popular design software like *Revit* and *Rhino*. Designers send geometry to Speckle, triggering a Speckle Automate webhook that opens Grasshopper scripts on a remote server or local machine. This setup allows both architects and engineers to contribute their analysis scripts, which then integrate into Speckle’s real-time environment. As a result, all stakeholders can view synchronized analysis updates without manually triggering individual scripts.

## Collaborative Team Effort

The project came to life thanks to a team of diverse professionals, including architects, structural engineers, computational designers, and software developers. Working collaboratively in an open-source framework, the team completed this solution within a 26-hour sprint, demonstrating the feasibility and potential of this approach in the field.

## Practical Application and Future Goals

The automation workflow allows designers to share project data with clients and project managers seamlessly, even if they don’t have design software installed. The flexibility of Speckle to leverage BIM information beyond specific applications like Revit and Rhino opens the door to further project applications, setting a new standard for design communication.

With this innovative setup now operational, the team is eager to apply it to more projects, enabling a more dynamic and collaborative approach to early phase design and analysis.

[<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 002.jpg" style="width:100%; max-width:1024px; height:auto;">](https://github.com/Laz-AP/SPLASH)
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 002.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 003.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 004.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 005.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 006.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 007.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 008.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 009.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 010.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 011.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 012.jpg" style="width:100%; max-width:1024px; height:auto;">
<img src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Emerging Tech - AEC TECH 2024 Page 013.jpg" style="width:100%; max-width:1024px; height:auto;">

<video controls style="width: 100%; max-width: 1024px; height: auto;">
  <source src="https://laz-ap.github.io/thoughts/assets/img/Micro-Automation-in-Design/Analysis Live Demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


<iframe title="Speckle" src="https://app.speckle.systems/projects/0a088653cb/models/3b0cd0e540@d9475a130c,5feb88aba3@c02f27e6e0,7ffc65a67a@fbb60cce88,bbde214205@1dc3d28ac2#embed=%7B%22isEnabled%22%3Atrue%7D" width="600" height="400" frameborder="0"></iframe>
