# ms-thesis-rrlab
My master thesis carried out at the Robotics Research Lab at RPTU Kaiserslautern-Landau titled: Reinforcement Learning on Sensor Data and Reaction Grid Maps.
I will be adding the code gradually. Due to proprietary reasons, .cpp and .h files that are related to finroc are not included. If this code should be needed, please contact me, I will have to consult the AG Robotersysteme. 

## Project
UE5FinRl/
├── gFinRlUE5DMapInterface.cpp
├── gFinRlUE5DMapInterface.h
├── make.xml
├── mFinRlSocket.cpp
├── mFinRlSocket.h
├── pDMapInterface.cpp
└── AutoBusEnv/
    ├── AutoBusEnvContActionSpace.py
    ├── AutoBusEnvMultidiscActionSpace.py
    ├── AutoBusEnvMultidiscActionSpaceUnstacked.py
    ├── test_env.py
    ├── train.py
    ├── eval_autobus_v3.py
    ├── eval_autobus_v4_taf.py
    ├── eval_data/
    │   ├── eval_postprocess.py
    │   ├── csv1.csv
    │   └── ...
    ├── export.py
    ├── inference.py
    ├── onnx_models/
    ├── plot.py
    ├── PyServer.py
    └── runs/
        └── ppo/
            ├── experiment_1/
            ├── experiment_2/
            └── ...
        └── vis/
            └── export_svg.py


