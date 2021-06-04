# ConGeometricAutoDimension
Copyright 2021 Cadence Design Systems, Inc. All rights reserved worldwide.

A Pointwise Glyph script to auto-dimension a selected connector with a geometric distribution function.

After selecting a connector, user inputs: the end spacings, max spacing, a growth rate, and desired number of grid levels.

The objective is to produce a distribution which increases from the end spacings up to the max spacing from either or both ends of the connector.

This requires determining the number of layers from each end and the connector dimension; a tedious trial and error activity if done interactively.  In addition, a calculation with logarithms is required for the number of layers.

The required dimension will be determined and then increased, if requested, to facilitate grid sequencing.
   
There is no "Cancel" or undo internal to the script. If you don't like what happens, click "Done" and undo the script execution directly in Pointwise.

![ScriptImage](https://raw.github.com/pointwise/ConGeometricAutoDimension/master/ScriptImage.png)

## Disclaimer
This file is licensed under the Cadence Public License Version 1.0 (the "License"), a copy of which is found in the LICENSE file, and is distributed "AS IS." 
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, CADENCE DISCLAIMS ALL WARRANTIES AND IN NO EVENT SHALL BE LIABLE TO ANY PARTY FOR ANY DAMAGES ARISING OUT OF OR RELATING TO USE OF THIS FILE. 
Please see the License for the full text of applicable terms.
