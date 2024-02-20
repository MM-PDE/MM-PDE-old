# Better Neural PDE Solvers Through Data-Free Mesh Movers

⚠️⚠️⚠️ This is an old version. The new code can be found at https://github.com/Peiyannn/MM-PDE.git. 

## Data-free Mesh Mover (DMM)
- Burgers' equation:  
  cd mesh  
  python dmm.py 
- Flow around a cylinder:  
  cd mesh  
  python dmm.py --experiment cy --train_sample_grid 1500 --branch_layers 4,3 --trunk_layers 16,512

## MM-PDE
- Burgers' equation:  
  python mmpde.py
- Flow around a cylinder:  
  python mmpde.py --experiment cy --base_resolution 30,2521


