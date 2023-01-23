# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
[https://YourDirectionsApiURLGoesHere](https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJQZHeACWpqlYRalM6MncXJV4&waypoints=place_id:ChIJOVbG-2CiVVERWCTwlkQW7c0|via:place_id:ChIJryXYQje3VVERzqKByYOBRik&destination=place_id:ChIJgVO8gJhEVFERSzXQZOq3PeQ&arrival_time=1692969333&mode=walking&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE)
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJQZHeACWpqlYRalM6MncXJV4",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJOVbG-2CiVVERWCTwlkQW7c0",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJryXYQje3VVERzqKByYOBRik",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJgVO8gJhEVFERSzXQZOq3PeQ",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 60.71971259999999,
               "lng" : -133.9849511
            },
            "southwest" : {
               "lat" : 59.45718549999999,
               "lng" : -135.3145518
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "84.9 mi",
                  "value" : 136570
               },
               "duration" : {
                  "text" : "1 day 4 hours",
                  "value" : 101298
               },
               "end_address" : "Tagish, YT, Canada",
               "end_location" : {
                  "lat" : 60.3129506,
                  "lng" : -134.2723895
               },
               "start_address" : "Skagway, AK 99840, USA",
               "start_location" : {
                  "lat" : 59.45718549999999,
                  "lng" : -135.3145518
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "1.0 mi",
                        "value" : 1542
                     },
                     "duration" : {
                        "text" : "20 mins",
                        "value" : 1194
                     },
                     "end_location" : {
                        "lat" : 59.46728679999999,
                        "lng" : -135.3005034
                     },
                     "html_instructions" : "Head \u003cb\u003enortheast\u003c/b\u003e on \u003cb\u003eState St\u003c/b\u003e toward \u003cb\u003e8th Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mv{iJ|r{xXELo@{AGOu@cBy@oBu@eBu@gBy@eBYs@Ws@w@oBCGq@eBw@eBw@mB}@gBc@sAGQYq@Ws@EKYo@Yq@u@cBqBqEu@gBu@eBw@kBs@_Bw@eBy@{BYm@[s@EIq@cBSi@]}@w@qBm@oBq@cBm@m@KIIEKCIAO?OBODMFMHKJKJABCFKTEL[z@}@lBYn@Yl@[n@"
                     },
                     "start_location" : {
                        "lat" : 59.45718549999999,
                        "lng" : -135.3145518
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "13.1 mi",
                        "value" : 21019
                     },
                     "duration" : {
                        "text" : "5 hours 0 mins",
                        "value" : 17991
                     },
                     "end_location" : {
                        "lat" : 59.62961000000001,
                        "lng" : -135.1642401
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAlaska Rte 98\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Canada (British Columbia)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "qu}iJb{xxX[l@[j@uClFwA`CILa@b@YNSBMDA?KBO?GAc@GIAYOMESOACWWGK]g@ACS]Se@o@sAq@uAkA{Ba@s@U_@y@_Am@k@_BmA]UWQaAs@eDwBeBmAqAeAoBeBkAsAAA{AoBW]}BeD}@iA]e@]c@MO]e@]e@{ByCKMy@qA]g@[g@yAyB]g@[g@?Ay@qA]i@]g@[i@]i@CEWk@Yo@Yo@AEm@aBO_@u@cCWw@IYK[Uu@Sm@CGWu@Wu@Oe@Ws@Ws@EKSa@[m@[k@[m@OYKO]e@e@o@UY]_@cAy@]YAA_@Y?A_@UAA_@WA?_@WAAk@_@w@s@_@_@ECWYACAA[[AA]]QSMO_@e@?A[g@AA[e@?CWa@EE[a@]e@A?qAcBUSWW[UWSGEa@Ua@WCAo@_@OGc@Sa@Sa@QMGSKc@Qa@Oc@Q]OCAWIICSEOAIAW@E?S?I@M@SFSDUF]H_@HC?a@JE@[BC?K@KAI?CAE?ICGEKGGCYWIGUW_@a@KKSW]c@QSMQ]g@EIU_@OUi@}@]i@[i@GIU_@[i@a@o@W_@]g@U]GI]e@i@u@q@}@EGUa@]i@IMi@_A}@aB[k@[k@[k@[k@AAYe@]i@GKS_@c@q@U][_@CC]a@_@c@KKSS_@a@GGUYSSKO_@c@[_@AC]e@OScBwCAAw@uA[k@ACYg@[k@[k@[k@[m@Yi@Yw@?AWq@?AWw@Uw@Qk@CMSy@CMOk@Ok@EMSw@I[Sq@Mc@Qo@AEUk@CGOa@GKAAIOQUCCWWAC_@c@WWGG_@a@_@_@]a@_@a@_@_@EEw@cAIKMUEGCCWg@ACUu@CEI[YcACKUy@Oo@CKSy@GUK]ACIWMYEKSc@S_@EGIKEKCCWa@AA[g@?A]e@SYIM]g@[e@?A]c@[a@a@e@SUKI_@[KIUMcAm@GEYOa@UeAm@yAs@]W]MSGAAWCGAOCSAc@?}@CI?UCMCMCUIUIMEa@QIEWKc@Oa@OA?a@Sa@QOGQIAAMISMIGWSECYYAA]]_@a@EEYUAAYQEAUKIAYAIAc@Ec@AKAWEMCMEIECAMMKOCCS]Yo@IOUaAQo@Oo@Qc@OUCEUYCCOQOKAAYOCAQIOGSGOIKEUOa@UECw@k@ECa@Y_@Y?Aa@[a@YOMOOa@[IKUYEGUa@ACOa@EWEKKq@?AGYC_@AKAUAa@AOAWAm@?MAy@CgAA[Ai@A[Ac@?CC[GaA?AOcBG_@Iq@CMGg@EYCKEYAKOk@EOOe@IYM[IYK]CGEIISEIKWMQ]g@GIU]]g@KOOWKOQWCCGIQW]e@KOQWKMSWKOMQACMKQUKKSUKM_@a@QSGEW]KM}AiB?AmA_Bm@u@[g@W_@W]KOQYIOQa@?AISSk@Yw@i@yAo@mBGOo@gBM_@y@_CM_@Wu@Uu@k@_BCKUw@EMOk@I_@IWUw@IUM_@Qo@CGQm@CIUq@?CQi@EKK[KWGSO]Yq@KYMUQ]IIc@m@W[]a@CCYm@[k@[m@[k@Wg@CEgBiDEK[m@Yo@Ue@EGYm@[m@[m@IOO_@Qc@GMYq@MYk@mAm@sAACa@{@Yi@Ua@Wg@CEm@oAa@u@AA[k@y@uAGMYc@Uc@[k@]i@IMQ]Ua@]i@]k@CEMSOUYc@CCy@qACEYa@s@gAEG]e@GIW[QUKMUWII]c@u@_AGG_@_@_@a@QQMK_@_@_@]CC]WCCWWCC_@a@WYe@q@CCWk@ISO[Se@EI[k@[k@]g@[g@]g@GIU[_@e@]c@]c@_@c@SWIK_@a@AA]a@Y[CE_@a@_@_@IIUUq@q@MIa@[YUECa@UYQGCa@UCAaAi@cAm@cAm@q@a@QMa@Y_@Ya@Ya@Y_@YcAs@a@W]WCA_@]a@[_@[AA_@W_@[a@Ya@Y_@[cBoAa@[a@YKISOcAo@a@Ya@WEE}@g@a@Ua@U[QECa@Ua@Ua@Wa@U]QCCa@OQIQGa@OeA_@w@YMEiBm@y@Wo@UMESGeAWa@KA?c@Kc@Ka@KeAWA?c@Ka@IQEQCc@Ic@Ka@Ic@Ic@IIAYGc@Ka@OQGQIa@SEC]Sa@WSMMI_@Wa@WAA_@WGCQKGCSIMCGAUGEAYEG?MAQAC?I?S?E@]@C?c@Dq@Fy@Fc@BQ@Q@c@B]BE@o@FW@QBQBYFG@SFODa@Jc@LE@]Ja@Lc@LWHm@PC@_@JA?WDI@}AJq@Dc@Bc@Bc@Bc@@_@BeAFE?a@@e@AS?g@Cg@GG?c@ECAk@Iq@KICc@I]GE?a@Kc@Ic@Ic@Ic@Ka@IKAWGWEo@Mc@IIAWGc@Ia@GAAiB]WGKA[GGCaB[k@KaAQEAc@IWGICKAWGc@IA?q@KSAIAW@e@DQBMBGBYJA?_@R[PEBWPIF[RG@QFUHK@O@C@K?SAC?GAKAOA?A[EWKSIUKMEa@SgBw@a@QGCQGICa@Sc@Qa@Qa@Qc@Qa@QgAe@cAa@a@Qc@Qa@QGCYMiBu@a@Qa@Oc@Qa@QOGu@]EA[K[KGCa@Me@Ma@K_AWi@Om@SWE[GEAc@Ea@HC?c@ZUXUXEJOZMPILa@b@UNQJQBWDK@M?W@c@?c@@c@@C?_@AA?WCIAGA[OMGSQSOMQIIUQKIQIAAMESGIAUAA@O@SFE@MFMDa@Pa@PGBYNa@TEB_@JMDUBa@FA?_@?C?S?QCQC[GWKCASKKGMIQMAAKGKIIIAAIMSUIKS[S]GMGKMWEMUo@CCSy@YaAc@oBG]I]S{@EOG[EQ?EIi@AUAIASA[?M?O@y@?E@m@BUBUHm@?ALi@FQXq@BIVi@Vk@FQBMDSF_@Hu@Bm@?o@?k@Ci@AIGe@Kk@I[?AQa@S_@W]UWCCY_@A?W]EEY[CE_@a@AC[a@_@e@QWs@w@U[_@c@EGWWa@]CCUMECKGUGIC_@K_@K_@Ma@MICYIc@Ka@K}@UiAa@ECWKKIOKQM_@Y]WCAa@U[QEAa@MUIMEUGKEc@Mo@SICKIMGKGIIKKQQAA_@e@IMOOCCc@c@GGSOIIA?SIMEOECAM?YAI@U@C?m@N_@PGDKFKFULA@IFUNGDE@SJGBODM@K@A?G?MCE?GAWCMEUIa@MEAGCa@Qc@QUIECEAUKMEw@[MGSIMGUIKGUIA?KGUIKGUIKGUMMGOIECKKi@a@k@o@KKKKGIKOa@k@MQ]e@QSq@o@GESQKKGEKGMGSIIECAUIKGUIECGCSIMEUKCAIESKEAGG]YCC][CCQYEIUe@Yo@GOW}@So@CIKc@EWKc@GUGWCKUw@GO?AYs@M[?AKQO]]s@EMaAuBMWQ[IQCEKQ]g@GGWWEEYSMIAAQKKGUMMGIGIKKMIGII_@_@IICC[k@QYIOQ[e@y@ACeAiBMWQY[k@EGo@gACEKOMU_@k@KOKOEE]e@KM_@c@QU?A_@a@]c@KMOSOO}@gAQUEGEESUKMQUk@q@EGw@_AY]WY_@a@KMGGU[_@c@]_@UO?AKGOKQGCA]MYCWEc@?QBE?]JC@OHMDEBMFSJMJKHSNGFE@UJEBGBUBG@E@i@F_@AM?GAMAYCIAe@ESCOCSE_@MCAMESGAAKGOGSMSOcAo@KGUOa@[KKSOa@[KKMKEEKISQYUGEm@e@?Au@i@_@YMISQQMOMKIQOAAq@g@]QSMMGa@WUKKIUMm@]UMKGEC]Qa@WSKMI]SA?y@YKEUIGCC?UAMAUAMAUAMAUCMAU@c@@M?U@M?U@M@U?c@@c@@M@U?c@BM?U@c@@c@@c@@c@@I?A@U@E?_AXc@LKDUFMDUFMDUFKDUFc@LGBE?UBM@U@M@U@c@DM@U@M@U@M@UBM@U@c@BM@M@G?c@Ac@?M?o@Am@?c@?G?"
                     },
                     "start_location" : {
                        "lat" : 59.46728679999999,
                        "lng" : -135.3005034
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "51.0 mi",
                        "value" : 82011
                     },
                     "duration" : {
                        "text" : "16 hours 23 mins",
                        "value" : 58957
                     },
                     "end_location" : {
                        "lat" : 60.17458360000001,
                        "lng" : -134.705458
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eKlondike Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYT-2 N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Yukon\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "al}jJng~wXOSUAc@Ec@Cm@EYGc@Ka@I]IEAc@Ma@KSGq@]a@UQIOIc@Ua@Ua@Ua@UcAi@a@UECw@q@c@i@GGo@oA[m@u@yAWe@CGYm@[o@[m@Yo@ACc@{@_AgCWs@Ws@CGQq@Uw@Uw@Mg@GQUw@_AkDUw@ESMe@Uw@Sq@AGSy@Uy@Sy@Me@ESe@yBQ}@Q{@EQQc@Ys@wBuFgBuEq@gBWq@Ys@Ws@Yq@GOQa@Yq@Yo@Yq@Yo@Yq@mAqCYq@Yo@Yq@Yo@Yq@Yo@Yq@Yo@yDqIYo@Yo@[o@Yo@Yq@Yo@Yo@[o@Yo@Yo@{DsIiC{E[m@[k@]g@]g@]g@[g@OSOO_@a@]a@eDoDW[}DiE_@a@_@a@_@a@_@a@]a@_AcA_@a@}@cAEEy@_A]a@_@c@_@a@}AgBm@q@OU]e@_@c@]e@]e@]e@_@e@]e@]c@]e@IKWS_@[a@[_@]a@[_@[aAw@a@[aAy@_@[_@[a@[aAy@_@[a@[_@[aAy@a@[_@[a@[qDyCQU_@c@]e@]c@_@e@]c@_@c@]e@EGW[_@c@]e@_@c@]c@_@e@oCkDg@o@kCcDoAoA_AaA_@_@_@_@SUKI_@]aA}@_@]_@]aCyBIIUU_@_@aA_AEEYY_@_@UUII]c@EEs@y@CG]i@[k@MWMUSg@]aAWs@Wo@AAUs@]iAMe@M]IUWo@Wy@IU]cAW{@w@{BUq@Uu@Wu@o@kBEQQa@Yq@q@eBKWMWaBaDKS]k@y@sAS]e@u@]g@w@mAACkAaBkB_CiCeDKMq@aAuB{Cc@m@W_@]g@yAyBCEu@mAy@sA[i@EGu@gAEIkCgEIMkCqD_@e@EGW]]e@QUKO_@c@{@aAAAY_@EC_@_@KKOQCCQSMM]a@GGeBmBs@i@_@[g@a@_A[A?_@Mi@O}CKoAFG@c@FiBTkC\\qCVc@D_@BC@c@Fc@Fc@Hm@HWFc@Hc@HG@[Fc@Fc@Ha@Fc@Hc@Fa@HA?c@Hc@Je@J_@Hc@HG@[Fa@Hc@Jc@Hc@Ha@HA?a@JQBeAHSAc@Ao@AeASWIc@OKEy@_@_@[a@[GGWY]c@MMk@gAO[IQ[o@Yo@]s@q@{AYq@]y@Sk@aBoEACsAmDg@mA[w@k@cBACWo@Wu@AESq@Oo@CIS{@GUIe@Qy@?CYuAQqAQyAGa@S_BGg@QiCEcBCm@AWEeAA]Ag@CmAIaCCkAEgACcACw@AOCeAC_AGkACm@AWGcBMmBEm@EUM}@a@aCEUy@gEGWSy@Uy@Sy@Qs@AEk@qBUw@Uw@Qm@CIWu@Ws@[}@Sm@Wu@e@yAu@}BWw@GQi@sAYq@}@{AY_@[g@U[i@g@_@]GGqA{@KGa@Sa@SKG{@OQEQAeAKc@Ec@Ec@EG?_AGc@Cc@Cc@Cc@CIA}@OQEOCUCy@Ui@Sc@Ya@Y_@[g@m@GGY_@[g@CGOYe@_A[q@GMWi@Ug@Sg@i@sAMYoAqCOa@IOUi@Se@IQYq@[q@EMIOO_@OWIWOYKWQe@Ui@Q]MYKWISGOQa@A?KUSg@Sc@q@aBIQMc@e@{Aa@mBQ{@m@yEAQIcAEq@AQGeAQkCEo@Q_DAMWaEAMWqD_@yCSeAc@eBCM]gA]cAEIUg@CEg@w@SYQUKMKOSSSWi@k@G?KAaA{@c@Wa@Wa@WaAg@u@Ua@MOESGc@M]YIAKEc@Ka@MA?cAm@YSECOKQQQSMMQSKIAASUOWSi@GUO]Qc@[{@CEOa@Oc@COCQG]Mw@QoAGe@Gg@CYGm@CUGs@AOIcAAAIaACWGk@Ea@Ea@C_@Ga@AMGy@K_AAKGw@ACI_AIy@MkAGo@ASKcACWEk@Gi@CYKcAC[Gg@IaAK_AKgAEc@E]O_AAAYiBSsAESIk@Q}@Mu@SgAKs@CKO_AACSoAW{ASkAAGMw@ESO{@Ko@CU]gBKq@CKQgAMw@CQKm@EWIg@?AYeBEWCUGm@Ga@E_@KaAOiAIwAGg@M_A?CM_AIm@CSMaAC[UiBAOIq@MaA?AK_AE[Gg@Ks@OmAAGKy@AEUoBAOK}@Gg@E[Gg@Eu@Ge@?EEm@CUAOEu@Gk@AWE{@?IIaBCi@EcA?CEeACeAACCaAEcA?CEeACy@KqCMkCGsAC_AEcA?AMiDCi@GmBKoCEYIcAIcAAKIw@I}@?EQkBM_BEc@E_@KwAU{BI{@I_A?CIcAAMGw@Gm@CUGs@AOKcAGq@AQOeBOeB?AIaAAIGy@CWGk@C]MiAG]Ga@G[QcASs@ACYy@Uy@[aASk@Qk@GSOa@So@AEWu@M[i@{Ag@{AQi@GI[k@[m@CEqAyBYg@_@k@[i@e@w@S[]i@g@w@Q]Ua@]}@MWg@kBKe@Q}@Mk@COO_AO_AO_A_@yB?EO_AMaAO_AIm@EQO_AOu@AGO{@?CKg@ESQ}@Q}@Q_AQ}@Ms@CGQ}@EOMk@[wAQ{@c@oBMi@Og@[eAA?c@_Aa@u@c@{@c@e@EEY]GISSa@e@OOOQSSKKQSMMQUKKEEY]EGc@i@SWACUYEGEISYCEGMOSCGEIWe@Yk@Q_@a@{@[o@KSO[Ym@Q_@IOa@{@IOIMOWACOSW_@kAcBy@q@MKq@m@q@[SIOCKCw@_@c@Ke@K_@QMGUIa@MAAa@Oa@Oc@Oa@OA?a@OOEQIeBi@CAc@Kc@KYGGEc@Sa@SA?_@Mc@MOGQIc@QKEUIc@OOEQGc@Oc@OKCq@]i@Oc@Ma@Mc@Mc@Ma@Ma@MAAa@Oc@Qa@OEC]M{Ai@o@S_@[a@[a@U}@e@EEa@[_@[a@Ya@[[YCAa@[][Y_@GE_@[a@[][c@]_@[_@]EC[WiA}@}AeAa@QqAm@eBg@YGc@McAWe@KaB]kBCGAiAOa@GaAQE?c@Cg@C]Ec@Gc@Gc@IKAkAUw@a@}@s@?Ag@k@Wa@a@}@Oa@EOQc@a@iAMa@Mg@EQO_AMm@AOMaAMaAe@cEUmCEa@E_@g@}E]eEWqC_@{DI{@KcAKaAKcA{@cIc@iCQ}@SqAq@wBc@qAIUm@iAk@{AaBsBEEy@}@QUKMkBsBsA_Bs@y@aAkAcAkA]e@]e@GKS]}@eBSe@{@iBg@uACEo@}Bi@qBa@mBEUKg@W{Aa@aCG_@[eBg@sCO_A[mBq@}DEQU}Ak@iDa@sBAG]wBG[Ga@O_AIg@WwASeAMw@Q}@Km@k@qD_@sBk@gDE[Ic@Mw@QeAO_AIc@W{AMy@c@aCIe@WwAG_@Y}AOw@AEO_A]uBSgAY_BG]a@}BAG]wBO_AO_A?ASy@U{@o@eBWs@Ys@AAYk@Ym@Yi@AA_@a@_@a@_@a@EE{@m@a@Ya@Y_@[C?]Wa@WcAq@o@c@qB{@IAc@Gc@Gc@Ec@Gc@Gc@Ga@EA?iBKc@Cc@Cc@Cc@Ca@CA?gAEc@C]CE?gAKc@EWAKCc@Ga@Ey@MMCc@GqAUoAUs@Oc@IGA}@MEA]Gc@Gw@Mw@Q]Gc@I[GkB_@mB]C?eASc@IYEaAOs@KOCSEs@OyA[GAYGy@OMCc@GgAQCA]Gc@GUEMCe@Ka@Gc@IOCcAU}AWYGGAc@KaASi@Ka@ICAs@Ia@Ii@GKCUGg@Ek@Ki@Km@QQEk@My@QEAc@I_@IA?c@MSEOEIAy@SA?c@QOGe@S{@UYKg@S]Kc@OUIKCWGKEQMOKOKOK[QEESOKO]c@?A_@c@MOM[MYKWO_@GSUk@CGQ{@I[K]Uy@EQGm@AAGo@AQCe@KeBIeC?E@gA?GA_A?S@q@?g@@_@BgABo@@UBgAB{@?IDeABy@?MFmCBeABeA?ADaA@YCkA@aA?_@Bg@BeAJmC?KBy@FmCFmCBgABeADmCFoCBo@?U@gA@gA?W@kALkB?iA@k@?Y?gA?]?i@?gA@aA?C?gA?q@@}A?u@?wA?k@?oB?uB?sA?k@?[?eA?gA?U?q@?gA?a@?sD?I?}@?w@@M?gA?gA?G?_A?I@{@@gA@gA?gA@g@@qCDeDBqC?E@cB@e@@gA?a@?c@?gA?C@cA@i@?[@o@@W@Q?u@@U@o@@uABsBB_CBiD?U@q@@gA@c@?a@@gA@{@?KBmC?_A?GDcD?wK@g@?_@?mC@_DA}C?cG@aA?gA?{CA_CAq@?}A?gA?w@?uA?gA@o@AW?eA?gA?A?eAAgA?w@?MAgA?i@?]?gAAY?k@AgA?_@AaB?MC_A?EAgA?w@AO?eAAw@AwAAcA?ACgAAaA?EAgA?o@AUAgA?EAaAAq@CyAAaAEgA?EAgAAsA?oB?Q?}@?GAgACaCAKAgAAgAAeAAOu@cICYKe@o@uCi@gAQ_@IK[k@S]_@m@EEeAaA]So@_@SMa@WaBgAiBy@gBw@]Oi@OaCo@sBy@_Aq@A?a@UgBaAqC{AYMa@Qa@Qc@ScAc@eAe@a@Sc@Qa@Qc@Sa@QeAe@CA]SaDqBe@k@yBsCW[_@{@[o@}AkDIWm@mB{A}EY}@cAyCWs@Wu@Wu@So@AEWu@o@kBUw@Wu@Wu@Uu@Wu@Wu@Wu@_@kAsAeEUu@yAuEyAgFwAcFQm@CIm@oBcAeDUw@So@o@uBUw@cAeDWw@Uw@M_@GWWu@Uw@Wu@Uw@m@mBWw@GUg@qAs@cBWs@Ys@Wq@Yq@?A]g@{@qA_@]mC_Cy@_@gCgAe@Ma@KgAYc@MSGMCgAWa@Kc@Kc@Ka@Sc@QWKII_@[a@[o@i@OQ_@_@_@a@_@a@yA}Ae@c@_@_@_@_@cBcBWm@a@aAOa@Yq@Yq@O]a@iAWu@Mc@GQm@mBGOS_@[i@_@o@Wi@Uc@GE_@_@_@_@gA_@a@GeAOc@GUEMCc@Gc@Ic@I]GCAeAk@cAi@cAk@c@Sa@UCA}@o@eCgBa@YeBmA_@Wa@]_@[cBsA_@]A?]_@_A_Aa@a@_@_@_@_@_@_@_@_@_AaA_@a@]a@_CeC_AcA]]gBgAa@WCC]Gc@Gc@Ic@Ic@IeAQc@IgAQ]GEAa@IgAUuE}@a@Qc@QgBw@a@Sa@QeAe@a@QkBy@gCmAcAi@a@Sc@Sa@Sa@Sa@Sc@Sa@Sa@Sa@S?Ac@MeA_@eA_@c@MgBo@oDmAsCyAeAi@?Ac@EmC[y@K{B?_@Nc@Pa@Pc@NMFSP_@\\_@\\_@\\a@\\_@^_@\\a@\\_@\\MLSLsBtAu@Fc@Bi@DeBKc@Ac@Cc@Cc@CGA[CgAKc@Ec@E[CuCSc@CKA{@Ac@?c@Ac@?gAAgAAA?a@CkBKgAGc@Cc@CkBMc@CgAGA?a@Ac@Cc@Cc@AeAEc@Cc@Ac@CgAEc@AGA[Ec@Ic@Gc@IgBYe@Qa@OeA_@c@OeA_@a@OUIq@Ua@MWIUISISISGSGMEc@KICUEC?OCSEA?UEKAa@Ec@ECA_@Ca@CA?SAOAE?k@CUAS?aAM}AEM?U?YAm@LA@}@Jk@Ak@FYDUDMBc@FIBWHYJIF_@^{@Xk@Vc@PQJkAZIBc@Nc@LE@[Pa@RSJMFc@Pa@Pc@H[H{@Tu@PA?a@BG@[EOAw@Ac@?G?YGAAa@CGAi@Ky@GMAUCc@GCA_@C_@Eg@?C?c@IYECAQEm@KGAc@EYDI?I@QAG@OBi@HKBk@J]V_@Ja@Lc@Jg@N]Pa@TeAf@a@Ta@Ra@TYNGBa@RA?a@TWLIDa@P]NE@a@RSHq@ZWLIH_@Xc@VcAj@cAj@a@Tg@XmFtBc@Na@Pc@Na@Pc@NmA`@YPa@Va@XSLmCh@iAn@sAx@[Ha@JmAZ[Hc@LkDbAC@a@Tk@ZYJcA`@A?cAn@a@VEB}@V}@n@GB_A\\g@LUFk@?i@C{@Mi@MEAu@S{@[iE{Aa@Oc@OUKKCc@Oa@OiBo@YKuCeAgBi@c@M]KEAa@MgAWw@SwBe@_Ds@u@QeAUu@QyAYa@Ic@Kc@IGA[Ia@Ic@KmAYgCi@c@KiAW_@Gc@Ka@IIAYGc@K_@IC?c@Ka@Ic@IEA]Gc@Ka@Ic@IMCUE]GEAc@IAAcAYQGi@WIEaAs@CA][_A}@wAsBAA]i@]g@[i@]g@]i@]g@]g@S]GImBuCIM{@wAmBkCGK]g@]g@]i@]g@[g@Yc@CC]i@]g@]g@]g@]g@]g@uAsBAC{@qA]g@]g@yAwBwAyBc@o@W_@]g@]i@wAwBKMQY]g@]g@]g@]g@{@oA]g@]e@U[KMgC}D[g@]i@]i@]g@CGW_@]i@sDqFQW_DuE]e@_@g@]g@]g@y@mAA?yBwC]e@]e@]e@[a@a@k@]e@{@kA}@mAKOeB}CACUo@[{@Uk@Ys@Yw@m@eBUs@ACm@mBUu@Ww@Uw@CIi@eBUw@Uw@K]}AcFmAwDa@oAK]Uw@m@mBCGaA{Ce@{AiAyDo@oBUu@]eAe@aBWw@Ok@EKUw@Wu@Uw@Wu@Uw@EIQm@Uw@q@}Bi@_BUu@Ww@qAaEa@oAUu@o@mBQm@q@wBWu@Uw@Qg@EMm@oBUu@a@qAc@sAUw@m@mBCEQq@Uy@k@oBCISm@Wu@w@aCO_@Ws@Ws@Ws@Sg@oCsF?AYk@sBcEeBsDk@kAIQ[o@oAmCSc@GKYm@[m@[o@[m@u@{AGMS_@[m@Yo@[m@[m@[m@GMQa@[m@u@}AGKSa@Yo@[o@OYIS[m@[o@GMS_@Ym@[m@[o@Ym@[m@[m@s@yAy@_B[m@Ym@w@}AWq@Yq@IQe@yACEQs@Q{@EOKm@Q_AAEYkCGy@AOEs@Ew@AMUsEEeAGgAMkCEeACc@OgBIcAIgAWuBUsAc@qBGWEUEMMa@GSUo@m@{AGKYq@yAeCy@cA_@c@}@iA]c@_@e@]c@_@c@]e@_@c@]c@EGY]]c@]e@}AmB}@iA{@iA}@iA}@iA]g@Ye@CC[i@]i@_@m@Yg@[i@ACYi@_@q@a@y@w@{AcAaCYq@qBwEqAwDEIWs@o@iBc@iAM]Wu@Wu@Wu@Ma@ISo@gBWu@_@eAi@wAiBkFe@sA}BqGgDgJISMa@Wu@m@iBM]IWYu@Ws@Ws@q@iBEMQe@Wu@Wu@Ws@Wu@c@qAuAuDeAsC[}@gA_Dk@_BgByEYs@w@sBm@sAYq@[o@Yo@Yo@EIUe@Yo@u@_BYo@ACYk@Ym@[o@Yo@[m@KU_BiDYo@Yo@[o@ISO[u@_BYo@[o@Yo@MYg@eAYq@Yo@[o@Yo@Se@a@y@Yo@u@_Bu@_BUg@CG[o@iB_EYo@[o@k@oAIOYo@[o@Ym@[o@oAoCMUg@eA[m@[m@w@}AQ_@GK[m@q@oAGG]g@SYkAgA_@_@A?_@Y_@Yg@][Sa@Ua@Wa@Wa@Wa@WSMo@a@a@Wa@Wa@Wa@Wa@YSMo@[a@Sc@Qa@Sa@S_@QCAeA[a@Mc@Mc@Ma@M]KEAc@Ma@Kc@Mc@KeAYgAYa@Ka@KAAc@Ka@Kc@Kc@Kc@Ma@KEA]IeA[iBg@c@Ma@MA?a@Mc@Kc@MiBg@s@SQGa@Mc@Oc@Oa@Oc@MIEWMa@Sc@Sa@S_@Se@Qa@OKEWEeAQKCWAa@?e@Hc@Jc@Ha@JK@WHc@Lc@LeAXc@La@Lc@J{@VIBc@Na@Nc@Na@Lc@Nc@N}@Xi@Na@LA?c@FWBKAc@AUAq@Ic@GcAm@a@Ua@WYOGG_@[aAw@GEYUa@Ya@Y_@Ya@YUQKI_@[a@[_@[IGWU_@_@_@]_@_@][AC_@e@]e@MQOU[k@Q[IO[m@[m@Ym@?As@eBO]ISg@qAc@{@]kAi@sAWs@Qc@GOo@iBWs@AAo@gBWs@GOOg@i@qBUy@CIOq@S{@YkAMk@Q}@Q}@Ow@AEO_AQ_AQ}@O_AQ_Aa@}BQ}@O_AQ_AEWKc@S}@Q{@I]I]S}@Q{@Mg@EUS{@Q{@Qu@AGQ{@S{@S}@Ka@GYQ}@Kg@GSUw@Sy@CGSo@Mc@IQYq@Yq@CEWa@]i@U[IG_@[_@YAAa@Ua@UKGUKc@Qa@QEC[Sa@YCC[[c@e@Ya@]c@?A[o@Ym@Wu@y@_CMa@Ww@Sq@eAkD?AUu@Ww@AEUo@Wu@Wu@AGWg@Yo@[o@Yo@IOQ[]i@y@uAUa@c@s@[i@]i@CGWe@[m@Q]GO[o@Yo@[m@?AYq@Wq@Um@CEYq@Yq@GOQ_@Yq@Ue@EIs@aBGKm@qAWi@CCYo@[o@Sc@GI[i@]k@[i@GMUW_@a@_@a@AA]]_@a@_AaAWUGK]c@_@c@]e@_@c@]e@[_@CC[i@]i@]i@y@qAAAYi@[m@[k@]k@MUMWYm@AAYk@[k@[m@[m@IQQ[[m@Ym@[m@w@{A[m@[m@Ym@[m@w@{A[m@[m@Ym@[o@[m@[m@qAiC[m@[m@[m@EGIGYm@g@eAk@aAs@oAEG[i@_A{Au@kAk@aAMS[m@Ym@[k@Q]A?GOYq@Yq@KSM_@Uu@Wu@Ww@Uu@EKOm@Ok@EMUw@Uy@Uw@GUMc@Uy@Sw@Uy@K_@IYWu@Uw@Mc@IQ[m@[m@Ym@GMU]]i@[g@]i@]i@EKW[]g@s@cAGI]g@]g@Yc@AC[m@[k@GKSc@Yo@CEUm@Yq@Ws@EKQi@Uw@Ww@Uw@Ww@m@mBUw@Uw@Ww@Uw@So@u@mBWs@Ys@Ws@KWOQ_@e@]c@_@e@]c@CC]S[QEAc@Kc@Kc@Ia@Kc@Ic@Kc@Ka@ISEOEc@Mc@Ka@Mc@Kc@Ma@Kc@Kc@MOEQGc@Qa@Qc@Oa@Qc@Qa@Oc@Qa@Qa@Oc@Qa@Qc@Oa@QGC[Ma@QeAe@a@Qc@SYMGE_@[a@]_@[a@[_@[a@]aAw@_@a@_@_@_@a@_@a@_@_@_@a@_@a@_@_@]a@_@a@_@_@CC_@Oa@Om@WWGc@OeA[c@MeA[c@M]KCAc@KiBc@uEiAeAYc@Ka@Kc@K]Ig@]_@WgCeBa@Y[SCG[k@[m@[k@[k@[m@y@yAIOc@{AUw@Ww@k@oBWw@Uw@Qo@CGS{@Uy@S{@Uy@Sy@Mi@YmAUy@S{@S{@S{@Sy@S{@S{@U{@Sy@S{@S{@S{@Sy@Qs@CGS{@_BqGEUS{@g@wBOq@CGWu@Wu@M]IWWu@KWMYYq@Yo@O]g@_Ag@cA_BcCGK_@e@{@iAgAwAUQa@]WSGGa@Wa@Ya@WMISKa@SeAe@a@SUKMCa@Mc@MMCUEc@GQCQAgAEWCsABM?U@eAF}AHM@c@@gADU@M@c@Dc@Bc@Bc@DG?[Bc@Bc@Bc@Bc@Bc@@c@BkBJc@Bc@Ba@Bc@Bc@BgAFc@Bc@Bc@@c@BeAFgAFc@@c@Bc@Bc@Bw@BG?c@BgADc@Bc@@c@Bc@BK?W?gA?kB?c@?y@?uAEoCKc@Ac@AgCKG?c@EyAKkB_@MGaAc@a@Sa@[_@]GEWYs@w@i@u@]g@KQOW]k@qBmDm@cAgA_Bi@u@s@q@eB}A}BwBGEYW_A}@aA}@YYEE_@]aA}@_@]_@]y@u@GG_A}@a@]_@_@_@]UUIGa@_@_@]_@_@{@y@EC_@]_@]a@_@USII_@[g@a@{@o@CA]Sc@Ua@Qa@QAAa@Oa@OYKICa@Mc@OQGyBs@UGMEmCq@GC[Cc@GE?aAAc@AO?SBa@DcALC@c@Na@Lc@Lc@NYJGBeAb@a@NKDy@\\c@PYLi@XmDdBa@To@ZSLa@Ta@Ta@Tc@Va@Ta@Ta@TA@_@Py@`@KBa@Lc@LIBYDi@FeAB_@Ec@Cm@K_Bc@g@O]Ic@Ka@MMCUIc@M]KyAa@SGo@QWIa@Mu@Us@Sc@Ma@Mw@UOEa@MgA[{@U{Aa@eAQm@I{BAQ?Q?gA@c@?kBBeA@A?c@@E?m@?S?c@?I?YCQAs@Ia@EAAc@K[IGCa@MA?a@QGEYMa@SECi@[u@i@]YCAaBsAa@[_@[e@_@_BqA_@[SQMIa@YaAq@QMOIc@SCA]I[GGAc@EEA]?WAK@wBF{@Bc@@c@@c@@c@@c@@c@@c@@M?U@c@@c@@c@@e@@a@@c@@c@@c@@U@K@c@@c@Bc@Bi@Bm@Fw@VIBWLwAp@OJa@V_@X[Re@h@_@`@]`@CBYd@[j@sAzBADs@dBYp@Uj@Y~@Qj@CLSz@Sz@ERe@zB_@bBc@zBe@zBSz@c@zBS|@o@~CGVS|@y@tDc@rBADSz@e@xBSz@e@xBg@xBQz@Qv@ADg@vBSz@I\\I\\Sz@Q|@_@`BGVc@pBe@bCQ~@Mr@a@lCM`AADKz@[bCMbAM`A?BK~@SzBALGdAIdAIdAGdAShCGdAALGv@QjCGdAGdAQjCc@tGGfAIdAGdAIdAQjCIdAYpEIdAEd@MbBGdAg@tGGdAIdAIbAIdAIdAIdA?BI`AQhCIdAIdAIbAg@tGShCIdAkAxOAPIdAi@rGIdAKnAe@|DMbAIt@CJEZK`@Q|@i@dCOn@Sz@Sz@A@Ut@Uv@Wv@Uv@Uv@Uv@Ux@ABk@jBm@nBUv@Uv@Od@e@bBa@zAGRcArESfAADMz@YdBEXKp@CNKbAGf@O~AEb@E^MbAKbAEb@E^KbAWfCKbACXQlBIx@AJK`AKbA]fDSfBGn@Y|CKbAKbAALIt@KbAKbAKbA?DK|@MbAGj@CVMz@QrAKr@I`@G\\Mv@AFS|@CLOl@I^IXSr@W|@Ur@ABYp@Un@AB[n@Wl@ABOZKPYh@A@q@jAGFSTi@n@A?STKJIFSTA?wAhAKF_@Za@Za@X_@ZOJQLa@Xa@X_@Xa@Va@V]Re@\\oA|@q@h@CB_@ZcAt@MHQPs@n@g@n@a@j@AB[d@W^g@bAUf@Yr@Sn@Wt@Ux@IZQl@[~AO~@OfAOhAMdAK~@M`AQdBIt@_@xCEXGn@c@tCO~@ADSpAKf@Mp@CJQv@ADYlA_@jAc@xA_@jA[dAABWx@Ut@CFSn@K\\{@nCc@|Ae@vAM^Of@GN]hAOb@[`AeCvHYx@Wv@CDk@dBOf@EL}@jCqAvDWt@o@jBGTg@tAWt@Yx@qBfGADWt@Wt@o@jBGPMb@a@nAUv@a@xAKZI\\Ux@GVQp@Oj@[tAK`@i@bCa@nBETMf@I^CRMv@Kv@AFw@rDg@~Bs@bDWnAQ|@S|@ERKh@Sz@Or@AHQ|@On@CLQ|@ABQv@?@Sx@GXM^Mf@ERUx@Mb@GRUx@Uv@CFSl@Wt@Wt@Sl@[|@Wt@Wt@KZIZWt@Uv@M^IVk@pBm@lBo@lBSp@Yz@Wt@GPOb@k@lBm@pBWv@GVe@vAaA~CY|@Uv@Ux@Uv@Wv@Uv@Uv@_@jAu@bC[jA[pAKb@EXQdAMx@If@ERIx@MjAO|ACTIx@AHOpAEd@OjAs@lGKbAM`AKbAMbAKbAM`AKbAMbAAPKn@Gf@K`@GZGTCJMd@CFIXK\\CL[v@_@|@Wj@KXKVUh@CFQ`@[n@Yn@[p@Yl@u@bBoApCYp@u@`B}@nBgClFYn@iA~BWj@_@p@MTk@v@[b@m@l@UT_@\\C@}@p@WPa@Va@RcAXu@Nc@HKBkC^}@JeBT}@JUBeBL}CBkA@i@@_@A"
                     },
                     "start_location" : {
                        "lat" : 59.62961000000001,
                        "lng" : -135.1642401
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "19.9 mi",
                        "value" : 31998
                     },
                     "duration" : {
                        "text" : "6 hours 26 mins",
                        "value" : 23156
                     },
                     "end_location" : {
                        "lat" : 60.3129506,
                        "lng" : -134.2723895
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTagish Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYT-8 E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "czgnJbtduX?o@?yA?}@Aq@EkAIaAGa@CIOq@o@cC_AcDOa@W_Ac@yAaAgDQk@u@eCy@sCUy@aAgD?AcAcDUs@Y{@y@}Bg@wAM]wAwD_@aAEISe@EKGMMUOY]i@_@m@OS]g@ACW_@k@y@Q[CCi@aAw@}AKUIOO[g@gAk@oAu@}A[o@[o@GOm@mAgCkF[m@u@}A[o@qAkC[o@Ym@w@}AYo@Q]IOYq@[o@Yo@Yo@EKq@qAQ_@GO[o@EIeAyBEGISMWACMWMUCEMWIOGKMYEGIQQ[CEWe@AAU_@EE]e@CE[_@MOQS]a@]a@A?w@{@GIKMQSQUMQEGeBgD]s@[o@Yo@[o@Yo@Sa@s@_BGO[o@Yo@GMS_@Yo@i@gAiAuBu@wAYi@[i@OYMQy@sAA?[g@]g@]g@EIW]]g@{@oACCYa@]g@}@mA?A]e@]g@]e@]g@y@oA_@i@Wc@CE[m@[k@[k@?A[o@Wg@AGYq@Se@}@aCQg@Wu@CEQq@Wy@Uw@AEK_@ESU{@I]a@oBMg@G][_BQ}@G[Ia@Q}@Oy@AEQ}@Q_AQ}@Q}@?CQ{@Q}@Q_AQ}@Ig@GUS}@Mq@Uy@IYQi@Ww@Ma@EKSk@Ui@]s@KSOWIMQ[?AU[GIOSe@m@g@k@a@]EEYUKIUM{A}@IGa@UQKuAw@_@SAAa@SA?_@Ua@UWOk@[GC[Qg@][Oa@WAA_@Ua@WAA]WQMa@[c@c@]Ya@g@IKGGOSGGMOOUIKKOGKGGQY{@_BEGUe@c@_AWm@Qc@AAKUK]EKQi@EKQk@Ma@Qq@I_@Uy@?CQy@AIOs@Ke@EYO_AQ}@YcBG]My@QgAAKMs@My@AGKo@COMy@AEOaAAOMo@Ks@QgAAEMm@COIa@QeAEWGUKe@Q_AAEKm@CIQ{@?AOm@CMIa@I[Mi@EQQ{@I_@_@cBOk@AES{@S{@AEc@mBUeAQs@Oo@EOMa@GWQu@Qo@EMIYM[CKQe@ACKUM[EKKYGKUg@EGIQMWACS[Yk@MYS]KQO]Q_@GSCECIK[GOAEEMsAqGSkAQ}@Q_Aa@}BQ_AEWKe@o@oCMa@I]Uu@M[Wu@Wy@e@iAKWs@cBWk@AE[o@Yq@Yq@Wk@ACYq@[o@MYg@eAAGUe@AC_@}@s@_BSg@Wk@CCWs@KUM]g@wAGQWy@Uu@Wu@Uw@AEi@kBCGQs@c@eBEOOu@AES}@S{@CMWoAa@{BYaBO_AQ_AO_AQ}@AIOu@Ke@YuAEOMk@S{@Qw@ACSy@U{@Uy@Sy@ACSu@Uy@Uy@Uy@?AUu@Uw@EOQg@Mc@GQSm@CGm@}AEIQe@EM[o@GOQa@Wq@Wo@ACWo@ACWu@Ws@KYK]m@mBEKOk@Ww@Uy@Uw@Uw@Ww@Qq@WaAU{@EQMi@S{@WgAa@mBGYIc@GWG]AIO_AKi@UuAOaAGe@E[MaAMaAMcAQwAIm@KcA?AIcAKcAAGQiCQeCGeAGeACUEo@KcAEi@C[CWIk@WwBUsA[eBi@cCCE]oASk@e@uAu@kBAC[k@i@_Aw@wAOW]i@GKS_@S_@e@w@GKO]CCKUM[M]GWEOMm@GUIc@?CI_@YyB]cCIi@Ms@SkAAKQo@GYYkAk@qBGQSy@Uy@Uw@k@uByAuFYwAGSCSKk@Ki@UuAu@aGOkAMcAWuBOqAMcAIi@CWOaAC[UgB[eC?AMaACSIo@EYGi@E]SgBGe@E[SeBG_@Kq@AOO_AOaAACO{@O_AACQw@SaASw@S{@AIQq@s@yCGYUy@EQMg@c@cBGQSu@ACUw@Uy@Ok@YgAUy@GWKc@S{@S{@CIMs@Sy@?CQ}@a@sBSgASmAKm@?EO_AOaAIi@QuA?C[eCMcACUGm@KcAMcAEi@Q}AKcAAQUuBMcAKcAKcAMcAAKIw@KcAKcAKcAQgBKeAIcAKeAIcASuBASIeAM{Ak@gI?Ia@yFe@kHEk@AYIeAIeAGeAIeAIeAGeACQEs@IeAGeAIeAGeAIgAGy@[}EIeAGeAAGMqBAQEgAAMCy@Cy@?M?gAAk@?[?gA@Y@wB?m@?Y@gA@gA?iA@[?k@@gA?gA@gA@eA@sC@uA@cC@gA?YAqBEwBGcBMwBAUGeAGeAEo@AWGeAOmCAUEo@Gw@AMIeAEa@Ea@KcAMcAE[Ge@O_AG_@I_@O_AQ_AO_AEMKq@O}@Q_AO_Aw@kEy@oEq@oDKm@O_AOw@eAeGCIMu@Q_AO}@EQKm@s@_E?EOy@g@iCo@qDCSKk@Ko@CQOaACSWoBAKIw@McACSa@wDW}BAGKcAKeAIu@AKKy@AIOaACOOk@]uAK]Uw@AAm@iBIWM]q@kBISM_@Wu@Us@AC_AqCEOYu@Wu@GQOc@Wu@IUM_@m@mBUq@ACUw@_A{CEKk@qBUw@Qk@iAsDWw@Uw@m@oBm@oBEOe@_BWy@Uw@Uw@Uw@IWM_@So@AGUy@Oc@ESU{@S{@ACOy@Ks@CMMaA?II{@SwBAQIeAIeAIcAASGq@IeACa@Ec@IcAEi@OmACOIk@EUQ}@AEe@qBS{@CIOq@U{@Ke@GUS{@Sy@S{@K_@I[S{@c@gBOs@}@qDq@uCw@}Cq@aCc@wA_FwMYq@u@mBo@}AYq@Wm@ACiAyCkAyCAAWs@Um@CEs@cBIWcAgCUm@Yq@[u@_AcCIUM[IWQi@WgAWkAQuAEc@Gw@AMIeA?Gg@kIIqAW}ESwCKsAGg@Gg@E[Gm@ESCQGa@CKUkAOo@g@yBCOOk@UgAqAmFy@gDa@eBo@qCOu@Q_ASsAIu@I_AEy@EgAG_CCeBCgACeBAi@AgACgACeBAk@AgACgAAgAAYCuBCqCAgACwAGgEAiAAgAAWEwB?e@Ca@Cw@AOCe@C_@Ea@OmAM}@Ou@S}@Q}@Mk@EQeAcFEQg@wBy@uDS}@S{@eAsE[{AS{@S{@e@yBoAsFQ{@w@kDi@eCg@yBQ{@S}@CKw@iDsAcGoAuFm@oCg@wBS}@Oo@qA_Gy@oD?Ey@uDACuAkG_BiH}@}Do@yCm@mC{B{J[uAQ{@]yA]{A{@sDS{@WgAgBaI]{AS}@gA}Em@kCS}@w@mDWcAOq@i@cCGSKg@S{@q@wCeAsES_Ay@qDQq@YkAc@qBACc@wBAC]eCMeBK}A?GEaB?uADiB@a@Be@FuATwCDi@JcAFs@ZyDj@oGZuD?ENaCFmA?Q@u@?S?oAEsBAg@C_@OuDQyDE{@QgDMoCIqBGgAASQ{DWwEKgCEoAC_@A{@Ay@?aA?a@@g@@e@BiAPiEP_EHiC@SBq@TkF\\eHPiFHoC?UBiB?}CAYGiECuA]aQw@uZAcBAiA?gAEiJAoAAaACwEAqCCoC?iAAgA?ECiCAgAEyEAgAAcBAm@AgAAgACmFD{BJkEZsCLeAd@wBP{@@Aj@oBTw@b@wAT}AXcBb@oF?CFkEEoAEgAGwAM{BGgAs@aMMqBYsEIeAc@{GUqEUsECi@?]CyE?{@?KDgADgAJmCB]p@gKRkC@MFw@n@{IRiCHgAHeAf@uG@UV}DFeA@ODqG?GA_ACgACgACgA]qICQc@uGQaAa@aCCOeAcDSa@eAoBQQ]a@_CgCUWgAqA_@c@e@m@Sc@c@{@Og@a@kAe@mB[qBCSg@_GY{C}@kKeAyLmB_VKeAWcDQqBKcAS_CSeCQ{CAiCHyCDeAD{@ZgC\\uBDQZeBFWRiANaBB[JqAD{@DoA?_A?cCOyCI}AIm@KcAKcAKcAs@oHgBePE_@qAkMg@oEm@cEo@_C]sAkAgCS_@[i@m@_AwAsAq@a@y@W{@Q]GiBOuCIgAEiDKm@AcIKc@FaBV_D~@_Bb@}HrBc@JgQrEsP~EeCt@gPbEoCt@QDcD|@sDz@sCd@eD\\gAJkK|@wFf@kIv@"
                     },
                     "start_location" : {
                        "lat" : 60.17458360000001,
                        "lng" : -134.705458
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "64.8 mi",
                  "value" : 104299
               },
               "duration" : {
                  "text" : "21 hours 3 mins",
                  "value" : 75798
               },
               "end_address" : "Whitehorse, YT, Canada",
               "end_location" : {
                  "lat" : 60.71971259999999,
                  "lng" : -135.0522818
               },
               "start_address" : "Tagish, YT, Canada",
               "start_location" : {
                  "lat" : 60.3129506,
                  "lng" : -134.2723895
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "13.3 mi",
                        "value" : 21367
                     },
                     "duration" : {
                        "text" : "4 hours 24 mins",
                        "value" : 15816
                     },
                     "end_location" : {
                        "lat" : 60.3397533,
                        "lng" : -133.9850134
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eTagish Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYT-8 E\u003c/b\u003e toward \u003cb\u003eSidney St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}zboJlaprX[BUBq@Bm@Da@?i@?U?YEWIs@a@UYOSS[O]M[Qg@Ia@I_@Ik@MkACc@GeAIgAUwDGeAGgAIeAGeAQmCGeAGeAGgAIeAGeAQmCGeAGgAIcA[yDcBiRo@{Hi@uG}@aK_@uECg@McBSsCW}Di@yEM_A]eCAIsA}GEOQ}@w@yDsAuGaB}IQ}@iByJm@cDGYw@{DQ}@}@yEIa@Q}@uCyNa@wBa@}BQ_AQ}@CKs@mDe@{BGSk@_BWg@c@}@k@{@}@}@_Aq@KEgCeAaBm@qAg@]MCAyAk@MGeAi@KEqAiACE{@qAEGo@wAUy@Uw@K[]{AO_AQcAIaAMsACw@EgAAg@CgBCqAAgC?iAAyEAiDAuEEoDCsD?IAwCAqA@wA?{@DgBHiAJwAzAcNNiBDuA?I?iA?C?cACoCKoCEgAMmCEgAEgASuEEgAGgAA_@KkC?_CFsCNsB@Gx@eG@A`@_CdA}FN_AX}AXaBP}@b@_CN_Ab@}BBQJm@fA}F@EF}@Fo@@UFgAD}@?GBqC@gA@gA@iA@w@CwAEqCCkC?CAgAAiA?}@?IAgA?gA?AVoDD_@JcAJ{@?GJeAHeAHu@BKR{@f@uBp@kBHUPYZk@Zk@FIT]\\g@X_@d@a@`@[NMNM`@]^]ZWf@[`@W`@Y^W`@W`@Y`@W`@YbAo@`@YZSf@]^WbAs@bAq@`@Y`@WJIRU^_@^a@DGVa@x@uAHON_@Xq@Xo@l@oBPk@BMNaAN_AN_APaAN_A^aCBOJq@N_ANaAN_ANaAN_ANaAN_ANaAN_A^cCN_A~@cGNaAN_An@cEN_AlA}HLaAj@gEv@iGZeCNaAPuAHo@l@_E@CR{@d@yBBIf@iBTy@Po@h@cCf@yBf@wBR}@Je@XmAVy@Vw@Vw@bAeDdAgDh@eBBIh@uBR}@L_ALcA?AJaAJiAH_AFeAHeA?CFcAFeA`@yGDi@P}ALcA@GV_CLaAFi@T{AHm@TsAN_ANaA^aCN_ANaAh@iDf@yCJq@BMN_A`@_Cp@aEJs@BKNaA^aCN_ANaAN_AP_AHk@DUl@cENaALaAN_A@CHaAlAcMJcBDeAFgABe@PwF?E@aADqCBgC?G?iACkGSwGA[EgAEgAE_A?GSkCGeAIeAEi@C[Ec@OeBKcAK}@MgAc@oCiA_H]}AQ{@oAsFQ}@S{@g@_CUs@EOQc@Qg@EMYq@O[cAkBy@yAEKy@wA[k@w@yAuAcC[m@[k@y@wA[m@[k@y@wAw@yA]k@sAcC[m@]k@[k@i@cAMS]m@i@_AoBwBWWGGYSGCa@QMEUMUKKGq@YSGUIKCc@Oo@SUGgA[oDeAc@Ma@MgAYw@WyC}@WIKC}CeAQEiBk@eA[_@MC?kCw@QEQG}GwB_@KyDgAaDaAsDgAc@KiBi@yEuA}@e@c@UKGUKOGQMYU}@mAc@o@IM{@aBK[qAsEk@kCS}@k@cCqBaJMm@COS{@S{@WiAmAcFS{@Mi@YmAg@yBy@uDgB}Hc@iBg@yBOs@i@aCS}@Qy@o@mC_AeEi@{CAEUaCGeACSE}AA]?gAAm@DcB@a@@e@@IF{@B_@RgBLcA^_CN}@PaAdA_G^uBVcAf@wBHWv@kBHSZq@nAqCt@_BXo@Xq@Zo@@AVm@Zq@Xo@Ti@j@cB\\iATy@FSt@{CNk@DO\\yA^qBHm@PkAVaDNqCHgBDgAD_ARsCL{AV}BJu@Hk@DSXcBF[Py@T}@T{@HYJ_@`AkDTw@DQLi@`A{CzB{Hh@mBJ[x@iCHWp@gBNYTi@z@_B\\m@x@uALUhB_DVc@v@uALSfCmEVc@x@uA@E~@{An@kAnA{B`@{@`@iAn@uBXsANiAN_AXcBD_@LaAXqB`@uCb@{CHi@l@oEJy@LaANaAN_AFYHk@b@_Cd@qBFWLa@~@sCFMXq@Zo@Xq@HQn@_Bd@{A@CZsAZgBXcC?ADgAJmCDgAHaBJ}DDgA?AHmCDcBBiA@uAA_BEmA?AIwAGq@E_@OoAEUMw@eAgGs@oEwAkHAEUq@GS_@aAq@oAq@y@CEg@c@g@_@_Ak@u@_@]SCA{BmAo@[a@UaAg@c@WGE_Am@UOa@_@e@g@CCQUGK]k@y@uACEUm@Ws@Ws@q@iBYs@s@oBaBiEq@gBYs@Ws@Yu@Wo@oA_DgBuEa@eAsAoDGOcBmEYs@{@{BaAgCWs@mBaFO_@Ys@Ws@Ys@Ys@iA{CYs@O_@ISiA{CYq@aAiCsBiF_BeEi@sA_@iAWu@Wu@Us@AC]sA[cBO_AQ}@Q_AQ_AQ}@O_AQ_AQ}@CQQi@Uw@Qk@w@qBq@u@[YSOQMOI]OCAc@Kc@?c@AK?W?c@@I@Y?c@@c@@c@@[@"
                     },
                     "start_location" : {
                        "lat" : 60.3129506,
                        "lng" : -134.2723895
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "17.4 mi",
                        "value" : 27980
                     },
                     "duration" : {
                        "text" : "5 hours 32 mins",
                        "value" : 19943
                     },
                     "end_location" : {
                        "lat" : 60.51436509999999,
                        "lng" : -134.3269189
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eYukon 1 W\u003c/b\u003e (signs for \u003cb\u003eWhitehorse\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mbhoJh}wpXAdAAn@CpC?ZAvBElCCtB?xC?rF@`A?fA@dB@zG@xB?hA@j@?bB?\\CrBAfAAdAIrCC`A?DGdAW`FSrCQtB]zDCRKbAUhCGr@MvAIbAKdAGj@QdCIvAQzCC`@Cb@OlCGdAOnCEdAAHE|@MvBKzAGdAGfAIlAk@vIIdAIdAGdAIdA[pEWvDCZa@~Fg@hHe@~GSpCc@pGIfAIdAQjCIjAG~@SjCQjCG`AADQjCIdAQjCIdAm@~IEf@KbBIdAQjCGv@ALGfAIdAIdA?FI|@GdAIdAEh@CZSjCGdAEf@_@pFMhBMfBYbEm@pH_@`ECTo@zFg@dEE\\Gd@O`AM`AAHKx@M`Ae@jDS|A[dCGf@S|AM`AWhBEZi@fEQjAKv@]bCO`A_@`CO`ACRKj@w@rEWtAWrAKj@Mp@cAvEa@lBs@|CKb@{@fD{@|CIVk@pBSr@sAdEsA|DOb@GP_BdE_@z@kAvC[p@Yn@wA~CS`@_CfFiCrFCBkB~D[n@]r@gA~B_BbDo@jAkAtBIN[j@SZIL[j@wA`Cy@tA[h@g@x@s@vASb@y@`BYj@u@~AYn@S`@GLYn@[n@i@lAIPEFUh@Yn@[n@Yn@EHUd@[t@Wj@[n@Yn@[n@Wj@mBbE[n@Yn@qAnCoApCA@kA`CeAbCMXYp@[r@uCpGiCjGYp@Sd@m@zAKTgBhEYp@gFdMYr@Yp@mAvCYp@Yp@Yr@kAtCYr@s@bBmAvCYp@Yr@mAtCYr@eBhEYp@Yp@mAvCYr@gFdMmAvCoErKsD`JYp@oEtKeBfEYr@s@dBYp@Yr@Sf@Uf@IRCHUf@mAvCs@bBoErK_CzFYp@c@bAi@rAYp@mAvCYr@_CzFM\\KTmBpEe@~@e@`A]j@]h@i@~@OR]d@_@b@CD{@z@s@p@MJ_@Za@\\aAx@_@\\UPKH_@Za@\\_@Z_At@kCzBcBxA_@Z_Av@c@`@aBvA_@\\a@ZURkAjA_@^]b@CB_@b@Y`@ORi@t@_@j@]h@MPk@bAw@rAABu@~Au@~AMVg@hAs@`BMVg@jAYn@GPgA`CYp@Yp@}D~IuEtJYl@Yn@]l@mBxD[l@{F|KYl@w@zA[l@w@|A[l@ILiC~D[d@A@_@b@yAhBcCfC_@^QRkCrC_AbAyB~B{EtGuB`DmFfIuCjE]h@[f@]h@eMlRU^]f@{@pA{@pA]h@]f@wAzB]h@]f@wAzBk@x@OVyAxB]h@uBbD]f@{@pA]h@[f@{@pA]h@]f@]h@y@pA]f@{@pAMROTsClEwA|B{@pAy@rAy@lA]p@[j@U^ELYr@o@~ACDK\\IXKV_@rAGXMf@?@Mh@CPCRa@fBI`@ObA}@rHk@hGKdAWhCIbAIt@G|@ETKdAc@lEQdBW`BO`A]`C?@e@xBADSt@[fAi@|AWt@Wt@IReBbD[l@AB[b@{@pA[f@wCfEi@x@QT]f@{@nAwB~C]f@yAtBwCfEqDjF_@j@}A|BY`@]f@{@nA]f@k@v@oC|DqDnF_B`CeCpDc@l@]f@]f@]f@]f@]f@OTMRw@xAmAvBGLw@zA[l@eKbS[l@cBdDcAlBw@zA[l@}EnJ{GpMYb@mIfP[l@gDrG{F|KiCdFsAhCoBvD[l@w@zAkCdFoBvDqAhCw@zA[l@[l@sAhCw@zA[l@[l@gDrG[l@wK~Si@dAuGlM[l@[l@w@zAyF~K[l@w@zAqAjC[l@_FpJyF|K[n@iCdF[l@qOlZ[l@qH|NCDkBpD[l@w@zAw@zAaE`Iw@zA[l@[l@w@|A[l@[l@kBrDsAjCgDtGYl@[l@oBvD[n@sAhCu@zAmCjFUb@{AvCYf@ADiC~EABYh@ABaFlJ[l@Wf@CD[l@Wf@[l@CBw@zAWh@CB[l@Wf@_@r@[l@[j@Wh@[l@wAlCoAbC_@p@w@zAsAhC[l@[l@EHaDfG_FlJw@zA[l@w@xAS^GLsAhCw@zA[l@[j@w@zAkAxBc@|@[l@[l@m@fAKP[h@]f@]h@]h@y@rA]j@_EpFUT_@^a@`@oAnAq@f@a@X_@Za@XC@]Rc@RyAv@kDnAOBc@JiBb@cDt@uAVmCd@c@HeAPkAR_@Jo@LaBr@[Pa@RaAh@cA~@cA`A]^mB~BeAlBm@hAIPu@~Ay@`BUn@Yr@Yp@Yr@Wr@Yr@Yp@Yr@GRcAfCqDhJi@pAIPWr@Yr@s@dBYr@q@dBYp@Yr@Yr@q@dBYr@Yp@Yr@Yr@Wp@Yr@s@dBYr@Wr@Yp@Yr@s@dBWr@gBjEWr@yCrHYr@s@dBWr@Yp@_C~FyCrHYr@s@dBeBlEYr@_K~VWr@mIzSYp@Yr@q@dB_G`OYr@eBhE"
                     },
                     "start_location" : {
                        "lat" : 60.3397533,
                        "lng" : -133.9850134
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 993
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 729
                     },
                     "end_location" : {
                        "lat" : 60.51619400000001,
                        "lng" : -134.331765
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eNoland Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yejpJfvzrXN`AL`ANbA\\bCL`A\\dCJt@BJN`AL`AJl@F|ALdDIn@YxC{AvB]f@w@lAC@aAr@a@XUNwBBG?YSSMc@kAWs@YiCMcAEe@FyADIh@eBLr@d@Rj@YFYBMKq@A?c@G_@CYv@"
                     },
                     "start_location" : {
                        "lat" : 60.51436509999999,
                        "lng" : -134.3269189
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 476
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 352
                     },
                     "end_location" : {
                        "lat" : 60.5135537,
                        "lng" : -134.3331111
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eNoland Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eqjpJnt{rXi@dBEHGxADd@LbAXhCVr@b@jARLXRF?vBCTO`@Y`As@BAv@mA\\g@zAwB"
                     },
                     "start_location" : {
                        "lat" : 60.51619400000001,
                        "lng" : -134.331765
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 316
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 238
                     },
                     "end_location" : {
                        "lat" : 60.5159828,
                        "lng" : -134.3301628
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "u`jpJ||{rXs@kAuBkD[i@AC]]_@a@_@_@_AcA_AaA_AaA"
                     },
                     "start_location" : {
                        "lat" : 60.5135537,
                        "lng" : -134.3331111
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "20.6 mi",
                        "value" : 33139
                     },
                     "duration" : {
                        "text" : "6 hours 44 mins",
                        "value" : 24213
                     },
                     "end_location" : {
                        "lat" : 60.5993061,
                        "lng" : -134.8699379
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eYukon 1 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ojpJnj{rXyCtHoC`H{AxDYr@s@dB_C~FYr@Wr@Yp@Yr@Yr@Yp@q@fBYp@Yr@Yr@Wp@Yr@Yp@Yr@eBlEYp@kAxCmAxCaAdCc@dAYp@[r@Yp@O^IPYp@iBdEYp@Yp@Yp@s@bB[p@ELU\\uA`Cy@tA]h@[h@A@[f@]h@]h@U^[f@GLYp@EHq@pACDUl@_@~@Sd@EJQh@M^eAfDaA~DCJUfA_@rBQ~@EVYjBM`AKj@CTM`AMbACNKr@W|BAFO`AuAxKS`BG\\Gh@EXM`A[dCk@hEM`AMbAE^c@hDO`AMbAi@fEMbAO`AEb@G^M`A[dCMbAObAEZGd@MbAeAnICRIn@KbAMbAa@vDCTUhCI`ASpCIdAC\\OlBIdAk@tGIdA_@pEUjCKbASjCUjCIdAGr@CPMbAMbAYdCKbAIp@q@xEAHOr@e@|BADUn@Wv@Wt@ADWh@u@`BYn@INSX]d@_@d@UZGFa@\\m@l@QNa@Za@Xa@ZYRg@ZgAp@[TA@SLMJa@\\GFeAdAiAvAmAtBSd@S^INa@jA[dAABOd@Ol@cAvE]jBStAIj@c@pCSfAO|@EVQ|@Md@U~@Md@m@jBa@dAO`@INIPa@x@c@v@_AvAILQXY`@SZOPY`@SXg@v@CB]d@yAtBA@[f@KLqAlB_ApAqBvC]f@_@d@MROR]f@]h@GJUZ]f@{@lA]f@]f@uDlF{@nA{@nA{AtB]f@GLUZ]f@[f@]h@{@pA]f@{@pA]f@C@oAdCKNO`@Wr@Yr@IRM`@Ux@Ux@Sx@GPq@hDI`@E\\i@nEa@jEEn@CTGdAQlCIdAGfAEf@C\\IfA[rEGdAo@~IGfAGp@ARKdA]bEo@hEAFQ|@S~@I`@_@rA_@tAMXWr@a@`AS^[l@[l@Wh@aCpC]b@STKL{CtD}@hAw@v@_B`BmAnB}@rBABUn@Yt@KXKZSx@Sp@UdAS|@Kd@e@zCCNc@zDALEv@IfAEz@AHEfAGfA?JCdCAf@?`@CfAAhACzAA|BCrCAfACpC?hAAJClECpCAhACpCCpCAhACrBCbCQlRChAGbHGbHCpCAhACnBErDAhAEbHAHCfCAfAAhACpCGxEEzEK`OCjCCpCAfACpCAhAEzEAfAAhAAfAAhAAfACpCAhAAfAAhAAhAAfAAhAGbHAfAAhACzEGbGAhG?X@hA?z@?JBvB@XHdCHpABZBj@HdADh@BZHx@@JJbATtBFf@L|@@DT~AH`@^jBd@pCp@pC^~ATz@FV`@|ABHPl@Pf@DNj@fB@FRn@BFTv@j@fB@FVv@DPf@~ATx@Rn@Vv@Vt@Vt@n@jBVt@Vv@Nd@FNTv@Vv@Vt@Vv@dAdDJ\\H\\Rz@P|@@?N|@P~@P~@?@L`ALbAJbABLFt@HdAHdABXHtBDfADhABbA?B?fA@hA?hA?NClCEz@EfACz@AJGdAQlCGfAGdAIfAGfAInAWjEIdAGdAQlCKdBYrDQ`COnAKbAWvBUlAQ~@a@~BOx@Yz@Wv@o@pBq@`BWn@A@[l@[l@CDwAlB]d@_@d@OTc@l@uA~A_ClE[j@KRi@lAMXKXWt@u@vBOl@Uz@g@vBUz@g@tBI\\I^Sz@g@xBSz@S|@Sz@g@xBoArFSz@Sz@U|@g@xB{@tDSz@S|@Sz@Sz@S|@Sz@S|@g@xBSz@g@xBoApFS|@Sz@oArFSz@g@xBMl@YjAg@xBQ|@o@pCcA`FMr@CHcA`GQ~@ERKj@c@|BQ~@Q~@Q~@O|@Q~@Q~@Q~@Q|@c@~BQ~@Q~@Q|@Q~@Q~@O~@Q~@Q|@Q~@Mp@CLQ~@Q~@Q~@a@xB?DQ|@Q~@O~@Q~@Q~@Mr@CJQ~@Q~@Q~@O|@Q~@Q~@Q~@Q~@Q|@ERmAnHQ~@CRIn@c@~DAJCTEp@QhC?BEfAEv@ANCfACbA?BEpC?d@Ab@?J?rB?PAhE?xA?fA?@AhAC~BAPCfACxACv@EfAEfAEfA?FOdCGfAIlASdCKjAQfBUvBGj@OnAe@bDk@hDYfBAFe@|CWzACJEXSjAEZe@rCg@hDAFObAObAOjAKv@It@QpBMdBGnAEfAEx@ExAClB?jB?F?~@@hA?H@|@?t@@|A@fA?`@@f@@fA@vCB`C?rA@hA@fA?@BhB?jD?LAbBI~D?JCz@A\\Ch@GzAEr@AVEn@GdA?DG`AGz@AHKdAEn@CTMbAKbA?@UjBWjBKp@Kz@AFO`AIn@U`B[vBAHSrAGd@iAlIMbAM`AObAIr@QpAO`AKv@AH]dCMbAm@pEIx@a@xDSvCMxCATEtBAnAAt@?P?rB@\\@n@?XBfABz@H`BFx@Bn@Dd@TdC?FVnCHr@LpAH~@?Bb@nEJdA~AfPVhCb@nEVhCVhCJbAHdAb@nEJbAJdAb@lEJdAJbAVhCJ|@XfDHn@`@nEVhCJdAJbAJdAThCJdAJbAJdAJbAJdAJdAHbAJdABPFp@fA|KNxA`AjKBLDv@LnCFfADfA@JBz@DfAHzB?|A?hA?fA?^EzDAfAA\\Aj@EfACfAIpCCfAEfAIpCCfAS`HChAEfAAf@EhBCfACfAKxEIpCChACfACfAChACfACfAChAMxEGpCShJChAEfAAj@AZChAE|@CpAEfAOxEInCAZCl@CfAEfAKnCChAEfAEfAEfAEfAA\\Ah@KpCCfAEfAIpCMhDQnFGjBS|FAl@Cn@KlDOlEShFEpAKdCEnBANEfAEdAAjACtAGtCAv@A|AAr@?|@?H?hAAnB?`@@hA?hA@fA?~@?H@fA?hA?hA@`C@vA?hA@hA?hB?f@@fA?d@?b@ArBCnCC~AAl@G|ACdAANEfAAJEz@Cb@MvBGx@CZEh@IdAIfAGdASjCEl@CXIdAQjCIfAIdAIdAADG~@IfAGdAGv@UzCIdACREp@IdASpBCVQtAWtBQjAMx@WxAIb@SbAQv@G\\K^Sz@Mh@o@hCOj@CNg@nB_AxDGVa@|AeA|DeAhEADi@tB_ApDSz@_ApDGRKf@_ApDgBhH_ApDGZ_@zAUz@wAxFc@jBMh@m@rCa@zBAHKv@O`ACRWrBCNIr@Ip@KlAAFGt@MtAEj@IzAADCt@M~BA`@g@pMInBW~GEfAW~GQxESvEc@pLC~@AF]fJEfAKnCKpCEfAALCx@EfAEfAQvEEhAMnCAd@a@hKQzEKlCc@nL[fISxFMnCEfA]hJEdAEhAQvEEhAEfA]bJKrCi@nNEpAEfAEfASxECt@AP]fJAn@CXKnCEfACr@ARInCEfAC^IpBEfA?NUdEATYxEMrBAF]hEKdAIdAAJ_@bEKdAKbA}AxPw@jIKdAWhCa@nEKdAOxAi@~FWhCa@nEGl@g@fFUdCKhAKbAWjCm@rGKdAm@tGqAbNAHk@jGWhCo@tGUbCeAdLI|@AFUhCWhCU`CMlAIdAKbAc@nEIz@AHc@|ES|BEf@E\\IdACROrBQfCSvEGfAIbBMnDOjFGhBAt@A~@CvAAbAAzAA|@CfGG~NE`IAtBAhAGtPAdDCbHCrCApCEzJEnHA`A?FAjAAfA?B?`AEnFAt@?@AdA?NAdCC`C?LCfAAhAALAx@?BAh@CbBA@?VCl@Ar@AT?@EfACd@A^?@EdAAXCl@A@Ev@?L?@KjBKfBCTEp@IdAC`@Eb@IfAIdASvCG|@SjCIdAQlC[rEIdAIdA?@MbBCh@QlCCTQ~CCX?BGfA?@GdACZGdBKtBGfB?FEx@EzAE~AGbBCnA?DAPAr@?JEfC"
                     },
                     "start_location" : {
                        "lat" : 60.5159828,
                        "lng" : -134.3301628
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.6 mi",
                        "value" : 10668
                     },
                     "duration" : {
                        "text" : "2 hours 9 mins",
                        "value" : 7758
                     },
                     "end_location" : {
                        "lat" : 60.6497296,
                        "lng" : -135.0220088
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eYukon 1 W\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "uxzpJbxdvX@D@D?D?N?b@ArBA^A~BGfDGdKAlBIdIKtFKhJMlJChAAfAMpKChAC~@?FAhACpB?^Av@?^E|CAt@EnBAt@AXAH?B?@AB?BEjCAl@?^At@AhAAbAClA?`@GnDGxCAt@A\\Cl@ItCExAKhCE|@GtAIvACl@_@`FU~Fk@vHe@xG_AhMIfAIdAQlCIdAIdAIdAIfAIdAIdAGfAAHGz@IdASjCIfAIdAIdAIdASlCIdASjCIfAIdAIdAAREp@]rEIfAIdAQlCIdASlCGdAIdAIdAIfACXYxDGdA]pEQzBCTu@~J_@dFGn@IdAG|@UtCo@zIEr@IdAIdA]rEIdASlCIhAI`AIdASjCCTOvBIdAIfASjCIdA]xEG~@g@xGcAlNIfASjCGdAA@GdASjCIdASfCSpCWnDEb@OfBKbA?@WjCUdBWzAIn@EPMl@EPQz@GV[lA]xAY~@Sn@g@xACHWt@KVu@hBe@fAk@nA_ArBaAxBg@fAgBxDqFxLa@z@e@dAqFpLk@lAYp@eCpF[p@Yn@EJeBtD{FfMyBxEqArC[n@Yn@mAhCeCvFi@jAcAbC]z@GL_B~DKVe@lAO^g@|AIRu@|BaApCOb@aAtCS^{DlLyBrG{@jC_DrJgBtFM^kBzF_BlEMz@o@jBmAnDkAhDo@bBw@nBIPoAtCEJSb@w@|Aw@xACDWd@]j@EJo@`ACF]f@Yb@CB_@d@[b@A@_@b@_@d@s@v@IHo@n@OPk@h@uAvAKJa@^uAtA_A~@wCvCIH_@^aA~@_C`CwAvAiAdA}D~DmDlDeBdBiFjFsCrCm@n@uGhGkBhB_B`ByAbB{BzCo@~@c@p@Yd@_@n@GHU^a@p@o@lAg@`Ai@hAEJGNiB~Di@nAYr@c@hA[|@Qd@cAzC_@lAc@zAc@xAa@xA[jAIXo@lCYpAk@jCeCzLa@rBcA|E"
                     },
                     "start_location" : {
                        "lat" : 60.5993061,
                        "lng" : -134.8699379
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.7 mi",
                        "value" : 4390
                     },
                     "duration" : {
                        "text" : "54 mins",
                        "value" : 3216
                     },
                     "end_location" : {
                        "lat" : 60.6833479,
                        "lng" : -135.0586331
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eYT-2 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYukon 1 W\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ysdqJpnbwXOZMd@uA|GwAlHkCxMiBxIcAfFIz@a@nB[zAU~@Sv@Qn@o@pB]hAQb@ITM\\Uj@}@tBUd@KROXe@z@o@hAA@[f@GHU\\]d@KLu@~@q@r@m@l@SLWTc@\\]Xo@`@]RGDYNIDWLMFSJeAf@a@RKFoAl@aChAkAh@qHnD}ExBGDa@Pc@Ra@PID{@^a@PQHQHoAh@WJa@Rc@PQHOFeBt@aA`@i@Va@P]Ng@Ve@V_@R]T_@VC@_@Xc@`@c@^g@f@_@^Y\\WXa@f@k@v@c@l@g@p@_@f@_@h@aB|Bs@`A]d@IJgBfCcAxAY`@a@l@{@nAg@p@]d@]f@Y^ED{@lAwAfBu@~@c@d@IJ_@`@CBc@d@u@v@c@b@YVeA~@w@p@m@f@q@h@i@b@kA|@e@\\g@ZYR[RMJaAj@OHu@`@u@`@a@ROHa@RgKbFwBbAcAf@w@d@cAf@{DjBsAn@yB`A"
                     },
                     "start_location" : {
                        "lat" : 60.6497296,
                        "lng" : -135.0220088
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "180 ft",
                        "value" : 55
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 60.68383199999999,
                        "lng" : -135.058835
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eYT-2 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYukon 1 W\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}ekqJlsiwXU?E@E@}@b@"
                     },
                     "start_location" : {
                        "lat" : 60.6833479,
                        "lng" : -135.0586331
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 207
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 145
                     },
                     "end_location" : {
                        "lat" : 60.685311,
                        "lng" : -135.0573498
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}hkqJttiwXYGIFOLYDQBI@I?UEMEMGIGCAIMMQOWKUACCKGSG[EOKm@Im@Mi@"
                     },
                     "start_location" : {
                        "lat" : 60.68383199999999,
                        "lng" : -135.058835
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 mi",
                        "value" : 2131
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1423
                     },
                     "end_location" : {
                        "lat" : 60.69928710000001,
                        "lng" : -135.0461584
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eS Access Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRobert Service Way\u003c/b\u003e",
                     "polyline" : {
                        "points" : "erkqJlkiwXWiCMeAKcAo@sGMeAKcAKeAq@sG_@yDe@mEs@{G}@yIk@gECOMo@k@aC_@gAyAyCGIqAgB}@u@_CiA{@KA?c@?U@M@e@Ba@JMBUHa@RYLGF_@^_@`@_B`B_@`@aB`B_@`@o@p@yAxB_AnA}DrEmAnA}@l@YHIBYBa@FAAY?IAc@C_@KAA]Mg@_@g@]CCO@}@gAe@i@YYAA_@[CCYQCAa@QA?WIICSEMAIAY?OAS@O?OBQB"
                     },
                     "start_location" : {
                        "lat" : 60.685311,
                        "lng" : -135.0573498
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 mi",
                        "value" : 1711
                     },
                     "duration" : {
                        "text" : "21 mins",
                        "value" : 1243
                     },
                     "end_location" : {
                        "lat" : 60.7125017,
                        "lng" : -135.050634
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eS Access Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRobert Service Way\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Robert Service Way\u003c/div\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "qinqJnegwXUNYJULq@d@IHQR]^kCpC_@b@}AhBaAfAo@v@MPSXINWb@KVMVSPSf@Md@oAxDEHg@~Au@zBGLs@dBQb@_@z@Ud@Wj@CDYn@Q^ILc@t@q@|@CBWXOL]\\[VQNi@`@SLOHE@ULKBc@Ja@BA?a@AA?a@GA?WIg@O]Mg@Sg@UeAk@UOKGECYY_@]YUGG_@_@Y[e@c@a@_@QSMIa@[IISOa@_@mBoBqA}A]c@AA_BcCsAkBGKGKGKEI?CCI"
                     },
                     "start_location" : {
                        "lat" : 60.69928710000001,
                        "lng" : -135.0461584
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 229
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 60.7143307,
                        "lng" : -135.0488822
                     },
                     "html_instructions" : "At the roundabout, continue straight onto \u003cb\u003eS Access Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRobert Service Way\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "c|pqJlahwXAMAMAGCEACAAAAECIAGDCAC?A?GCKGOKo@o@sCoCeAaAMO"
                     },
                     "start_location" : {
                        "lat" : 60.7125017,
                        "lng" : -135.050634
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 637
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 494
                     },
                     "end_location" : {
                        "lat" : 60.71971259999999,
                        "lng" : -135.0522818
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e2nd Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qgqqJnvgwXSESMKCOGUE]@KG[\\_At@IHEFG?IAy@j@g@\\_@ZeAr@q@d@aBlAyCvBsA`AcAj@}CtBED"
                     },
                     "start_location" : {
                        "lat" : 60.7143307,
                        "lng" : -135.0488822
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 60.5164037,
                        "lng" : -134.3331297
                     },
                     "step_index" : 2,
                     "step_interpolation" : 0.7602093560698593
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "mv{iJ|r{xXei@aoAgLiScMxUqIzCkQoVor@_z@ij@s|@eg@mUujAgwBal@{]o_@k`@cSqr@gi@kkAmn@ueA}q@_q@{`Agb@mn@Juw@wGax@oRoc@lCoJ{WtAk]uj@s^k^_FccAauAwb@oJuh@mUio@dAo\\sd@oYc~@_sAwwB}oAgpAcgAcqBaH_Is`@wDa]dGgOiEaPs_@iJay@eQy}@_`@qTyWg`@cOmn@yHyc@cNcJyPgTgQywAqO}wAsQwoBag@}aBsh@uk@gx@_^_n@aSwRokA}e@ecAqTiqAcS}y@cd@kMynAcTo[}IiJo`@pCe|BBsdG{Mg\\qa@oRuX}S{Pcg@yb@auA_e@g\\g`@eg@gi@a_@ex@e]u\\kNuTdEom@nBqk@{Hat@vEqt@zIor@nYqRfHw]eL{o@wNm\\_V}qAcnBo~@ylCq|@kqBmNeaAya@}m@ukAq|Cu}@qcBagAs`@ia@`Gq\\cR{f@adBczAyoCar@e{A{o@aiAeaAwf@cZaM_LwZmTq{@g^i]}g@nB{q@Rek@gk@a\\{Vyh@nD}`@|D}l@wHs^mSo_@V}OtIcMna@sV~kAu\\z}D_^tzBmn@~z@_q@|gCoiAz~Ega@pw@c_@|EkIsb@q\\mz@g`@yx@yk@ubA}d@suAim@an@sUojAaeAkpDkeAoyE}[ggBeSsoCiRaiCye@utBci@c_CsX_dAkPuoAyDcaAog@w|Buh@}~Bl@yvAZegGXu}B|Bw`AgRme@ePe{AjCkl@{L{qAkKsN}\\sAeiBjd@wk@zA}QwuBid@ckCuXgScJm\\f@_uBxMgyA~Iyy@p`@u[|p@kkDbP}qApIy`BwVsjAsb@ql@}pAu`@gc@}}AsDud@dMyi@fTshA|e@klA`Y}lAlF{j@gHsm@}a@yd@qhAatCgGjTKbv@sKv_B_`@p|Ek_@`cBco@|pAyoBdvEyl@nrAeh@tf@ov@l}AesA`lBcb@~u@wUfqAaeD|{FoeDjrGaq@ppAe|@vf@aj@nfAmaA`dCwFju@mGrSaHsBb@uNc@tN`HrBp@eQyLHkV|m@od@|bAof@~yCkQ|uA_\\p`@_Vbu@ij@jx@gSfmAyb@jdAeL~lF^vxAtS|z@rNlw@mKpuAu_@d_Ai_@bbBc`@lgCgQjsCwRjwCf^`hEuR|bJ{n@jiDmXpfH_j@zoGeFngEq_@ztJc_@twEq~Br`GupBjeCmj@rbCi`@b_@mp@l[yf@xo@u~@vi@gNs\\qVudAuNdG_YbVeJ}Ga[lTsWvd@_q@_k@__@~T"
         },
         "summary" : "Klondike Hwy",
         "warnings" : [
            "Walking directions are in beta. Use caution – This route may be missing sidewalks or pedestrian paths."
         ],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
