---
layout: page
title: Reliable Task Offloading in Mobile Autonomous Systems Through Semantic MU-MIMO Control
description:
img: assets/img/NSF.png
importance: 1
category: work
---
<style>
.nsf {
  width: 135px;
  height: 121px;
}
</style>
<img src="/assets/img/NSF.png" class="nsf" alt="NSF Logo">


Mobile autonomous systems (MASs) such as self-driving vehicles and drones have a pivotal role in critical applications such as urban mobility, precision agriculture and remote surveillance. To achieve their tasks, MASs increasingly rely on high-throughput low-latency streaming of computer vision tasks (e.g., object detection) to edge servers. However, ephemeral environmental factors such as blockages, congestion and fading may erratically interrupt the flow of tasks to the edge servers. Existing work has addressed computation and communication issues of task offloading by MASs separately, which necessarily leads to suboptimal solutions. Task accuracy, indeed, is inevitably tied to the quality of the multimedia data being sent to the edge, which in turns depends on the adopted wireless strategy. However, the wireless parameters being used depend on the quality of data being sent (the more compression, the higher the latency), which ultimately impacts the desired task accuracy. Thus, to achieve applications that are “resilient-by-design" without compromising task accuracy, the semantics of the multimedia data must be holistically and fundamentally intertwined with real-time optimization of wireless transmissions. The core advance of this project is the design and experimental evaluation of fundamentally novel techniques for hardware-based semantic-driven joint optimization of multimedia compression strategies and MU-MIMO transmissions in the context of resource-limited wireless systems. The PIs will leverage the support of this project to involve minority and underrepresented students in research and outreach activities. As part of the project, graduate students will develop unique expertise at the crossroads of machine learning, embedded systems and wireless networks.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_1_1.png" title="Edge Task O" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Real-time object Detection with Edge Task offloading
</div>

The key technical efforts of this project will focus on the design of novel deep reinforcement learning (DRL)-based strategies that will control how the acquired data stream is compressed and wirelessly transmitted to the edge servers through MU-MIMO. The PIs will utilize techniques based on split computing to avoid increasing computational overhead due to the compression and MU-MIMO channel state information (CSI) feedback, while keeping the task accuracy close to the original. A full-fledged drone-based prototype based on customized software-defined radio (SDR) interfaces based on FPGA real-time processing and edge computing will be developed as part of the project. Large-scale data collection campaigns will be performed with a 64-antenna SDR testbed at Northeastern, a drone experimental testbed at UC Irvine, and the AERPAW PAWR platform to (i) collect the necessary wireless/multimedia data to train our algorithms; (ii) perform extensive testing and performance evaluation.

