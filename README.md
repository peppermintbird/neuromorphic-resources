### Neuromorphic computation resources

> A comprehensive collection of datasets, benchmarks, and resources for neuromorphic computing research. Organized by application areas including vision, audio processing, robotics, and brain-inspired learning.

<table>
  <tr>
    <td rowspan="2" colspan="2">📌 Being updated</td>
  </tr>
</table>

---

## About neuromorphic computing

Key developments to watch in neuromorphic computing:

1. Large-scale neuromorphic systems (Loihi 2, SpiNNaker2, TrueNorth evolution)
2. Event-based sensors and cameras
3. Spiking Neural Networks (SNNs)
    - Vision: `DVS datasets`, `N-MNIST`, `CIFAR10-DVS`
    - Audio: `SHD`, `N-TIDIGITS`, `DVS-Gesture`
    - Robotics: `Event-based control datasets`
4. Neuromorphic hardware accelerators
5. Brain-inspired learning algorithms

---

## 🗂️ Datasets by area

### 👁️ Vision

<table>
  <tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>N-MNIST</strong></td>
    <td>Event-based version of MNIST using DVS camera</td>
    <td>60,000 training + 10,000 test samples</td>
    <td><a href="https://www.garrickorchard.com/datasets/n-mnist">Download</a></td>
  </tr>
  <tr>
    <td><strong>CIFAR10-DVS</strong></td>
    <td>Event-based version of CIFAR-10</td>
    <td>10 object classes, DVS128 camera</td>
    <td><a href="http://www.garrickorchard.com/datasets/cifar10dvs">Download</a></td>
  </tr>
  <tr>
    <td><strong>DVS128 Gesture - IBM</strong></td>
    <td>Hand and arm gesture recognition</td>
    <td>11 gesture classes, 1,342 recordings</td>
    <td><a href="https://ibm.ent.box.com/s/3hiq58ww1pbbjrinh367ykfdf60xsfm8">Download</a></td>
  </tr>
    <td><strong>N-Caltech101</strong></td>
    <td>Event-based object recognition</td>
    <td>101 object categories</td>
    <td><a href="https://www.garrickorchard.com/datasets/n-caltech101">Download</a></td>
  </tr>
  <tr>
    <td><strong>DDD17</strong></td>
    <td>End-to-End event camera driving dataset</td>
    <td>12 hours of driving data</td>
    <td><a href="https://docs.google.com/document/d/1HM0CSmjO8nOpUeTvmPjopcBcVCk7KXvLUuiZFS6TWSg">Download</a></td>
  </tr>
  <tr>
    <td><strong>MVSEC</strong></td>
    <td>Multi-Vehicle Stereo Event Camera</td>
    <td>Outdoor driving with stereo event cameras</td>
    <td><a href="https://daniilidis-group.github.io/mvsec/">Download</a></td>
  </tr>
  <tr>
    <td><strong>POKER-DVS</strong></td>
    <td>Playing cards object recognition</td>
    <td>Event-based card dataset</td>
    <td><a href="http://www2.imse-cnm.csic.es/caviar/POKERDVS.html">Download</a></td>
  </tr>
  <tr>
    <td><strong>N-ImageNet</strong></td>
    <td>Large-scale event-based dataset</td>
    <td>ImageNet recorded with event camera</td>
    <td><a href="https://arxiv.org/abs/2311.04757">Paper</a></td>
  </tr>
  <tr>
    <td><strong>DVS-OUTLAB</strong></td>
    <td>Event-based outdoor scenes</td>
    <td>Natural scenes dataset</td>
    <td><a href="http://www2.imse-cnm.csic.es/neuromorphs/index.php/DVS-OUTLAB">Download</a></td>
  </tr>
</table>

### 🔊 Audio

<table>
  <tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>SHD</strong></td>
    <td>Spiking Heidelberg Digits</td>
    <td>10,420 samples, German and English digits</td>
    <td><a href="https://zenkelab.org/resources/spiking-heidelberg-datasets-shd/">Download</a></td>
  </tr>
  <tr>
    <td><strong>SSC</strong></td>
    <td>Spiking Speech Commands</td>
    <td>35 word classes, event-based</td>
    <td><a href="https://zenkelab.org/resources/spiking-heidelberg-datasets-shd/">Download</a></td>
  </tr>
  <tr>
    <td><strong>N-TIDIGITS</strong></td>
    <td>Neuromorphic version of TIDIGITS</td>
    <td>Spoken digits using cochlea model</td>
    <td><a href="https://docs.google.com/document/d/1Uxe7GsKKXcy6SlDUX4hoJVAC0-UkH-8kr5UXp0Ndi1M">Download</a></td>
  </tr>
  <tr>
    <td><strong>DVS-Lip</strong></td>
    <td>Audio-visual speech recognition</td>
    <td>Event camera + audio synchronization</td>
    <td><a href="https://sites.google.com/view/dvslipdataset">Download</a></td>
  </tr>
</table>

### 🤖 Robotics & control

<table>
  <tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>DHP19</strong></td>
    <td>Detection and tracking of humans</td>
    <td>Probabilistic event cameras for pedestrians</td>
    <td><a href="https://sites.google.com/a/udayton.edu/issl/software/dataset">Download</a></td>
  </tr>
  <tr>
    <td><strong>Event-Camera Dataset</strong></td>
    <td>Neuromorphic SLAM collection</td>
    <td>Event-based localization and mapping</td>
    <td><a href="https://github.com/uzh-rpg/event-camera_dataset">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>Prophesee Gen1</strong></td>
    <td>Automotive detection dataset</td>
    <td>1 Megapixel event-based detection</td>
    <td><a href="https://www.prophesee.ai/2020/01/24/prophesee-gen1-automotive-detection-dataset/">Download</a></td>
  </tr>
  <tr>
    <td><strong>DDD17</strong></td>
    <td>DAViS driving dataset</td>
    <td>Urban and highway driving scenarios</td>
    <td><a href="https://docs.google.com/document/d/1HM0CSmjO8nOpUeTvmPjopcBcVCk7KXvLUuiZFS6TWSg">Download</a></td>
  </tr>
</table>

### 🧠 Brain-inspired learning & neuroscience

<table>
  <tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>N-MNIST</strong></td>
    <td>Saccadic eye movement version</td>
    <td>Bio-inspired event-based recording</td>
    <td><a href="https://www.garrickorchard.com/datasets/n-mnist">Download</a></td>
  </tr>
  <tr>
    <td><strong>Allen Brain Observatory</strong></td>
    <td>Visual coding dataset</td>
    <td>Neural responses to visual stimuli</td>
    <td><a href="https://observatory.brain-map.org/visualcoding">Download</a></td>
  </tr>
  <tr>
    <td><strong>BrainScales Datasets</strong></td>
    <td>Analog neuromorphic recordings</td>
    <td>Hardware-in-the-loop experiments</td>
    <td><a href="https://ebrains.eu/">EBRAINS</a></td>
  </tr>
  <tr>
    <td><strong>SpiNNaker benchmarks</strong></td>
    <td>Large-scale SNN simulations</td>
    <td>Benchmark datasets for scalability</td>
    <td><a href="https://github.com/SpiNNakerManchester">GitHub</a></td>
  </tr>
</table>

### 🎯 Benchmarks & multi-modal

<table>
  <tr>
    <th>Resource</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>Tonic</strong></td>
    <td>Dataset library for event-based data</td>
    <td>Unified interface for multiple datasets</td>
    <td><a href="https://github.com/neuromorphs/tonic">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>SpikingJelly</strong></td>
    <td>Collection for SNN training</td>
    <td>PyTorch-based framework with datasets</td>
    <td><a href="https://github.com/fangwei123456/spikingjelly">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>Event-based Vision Resources</strong></td>
    <td>Comprehensive dataset collection</td>
    <td>Curated list of neuromorphic datasets</td>
    <td><a href="https://github.com/uzh-rpg/event-based_vision_resources">GitHub</a></td>
  </tr>
</table>

## ⚙️ Hardware

### 🧠 Neuromorphic Chips
<table> 
    <tr> 
      <th>Chip / System</th> 
      <th>Access model</th> 
      <th>Power (approx.)</th> 
      <th>On-chip learning</th> 
      <th>Deployment</th> 
    </tr> 
    <tr> 
      <td><strong>Loihi 2</strong></td> 
      <td>Research (INRC access)</td> 
      <td>~1–5 W per chip</td> 
      <td>Yes (programmable plasticity)</td> 
      <td>Advanced research, adaptive robotics</td> 
    </tr> 
    <tr> 
      <td><strong>SpiNNaker2</strong></td> 
      <td>Research community</td> 
      <td>Board-level scalable</td> 
      <td>Software-defined</td> 
      <td>Large-scale SNN simulation</td> 
    </tr> 
    <tr> 
      <td><strong>TrueNorth</strong></td> 
      <td>Research (limited availability)</td> 
      <td>~70 mW per chip</td> 
      <td>No (offline training)</td> 
      <td>Historical milestone, low-power inference</td> 
    </tr> 
    <tr> 
      <td><strong>BrainScaleS-2</strong></td> 
      <td>Research (EBRAINS access)</td> 
      <td>Higher (accelerated analog)</td> 
      <td>Yes (analog plasticity)</td> 
      <td>Neuroscience + accelerated experiments</td> 
    </tr> 
    <tr> 
      <td><strong>DYNAP-SE2</strong></td> 
      <td>Commercial + research</td> 
      <td>Ultra-low power (mW range)</td> 
      <td>Yes (local learning)</td> 
      <td>Embedded robotics & edge systems</td> 
    </tr> 
    <tr> 
      <td><strong>Akida</strong></td> 
      <td>Commercial</td> 
      <td>mW–100 mW range</td> 
      <td>Yes (edge incremental learning)</td> 
      <td>Industrial edge AI</td> 
    </tr> 
</table>

### 📷 Event cameras 
<table> 
  <tr> 
    <th>Camera</th> 
    <th>Access model</th> 
    <th>Power (approx.)</th> 
    <th>Resolution</th> 
    <th>Deployment</th> 
  </tr> 
  <tr> 
    <td><strong>DAVIS346</strong></td> 
    <td>Commercial</td> 
    <td>~200 mW</td> 
    <td>346 × 260</td> 
    <td>Research + robotics prototyping</td> 
  </tr> 
  <tr> 
    <td><strong>DVXplorer</strong></td> 
    <td>Commercial</td> <td>Low-power</td> 
    <td>640 × 480</td> 
    <td>High-speed robotics & drones</td> 
  </tr> 
  <tr> 
    <td><strong>Prophesee Gen4</strong></td> 
    <td>Commercial / automotive</td> 
    <td>Automotive-optimized</td> 
    <td>1280 × 720</td> 
    <td>ADAS & autonomous systems</td> 
  </tr> 
  <tr> 
    <td><strong>Sony IMX636</strong></td> 
    <td>Commercial</td> 
    <td>Low-power</td> 
    <td>1280 × 720</td> 
    <td>Industrial + embedded vision</td> 
  </tr> 
</table>

## 📬 More 

### Newsletters & Communities & Events

1. **[Open Neuromorphic](https://open-neuromorphic.org/)** - A global community fostering education, research, and open-source collaboration in brain-inspired AI and hardware
2. **[Events from NeuroPAC Calendar](https://www.neuropac.info/calendar/list/)** - ;calendar list with workshops, conferences, summer schools.
3. **[Neuromorphic Job Board](https://forum.neuromorphs.net/t/job-openings)** -Job openings 

### Key research groups

1. **Telluride Workshop** - Annual neuromorphic engineering workshop
2. **CapoCaccia Workshop** - Cognitive neuromorphic engineering
3. **Human Brain Project (HBP)** - European neuromorphic initiative
4. **Intel Neuromorphic Research Community (INRC)** - Loihi access and research
5. **SpiNNaker Community** - Manchester neuromorphic platform
6. **iniVation** - Event-based sensors and tools
7. **Prophesee** - Event-based vision systems
