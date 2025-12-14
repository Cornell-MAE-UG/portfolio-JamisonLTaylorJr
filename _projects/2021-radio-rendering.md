---
layout: project
title: Fluids & Heat Transfer Lab Blade Design
description: Turbine Blade Optimization
technologies: [MATLAB, LABView, Fusion 360]
image: /assets/images/turbine.jpg
---

As part of MAE 4272: Fluids and Heat Transfer Laboratory course, our team was tasked with designing a wind turbine blade capable of maximizing power output under fixed wind tunnel operating conditions. The primary objectives were to optimize aerodynamic performance, prevent structural failure under free-spin conditions, and ensure compatibility with system constraints such as the 55 MPa material limit, 6-inch blade length restriction, 1-inch radius hub, a maximum safe rotational speed of 2000 RPM, wind speeds characterized by a Weibull distribution, and fixed parameters of k = 5 and c = 5.

![]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Using a MATLAB-based blade element and bending-stress model, our team iterated twist and chord distributions to improve power output while reducing root bending stress. The final design operated safely across 8–11 Hz wind-tunnel frequencies and achieved a peak experimental power of 1.33 W at 1664 RPM, which aligned closely with our theoretical optimal operating point.

![]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Testing revealed that actual torque values were lower than predicted, indicating that the MATLAB model overestimated torque at high tip-speed ratios. System-level constraints such as the torque-brake control resolution and the approach to the 2000 RPM safety limit ultimately prevented the turbine from being tested above ~11 Hz.

![]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Despite these constraints, the final blade design met the project requirements, demonstrated stable behavior across all assigned frequencies, and delivered consistent power generation. The project underscored the importance of coupling aerodynamic modeling with structural safety considerations and system-level limitations. It also highlighted several pathways for future improvement, including incorporating tip-vortex losses, modeling induction effects at high TSR, and refining CAD geometry to reduce drag and improve manufacturability.

![]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Overall, the design met its theoretical goals and produced consistent experimental performance. The project highlighted the importance of coupling aerodynamic design with realistic system constraints and offered several clear improvement paths for future iterations.


![Shaded rendering of earlier version]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Nulla et magna urna. Morbi a ipsum sollicitudin, rhoncus risus volutpat, ultricies nunc. Quisque mollis finibus ante id imperdiet. Quisque vehicula elit sit amet felis facilisis fermentum.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

I was inspired by this old radio when I made this rendering:

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.
