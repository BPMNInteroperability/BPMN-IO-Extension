# BPMN-IO-Extension
These extensions of BPMN 2.0 are intended to represent interoperability in models made with BPMN2 Modeler. They are linked to the the work readable at : https://tel.archives-ouvertes.fr/tel-02122344
The dataInteroperabilityBarrier extension is used to represent an exchanged data with an interoperability problem. This extension is related to two tasks by a Data Association.
The dataInteroperabilityResolved extension is used to represent an exchanged data for which an interoperability problem has been resolved. This extension is related to two tasks by a Data Association.
The purpose of the performanceMeasurement extension is to display performance metrics for cost, time, quality, and reliability for the tasks or subgroups of tasks that are affected by these data exchanges.
The performanceAssociation extension is used to link the performanceMeasurement extension to the corresponding tasks or subgroups.

The first two extensions do not have different properties than a classic Data Object.
The performanceMeasurement values change in the properties of this extension.
Note that when modifying the values for the first time, the outline of the extension appears in red dashed lines. But if you close the model (after saving it) and open it again, the outline appears normally.
