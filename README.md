# New_CLEAN
## Procedure

**Note**:
This source code was developed in Linux, and has been tested in Centos with Python 3.10.

1. Clone the repository

        git clone https://github.com/Biologicalbigdata/New_CLEAN.git
2. Create and activate virtual environment 

        conda env create -f environment.yml
        conda activate new_clean

3. To use gpus properly, install the pytorch and cuda for your gpus. This code was tested on pytorch=2.4.0 using cuda version 12.4
   
## Example

- Run New_CLEAN 

        python test.py 
        

