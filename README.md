# Gmod Animations Sit&Сidle fix for small models
Just shitty Blender Proj

# ONLY FOR F_ANM, im lazy to do for m_anm

# Without fix

https://github.com/DiskInsideHead/gmod-animations-sit-cidle-fix/assets/138657329/947090df-d87f-4d18-9907-1f1cb7439130

# With fix

https://github.com/DiskInsideHead/gmod-animations-sit-cidle-fix/assets/138657329/fa145d95-6c9b-4d23-a126-a11100aa2629

# Anyway listen user how to handle these two projects

1. Open sit_and_pose.blend

2. Looked at the two variables sit_up_mod and sit_up_mod_plus. sit_up_mod is basic, the second sit_up_mod_plus is additive and affects the animations sit, sit_zen, sit_rollercoaster, pose_ducking_02 because they are located a little lower than the others.

3. Changed the variables to the desired ones, clicked the arrow and export.

4. Repeat with cidle_cwalk.blend, there everything is simpler, there is only one variable!

5. Rename the anims folder to anims_fix

6. Throw anims_fix in the compilation directory of the model.

7. Throw anims_sit_fix.qci into the model compilation directory.

8. In the main QC after $includemodel "f_anm.mdl" write $include "anims_sit_fix.qci".
   
9. Compile



