# POP_Housing

Photopolymer Open-Source Pressure (POP) Housing
designed by Breanna Motsenbocker at the University of Rhode Island
Undersea Robotics and Imaging Lab

POP is a compact pressure housing that has been successfully tested to 4000 psi
(~2600 msw). The design provided here is essentially a baseline that can be modified for various
applications. It was designed in Fusion360 and can be manufactured using SLA 
3D printing. The internal volume can hold a battery
and a Raspberry Pi Zero control board (or other similarly sized PCBs).

There are 3 components to POP: the main body, end cap, and collar. The main
body has mounting points on it that can be used with 1/4" bolts. The
end cap has a dash 226 O-Ring groove. The collar screws the end cap and main body
together to ensure the O-Ring is compressed to create a seal. The end cap
can be modified to add in pass throughs (for bulkheads, ribbon cables, fiber
optic cables, etc.) and attach sensors/instrumentation. This way the user could print one
main body and simply switch end caps depending on the use. 

This respository contains the .f3d (Fusion360), .stl, and .form (PreForm) files for each piece. 
The PreForm files show the optimal printing orientation we have found
to keep the O-Ring groove/surface clean. There are supports on the threads of the 
collar and main body so I recommend sanding them down and screwing the collar on and
off a few times to wear down the supports.

Note: PreForm may give you an error that the main body .stl has an integrity issue,
this is a superficial problem and will not impact the housing. If you have questions
about this feel free to contact me.

