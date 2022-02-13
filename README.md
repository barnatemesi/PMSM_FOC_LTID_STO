# PMSM_FOC_LTID_STO
FOC control of a PMSM motor including a second-order SMO (STO). It was implemented in MATLAB/Simulink 2018b.

The estimated load is used for feedforward load-torque compensation. The used Sliding Mode Observer is of second-order.

A short design documentation is attached, however, this algorithm is in pre-alpha release. So, the documentation is not complete as of now.
The design is an extension of the following publication: A New Load Torque Identification Sliding Mode Observer for Permanent Magnet Synchronous Machine Drive System. Published by an AAU (Denmark) / Zhejiang Sci-Tech University (Hangzhou, China) based research group. You can find it in IEEE Transactions on Power Electronics, vol. 34, no. 8, journal.

Initialization is done in: Model Properties / Callbacks / InitFcn*
