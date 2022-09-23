---
layout: archive
title: "The Lab!"
permalink: /lab/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}
# ALSETLab is a set of Laboratory Facilities!
- ALSETLab Maxwell: contains three types of test-benches for real-time hardware-in-the-loop and controller-in-the-loop experiments supported by real-time simulators from different vendors.
![maxwell](https://ecse.rpi.edu/~vanfrl/documents/thelab/maxwell_red.png "ALSETLab Maxwell")

- ALSETLab Volta: is a power hardware-in-the-loop facility for inverter functionality testing of 15 kW capacity.
![volta](https://ecse.rpi.edu/~vanfrl/documents/thelab/volta.png "ALSETLab Volta")

Below is a more detailed description of the test-bench that uses Opal-RT simulators, however, observe we also have Typhoon HIL simulators and a dSPACE SCALEXIO platform.

A presentation of the lab platforms can be found [here](https://docs.google.com/presentation/d/1MNE_EfQC5XP10JcTPuwSA8qgoDPmWf08uzJDgy0oNcc/edit?usp=sharing).

# ALSETLab Maxwell Test-bench using Opal-RT simulators
![labsmall](https://ecse.rpi.edu/~vanfrl/documents/thelab/01_overview_p2.png "Small Lab Picture")

## Information Flyers
Please download our informational flyers in the following links:
  - [Overview - General Public](https://ecse.rpi.edu/~vanfrl/documents/thelab/01_overview.pdf)
  - [Overview showing timing and comms layers](https://ecse.rpi.edu/~vanfrl/documents/thelab/02_overview_plus_layers.pdf)
  - [Overview of our in-house tools software tools](https://ecse.rpi.edu/~vanfrl/documents/thelab/03_tools.pdf)  

## Lab Description
Digitalization and renewable energy sources bring tremendous possibilities to
revolutionize the way we produce, transport, distribute and consume
electricity. However, they also bring tremendous challenges to maintain
adequate resiliency and cyber-physical security of electrical power
networks.

**Our research focuses** in the development of transformative **concepts, methods/algorithms, cyber-physical models, and tools** to take maximum advantage of renewable energy sources by bringing the
grid into the digital age, while at the same time meeting the challenges brought by renewables and cyber-physical threats to power grid
resiliency.

We develop fundamental research by interweaving skills in electrical power grid control and stability, system identification theory, embedded
systems, and most importantly, modeling and simulation.

We are setting the foundation for the Digital Grid of the future!

**- What is ALSET Lab?**

ALSET is a simulator-based laboratory that can host real-time
hardware-in-the-loop experiments on time-critical applications for
cyber-physical power systems.

- ALSET is a ***simulator-based laboratory***; that is, we test our developed applications by applying them to
realistic models of power systems that are simulated by our computers.
ALSET is the home to four eMEGASIM/ePHASORSIM OPAL-RT computers with a
total of 128 real-time cores designed to simulate the behavior of large
power systems, from mega-grids to microgrids. If you are wondering why
we don’t test our applications on real power systems; well, it’s because such testing requires applying multiple interruptions on customers’
power supply, which is obviously not desirable.
- At ALSET, we run ***real-time hardware-in-the-loop experiments***. ***Real-time***, because each second of experiments takes precisely one second, thanks
to our powerful simulators. That means, from the other equipment
point-of-view that are interfaced to the simulator, the output signals
of the simulator are as if they are coming from a real power system. The experiments we run are ***hardware-in-the-loop***; that is, we implement our developed applications on real hardware that are interfaced with the simulators.
- Our experiments deal with ***time-critical applications***, meaning that our developed applications need to precisely know the real time. This means that the hardware hosting these applications should be fed by a very precise time signal with accuracy of a few microseconds.
We have a particular infrastructure that is designed to fulfill this
requirement.

**- Why is ALSET Lab important?**

Most of our research work at ALSET is focused on ***cyber-physical power systems***. Why cyber-physical? Because electrical power systems are increasingly
becoming digitalized, leading to their transformation into a class of
cyber-physical systems (a system of systems) where the electrical grid
merges with Information and Communication Technologies (ICT). This type
of complex systems present unprecedented challenges in their operation
and control, and due to unknown interactions with ICT, require new
concepts, models, methods and tools to facilitate their operational design, and testing/verification/validation of
their performance. We have built ALSET to address these challenges!

**- How to get involved?**

**Gain Digital Skills:**

Undergraduate students can join in summer research projects developing skills and contributing to our projects.

Co-terminal students are specially encouraged to start early in their degree to
compliment their formal course work with unique skill development with
the latest technology that is in high demand in the electrical power
industry, world-wide.

**Collaborate in Transformative Research with ALSETLab:**

ALSETLab is always looking to partner in collaborating through Sponsored
Research projects and to join in attracting federal/state funding
research opportunities. For examples of on-going and previous
collaboration projects, please visit:

[https://alsetlab.github.io/research/](https://alsetlab.github.io/research/)

**Support and Donate to ALSETLab:**

Several of our projects or initiatives that have the potential to be
transformative in nature and/or position RPI to be a leader in power
grid research do not qualify for funding from traditional research
grants.
- Check’s or money orders payable to Rensselaer Polytechnic Institute, declared as a "Restricted Gift" with a letter stating:
  - Subject: Restricted Gift to Prof. Vanfretti to be Administered by the ECSE Department at RPI.
  - *** Your name / company ***'s policy/preference is that the funds associated with this gift will not be used to cover institutional indirect costs such as overheads. This gift is being made with the understanding that they will be utilized only to finance direct costs associated with Prof. Vanfretti's research efforts. Costs may include, but are not limited to, travel expenses, materials and equipment, software licenses, etc.

For more information on how to support ALSETLab and examples of previous donations, please visit visit: [https://alsetlab.github.io/donate/](https://alsetlab.github.io/donate/)
