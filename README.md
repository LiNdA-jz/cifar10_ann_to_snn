# cifar10_ann_to_snn
2022 UoM 3rd Year Project

Jiayi Zhang

## run the file
The "cifar10_ann_to_snn.ipynb" file is the file to be run. It could be run on Google Colab. By clicking on the "Run all" command, the code will be run automatically. The results of the classification will be displayed when the code finishes running. The number of tests to be run could be changed by editing the parameter "num_to_test" in "config['simulation']". Currently, it runs for 600 tests and it would take more than half an hour to run. 

## references
The code is based on the paper "Conversion of Continuous-Valued Deep Networks to Efficient Event-Driven Networks for Image Classification" [1] and the git repository of the snntoolbox [2].

[1] Rueckauer, B. and Hu, Y. and Lungu, I.A. and Pfeiffer, M. and Liu, S.-C., Conversion of continuous-valued deep networks to efficient event-driven networks for image classification, Front. Neurosci., 2017, doi: 10.3389/fnins.2017.00682

[2] Rueckauer, B. and Hu, Y. and Lungu, I.A. and Tumu, N. and Orth, M. and Renner, A. and Olin-Ammentorp, W., snn_toolbox, 2021, URL: https://github.com/NeuromorphicProcessorProject/snn_toolbox.
