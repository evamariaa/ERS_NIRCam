# ERS_NIRCam
Demonstration to duplicate the data reduction of a transit of WASP-39b observed with NIRCam/F322W2 as part of the JWST Transiting Exoplanet Early Release Science Program (ERS 1366). This demonstration follows the data reduction with Eureka! presented in Ahrer et al. (2022).

Run the following commands to get started! These commands set up an environment with Eureka! v0.5 - see the Eureka! documentation at https://eurekadocs.readthedocs.io/en/latest/index.html for more information.

```
conda create -n ers-nircam python==3.9.7
conda activate ers-nircam
conda install jupyter
git clone -b v0.5 https://github.com/kevin218/Eureka.git
cd Eureka
pip install -e '.[jwst]'
cd ..
```

Ensure you are in the correct environment with ```conda env list```!
