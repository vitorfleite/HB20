# Hyundai HB20 (2019) CAN bus description
The Hyundai HB20 ("HB" stands for "Hyundai Brasil") is a subcompact by Korean manufacturer Hyundai Motor Company, which was launched in 2012. It is Hyundai’s third vehicle produced in Brazil and has flexible-fuel engines, therefore it was not exported to other South American countries until 2016, when it began to be sold in Paraguay and Uruguay.

CANid,bytes  
0x0a0,8,[1]  
0x0a1,8,[2]  
0x18f,8,[3]  
0x260,8,[4]  
0x2a0,8,[5]  
0x2c0,8,[6]  
0x316,8,[7]  
0x329,8,[8]  
0x545,8,[9]  
0x580,8,[10]  
0x5a0,8,[11]  
0x690,8,[12]  
0x5a2,4,[13]  


[1]  
rpm?

[2]  
map?

[3]  
BO_ 399 EMS_H12: 8 EMS
 SG_ R_TqAcnApvC : 0|8@1+ (0.2,0.0) [0.0|51.0] "Nm"  DATC,IBOX
 SG_ R_PAcnC : 8|8@1+ (125.0,0.0) [0.0|31875.0] "hPa"  DATC,IBOX
 SG_ TQI_B : 16|8@1+ (0.390625,0.0) [0.0|99.609375] "%"  ABS,ESC,IBOX
 SG_ SLD_VS : 24|8@1+ (1.0,0.0) [0.0|255.0] "km/h"  CLU,IBOX
 SG_ CF_CdaStat : 32|3@1+ (1.0,0.0) [0.0|7.0] ""  AEMC,IBOX,TCU
 SG_ CF_Ems_IsgStat : 35|3@1+ (1.0,0.0) [0.0|7.0] ""  ABS,BCM,CLU,DATC,EPB,ESC,IBOX,LDWS_LKAS,MDPS,SMK,TCU
 SG_ CF_Ems_OilChg : 38|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_EtcLimpMod : 39|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ R_NEngIdlTgC : 40|8@1+ (10.0,0.0) [0.0|2550.0] "rpm"  DATC,IBOX,TCU
 SG_ CF_Ems_UpTarGr : 48|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_DownTarGr : 49|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_DesCurGr : 50|4@1+ (1.0,0.0) [0.0|15.0] ""  CLU,IBOX
 SG_ CF_Ems_SldAct : 54|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_SldPosAct : 55|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_HPresStat : 56|1@1+ (1.0,0.0) [0.0|1.0] ""  IBOX,TCU
 SG_ CF_Ems_IsgBuz : 57|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_IdlStpFCO : 58|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_FCopen : 59|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX
 SG_ CF_Ems_ActEcoAct : 60|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX,TCU
 SG_ CF_Ems_EngRunNorm : 61|1@1+ (1.0,0.0) [0.0|1.0] ""  ABS,ESC,IBOX,TCU
 SG_ CF_Ems_IsgStat2 : 62|2@1+ (2.0,0.0) [0.0|3.0] ""  CLU,IBOX,TCU
  
  
 [4]  
 
 BO_ 608 EMS16: 8 EMS
 SG_ TQI_MIN : 0|8@1+ (0.390625,0.0) [0.0|99.609375] "%"  ESC,IBOX,TCU
 SG_ TQI : 8|8@1+ (0.390625,0.0) [0.0|99.609375] "%"  ESC,IBOX,TCU
 SG_ TQI_TARGET : 16|8@1+ (0.390625,0.0) [0.0|99.609375] "%"  EPB,ESC,IBOX,TCU
 SG_ GLOW_STAT : 24|1@1+ (1.0,0.0) [0.0|1.0] ""  BCM,CLU,IBOX,SMK
 SG_ CRUISE_LAMP_M : 25|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX,TCU
 SG_ CRUISE_LAMP_S : 26|1@1+ (1.0,0.0) [0.0|1.0] ""  CLU,IBOX,TCU
 SG_ PRE_FUEL_CUT_IN : 27|1@1+ (1.0,0.0) [0.0|1.0] ""  IBOX,TCU
 SG_ ENG_STAT : 28|3@1+ (1.0,0.0) [0.0|7.0] ""  ABS,AHLS,AVM,BCM,CLU,EPB,ESC,EVP,FPCM,IBOX,LCA,LDWS_LKAS,MDPS,SCC,SMK,TCU
 SG_ SOAK_TIME_ERROR : 31|1@1+ (1.0,0.0) [0.0|1.0] ""  DATC,EPB,IBOX,TCU
 SG_ SOAK_TIME : 32|8@1+ (1.0,0.0) [0.0|255.0] "Min"  _4WD,DATC,EPB,IBOX,TCU
 SG_ TQI_MAX : 40|8@1+ (0.390625,0.0) [0.0|99.609375] "%"  ESC,IBOX,TCU
 SG_ SPK_TIME_CUR : 48|8@1+ (0.375,-35.625) [-35.625|60.0] ""  IBOX,TCU
 SG_ Checksum : 56|4@1+ (1.0,0.0) [0.0|15.0] ""  ECS,IBOX,LDWS_LKAS,MDPS,SCC
 SG_ AliveCounter : 60|2@1+ (1.0,0.0) [0.0|3.0] ""  IBOX,LDWS_LKAS,MDPS,SCC
 SG_ CF_Ems_AclAct : 62|2@1+ (1.0,0.0) [0.0|3.0] ""  IBOX,SCC
 
 [5] 
 
 ?
 
 [6]
 
 ?
 
 [7] Ignition key?
 BO_ 790 EMS1: 8 XXX
    SG_ SWI_IGK : 0|1@1+ (1,0) [0|1] "" XXX
    SG_ F_N_ENG : 1|1@1+ (1,0) [0|1] "" XXX
    SG_ ACK_TCS : 2|1@1+ (1,0) [0|1] "" XXX
    SG_ PUC_STAT : 3|1@1+ (1,0) [0|1] "" XXX
    SG_ TQ_COR_STAT : 4|2@1+ (1,0) [0|3] "" XXX
    SG_ RLY_AC : 6|1@1+ (1,0) [0|1] "" XXX
    SG_ F_SUB_TQI : 7|1@1+ (1,0) [0|1] "" XXX
    SG_ TQI_ACOR : 8|8@1+ (0.390625,0) [0|99.6094] "%" XXX
    SG_ N : 16|16@1+ (0.25,0) [0|16383.8] "rpm" XXX
    SG_ TQI : 32|8@1+ (0.390625,0) [0|99.6094] "%" XXX
    SG_ TQFR : 40|8@1+ (0.390625,0) [0|99.6094] "%" XXX
    SG_ VS : 48|8@1+ (1,0) [0|254] "km/h" XXX
    SG_ RATIO_TQI_BAS_MAX_STND : 56|8@1+ (0.0078,0) [0|2] "" XXX
    
[8]

BO_ 809 EMS2: 8 XXX
    SG_ TQ_STND : 0|6@1+ (10,0) [0|630] "Nm" XXX
    SG_ CAN_VERS : 0|6@1+ (1,0) [0|7.7] "" XXX
    SG_ CONF_TCU : 0|6@1+ (1,0) [0|63] "" XXX
    SG_ OBD_FRF_ACK : 0|6@1+ (1,0) [0|63] "" XXX
    SG_ MUL_CODE : 6|2@1+ (1,0) [0|3] "" XXX
    SG_ TEMP_ENG : 8|8@1+ (0.75,-48) [-48|143.25] "" XXX
    SG_ MAF_FAC_ALTI_MMV : 16|8@1+ (0.00781,0) [0|1.99155] "" XXX
    SG_ VB_OFF_ACT : 24|1@1+ (1,0) [0|1] "" XXX
    SG_ ACK_ES : 25|1@1+ (1,0) [0|1] "" XXX
    SG_ CONF_MIL_FMY : 26|3@1+ (1,0) [0|7] "" XXX
    SG_ OD_OFF_REQ : 29|1@1+ (1,0) [0|1] "" XXX
    SG_ ACC_ACT : 30|1@1+ (1,0) [0|1] "" XXX
    SG_ CLU_ACK : 31|1@1+ (1,0) [0|1] "" XXX
    SG_ BRAKE_ACT : 32|2@1+ (1,0) [0|3] "" XXX
    SG_ ENG_CHR : 34|4@1+ (1,0) [0|15] "" XXX
    SG_ GP_CTL : 38|2@1+ (1,0) [0|3] "" XXX
    SG_ TPS : 40|8@1+ (0.469484,-15.0235) [-15.0235|104.695] "%" XXX
    SG_ PV_AV_CAN : 48|8@1+ (0.3906,0) [0|99.603] "%" XXX
    SG_ ENG_VOL : 56|8@1+ (0.1,0) [0|25.5] "liter" XXX
    
 [9]
 
 
BO_ 1349 EMS4: 8 XXX
    SG_ IMMO_LAMP_STAT : 0|1@1+ (1,0) [0|1] "" XXX
    SG_ L_MIL : 1|1@1+ (1,0) [0|1] "" XXX
    SG_ IM_STAT : 2|1@1+ (1,0) [0|1] "" XXX
    SG_ AMP_CAN : 3|5@1+ (10.7316,458.98) [458.98|791.66] "mmHg" XXX
    SG_ FCO : 8|16@1+ (0.128,0) [0|8388.48] "ul" XXX
    SG_ VB : 24|8@1+ (0.101563,0) [0|25.8984] "V" XXX
    SG_ TEMP_FUEL : 48|8@1+ (0.75,-48) [-48|143.25] "" XXX
    SG_ Split_Stat : 56|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Ems_IsaAct : 57|1@1+ (1,0) [0|1] "" XXX
    
[10]


[11]
BO_ 1440 ACU11: 8 ACU
 SG_ CF_Ods_SNRcv : 1|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS
 SG_ CF_Ods_IDRcv : 2|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS
 SG_ CF_Ods_RZReq : 4|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS
 SG_ CF_Abg_DepInhEnt : 6|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS
 SG_ CF_Abg_DepEnt : 7|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS
 SG_ CF_PasBkl_FltStat : 28|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS,PSB
 SG_ CF_DriBkl_FltStat : 29|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS,PSB
 SG_ CF_PasBkl_Stat : 30|1@1+ (1.0,0.0) [0.0|1.0] ""  IBOX,ODS,PSB,TMU
 SG_ CF_DriBkl_Stat : 31|1@1+ (1.0,0.0) [0.0|1.0] ""  ODS,PSB
 SG_ CF_SWL_Ind : 32|2@1+ (1.0,0.0) [0.0|3.0] ""  CUBIS,IBOX
 SG_ CF_Acu_FltStat : 34|2@1+ (1.0,0.0) [0.0|3.0] ""  CUBIS,IBOX
 SG_ CF_Acu_ExtOfSab : 36|2@1+ (1.0,0.0) [0.0|3.0] ""  BCM,CLU,CUBIS,IBOX
 SG_ CF_Acu_Dtc : 40|16@1+ (1.0,0.0) [0.0|65535.0] ""  CUBIS,IBOX
 SG_ CF_Acu_NumOfFlt : 56|8@1+ (1.0,0.0) [0.0|255.0] ""  CUBIS,IBOX


[12]

BO_ 1680 CLU2: 8 XXX
    SG_ CF_Clu_IGNSw : 0|3@1+ (1,0) [0|7] "" XXX
    SG_ RKE_CMD : 3|3@1+ (1,0) [0|7] "" XXX
    SG_ CF_Clu_DrvDrSw : 6|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_DrvKeyLockSw : 8|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_DrvKeyUnlockSw : 9|1@1+ (1,0) [0|1] "" XXX
    SG_ PIC_Lock : 10|3@1+ (1,0) [0|7] "" XXX
    SG_ PIC_Unlock : 13|3@1+ (1,0) [0|7] "" XXX
    SG_ CF_Clu_DrvSeatBeltSw : 16|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_TrunkTgSw : 18|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_AstSeatBeltSw : 20|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_HoodSw : 22|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_TurnSigLh : 24|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_TurnSigRh : 25|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_LdwsLkasSW : 26|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_WiperIntT : 27|3@1+ (1,0) [0|7] "" XXX
    SG_ CF_Clu_WiperIntSW : 30|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_WiperLow : 31|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_WiperHigh : 32|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_WiperAuto : 33|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_RainSnsStat : 34|3@1+ (1,0) [0|7] "" XXX
    SG_ CF_Clu_HeadLampLow : 37|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_HeadLampHigh : 38|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_AltLStatus : 39|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_EcoDriveInf : 40|3@1+ (1,0) [0|7] "" XXX
    SG_ CF_Clu_SwiGearR : 43|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_SWL_Stat : 45|3@1+ (1,0) [0|7] "" XXX
    SG_ CF_Clu_ActiveEcoSW : 48|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_HazardSW : 49|1@1+ (1,0) [0|1] "" XXX
    SG_ CF_Clu_AliveCnt2 : 50|4@1+ (1,0) [0|15] "" XXX
    SG_ CF_Clu_AstDrSw : 54|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_LkasDispMode : 56|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_AutoLightLevel : 58|2@1+ (1,0) [0|3] "" XXX
    SG_ CF_Clu_SunRoofOpenState : 60|1@1+ (1,0) [0|1] "" XXX
    
   [13]
   
