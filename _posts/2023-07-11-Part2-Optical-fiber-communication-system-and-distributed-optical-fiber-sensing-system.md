---
title: "Part2-Optical fiber communication system and distributed optical fiber sensing system"
layout: post
---
As shown in the left part of the following picture, a typical optical fiber communication system consists of three main components: a transmitter, an optical fiber, and a receiver. The transmitter comprises a laser and a signal modulation component. Its primary function is to encode the electrical signal into a light wave for transmission. On the other hand, the receiver is made up of a photodiode and a signal recovery part, responsible for converting the received light back into an electrical signal. Various methods exist for modulating the electrical signal into optical light, such as amplitude modulation, frequency modulation, and phase modulation. Through the manipulation of the light's amplitude, frequency, or phase, the information is effectively encoded onto the light wave.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog2_fig1.jpg" align="center" width="800"></a>
</div>

Now, let's shift our focus to the DOFSs system, as illustrated in the right part of the picture, which also comprises three main components: a laser, an optical fiber, and a photodiode. However, there are notable differences between the optical fiber communication system and DOFSs:

* In DOFSs, as we don't need to transmit signals over long distances, only a laser diode and a photodiode are required for sensing purposes.

* Unlike traditional optical fiber communication, where forward transmitted light is utilized, DOFSs use backscattered light. Consequently, both the laser and photodiode are located on the same side of the optical fiber.

You may wonder how DOFSs achieve sensing capabilities with the backscattered light. It all relies on three scattering phenomena within the optical fiber: Rayleigh scattering, Raman scattering, and Brillouin scattering. The intensity, frequency, and phase of the scattered light are affected by external factors such as temperature, strain, and vibration. As a result, by demodulating the intensity, frequency, and phase of the backscattered light, we can accurately derive the external parameters. We will explain each scattering phenomenon in the following parts.


[Next Part3](https://haleyhw.github.io/web/Part3-Recall-some-basic-knowledge/)
