steps to enter openlane

<img width="705" height="60" alt="image" src="https://github.com/user-attachments/assets/bca31dbe-2563-43d2-a06a-8cc3b14244c6" />
<img width="295" height="57" alt="image" src="https://github.com/user-attachments/assets/1339a04f-5222-4d54-a885-9c5039b48f4e" />

Then, run_synthesis, run_floorplan, run_placement.

in openlane folder, magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def &

<img width="879" height="65" alt="image" src="https://github.com/user-attachments/assets/dfbc30d6-450d-4131-a66d-dae1cc52468e" />

magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &

Zoom in and out with z and shift+z
To enter magic commands, type a : and then the command, then press enter. You will see what you type appear in the console below. 
Press the S key to select the entire die and then V to center the view, and then Z to zoom.



<img width="568" height="506" alt="image" src="https://github.com/user-attachments/assets/10073026-4aa1-414c-b390-d7e91176874c" />
<img width="559" height="561" alt="image" src="https://github.com/user-attachments/assets/5b17345f-4b7e-443d-90e3-43f8f4518dcb" />
<img width="593" height="221" alt="image" src="https://github.com/user-attachments/assets/2655fe36-a0f9-49c9-8ef9-9ce0ae4b5cff" />
<img width="1003" height="687" alt="image" src="https://github.com/user-attachments/assets/4ed96134-720e-4614-aaa3-a8e63bf3d997" />
