### Neuromorphic computation resources

> A collection of datasets, benchmarks, and resources for neuromorphic computing research. Organized by application areas including vision, audio processing, robotics, and brain-inspired learning.

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
  <tr>
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

### 🧩 Segmentation

<table>
  <tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>EV-SegNet</strong></td>
    <td>First event-based semantic segmentation benchmark (CVPRW 2019)</td>
    <td>Semantic labels for DDD17 driving sequences</td>
    <td><a href="https://github.com/Shathe/Ev-SegNet">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>ESS (uzh-rpg)</strong></td>
    <td>Event-based semantic segmentation learned from still images (ECCV 2022)</td>
    <td>Introduces DSEC-Semantic; also uses DDD17</td>
    <td><a href="https://github.com/uzh-rpg/ess">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>OpenESS</strong></td>
    <td>Open-vocabulary event-based semantic segmentation (CVPR 2024)</td>
    <td>Annotation-free; evaluated on DDD17 and DSEC-Semantic</td>
    <td><a href="https://github.com/ldkong1205/OpenESS">GitHub</a></td>
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

### 🤟 Sign language

<table>
  <tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>SL-Animals-DVS</strong></td>
    <td>Spanish sign language signs for animals, recorded with a DVS</td>
    <td>~1,100 samples, 59 subjects, 19 signs; SNN baselines (SLAYER, STBP, DECOLLE)</td>
    <td><a href="http://www2.imse-cnm.csic.es/neuromorphs/index.php/SL-ANIMALS-DVS-Database">Download</a></td>
  </tr>
  <tr>
    <td><strong>ASL-DVS</strong></td>
    <td>American Sign Language static handshapes (letters A–Y, no J)</td>
    <td>24 classes, 100,800 samples, DAVIS240c</td>
    <td><a href="https://github.com/PIX2NVS/NVS2Graph">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>N-WLASL</strong></td>
    <td>Event-based re-recording of WLASL (word-level ASL) from a monitor</td>
    <td>21,093 samples, 2,000 glosses, DAVIS346</td>
    <td><a href="https://ieee-dataport.org/documents/n-wlasl">Download</a></td>
  </tr>
  <tr>
    <td><strong>DVS_Sign / DVS_Sign_v2e</strong></td>
    <td>Sign gestures for human–robot interaction, real DVS + v2e-converted</td>
    <td>5 categories (verbs, quantifiers, position, things, people); SNN (STBP)</td>
    <td><a href="https://www.mdpi.com/2079-9292/12/4/786">Paper</a></td>
  </tr>
  <tr>
    <td><strong>EvSign (ECCV 2024)</strong></td>
    <td>Continuous sign language recognition and translation with events</td>
    <td>Chinese SL, 6,773 videos, 1,387 glosses, gloss + text labels</td>
    <td><a href="https://github.com/zhang-pengyu/EVSign">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>Event-CSL (OpenESL)</strong></td>
    <td>High-definition event-based sign language translation benchmark</td>
    <td>14,827 videos, Prophesee EVK4-HD 1280×720, indoor + outdoor</td>
    <td><a href="https://github.com/Event-AHU/OpenESL">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>Spike-SLR (BMVC 2024)</strong></td>
    <td>Energy-efficient spiking transformer for event-based sign recognition</td>
    <td>Method; evaluated on SL-Animals-DVS</td>
    <td><a href="https://bmvc2024.org/proceedings/493/">Paper</a></td>
  </tr>
  <tr>
    <td><strong>Awesome-Sign-Language</strong></td>
    <td>Curated paper list for sign language recognition and translation</td>
    <td>Includes LLM-based and gloss-free translation work</td>
    <td><a href="https://github.com/ZechengLi19/Awesome-Sign-Language">GitHub</a></td>
  </tr>
</table>

### 💬 Language models

<table>
  <tr>
    <th>Resource</th>
    <th>Description</th>
    <th>Details</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>SpikeGPT</strong></td>
    <td>Generative language model with binary, event-driven spiking activations</td>
    <td>RWKV-based, 46M and 216M parameters</td>
    <td><a href="https://github.com/ridgerchu/SpikeGPT">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>SpikeLM (ICML 2024)</strong></td>
    <td>Fully spike-driven general language modeling</td>
    <td>Elastic bi-spiking mechanism; discriminative + generative tasks</td>
    <td><a href="https://github.com/Xingrun-Xing/SpikeLM">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>SpikeLLM (ICLR 2025)</strong></td>
    <td>Scaling SNNs to large language models via saliency-based spiking</td>
    <td>7–70B parameter LLMs</td>
    <td><a href="https://github.com/Xingrun-Xing2/SpikeLLM">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>SpikingBrain</strong></td>
    <td>Spiking brain-inspired large models for long-context efficiency</td>
    <td>7B and 76B; hybrid linear attention, MoE, spike coding; weights released</td>
    <td><a href="https://github.com/BICLab/SpikingBrain-7B">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>SpikingBERT (AAAI 2024)</strong></td>
    <td>Spiking BERT trained by distillation with implicit differentiation</td>
    <td>Encoder-only; evaluated on GLUE</td>
    <td><a href="https://github.com/NeuroCompLab-psu/SpikingBERT">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>SpikeBERT</strong></td>
    <td>Language Spikformer learned from BERT via knowledge distillation</td>
    <td>Two-stage pre-training + task-specific distillation</td>
    <td><a href="https://github.com/Lvchangze/SpikeBERT">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>MatMul-free LM</strong></td>
    <td>Scalable matmul-free language model, mapped to neuromorphic hardware</td>
    <td>Ternary weights; runs on Intel Loihi 2</td>
    <td><a href="https://arxiv.org/abs/2406.02528">Paper</a></td>
  </tr>
  <tr>
    <td><strong>LLMs on Loihi 2</strong></td>
    <td>Neuromorphic principles for efficient LLMs on Intel Loihi 2</td>
    <td>370M model; ~3× throughput, 2× less energy vs. edge GPU</td>
    <td><a href="https://arxiv.org/abs/2503.18002">Paper</a></td>
  </tr>
  <tr>
    <td><strong>event2vec</strong></td>
    <td>Word2vec-style embedding of events, bridging event data and NLP</td>
    <td>Evaluated on ASL-DVS; aimed at event input to LLMs</td>
    <td><a href="https://github.com/fangwei123456/event2vec">GitHub</a></td>
  </tr>
  <tr>
    <td><strong>Awesome-Spiking-Neural-Networks</strong></td>
    <td>Maintained SNN paper list, including spiking LLMs</td>
    <td>Updated with 2026 conference papers</td>
    <td><a href="https://github.com/TheBrainLab/Awesome-Spiking-Neural-Networks">GitHub</a></td>
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
