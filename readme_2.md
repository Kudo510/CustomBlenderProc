

create folder cc_textures 
create folder resources/output 
blenderproc download cc_textures output_dir=cc_textures 

correct in 
home/cuong.van-dam/blender/blender-3.5.1-linux-x64/custom-python-packages/lib/python3.10/site-packages/bop_toolkit_lib/dataset_params.py

blenderproc run examples/datasets/bop_challenge/main_itodd_random.py /home/cuong.van-dam/CuongVanDam/do_an_tot_nghiep/cnos/datasets/bop23_challenge/datasets/ resources/cc_textures resources/output --num_scenes=25


add the path to /home/cuong.van-dam/CuongVanDam/do_an_tot_nghiep/cnos/datasets/bop23_challenge/datasets/
change the name from icbin to the one u want as banjinjian in the main_icbin_random.py
"/home/cuong.van-dam/blender/blender-3.5.1-linux-x64/custom-python-packages/lib/python3.10/site-packages/bop_toolkit_lib/dataset_params.py"

"/home/cuong.van-dam/blender/blender-3.5.1-linux-x64/custom-python-packages/lib/python3.10/site-packages/bop_toolkit_lib/dataset_params.py", line 98, in get_model_params

/home/cuong.van-dam/blender/blender-3.5.1-linux-x64/custom-python-packages/lib/python3.10/site-packages/bop_toolkit_lib/dataset_params.py", line 75, in get_model_params

textures to use
resources/cc_textures/Tiles110
resources/cc_textures/MetalPlates004