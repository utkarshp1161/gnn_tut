# gnn_tut
gnn handson

environment setup:
- conda create -n gnn_tut python==3.10 
- conda activate gnn_tut
- pip install pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.0.0+cpu.html
- pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118