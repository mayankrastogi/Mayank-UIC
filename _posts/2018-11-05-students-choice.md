---
layout: post
title: Student's Choice Topic&colon; Teslasuit &ndash; Full-body VR Haptic Suit
categories: [CS491, Assignments]
permalink: cs491/assignments/students-choice
draft: false
---

The [Teslasuit](https://teslasuit.io/) is a full-body VR haptic suit. It is *"the world’s first fully integrated smart clothing apparel with Haptic Feedback, Motion Capture, Climate Control and Biometric Feedback systems."*

![Teslasuit](https://teslasuit.io/wp-content/uploads/2018/04/26678459_1202398453227584_3620536319344606942_o.jpg)

## Table of contents

{::options toc_levels="1..3" /}

1. table of contents
{:toc}

## Overview

Virtual Reality has gained a lot of traction in the past couple of years with the advent of cheaper Virtual Reality headsets becoming available to the consumers, owing to cheaper cost of small high-resolution displays &ndash; thanks to the smartphone industry &ndash; and cheaper computing and graphics processing power &ndash; thanks to the gaming industry. While these head-mounted displays, coupled with their motion-tracked controllers, are able to put our heads and hands into the virtual world, the rest of our body is still missing from this world. Furthermore, our sensation of this world is also restricted to our senses of sight and sound. Unless you are playing in a sci-fi virtual world, where our consciousness is separate from our bodies, the experience of floating head and hands doesn't feel very real.

Although a few developers are working very hard in overcoming this problem, by estimating the body position and pose based on the position of the headset and the controllers, the fact remains that these are still, at best, estimates and might occasionally differ from the reality. One such implementation, that I am really looking forward to, is from [Brandon J Laatsch](https://twitter.com/BrandonJLa) from [Stress Level Zero](http://stresslevelzero.com). Have a look at the following video, which demonstrates his team's work for an upcoming game from his studio:

<div style="max-width:854px"><div style="position:relative;height:0;padding-bottom:56.25%"><iframe src="https://www.youtube.com/embed/dX3m8HiL-5c" width="854" height="480" style="position:absolute;left:0;top:0;width:100%;height:100%" frameborder="0" scrolling="no" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div></div>
<br>

> A more accurate way to put the user's body in the VR world is by using full-body tracking. The [Teslasuit](https://teslasuit.io/) allows you to do that, and a lot more! It is ***"the world’s first fully integrated smart clothing apparel with Haptic Feedback, Motion Capture, Climate Control and Biometric Feedback systems."***

## Features

### Haptic Feedback System

![Teslasuit Haptic Feedback System](https://teslasuit.io/wp-content/uploads/2018/04/Teslasuit-haptic-feedback.jpg)

The **Teslasuit** uses two systems to deliver haptic feedback to its wearer &ndash; **Transcutaneous Electrical Nerve Stimulation (TENS)** and **Electrical Muscle Stimulation (EMS)**. Both of these technologies are widely used in the medical field. While **TENS** is widely used for **pain management**, **EMS** is used for **physiotherapy** and **weight training**. According to [WebMD](https://www.webmd.com/back-pain/guide/electrothermal-therapy), *"in TENS therapy for pain management, a small, battery-operated device delivers low-voltage electrical current through the skin via electrodes placed near the source of pain. The electricity from the electrodes stimulates nerves in the affected area and sends signals to the brain that "scramble" normal pain perception"*. 

![Teslasuit Haptic Feedback System](https://teslasuit.io/wp-content/uploads/2017/05/5E878494DAA641F5C9B154DA08140B1B75F68A77E3DCB1511.jpg)

Likewise, the **Teslasuit** uses mild electrical impulses to not only affect the receptors but also the nerve endings. Depending on the amount of current, material, voltage, form of a wave, contact force, electrode size, hydration, and skin type, the suit can deliver to its wearer almost the whole range of sensations that we have in real life. This type of haptic feedback is termed as **Electrotactile feedback**.

> Unlike vibration (also called **Vibrotactile feedback**), ***electrotactile feedback can transmit the feel of a breeze, texture, weight, weather &ndash; for example, precipitation like rain and snow***. With the help of this system, the suit is also able to **simulate weight**, allowing the users to feel the heaviness of the items they are picking up, or interacting with.  

### Motion Capture System

![Teslasuit Motion Capture System](https://teslasuit.io/wp-content/themes/teslasuit_v3/images/teslasuit_page/1920/mocap.jpg)

The **Teslasuit** is equipped with professional-grade mo-cap sensors, which lend high precision, full-body tracking capability to the suit. The **on-board chip** on the suit processes the data from these sensors, allowing the Teslasuit to provide an **avatar system** and a **gesture control** system.

In particular, the Teslasuit consists of 11 motion capture modules, each of which is equipped with **MEMS** motion sensors. ***MEMS** are **micro-electromechanical systems** of devices that involve both mechanical and electrical parts to determine the physical properties of objects.* 

> These MEMS motion sensors transfer the position of joint angles of the limbs. The data obtained from them are sent to the slave microcontrollers. The main microcontroller reads all the data from the slave controllers, and once the data is processed, it is transferred wirelessly to a computer, tablet or smartphone device.

![Teslasuit Motion Capture System](https://teslasuit.io/wp-content/uploads/2017/05/MotionCapture.gif)

This way, the Teslasuit is able to completely simulate user’s body movements in xR environments сreating a digital representation of the user, that is called an avatar or “skin”. Such an implementation provides a **higher degree of personalisation**.

### Climate Control System

![Teslasuit Climate Control System](https://teslasuit.io/wp-content/uploads/2018/09/climate-control.jpg)

Teslasuit climate control is based on **thermoelectric technology** with embedded [Peltier elements](https://en.wikipedia.org/wiki/Thermoelectric_cooling). It’s a smart, heat exchange technology that creates instant coolness or warmth when needed. Cool tones improve and accelerate thermal energy exchange between the body and the textile, where the redundant heat is then dissipated to instantly reduce the wearer’s temperature. ***Peltier elements** have the following advantages:*
- maintain the necessary temperature when a higher or lower temperature is required
- make no noise
- operational at a wide range of temperatures
- have a small size and may be implemented into diminutive devices

### Biometric System

![Teslasuit Biometric System](https://teslasuit.io/wp-content/uploads/2018/09/biometric.jpg)

Teslasuit biometric data can be divided into 2 main types &ndash; **physiological** and **behavioral (behaviometrics)**. The former category is related to the body, and the latter is connected with behavioral patterns. The Teslasuit comes equipped with the following sensors:

- **Electrocardiography (ECG):** Electrocardiography is the process of recording the electrical activity of the heart during a certain period of time by means of electrodes placed on the skin. Teslasuit with electrodes tracks the user’s heart rate and allows viewing real-time ECG with great precision
- **Galvanic skin response (GSR):** GSR covers the changes of electrical characteristics of the skin. Teslasuit GSR provides an indication of the emotional state that has visual expression and can be quantified. It gives a strong signal of physiological and the psychological processes of the users
- **Electromyography (EMG):** EMG is a method for studying bioelectrical potentials that arise in skeletal muscles with the excitation of muscle fibers. Teslasuit EMG functions with the help of cutaneous electrodes. The measured EMG signals cover various types of data regarding the nerve system, e. g., muscle fatigue, muscle movement, and development of motor skills
- **Skin temperature:** Teslasuit is equipped with thermal sensors all over the suit that allow for monitoring and controlling the clothing’s internal temperature from low to high temperatures. With this critical feature, the Teslasuit can provide the user a wide range of temperatures. Settings within the suit allow for imitating close to extreme, but still permissible temperature
- **Measuring radiation:** Detecting and measuring ionizing radiation is enabled with the Geiger counter. Such a measurement will help to prevent adverse health effects of radiation exposure in hazardous work conditions

The presence of these sensors in the suit have a wide variety of applications such as weight training and physiotherapy.

## Specifications

- Smart textile two-piece full body suit (jacket and trousers)
- Haptic feedback system
- 11 motion capture sensors
- Climate control system
- Wireless (Bluetooth or Wi-Fi)
- Control unit
- 16-64 Channels (32-128 electrodes)
- Pulse Amplitude 0-80 mA (per channel)
- Frequency 1-1000 Hz (per channel)
- Pulse Width 1-260 &mu;s (per channel)
- Rechargeable long-life battery
- Size: XS, S, M, L, XL, XXL, XXXL, and tailor made

## Applications

Teslasuit finds its applications in a wide range of use cases ranging from medicine and military to sports and video games.

- Gaming
- Virtual Dating
- Health Well Being
- Education
- Animation
- Sport & Fitness training
- Science & Engineering
- Psychology
- Real life training simulations

## Developer Tools

![Teslasuit Developer Tools](https://teslasuit.io/wp-content/themes/teslasuit_v3/images/teslasuit_page/1920/software_state1.jpg)

The Teslasuit comes bundled with free software to enable faster integration with applications. The bundled software include:
- **Haptic Editor:** For developing haptic presets and managing the climate control system
- **Haptic Player:** For playing the presets created with the Haptic Editor
- **Skeletool:** Tool for motion capture
- **Native SDKs:** API bridge between the applications and the suit; available for Windows, MacOS, Linux, and Android
- **Game Engine Plugins:** Plugins for [Unreal](https://www.unrealengine.com) and [Unity3D](https://unity3d.com) game engines for developing fully-immersive XR experiences

## Potential Issues

- **Daily Use:** While the Teslasuit may become very popular amongst the VR gaming audience, arcades, and businesses, one cannot expect it to be instantly popular with AR applications. For use with everyday Augmented Reality applications, the suit will need to look more similar to regular clothing, instead of the futuristic looking jacket and trousers
- **Privacy:** The suit generates a lot of data. The motion capture sensors can literally record each and every movement of the user, which can be misused by malicious applications. A finer permission-based access control mechanism is needed that will give the user control over what sensors an app will have access to
- **Safety:** Since the suit uses electrical impulses to stimulate the user's nerves and muscles, it raises a question over how safe these impulses are for the user, since different users might respond differently to the same intensity of electrical impulses. Moreover, these impulses might prove fatal to some users, for example, people who have pacemakers in their chests
- **Cost:** With so many high-quality sensors, the overall cost of the suit will skyrocket. The suit should be released with several variants &ndash; a stripped down and affordable version will be useful for the general public for gaming, whereas the full-fledged version will be suitable for businesses, and other commercial uses 

## Conclusion

The Teslasuit has achieved non-invasive immersion of its users into xR by including TENS/EMS stimulation and high precision motion tracking. 

> The Teslasuit has been created using modular technology. The advanced haptic element recreates the sensation of touch and simulates the feeling of the weight of objects in a virtual world. Motion capture provides a 2-way communication in a VR/AR environment, gesture control and position tracking.  The climate component transmits the temperature change in a digital environment and simulates a range of temperature sensations.

The suit is not yet released for commercial use, but is available for B2B customers (enterprises and game development studios). This means it will take a while till we get to buy the suit.

The Teslasuit has been used and reviewed by people at [TechRadar](https://www.techradar.com/news/beyond-haptics-blurring-the-line-between-your-virtual-avatar-and-your-body) and [Seeker](https://www.youtube.com/watch?v=u9PjcgqKAfw), and they have great things to say about it! Check them out while we wait for the suit to be publicly available!
 
 <br>
 
 ***Watch Trace, from [DNews](https://www.youtube.com/user/DNewsChannel), as he tries out the Teslasuit with Teslasuit co-founders Dimitree Marozau and Dimitri Mikhalchuk***
 
 <div style="max-width:854px"><div style="position:relative;height:0;padding-bottom:56.25%"><iframe src="https://www.youtube.com/embed/u9PjcgqKAfw" width="854" height="480" style="position:absolute;left:0;top:0;width:100%;height:100%" frameborder="0" scrolling="no" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div></div>
<br>
<br>

***TechRadar trying out the Teslasuit at London's [Future Tech Now Show](https://futuretechnow.co.uk/)***

<div style="max-width:854px"><div style="position:relative;height:0;padding-bottom:56.25%"><iframe src="https://www.youtube.com/embed/fCsjUG6-F4I" width="854" height="480" style="position:absolute;left:0;top:0;width:100%;height:100%" frameborder="0" scrolling="no" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div></div>
<br>

---

## References / Further Reading

- [Teslasuit &ndash; full body VR haptic suit](https://teslasuit.io/)
- [Teslasuit answers all questions of LBE and arcades owners concerning VR smart clothing](https://teslasuit.io/blog/wearables/all-the-awkward-questions-of-lbe-and-arcades-owners)
- [Teslasuit Project announces the first full body haptic suit with motion capture and climate control](https://teslasuit.io/blog/haptic-feedback/teslasuit-project-announces-the-first-full-body-haptic-suit-with-motion-capture-and-climate-control)
- [Teslasuit Motion Capture System](https://teslasuit.io/blog/motion-capture/teslasuit-motion-capture-system)
- [How do Teslasuit technologies change enterprise training?](https://teslasuit.io/blog/haptic-feedback/how-teslasuit-changes-enterprise-training)
- [TENS and Electrothermal Therapy for Pain Management &#124; WebMD](https://www.webmd.com/back-pain/guide/electrothermal-therapy)
- [Teslasuit: real gaming experience &#124; Mepits](https://www.mepits.com/tutorial/485/trending-technologies/teslasuit-real-gaming-experience)
- [Seeker &ndash; This Virtual Reality Suit Lets You Experience Touch](https://www.youtube.com/watch?v=u9PjcgqKAfw)
- [TechRadar &ndash; Beyond haptics&#58; blurring the line between your virtual avatar and your body](https://www.techradar.com/news/beyond-haptics-blurring-the-line-between-your-virtual-avatar-and-your-body)