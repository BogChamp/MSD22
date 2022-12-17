# MSD22

KL_CPD.ipynb depends on: data_loader.py, klcpd.py, median_heuristic.py, mmd_utils.py, optim.py, run_klcpd.py and util.py.


Additionaly, the notebook depends on original GitHub repository of Kental Change-point detection by Wei-Cheng Chang, Chun-Liang Li, Yiming Yang & Barnabás Póczos.


Logs of previous exeperiments are available in exeperiment_log directory.

To reevaluate results from TSCP https://arxiv.org/pdf/2011.14097.pdf article, open TSCP.ipynb. All needed code is there. To change settings, find cell with parameters and set them on needed. Then you can run all cells, final cell of notebook will give you f1 score.

To run experiments with Barlow Twins + TSCP, open BarlowTSCP.ipynb file. Similar to simple TSCP, you can change settings and then run all cells. 
