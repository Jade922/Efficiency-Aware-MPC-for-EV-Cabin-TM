# Efficiency-Aware-MPC-for-EV-Cabin-TM
Cabin cooling under hot-weather conditions imposes a considerable energy demand on electric vehicles, significantly constraining driving range. This repository develops an adaptive efficiency-aware MPC strategy for automotive air-conditioning (AC) systems, integrating a control-oriented thermodynamic model, a predictive optimization framework. 

## Model Evaluation on Real-Vehicle Platform
The refrigerant and cabin air circuit physics-based models were validated against the experimental data. 
Real-vehicle experiments were conducted under four representative operating conditions covering different vehicle velocity profiles at elevated ambient temperature:
1) Standstill operation (0 km/h) with an ambient temperature of 40◦C; (See ModelEvl_C00_.png)
2) Constant-speed operation at 40 km/h with an ambient temperature of 40◦C;  (See "ModelEvl_C40_.png")
3) Constant-speed operation at 80 km/h with an ambient temperature of 40◦C;  (See "ModelEvl_C80_.png")
4) CLTC driving cycle with an ambient temperature of 38◦C. (See "ModelEvl_CLTC_.png")

The proposed control-oriented models accurately predict the evaporator wall temperature $T_{ev}$, cabin air temperature $T_{ca}$, compressor speed $\omega_{mp}$, and air temperature near the driver’s head $T_{hum}$, achieving maximum normalized RMSE values of 8.90%, 6.85%, 8.82%, and 4.27%, respectively
