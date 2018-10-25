# TouchDesigner to Node-Red Communication Example
Example of sending data from TouchDesigner to Node Red

## Node Red Flow
A sample Node-Red Flow that receives data from TouchDesigner and creates a dynamic table from this can be found in `node-red-flow.json`.
Note that this requires the use of the Dashboard library from NR.

## Sending Table DATA from TouchDesigner
A sample TOX for collecting data form a table and sending this as a JSON blog to Node Red can be found in `base_status_from_TD_to_NR.tox`.
In addition to sending the data, this noisily generates some fake information for the sake of visualization.