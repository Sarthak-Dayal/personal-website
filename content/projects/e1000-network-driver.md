+++
title = "e1000-network-driver"
+++

## E1000 Network Driver for GheithOS

In two weeks, I, along with two of my classmates, built a E1000 network driver for an emulated Intel i217 card that allowed communication between different emulated instances of QEMU on different machines across our wifi network. More details below.

As part of my Operating Systems class at UT Austin, every student built a custom UNIX-based kernel that had features including virtual memory, an EXT-2 file system, preemptive multithreading, process management, and more. At the end of the semester (as part of our final project for the class), the entire class decided to collaborate and turn this kernel into a more complete operating system that could play a networked game of Doom.

Each team took on a different part of the project, from sound to graphics and we decided to go with networking and build the driver to provide support for a team that used our driver to layer ARP, UDP, and IP with our support.

At the end of the two weeks, we had a full network driver with support for packet sending and receiving, checksum offloading, and more. For our demo, we showcased the sending and receiving of a text version of a picture of our dear professor, Dr. Gheith. While we were disallowed from making the project public so that future classes did not use our code, here is the presentation we gave at the end of the year:

<iframe src="https://drive.google.com/file/d/1vics6rRMpO_RACtTcPDGbr36wDIicQIU/preview" width="100%" height="500" frameborder=8 allow="autoplay"></iframe>
