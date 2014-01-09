# ConGeometricAutoDimension
A Pointwise Glyph script to auto-dimension a selected connector with a geometric distribution function.

After selecting a connector, user inputs: the end spacings, max spacing, a growth rate, and desired number of grid levels.

The objective is to produce a distribution which increases from the end spacings up to the max spacing from either or both ends of the connector.

This requires determining the number of layers from each end and the connector dimension; a tedious trial and error activity if done interactively.  In addition, a calculation with logarithms is required for the number of layers.

The required dimension will be determined and then increased, if requested, to facilitate grid sequencing.
   
There is no "Cancel" or undo internal to the script. If you don't like what happens, click "Done" and undo the script execution directly in Pointwise.

![ScriptImage](https://raw.github.com/pointwise/ConGeometricAutoDimension/master/ScriptImage.png)

## Disclaimer
Scripts are freely provided. They are not supported products of
Pointwise, Inc. Some scripts have been written and contributed by third
parties outside of Pointwise's control.

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, POINTWISE DISCLAIMS
ALL WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED
TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE, WITH REGARD TO THESE SCRIPTS. TO THE MAXIMUM EXTENT PERMITTED
BY APPLICABLE LAW, IN NO EVENT SHALL POINTWISE BE LIABLE TO ANY PARTY
FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES
WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF BUSINESS
INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR
INABILITY TO USE THESE SCRIPTS EVEN IF POINTWISE HAS BEEN ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES AND REGARDLESS OF THE FAULT OR NEGLIGENCE OF
POINTWISE.
	 

