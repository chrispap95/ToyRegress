for use with root 6.10.04 (CMSSW_9_3_2)


setup a cmssw release
    cmsrel CMSSW_9_3_2
    cd CMSSW_9_3_2/src
    cmsenv

get the repository
    git clone https://github.com/saraheno/ToyRegress.git


cd to the area
   cd ToyRegress


make the toy data
   make
   ./main


run the regression
  root.exe
     > .L TMVARegression.C
     > TMVARegression("BDT")