# ObstructionDetect
Initial sketch of an idea to enable lab robots with a vision system to detect an obstruction before approaching an instrument. Could also detect obstructions before an instrument opens a door or drawer, eg a plate reader. Checkerboards are placed in each 'keep clear' area, and the vision system looks for these and detects if the board is clear. A decision can be then made if it is safe to trigger the automation's next action.
A beneficial side effect is that the checkerboards act as a visual cue to the lab users as to where they can and cannot place labware.

Uses the excellent Checkrboard code by Lambdaloop https://github.com/lambdaloop/checkerboard and Skew Correction by Ashuta https://blog.ekbana.com/skew-correction-using-corner-detectors-and-homography-fda345e42e65
Apologies to both authors of the above excellent code, my glue is appauling, but it demonstrates a principle.
Apologies also for the images used. Stuck in lockdown, I used what resources I had.
