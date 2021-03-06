# IfcAnnotationTypeEnum

This enumeration defines the different types of Annotation elements an _IfcAnnotation_ object can represent.

## Items

### ASSUMEDPOINT
A single extra point (assumption or interpretation), used to complement survey data in initial state modelling.

### ASBUILTAREA
A set of as-built survey points on a surface.

### ASBUILTLINE
A set of as-built survey points on a line (e.g. breakline).

### NON_PHYSICAL_SIGNAL
A virtual or fictitious signal. As opposed to the physical signal, the non-physical signal does not need to send information to the train. E.g. a fictitious signal on the signalman's display needed to define the route exit towards open line where there's no real signal. A virtual ERTMS L2 signal is also a non-physical signal but can have a physical presence, i.e. a stop marker board along the track.

### ASSUMEDLINE
A set of extra points on a line (breakline) as an assumption or interpretation, used to complement survey data in initial state modelling.

### WIDTHEVENT
A kind of event that specifies the width at a specific location along a road alignment, and the type of transition from the previous location. The locations are specified using an IfcLinearPlacement measured along the alignment axis curve.
The element(s) that are affected by the width event is currently proposed to be specified by containing the event in a specific lateral breakdown element of the road spatial structure (e.g. a Lane or the entire carriageway).

### ASSUMEDAREA


### SUPERELEVATIONEVENT
A kind of event that specifies the superelevation (cross slope) at a specific location along a road alignment, and the type of transition from the previous location. The locations are specified using an IfcLinearPlacement measured along the alignment axis curve.

The element(s) that are affected by the superelevation event is currently proposed to be specified by containing the event in a specific lateral breakdown element of the road spatial structure (e.g. a Lane).

### ASBUILTPOINT
A single as-built survey point.

### USERDEFINED


### NOTDEFINED

