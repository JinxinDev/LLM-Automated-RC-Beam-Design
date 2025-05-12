# Multi-Agent Large Language Model Framework for Code-Complying Design Automation of Reinforced Concrete Structures

This repository contains supplementary materials, including a GUI demonstration, for the paper titled "Multi-Agent Large Language Model Framework for Code-Complying Design Automation of Reinforced Concrete Structures."

## Abstract

The current manual approach to designing reinforced concrete, guided by structural design codes, is inefficient and susceptible to human error. This paper presents a Large Language Model (LLM) framework to automate code-complying design and achieve interpretability and verifiability. The framework decomposes complex tasks into subtasks handled by coordinated LLM agents with specialized expertise, enabling automatic structural design and human-robot interaction for exploring alternative solutions and explanations. This framework was tested using case studies on the design and evaluation of 30 beams and compared against commercial engineering software SAP2000, demonstrating how the agents collaborate and cross-check results while maintaining high accuracy (97%), high efficiency (90% time-saving), and transparency in structural analysis and design. An intuitive Graphical User Interface (GUI) that supports natural language queries was developed to facilitate practical use. By bridging the gap between intuitive communication and rigorous structural analysis, this framework provides a paradigm shift for automatic structural design.

## GUI Demonstration

A video demonstration illustrating the functionality and user interaction with the GUI prototype is available here:


The GUI showcases:
* Inputting design or evaluation queries using natural language and OCR-enhanced image uploads.
* The "Tool Execution Status" panel indicating completed analysis steps.
* The "Key Takeaways and Recommendations" section presenting design decisions.
* Interaction with the "Further Inquiries" tab for design refinement and follow-up questions.
* The "Processing Options" for selecting different calculation validation modes.
* The "Save Design Case to Database" feature.

## About the Framework

The core of this framework is a multi-agent system where specialized LLM agents handle distinct aspects of the structural design process:
* **Task Dispatcher Agent:** Processes user queries (text and image) and routes them.
* **Structure Design Agent:** Generates new structural designs based on user requirements and code-verified tools.
* **Design Evaluation Agent:** Assesses existing structural designs against code requirements.
* **Code-based Knowledge Component:** Integrates specialized calculation tools (programmed per ACI 318-19) and code provisions.
* **Expert Consultation Agent:** Facilitates follow-up interactions and design refinements.

The system emphasizes transparency, verifiability, and adherence to design codes (specifically ACI 318-19 for the current beam design case studies).

## Repository Contents (Example Structure)

* `/README.md` - This file.
* `/gui_demonstration/`
    * `gui_demo_video.gif`
* `/supplementary_materials/` (Optional: for additional figures, detailed walkthroughs, etc.)

---

*This README provides a general overview. Please refer to the full manuscript for detailed methodology, case studies, and discussion.*
