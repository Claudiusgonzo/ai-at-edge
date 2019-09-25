---
title: "Run ONNX model with OpenVINO™ in Intel® powered hardware"
permalink: /docs/onnx_openvino/
excerpt: "Run ONNX model with OpenVINO™ in Intel® powered hardware"
variable:
  - platform: windows
    name: Windows
  - platform: macos
    name: macOS
last_modified_at: 2019-09-24
---

## Run ONNX models with OpenVINO™ in Intel® powered hardware

| **[Intel® powered Aaeon UP Squared and IEI Tank developer kits](https://software.intel.com/en-us/iot/cloud-analytics/microsoft-azure){:target="_blank"}** |  |
| :----------- |
| **Get good, better or best** Intel® powered developer kits come with one or multiple CPU choices - Atom, Core and Xeon. You can select to use the one that best fits your use case |
| **UP Squared** that comes with Intel's Atom processor is a high performance kit that provides a clear path to production, simple set up and configuration with pre-installed Ubuntu OS, expanded I/O to help with rapid prototyping, and a means to incorporate complex and advanced libraries in an intuitive fashion. All bundled into one package along with prototyping sensors with a clear path to industrial grade sensors for commercial deployments.  | ![UP2]({{ '/assets/images/devices_up2.png' | relative_url }})|
| **IEI TANK AIoT** Developer Kit ships with either Core (i5/i7) or Xeon (E3) processors with an optional vision accelerator enables analysis of more than 16 video streams, deep neural network (DNN) inferencing for AI at the edge and comes with consistent APIs and runtimes across cameras, edge appliances, and cloud solutions | ![Tank]({{ '/assets/images/devices_tank2.png' | relative_url }})| 

| Solution example |
| :----------- |
|  Intel and Microsoft joined forces to create development tools that make it easier for you to use the cloud, the edge or both, depending on your need. The latest is an execution provider (EP) plugin that integrates two valuable tools: the Intel Distribution of [OpenVINO™ toolkit](https://software.intel.com/en-us/openvino-toolkit){:target="_blank"} and [Open Neural Network Exchange](https://onnx.ai/){:target="_blank"} (ONNX) Runtime. The goal is to give you the ability to write once and deploy everywhere — in the cloud or at the edge. 
Read [Intel's blog](https://blogs.intel.com/iot/2019/08/21/intel-and-microsoft-advance-edge-to-cloud-inference-for-ai/#gs.5vaef1){:target="_blank"} regarding ONNX and OpenVINO™. |

| This solution example provides step by step instructions for enabling [ONNX](https://onnx.ai/){:target="_blank"} with on Intel powered devices. ONNX is an open format to represent deep learning models. With ONNX, AI developers can more easily move models between state-of-the-art tools and choose the combination that is best for them. ONNX is developed and supported by a community of partners. |
| [ONNX Runtime with OpenVINO™ by Microsoft](https://github.com/Azure-Samples/onnxruntime-iot-edge/blob/master/README-ONNXRUNTIME-OpenVINO.md){:target="_blank"} | 
| [ONNX Runtime with OpenVINO™ by Intel](https://github.com/intel/Edge-Analytics-FaaS/tree/R1_2019/Azure-IoT-Edge/OnnxRuntime){:target="_blank"} |

| Enable ONNX with UP Squared |
| ![Enable ONNX with UP Squared]({{ '/assets/images/devices_onnx_up2.png' | relative_url }}) |
