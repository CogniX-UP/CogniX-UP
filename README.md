<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/CogniX-UP/CogniX-UP/assets/136436261/99843624-b6c8-4656-8f3f-87129239a2bb">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/CogniX-UP/CogniX-UP/assets/136436261/59b85295-2208-429f-bb54-1939b683ad92">
  <img alt="cognix logo" src="https://github.com/CogniX-UP/CogniX-UP/assets/136436261/59b85295-2208-429f-bb54-1939b683ad92">
</picture>
</p>

Welcome to the Cognix project, a software platform for the design and evaluation of offline or streaming data-flow systems, with a focus on the analysis of EEG and Eye-Gaze signals. Development eventually led to various subsystems that can be utilized outside of these domains. As a result, the Cognix platform is composed of several repositories, each handling a different aspect of the system. Below is a summary of each repository:

### [CognixCore](https://github.com/CogniX-Up/cognixcore)

A Python library for offline and streaming graph-based processing and evaluation, designed for modern flow-based/node-based scenarios. It is the driving force behind the [CogniX](http://cognix.gr) project, but was designed with extensibility and modularity in mind. This library started as a fork of [ryvencore](https://github.com/leon-thomm/ryvencore), with additional functionality. Due to requirements that introduced breaking changes and deviation from the original source, the [fork](https://github.com/HeftyCoder/ryvencore/tree/cognix) was moved to a stand-alone repository.

### [CognixLib](https://github.com/CogniX-Up/cognixlib)

Cognixlib is a python package and library designed to help with the offline or online analysis of EEG and Eye-Gaze signals. It emerged as a deliverable of the [CogniX](http://www.cognix.gr) project. It provides a scripting API that helps in the manipulation, filtering or general transformation of various kind of biophysical signals, currently specialized for EEG and Eye-Gaze. It also provides a node-based API created using the scripting API and [cognixcore](https://github.com/CogniX-Up/cognixcore). The original commit history can be found in a [fork](https://github.com/HeftyCoder/Ryven/tree/cognix). After initial development it was moved to this standalone repository. Much of the library is still being tested and improved on, so you can expect breaking changes.

### [Cognix Editor](https://github.com/CogniX-Up/cognix-editor)

Data-Flow Programming Editor for cognixcore; For graph evaluation in offline and streaming scenarios 

## Getting Started

To get started with the Cognix platform, follow the instructions in the individual repositories linked above.

## License

The Cognix platform is licensed under the GNU General Public License v3.0. See the LICENSE file in each repository for more details.

## Acknowledgments 

COGNIX stands for "Electroencephalography and Eye Gaze-driven Framework for Intelligent and Real-Time Human Cognitive Modelling", which is a research project financially supported by the Hellenic Foundation for Research and Innovation (H.F.R.I.).

The project has been approved to Support Faculty Members and Researchers in the field of Engineering Sciences and Technology. The project is coordinated by the University of Patras (Greece), with external collaborating partners Cognitive UX GmbH (Germany) and the University of Cyprus (Cyprus). 

<p align="center">
<img alt="hfri funding body logo" width="200px" src="https://github.com/CogniX-UP/CogniX-UP/assets/136436261/fb96eb51-dc2e-4b4e-b208-e843b8ca6899" />
</p>

