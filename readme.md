### EQ1979 jsfx plugin

-----

## Use the Github "Release" download link to get the plugin.
Plugin works with external files located in /data folder.

-----

Frequency accurate modeling of a Neve 1073 filter stage combined with an input gain-compensated saturation.
Designed by cascading ~30 peq/butterworth filters to reproduce frequency response, bumps and drops of the original console strip.
Input saturation based on "arctan" modeling, which is gain-compensated. Includes additional independant gain trimming.

Controls :
- Left mouse button to change knob value, right mouse button resets control.
- Frequency bands for Mid and Low and gain trimming is done using mouse wheel.

Versions :
- Beta 0.96
  - New slick GUI By Fluidshell Design !
  - Improved saturation with progressive bias error
  - Electrical components noise modeling added
  - Frequency band controls can now be set/reset using mouse click too (mousewheel still).
  - Right clicking on the lower right corner of the UI displays/hides reaper native slider controls.
- Beta 0.95
  - Improved modeling of HPF and Low Shelf filter responses
  - 10Hz parameter smoothing on Low, Mid and High frequency gain parameters for automation-safe operation
- Beta 0.94 - internal bugfixing stage never released
- Beta 0.93
  - HPF frequency response tuned with expected bump
  - Testing parameter smoothing on HPF
  - Correcting minor GUI bugs on switching to +-16dB for shelfs
- Beta 0.92 :
  - GUI : Added mousex lock on control change, no more control swapping when adjusting parameter
  - Lowered low and high shelf EQ max gain down to 16dB as per original 1073 design
  - Added EQ On/Off and Phase buttons as per original 1073 design
  - minor tweaks
- Beta 0.91 - Low Shelf GUI Fix and Sat mouse speed increase by 25%
- Beta 0.9 - First release

To Do :
- Update saturation model to match harmonics brought by the Neve input gain stage / transformer

Dependecies :
Filter methods are derived from Oliver Belanger's COOKDSP library - Copyright (c) - 2014 - Olivier Belanger
