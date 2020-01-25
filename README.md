# AutoSampler
AutoSampler Simulator

<<<<<<< Updated upstream
Purpose: To Emulate AutoSampler HW/SW system

Physical Control Components [and discrete representative states]:
- Gripper [opened, closed]
- Gripper Extender [Sampler, Carousel, Riser Space, Warmer]
- Gripper Escalator [Top, Above Tubes, Mid Tube, Sampler]

Physical Detection Components [and functional outputs]
- Tube Detector Check [Present, Empty]

Trial Emulation #1: use of the "processing" (visual coding) language
Architectural Design: FSM Event Driven
=======
Emulation of the HW/SW protocol required for moving sample tubes from a rotating carousel to a tube warmer to a tube sampler

Physical Components (and their respective states)
- Gripper [open, close]
- Gripper extension [sampler, riser space, carousel, warmer]
- Gripper escalator [sampler, mid-tube, above top tube, top]
- Carousel Tube Detector [tube detected, tube not-detected]

Initial trail using processing 
Software Design Pattern: FSM event driven


>>>>>>> Stashed changes
