---
layout: projects
title: BitThunder
prev_section: home
next_section: fullfat
permalink: /projects/bitthunder/
---

BitThunder is by far my biggest project yet. Its a real-time operating system that uses FreeRTOS
at its core. BitThunder builds on top of FreeRTOS to provide a fully featured driver model, consistent
API and the usual filesystems and networking stacks required in all modern systems.

BitThunder creates a process model around the simple tasks that FreeRTOS provides, allowing all
resources used by a process to be managed and tracked. This allows processes to be killed, without leaking
resources. This feature requires an MPU/MMU hardware.

For more detailed information, see the main bitthunder website, <a href="http://bitthunder.org/">bitthunder.org</a>
