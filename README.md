# Easy-for-beast-input
Costume script with sloved bugs for preparing input file for Beast2 from [dongwei1220/EasySpeciesTree](https://github.com/dongwei1220/EasySpeciesTree)
Easily construct the ML species tree with all single-copy genes shared by different species

## Usage
Please modify the path for all dependent softwares and prepare the `SpeciesID prefix file` to offer the prefix of all abbreviated species id. 

```
Usage: EasySpeciesTree [-h] -in1 INPUT1 -in2 INPUT2 -in3 INPUT3 -in4 INPUT4
                       [-t THREAD] [-nb BOOTSTRAP] [-m MODEL]
-------------------------------------------------------------------------------------------------------
EasySpeciesTree <SingleCopyOrtho> <Orthogroups> <protein file> [thread] [bootstrap] [model]
Author: Wei Dong <1369852697@qq.com>, FAFU
Co-author: Yujie Huang <yujiehuang@zju.edu.cn>, ZJU
Version: v2.0
Easily construct the ML species tree with all single-copy gene's protein sequences
-------------------------------------------------------------------------------------------------------

optional arguments:
  -h, --help            show this help message and exit
  -in1 INPUT1, --input1 INPUT1
                        offer the prefix of all abbreviated species id 
  -in2 INPUT2, --input2 INPUT2
                        offer the Single-copy Orthogroups file, SingleCopyOrthogroups.txt
  -in3 INPUT3, --input3 INPUT3
                        offer the all Orthogroups file, Orthogroups.csv
  -in4 INPUT4, --input4 INPUT4
                        offer all species protein sequences
  -t THREAD, --thread THREAD
                        set the number of thread, default=10
  -nb BOOTSTRAP, --bootstrap BOOTSTRAP
                        set the number of bootstrap, default=100
  -m MODEL, --model MODEL
                        set the model of amino acid substitution, default=PROTGAMMAJTT
 ```
