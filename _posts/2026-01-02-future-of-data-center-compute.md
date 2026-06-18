---
title: "House View: The Future of Data Center Compute"
tag: "House View"
excerpt: "A primer on the architectural shifts ahead for data centers — breaking the memory wall, photonics-based interconnects, and the rise of small, modular edge compute."
credit: "Originally published as a Roadrunner Venture Studios house view."
---

## Introduction

With around 5.52 billion internet users and 4.88 billion smartphone users worldwide, humankind is generating and consuming more data than ever before. In 2024, users created more data in a single week — about 2.8 billion terabytes — than in the entire year of 2010. It's easy to think of digital tech as just our phones or computers, but the truth is far more complicated. Our devices depend on a complex global system of fiber optic cables, satellites, communication towers, and data centers to power the apps we use, store the data we create, and keep our digital world running smoothly.

Data centers act as the hubs for this system where vast amounts of information are processed, stored, and distributed, making them indispensable to the functioning of the modern digital ecosystem. Data center performance has gradually improved over the years, but significant innovation is still needed to meet future global demand, which McKinsey & Co. estimates will grow by an annual rate of ~20% through 2030.

The ever-growing demand for computational power — largely driven by the recent explosion in artificial intelligence (AI), machine learning (ML), and big data analytics — is accelerating groundbreaking advancements in data center technology and will require the development of new architectures and innovative solutions. Deep tech computing breakthroughs will not only drive the future of AI/ML, but will also redefine industries across the globe, from healthcare to energy.

Roadrunner is interested in founders, start-ups, and scientists with innovative ideas on how to move the needle on 21st Century data center design. Read on to learn more about one of the areas that are most exciting to us.

## Topics That Excite Us

- Alternative chip architectures (including non-transistor based compute)
- Architectures that address the cold memory/memory wall issue
- Manufacturing improvements for photonic chip components
- Small, modular edge data centers

## General Data Center Background

Data centers are the backbone of our digital world, housing essential equipment needed for data processing, data storage, and networking. Data centers are composed of four main components: the facility itself, the equipment to power and operate the facility, the hardware, and the software. Specifically, data center computing hardware can be organized into three main levels:

- **Chip-level.** The most granular level of computing, where individual computational tasks are performed within microprocessors or chips.
- **Server-level.** A functional system, or computer, consisting of multiple chips that work together to perform specific tasks within a data center.
- **Rack-level.** The physical infrastructure, typically a 19-inch rack, houses and interconnects multiple servers, ensuring efficient operation and scalability within the data center.

## The Core of Compute — Transistors

Transistors are tiny switches that control the flow of electricity on a chip, enabling computers to make decisions and perform calculations. They are the fundamental building blocks of modern electronics and have greatly benefited from Moore's Law — the observation that the number of transistors on a silicon chip will double every two years with minimal rise in cost. This trend has guided the industry. Transistors have historically shrunk in size, leading to improved performance and reduced power consumption as each electron can travel shorter distances.

The first modern transistor, invented in New Jersey at Bell Labs in 1947, was 40 micrometers long. Current commercially available transistors measure just three nanometers wide — about 13 silicon atoms. These miniscule sizes are nearing the physical limits for transistors. Further progress is both costly and slow. Soon we will be physically unable to make transistors smaller because (1) silicon will fail to control the flow of electricity due to a quantum-mechanical effect known as tunneling, and (2) the copper wires connecting the transistors cannot be physically thinner than the size of atoms.

Smaller silicon transistors will not be the only approach to improving compute performance in the 21st Century. Scientists have recently begun exploring ways to downsize transistors from three to two dimensions using new materials — such as graphene and molybdenum disulfide — in next-generation electronics. The flat, planar structures of these 2D materials have the potential to extend Moore's Law beyond the capabilities of silicon, which has a 3D tetrahedral structure. Others are investigating alternative chip architectures that go beyond transistors as the foundation for computation, including designs with improved performance for AI/ML. Metamaterials may enable optical compute, in which light, rather than electricity, is the medium of computation. Roadrunner is interested in these innovative chip architectures and how they can improve performance irrespective of science's ability to invent smaller transistors.

## Breaking the Cold Memory Wall

Advancements in transistors, chip design, and parallel processing have greatly enhanced the speed at which processors perform calculations. However, servers rely on more than just processors for efficient task execution — memory and storage are also essential components. Memory temporarily holds active data and instructions for processors, while storage is used to save data long-term. Memory is crucial for task execution, but the rate at which data can be read from or written to memory by a processor (memory bandwidth) hasn't kept pace. This differential has created a "memory wall" problem. Over the past 20 years, hardware FLOPS (operations per second) has increased 60,000×, while memory bandwidth has only improved 100× and interconnect (data moving from computer to computer) bandwidth 30×. This means processors often must wait for data, unable to work at their full potential. Some estimate that CPUs and GPUs frequently operate at only 30-50% capacity due to this memory wall problem. To make matters worse, memory is confined within individual servers, preventing efficient sharing with other devices and further slowing down overall performance.

Industry has not yet addressed the memory wall problem and scaled data transfer speeds to meet the demands of modern systems. Roadrunner hopes to see an architecture that decouples memory from compute in the future. In a disaggregated architecture, memory is seamlessly shared across all servers regardless of physical location. This system would unlock efficient resource utilization and prevent situations where some servers run out of memory while others have unused capacity. Such an architecture would feature a hierarchical memory structure and require innovative interconnect solutions. This approach would enable memory to be shared at the data center level rather than within individual devices, allowing the entire data center to function as a single unit.

## The "New Unit of Compute": The Data Center with Photonics Solutions

Jensen Huang, CEO and Founder of Nvidia, often refers to data centers as the new "unit of compute." Traditionally, data centers were static; each server would run a single application. Today, data centers have dynamically evolved to allow thousands of chips to work together as one machine to solve complex problems and algorithms. To meet the future demands of AI and high-performance computing, data must flow seamlessly and efficiently between chips, servers, and racks.

Optical interconnects, traditionally reserved for high-speed data transmission over long distances, are now being adopted for shorter connections as data rate demands rise. Designers are replacing copper wires, which once dominated all data center connections, with fiber optic cables at the server- and rack-level, enabling data to travel at the speed of light rather than at the speed of electrons. However, copper wires are still responsible for chip-to-chip connections. As a result, the bandwidth at the chip's edge is failing to scale at the pace required to meet growing demands. Increasing the number of input/output (I/O) connections is a common solution to boost shoreline bandwidth. Yet the physical space at the chip's edge is limited, restricting the number of copper wire connections that can be accommodated. This data transfer bottleneck — due to the physical and bandwidth limitations at the chip's edge — is commonly referred to as the "shoreline problem."

To tackle the so-called shoreline problem, efforts are underway to bring the advantages of optical technology from the server- and rack-level down to the board- and chip-level. Innovations in photonics are reducing dependence on copper connections by moving optical signaling closer to, or even within, the chip — extending beyond the shoreline to the point-of-compute. Optical signals address the shoreline problem and enhance bandwidth in two key ways: (1) allowing data to travel at the speed of light instead of electrons and (2) increasing data capacity through wavelength-division multiplexing (WDM). WDM enables multiple wavelengths (colors) of light to transmit data simultaneously over the same optical fiber without interference, significantly boosting capacity without adding physical connections. Scaling down optical elements like modulators and lasers to the chip level is challenging, power-inefficient, and costly. Converting electrical signals to optical signals is difficult and energy-intensive. Additionally, co-locating optics with chips generates concentrated heat, exacerbating already significant cooling issues. If designers are able to improve the manufacturing of photonic chip components, that would enable massive collections of GPUs across the data center to operate as a unified system, communicating directly with disaggregated memory.

## Edge Computing: Little Data Centers Everywhere

As we generate and consume more data than ever before, compute will need to reside where the data is generated — at the edge. More everyday devices are being connected to the internet and transformed into Internet of Things (IoT) devices, such as smart refrigerators, video doorbells, and app-controlled lights. With more devices coming online, it's no longer practical to send all generated data to a centralized location for processing. As such, Roadrunner envisions a future where small, modular, but compute-heavy edge data centers will be embedded into everyday infrastructure like electrical poles or phone towers. In this vision, compute infrastructure will be hierarchical. Easy processing will take place in neighborhood data centers, while large, out-of-the-way, and advanced data centers will train new large AI models at central locations. This shift in data center design and geography will redefine how we think about connectivity and will ultimately enhance the user experience.
