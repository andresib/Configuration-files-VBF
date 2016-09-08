# Event Selection used with these configuration files

No trigger is applied on MC
Exactly  ̔1 ̔ electron with eta<2.1, Pt>10 GeV,
Tau eta<2.1 with Pt >20 GeV and eta <2.1, Pt>8 GeV for Muons
Require no b-jets with pT > 20 GeV, using the loose working point of the CSV algorithm (0.460). 
No cuts on muons, taus and Central Jets
Overlap removal applied
MET>180 GeV
VBF cuts:  two jets with pT > 60 GeV |Delta_eta(j1, j2)| > 4.2, eta(j1)*eta(j2) < 0., Mjj > 1 TeV. 
Gen_weight applied for three amcatNLO samples and TTbar
0<Iso<0.3, Loose, and Tight cut based working points scanned

```
1. export SCRAM_ARCH=slc6_amd64_gcc530 
2. cmsrel CMSSW_8_0_10
3. cd CMSSW_8_0_10/src
4. cmsenv
5. source /cvmfs/cms.cern.ch/crab3/crab.sh
6. git clone https://github.com/dteague/Generation
7. cd Generation
8. git checkout Condor80x
9. cp -r Fastsim_Grid/ ..
10. cd ../Fastsim_Grid
11. ./setup.sh
```
