# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=Batman+Turkey&waypoints=Palm+Jebel+Ali&avoid=ferries&destination=Burj+Khalifa&mode=walking&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ0wpjbvxGC0ARLhZh_uJSuo8",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJLyIJKfIQXz4RaI10pzbH6O4",
         "types" : [ "establishment", "natural_feature" ]
      },
      {
         "geocoder_status" : "OK",
         "partial_match" : true,
         "place_id" : "ChIJS-JnijRDXz4R4rfO4QLlRf8",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 37.8896027,
               "lng" : 55.2834383
            },
            "southwest" : {
               "lat" : 24.9678973,
               "lng" : 41.12953419999999
            }
         },
         "copyrights" : "Map data ©2023",
         "legs" : [
            {
               "distance" : {
                  "text" : "2,301 km",
                  "value" : 2300612
               },
               "duration" : {
                  "text" : "18 days 13 hours",
                  "value" : 1600698
               },
               "end_address" : "Palm Jebel Ali - Mina Jebel Ali - Dubai - United Arab Emirates",
               "end_location" : {
                  "lat" : 24.9994412,
                  "lng" : 54.992947
               },
               "start_address" : "Batman, Batman Merkez/Batman, Türkiye",
               "start_location" : {
                  "lat" : 37.8896027,
                  "lng" : 41.12953419999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 918
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 711
                     },
                     "end_location" : {
                        "lat" : 37.88533109999999,
                        "lng" : 41.1383715
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e on \u003cb\u003eAhmet Arif Blv.\u003c/b\u003e toward \u003cb\u003e1610. Sk.\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eGo through 1 roundabout\u003c/div\u003e",
                     "polyline" : {
                        "points" : "_igfFqb`zF^_A\\cAf@yAzA}Dt@{BbAeCx@{BrAuD`CcG|A{DAC?AA??A?AAC?E?A?A?A?A?A@A?A?A@??A?A@A@A?A@??A@?@A@A@?BAB?nBeF@CRe@BE@EJE"
                     },
                     "start_location" : {
                        "lat" : 37.8896027,
                        "lng" : 41.12953419999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2807
                     },
                     "duration" : {
                        "text" : "36 mins",
                        "value" : 2171
                     },
                     "end_location" : {
                        "lat" : 37.865215,
                        "lng" : 41.1549207
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eÖzgürlük Blv.\u003c/b\u003e",
                     "polyline" : {
                        "points" : "inffFyyazFBIFOHUHQh@_Bx@qB`@{@DIRS\\m@j@cA|AqB~AwAzA}@h@Q~B{@bFaBxEyArFgBB@@?@?@?@?@?@A@??A@A?A@??AtG{BrAc@TI`D_AnEyA`IiCr@U`@MvH_CvEqAXK^OdA_@hAy@@?@?@?@A@?@??A@?@A@A@A?A@A?A@CjAeBVe@x@gBTk@zAiEt@sBRm@r@oBnFkON_@DEDGHG"
                     },
                     "start_location" : {
                        "lat" : 37.88533109999999,
                        "lng" : 41.1383715
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.6 km",
                        "value" : 6619
                     },
                     "duration" : {
                        "text" : "1 hour 22 mins",
                        "value" : 4902
                     },
                     "end_location" : {
                        "lat" : 37.8331379,
                        "lng" : 41.2180202
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eBatman Mardin Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD955\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "spbfFgaezFFAFABADADCFGBEBC@C@CBEBK@K?G?GAG?KCIN}@zAmDH_@Fi@hC}HRe@Rc@NYL[T]NUVa@Va@Zc@T]jA_BVa@`B_Ch@q@d@q@V_@Xa@f@s@T[d@q@V_@X_@PW^i@V_@DERYX_@BGX_@n@aADGt@iADIDITc@NWDKbAcCn@aBBEN_@Re@fCgGJSXs@fEgLhAoCVq@b@iAN]bB_ElAwC`@aApAcDjAuCnAgDb@eAXo@hAcCjAwBVk@JSj@_B~@gCJYL_@Rg@|AgExFeOBKdBqE~DoKvAwDbBsEjCmH|@_Ct@uB|Lg\\N_@bDwIr@cCfLqZj@yA|JeX^}@~FoOpFwNRk@rByF^}@vB}F~BqG"
                     },
                     "start_location" : {
                        "lat" : 37.865215,
                        "lng" : 41.1549207
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "35.4 km",
                        "value" : 35447
                     },
                     "duration" : {
                        "text" : "7 hours 21 mins",
                        "value" : 26459
                     },
                     "end_location" : {
                        "lat" : 37.669721,
                        "lng" : 41.4546064
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eBatman Mardin Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD955\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ch|eFskqzFPUR]Te@Ra@j@gAb@o@NQl@s@^e@hAuAFG\\a@jBsBXUl@e@DEdAq@pCuAdAc@NGtD}AdBs@fFyBrEkBfBu@`FqBXMbCeAbAa@^Q`@O`@QLGv@[bFwB`Aa@bBs@bAa@n@YPG~D_Bx@]PGvD{ANINGp@[j@YxAg@NGPGn@Uv@M`@IPCLCB?nCKHAjBDD?R?b@?L?@?RB`@Fn@HB@RDNBPDNDJ@h@HPBPBb@HF@XF`@H`@N`@P`@N^RdCpAtEbCfBt@d@L^JB?dAT`@HLDTBn@H|AJL@T@b@@~@@nAA`@?d@Gp@GvBWFAz@QnAc@\\Mr@YpAk@TMh@[`@Wx@o@\\WDCfEsDLMvCcC~CiCr@k@DENMZYNMZYNKjIgHlB}AhAaALKNM|FyEpC_CvAmANMx@s@\\YLKz@s@\\Yh@c@NMzL}JhCuBj@e@\\WZYRO@CjEkDLKlAcA~AsATQNKnEkE~CmC|AoAzE_E|EcE|AqAvCeCXUjB{AzDeDr@m@xCgCxAmAvE}DhJ{HdBwA\\YbHaGlGiFx@s@\\YjJ}HhDsCZY`BsAnFqE|AqAjHeGfDsCTQhB{Ah@c@bCsBfBuAhAy@pB{AzAqApBkBf@c@ZUXO~@i@n@WNGPG\\MBA`@KNEx@SfASrCa@TCb@GrASt@MfASXGj@O~@[d@Qn@Yj@]DCNILKVOFGt@m@~@y@?AZY\\_@^a@zA_BJKlAqArCyCh@k@`AcAzB_CDEvBaCZ[NQFIX_@d@q@Xe@@ATa@P[DGN[DGHQHSTk@^}@@IRm@Nk@H_@Lg@TuAHe@Fg@@MFk@BOHgAB]NuBHkADm@Fk@Dm@JwADm@Dk@Fk@Ba@@KFg@Jo@D]BKJk@DSFUVcAPw@@GLa@n@yB@Eb@sAJ_@^oAPg@Ni@Ng@^oAHYTw@^oA@ANg@Pg@BG`@cARe@Re@Vm@P[Ta@R[BEXa@Xa@LQv@kARUb@i@NUn@aADG`@q@DKTc@?CPc@HOFUNi@DOVgANkAPeC?GDk@NuDF_BJsARyC?YBaADqBHyF?EFsADqAFcBBm@P_F?AHgBD]B]R}A@GViAT}@^cA@CRa@P]BCXa@DET[f@g@LKJIPOROHG^ULIp@_@FEVM`Ag@^S`CiAHEt@c@XOrAy@p@_@|@k@VOd@]BA`@_@RSn@o@b@g@JM`@i@BG`AaBBEXi@N]LWPe@\\cAVw@BKV_ANs@@IJk@Ls@Da@L{@D[Jy@NiAFk@Hi@PyAFg@?CRuALcABSPwAHm@Fi@Hk@Fk@Hk@BQDYP{ATqBJ{@@EDe@Hk@BWBSD]@MDe@Ds@?K@a@Bk@?U@eA?QCkAAi@AYAQCi@ACUcCIu@Ec@QwA_@qDg@sEIs@OyAIk@{@sHa@qDi@{EQwAWmCe@uEK}@UqBWeCCOg@kE?GGc@Gm@MsAO{AQcB]cESoCAEIyAEm@AWGgBG}CAWAe@AWC_@KoAIqAGw@ASEs@GyAAe@KgCGyACe@GaB?GGqAGyAGyAKgC?KI{BIgC?AOaFCk@Ck@Am@GyACaAAYCk@Cm@AUAWGyAASAWIyACk@Eo@Cs@Ae@Ac@Au@?A?qA?G@k@?IDqBHeBDe@Ds@B[Hs@@OJ}@Hk@@IJu@f@wC`@aCTuATuAbAcGBOZqBX}BJ_ABYPcBRwB?ADk@Dm@B_@HeBBm@Bi@FaBDuA@a@DsCBuA?_B@gC@uC@mA@k@@m@DgD@{@@k@D{A@i@@}A?m@@k@FkJDcFD}D?e@@k@@yAHqG?KDaEBoB@m@@yA?KLqHB{A?GNmH@_@PuDF_BDq@@a@@q@?M@eB@_CByBBcA?A@k@@m@Bk@BsB@U?mAA_BAs@?AGyACo@E{@Gu@AQO_BSoBCKMu@I_@a@oBCOQq@W}@Us@CGWu@o@{AQe@CCOa@g@kAM[o@uAg@gA_@w@KQi@gAMU]q@kAyB}BgESa@m@iAiA{BKSi@iA}@mBUg@Sc@Ue@GMq@mB[iAACSu@GWCKG_@QmAU}BEw@?ECwCHiADy@@_@@aABqA@_ADuB?QHaD?QD{ABk@DcBBc@@m@Bm@LaFPoG@O^aND{AJgE@YFyAD{AHgC@_@@K@m@Bm@JsD@m@HgC@m@BaA@WDyAD_B@g@D{ADyAD{ADyABk@D{AHsDHmCBkA?GDqAD{A@k@Bo@@k@PaFPaFDy@FgBHkCBeA?M@G?KFmC@SBk@?GBm@Bu@BiA?GBk@BcA?WHoD@kA?aA?K@mA?e@?G?a@?C?G@yA@m@?KDoCDuC@w@?m@@e@?E?A?e@?G?k@?i@?C?e@?G?m@?e@?_A@Y?G?e@?G?yA?U?{D@kB@{A@sA?s@@}B@w@?e@@m@?E?_@@{@@WD{@?EDe@B]@M@GHy@TwAR}@@G@CZkA?Ar@wBBI\\}@r@qAP_@b@q@NSZ]LMh@g@@ALOJI@?\\Y\\YDCVSLKPIZQBABAx@a@BA^QBCXI^Ol@Sv@YDAZKbBo@`@MDCf@Qt@W`@Od@QB?XK^MHCVI`@MHCx@YBADAdBm@TIbA_@p@UZMTIdBm@lAc@TI`@MXIhDeA@A`@KZKlBm@@?@A\\IxBo@@ALCb@K@?^KzBg@b@IPC@?^G`@IjBYb@It@KPC@A|HmAfAQJA?AxBWnAQ@?nAQpGq@`@GfAOB?@A`AMVEzDo@B?XEHAf@I|@Mf@I@?`@I@?l@Kx@MD?\\EBAbAM^EB?@?d@GnEYB?x@Ep@C|BCR?t@AfAG~@ElAE`AED?l@A|@CR?vACfAAfA?H?`B@R@j@DF?b@D@?h@Jz@PLBj@L~@TD@v@PpAb@B@ZNn@XhEzBhCvALFhAl@f@Z|BvA`@Pj@RzATF@fCFl@@|@BL@hBAbC@hC@bAAV?r@?z@?dBJf@F\\FjA\\|@b@h@Tf@ZhA~@r@l@b@`@t@r@@@LNn@l@t@`@RBRBXTd@THFD@^RNFDBj@Vd@RhCfAFBNF`C`Ab@R^PPFNF`@PbAd@`A`@LDbBr@RJ~Ap@dBv@ZLhBv@`Ab@`@PrAf@dAXrAVl@FdAHdABZAbAAdAKnAO`AUVGl@Kb@ILCv@Mj@KXG`@Ib@KB?\\IdAQdASb@INCPCrCg@~@Q`@InAWXG`@Gb@Ib@GHCVEb@I`@Ib@Ib@IfB]`@GdASjB_@bASZGpAY`ASt@GNAb@AHAX?b@??@b@BJ?VDTFJ@b@J@@\\LPFh@Th@P\\J"
                     },
                     "start_location" : {
                        "lat" : 37.8331379,
                        "lng" : 41.2180202
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.1 km",
                        "value" : 3062
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2476
                     },
                     "end_location" : {
                        "lat" : 37.65629029999999,
                        "lng" : 41.4736222
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wj|dFir_|Fr@aAFINWXe@R_@FIRg@HYBGHa@Ha@@]?e@E_AAMEk@G_@?KEa@?ICm@Ag@?YBKDKHKJEb@MDAd@Ml@Uf@Qb@Ud@QBA`@Md@Q`@OXQTQNSJSFUDW?]?Q?YCs@Ec@ESAGKUOWS[O[Qi@Ma@Qi@Oe@[q@Wm@[u@[s@EISe@?A_@y@[w@[y@Wq@Qg@AGOk@Sy@G[?YBa@H]Fa@?a@C{@IgA?IMiBAs@@K@_@Bi@BODc@Jm@HYJSLOLIJGLILCPCZENAPCVEVAZCZAZA`@A\\?@?X@X?XAVABAPCRCZITGNIHIHMLOJKLILETEZCZAF?F?PDXFVHZFVBH@N@T?L?BATENINGNETC`@Ed@If@M`@Kh@St@Uj@SfA]\\M\\K^KTGHAFATAV?XCVAT?P@PDJ@B?F?LC@?NG`@Oh@Up@_@TOHEHGn@a@l@]JKFGTQn@g@h@a@FGDCBCBCBCDCBCBCBEDCBCBCBCBEBCBCBEBCBEBE@CBE@EBE?C@A@G@E@E@G?E@E@G?E?G?E?G?E?G?E?G@E@E@G@CBEDADAB?D?D?D@B@D@D@B@D?B@@?B@D@D@D?B@D?D?D?B?D?D?DAB?DADADAB?DADA?AB?DADABADADABAD?DABAD?DADABABCBE@E@ECK"
                     },
                     "start_location" : {
                        "lat" : 37.669721,
                        "lng" : 41.4546064
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11.5 km",
                        "value" : 11500
                     },
                     "duration" : {
                        "text" : "2 hours 44 mins",
                        "value" : 9840
                     },
                     "end_location" : {
                        "lat" : 37.5880948,
                        "lng" : 41.5206616
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yvydFcic|FtA?b@GTCRQHg@@c@@eAAe@Hi@?Y@CHk@@[COI]AK@GDEJ?NBPGVSJSRSFODc@RqBBSLg@@E@O?UBKFOFKV]?CFQH{@@YAWBUDMDGPUBM@_ADUDQJSx@y@FGVO~@g@FEPURCLMJKRGDC^Yl@YPAJ?z@ARCFGNMBCX[HI@AHQDa@?a@CS@K@IDENERU`@w@Na@Xo@HUHSb@{A\\{@^_ANg@HYFe@BU@GDSLYLWRe@Rc@BUFKBUCc@My@Q[AIBKFAHCNGBMHOAOEK@KDEDY@]@i@Ho@J[VgAV_A@ADINU?AHSFWPQFCNGLKHIBAJQLG@E@ORk@JGLCLCL@JDHJJHFF@@LFJ@D?F?L?LCJCLGDENCDCLGRQJMFIt@oAHOJOJKFCF?RAV?RCNC@?LGRKPODEDGBKBI@Q@O@MBMTa@LKPKRKHEFEBC?C@EFU?ADKDMBEHQVc@JUJ_@DGJSLWTWFIZ_@LKBCXU^S@ARKDADAB?B?B@DBBBBB@B?@BJL`ABHHn@Hd@@DBPH\\LV?BBBN\\LXHVLh@J`@Hh@Ht@H`A@XHrA?DFrABj@@R@HBFDF@@FHZVTPh@^bAv@j@\\B@f@XVJXHD?n@Fj@FVJJDHHJLJPJP^n@Xd@`@r@Zr@N\\FFDDB@@?B?DAJCf@ShA_@LGJIFGDGDIBK@C@G@KAOCa@Ec@AQ?IAK@K@O@KFQHMLQNYHMBIFQR{@TaADUBU?[?Q@M?OBMBO@EHYHWHYDSD]Hi@L}APkBFq@NkAJw@Fk@J}@BS@G@CDMFKZe@?Ab@m@Xm@HQDGFIFG@AHETILGLIVSz@u@zBqBJMT[FMHIDGHGb@Sn@OJEf@[t@k@^UNMBATULON]Pa@Zo@DIPUPO@CNMRWBGDM@G?K@Y@]?SDUF[Jg@BMPu@DWBSDw@B_ADs@F}@B_@DkABiA?M?e@?M?G@I@E@E@GBCBC^YHGh@]^_@bAwA~@_BLQJMj@i@j@g@TUd@k@`@m@`@o@RYVULMXO\\SLMDCLSV_@R_@DMDKLa@F]J[FQDIRUVU^[PSLQLQR]|AuC\\i@@ChAqBNWn@_A\\_@|@{@PQPUNQb@i@HMFGNY\\q@HQLUHMDGLONQNSBIDILe@FU?EBMHi@Hg@DSDKFQH[BMBGBGBEDCDAJAN?L?LAL@H@HDLJHN@@LVPd@LXLLTTJHLJ\\Tn@\\d@RZVDBVVX^T^R^P^Pf@LZ\\v@J^L`@Ph@?BFLFNDF@@HHNL`@^TVBBTX?@Zf@dAtADDJLTPl@\\bAt@~@t@l@f@p@f@l@h@VTNNLHB@B@D@F?B?F?DA@?PCVIj@Ub@Qj@UFCpAi@b@Uf@YLKHGDEBCDAFCDAFALAT?L?P?XAZAV?V@N@F@H?PEd@GPAFA\\EZCZ?^@j@JZFf@HJ@XBZ@d@?RAPCb@OHCNIp@]BAxA_AJIpAy@pAcAz@w@DCZ]Xc@N]d@qAz@wCFODMDIDEDIJSL[X{@\\iALe@F[Ne@Pg@L[LU?AV_@nAkBTUb@e@X]h@u@Z_@fAoAz@iA^g@h@s@h@q@Z[DENKh@]BAXMfAg@~@k@j@]RMRMl@e@t@o@VS`@WbAg@j@[^WZQ@ANGb@MFAF?@?B?@@B?@@HFJRNZFPBBLRb@f@BBB@@@D@D@R@h@@N?H?F@DBD@BB`@\\B@BB@?z@`@B@DB@@DDp@j@@@@@B@B@dAXB@FBB@RLj@XFDXHD@JB\\HxAT|@LHBx@JH@FBh@PFBBB`@L@?B@D?`@?l@@X@`@@@?B@B?DBr@PLDP?bBNh@Dd@DxANLBdAPd@HfBXv@NbAPr@H^DB?dAHD@R?FAD?b@MTMRMPONO@ANQVc@^e@@CLQHQ?ANg@J]BQD]B_@Du@Fg@D]H[JWJQXg@\\i@DG^o@TWNQTWNU@EBE@CDQD]BSHi@Js@@M?KBS?OBe@@SBQ@MFSFMJQVa@LMBCVOFEL?RBHD"
                     },
                     "start_location" : {
                        "lat" : 37.65629029999999,
                        "lng" : 41.4736222
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 177
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 232
                     },
                     "end_location" : {
                        "lat" : 37.5877475,
                        "lng" : 41.5225568
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qlldFcol|FCYAS?Y@Q?GBUBWLm@@M@I?K@K@G@GDKDM?E@E?C@M?I?E?G?E@EDGJQBG"
                     },
                     "start_location" : {
                        "lat" : 37.5880948,
                        "lng" : 41.5206616
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "63 m",
                        "value" : 63
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 37.5879884,
                        "lng" : 41.5231113
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eDargeçit Gercüş Yolu\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mjldF_{l|FCKAK?O?I?I?CAEACAICGCGACA?AAAAC?CAK?"
                     },
                     "start_location" : {
                        "lat" : 37.5877475,
                        "lng" : 41.5225568
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "32 m",
                        "value" : 32
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 37.5877444,
                        "lng" : 41.5232956
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eDargeçit Gercüş Yolu\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}kldFm~l|FHIPMTM"
                     },
                     "start_location" : {
                        "lat" : 37.5879884,
                        "lng" : 41.5231113
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 412
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 422
                     },
                     "end_location" : {
                        "lat" : 37.5889435,
                        "lng" : 41.5274747
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDargeçit Gercüş Yolu\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kjldFs_m|FWUCEIOg@_AWe@CECGMe@?CUaAG[AGCUOy@Q{@CII]I[I_@Ic@CMKe@Mk@EQ?E?I?OBSBOJa@DO@C@EBK"
                     },
                     "start_location" : {
                        "lat" : 37.5877444,
                        "lng" : 41.5232956
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1391
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 951
                     },
                     "end_location" : {
                        "lat" : 37.58222019999999,
                        "lng" : 41.5378211
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "{qldFuym|F@K@C?C@C?EACAEI[AK?ACSE]?ECKGa@AIAGCg@AM?C?O@a@@K?GJ{@BQD]Fa@BUBMBKFQP_@P[DGP_@@A?C@E@GDQ@G@E?C@CNYR[N[FMDG@CBCBA@CRKJGFIHIJWPW@CBC@CTQJGFCDAPGTI@?@A@?@C@?@C@ALS@CBCNKDCHCRELADAF@R@NDJD@?VFP@B?@?B?NELGTG@AD?NAHAV?PAHANETEJAFAF?N?Z@T?BA@?@?RIBA@?\\UDCBAFA@AXELCFADA^MZMFAJCf@KJC@A@A@A@?FIJOHQ@C@AJa@@GBGB[BSBU?E@I@M@IL{@BY?E@CAC?y@?Y?Y@G?IH_A@M@G?EH_@DMDKJUFOL[L]L]La@BIFUFY?E@E?CDg@Dc@"
                     },
                     "start_location" : {
                        "lat" : 37.5889435,
                        "lng" : 41.5274747
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 328
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 319
                     },
                     "end_location" : {
                        "lat" : 37.5812363,
                        "lng" : 41.5408739
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eUlaş Köyü Yolu\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{gkdFkzo|FMKCGACAE?COeAAQG}@?G?CAG@GBe@@E?A@ELo@BGBITc@JMFEJEPSBEBC\\i@R]`@q@NWHMNSFG"
                     },
                     "start_location" : {
                        "lat" : 37.58222019999999,
                        "lng" : 41.5378211
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 95
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 118
                     },
                     "end_location" : {
                        "lat" : 37.5816375,
                        "lng" : 41.5416794
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eUlaş Köyü Yolu\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "wakdFmmp|F@I@I?E@C?AAC?A?AACCAACAACAC?AAACACACAC?AAC?CACAACC?AAA?AAE?A?CAA?A?ACAAAAACAOCAAA?AAAAAC?C?A?C?CAI"
                     },
                     "start_location" : {
                        "lat" : 37.5812363,
                        "lng" : 41.5408739
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "57 m",
                        "value" : 57
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 37.58118899999999,
                        "lng" : 41.5419548
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eUlaş Köyü Yolu\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gdkdForp|FDCBABAFADABC@ABCFINMDATE"
                     },
                     "start_location" : {
                        "lat" : 37.5816375,
                        "lng" : 41.5416794
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.2 km",
                        "value" : 5191
                     },
                     "duration" : {
                        "text" : "1 hour 4 mins",
                        "value" : 3860
                     },
                     "end_location" : {
                        "lat" : 37.5694567,
                        "lng" : 41.5833584
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eUlaş Köyü Yolu\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "makdFetp|FMOAAAAAACAAAMGUIs@UOGQGWKm@[ICm@ScBq@EASIICKEUIQIQKSOSMSM]Q]OGCYMOGQOWOECECWS[SIE[Ou@e@s@g@SMw@e@IISSGGaAcAc@_@a@a@CEOQMOMQGKSa@AAQa@Uw@I]IYEQ]sAKc@Sk@EUAMAEGi@Ii@M{@M}@ESG_@CKOiAEa@C[?KAi@@S?WAs@@_@?G@I?I?CFe@@M@O?I?o@?i@@S?I?I?K?KCMCOIUGSGSEQAM?EAG@G?KHs@Fc@@GH[DURm@DU?A@G@E@e@B_@@O?E@GDOFYNo@FSHSBGDI@C@CDCHEHELCTCNELGFEJKFIZg@PSBEDGDEJGDCDAFCF?XAJAPCZGJEHEBCBALOHKNWPWJQJUFQRm@N]Tk@FQLo@J]Jg@HUBEBC@A@A@?DADAP@B?b@@D?`@@^AB?`@Eb@EFAL?J@N?d@@N?P?v@AD?h@CP?`@Aj@@@?P?F?B?F?B?B?D@T?PAJCDAFEJILKHIHMVc@f@aAXe@LWTi@Xs@Lg@HY@C@C@A@A@A@A@A@?B?F?~@AH?JAB?DApA_@h@SNGh@UFCPK@A@CBEDM@E@E@CH{@@GPkBHw@B[Hk@Fa@Ni@Ro@L]DGN]f@eAb@_AHOHSNc@Jg@DQFa@D[Fu@@ODq@BWD]B[Fs@H{A?ED_BBcA@_@?M?]?O@OD_@@KJs@Fc@BSNgAJi@Fa@TmAJs@Lm@DOJe@Nm@Ne@Rs@Tw@L]H]FW@G@KD_B@_A@MBKHc@HYDOHSHQLYT]NWJ[Ri@Xw@Xq@JUFS@CVcARs@V{@BGL]Rk@FQFOXaADKZ{@LUJSd@q@TWf@c@j@c@VWHIj@a@r@a@z@m@n@_@`@W\\SDAHEZKDABCFCPOPSHMRe@Pe@BG@IBQDQFYHa@H[Jc@J_@Pe@FQL]@CHOd@q@NSNUNQBERSVWRIHC@?D?H@"
                     },
                     "start_location" : {
                        "lat" : 37.58118899999999,
                        "lng" : 41.5419548
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 km",
                        "value" : 3505
                     },
                     "duration" : {
                        "text" : "40 mins",
                        "value" : 2382
                     },
                     "end_location" : {
                        "lat" : 37.5839868,
                        "lng" : 41.6143337
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cxhdF_wx|FDSh@KDOoBkAK?c@Be@@eAc@Wc@[[SS[aBKi@m@yCQiBQuAEm@KyAEk@?EAoD?GDc@TuBDM\\kA@_B?m@Cm@GyACi@a@sDCUVgCG_AGuAACg@kCUQ{@o@aAq@]Kg@MUCUoCC_@m@eCBkACOYsAw@mDAgACKgAeFGaA_@sA[iACGwAsCaB_CSe@m@uA_AyDEGk@s@EKi@kAc@}@g@[_@Ua@WYWsAsAMMg@o@i@o@_As@uAaCoAyA]}@M_@CEY_@o@{@Qk@o@yBo@cAe@w@eA}@wAmAwAmAOMESGUm@y@eBYSYWa@[e@YoAm@LSa@KkAg@mA"
                     },
                     "start_location" : {
                        "lat" : 37.5694567,
                        "lng" : 41.5833584
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.9 km",
                        "value" : 3861
                     },
                     "duration" : {
                        "text" : "49 mins",
                        "value" : 2954
                     },
                     "end_location" : {
                        "lat" : 37.576406,
                        "lng" : 41.6541357
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}rkdFqx~|FHAJEPMVSR_@JIHETENGHGLONSRk@b@gCP{AD[BaA?gBByA@U@eAAy@CaA?e@?u@@mD?UDmAJ_BFm@DYTeBHg@Fs@Bk@HuBBeAB_@BKFM@CFIDM@KBSBWBWBYBO?S?O?]?E@I@MNiA\\iBFSBM@M?E@GAaB?U@UDUBIDMBM@K?A?SAOAUAU?G?m@PsAPw@La@DODUFw@FgA@S?Q?QAMAMAM?Q?qAB_@?YAYC[?[?SBY@Q@QFMN[HW@CBIDODIDKDYDQBMFMJSLYFSDSBODO@M?SAOAQ?KAM?G@UB_@Lq@Fi@@O?Q@IBKBI?CFMDIBI@GBM@U@WB_@De@D]BS@W@c@?S?o@A{@?ICICGUq@EUCQSkAOy@GUACCGEKGUIg@Gm@AS@M@ODOBMDO@OAM?CAGMm@Us@EKAOAM?SDODILIJEHCJEFIDGDMDM@KBIDG@G?KAQAACQCOAQCIEEECEAGEEGCMAKAO@OBQBS@Q?KA]Ei@CIGIGECICECKCM?Q?SBO?EFg@NaAHkABSBODMHSBMDO@O?IH{ABQDOBGl@{@b@k@JO?ADKDKf@_BHSBIBEBEBMDMBQPiALk@Na@j@oALY|@oBTm@@CZk@Zi@`@_AFERUDGDIDOJWPo@@I@KM{AAKEoA?I?K@K@ODML]JUb@gAFIDEBADAHCHCHEBGBI@I@MBQ?CDOF[LUHIHIBCJGFCDCFELS"
                     },
                     "start_location" : {
                        "lat" : 37.5839868,
                        "lng" : 41.6143337
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2609
                     },
                     "duration" : {
                        "text" : "30 mins",
                        "value" : 1775
                     },
                     "end_location" : {
                        "lat" : 37.5546507,
                        "lng" : 41.6630104
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qcjdFkqf}FC{@@GDCfBIDBNDbAPv@FN?N?P?v@QfCq@jA[|@SvHkBvB_AjAs@zG_E`E}B~BqAfDmBVKbBw@lCyAtEwBzBcAbAi@rCwAnAq@fCuALGnAo@tBk@xAm@VEp@KTC~@E~AGn@ERAb@ChBIzBKhBGlBMh@Er@GPA`AGv@EV?`@@"
                     },
                     "start_location" : {
                        "lat" : 37.576406,
                        "lng" : 41.6541357
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 360
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 268
                     },
                     "end_location" : {
                        "lat" : 37.5529447,
                        "lng" : 41.6664696
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDargeçit Midyat Yolu\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "q{edFyhh}FnAqD`@eA`@gAp@iBFQjAeDz@qA"
                     },
                     "start_location" : {
                        "lat" : 37.5546507,
                        "lng" : 41.6630104
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.2 km",
                        "value" : 6198
                     },
                     "duration" : {
                        "text" : "1 hour 12 mins",
                        "value" : 4323
                     },
                     "end_location" : {
                        "lat" : 37.5345343,
                        "lng" : 41.7288896
                     },
                     "html_instructions" : "Continue straight",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "{pedFm~h}FFIFKDOv@{B`AuB~BqFb@sAT}@Na@La@lAmFNk@BU^cBl@wCRoARoAh@qDTkB?AVaCRiBJ{AJgB@KBs@L_C?C?ODw@DiC@uA@c@?YBiB?aBCsD?WE{AKkDMuBIsAIuACaAAyA?yABsAHqAJgAZkB^iBBGt@gCr@aBl@iAP[f@{@|BwCRY`BsBdAuA~AkBPWvBoC|@iAp@{@Za@xAiBLQr@_ArAaBfAwAn@w@p@}@|AkBxAmBZ_@JOfAsAtAiBlA{A|C{DX]vAmB~@uAV_@Tc@l@eABGt@}Az@{BVm@j@sBj@mB\\oBh@sCf@yCtAyIjAmH~@cGJk@Hi@RwAh@kDVgB\\{BLw@^qCVsBV_DLmCHeBD{B@}CAiCAm@GoCS{EOeEIcC?CIgCQaFAe@AGWiGCs@FUK{F"
                     },
                     "start_location" : {
                        "lat" : 37.5529447,
                        "lng" : 41.6664696
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.3 km",
                        "value" : 6346
                     },
                     "duration" : {
                        "text" : "1 hour 18 mins",
                        "value" : 4678
                     },
                     "end_location" : {
                        "lat" : 37.4906475,
                        "lng" : 41.7639508
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "y}adFqdu}F@C?C@A?A?A?A?A?C?A?A?AAE\\[\\WhDgBb@W^SjBcA~@k@fAi@l@[JGz@]bA]fA]VKzAo@@@`@]n@g@h@m@`@m@Vg@n@{A@Cl@sBb@wA\\kAHSh@cBX{@J_@Nc@v@mC@Cf@sA^}@`@u@NQNU\\_@t@m@LIXQd@U~@a@LElAa@x@]PI`Ag@nAu@hBmAz@g@VQ~CoB~B_Bf@]b@_@\\_@Ta@d@_AJWVu@Ry@RoAP{@PsAVcBVcBRaBRkAPeA\\sAZiAFYf@yA`@qAl@kB\\y@r@kBj@kAdAoBx@sAx@oAZe@`@o@|AaCf@w@t@iA|@sADG~@sAp@{@LOt@}@JKnAuAPQdAqAd@e@~AiBzAeB?A`BgBzAiBFItA}AbAiAX]|@cAt@}@HIx@}@\\YTSp@c@RMLGr@]BAz@W\\M|@SlBULCxEe@bAIFAp@Mr@M~@[rAg@zB}@n@Un@Ov@Kb@AL?h@@hAF`BTr@Jt@Dh@?\\Cn@K@?^Of@UZUVUfBsBDE\\a@h@g@bAm@`@Oh@QB?`@G`@AbACf@Fn@JhATh@Pd@Pz@h@@Bp@n@HHHHHHHJHHHHHHHHHHHFHHHHHHJHHFHHHFJHHHJFHFJDJFJDJDJDJBJDJBJBJ@LBJ@J@L@J@V?J?J?LAJAJALCJAJCLCJCJCJCJCJEJEJGJEHGJGJGHIHGJIHGHIHGJIHIHIHIHGJIHGHIJGHGJGHGJGJGHGJIHGHGJGHIJGHGJIHGHGJIHIHGHIJIHGHIHIJIHGJK"
                     },
                     "start_location" : {
                        "lat" : 37.5345343,
                        "lng" : 41.7288896
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2175
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1556
                     },
                     "end_location" : {
                        "lat" : 37.471792,
                        "lng" : 41.7670998
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDeğerli Köyü Yolu\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qkycFu_|}FDDHBD?J?L@`@ETCb@KfASJANCj@Eb@I~@Ut@KbAIb@Af@ClA?xAEnAEJ?d@?n@Bj@DdAL@?X@HA\\?n@EPA`@B~@Nz@Nb@FJ@HALAREv@Wb@Kj@ORGXEPARAr@?fBIbAGDAFALK`@_@\\SRMNGNCPEh@EpAIB?fBUh@GXGTGZOd@SPILEREb@ER@^BfANv@?\\Ax@Cr@G^Af@Ix@W|@QJAnBc@XIVMVM\\KXMXOTSVUb@g@`@i@VYLKBAHGHAFCD?N@J@JBbB`@~A^j@L"
                     },
                     "start_location" : {
                        "lat" : 37.4906475,
                        "lng" : 41.7639508
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.3 km",
                        "value" : 3272
                     },
                     "duration" : {
                        "text" : "39 mins",
                        "value" : 2366
                     },
                     "end_location" : {
                        "lat" : 37.4454955,
                        "lng" : 41.7773194
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uuucFks|}FNQHKDGBIJWl@sA|@cBJSDKBIHOBEBEDEDCDEFEd@Qf@OLEFCHEBCFIDEDEFGJGFEHEXMh@Kt@KtAO\\CNAJCFAHCBAB?HE@A@?@?@?@@@@@?@@@@@?@?B@@?@@?A@?DA`@INGNGFCDEBAB?@AD?D?h@?`@@H@H@D@D@F@B?B?BAFAD?XEJCVGFCDAB?DAD@V?D@D?BAFAt@CdA?b@?r@Ef@GZCb@Ev@Kj@K^IZK^QRKPMDCFGDEX]PYJQDIBCBCDCBCB?BAB?\\BXBD?BAD?BADCLIPUHKFMDGBIBEFMHMLMNMb@YDAFERK`@YHENKDCB?DCBAD?BALAn@G`AG|@CJAh@EJAf@KJCPEPC`AC^AD?DAHCPIJCJGf@Ur@[b@Oj@Sd@Qp@SRCTEd@CLCF?DAFCJEPIHCHAJANAZEJCJELGBATOBCVQHKDEf@w@n@}@p@{@FGr@{@@?x@gAt@cAX]HI@ADENMZUPKRMVK\\M`@KXIVGFCr@Sl@WDATMf@Y`@WBCJEFCBABAB?FAH?D?D@H@PDVHd@Rj@^HDLFJDVF^Hn@H`@Nr@\\@?d@Rt@ZnA`@t@RHBHBVHFDB@BBB@@@@@B@@?B?B?B?@?@?BADABAHEZ[LKDETK`@WTKFCDCBAB?DAF?J?b@DN@H@FAJCHCHEJKZYBCFE@?RKn@Wn@UHEDCDCFEBE"
                     },
                     "start_location" : {
                        "lat" : 37.471792,
                        "lng" : 41.7670998
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 504
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 344
                     },
                     "end_location" : {
                        "lat" : 37.4424024,
                        "lng" : 41.7809901
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "kqpcFgs~}FLADCDEFMJUJ_@^eAH]BODMBIFIBGDEFEBC`@UTKDADAJAHAFAF?B?DAFAFEJIb@c@FITSVYDIPc@Xi@R]L[HUDO@I@G?E@I?I@G@I?GBIBCBEBCDAPERAFCDCFEFCFAHCVK"
                     },
                     "start_location" : {
                        "lat" : 37.4454955,
                        "lng" : 41.7773194
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2212
                     },
                     "duration" : {
                        "text" : "31 mins",
                        "value" : 1831
                     },
                     "end_location" : {
                        "lat" : 37.42592450000001,
                        "lng" : 41.7898429
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBostanlı Köyü Yolu\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_~ocFej_~FVG^A\\@~@DD@vANp@Pz@PTFVB@?L@P@B?\\AZEn@EPARAVBh@AB?VAJAJAPELKDEHIZa@T]R[FGDCJEFCF?@AH@D@DBDB@B@@BBDDBBBB@@@@DBD@F?F@LARAp@E@Al@IL?F?H@HFFFDHFLDJBDFBH@F?DAB?@AJEHIJOVk@FKLORM@?JEPCV@P@D?XFj@PH@H@FCj@c@l@g@rC_Cz@q@JIPOvAmAn@i@JG\\Yb@OfCs@ZKf@QlAc@`@ORQZYv@u@XWBEFKpA_CHMLQ?AHMhAgAv@w@`Ag@DA|@SBAd@G\\Eh@IZEFAZEVCPIXKf@SBARSTWFMN]HQ|@kC@GHm@@_@?IBqABu@"
                     },
                     "start_location" : {
                        "lat" : 37.4424024,
                        "lng" : 41.7809901
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "13.7 km",
                        "value" : 13707
                     },
                     "duration" : {
                        "text" : "3 hours 1 min",
                        "value" : 10846
                     },
                     "end_location" : {
                        "lat" : 37.3353186,
                        "lng" : 41.8529896
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_wlcFoaa~FjAhAHDPLZFl@Bl@Ab@I`@G~@SlB[B?|@Qz@Mb@CR@D?hAFxALF?bBJj@Df@B^@~@BfAD\\BDBLDPL?@RRP^Vv@Pd@Pf@DJNXNTTTNJ\\X\\XZX`Ar@VJNDN?NCPEj@OBAZO`Ae@pAm@l@c@b@]T]Te@Zw@t@_CBGf@kBTeAD]Hk@\\aCRwAJs@XyB@EJc@@ENc@hA_BV]^m@\\u@l@aBNYP_@d@u@vCgDp@{@dAmA|@_ADClCkCDClAoAz@{@p@w@Tc@JURi@Je@Fa@Fw@@Q@a@?s@Gu@M{@EUQw@kA}EKy@AGC}@BkCDcEFyAH}@TiAx@eDl@wBb@s@JK\\c@v@k@LKlFaDn@_@lAw@jAi@tAc@jAYbAMnAK`AAfA?n@?vAAF?V@l@N@@bBl@rBp@RDhAPd@Ft@@n@?P?hFi@bCMnAAB?jBGtAWp@MbCc@~A_@l@[b@[n@k@~B}CHMj@m@JMl@_@@A`@Sr@Ob@EvAIl@CnBIv@Ox@Uf@U^]TSb@c@z@yArAuBfAyAXc@p@_Ar@k@f@]DEnAg@n@Sl@Iv@?`@Bh@FLBx@R~@\\`@P`@Rz@b@l@`@PNDBRVVb@BD^hAFNX|@Vt@|@lC`@rA@FTlALhADx@Fz@DvBBvAHvD@PDl@Jh@Jb@LXLX^l@ZXDDd@Xx@R^DRBn@EB?l@ITMHCh@[JIRQRWHUFK^uALcAHm@Fi@D_@ZmB\\oAv@oBp@mAz@iAt@y@HGhAs@t@]BAtAg@x@Qx@ILAb@CB?d@?fAAn@?dB?v@?N?jB?tB?vA?bA@t@Cv@Ix@O|@]t@a@t@g@dA}@jIwIpBuBlBsBhCoC~BcCxB}B|BeC~BcClBqBvB}B`BcBhAiAzBaCvByB`CkCzBoCvBsCxBsCpBmCx@gAt@_A|B{CjBgCfAyAf@s@vBqC`BwBvAoBdB}BjBgCx@eA`AmAdAsAp@s@pBoBxByBtBsBzBwBxAuApAqAdCeCfCcCzByB|@{@vAuAxA}Az@y@t@s@b@_@rAuAhBiB~@}@`E_EnBkB~A{AhAgApBkBrBoBx@u@f@e@j@m@lCiCx@w@rAqAb@a@~A_BHIrSiSlBkBNM"
                     },
                     "start_location" : {
                        "lat" : 37.42592450000001,
                        "lng" : 41.7898429
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2813
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2038
                     },
                     "end_location" : {
                        "lat" : 37.344857,
                        "lng" : 41.8822487
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w`{bFelm~FMkBWiCyBaSMmAwBqNyAwJWw@Sw@Ww@Ie@I[K[I_@Us@Sk@GUK[K]GWMa@[mAe@_B]oAe@cB_@uAQm@[eAe@kBSo@Qm@a@uA}@aD]kAg@eBW_AK_@Mi@CKq@wB[iAKa@K[M]_@gAk@uBUu@Uk@MWIUKYe@iBCMa@aBCKa@eB]}@Uo@So@Uq@YaAW_AW_Ae@sBc@aBY_AWaA]qAUw@Uw@a@}A_@}AFk@"
                     },
                     "start_location" : {
                        "lat" : 37.3353186,
                        "lng" : 41.8529896
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.9 km",
                        "value" : 2916
                     },
                     "duration" : {
                        "text" : "35 mins",
                        "value" : 2085
                     },
                     "end_location" : {
                        "lat" : 37.3451348,
                        "lng" : 41.9135819
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAlanya Cd.\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "k||bFacs~F?UBQt@iEDOv@gD`@mBh@iCR_Ad@iBnAkDh@wAH]TaAP}@\\}A\\qBd@eFJqAX_DHeAVuCTwCRkCBa@ReDVaEFsALgCF}CH{C?g@?]@_@YcBCQWgBAGCUWuAAGc@mCG[AMYcBKo@Mw@_@aCYmBIq@m@gDk@wCG[Kc@_AeEqAeGeA}EWoAw@kDYqA[uAa@cB[cAEQCKAK?M?I?G?G@K@I"
                     },
                     "start_location" : {
                        "lat" : 37.344857,
                        "lng" : 41.8822487
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18.4 km",
                        "value" : 18375
                     },
                     "duration" : {
                        "text" : "3 hours 39 mins",
                        "value" : 13110
                     },
                     "end_location" : {
                        "lat" : 37.35755959999999,
                        "lng" : 42.1145575
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMardin - Şırnak Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidyat - Cizre Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD380\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "a~|bF{fy~F{@{B_@kAGOk@iBOc@Oi@?AMg@W_AQw@Mk@i@eCKc@I]Ou@S}@g@uBUgAKa@o@wCa@iBKe@[yAi@}BEU]{Ae@qB[wAMi@GYMk@c@mB_@iBAGI[Ma@c@yACIMc@Qg@Si@Sg@Ue@_@u@a@q@q@eA]e@k@w@eBsBu@y@_@a@W[oAsAmAoAq@u@W]GGGIQWSYWc@Yg@IOQ_@MWEIa@gAMc@IUOc@Qw@Mm@Q}@SuAY_CG_@QwA_A{HMcA_@uCQwACW]gCEe@MaAEWU}BKaAGw@Eg@C[EwACa@?YAa@?g@Aq@?a@?_A@e@Bi@@u@FyAFoAHqBFwA@SDeA@YFgBB_B?S?eA?E?y@As@C}@EkAGeAIkA?EGg@Gy@Y_CQqAGe@MeAC[Im@UiB]wCoAsKc@kDCW]uCgAcJYcC_@iDSyAsBwPcBaNK_Aq@sFc@mDc@oDeCqS[aC_@gDWaCg@_FKcAq@{GsA}La@gE]aDKeA[sC?CWmDIoBGaC?oBBcCF{EDiEBoADcGFiFHoGTaSDwE@}@DmDFmDBeC@k@FqF?}AG{ASgGCm@MuDSuEI}BAc@KcCC}@QwDOqDM}DIcD@_BBiCJaCNqBJaAVuBr@kEl@}Dl@}Dn@{Df@iDXmBRuAj@}Db@_DDYdA}GDWv@cFZkDVeGb@uK~@oUtA_]h@iMh@aMVmGBe@TwFRaFdCwn@d@{Kf@oLD}@HuB|@aU\\kHd@gLNwER{EFaBJyBHqBLsCTuCRgC^kDV}BT}@x@_I?Eh@_FZeDXoBv@uHpAwLh@eFn@sFZgDv@kILmANoBHkABo@BgA@iA?gAGiC?EGgAImAASa@oDAIWyBMiA]{CQiBMkAK_AK_AWcCKmAUmBe@mDG_@UsBaBoLSgBUkBE_@Gg@QyAMiA[yCg@uEq@iGEWQ_B]eD]{C_@oDAKWwBKgAm@kFe@eEqBiR"
                     },
                     "start_location" : {
                        "lat" : 37.3451348,
                        "lng" : 41.9135819
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "66 m",
                        "value" : 66
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 37.3570928,
                        "lng" : 42.1149715
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wk_cF_o``Gx@Yb@w@"
                     },
                     "start_location" : {
                        "lat" : 37.35755959999999,
                        "lng" : 42.1145575
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "92 m",
                        "value" : 92
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 37.3574335,
                        "lng" : 42.1158757
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yh_cFqq``G{@{AGyA"
                     },
                     "start_location" : {
                        "lat" : 37.3570928,
                        "lng" : 42.1149715
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1275
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 845
                     },
                     "end_location" : {
                        "lat" : 37.3522044,
                        "lng" : 42.1286791
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}j_cFgw``GRg@P_ALi@FSJ[t@gC^mAzAaFh@aB\\gAzA_FjBiGx@mC~@}Cl@oBzAuEJ[DKtAgEPi@hBiFZ}@BK@K@E?K?S"
                     },
                     "start_location" : {
                        "lat" : 37.3574335,
                        "lng" : 42.1158757
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.1 km",
                        "value" : 6099
                     },
                     "duration" : {
                        "text" : "1 hour 11 mins",
                        "value" : 4263
                     },
                     "end_location" : {
                        "lat" : 37.33334,
                        "lng" : 42.1847463
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMardin - Şırnak Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidyat - Cizre Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD380\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gj~bFggc`G~@gAlFuGX]zBmClAuAh@i@|@iALOh@o@t@}@|@gAz@cAdAqAz@cA|@eAHIlAwAdAkABEX[@Ar@{@Z_@r@{@HIdAqAZ_@bAmAHKp@y@v@_APQz@cA~@eARWbCeCf@m@`@k@HMZi@t@{ARc@DKRe@X{@b@yAPs@FUXsAN{@?CHi@?CHg@Fg@Dk@F_ADq@@[DmA?s@?q@?c@Cu@AQAcAEuAI{CIiDAk@AQKqEAaD?kC@oAWiD?GEm@ImAO}DEyAKsCSyDKqAGy@OwAAECSKs@U}AO{@WsA_@aBOo@K]Om@m@kBk@iBCI]eAAC[cAa@kAEOQq@_@kA]eAg@cBOk@CKKe@?EKi@Ie@K}@Gu@EwA?{@?A?e@?A@C@k@@i@Bg@?CHcATiBPmAL{@X_CPyAT}AVkBRuApBkOHk@He@VkBJ{@L_ADa@Hm@Nw@H]H_@Je@Ne@Ri@j@wAl@kAf@y@p@gAJOfAwAz@eA`CkB|AkAzAgA\\W`@Y`A{@p@g@l@g@p@a@jAs@RMz@q@b@]\\Yp@e@ZUbAo@TOz@o@XU`As@BAnAaA@?|BcB"
                     },
                     "start_location" : {
                        "lat" : 37.3522044,
                        "lng" : 42.1286791
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 182
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 150
                     },
                     "end_location" : {
                        "lat" : 37.3328837,
                        "lng" : 42.186658
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eYafes Cd.\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ktzbFuen`GGQAE?C?E@C?C@G@EFUTm@`@kAF[Fo@Fk@Be@BW"
                     },
                     "start_location" : {
                        "lat" : 37.33334,
                        "lng" : 42.1847463
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "9 m",
                        "value" : 9
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 37.3327997,
                        "lng" : 42.186641
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eYafes Cd.\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oqzbFsqn`GNB"
                     },
                     "start_location" : {
                        "lat" : 37.3328837,
                        "lng" : 42.186658
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 871
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 664
                     },
                     "end_location" : {
                        "lat" : 37.3325095,
                        "lng" : 42.19645329999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eYafes Cd.\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD400\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_qzbFoqn`GGi@CaAAk@JgBB{@BiA@[?eB?{A?_A?{@@YDgAH]?W?K@Q@m@@_@FaE@GDgCHaF@kD@uCCoA"
                     },
                     "start_location" : {
                        "lat" : 37.3327997,
                        "lng" : 42.186641
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "61 m",
                        "value" : 61
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 73
                     },
                     "end_location" : {
                        "lat" : 37.3330113,
                        "lng" : 42.19663560000001
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit onto \u003cb\u003eŞırnak Cd.\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "eozbFynp`GACAA?AAA?CYMC@[@OAGCKG"
                     },
                     "start_location" : {
                        "lat" : 37.3325095,
                        "lng" : 42.19645329999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1012
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 802
                     },
                     "end_location" : {
                        "lat" : 37.3369611,
                        "lng" : 42.2066552
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCezaevi Cd.\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "irzbF_pp`GS}CUaB[}BEUKq@AMCUEOCMISM]Sg@IOkAwACCKMc@e@OQGGKQEKGKKUIUGWEQGQAKAICQCSCOAKCGYcAIUMe@u@iBEIi@gAe@aA_A_Ba@y@EOGOEOGk@QcAUsAO{BC[CKCICK"
                     },
                     "start_location" : {
                        "lat" : 37.3330113,
                        "lng" : 42.19663560000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "13.5 km",
                        "value" : 13452
                     },
                     "duration" : {
                        "text" : "2 hours 56 mins",
                        "value" : 10581
                     },
                     "end_location" : {
                        "lat" : 37.3091662,
                        "lng" : 42.32907669999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBozalan Yolu\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_k{bFsnr`G^o@Vm@BGL]Fc@BW@W?q@?S?CIyH?AAYGgEEgCA]A{@?Q?i@C}@?QCy@SiKCqAAk@G{BCeBAm@EaDM_IEgBGcCKsDCm@KwD?QAs@AaA?GCyAC]?cA@KAMCkB?UAm@Em@Gg@CSGWMi@?ASw@Gc@G_AGg@?I?E?C@EBGRc@BI@E@I@G@O?I?U@GBQLi@Ni@BM@G@K@Q?e@Cs@Ak@?A@_@?SFc@@K\\uBLw@H]H_@Rq@BILg@FW@I@MBSBUDSBMBUBIBS@IBa@@a@C_AAg@@S@SBSBMJm@R_ABGBGDGDGLMZ_@NSDK@E@G@G?E?GAGAOWgAEWAK?K?I@ITqAR}@Li@PiAFw@@E@M@Q@E@GDYHWFQDKDIBEFCJINIHIBAJMNSDK@GBG?I?K?KAGAKAGIa@Q_AIe@ESAIAI?G?I?K?A?I@K?IHw@BMHw@@G@I@O@S@S@MBc@JaA@ENwADWH_A?A@QAM?IAICGAICGCEEGUSQQsAgA_@WQKGEQGYI_@G{BE_@A]AEAc@ISIGGGECECEACAGACAE?A?C?C?G@E@E@E@C@CDKR[RWDINSLMZ[f@e@pB_BJGj@a@p@e@PMHG@AJOLU^w@LYDQBG@C@GBM@M@M@U@M@M@KBK?CBIDQFKLWPa@FIFKLSJSDGFOF_@@c@@QAQ?[ASAQ?MCMCOAEEIEMGIAAEEEGGEKEUGSGQE[Ee@IKAMAIAECAACACC?AAA?CAA?A?A?A?A@A?A?A@A?A@??A@?BAB?JEb@IXITKFCJGJIh@e@LM@AFKJMLYJSHWBQFWBY@QBY@IBUBSBKDKFODKFGDGJMFGLMNITId@Kj@KHCJEFEROPS`@k@v@qAJS^w@P[b@u@\\c@NQVWLMf@a@ZYn@c@j@_@HEFIFGBC@C?A?C?A?A?A?AAC?AACA?AAAACAA?C?AAE@A?I@G@[Fe@LUBcAP[B[Aq@Ce@GUEOGWKYMQEK?G?c@HK@OBM?i@AW@K@E?QBM@SBG?E?AAC?CCACACAACI?IAW@Q@s@@q@@S@O@MF[BMVuARkA@GHu@@W?KAKAECGEGCACCA?AAKAM?_@Ce@EAAGAOAGAMAOAa@?O@SASAQCYEGAI?E?C@E@EBCBEHAFABADAFAHANCHAFELCJGJY`@]XGDC@C@A@C?C?CACAAAAAAAAAAC?AAA?A?A?A?A?CN]BGHY@M?M?I?MAIAIAOCMKs@Ec@Cg@?[?Q@I?CBSFODKDILQFIPMRQTSZ_@T[LS`@g@HKPUNM`@]PORULSBCRa@P[NSBCDIHKPMPIPCt@@N?JALEJGHKFIBE@E@G@CBUBa@B[F_@fB}F`@qABO\\_A~@qCDKb@mA\\_Ar@qBHSZy@hBgFt@yBX{@BI|GsRtEuMDI`B_F`@gAZ_AFWDMLa@f@sArAuDXu@bByEL]n@gBl@gBNe@`@qAf@gB\\oAVcAVy@\\oAx@qC@G`AaD|@cD@GXeATy@Li@DSFQDMDIFMDMDI@ADGLOd@a@RMLIRKTK`@QFGBEFEDKFMJg@VuA@CJe@Ja@Rq@R}@DUBS@K@E@S?M@M@O@YASGuA?Y?W@O@ODYHa@Lc@Ni@Tw@dAyDjB_H\\mAv@}CRw@|CuKJ_@fAwDx@uCBOXaAf@qBvA_FXgA|@aDp@mCh@mB`@_B@C\\uAb@_B`@yA^sAd@aBJ_@ZkAb@{ALc@Tw@`@_B^qARs@H[Ru@Ts@Nm@VaAVaAPk@Nm@Ni@Ru@@ENc@Nm@Ry@d@eBn@aCh@mBj@qBh@qBn@wBTw@d@cBh@uBp@cCT{@Ng@DOl@wBh@iBNi@Pm@VcAp@gCLe@ZeAf@eBZgAJa@ZqAJa@Nm@V_AT{@Pq@La@FQDQDOFQ@M@K?MAK?CAGEMKOQUOQUOQMQOMMKOIMEQIYI_@GWGSIWEMEKEOEICOAE?K?G?I@G@C@A@E"
                     },
                     "start_location" : {
                        "lat" : 37.3369611,
                        "lng" : 42.2066552
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "10.9 km",
                        "value" : 10893
                     },
                     "duration" : {
                        "text" : "2 hours 16 mins",
                        "value" : 8142
                     },
                     "end_location" : {
                        "lat" : 37.2484833,
                        "lng" : 42.4146896
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "i}ubFwkjaGFCLAD?H?T@N@V?^A\\A\\CXENEJEXKJERKXQHGNMTQFAHADAD?B@D?BB@@@@@?@@@B?@@B?B?BAB?BADADABCDEHEFABAB?BAB?@?B@@?@?@@@@@?@@?D@@?DAB?FCDCLELCTCRCPCl@IFATCLCR?N@TDR@TBP@JAHA@?DCNGJIHKLUP]Ra@BEPWNQLSLWHOFWBK@K@MAOAKAMEKCIAAGIGGKIOKQIKEGEGCOIYOk@]WQWOQOYUGKEIAIAI@GBMJYN_@FSNe@Ri@BIb@{AVy@Jc@DSLg@Ps@XgAPs@f@oBj@sB`@{AJg@VaAd@cBb@{A^mAH[HQLi@FU^cBb@eBHYZiA`@wANe@n@wB`@sAXy@Ja@Lc@Nk@FYHa@Pq@J_@Lc@RaARu@Nq@Le@V_AZkAHYBKBMNq@Rs@@GJa@Rq@Rs@Ja@BGBGFK@ATg@R_@LO\\k@Va@^m@`@o@Zg@\\g@^q@LUVe@PWPUr@kAl@_Ah@y@p@aAt@mAp@cA`@o@RYf@w@\\i@^o@JQt@gAj@_AR[P_@\\i@Zi@p@eAn@cAXc@NS@ATa@`AuAx@qAl@eAj@_AXc@p@gAx@sAv@mAn@cAj@w@^k@Xa@|@wAbAcBb@o@vAyBzAaCfAeB@At@kA`AaBdA_Bb@o@@Ah@w@^i@d@w@p@gAl@eAXa@BG\\e@|@wAbA}AHMr@iAv@qA\\i@LSj@_Ax@mAPUn@eAv@mAnAsBNUp@eA`A}A~@{An@gAFKt@kAp@eAv@oAp@cAz@qAVa@TYd@u@^o@n@cA@A`@m@Xa@Zg@\\g@n@_ABER[T]j@w@^o@l@aAp@eABEn@aAt@kAx@oAZg@Vc@t@kAv@mA|@wAz@uADG\\k@n@gAHQ`@w@r@qAp@kAr@gAj@w@Zk@Vc@r@qAj@_AV_@j@y@zC{ENWJOlE{G~@{AbAaBt@oAv@qAt@gAz@sAb@s@NSh@{@v@qAj@aAZi@Xa@@Ab@o@`AaBv@kAHMn@_A~@yAn@eAlAsBJQZc@v@oABE~@uAv@oAj@}@Xa@l@eAx@sAr@kA`@q@j@}@BEv@qAp@cAr@iAz@uAd@w@b@s@LQn@cAl@_A^k@t@kAx@qAVa@p@cAbA}A`A{AHKv@oAt@mAh@{@`@o@t@iAh@{@dA_Br@kA\\i@b@w@Vk@HSL[V}@FQLc@L_@FOBKBG@G@G?MAUAIAKESCMCOAMAIAG?Q?W?U?Q@UFo@Ho@Jw@Fm@@MLaAJo@H]FMBELQJMJGZQXKVEh@Md@KZG|@SZEhASfAQl@M^GfAQnAUnAU|AYfAS~@Q^G`@IdAS`ASfAQ|@On@Kx@Or@Kb@I^GLEVEVENCNAX?"
                     },
                     "start_location" : {
                        "lat" : 37.3091662,
                        "lng" : 42.32907669999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.2 km",
                        "value" : 4194
                     },
                     "duration" : {
                        "text" : "52 mins",
                        "value" : 3094
                     },
                     "end_location" : {
                        "lat" : 37.2479003,
                        "lng" : 42.462064
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCizre Silopi Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD430\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE90\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow D430/\u003cwbr/\u003eE90\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_bjbFyb{aGAcEEoJAoB@mAF{MFwH@yID}FBuEFgH?c@@u@HyS?e@?]?a@@cOJyY?mABoBAU@O@mF?qC?e@BeD?s@?m@?c@@_C@eC@aA@m@@oE?m@@}B@cB?K?iB?i@@oB?m@BiJ?s@?g@?k@@aB@yA@aA@uA?mB@iB@yA?S@oCDgJ@uBBwE@}DBsG"
                     },
                     "start_location" : {
                        "lat" : 37.2484833,
                        "lng" : 42.4146896
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 37.2477631,
                        "lng" : 42.4620711
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eİpekyolu Blv.\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD430\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE90\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k~ibF{jdbGZA"
                     },
                     "start_location" : {
                        "lat" : 37.2479003,
                        "lng" : 42.462064
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "14.1 km",
                        "value" : 14136
                     },
                     "duration" : {
                        "text" : "2 hours 48 mins",
                        "value" : 10061
                     },
                     "end_location" : {
                        "lat" : 37.1558055,
                        "lng" : 42.5688035
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eİpekyolu Blv.\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD430\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE90\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow D430/\u003cwbr/\u003eE90\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o}ibF}jdbGCq@?a@?eADgB?OBaEJ}DHwADy@Fq@HuAd@eELcAJy@XmBT{@XoAZsAJg@j@_CdAaDb@kAf@oA|@oBd@iANYP_@^w@f@{@T_@hBqCzCyDnC}C~AkBTYfAmAbAoAp@aAX]vCwCt@}@FEhAoAp@w@xA_BdFyFbDqD`EsEpJoKxDkETUpAwAlP}QDEl@o@nUkW|@cAf@i@x@{@t@w@fDcDJITYd@m@dAsA`AqAhBsB~EoFpGkH|EoFbH{Hx@}@~AgB|AgBhAmA`BkBrIkJtEcFfBuBvAsApBoBpFyGfDuDjDwDdVkXhDsDdBoBVW|B_CrFyFzAgBhAkAzLgNhXuZpFiG~OoQrOaQjHgHb@i@`FkGxNePFGlHeIjW_Yr_@ib@zEsFzBaCnB}BhD{DlAsAnGgHzBgCfOgPlPsQpBqBdC_C|@q@|@k@rBcAh@WHEbB_ApAo@nAU`BQ"
                     },
                     "start_location" : {
                        "lat" : 37.2477631,
                        "lng" : 42.4620711
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "44 m",
                        "value" : 44
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 37.1558892,
                        "lng" : 42.5692691
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eSilopi Habur Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD430\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE90\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y~waF_fybGIUCKAOAQ@Y"
                     },
                     "start_location" : {
                        "lat" : 37.1558055,
                        "lng" : 42.5688035
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1251
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 918
                     },
                     "end_location" : {
                        "lat" : 37.1448264,
                        "lng" : 42.5692653
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSilopi Habur Yolu\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD430\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE90\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Iraq\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "i_xaF}hybGj@OdCg@lB_@|@MxAK`CLbCRnHl@xCTvCu@f@]j@UZE`@Al@?~Hx@bHr@n@Fn@F"
                     },
                     "start_location" : {
                        "lat" : 37.1558892,
                        "lng" : 42.5692691
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1254
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 928
                     },
                     "end_location" : {
                        "lat" : 37.1382273,
                        "lng" : 42.5759524
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ezuaF}hybGtOxApALZDTAPCTKJOBEFMDYB]DcEDyE?E?QDYLQNG`@Cf@BzAF^@^AZCZGZKXQTUP[L[F_@Fw@Cw@@kCHoCVcBb@yBFWFUFKJKPM"
                     },
                     "start_location" : {
                        "lat" : 37.1448264,
                        "lng" : 42.5692653
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 1951
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1465
                     },
                     "end_location" : {
                        "lat" : 37.1403369,
                        "lng" : 42.59755579999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCd Îbrahim Xelîl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}ptaFurzbGJ}HAiIBoH@aIHuOAkGCeEKmDASKqBMoBQyB[mCOiAG]Ge@O}@UuA[iB}@{E_DeRc@eC"
                     },
                     "start_location" : {
                        "lat" : 37.1382273,
                        "lng" : 42.5759524
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1676
                     },
                     "duration" : {
                        "text" : "21 mins",
                        "value" : 1237
                     },
                     "end_location" : {
                        "lat" : 37.1419431,
                        "lng" : 42.616135
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eCd Îbrahim Xelîl\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "c~taFwy~bGs@_EuBiLmAyHc@iDIw@O}AOqCQcDMsDEuBAs@EiD?iC?q@BmD@a@?GDeHf@g\\"
                     },
                     "start_location" : {
                        "lat" : 37.1403369,
                        "lng" : 42.59755579999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18 m",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 37.1420416,
                        "lng" : 42.6162927
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003e\u003cspan dir=\"rtl\"\u003eHighway 2\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "chuaF{mbcGEACGIS"
                     },
                     "start_location" : {
                        "lat" : 37.1419431,
                        "lng" : 42.616135
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.3 km",
                        "value" : 5313
                     },
                     "duration" : {
                        "text" : "1 hour 6 mins",
                        "value" : 3977
                     },
                     "end_location" : {
                        "lat" : 37.1381727,
                        "lng" : 42.6755394
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eHighway 2\u003c/span\u003e‎\u003c/b\u003e",
                     "polyline" : {
                        "points" : "whuaFynbcGCi@Ck@NcHB_F?{A@mA@gB@{A?IBgEByDBeB?q@@kBB{E?YD}D@uB@mB@uB@eB@QDcC@_A@}ABsBBcCBgF@iB@UBmB?[B{A@e@@uA@c@?cA?qA@yABwA?{@BqC@eG@}ABmF@kCDqGB{BDaF?G@{A?U@qC@iD?_@@}@@oBBwB?KBsB@gB@cA@O@wADuE@i@?gA@q@?{AB}AFoG@E@eH?s@ByEBiBFcI@_@B}DD{DBiDByD?c@AmAHwEBmB@o@BgAPoCB]Fk@TqBL}@TwALu@@IH]|AiGfCoKtAyFt@mDHc@DOBIViA?C@A@A@ADA"
                     },
                     "start_location" : {
                        "lat" : 37.1420416,
                        "lng" : 42.6162927
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 236
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 37.1371787,
                        "lng" : 42.6778643
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eCd Îbrahim Xelîl\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qptaFcancGhA}E@IPu@@GNYPc@d@aA\\i@"
                     },
                     "start_location" : {
                        "lat" : 37.1381727,
                        "lng" : 42.6755394
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 364
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 318
                     },
                     "end_location" : {
                        "lat" : 37.1341835,
                        "lng" : 42.6775238
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "kjtaFsoncGBF@FDDBDDDDBFDF@HAD?BADABAFEFGDGBG@E@G@G@EXLPF@@b@N\\Lh@Jd@FJ@XBt@BT?l@A`@AD?@?f@CNAD?H@D@F@JF"
                     },
                     "start_location" : {
                        "lat" : 37.1371787,
                        "lng" : 42.6778643
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.2 km",
                        "value" : 6166
                     },
                     "duration" : {
                        "text" : "1 hour 25 mins",
                        "value" : 5086
                     },
                     "end_location" : {
                        "lat" : 37.0825916,
                        "lng" : 42.6582106
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eDuhok ↔ Zakho\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 2\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Route 2\u003c/div\u003e",
                     "polyline" : {
                        "points" : "swsaFomncGRA\\AjCAxFBjDB|B@N?`DBn@Ah@E^C`@Er@Kn@Ov@U`@K`Be@bAYb@Mb@MXItBm@v@Kf@Er@Ej@A^?P?\\@`@Br@H`@FZF`@Jp@P`@Nd@R`Ab@l@VxAp@XL`@N`@N`@LNDD@XDRD\\Fp@Fr@B\\@`@?`AAxAAj@A|@?N@\\@d@@v@FJ?r@H|AVNBh@Lv@RxBr@fHzBx@XfA\\t@VHBv@XxAf@bGrBj@Rn@RjExAr@VTHVN`@Tl@d@t@t@z@z@PNhAfA^\\\\VZVVNDDl@`@h@XJFt@`@f@Vf@RrAj@`A`@JDTJpBx@xCnA`Bp@^PtAj@~B`A^PXNb@Xj@b@ZZDDXZJJbApAf@n@|@lAf@t@j@p@`@f@`@b@`@\\n@d@p@`@~@d@`Ah@fAf@nAl@lAn@rBbAvAr@tBbA|@d@DB~CzArBdArAn@VL`@RJF|Av@z@`@rAp@h@Vf@TbB|@jCpAl@X|@b@l@TbAb@TJRHLDfA^\\J~@ZbB`@bAXvBd@B?dDh@jD`@zAPp@FxBRXBjEj@H@"
                     },
                     "start_location" : {
                        "lat" : 37.1341835,
                        "lng" : 42.6775238
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 106
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 37.0816396,
                        "lng" : 42.6582176
                     },
                     "html_instructions" : "Take the exit on the \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "euiaFytjcGPCT?bABpAA"
                     },
                     "start_location" : {
                        "lat" : 37.0825916,
                        "lng" : 42.6582106
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 144
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 110
                     },
                     "end_location" : {
                        "lat" : 37.0803583,
                        "lng" : 42.65821100000001
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "goiaF{tjcG\\?f@?v@A|AEN?F?B@FF"
                     },
                     "start_location" : {
                        "lat" : 37.0816396,
                        "lng" : 42.6582176
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 155
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 148
                     },
                     "end_location" : {
                        "lat" : 37.0801734,
                        "lng" : 42.6566876
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "ggiaFytjcG@B?B?@@@?B@@@@@@?@@@@@@@B@D@@?@?@?@?B?@?B?@AEnA?JCxA@xA"
                     },
                     "start_location" : {
                        "lat" : 37.0803583,
                        "lng" : 42.65821100000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2164
                     },
                     "duration" : {
                        "text" : "32 mins",
                        "value" : 1922
                     },
                     "end_location" : {
                        "lat" : 37.0650978,
                        "lng" : 42.6460374
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "afiaFikjcGBB@@?@BB@B@@?@?@?@?@@@?@?@?@AB?Bl@v@X^NXXj@Xt@HTFp@b@nA^bAt@pA^dAZbAVh@DHFNNPTRRNRLTNXLTJXFZH`@JXH`@N`@RLLDDTT\\h@t@jAh@bAVZXVXRXPl@\\t@`@VR`@`@d@l@X`@d@t@DHt@tAh@bAJLjAzApA|APTb@h@ZZ^`@p@h@b@ZRNb@Vz@b@`A`@rA\\v@RrA\\lD~@dAPJ@fAHz@Cz@CrAKVAbBKdAOVMRQJMBEH]R{ADMBEDE@AJADAD@@?FBNP"
                     },
                     "start_location" : {
                        "lat" : 37.0801734,
                        "lng" : 42.6566876
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.3 km",
                        "value" : 8322
                     },
                     "duration" : {
                        "text" : "1 hour 34 mins",
                        "value" : 5638
                     },
                     "end_location" : {
                        "lat" : 36.9924283,
                        "lng" : 42.6418457
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{gfaFwhhcGA~@LhAZhADLLLZPdAL|HT|@JhCbAp@VrA\\`BXVBhCR~DZZ@nBFpECx@?tAEzAKjAUz@SfAO|BMlBIh@K`Dk@z@Aj@Jj@RnAz@vAj@x@Rx@BrAQhBu@rCkAvNqGrEmBzA]xBDn@?n@Mf@[dAm@v@KF?nBIrEPp@FpCRvOpBH@l@Dj@B~ADbEN`D\\rLbAtALf@DzGf@zFd@nAPpALh@FrCRbPvAN?^B`Jz@tAFbPxAzDZ~Hp@|Hn@lD^vPrAfOnAlEd@dL|@l_@fDvDVvF\\l@?|@DrAAtAGbBGxBYvASzAUlAWfBk@j@QjAc@zAm@v@c@jBeA"
                     },
                     "start_location" : {
                        "lat" : 37.0650978,
                        "lng" : 42.6460374
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "22 m",
                        "value" : 22
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 36.9924708,
                        "lng" : 42.642092
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uax`FqngcGGo@"
                     },
                     "start_location" : {
                        "lat" : 36.9924283,
                        "lng" : 42.6418457
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "10.8 km",
                        "value" : 10822
                     },
                     "duration" : {
                        "text" : "2 hours 10 mins",
                        "value" : 7774
                     },
                     "end_location" : {
                        "lat" : 36.9445349,
                        "lng" : 42.7376241
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}ax`FapgcGb@WjUoQ|A_ADArA_AjAo@lAaAr@_@hAw@n@g@x@m@dA{@r@o@RQl@m@r@w@z@i@p@_@`@SdBo@vBgAfDyBz@g@lAw@zA}@NKhBiArAy@jAs@z@k@`BiA|AgAzAcAhBqAzAkA|AkAfAw@j@a@TQ`As@|@m@t@i@pAw@`BgAlBsAnDy@XCPERQXO|DeCh@c@|BsAdCoBzBwB`BeBlBaCh@o@xBiDvBiEjBmEj@sApA}DbAoDr@_D`@iCp@wEVoCX_FRiFNyIN{JNeHDeBPeIRwLBu@X{Ld@gN@QXuK\\yML_ELsENkFd@qP^gOXaKHcD^mK`@cJV}CHg@|@cGr@iDz@}CvBeGp@wAn@eAxAgCBEhAgBjAwBfAiBdAiBdAiB|@{AhAqBhBcDfB{C~C{G|AkDhAwC|@mC|AgFtAkEV_AdBaG`@_BRq@x@qChBcGdB{Fp@}CvBuFnAwCt@sAz@yAdAaB|DkEbE{DpDqDhBcBf@o@\\i@FWBSAKIS"
                     },
                     "start_location" : {
                        "lat" : 36.9924708,
                        "lng" : 42.642092
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "7.8 km",
                        "value" : 7805
                     },
                     "duration" : {
                        "text" : "1 hour 34 mins",
                        "value" : 5629
                     },
                     "end_location" : {
                        "lat" : 36.8985384,
                        "lng" : 42.8028235
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ivn`FcezcGx@w@hHyGhAeAvAsAjAgA|DaEvCwC~CuCpFgFNOJKdFyEfByBpBwBlAuANQ@AvAqBjBsCz@sAnBqDlAkCLYbBcD~AoDFMXo@`AwBvAwCfAmC`ByDtB}Ev@iBnCsGhGoNL[jAuCbH}P\\q@r@aBrAoDnAcD`AgCv@sB\\_AFM`AmBhA{BpAkC`AqBz@aC~AqD?A|BiFjBiEfA{Cv@kCl@_B|@oBJUfAaC`AwBlAiCjAeCv@iAbAmCh@uAf@gA~@{Ad@kAt@_Bx@uBnBkCvAmBfC_DhC}CjCkDrAiB~AqBdAoAtCaC^i@|CwDdAuAbDiEbC_DlBgCxDaF`@g@rHiJ\\i@lAyAvDiEdAkAbFwFPQvFcGfEqE"
                     },
                     "start_location" : {
                        "lat" : 36.9445349,
                        "lng" : 42.7376241
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "33 m",
                        "value" : 33
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 36.89874,
                        "lng" : 42.8031016
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ve`Fs|fdGg@w@"
                     },
                     "start_location" : {
                        "lat" : 36.8985384,
                        "lng" : 42.8028235
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2817
                     },
                     "duration" : {
                        "text" : "33 mins",
                        "value" : 1982
                     },
                     "end_location" : {
                        "lat" : 36.8794404,
                        "lng" : 42.8236077
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cxe`Fk~fdGJMf@m@|A}AnBuBPSjAqA\\_@bAgAvCgDfCmCDEjCyChAcAFGnAmA`BcBtA}AzBcC~AeBVYHKl@w@hCqCDEfBmBbBkB`AiA|BaCdAgA`AaAPSnAsA\\_@lAuA@AjAoAX]vAaBBCjAkA|BqBTSvC}CdBmB`@c@`AcAHKRSFI|@gADGdAoAb@i@~@mALO~@iAbCkCvD_EBC"
                     },
                     "start_location" : {
                        "lat" : 36.89874,
                        "lng" : 42.8031016
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 36.8792663,
                        "lng" : 42.8233627
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "o_b`Fq~jdG`@p@"
                     },
                     "start_location" : {
                        "lat" : 36.8794404,
                        "lng" : 42.8236077
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1238
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 887
                     },
                     "end_location" : {
                        "lat" : 36.8708242,
                        "lng" : 42.8324307
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m~a`F_}jdGzI{Jh@m@~DaEvFeGtAwAhJiKpEcFrDeETW"
                     },
                     "start_location" : {
                        "lat" : 36.8792663,
                        "lng" : 42.8233627
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "23 m",
                        "value" : 23
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 36.8709007,
                        "lng" : 42.8326678
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "si``FuuldGOo@"
                     },
                     "start_location" : {
                        "lat" : 36.8708242,
                        "lng" : 42.8324307
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.7 km",
                        "value" : 2665
                     },
                     "duration" : {
                        "text" : "33 mins",
                        "value" : 1965
                     },
                     "end_location" : {
                        "lat" : 36.8601167,
                        "lng" : 42.858217
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cj``FewldGNUdAmATW|@gAX]Zc@JQJMr@o@rAcAn@g@XW`CmCnByBf@i@zCoDRSbAoAHM`@q@f@u@FMz@_Bj@wARu@Li@DQPwAJ_AFu@NgBDa@Fw@@GLoB@KLsBBOHkAJgA@GRcBD[`@qCBMR}A`@}CLoAXiCNyA@Id@}DX}CPcBRgBZeC@OHk@^wBRaANy@j@oC^yAb@iAp@cBFQ\\y@LYDIf@uALYnAeDBKFMd@{APg@"
                     },
                     "start_location" : {
                        "lat" : 36.8709007,
                        "lng" : 42.8326678
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "26 m",
                        "value" : 26
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 36.8599028,
                        "lng" : 42.85808670000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wf~_F{vqdGj@X"
                     },
                     "start_location" : {
                        "lat" : 36.8601167,
                        "lng" : 42.858217
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 749
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 548
                     },
                     "end_location" : {
                        "lat" : 36.8566102,
                        "lng" : 42.8654195
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ke~_FavqdGj@yAvDiKfAyCHUHUBI`BqERi@~BsGPm@Tq@R{@Pw@Ha@"
                     },
                     "start_location" : {
                        "lat" : 36.8599028,
                        "lng" : 42.85808670000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "24 m",
                        "value" : 24
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 36.8566623,
                        "lng" : 42.8656691
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yp}_F{csdGEGAGACAE?G@O"
                     },
                     "start_location" : {
                        "lat" : 36.8566102,
                        "lng" : 42.8654195
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "7 m",
                        "value" : 7
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 36.8567215,
                        "lng" : 42.8656897
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cq}_FmesdGKC"
                     },
                     "start_location" : {
                        "lat" : 36.8566623,
                        "lng" : 42.8656691
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 126
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 93
                     },
                     "end_location" : {
                        "lat" : 36.8565528,
                        "lng" : 42.8670938
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oq}_FqesdGFy@PgCFuA"
                     },
                     "start_location" : {
                        "lat" : 36.8567215,
                        "lng" : 42.8656897
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "14 m",
                        "value" : 14
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 36.8566432,
                        "lng" : 42.8671963
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mp}_FinsdGQU"
                     },
                     "start_location" : {
                        "lat" : 36.8565528,
                        "lng" : 42.8670938
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "14 m",
                        "value" : 14
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 36.8565239,
                        "lng" : 42.8672548
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_q}_F_osdGVI"
                     },
                     "start_location" : {
                        "lat" : 36.8566432,
                        "lng" : 42.8671963
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 1979
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1425
                     },
                     "end_location" : {
                        "lat" : 36.854229,
                        "lng" : 42.8892851
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gp}_FiosdGf@wHh@gJFmAVkFHgBXqEDw@TyE?ANwDLuDPqFl@qMJ_Ch@uKb@gM@_@NuEBu@@WBoAFkA@WLcAH]F]Ha@Hw@Dm@"
                     },
                     "start_location" : {
                        "lat" : 36.8565239,
                        "lng" : 42.8672548
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 36.8541401,
                        "lng" : 42.8892258
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}a}_FaywdGPJ"
                     },
                     "start_location" : {
                        "lat" : 36.854229,
                        "lng" : 42.8892851
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "41.7 km",
                        "value" : 41729
                     },
                     "duration" : {
                        "text" : "8 hours 18 mins",
                        "value" : 29884
                     },
                     "end_location" : {
                        "lat" : 36.5475014,
                        "lng" : 43.0178145
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ka}_FuxwdGTiDDmAReFb@wLB{@T}ENuDd@_M^gJBe@ReG\\sHTcHfAq\\LsDBkADuATaCZ_B\\}@l@}Ax@kAnAaAf@]b@WTKbAa@fCaAjA[lAYhASv@BnCD|AL~AAt@AhAKfBQv@WHCVGb@KzBk@LE`@KtA]b@Kr@QvCq@~Cq@hBe@hBe@`@MTE|Dy@VGhDk@vA]NEz@SpCe@z@MrAMhAI|BYjD]zD[XE~CUxHa@DAtBMnJk@xE[|DU`AI`BKtLu@vIi@r@EjBKdO}@~Ko@`Lm@t@GtBOpE_@jHm@jE]bAKfFa@dHo@rE_@nOoAxCWrMgArAKbAIJAdDYzCYhDYf@CvDYlBQnFa@rIq@tFe@xCWtMyAdDa@dAObBWdAMtHaAdGy@bEi@~Di@hEm@|Eo@nEm@pEk@~ASzHiAhGs@dG{@rEm@`Eg@jEo@~BWn@KzB[`H_ApB[x@KRCjDa@xBYj@IVErCa@NCrAQHC|BYx@KxAQ\\GB?VEdFo@^Et@Mz@K`AOnAQp@Kl@Kt@Kb@GnBY`AO|@QNC\\GzGyAlA]\\I^KRG~C}@jBc@pEgAVInBg@pNuDxA_@~OeElIwB|MkDlIwBjEiApCo@hQqElCs@zBk@tHqBZKhEiAzIcCjNmDxEaBpD_Bb@[xDcC|AgAj@_@xEmEtBmB~AgC~@qB|@{BTk@hB}Gt@_EDiAF]U_@VuCN}H?wDAOEaCIcCg@mJCiA@}ADwABy@LiAL}@Ji@d@oBPq@Vu@Tm@r@}AR_@p@uAb@y@jA}Br@uAfA{BBEvAqCz@cB^w@P]fAuBRc@p@uA|@gBz@cBrB{DHQdCaFNY`@w@tAoCbAsBn@qAJUXu@LWVi@f@uAZaAHWNm@d@qBLw@NmAHi@JiABo@Dg@BqA?iA@[A}AEmA?EGmAQuCIsAAS]}ECi@UyCMaCGuBAuA@}ABmAB_@JsAFo@Jo@VmA^wAVs@La@Tk@JSHQ`@u@|@sAf@o@h@s@~@aA|@}@NQ^_@|@_Ap@o@n@o@l@m@n@m@`A}@jAkAj@k@r@s@dAeAx@{@@Ax@y@h@i@|@_A~A{Ax@y@`@_@RYPQt@w@t@_Ab@o@d@u@`@y@Zu@Pe@^kAVaARaALy@Fi@Fq@Bg@Dw@By@@m@?g@Aw@A{@Aq@Cy@Ao@Ai@IcCGuBGgBEsBKmDEkBAw@AqA@mABw@Bk@Bi@H_AJcATeBPgAPiATqA@KZoBN_A^wBLy@`@gCRmAZcB?CNy@P{@T}@Ru@DONa@Tm@`@{@Te@Zg@b@o@V[X[RURSXWh@a@FE^Wx@c@b@Ur@[bAa@f@Ql@SpAe@fBm@rBs@~Ak@|@]b@OtAe@~Ak@n@Ud@OnAe@TI`A]l@Wb@Ol@SFCp@Uv@S`AU~@G`AI|@?bADbAFRDx@TdAT`@LXLZNb@Rd@X`Ap@TRz@p@t@n@x@l@n@`@ZRRJd@TNFXJXH\\HtAXp@HlBPzBPrAFlBJpBJZBz@DtAFt@Hn@JXDn@Nb@Ln@Rr@V\\Nj@TtAn@|@^hChAb@T|Ap@|EnBl@XhAf@|Ar@v@^pAj@|@b@fA`@\\NfAZb@LXF\\F^F`@Fr@FL@P?R?n@?pACTAtBQ`AG~LiAvFi@xJ}@nCUvBQhE_@rCWdCU~BSpBIlA@bAHZBVDZDZHXHr@RPHVLJFRH`Ah@tA~@l@d@p@f@fBnAv@j@|BdBtB|A`BnAnCtB`BlAnA`AtAfAb@^jA|@pBxAr@h@z@l@rA~@rAbAx@n@pA|@~@l@jAj@`A^r@VjAVJB^FTBn@FnAFR@^?V?H?N?f@Cj@EFA\\EtAS|@OvGoA\\GfB]pEw@tB_@jEw@h@MhASrAWlASz@MtBYd@Ez@Gn@CvDUdDUvFQ`EAfE@b@?tDHj@DvAJpG\\nFXrG\\lFX`FV`AFxERvG^r@BpDPzEV`GXhERlADzFX\\BxFXD@`CL|CRvAFlDPrGXv@DvDRxAHb@Bd@BzEVD?hETnBJpFTzETj@BfMp@xLn@lDL|AFzDTfAFrLl@bBJb@B~EVbKb@rETzCNdER|DRpBLv@DF@xEX`CJzAHnDF~DBxDBj@?rBArBA~@AL?b@A`BGbAET?pEYHAhEc@bEe@DA|C_@PElCg@xG{A~Bs@|Bs@pDmAdBm@fDqAdBs@bF{BfGcDdEcCdFgDf@[xBuAjCcBrGaEdFgDdDsBx@i@`EiCROlEqCvGeEpFkDf@Y|EyC`BgAj@i@"
                     },
                     "start_location" : {
                        "lat" : 36.8541401,
                        "lng" : 42.8892258
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "89 m",
                        "value" : 89
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 36.5467628,
                        "lng" : 43.0181519
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "{da~Ei|peGB?@A@?B?@?@AJENILGPKNIHGFCHABAFA@AB?B?@?B@"
                     },
                     "start_location" : {
                        "lat" : 36.5475014,
                        "lng" : 43.0178145
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "16.8 km",
                        "value" : 16751
                     },
                     "duration" : {
                        "text" : "3 hours 21 mins",
                        "value" : 12037
                     },
                     "end_location" : {
                        "lat" : 36.417671,
                        "lng" : 43.1078434
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "g`a~Em~peGhAgAz@q@f@[tA}@bFcDzFqDjHqERMhBiApJeGtCmBVO|E_DpBoAtD{BrIoFpG}D|AcAnD{BnBqAzCmBtAy@JGxB}AzE{ChF}Cr@_@r@YtGqCdG{BHE`Bw@fGqCtGwCdD_Br@]hH}CDCvFkCl@W~G}CzEuBxDeB`Bu@FEhHcDhD}A`DyAdHeDtAm@dD{AvFkCrEwBd@UjAg@XOjGsC~G_DdCeAn@s@DEfHiDhLiF`@QbCgA^QfHaDnGyCxBaAz@_@pAm@LE~G}CzFmClFcClAi@`Aa@t@[j@WFCp@[jAk@z@a@VM`CiAd@U~DuBvEkC|DiCdBgAZWNKpDqCnAeA|CiCZWrEsExFcG`F{FJOhEaGt@cA|BoDfAcB`BgCv@mALQ~AeC~GmK|CwEhBuCzBkDtDcGXg@tEmHHMLStBgDfAcBVa@rK{PvA{BzEuHp@cA^k@~@yA`B_CjAcB`BsBr@}@tAyAzBcCfGoGHGJM|@}@b@e@dBgB~BeC@?rCyChAkAnCwCrAuAvByB~AcB`DuCnGwE~AeAXQn@c@|A}@fDeBlD_BvAo@DCxEwBhDyAlB{@nB}@t@Y~B_AhCeApBy@xDcBz@_@^QnEqBzAm@p@WrD}A|E}AzDeAv@O|@QxB[JC~C_@`@GfBWp@_@~Dg@`AMtHu@`Hs@lGm@rEa@tAMjDa@LCfBWFA`GcAvB_@z@ODAfFsAzB]XE"
                     },
                     "start_location" : {
                        "lat" : 36.5467628,
                        "lng" : 43.0181519
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 36.417668,
                        "lng" : 43.1079878
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eRoute 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "myg}E_obfG?]"
                     },
                     "start_location" : {
                        "lat" : 36.417671,
                        "lng" : 43.1078434
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.3 km",
                        "value" : 8342
                     },
                     "duration" : {
                        "text" : "1 hour 41 mins",
                        "value" : 6066
                     },
                     "end_location" : {
                        "lat" : 36.3550831,
                        "lng" : 43.1511389
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "myg}E}obfGzBq@tBq@zCaAhE_BlEaBxBy@l@UzAi@pAg@rDuAjE}A`A]pEaBxBu@xB{@zB{@ZKd@S~EiBjFmBrE_B~EiBf@Q~B}@zAi@bKwD|GeCvCeA~FwBfC_A~Ak@v@YlB_A~BuA~@u@JIRODCbCwBxGoG@AtMeMbBcB^_@xGyGxAaBJKLKPQDADCBAjAqB`AgB\\k@^q@j@oAzEqLjCeGvBoEnBcEfEaJ\\s@t@{AR_@`CeFj@iAfB}DjDeHl@_ARULMVMb@WZKXE~@CpK?fB?jABT@hA?P?f@?h@@z@FzH|@rJhAh@FlALh@D`@B`@C\\It@_@v@m@dQoNtDeDrB{AjEcD~@s@dDiCTQb@]vD}CjEeD`CuBhC{BhAaAlBeB"
                     },
                     "start_location" : {
                        "lat" : 36.417668,
                        "lng" : 43.1079878
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 313
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 234
                     },
                     "end_location" : {
                        "lat" : 36.3530556,
                        "lng" : 43.15352499999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eجسر السويس\u003c/span\u003e‎\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gr{|Es}jfG`A}@PStAsAVW`@m@Zc@t@gBj@o@p@s@"
                     },
                     "start_location" : {
                        "lat" : 36.3550831,
                        "lng" : 43.1511389
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "45 m",
                        "value" : 45
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 36.3527408,
                        "lng" : 43.1538435
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eAl-Suez intersection\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "se{|EolkfGTUh@i@"
                     },
                     "start_location" : {
                        "lat" : 36.3530556,
                        "lng" : 43.15352499999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.7 km",
                        "value" : 2732
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2041
                     },
                     "end_location" : {
                        "lat" : 36.3343614,
                        "lng" : 43.1723911
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eشارع السويس\u003c/span\u003e‎\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sc{|EonkfGX[rNaOdCmCl@o@b@e@TYNOp@g@HEr@WrBw@RG^Mj@Qv@_@XOj@w@j@}@DKDE`@sAPw@Pq@XeA^o@jAmAp@m@`@a@FEdC}AXQxA}@hDqCh@e@zBmBNMdGaF|@w@XUZUXWtEsDp@e@v@]zAs@FAFEzBcAxAmAdA_AzAgAj@a@dA[x@w@^[NUDANo@?IFk@LeEFeCJq@"
                     },
                     "start_location" : {
                        "lat" : 36.3527408,
                        "lng" : 43.1538435
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "19 m",
                        "value" : 19
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 36.3341988,
                        "lng" : 43.1723288
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wpw|EmbofG^J"
                     },
                     "start_location" : {
                        "lat" : 36.3343614,
                        "lng" : 43.1723911
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 657
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 521
                     },
                     "end_location" : {
                        "lat" : 36.3312104,
                        "lng" : 43.1786405
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wow|EabofGFQ|@mCJWJW\\cAfAiDDOb@{Ab@eANa@\\w@RcABI|AsDbAuBn@oAj@{A"
                     },
                     "start_location" : {
                        "lat" : 36.3341988,
                        "lng" : 43.1723288
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "33 m",
                        "value" : 33
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 36.3310009,
                        "lng" : 43.1783768
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a}v|EoipfGJJ\\f@"
                     },
                     "start_location" : {
                        "lat" : 36.3312104,
                        "lng" : 43.1786405
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "78 m",
                        "value" : 78
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 36.3303566,
                        "lng" : 43.1787259
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w{v|E{gpfGz@_@bAe@"
                     },
                     "start_location" : {
                        "lat" : 36.3310009,
                        "lng" : 43.1783768
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 36.3304,
                        "lng" : 43.1788369
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wwv|EajpfGGU"
                     },
                     "start_location" : {
                        "lat" : 36.3303566,
                        "lng" : 43.1787259
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "84 m",
                        "value" : 84
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 36.3299594,
                        "lng" : 43.179603
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_xv|EwjpfGvAwC"
                     },
                     "start_location" : {
                        "lat" : 36.3304,
                        "lng" : 43.1788369
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "62 m",
                        "value" : 62
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 36.3294865,
                        "lng" : 43.1792342
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "guv|EoopfGz@l@`@Z"
                     },
                     "start_location" : {
                        "lat" : 36.3299594,
                        "lng" : 43.179603
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 194
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 141
                     },
                     "end_location" : {
                        "lat" : 36.328387,
                        "lng" : 43.1808356
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "irv|EempfGD@`BcB`AuBp@cB?E"
                     },
                     "start_location" : {
                        "lat" : 36.3294865,
                        "lng" : 43.1792342
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 115
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 77
                     },
                     "end_location" : {
                        "lat" : 36.3274796,
                        "lng" : 43.1802279
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mkv|EgwpfGpAx@bB~@"
                     },
                     "start_location" : {
                        "lat" : 36.328387,
                        "lng" : 43.1808356
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.1 km",
                        "value" : 5085
                     },
                     "duration" : {
                        "text" : "1 hour 3 mins",
                        "value" : 3773
                     },
                     "end_location" : {
                        "lat" : 36.2974221,
                        "lng" : 43.21541879999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wev|EmspfGXy@f@oAj@sADKXo@l@iALQXi@n@aAn@_An@{@n@{@hAqA\\YvBoBjB{AlC{Bp@g@pAeAXUdCsB~CgCf@_@nC_CnB_B`Au@`Aw@jHaGvBeBr@m@dAkAZ_@DE^g@`@u@Fu@Bm@Vq@\\oADKb@gAHYLw@LeA@Gb@{Bh@uCl@eDx@cEr@qDz@yEj@sD`AoFd@sCJYbBwE|AqIFW\\mB`BoJbA}EDWFWBiCDoAVeAn@uBv@mBJUx@{AnAeBxAsAhBuANGlAi@XOt@]h@KdAUdAMn@IHAzDGrAChFIhJMrBExBGx@CTAn@A`KY~@C"
                     },
                     "start_location" : {
                        "lat" : 36.3274796,
                        "lng" : 43.1802279
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 186
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 146
                     },
                     "end_location" : {
                        "lat" : 36.2966573,
                        "lng" : 43.2169984
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ip|EkowfGCU?K?CBG@GFEFENG\\SLKJITWDEFIBEDI@E?A@KAIEOCM@K@SFQ@GBIDO"
                     },
                     "start_location" : {
                        "lat" : 36.2974221,
                        "lng" : 43.21541879999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11.0 km",
                        "value" : 11022
                     },
                     "duration" : {
                        "text" : "2 hours 16 mins",
                        "value" : 8171
                     },
                     "end_location" : {
                        "lat" : 36.2262772,
                        "lng" : 43.2980776
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "cep|EgywfGh@UTQPIRIh@g@PSHKp@c@j@Y?CHUR[PQd@g@XY|@eAZm@@CTe@L[t@kBN]r@_CDOJ_@Bc@De@DaBBo@Lw@Js@F]X{At@sDx@oDlAqE|AaFTi@Vs@z@{BRa@Zu@Xm@^y@Vg@r@qAl@cANYVa@DIX]`@i@bBeBd@e@h@g@nF_FnE{DfAaAfA_A`BoAzC_ChA{@x@w@~@{@^c@\\]LQt@}@^y@l@yA\\w@Xs@n@wAXo@Pa@^{@Te@|@sBHWDIZw@Na@vDwIZe@d@q@Zs@^kAXeAXu@fCcGBG|@aBv@wA^g@FKfBaD^q@~@wANOBCj@i@tAqAx@w@hLyK~@}@nB{Ab@]tA}@`@U`C}At@k@zDyCdE_EjDcDtBaBzAoAROpAmAV]vAiBBE~BqCjA}Ad@m@~@{@hBgBNM^]^c@jAsAhAqAHIn@q@\\]xAcBBE`ByABEpA}Al@s@h@q@t@qATe@fBqDbAsB^y@BGn@wAHQHQJWNY@EtA{Cn@qBBKVaAPw@V{@DIJUh@q@TWx@q@HG\\]R[JWBMBMFYRs@Nk@F]LWNYHIDGNQn@iAn@kAjA_B^m@P_@HWBEL_@L[FKxCkEpAeBLQNSDGvAsBpBkDNWnAeCvAyCN[P]BETc@rAkCXg@R_@`@s@\\g@dA}AfBiCZe@bBiCp@iANWP]d@y@xBuFN[PWJOBAHGLKLKJOJKjAkAXYpBoBXYjCuBJIz@o@\\YVSRKNGREPGfD_A@A~Bs@pC{@FCz@WfHsBl@S~@YjBk@rAc@r@QbFwArBk@VGtDeAXIp@Q|Am@lAe@xBy@VIJE`A[t@W|FkBJE|CwAFEl@e@FEj@i@rCmCl@k@zByB~@_AjAiANODEbBmBBEb@g@n@u@"
                     },
                     "start_location" : {
                        "lat" : 36.2966573,
                        "lng" : 43.2169984
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "75 m",
                        "value" : 75
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 36.2258068,
                        "lng" : 43.2974763
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gmb|E_tggG|AvB"
                     },
                     "start_location" : {
                        "lat" : 36.2262772,
                        "lng" : 43.2980776
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "67 m",
                        "value" : 67
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 47
                     },
                     "end_location" : {
                        "lat" : 36.2253845,
                        "lng" : 43.2980118
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ijb|EgpggGtAiB"
                     },
                     "start_location" : {
                        "lat" : 36.2258068,
                        "lng" : 43.2974763
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 132
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 93
                     },
                     "end_location" : {
                        "lat" : 36.2244979,
                        "lng" : 43.2970455
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sgb|EqsggGjAjATf@lAjA"
                     },
                     "start_location" : {
                        "lat" : 36.2253845,
                        "lng" : 43.2980118
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "59.7 km",
                        "value" : 59713
                     },
                     "duration" : {
                        "text" : "12 hours 3 mins",
                        "value" : 43404
                     },
                     "end_location" : {
                        "lat" : 35.8858015,
                        "lng" : 43.7817344
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cbb|EqmggGtD{Dh@k@t@y@dBgBhEoEhEmEtBwB`CoBlK{IDCzB{AtDiCPKz@k@rOoI`HqDdFoCpCaBFCbIwEpByAx@o@fDgCzCqC~EqEdCqCHKVYh@m@p@s@^c@fCkDlFkHtJ_P^m@h@}@FK~ByDhHoL~FyIPWdGsH`@i@\\a@`@g@jD_EhD}DrA_B|@}@n@g@jCsC~CgD|GiH|BgCjDyDtEuFhG{ItAwBbCiE`B_DpC}FxAcDl@{AfAmCrCqHz@}B`AwBnAqC~AkC`BeC~AqBt@}@pBqBlAeA^WnA_AjAw@pBkAvBiApGsC`FaChBu@fCsA~Aw@`BiAvBgBvBsAx@w@dA_AvBsBdAmA~BuCxBaDtAyBv@sAdBeDbE}It@cBhByDvIoQ|AuCfEkHlB}ChCyDpGyIzAiBxAgB`BqBnFkG`CyC|AwBxA}Bv@qAxAsCfA_CfAgCjAyCr@oB`AaDx@{Cn@qCj@mCpAkGn@qC@Ej@}B\\uA@Gr@cC`AsCfBkEbBwDtCkFzEuH`F}HjByCrCoErAkBxAiB`@e@xAcBfBgBxBsBxCgCfKaGnCuAjCaAhEsAdGcAhBo@fF}ArFiBtGmC~EeCfDqBpD_CtB}AxD}CpCmCrD{D`HoHfDsDpE{EhCsC|AcBxCqCjCyB~CcCtCmBnC}AnBeAdDcBhAc@lCcArFiBbNcEnEwAzBs@jC}@nBs@hBq@jBw@vDcBhCmAbBy@~Aw@nAs@vCaBjEiCdBkAfAs@|DqCfCmBxEuDbB{A~CuChH_HtCgDbBoBdE}ElFiGfBsBpGsHtDiEnFcGzF}FjH_H|CiCbIoGnGwEnBmArIoFlCkBnBmAvBuAbBcArEsCnD{BdCiBjBuAlCaCpBiBhCkCnA{Az@gAz@}@b@o@f@g@NUNWb@g@b@o@T[h@cAN]NYXi@r@oA`@s@T_@Xi@\\i@Zq@rAyCZq@|AuDpAwDdA}C`BaGhA_Fn@aD\\}A?An@}CH_@TmAvBoKHa@r@kDz@mEXyAFYz@mDl@uBv@}Bt@iB|@mBDI\\s@\\i@Zo@R[V_@hA_Bt@}@v@}@|@{@jAeAd@a@h@_@d@Yd@[~BwAnBqAhAs@zA_AlBkApAw@fAs@~@o@vAeAbAy@~@y@t@s@z@y@p@q@lDsDjBkBhBiBdCeCfEkEdEiEjAkAlAmAjBkB`BcB~@_A~@_AnEkEdAgA~@aAnCyCj@W^Yl@w@j@y@^o@b@w@b@}@j@uAj@{A^mAZoA\\{A`@eCHk@Js@JeAFaAFqCDgB@oB@aAB}BFqEBiCBgB?G@_AEmAFiBL}Bh@_GVwBz@yEn@_D`@aBj@oBr@wB`AgC|AaE~BoFlBmEnBuEvCiHvBgFvC_HhAkCnAsCp@_Bn@qAhA}B~AaDjBaD|A}BxA}BvAqBlB_ChCyCrByBzB_ChD}C|BiBjBwA~AeA`C}AxCcBdAk@fB}@pCuAtGwCzEaCdD_BbEkBxBeApBaAnCqAjAk@|BcAdBy@fAi@xAw@lAu@vBwAvB_B~AsAj@g@lAmAdBeBz@cAz@cA|@iAv@gArAyBxCgF|CqG`CqGdCcHt@oCjAmCrAsDtAsDxB_FpBaEpBsDxBuD`CsDxByCp@aA~BoCzA_BfB{BtCaDjBqBbBqBhDwDl@m@vAaBnB{BpAgBxBcCtDeF|D{FzAaCbBuCbBwCzAuC~DgIvCiGdBuDtEyJvBiElCwEvA{BlBmC~B}CzBkCpDyD|CsC`EcDnDmCrKwHpGsE`E_DbBoA^]nCgCzC_DnA}AfCiDxAyBtBkDlBuDR]h@iAdCcGlBaFjDiJjCaHhAyC|AgEnA_DfAyCzA}D|@aCDKr@iBzAeEdBeFnAyDf@_B`@oA`AgDnBiHhAeENo@Ry@bAcEhAgF~AgHpBaJjCoLNu@vAqG~BkK~AoHb@oBtA}F|B_KrBiI~BuIvB_IdAoDjBqGf@aBjBiGxAyExBoHzAeF~@{Ct@cClCeJz@qC@ElBiGnD{Lh@cBTs@FONc@~@yCXu@j@{Ab@kAN_@N_@\\{@dAcCdB}D`@y@v@}AZm@f@aABEZk@jBcDhCcEb@q@t@iAt@gAl@}@bB_CnAgB|BcD`CoDt@eArDkFhD_FNU~BiDbCiDvDoFjDeFBEzAuB`CkDxB}CvB_DpAqB~AqCv@yA`@{@x@eBbBeEbAyChAmDf@oBhAcFd@wCn@sDb@sDj@oF`AkHf@{G`@gEbAsKfAuJJcARwAz@uIn@uG^_D\\wDlAgLjA_Lz@uInA{LlCiVpCoXfByPx@aIt@mHh@kEh@}DdBwJX{A`B}HfAyEp@gCl@sBt@iCf@}A`AyCz@kCh@sAtBwFh@oA`@_AhB_ErCsGbBwDtByEt@eBtAeD~DcJTg@lAmC|AkDdCwFhEwJjCeGbAcC~BcF`JoSnAuCzEyKdCwFfAcCz@oBrAwCfEyJhAeCrCkGtBqEdBsD|HuOt@uAvAmCpCeFbCqElDuGzBeEvDcHLS`D}FjBkDlDuG`CoElLiTnEeItByDrEeI"
                     },
                     "start_location" : {
                        "lat" : 36.2244979,
                        "lng" : 43.2970455
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 km",
                        "value" : 3545
                     },
                     "duration" : {
                        "text" : "43 mins",
                        "value" : 2605
                     },
                     "end_location" : {
                        "lat" : 35.864802,
                        "lng" : 43.811086
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "g}_zEybfjGBSLUVk@j@eA~@cBj@gAd@{@JYHUFUBMJaA?C?C?A?A@C?CBKDKBEBEDEDCDCHA@?@?B?d@[LMRY`B{CvAeCJONOlCaFvCoFxG{Ll@gAnAyBrCcFvBoDhCcEtA{BbEeGpBsCbFaHpEkGjE_GLQ|B}CPUlGqIhCqDzDeF|DuFdHsJbEaG"
                     },
                     "start_location" : {
                        "lat" : 35.8858015,
                        "lng" : 43.7817344
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "75 m",
                        "value" : 75
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 35.8652557,
                        "lng" : 43.8116949
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_z{yEizkjG{AwB"
                     },
                     "start_location" : {
                        "lat" : 35.864802,
                        "lng" : 43.811086
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 km",
                        "value" : 4671
                     },
                     "duration" : {
                        "text" : "56 mins",
                        "value" : 3376
                     },
                     "end_location" : {
                        "lat" : 35.841243,
                        "lng" : 43.8541547
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{|{yEa~kjGvAsCrAoC`AyBlA{B`CkFbB{C?CfBmDfD{Gt@yA^q@j@gAlCeFnBoDbBkC~CmFlAsBrA_CPYbCeEbAmB`CqEp@qAdAgCjCsG^w@DMnBmEbBuD|@sBv@gBnDiIl@wA`@_Ab@cAtB{ExAiDDMtDyJl@}AxAaDrAgC~AuDnA{ChDmIRg@nB{E|AyDzA{D^}@`CcF~AeDDKtAkCfDuG@CnB_F"
                     },
                     "start_location" : {
                        "lat" : 35.8652557,
                        "lng" : 43.8116949
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 668
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 480
                     },
                     "end_location" : {
                        "lat" : 35.8361659,
                        "lng" : 43.8580847
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "wfwyEmgtjGvC_C~C}BrEgDz@m@tAeA`Au@xDuC\\UPKVGRA"
                     },
                     "start_location" : {
                        "lat" : 35.841243,
                        "lng" : 43.8541547
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "59.0 km",
                        "value" : 59018
                     },
                     "duration" : {
                        "text" : "11 hours 47 mins",
                        "value" : 42448
                     },
                     "end_location" : {
                        "lat" : 35.3852775,
                        "lng" : 44.1624528
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 80\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "agvyE_`ujG`@{@\\u@bCgFtAmCjCiFbCkEl@iAd@y@fByC~BsDbBiCtB_DjBkCHMvAuBhAyAlCkDnBaC~AoBjBaChBaC~AiBrGeIlDqEbIaK|CyD~BaC|@{@fCyBdAu@fBoAjCcB~BsAf@WrAs@vBgAzCeArFeBbGcBnDcAdGcBzEkAlIcCbD{@lGeBjFwA~Bo@zK}C`IwBfCs@v@UbFwA~IgC~GeBjBi@hDaA~EuA|F_BlFuAtDeAjEkApI{BxV}Gt@SbOyDtPwEhMgDz@UpMoDjL}CREvLaDpKqCjBg@zOmEfOaEhMkD|MoDfMkDjHoBhL}CtKsCdL_DrJeCjMqDpOaErIcChD{@dBc@jGeBfI_CtL{Cr@QfA[tDgAfBg@nF{AfD_AhF}AbIeCzImCdGkBnIkCnF_BvBo@xAc@hRkFlUoGbKqC|QeFjA[x[{I`GaBrF{ArSyFn@Q|RkFbHoBnF{ArBi@|Bq@bOeEtI_Ct@QzEsAp\\gJ^K~DiAfA[fQyEtA_@~MsDtA_@xLeDvGkBxIcC`VqGfJiCdCs@vGiBjCu@nD{@z@_@~@_@rB}@zAw@`@Up@a@rA_An@i@`@_@v@w@n@s@hByBzCyD|@gA`EgFlAyApCsD~C{DhG{HhFsGjEwFTYnCkD~EeGxLmO|EiGjEoFvAeBx@eAFKlAaBf@m@xBmCbEkFrF_HHKlFyG|HyJjEqF~AoBzAoBlEsFtBgC`@i@tAqB`BqBrOmRpFcHbEiFlEuFdD_EdD_EbBqBtJ_JnBaBvEwCpC_BdD}AtB{@~IsD~E}BhA_@tJkEhD{ApDaBfEkBdH_DdBw@dDyAtGaDxJ{FjAw@`HwEbGcFnFqEFGnGiFxE{DlEwDbEiDfEoDFEpGoFjAaA~PuNjHcG~AsABAfKoIfKaJjDoCFE|AmA`EyDhI{H|@iAl@s@rEwFbAwA~KcO`CeDdKwNn@w@rDaFxTmZ|[ec@d@o@bE{FhRkVdB}B`B_CfBeCbPqTbB}BbEsFpFoHjBgClBgCdPiTtFsHd@o@`PcTd@k@tKqMhAcAnAyAxLkN|L{MnN_PbRwSlAoA`CeClJkKjLoKhIsF`DcBn@]jZyOjDuBx@c@`WaN|MwG|JkFlHyD`L_GvDkBjOeIxGmDlMeHtLuGtGqEtIaGvDcDdCoBfQcOtBeB|LgKpA}@dSuPvAkA~JqIjB_BpVoSnCuBbCgBjAw@~A{@rDkBdCs@~DiAbFy@fGa@lEKrKQ|IIxFIdIStCInPMfHI`FIrJOhEIbBErJIjKQ`QO`CEbPUdJQ`AAb@AtHMhKK|CShBUL`A\\Xb@Jb@Bb@?`AMTEXMTMZUX_@f@?jBA|LKn@ArDGtDU^Eh@IxA[`Cc@`CeAhCkAdBqAbAu@`CaCfB}BZa@Tc@vD{GpEuIFM|CgGrFgK~CaG`AoB`AmBjEiIxAmCjGiLbF_J~@sAtFaI?ATUdH_I|J}IjB_BtIeIjDcDfQqOnGsGlBeBpBgBzBoBdQmOxLsLlIqH"
                     },
                     "start_location" : {
                        "lat" : 35.8361659,
                        "lng" : 43.8580847
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 395
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 287
                     },
                     "end_location" : {
                        "lat" : 35.384687,
                        "lng" : 44.1665143
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "_e~vEinplG~@iBf@qA^}AF]Jw@Ju@Bq@Ae@Aa@Cg@Ee@Q_BU}A"
                     },
                     "start_location" : {
                        "lat" : 35.3852775,
                        "lng" : 44.1624528
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1269
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 932
                     },
                     "end_location" : {
                        "lat" : 35.3896232,
                        "lng" : 44.1791271
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRoute 19\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ia~vEugqlGmAuE]yA_B_FM[aBaFcEgPy@gCiGmTy@qCy@aCa@{A"
                     },
                     "start_location" : {
                        "lat" : 35.384687,
                        "lng" : 44.1665143
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "9.7 km",
                        "value" : 9711
                     },
                     "duration" : {
                        "text" : "1 hour 57 mins",
                        "value" : 6999
                     },
                     "end_location" : {
                        "lat" : 35.3315355,
                        "lng" : 44.2487755
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "c`_wEqvslG`FeChX}MvBeAjB_Az@e@dD{AlGuCvGwDn@_@lD{AvAY|B[pNwBvAU~C_@vFs@tBY`C]`AOxIsAnCw@nAk@lA}@tB_BdCaBhDcDlKeJtC_CvIaH`ByA~DmDfLyK~K}MrEgHLQPUfJiLtLcPjDwEBCdDqEl[_c@tYs_@`FuGxBgCrA{A|@cA^s@tAsCDOVuAT}ALeBH{ALuBRaDH}@Hu@RiCnBuWbCaXbC{]`AiLP}BLmAXgBNw@d@yAT{@Zy@XeA\\eANk@Tu@Vs@FO`AsA|@_B[M"
                     },
                     "start_location" : {
                        "lat" : 35.3896232,
                        "lng" : 44.1791271
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.7 km",
                        "value" : 8655
                     },
                     "duration" : {
                        "text" : "1 hour 44 mins",
                        "value" : 6241
                     },
                     "end_location" : {
                        "lat" : 35.2880999,
                        "lng" : 44.3081885
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cusvE{iamGvBcBj@q@`@Y^Wv@k@t@g@p@Wh@Yh@Sd@Ql@S~@Q|@_@~AS`AKt@Gd@CVCr@Et@Cl@CpACZA`ACfA@nBIpEOdBAl@Et@EbAGl@U@?p@[~@c@~@c@v@WhAq@nAg@bBiAdBq@ZMjAg@x@e@z@c@t@a@|A_@tAYBA~KoCjHgBbTgEZGfGiAnB[dAQt@SnASx@a@l@Y~@k@n@w@fAsAh@eBt@mBTaBBSHsBByACqAAIKsFwAkZG_Bm@{OsAaVqAy\\qAa\\G{AE{@Cu@Au@Ag@@iA@w@?I?cAFaARyB`AsEvCqMdEkPf@iBRo@Ro@Ne@Po@JYd@y@Pe@V[~@wA^k@fAqA`BqAtBkAhHqCnAg@tBcAfOkHtEyBvD_BlAk@x@{@d@g@LMp@u@hA}@~B_ChAkBpDaFlFmHh@w@PULStCuDb@k@"
                     },
                     "start_location" : {
                        "lat" : 35.3315355,
                        "lng" : 44.2487755
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 387
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 287
                     },
                     "end_location" : {
                        "lat" : 35.2877626,
                        "lng" : 44.3112327
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sekvEe}lmGUWe@EWAOAGAe@IQSMWLw@PeAf@qAtAaDBErAmC"
                     },
                     "start_location" : {
                        "lat" : 35.2880999,
                        "lng" : 44.3081885
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 245
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 175
                     },
                     "end_location" : {
                        "lat" : 35.2862274,
                        "lng" : 44.309311
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ockvEepmmGVb@zAnBn@n@VTLLTTpA`C"
                     },
                     "start_location" : {
                        "lat" : 35.2877626,
                        "lng" : 44.3112327
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "12.5 km",
                        "value" : 12529
                     },
                     "duration" : {
                        "text" : "2 hours 31 mins",
                        "value" : 9050
                     },
                     "end_location" : {
                        "lat" : 35.2097331,
                        "lng" : 44.39263
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}yjvEedmmGdQiSnAaBtGsIdAaBr@wBVcCDoBFuBKmCAyECoACk@GgBCWAyAA{BAeAUuMY_ZYiLAMQ_DEi@?s@FeADg@Aq@Mq@Q_AYy@@gA\\s@r@w@dCoC|@aAbMeRfAaBZe@pDkC|CcBdB_AzNwHhFoC~LaGfQsIZMlOmHbD}A`D{Af@W`FqC`CeBfAy@HGvAeApAcARQvCmCr@o@dCgCHI`BuApBaB`CiBJIzAoAv@m@tAgAz@w@tEkEzA_AfBu@nA}@bCg@HCxAk@bBq@TK|Ae@REzAa@nA]ZIbDy@NErBe@`DkArBE`DkAdDm@`@SrAo@pDiChAcA`Ay@bBcC^k@nBcCZc@dBwBxB_CrB_CBCz@mALIn@e@rAw@xBuAzAi@lAc@lAm@tA]hFiBnGeChDqAnBa@z@M@?tAc@tAc@x@a@`BeA~@}@~AcAlAsBvD_EjEsGnE{GzCkEjD_FLQtEgHpAuBdCwBvAu@`Bi@hBYzAU|A[|AK|@WHCrB]xAKhAQ~@Eh@C~AOrA?|AEh@?~AAd@SfAq@p@o@t@}@x@kAn@aAf@cA^aAT}Af@{Bb@wCpBkMrBiMLu@~@cH"
                     },
                     "start_location" : {
                        "lat" : 35.2862274,
                        "lng" : 44.309311
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "9.6 km",
                        "value" : 9588
                     },
                     "duration" : {
                        "text" : "1 hour 55 mins",
                        "value" : 6913
                     },
                     "end_location" : {
                        "lat" : 35.1378594,
                        "lng" : 44.442409
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKirkuk St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 2\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 3\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "y{{uE}l}mGt@[vDuAx@Yx@]bBq@j@SlD_BnB_AjAm@p@a@lB_AbC{AtCiBz@o@vB_BnA_A|AkAhC}Bl@i@z@y@z@y@VUtC}CtB}Bt@{@jAmAb@c@vDkE`L_MlJiKvBaCvP}QfKgLrCyClAmAfBaBxDaDv@w@HELKXQtAcAbAs@v@i@jAw@vCiB|A_Al@_@v@a@\\SjCoAdAk@~BmAzBgAvC}AvAs@dAk@pAq@xAs@pAu@bBaAzBwA~C{BdD_ChCsBpAgAbDwCdBeBRQjAiAz@eAxCgDz@iAbC{C`@m@~BgDZe@vA{BzC_Fp@mA^e@`A_Bl@}@|@yAzCcFVe@tDeGp@mArDaGfA}Ax@cAd@k@@AvB}BfB}AROzAmApC_B`Ac@vBcAlD_AzCy@pC]bBK~AGl@Ah@ApBA`B@D?lB@xBAv@ClCObAM^Et@Op@MJC\\IVIb@KjCaAvD}AjGuBzEy@nAGlBCbBF`AHlAPpDh@hFbAzFfArCh@dDl@"
                     },
                     "start_location" : {
                        "lat" : 35.2097331,
                        "lng" : 44.39263
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 35.1378298,
                        "lng" : 44.4425721
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eKirkuk St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 2\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 3\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "szmuEadgnGD_@"
                     },
                     "start_location" : {
                        "lat" : 35.1378594,
                        "lng" : 44.442409
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "35.4 km",
                        "value" : 35449
                     },
                     "duration" : {
                        "text" : "7 hours 8 mins",
                        "value" : 25661
                     },
                     "end_location" : {
                        "lat" : 34.8693554,
                        "lng" : 44.6374626
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKirkuk St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 2\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 3\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mzmuEaegnGNB`Cb@d@Ht@HdAHlBHtA@pAGx@Ab@C`BMx@Gd@IpBg@fBe@hEgBzDqBtAw@bFiCnBeAhAm@rBgAdG}CbJyEpFuCfQ_J|HgEr@e@h@Yj@]nA}@bA}@~@_Ar@w@z@cA|@mAnAoB~@cBjAiC|@yBnA_DhBuEzEyLdBeENa@\\y@HSt@kB`GgOjDyIbAkCfBeEhBaEtAmCfAkB\\k@dA{A|@kAlAwAhBkBlAgAv@i@zB{AvAw@x@c@`Ac@nBw@~Ak@`Cs@bAYdAWrCq@fE}@hCm@tA[lB_@vCs@pBc@z@ShCq@|Aa@nBk@rIoCfC}@dDqAbBq@dAa@jD_BtBcA`By@hDgBtCaBdDoBrCeBzByAzCiBxDeCzDcCxG_EbAq@`JuFlBiA^SfCyAlDiBjCoA`Bu@h@WxBaAbBq@pAg@zEgBlCaAhCw@xDiAxCw@hEaAdAUnAYZElE}@nDi@xGgArEu@hAShGiAdDs@vA]fBc@|GkBVIhDgApGyBjFuB|CqAbD{AhFiCzEmCvD{BLIjDyB^Wl@a@hBqAxDsCjFeEjFmEtEoEdEkEnCwCtCiD`M{NhBwBnFkGdCyC~BoC~E{FxEeF|B}BnBmB`A_AdCyBbCuBhCsBrAcAPOxAgAtB_BhDaCzJgHzDuChE{C`CeBnE_DnEcDv@k@j@a@jCgBXSlEsC~A_AnBiAhFsCtDiBj@WjF_CtCiAfE_Bl@SxHiChEyAhC}@`A]xAg@vCcAxDsAhDiAnBs@pBq@vBu@zAg@pFkBxBu@lE{AvDqA`@OpAc@RGtAe@tBq@jBm@bDiAjEyAfDkAjEyApCcAtAg@pC_ATIhKmDfDkAvE_BrAe@xG}Bn@UvW_JtAg@p@UzBu@lBw@dAe@j@Y`@UfAq@JIn@c@~@w@lAiALMNO\\a@rAeB`AoAnBuClCyD`CiD`CiD~D_GlDcFnFyHnAgBl@_AbAwArAmB~BeD~BkD`B}BlC{DJO~BeDx@mA`CkDbCiDfA_Bf@s@JQZc@h@u@z@oAh@w@tCaEvE}GzDuFpAkBjGaJ~BkDbB_CpAkBfCsDhDaFl@w@^i@hD}E|@uAnAoBf@s@~AqBpAuAl@m@t@s@t@o@RQtAgA`@YtA}@xA_AzBuAnD{BlBkArD{BfC_BfC}AzCmBVO~BwApCgBhEkCtAy@JGnAw@r@e@TOnAu@pBoAbDsB|CkB|E}ChGuDzAaABAxEyClAu@fAq@v@c@JGh@]zA_AzBuAlCeBvBoA|@k@d@YjCaB~E{CrIkFrJcGfHmEvEuC~CoB`DoB|H_F~CmBnDwBbDsBdF_DFCd@[~BwAdEiCzA_Ab@WvA}@d@Y@AdDsBlBkAr@e@r@c@h@[z@g@xEyC|GeEnAw@fGsDbAo@`DoBtCmBtBsAhAk@rMiI|DyBrCkBnBuAt@g@~BqAn@]jFqCd@WTIjHyBvFwAdEuAhHgChBq@jEuAzAm@fEmBdDuBh@]xHoEvAcALGdDiClFkEfCoBzBcBfBgAt@c@dA{@ZWPG~AyAdA}@xBmBnFmEROv@e@pAiAzAcAXMFEv@Ub@IhCoBzBeBZUvN}KdBuAP_@hEmC"
                     },
                     "start_location" : {
                        "lat" : 35.1378298,
                        "lng" : 44.4425721
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "10.4 km",
                        "value" : 10413
                     },
                     "duration" : {
                        "text" : "2 hours 5 mins",
                        "value" : 7489
                     },
                     "end_location" : {
                        "lat" : 34.7844417,
                        "lng" : 44.66806640000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eKirkuk St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 2\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 3\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "olysEcgmoGFSFOLQLK~DyC`Ag@tAq@~NgIzEeCJGr@c@tC{AtIyE~GyDtJiFfCqApCwAdIsE|H_E`GaDlFyCnCwAtEaC`H{D|BgAfDqBdGeDhEwBnAu@xAy@|Aw@|A{@bOiIrBeAbB}@rBiArCwAtC}Az@k@`By@dB_ApXcOvPgJlDiBtAw@|Ay@nQmJrIyE`@UzCaBdBaAlS}KlHyDtJiFjGaDrCuA|Ai@xAk@~F}ANE`AWjB_@fCc@`DYxAIfBGpCCzAB`B@vCJzBTfBTzAV`ANnBb@bBb@hAZ\\LfCx@`A\\bTlHzG|BvJdDb@VtB~@~DrAzAf@fEvAjEzAbBj@nBp@jEvA`A^xCbAND"
                     },
                     "start_location" : {
                        "lat" : 34.8693554,
                        "lng" : 44.6374626
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "30.1 km",
                        "value" : 30075
                     },
                     "duration" : {
                        "text" : "6 hours 1 min",
                        "value" : 21657
                     },
                     "end_location" : {
                        "lat" : 34.6206084,
                        "lng" : 44.9105748
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wyhsEmfsoGBE@C@?@?@AD?H@VHVDJBD?@AFCRQ\\[TWFInAoARSx@}@`@a@^a@NOd@e@fAcAt@}@hAoAd@g@x@y@hBmBd@e@nAqA~@eA|AcBtC}CdCkCfBiB|BaCHGfCiCjDkDhDeDz@oB|AyAxCwCtC{CpCuCbBiBPQt@}@Z]NOz@kARm@n@cA|B_DNU|CeE|CeExDqFvD{EvCwDdBwBbBaCvGkJvBkC|CsD~@iAtFoGrB{BrEcFlHaInAuA~PiSbDwDlGkHn@u@|FoGvBgCdIkJfNyPnEmFhEeFxGiIJMjDeEBCnGiI|GwIdDeEjBeCDEjHmJpDsE`BwB~CyDtCmDBGhD{EjGgJnAiBpDcFzGiJlCeD~BcDdJ}L^e@TWvAgBjEqFzCwDh@y@dBiCPYpBuDhAyBr@oBRu@V_Ar@wB\\}APy@PaAzAoI~AuKfB}Jf@mCbIof@XcBbBuJh@yCj@sDJi@r@sEd@eDfAuHpA}HHi@rCcRdCePbBwJ~@gGTyAtAgIf@qCt@}DpBcLz@sEdAsFnBwJfBiLxCkN\\cBfCyLFYxAwHJc@n@kC`CuJvCkJf@_CTgA\\{@Xi@Ra@f@q@`BcBpGeGxMuJpF_E^YxLeIlFsDfJkGpE{CrFuD|HuFbKiHvCsB\\UtFyDzCuBhEqC`EqCxHkF`O{J~AeAvBwAlMkIxNeJtD}B`GcD|JmFHC~CoBlLsGrOsJzSoMzFqDhLiHbDuBvE}CjEsC`C{AbAq@pBqALKrCoBz@m@f@]xAwBj@y@fBqBZ]l@q@JQjAyBFUHg@@EHc@h@iCRaA?EHc@lA{G@I@CN{@ZgBRqAX_BRsAFYj@mD|@sFFa@`BsJl@qDl@eDDSrCoOnBaLRgApAoHj@cD^uBv@oE`AsFlBoKhCcOLo@xAcId@kCbAiFjCuMrBcNnBaMr@mEt@sBbAoD^gAdAwCvBkGlAaDFO@yAd@_PZaNJoEJmEB_DJUjAyCj@qBRo@|EcFfAbAr@cAlDmFLUl@gAd@}@fAmBpCuDxBkDpEiGnDoEdBgBlB_BfCsBvBuAbFmDxDqChAs@Ha@"
                     },
                     "start_location" : {
                        "lat" : 34.7844417,
                        "lng" : 44.66806640000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "45.0 km",
                        "value" : 44961
                     },
                     "duration" : {
                        "text" : "9 hours 0 mins",
                        "value" : 32402
                     },
                     "end_location" : {
                        "lat" : 34.3255771,
                        "lng" : 45.1660046
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yyhrEarbqG`Ei@tFs@xEoAbDyAjG}FfGcGlGiGbLyKtTsTxIyIlFkFlOiOfCeC|QyQvMwMbTaTvD{DjFoFjMuNhBgC|GiJzDaFRW~a@cj@jA}AzAoBb_@}e@hSqWjCqCbCmB\\OdHkCxP_D`Eu@rCqCzSsD|G]jJXfJXnb@jA~DTd\\`ApDJ~Pn@hBJzFXzP|@T@rKt@hGb@z@DjAFd@BdXtA^Bhh@xChAFpV~AzAJzDRhBJ~G^hG\\~Fd@D?`EGrGw@xJyFbAm@lE}AlGqGnMsMhEeEza@ga@b`@__@vc@gc@~OmOzVcVhBgBxFyFvXoXpS}RxGoG~KsKxMeMlGmEpAo@pDeBpVuHpL_GbNkDfAY|DmA`IeCfIgCfCw@pH}BtIiC~Bu@bHy@VEvFHrKbBjCb@bKbBzHrAxGfAjXhEnObCtEl@`@DvEXzBKdCG~B]dFcAjLaH|A}@zFiDvNoIxEwCzDaCtJcGzBuA|BuAlZwQ|A_Aj`@qUj_@{Tr@a@|H}EnNgIdEkC~AcAf@[tRoLhG{DnBmAdBeAlRcLdF}ClKqGrAy@jJwFzEuChC}A|LoHvJ}FrJ}FlAu@nJyFt@k@vFgErEiEjMaN~BkC~@gA`BmBvJqKpEgFjF{GhBsD~CeGXi@zCoI`DoHxAiDtGgOFMn@wAtBcFpJ_UtG_PHSlFuM^_A`DkKLm@zAgIl@wFn@iMhAqYb@iLb@wJZaH@a@z@{R`@kJt@sQF{Al@_Od@mKPuDXyFH{A\\sDd@cElBgPj@yEbAwI\\}Cp@}FDYRcBnBeP`AiIz@sHNsADk@HoAH}ADoBB{BCuCKiKAc@WqPGiHBsC@{AFqAPeDTsCZyBh@qCd@uBv@oDPw@hAiFhB}HtB_Kx@{DjA_GtEwUJi@VuAtGi\\nCaN@I"
                     },
                     "start_location" : {
                        "lat" : 34.6206084,
                        "lng" : 44.9105748
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.8 km",
                        "value" : 5847
                     },
                     "duration" : {
                        "text" : "1 hour 10 mins",
                        "value" : 4227
                     },
                     "end_location" : {
                        "lat" : 34.2878479,
                        "lng" : 45.1614933
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKalar Road\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{eopEontrGF@`BND@dOlCtNlClEt@|AXnBZhB^r@N|B`@bANvBb@xB^lAR~@PtAT~A\\jARjBZhCf@fBXzBz@`Bx@dAl@nAdADDfBjBdArAz@bApAdBnAzAfA`Bx@fBl@jA`@hAVh@zApD~@hBrAlBf@j@d@`@HFTPb@Td@RfA\\~BJhAA|AKjDY~DY~BAnALnBb@dBj@tBfAvAp@hBr@nAVbDj@x@HhB^xC`@lDd@~@NlBVn@J|@Lf@Jf@HjANl@HfAHzALz@B|@DjBNxAD@?fCNp@@v@DF?l@APE`@IRITMh@Y`@_@\\i@V]N]Je@Ry@J{@Du@?]?WC[CQEm@Mo@Ss@AEYcAiAyD}CuK_AeDo@cC]eBOmACS]cCa@kD"
                     },
                     "start_location" : {
                        "lat" : 34.3255771,
                        "lng" : 45.1660046
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 191
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 144
                     },
                     "end_location" : {
                        "lat" : 34.286565,
                        "lng" : 45.1628687
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eKalar Road\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "azgpEirsrG~@oAxC}Cf@e@"
                     },
                     "start_location" : {
                        "lat" : 34.2878479,
                        "lng" : 45.1614933
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "60 m",
                        "value" : 60
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 34.2862478,
                        "lng" : 45.1623744
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_rgpE}zsrGv@~@?DD\\"
                     },
                     "start_location" : {
                        "lat" : 34.286565,
                        "lng" : 45.1628687
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 862
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 626
                     },
                     "end_location" : {
                        "lat" : 34.2785582,
                        "lng" : 45.1632119
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "apgpEywsrGnBGtAEZAf@CtAErCIp@ClDKx@EfCMzEUlBs@PGhBE~@AdBE"
                     },
                     "start_location" : {
                        "lat" : 34.2862478,
                        "lng" : 45.1623744
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "45 m",
                        "value" : 45
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 34.2783671,
                        "lng" : 45.1636554
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_`fpEa}srGNg@Le@FK"
                     },
                     "start_location" : {
                        "lat" : 34.2785582,
                        "lng" : 45.1632119
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 34.2782822,
                        "lng" : 45.16365140000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "y~epE{_trGF?B?D@"
                     },
                     "start_location" : {
                        "lat" : 34.2783671,
                        "lng" : 45.1636554
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 124
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 34.2778893,
                        "lng" : 45.1648731
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g~epEy_trGDUBKH[?E?A?C?IAKBIDELQBCFMBIP}@@W"
                     },
                     "start_location" : {
                        "lat" : 34.2782822,
                        "lng" : 45.16365140000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 728
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 545
                     },
                     "end_location" : {
                        "lat" : 34.2720915,
                        "lng" : 45.1643463
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "y{epEmgtrG~Bj@b@J|Cv@pA\\|C`AVFVH~Ab@jCp@h@P^FLALAHEFC?A@A?A@CFg@He@^{@Vm@FEFEFCHCpAE"
                     },
                     "start_location" : {
                        "lat" : 34.2778893,
                        "lng" : 45.1648731
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 682
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 513
                     },
                     "end_location" : {
                        "lat" : 34.2673276,
                        "lng" : 45.1597956
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKalar Road\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qwdpEedtrGHVRZRp@Vt@TX`AdAr@p@^VHFd@\\n@b@?@hAx@bAr@f@`@rAdAPNdAz@z@p@LJ^Zn@f@\\Xp@j@TP"
                     },
                     "start_location" : {
                        "lat" : 34.2720915,
                        "lng" : 45.1643463
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3236
                     },
                     "duration" : {
                        "text" : "39 mins",
                        "value" : 2339
                     },
                     "end_location" : {
                        "lat" : 34.2414046,
                        "lng" : 45.1459797
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eKalar Road\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "yycpEwgsrGJ`@DDf@`@RLXNb@RNDZF~@JbBTtAPrANfBTfBVzBZh@FpCZ`D^hANv@LnHv@|@Px@X^NVNp@^n@b@fBpApErDfA|@rAfAhDvC|ApATPlDzCNLrD~CB@`Ax@hDrCV`@hCbEn@~@r@fA\\f@FHDBDBJHfAt@\\PXHn@NbDr@bHbBhOfDfH`BhCp@"
                     },
                     "start_location" : {
                        "lat" : 34.2673276,
                        "lng" : 45.1597956
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.3 km",
                        "value" : 5334
                     },
                     "duration" : {
                        "text" : "1 hour 5 mins",
                        "value" : 3902
                     },
                     "end_location" : {
                        "lat" : 34.19387340000001,
                        "lng" : 45.1537134
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ww~oEkqprG@A@A@?@AB?^Cf@CbC[jCShBQhCUdEa@zC[dBQF?N@REh@IfBMTCx@Kv@GJAhAIlAKf@G^ERAfCSbCSx@KbGi@\\CnD]vFg@rIu@tEc@pP{AhEa@jAKzAOdBOxCYrP}AnEa@vD]~UwBzD]ry@mH`AIpAM~b@uD\\A"
                     },
                     "start_location" : {
                        "lat" : 34.2414046,
                        "lng" : 45.1459797
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.9 km",
                        "value" : 3892
                     },
                     "duration" : {
                        "text" : "49 mins",
                        "value" : 2960
                     },
                     "end_location" : {
                        "lat" : 34.2023991,
                        "lng" : 45.1944243
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eExpress As Sa'diyah\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 5\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "unuoEuarrGGkAQyCQiDOsCGiAMyBKqBC]KsBMaCOgCMiCQ{CMoCAOScDQaDOyCOmCCs@GcAIeBQsDMeBI_AMmA[{Be@}Ci@sDq@qEm@cE[yBm@{Da@sC]aCg@eDg@gD_@cCIq@QmAc@qCa@uCg@kDIg@]}Bi@uDe@uBQy@Us@}@yCiAmDY{@m@qB}@qCcAaDACgAsD]mAa@aBo@sCCMg@{BKm@Gk@Gu@CaACk@EsBAs@Cu@Ao@?g@?U?M"
                     },
                     "start_location" : {
                        "lat" : 34.19387340000001,
                        "lng" : 45.1537134
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "26.1 km",
                        "value" : 26122
                     },
                     "duration" : {
                        "text" : "5 hours 14 mins",
                        "value" : 18810
                     },
                     "end_location" : {
                        "lat" : 33.985178,
                        "lng" : 45.2573726
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eتقاطع امام ويس\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_dwoEc`zrGz@Vb@Zd@^rAtAlAbA`At@jAt@r@\\TJfAb@DBpA`@l@NrAVpBRnAFlADfBEbCS~C]dE_@rEe@zEg@hGq@zDa@lEc@lFk@jBSDAhBQ~Ek@pEc@nEg@dFs@bDo@hCm@nBg@dAYdBi@rBq@tBs@n@Wd@S|Am@bEgBb@Qb@S|Ao@hCkAlEoBrB_APIRIfDuAx@]fBw@vAm@~BcAdFuBJEjEmB~As@ZMtAm@`CcAn@YzD_BpDyALG`DsATKBAfCiAb@QvEqBzGwCxEoBlAg@zDcBzCqAdDwApD}AtB}@fCcAnB{@zEuBBAvCmAhBu@xGwCbF{BPIbFsBrEmB|FkCbEeBlBy@xB}@d@ShBu@f@U`DuApAq@|A}@@ApAy@xAcA~AoAzBiBjDsCdA{@fCqBp@k@pEsDjEoD|DcD`FaEhEkD@AdEiDb@_@bH_GrDyCnBaBt@q@vC_Cd@_@rAeAnAcA~AsAxAmAz@q@`As@n@a@NKbB_AvAk@~Am@`AWlA[nBc@fBe@|Ae@~@]FCr@YbAc@fAg@p@_@fAo@p@a@zAcAj@a@r@i@`ByAr@s@z@{@x@{@h@s@Z_@vAsBf@w@z@yAt@yAd@_AJSd@aAf@eAbAoBFMxA_DhA_CbAoBp@{AfA}BzAaDxAwCx@iBh@cAt@}AjAqBz@yAx@oAJOh@u@rAgBrA{AtBwBlBgBhA_AtAeADEbAq@zBwAdAm@`Ag@jD}AtD_BXMpD{AvCkAxAk@vAk@lAg@~BeAnAg@tAi@`CaAnBy@dAe@dAc@bBq@pAi@fAc@~Aq@pCiApB{@tBy@vAo@j@Ut@[rB}@TKhCcA|By@`A[fA[lA[hBa@t@MrAWRERCpBWnBQ`BMtBIN?~BET?zBE|CGxCEfBCj@ATAfCC|BElACtJOzAC|BC~BInDEjCEh@AvACjACfCElCCpCB`CDzAJr@D`@BpBPnCZfC\\|Dt@xBf@fAVzC|@dD|@`D~@~Ab@r@RrCx@|Bn@xEtAvDdAvBl@FB`D`A~Cz@`Bb@hBd@fB^jAVdBVTBbBVpBNdCJzBDfCB~@BrGHv@@hDFlABnB@pEFfBBd@@`DD|CDnCBlCDpCDL?|CDzCDjDD|DFjDB`EE|CObDYpDY`DUf@C|BQtEa@|D[nCWfDYvD[`DSlCS`BOx@GlD[zCUjDYn@EdBObDY`DW~BOvE_@jDY|BQzAKnFe@jE]`DU|CYjBOp@E`DYlCUbCQnD[hF_@vGk@zFc@JA~AOhCQpCW^CtBO`CMbBCzB?p@?hDDdDJvCPlCVRB|ANbBT|ANpAL|AP`D\\\\DbAJxCZbCVdBRhCXl@F~@J|D`@\\DnBVbCV`DZdBT"
                     },
                     "start_location" : {
                        "lat" : 34.2023991,
                        "lng" : 45.1944243
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.3 km",
                        "value" : 6344
                     },
                     "duration" : {
                        "text" : "1 hour 18 mins",
                        "value" : 4662
                     },
                     "end_location" : {
                        "lat" : 33.9633453,
                        "lng" : 45.30665519999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kvlnEqifsGHiAGaASu@{@cBiAcByBeDiBeCOSMOQ_@G_@Dg@Pk@zAuBf@u@pDsEtAoBv@eA`@w@BGTo@ZeAd@oBNqAj@yENgA@Cl@kBnAmEVuAEeAa@gB_@wAk@kCMo@[uBGi@CY@iBJgBTeB@Cv@iC~@{B\\m@f@o@DAv@WtA@hB@D?`CZjF~@tAXXF^Fp@AhBOpDYj@EnBGdAKz@Sx@a@v@y@Xc@fAkB|@aBr@}BZiBj@kDv@aFDURiARu@n@kB|@gBrAgCpA_BfCwEFKlDsGh@cA|AeAd@]VKdG_CDAxFe@`@C`DY\\a@r@w@bA_ALKf@aB`A{CL_@H[bA}EhAsFFWt@wBLs@Fa@Lq@?aCKoA_@mE[sBc@qFOkAe@_Dk@yES}AGkAGuACc@PgCLgBVcAdAyANQhAyABSLgB?aCCoB"
                     },
                     "start_location" : {
                        "lat" : 33.985178,
                        "lng" : 45.2573726
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "19.5 km",
                        "value" : 19507
                     },
                     "duration" : {
                        "text" : "3 hours 52 mins",
                        "value" : 13905
                     },
                     "end_location" : {
                        "lat" : 33.8090968,
                        "lng" : 45.3374547
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}mhnEs}osGhDfAjBl@nMvEnIzCdC|@lHlClHjCdC|@dC~@d@N~DfBfALlC\\h@HdC^nBZ~In@pDVrHh@`Fn@vFt@pANX@jCHd@KhB[~Bc@vCi@bLsBhB]B?dBOnCUF?nCBdEfAfExDhTzRdCxBrD`CnH|ArPBdMX`IRrDHx@BxBFzFL`IRjBF~GPrDHdJTvELfABV@vBDfJNpDFjKPrMT|HN~FP~GRvENhADrNRvBDx@WdA[`EkBpDaBbPqJpa@{`@zFuF`C_C|IaOxFqJl@aAV_@nQmXlCcE|DeGr@gArHeE^YnHgFbOkKlBsAd]gRhKyFlKgGxHqEzFgDxJ{FzCgBn`@gUn\\uRzCgBtf@sYv@SvHgBhCo@te@gMbO_EdPiExPoFbIsABAnCG~@ZhDhAhQxk@xDrL"
                     },
                     "start_location" : {
                        "lat" : 33.9633453,
                        "lng" : 45.30665519999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.2 km",
                        "value" : 8243
                     },
                     "duration" : {
                        "text" : "1 hour 39 mins",
                        "value" : 5936
                     },
                     "end_location" : {
                        "lat" : 33.7523011,
                        "lng" : 45.39260549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ijmEa~usGjGmHrGyH`MgOnIeIzNmNhRaQpFcFpEyCnJgDfMqEtEcBlIsCpN{EnHwBbD_AzLmEjDeCbIkJpAgBbCeD~Vi]hDoEv@eAxZca@pBkCzWo]pE_GlWa]fAyArCwDxGmJrF{HbGsIFIFKx@oA|Ag@"
                     },
                     "start_location" : {
                        "lat" : 33.8090968,
                        "lng" : 45.3374547
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1560
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1128
                     },
                     "end_location" : {
                        "lat" : 33.7527567,
                        "lng" : 45.4094379
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 82\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{f_mEyv`tGOoDAOWyFI}Aw@{R?UQeJCaO@{P`@cT@s@"
                     },
                     "start_location" : {
                        "lat" : 33.7523011,
                        "lng" : 45.39260549999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1567
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1141
                     },
                     "end_location" : {
                        "lat" : 33.7425524,
                        "lng" : 45.4211023
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wi_mE_`dtGHADAHGDGh@e@l@q@z@cAfJgL|m@cu@"
                     },
                     "start_location" : {
                        "lat" : 33.7527567,
                        "lng" : 45.4094379
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "17.8 km",
                        "value" : 17780
                     },
                     "duration" : {
                        "text" : "3 hours 34 mins",
                        "value" : 12865
                     },
                     "end_location" : {
                        "lat" : 33.6550843,
                        "lng" : 45.5510545
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}i}lE{hftG~iBfDjQqAfLiEzb@{TfE{B|{@ce@pFqD`IiFvD{DrDoIlSquAxVyeBlIsl@lIql@t@{Ft@yFHi@dK_s@^qB^wAvCcHBInKaNvCuDr@}@\\e@h@s@~@kAzAoB|BwC|KwNzAoB|EmGpVa[bGaIdPmTpIuKrBkClNsQdKyNlBmCLOjCcEvRc]dFmJ`@w@hAuBf@_A|N}S|BgFlByGjBsGd@mCtByLxAcLIuD?Aq@kDAE]_CuCwBm@c@}@u@sCoBECwG_GSQKK}BwB"
                     },
                     "start_location" : {
                        "lat" : 33.7425524,
                        "lng" : 45.4211023
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 674
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 479
                     },
                     "end_location" : {
                        "lat" : 33.6523676,
                        "lng" : 45.5575602
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRoute 13\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ggllEau_uGtBcHzBsI|GgSLU"
                     },
                     "start_location" : {
                        "lat" : 33.6550843,
                        "lng" : 45.5510545
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "81.0 km",
                        "value" : 80953
                     },
                     "duration" : {
                        "text" : "16 hours 14 mins",
                        "value" : 58467
                     },
                     "end_location" : {
                        "lat" : 33.1297708,
                        "lng" : 45.9132814
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ivklEw}`uGFOlBiGL_@l@iBj@aDG_DI}@Gu@s@yJgCyWy@eIi@eCq@eDcBiFOc@KSkCkEaGwHoHiJ{EiGkBqEq@yCOaCKcB?Ir@sTl@cJfB}W\\kFDm@fAwPCw@MwD?oDPsBLeBHa@x@sDT}BTyCdAoMP{CZqFt@sM`EoUN{@Jo@`@aCdAaGLq@LsBIaBCc@jBuY^yGr@cM`E}e@ToCdAwMbDy`@`A_Lj@gHVyCr@cJxAkSVoQ?o@@O@m@?EDgC`@kV|@}XDgAl@qG@G\\kBj@uAH{Bu@gHQyF\\aDZaE?EG{A?ICi@qAqCIIaNuKcO{MwEeEwFkHW{@_@mA?yALQh@u@jCeCrEkFd@u@`FqHrQ}ZxAcCvB{Dp@mAXe@pEqHxDmGdGgJTWlDqDXY~EqExE}C~DkBtLqE~B{@dAa@lGaCjHqCfDoAZMxPeGdN}EvLiEdLaDvEqApHuBjYkI~GqB~`@yJtBm@`AYpTqGbPwE`Bc@ZKxF_BxNsDpDgARGpBs@jC_AvCkAb@S`GsCd@YvGyDrGsEtB{AxBmBfBoAdGiEvAeAjJ{GbFsDbGmElF}DbOyKfCqBpAcA~BuArB]d@GpC}@NEdBe@Z]XYz@{AvBmBtAwAj@eAZaAb@s@rC{BhGiEbCkBtEyC|AiAdPoLtDuCjGyEDCjBwAnA}@@?xImGlA{@xEqDLI`@[xJmH`CcBn@e@tHqFrRaNZU|DyCbO}KfO_L^UdCyABATEb@G|CA~BZlAP|Gr@hDDjKGrCAv@?~Ep@dANnC\\xCT~GBhE?z@?nBNpB`@`A\\fCz@`@Fb@DPBhASn@[|@aAh@w@z@_@b@KTElCMvB?`G?lDAp@?nEA~@?hAAjA?fBA~DAz@@rIFlDSfDYz@ItDe@DA~Eo@|KqAfAMRC|Du@lAUbFqAdD_ARGx@YrJaDhBm@pIyCXKtEaBt@_@fAm@jAk@lDeBrFmCpL}F|DoBtFqCpCuAtDkBjJ{E|BiAtMqGpE{Bh@Wx@_@dIyDnAm@vTsKbCqAjO_IvLsGrH_EBAZQnGwD`EmCDEnDgCpEyC~CkBbEmB`Bw@`CgA|GaD|M}GjGaD\\QnDkB`@SrFoC~GiDfM{Gv@a@XOhKiF^SvMoGdKgFHGbBwA^u@x@wALWbAiCRk@jAuDpA}FpDaUdA}FrCwOh@uDF_@tIeYJ_@fEoNxE_PrBkGxAiEj@gB^mAzAgFn@wBxCaKTy@dA_ClAoCt@cBfAoBLm@Je@ZeBdEsIhAgCpDqI\\aAHUJG`@QhBeAfFoAnEgAxR_E~Bi@`LgCrBuADCZUTOZQ\\{@Hg@TwANuATkDBm@TaFJeDB{@JmALuBDi@B]Je@Tw@Zq@j@aAZy@p@iB~@yBz@aBVm@V_ALs@R{AFiALiA^aB`@}@j@eAfCqB^YvJaGrOgKlG{Dv@i@fR{LxDaCtCgBjGcEvK_HhPqKbDoBvGaExCoBpHaFxCoB`IoFjBkAhJaGbDoBzCkB^U^UtHwE\\UzCmBXSzFqDpGaEb@YdMgIvMoIpEcDFEvGiDhAk@xBaAdIuDXOjF_CfJeEfRmIfCkA~GcD`\\kOjHyCn@Y~G}CfIsDfJcEb@S`EeBt@[vKwEhJ}D`DyAxJmErDaBfAg@|DeBbEiBdFyBbEiBdEiB^QLGRIPIpD_BbDwAfH}C`CgAtEqB~G}CVKbF}BxOoHxBcAzAe@vC}@fDk@|B_@h@IhQkCjJcB|GkAdCg@hB_@dHwARChUsDVEpF{@DAhIqAv@O~I{A~I{AvCg@zCg@~GkAjN}BlR_DtEu@xEcArBa@hHoBhCs@rBi@|C_AxBo@pA_@zLqDnCw@rToG~EuAnF}AtC{@hJmCbKyCnEgARGbGeBxDgAlRqFlPyEnK{ChGiBnGkBVInK{CnHuBvKgDx@YrEeB|Ao@`GcCHE~BaAf^cOxAo@bBu@f[}MtEkBbEcBdAa@|MqFfUoJz@_@hB{@`Ac@bAc@z@_@z@[j\\yMzJeErIqD`Aa@nF}BdPaH@AtBy@dO}FdXyKvAm@bHuClN_G`EcBxF}BzDaBpSuItMuFLGnFyBfIeDrHuCxL{DfJiBt@IdEKtHQv@CjCJfCL~Id@nHBdCT|ClAvBrAHDzB?nJQ`J_AtLsBxBc@tGoAzHaBxM_BrIq@hDYxJ}AtL_BjLiAz@KdPgChGeAlAb@~E|CtCvCFDbAnB|BnFfDbJfCvG|U`m@HR`DvHbHvPfBzF~AjFPZd@~@zDnHjFtKvChGxFhLlBzDb@dA|CjHhDrFxD`Fx@dAzD|EnIjKvSbWX\\zSxWvDvG"
                     },
                     "start_location" : {
                        "lat" : 33.6523676,
                        "lng" : 45.5575602
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2572
                     },
                     "duration" : {
                        "text" : "31 mins",
                        "value" : 1883
                     },
                     "end_location" : {
                        "lat" : 33.1165443,
                        "lng" : 45.93501810000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ateiE_mfwGl@?|@Uh@wA`CkG|@eBt@eA`JcNtBuDVe@Zy@tCyHbCgI\\kAvCaMhB{FX}@N_@bAiCfBsEHUpAuCl@cBJ[~A}DRo@z@gCDIdDuERY|B_Bb@Y~B}@dC_A"
                     },
                     "start_location" : {
                        "lat" : 33.1297708,
                        "lng" : 45.9132814
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1421
                     },
                     "duration" : {
                        "text" : "18 mins",
                        "value" : 1064
                     },
                     "end_location" : {
                        "lat" : 33.1107201,
                        "lng" : 45.9449836
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 13\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eGo through 1 roundabout\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kaciE{tjwGiBoHyCiMAeAVyBv@iCJOtAgBxB{APIAI?G?C?A?C@A@C?C@A@ABEBC@AB?@A@?BA@?B?B?B@PEVERAPC^KnBaA|@g@`EuBnBaAnLcGh@i@"
                     },
                     "start_location" : {
                        "lat" : 33.1165443,
                        "lng" : 45.93501810000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "130 km",
                        "value" : 129858
                     },
                     "duration" : {
                        "text" : "1 day 2 hours",
                        "value" : 93772
                     },
                     "end_location" : {
                        "lat" : 32.5181559,
                        "lng" : 47.0639968
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eRoute 13\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Iran\u003c/div\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "_}aiEcslwGHUDMFG|@{@r@u@vAoAfAgAf@m@d@m@|@oAPW`@o@fA_BfByBlAgAnBiBtAaBDGDIL[`@uAFSN]DGDENGNYfAcBpDmFjDcFNUfEoGtBaDPSPKjCcBzAaAvBeAvEgBz@i@|Bs@dCcAt@YfAe@vCiAhBu@jBu@lBy@hDqAfDoAh@UrAi@xCiA~@_@`@Sb@Sn@c@j@a@vCsBxBaBzBgBtEeE|BuBf@w@RUHI^[h@c@pCeC`BuAlAeAtCuCfEwD`DwCpAqAhAaAz@y@|FeFzYkYpGuGnCqCrBwBxEkElBkB|A}AfD_Df@g@xAyA`DyCvBmBfBgBxAyA`@]^WRMTKNGRGn@KZENAT?T?N@bAJ\\@^A`@CNENENELGLKRQjBaCjA{AzByCtGqIlHoJV]jA{AZa@bC_DbC_DvBwC|DgFhEsF~BwC\\c@vBuCvCwDrH{JfDkEDGxCuDvIcLr@}@n@}@RWdC{CtCyDpDsE~ByCj@w@T_@Re@Pk@Ni@Ji@|AeItA}G^eBpLsl@V_CDSR[r@k@p@UxCcAlOiEdA{@h@a@tC}CtF}FdDmDnFwFxMgNpJcKnToUzAcBdHyHpJmKjB{BhGsHdH_JfIkKpPqT|ByBx@y@LMdE}CpJqEbF_FpHsJ~F_IjRgWX]lNmR~Ve]rTgZvZcb@lDwEpNkRrVw\\hXg^rXs_@bDiEbUwZvG_JfPuTfLqPf@sAjAaD`EiOlGyWnH}Z|EwTzCcNlIe\\fKib@tCeM`AmEdMeh@R}@Ji@vCcNXaDoAi]?I{Bgt@OaFy@iXqAua@{Aid@c@uMq@_Sq@kTcAuYgAi\\g@mTUaK[qE}@yLe@oCyBaMkEgWKi@oG{^cCiN_CkNqA{HmAqJQyDUgGImEOkHSuIaA{`@GoB_A_Yg@mR]uMe@uQaCy}@YqKScLUo\\GcIQ_YSmZCmFIkKGaPIsOEeECyCK{LKyUIwOWgf@EiGC{DUqZQ{XA_AAcIB[RiDv@_MjAcKp@gGvC}XxAiNbA}IhBcPl@qFdDmZ`E__@nDw[`Jyx@vA_FJ]BGh]u`AxPye@~`@_iAzPwe@vBcGlD{JhG_QxF_P|I{VrI}Uf@wA`FeNbEkLnCaHtB}FlFcOx@yBvBeGdOwa@vA_EvI{VvFePFObCwGvDiKlIkUvI_VlIaWp@qBp@qBvCaJfGwOlD{JjJuW`GsP|D{KpFoOtFgPbEqGtEiHhIqNbAeBpDkG`CcE~AiCpBeDtRw[Zi@~GwLzIqOrDqG|Sa]x@uAnBgDzHsMrLeS`@s@dRg[~GgL@AdMaTxLqSjAoBrFqJbEiHhMyS~MyTdLuRdAiBl@cAbJsOhLsRpEsH@CnLoSzFmJt@mAT_@vEyHlF}ItJgP~B{DrMiT`JwKtJ}JjBeBfOqNhG}FXYdLsKrKaK|@{@tIuIjJeLbDyEfBiCrTy[fG}IzGuJvMoRjEoGpIcMjRsXdEmGjC}D`CyDr@kApC}Hn@wFFu@t@aJDsAj@yOLsDfBeVz@}EdAgGl@aCzAkGvIq[tE{PBGtJm]tJk]z@{CxAkFfA}D`DoLhLeb@dAmD~F{RlDmL~DyM\\kAjIgS~DwJpDeJBG~A_EjKyWnFaNrEgLnEaLvHqRdAkCfMe[jFsKpDsHjQs_@b@_A`BcD~Skb@vCiGbQs^bFmKrImQfDcHlHmObMuWfIqQRa@`LgUvGuL~CqE@Cr@{@jJ}LjQgUfFwGzFmHdCaD`Zm_@HKlS{WvCwDfEmFlEsFrFaH~K_PDG~BgCxEiFbG_HnFsF`KkHFGxEkDhCkBtImGbE{ClHkFJI~LaJfFcDjA{@nLyIpCwBlB{AhQsLlA_AfLyIrJoHfGqElPqLNK~UuPxLoJpAeArC}BrEwD~LkLtEqGrLwPhA{ArCyD~HqKv]ye@nQwVh@s@nBoCvCaEnGgJ|J}MjDyE|CiElMwQlD_F|AyBpAkBpRgX|IyLjCqDnIkL^g@vMwQfGqIbAuA`S{XxHsKlPuU`B_CfF{GrEcGnI}L~G{IbCiE@ChCkHvBwId@oB|CgKbBuFfBeHp@mEvEcQbAuDlBsG~EgNvCyGfEaJxLkWrEuJhTyc@|@gBz@iBrLmVnGeNRc@|GcOzJkSjLaVzIsQ|Tye@nDwHpEcJ`Qs]`@u@vKaVZcAjAyDj@uEb@wGj@iIRiDbEws@TsDTyDnD}m@FkA`A}HTc@~@eBVa@~@yAlCqCxMcNvAyAbTqSlI}InCwCz@gAdM}OnDyErD{ElIyKzDcF|MgQdDiEpNyRdEyFvByCxC}DxDeFb@k@pWi\\LQrTyZnEuGFIn@y@`IqK~KqNbC}DV[`BoBzAiBvLqPrFeHvCuDJMr@gApLiQlBiDfGsKdB{Cv@wAdM_TpEeIdD}FrE}H|EmIjM_UfCoE|@aBpIgOd@y@~NwVJQbL_SdJsO`BsCvDuGnEaIxEcI|F}JfEyHzCwHViA~@iEv@iExAcIZeB`FcVZ{AbAeFhBeJzCeK"
                     },
                     "start_location" : {
                        "lat" : 33.1107201,
                        "lng" : 45.9449836
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.9 km",
                        "value" : 4880
                     },
                     "duration" : {
                        "text" : "58 mins",
                        "value" : 3492
                     },
                     "end_location" : {
                        "lat" : 32.4921451,
                        "lng" : 47.1054921
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eRoute 13\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road may be closed at certain times or days\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Iraq\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "oeneE_eg~Gf@mAlNwZTe@zF{NjEwKRi@rFcON]jBkElDgJj@}AxA{CxCkFTa@fE{GnDiFx@mAjDuF`EaGzD_GHM\\e@hCsD~BeEjBuCN]tBoElAsCrBmEzBmFr@_BlF{L|B_FzBuEp@mAfAaBbAkAr@w@`B_BbBcBhCcCrBiBdDsC~@gA"
                     },
                     "start_location" : {
                        "lat" : 32.5181559,
                        "lng" : 47.0639968
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "55.2 km",
                        "value" : 55178
                     },
                     "duration" : {
                        "text" : "11 hours 1 min",
                        "value" : 39637
                     },
                     "end_location" : {
                        "lat" : 32.1136137,
                        "lng" : 47.4322416
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eRoute 13\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road may be closed at certain times or days\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "}bieEiho~GjA}A~BaDpAaCjC{EtAgCxB}D~AoCbBuCj@iATa@fAuBtDiIl@_B|@eCvDiMv@uCdByFrAoDnAuCf@mAhHwO|GaOdB{Dn@sAl@sAhDqHhBmDFMnC{DxD}D`CuB~B}AdB{@bB]zAKdAC|ALfBTdBTrDj@hBTn@HnBJp@Er@Qz@]p@e@l@g@Zc@\\o@h@qAdAsC`ByERm@jBmFvCqIv@aCvA_DnAqC~CwF|CiFfDwFbEaH~CiFnFcJzBcErEqHrFmJpEmHLQtDkGjCoDhBoBxCkC|C{BxDiBbE_B|H_DpGaCd@SjGiCtOeGtHyCrDuAjCm@zPcJhE}AbBk@lE{AtC_DtEuEbFkDnCiBlCoDl@aBh@wA`BiEr@uBh@uDPiC\\iGYcECyDJk@Hc@vA}BpImOpFuJ|Q{[\\m@xB_EvAoC|DsHlEoMhBwEhK_XfI}Sh@qAdDcJfNy_@rByFhI{SnGiPbFoMdNq^`DoIzBcGBG~KkZbCkG~EmMxD_KpHsR|GoQlLoZfJeV~I}UhKwXtBuFbEwKrDsJf@sA`HuQ~FyJjEkH~Ty^vAyBbMoR~EyFpEkDVQzBeB`Aw@rGcGbEaGzD{IfCiKr@yCtCqLh@wBlH_ZbAcElCqLjAwBbE}Dl@_@hCcBnFiCdI{D|A}@nYaP`IoEzA{@nY{OjGeDZQ~LsGxHiEzMqHPKjCuAz^yRxA{@z]kSrEcCx@c@dQgJnTmLfFoCbEyBhYmOlEaC~_@eTtC_Bz\\cRpHcEtPeJ|H{DjFcBtDy@|QaEfWeG`SwEnQwDtCm@vOqCpD{@lIiB|GaBhKuBzIoBvFgAlIsBtIgBnFsAfQoD|Ci@nJsAzMcBnFk@zFs@tFk@`Fo@bEi@laAmLvMeBzYiDnKuAhGw@fEe@vJwArCk@xBi@rHcChGoB~PqFfOmEnKgD|IuC`TaHfIiCpUeHxZuJvNsEzMaErJqC|FwBjYwIlJsChF_BdLoDpGcBxDmA`EqAhAc@zCsBhBoApR_OnC{BtAgA`\\wVxFmE~I_HpFeEdQaN~FoEfEeDdHiFfJgHlDwCpCwCpAgCbCyF|A}B~AmB`BwAdBsAh@a@fAo@hBw@zFeBxCEjB?lBDdGZvCRtJr@~AFv@FxABrBCtAEvCQ`JiCvGqBrEuAd@SNMv@y@`DuDrPqRnHwIpAeBTYdF}F`FwFxEyFvKcM~EcGjCoCz@_AbAy@~AqAhDsBbFuCbB_A~NaIpOcI"
                     },
                     "start_location" : {
                        "lat" : 32.4921451,
                        "lng" : 47.1054921
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.7 km",
                        "value" : 8717
                     },
                     "duration" : {
                        "text" : "1 hour 46 mins",
                        "value" : 6350
                     },
                     "end_location" : {
                        "lat" : 32.0532648,
                        "lng" : 47.4853986
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eطريق مسدود\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ae_cEobo`HSmJMkDAyBVaBf@qAtAoCxAyCtUmg@fHoOzPk^fAqC`@o@jPcIzd@}Ub^qQ|Y}OpQwIj@[pEiB~AmAVQrTiPnTwPrMeHnKyEzGwCtQ}HvEcBfFuCzCgBlBgA~NkIla@yUVWxAyA"
                     },
                     "start_location" : {
                        "lat" : 32.1136137,
                        "lng" : 47.4322416
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "25.4 km",
                        "value" : 25415
                     },
                     "duration" : {
                        "text" : "5 hours 6 mins",
                        "value" : 18353
                     },
                     "end_location" : {
                        "lat" : 31.8880836,
                        "lng" : 47.665341
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "{ksbEwny`HhSqYd]qe@lDyE^w@t@sB|Mye@XeAnFcSnG_UhHoWdAaEbF_Q`AeCdE}H|O}YdTw`@`BcCRYp@}@fm@{m@xNwM~c@m_@~CiCZWjJwHfZkVvJiIzJmI|YuWxMqLxR}PhJgHDCrRqQlIcIvIqHJKlHcGv[eZzJkJ~CmCxKaFr^mPjHcDdEuBhCiC|D{FlUm\\t\\we@tUc]n@}@|ImMrDuFjKeSjA{BhFoEnNuK~N}KjG}EzP{MlCeCzM_MxCuC`SuRx@y@HD^QrLmLxEcEvOcNbO}J~J{GjOkJtSgNtDqFxXyc@tVu`@jLgRJOtAeBnAaApBuAzYoQbZqS|IaG"
                     },
                     "start_location" : {
                        "lat" : 32.0532648,
                        "lng" : 47.4853986
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.9 km",
                        "value" : 6944
                     },
                     "duration" : {
                        "text" : "1 hour 23 mins",
                        "value" : 5008
                     },
                     "end_location" : {
                        "lat" : 31.9181271,
                        "lng" : 47.7298239
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ocsaEks|aHs\\m}@mDqJiRwh@wSwk@k^_bA{[s}@_Lc[mf@wsA"
                     },
                     "start_location" : {
                        "lat" : 31.8880836,
                        "lng" : 47.665341
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.3 km",
                        "value" : 8328
                     },
                     "duration" : {
                        "text" : "1 hour 40 mins",
                        "value" : 6001
                     },
                     "end_location" : {
                        "lat" : 31.8496289,
                        "lng" : 47.7629087
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRoute 13\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "i_yaEkfibHxR_MzGgCnOaGpXeIxJuCt]gK~@Wjg@oOtC{@xV}Hnb@}L~E{A~|@cYrU_Hz^uKrI_C~F_BlTkHtKyD`B_A`Bs@z@g@|@g@j@a@v@o@bA{@h@g@t@}@h@s@d@m@^m@l@eAh@eAb@cAZy@|@{BdAgCTk@JSRY"
                     },
                     "start_location" : {
                        "lat" : 31.9181271,
                        "lng" : 47.7298239
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 99
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 82
                     },
                     "end_location" : {
                        "lat" : 31.8497177,
                        "lng" : 47.7639501
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eشارع منفذ الشيب الحدودي\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "eskaEeuobH?gA?[IgAGc@"
                     },
                     "start_location" : {
                        "lat" : 31.8496289,
                        "lng" : 47.7629087
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.7 km",
                        "value" : 3652
                     },
                     "duration" : {
                        "text" : "44 mins",
                        "value" : 2633
                     },
                     "end_location" : {
                        "lat" : 31.8539994,
                        "lng" : 47.8019147
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wskaEu{obH\\_@NQDIBGBM?MSeBUwCYyEa@oF_@cF[uE_@wFWoDg@qFUoD]wE_AqMg@uH_@_Ge@kGi@iHYqE]cGw@uHGq@g@sEMqAOw@Qw@Y_AWm@Yw@Qe@Kg@EYIg@Im@Ei@CmA?k@Ak@?cB?eDG{DCeDCyECwIAeGEqFAuAGqB"
                     },
                     "start_location" : {
                        "lat" : 31.8497177,
                        "lng" : 47.7639501
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 124
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 101
                     },
                     "end_location" : {
                        "lat" : 31.853189,
                        "lng" : 47.802812
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eشارع منفذ الشيب الحدودي\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "onlaE}hwbHNUX[vBaC"
                     },
                     "start_location" : {
                        "lat" : 31.8539994,
                        "lng" : 47.8019147
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 723
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 517
                     },
                     "end_location" : {
                        "lat" : 31.8488109,
                        "lng" : 47.8084692
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTarigholghods\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Iran\u003c/div\u003e",
                     "polyline" : {
                        "points" : "milaEqnwbHdEcGdTgZ"
                     },
                     "start_location" : {
                        "lat" : 31.853189,
                        "lng" : 47.802812
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1228
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 892
                     },
                     "end_location" : {
                        "lat" : 31.84136909999999,
                        "lng" : 47.8180517
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eTarigholghods\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Iraq\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ankaE}qxbHNGDALS|BkDr@_Af@u@|AsBh@u@vAsBd@o@|@kAjBgCl@y@~A{BjBkCdJgMd@s@hCqDPi@"
                     },
                     "start_location" : {
                        "lat" : 31.8488109,
                        "lng" : 47.8084692
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 957
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 698
                     },
                     "end_location" : {
                        "lat" : 31.835597,
                        "lng" : 47.8255652
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eTarigholghods\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Iran\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "q_jaEymzbHrIeMxB}CdGoI~FmIlD}E"
                     },
                     "start_location" : {
                        "lat" : 31.84136909999999,
                        "lng" : 47.8180517
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 104
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 87
                     },
                     "end_location" : {
                        "lat" : 31.8361612,
                        "lng" : 47.8263814
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o{haEy|{bHGYMUKKUOSMKIGIIQCOAQ"
                     },
                     "start_location" : {
                        "lat" : 31.835597,
                        "lng" : 47.8255652
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "17.5 km",
                        "value" : 17452
                     },
                     "duration" : {
                        "text" : "3 hours 30 mins",
                        "value" : 12590
                     },
                     "end_location" : {
                        "lat" : 31.7659717,
                        "lng" : 47.9784551
                     },
                     "html_instructions" : "Continue straight",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "__iaE{a|bHCWAK?GBUJk@^mAf@uB|@eDLa@\\eAf@oBj@uBn@}BbAiD^yA~@gDz@}Cv@uC~@iDv@wCv@qC`@yAf@iBZiAl@uB`@aBj@wBAE?C?C?GBE@C@ABC@?tBgH~AyFX_An@aChAaEt@oCj@qB\\oAr@mCp@_Cf@kBh@mBjAaEJa@j@yBRy@Ng@F]DWDg@AGQo@Og@Oq@I]K]Mk@Qk@Uy@Mc@Kc@Qi@Oe@Ok@K_@AAQm@Ok@Sq@Uy@Ss@Wy@GUUy@Og@Uw@Qq@W_AQi@Ma@g@eB]eAa@{Ae@kBi@oBi@uBe@wAg@}ASi@GYAQD[DOPe@@I~DwOvFyTfIc[zBmI`CoJzDkOb@cBtD{NbG{UrBsIdCuJfDsMdAaERw@jAyEzB_JjEkQLg@~AoGdDuMrAiF^}AtBoIbAcEtAsFjEwPPm@`BqGzB_JdHqXrAiF`AwDdCgKtCkLnBeH|@qDl@aC`BwGbBuGrAkFlDoLfAoDlAeEfCsIdB_G\\cAb@_Bh@gCd@sCZkCPoCLwCPmCPaBRoATsAd@mBl@kBd@iA^{@bAoBfAaBnBoC~CiEtBoC|CeEx@iA~DqFnAcBpAiBl@w@hAeBrAwBh@}@~@{Ab@s@lBcDzCcFjAsB|AgCzDsGbAeBzCeFlD}FzCcFvAqB~AoBdBkBbAaAfA_AfB}AtE{CpKcGvJsFvG}DpBaAn@[p@_@tBmA|CeBxEmCbC{AfAm@xIsEdAg@fA_@jAc@fA_@lA_@f@Mr@SbB_@NElAU`AMnAQbBUzBOxBOxBEv@C"
                     },
                     "start_location" : {
                        "lat" : 31.8361612,
                        "lng" : 47.8263814
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "54 m",
                        "value" : 54
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 31.766058,
                        "lng" : 47.9778888
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ih{`EkxycHQpB"
                     },
                     "start_location" : {
                        "lat" : 31.7659717,
                        "lng" : 47.9784551
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "37 m",
                        "value" : 37
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 31.766058,
                        "lng" : 47.97755919999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "{h{`EytycHPh@QV"
                     },
                     "start_location" : {
                        "lat" : 31.766058,
                        "lng" : 47.9778888
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18 m",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 31.7660185,
                        "lng" : 47.97737619999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{h{`EwrycHFb@"
                     },
                     "start_location" : {
                        "lat" : 31.766058,
                        "lng" : 47.97755919999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "72 m",
                        "value" : 72
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 31.7654391,
                        "lng" : 47.9777107
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sh{`EsqycHHC~Aw@HE"
                     },
                     "start_location" : {
                        "lat" : 31.7660185,
                        "lng" : 47.97737619999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11.0 km",
                        "value" : 10974
                     },
                     "duration" : {
                        "text" : "2 hours 13 mins",
                        "value" : 7961
                     },
                     "end_location" : {
                        "lat" : 31.6977579,
                        "lng" : 48.036035
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by موکب خدام ابالفضل العباس (ع)اهالی الاهواز (on the left in 4.2 km)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "_e{`EusycHNBJ?J?LAT?T?PB^FfCf@hHpAbKfBrAPjBVfAP`@JZJd@RZNbAl@p@f@v@n@pA`AhA|@JHpA`AhA|@FF`Ar@bBjA|AhAzAbAdBhAFDfBfAj@\\RHTFRFLDPDb@Fp@Lx@JdALh@Fd@Jl@Jn@Np@RzAd@pA^zAb@vAZ\\HRBZ?FALCJCPIz@o@rAcAjByAtB_BxAiAxBcBhByAjBwA|AmAdBsAfCqBtBaBhBuAjByA|AkAVStBaBlByAvC_CjCsBnCwB|AkAjB{ApB}AtAeAlCuBjCmBtBcBdCmBhA_ArAaAfBuArB}ArAgAr@g@l@e@dAu@t@e@`Au@j@i@TQPS~@{@nIgGrAcApMiK|@{@jAqAdDmFhBaF\\oAZkCHoBf@qEJ_B?I@{@G{@GsAVsEV{Fr@{GZqDAWAi@CeCXyGJy@RsAtCcObC{JjEuQnF{TfJ}XL]nBkGZ_ArHaPzC}Fz@iAZa@nBcB@AzK{FdIiEfO_JjDsBvRsKjK}FZSJKBI@G?EAE?CCIEEKG"
                     },
                     "start_location" : {
                        "lat" : 31.7654391,
                        "lng" : 47.9777107
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "24.0 km",
                        "value" : 23991
                     },
                     "duration" : {
                        "text" : "4 hours 50 mins",
                        "value" : 17389
                     },
                     "end_location" : {
                        "lat" : 31.5674283,
                        "lng" : 48.2088389
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eHofal Rd\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by دهیاری هوفل شرقی (on the right in 20.9 km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_~m`Eg`edHpAK^OFCD?D?J?B?BA@?DAPSHGRQxCoBtEkDxGwG|CuCzJiJh@i@TYNQf@s@d@{@l@eA~H_NdLmSvCkFPYpK_S~IiPfIiOx@{A`EoHzBcErDmH|AaF|CmNdFoVzEmVjBsK`@cD@SBY@]AYEu@EeA[eHoAkRcC{ZAS@I@IDMFGJCRAbROD?bMSbMQfHKzLSxCFlA@XHTVJXTNv@h@fJtGn@\\b@VlAh@d@Nj@JvC\\xC\\tF`AfE~@TBp@BT?VI`@SZIPCh@DjCp@V@R?LATGPGl@KpAWXIJGLKHMPUR_@Xg@P]Ta@|@eBvAgCpAoCdBwDd@_AdFcL`BoDx@qBdB}Db@aA\\o@tBkDnIwMz@qAVa@hAcBXa@RY|@gAdA_BbEgGZc@Z[n@q@x@y@|AoAHGhB_Bt@q@bEmDLKrCiCJKbDyCr@q@BCdC}B`FsI|AiC`C}D\\i@`EaIZi@zFgKHOBEvAgClGcL`J_PzBqD|AoCJS~E{IHM@CJQtFkJpFwJHQJQ`KsO~@gBJWLYJ_@hAeGbC{Nn@wDJi@Jc@BEFSHSdCuFnAqCHUDI\\{@l@gAT[d@o@PSfAgAt@q@`@e@JQ^u@n@mABIdB_ErCuGTi@fAeCBILa@lC{H@ARk@\\eAXw@h@{AFQ^iA@CvBqGl@kBbEgMbEyMhJmY@EL_@dAeDh@eBBE@GDQNy@N{@H]Ha@Jk@TsAzBwM|@cF|@uEBKDSh@aDr@_Ef@eCBGDGFKDGHKHMVWPObBsAvAiA`CmBpC{BROtAiA|D_Dz@s@hI{GlRqOdDmCl@}@f@cAZ}@|@oENu@H[r@sDnAoG|@qEt@uDZ}Af@eCHWJWR]LOJKzAiArA_A~AkAnA}@~AiAvB{AxB_BHEnBwAtReNb@Yt@i@tFwDtB}AnA{@fBoArByAnA{@`BmAtAaAtAaA^UhA}@PQRSZWNQjAkA`C}B~@_AbB_B`AaAh@i@hDeDRS~C_DdLwK~F}FHIDMDS@E?G@OUcO@c@Ds@Fa@DYRq@Nc@`@s@`@s@l@u@n@o@`Aq@DC"
                     },
                     "start_location" : {
                        "lat" : 31.6977579,
                        "lng" : 48.036035
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "27.3 km",
                        "value" : 27256
                     },
                     "duration" : {
                        "text" : "5 hours 30 mins",
                        "value" : 19826
                     },
                     "end_location" : {
                        "lat" : 31.4809138,
                        "lng" : 48.4348989
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eHamidiyeh\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by مرقد المرحوم جاسم هیوری (on the right in 26.1 km)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mot_EgxfeHyCuAyAmAiXif@OOCC]OcAm@YYWi@?AAeA@g@DqA@Y@q@KiAOq@a@{@y@gB}@sA{@qAk@eAQu@Iq@Ku@MiB?IEkA@e@JmDFuAHiC?c@?u@AkACeBByCJqGBwCFeIF_RRiQh@ki@HmHXcD\\wD?IBuCBoBWsAMk@s@qDyBiGo@sAUg@cIcJ}KuNuBoCaBwBY]y[sc@]u@[q@[eBkA_Tg@uI@S?CBg@?G|B{GL]|Psa@`KiVdAk@zS}ANA|B_A@A|CmCzB_DT_@|@yBpCaHnD}IXkB@ETyCU{LCgAo@wTIyE?Sw@oDeB}HMk@i@uB@c@Bk@jAyDNi@f@aBjCsE~BeEtDsGdA{@t@m@lAaAdDqAXKVK@Ux@sJlB{EhFoMBGh@g@nd@yKh@g@RQd@m@x@eA`Qi\\T}@bEyb@RwBbA_CpEkEHGnGuDrOcJ|FiD@Ax@k@b@c@FG~@u@dAaAlAkAnAoA~@aATUhKiKhIyHzEqEv@u@xBuBRSjAeA|@sAz@mA|BeEvAuC`@w@nEeI`@w@nEwItIqPv@iAj@{@nPkSvBaClB_CjFiGDEx@eA`@g@~@wAbB{CBEhA{Bn@iABEf@s@`BiC~F}JxK}QrA{BlBaCxBoCv@aA|@cA|C_EtFyGfFsGrHiJvAaBf@k@HMPYZc@d@}@f@yAd@aB`@oApAmEd@oAh@sAZw@`C_HnGaPb@eAb@g@fBkBr@cBpAuCj@qApKcVhAoC|FqN^_AjD_JNkAf@eEGsAu@iUCgBVcARw@`@w@Ra@xHkOz@aE`EyRdC}FtI_ItIwNr@_ANS|CeElE_GrAqBhC}ArFeDhGsDHGlAiAtBoB@ClC{EnIgOXg@rBsDDU|@gEDQx@cEHa@R}@`@oB`@uBLm@P{@R}@Z_BDQBGBGz@sAd@k@LOd@k@JMxAgBLMHKXa@j@u@PGJ?^FLDLBJ@L?NAJCJEHIBE^m@fAcBn@cA`@q@`@q@BCh@iAd@cAlAmCx@eBJSx@iBZo@LYDI@K@K@M"
                     },
                     "start_location" : {
                        "lat" : 31.5674283,
                        "lng" : 48.2088389
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1200
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 907
                     },
                     "end_location" : {
                        "lat" : 31.474504,
                        "lng" : 48.4445383
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit\u003cdiv style=\"font-size:0.9em\"\u003eGo through 1 roundabout\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by فلافل فروشی ابو محمد (on the right in 180m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "urc_Ec}rfHBEDEBEBI@MHIFSDMb@qABEFQHQHOFKJOFKLQBEJOLOLQFOFOFOHSJW\\o@v@uA`@q@BG@C\\c@|A_Cn@eALQPWNQVQHCLAJAL?@BFBH@DADADCDGBGBK?M@MAOAKAQEOCMHOFQJQT_@Ta@~E{H`@m@DK@EDI@GHMFMfAgBlCiE"
                     },
                     "start_location" : {
                        "lat" : 31.4809138,
                        "lng" : 48.4348989
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2149
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1561
                     },
                     "end_location" : {
                        "lat" : 31.4621034,
                        "lng" : 48.46192019999999
                     },
                     "html_instructions" : "At سوپر مارکت الباجی, continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eHamidieh Rd\u003c/span\u003e‎\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sjb_EkytfH~@{AJOrD}F`DaFl@_AjCcElB{CBCR[HMpDyFxDcG`@o@NUjBuCfDgFdJqNNUnB{Cl@aAx@qAXa@~@_B~DiGxAaCnAqB"
                     },
                     "start_location" : {
                        "lat" : 31.474504,
                        "lng" : 48.4445383
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "20.8 km",
                        "value" : 20809
                     },
                     "duration" : {
                        "text" : "4 hours 12 mins",
                        "value" : 15132
                     },
                     "end_location" : {
                        "lat" : 31.3393623,
                        "lng" : 48.619778
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eجاده دهکده\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کافه seven7 (on the right in 18.8 km)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "c}__E_fxfHz@sAjFaI`A_BbA}AnAoBz@sAvEoHl@_AhDqFbEsG`KcPdA_B`FaILSNUlKmPj@}@rFwIfBqC~J{OfC}DnIuMnJcO`A{APYLSh@y@tGeKpG{JhAgBx@oAz@sALQdGmJFKNUv@mAV_@zEsHNS@AnAqBbBkCnOcVlHiLbCyDbF{H^k@p@eAnE_HXc@@CJOjFaIvAwBjBqCf@u@|@sAtBaDpAaB\\Y`@Y|AkAfBaAfLwG`JeFTMbLoGfAm@pDuBPKzA{@~CgBNGjEeCb@W~A_AfDoBZSrAo@VM~@[f@MNCFE`[uDzEm@pAOnEi@JArGw@h@Il@GlAOlEm@p@KxCg@zAWZGfA[p@U|Aq@TK`@Sf@]ZSVQv@q@r@m@b@c@^a@b@k@d@s@l@_Ab@s@NYjDkGHMxD_H`CiE`@u@hE_ILY|@aBlA{BvDuGpDmGh@}@dAgBnAwBrDsG~B{DfDsFnCyEbAcBvCcFzEkIdD_GdH}LlE{HlDoGb@w@zE{I|GsLbEkHzCoFfF}ITc@jJePlE_Il@eAdEwHDGlMiUZm@jDcGxEoIzCoFhDeGd@y@zGiLlE}H`@q@t@uAvByDpBqDDMxAuDd@qAzAkE|@cC`AoCtAwDFOdA{CFQvBwFr@oBVo@`B}DxCoHlBcF`@gAHUb@gAfBeEn@{Al@}AnAgEJ_@t@{CV}@Ps@Pw@Pw@`@gBBKf@wB`@mBP_AVyAt@{DHc@`AcEp@yCnBeIb@}ATk@d@_Ab@s@p@_Ax@}@vAqAr@q@zAqArAsAb@c@XYvA_BpB{BvEkFNOz@aAPSnBgB|CeD"
                     },
                     "start_location" : {
                        "lat" : 31.4621034,
                        "lng" : 48.46192019999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 31.3394023,
                        "lng" : 48.6199318
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_~g~Ds`wgHEMAO"
                     },
                     "start_location" : {
                        "lat" : 31.3393623,
                        "lng" : 48.619778
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1220
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 912
                     },
                     "end_location" : {
                        "lat" : 31.3343221,
                        "lng" : 48.6300965
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at Adel Paddy Machine\u003cdiv style=\"font-size:0.9em\"\u003eGo through 1 roundabout\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by دفتر برنج کوبی الماس (on the left in 210m)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "g~g~DqawgHx@}@nB{B`CmC`@e@jDuD|@_AxBcCrC}C|AcBx@oATm@Vy@AK@I?G@GBE@EBEHiAFy@?mBEqABcFEeCE[G]OWIQAE"
                     },
                     "start_location" : {
                        "lat" : 31.3394023,
                        "lng" : 48.6199318
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3204
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2431
                     },
                     "end_location" : {
                        "lat" : 31.3198382,
                        "lng" : 48.6572307
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e5th\u003c/b\u003e exit onto \u003cb\u003eEnghelab\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Keshavarzi Bank ATM (on the left in 20m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "o~f~DcaygHS?SCSCQIGCIEOKOOMOAEAC?AAC?ACE?ACQ?Q@]Ji@JOBEFIHGTKd@GTETKRONQXe@`D{HnC}GbFsLj@sATg@b@iAnBwEx@kBhAmCpAyCLYv@kBr@iB|CkHb@cAXm@z@mBZq@rAaDFSXq@zAqDjBmERe@Vo@HQXo@`CsFdBkEVk@j@sArDqIJQ`@gAh@mA`@aAb@iAZs@LWDQ@K?K?ODA@?B?@AB?LIDGDI@I@Er@q@Ze@Na@DCj@[|@]l@Sx@W"
                     },
                     "start_location" : {
                        "lat" : 31.3343221,
                        "lng" : 48.6300965
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 262
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 194
                     },
                     "end_location" : {
                        "lat" : 31.317655,
                        "lng" : 48.6582166
                     },
                     "html_instructions" : "At خانه, continue onto \u003cb\u003eRahnamaee Bridge\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_dd~Duj~gHj@OB?f@Od@ONG^Kd@Qt@Sn@Sp@Uf@Q^_@"
                     },
                     "start_location" : {
                        "lat" : 31.3198382,
                        "lng" : 48.6572307
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 296
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 31.3165975,
                        "lng" : 48.66106509999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e at کافی نت رهنما .نمایندگی رسمی همراه اول /\u003cwbr/\u003e ایرانسل/\u003cwbr/\u003e رایتل onto \u003cb\u003eEnghelab\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by پارکینگ (on the left)\u003c/div\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "kvc~D{p~gH?QJ_@Pg@Pi@Tw@Rq@XaAZ{@Rq@J_@DWZ}A@E"
                     },
                     "start_location" : {
                        "lat" : 31.317655,
                        "lng" : 48.6582166
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "70 m",
                        "value" : 70
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 31.3166972,
                        "lng" : 48.6616337
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eEnghelab\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Cafe Carina7 (on the left)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "woc~Dub_hHI?ECKKGS?CCU@QFUHI"
                     },
                     "start_location" : {
                        "lat" : 31.3165975,
                        "lng" : 48.66106509999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "57 m",
                        "value" : 57
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 31.3165734,
                        "lng" : 48.6621924
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e at Azerbaijani mosque to stay on \u003cb\u003eEnghelab\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "kpc~Def_hHX}@?q@"
                     },
                     "start_location" : {
                        "lat" : 31.3166972,
                        "lng" : 48.6616337
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 264
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 196
                     },
                     "end_location" : {
                        "lat" : 31.3176637,
                        "lng" : 48.6645177
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by كانون پرورشي كودكان و نوجوانان (on the left in 220m)\u003c/div\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "qoc~Dui_hHKc@k@eDm@gDO[[QgAq@"
                     },
                     "start_location" : {
                        "lat" : 31.3165734,
                        "lng" : 48.6621924
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 292
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 214
                     },
                     "end_location" : {
                        "lat" : 31.3165039,
                        "lng" : 48.6672776
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at اداره کل کانون پرورش فکری خوزستان onto \u003cb\u003eTakhte soleiman Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by دفتر اتباع خارجه استان خوزستان (on the left in 160m)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kvc~Dgx_hHFUFOHSh@aBtAqE@EbAgDBEBE"
                     },
                     "start_location" : {
                        "lat" : 31.3176637,
                        "lng" : 48.6645177
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 947
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 706
                     },
                     "end_location" : {
                        "lat" : 31.31181399999999,
                        "lng" : 48.675532
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e8th Bridge\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by the bridge (on the left in 500m)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "coc~Doi`hHTo@rAsD|@{BJUFO\\y@Tc@|@eBdAiB`AcB\\i@zAgClBmCf@s@FKh@cANYPYXu@Zu@\\eAXmA`@aB"
                     },
                     "start_location" : {
                        "lat" : 31.3165039,
                        "lng" : 48.6672776
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1211
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 932
                     },
                     "end_location" : {
                        "lat" : 31.3087475,
                        "lng" : 48.68774639999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eZand St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by چاپخانه شاخص اهواز (on the right in 40m)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "yqb~Da}ahHDO@GNaAPcATeBLq@NeATcBHk@PsAVaBVkBR}AX{BJu@BUf@gCTwAT}AXoBVsBReA`@sBZyBPcAReAHe@Ls@\\qB`@sANw@"
                     },
                     "start_location" : {
                        "lat" : 31.31181399999999,
                        "lng" : 48.675532
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 765
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 589
                     },
                     "end_location" : {
                        "lat" : 31.3062581,
                        "lng" : 48.69525489999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003e10 پاداد\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by فروشگاه آنلاین شکار (on the right in 56m)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "u~a~DmidhHBOF_@Tw@v@eD|@wDXmA|AyGVgAr@{Cf@uBv@yCt@yD"
                     },
                     "start_location" : {
                        "lat" : 31.3087475,
                        "lng" : 48.68774639999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 267
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 216
                     },
                     "end_location" : {
                        "lat" : 31.304258,
                        "lng" : 48.696363
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit\u003cdiv style=\"font-size:0.9em\"\u003ePass by مسجد جوادائمه (on the right in 60m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "coa~DixehHDCBA@A@A?ABA@C?A@C@A?A?A?A?A?A?A?A?A?A?A?AAENCJCFEFMHQHQDIJKHIDADAnBSzCo@D?"
                     },
                     "start_location" : {
                        "lat" : 31.3062581,
                        "lng" : 48.69525489999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 481
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 349
                     },
                     "end_location" : {
                        "lat" : 31.3052367,
                        "lng" : 48.7012921
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at بیمه ایران نمایندگی نادرزاده onto \u003cb\u003eShahid Dastghebe Blvd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کلینیک دامپزشکی دکتر عالی پور (on the right in 27m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sba~Dg_fhH_@yDEy@E]McBAMWwB?E[aCEYc@{CSwAUgA"
                     },
                     "start_location" : {
                        "lat" : 31.304258,
                        "lng" : 48.696363
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 312
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 230
                     },
                     "end_location" : {
                        "lat" : 31.3026348,
                        "lng" : 48.7025155
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at دفتر رسمی ازدواج شماره ۱۵۶ onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eكوچه توحيد\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wha~Da~fhHlAa@v@[bA]hAc@rAg@`DmA"
                     },
                     "start_location" : {
                        "lat" : 31.3052367,
                        "lng" : 48.7012921
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "38 m",
                        "value" : 38
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 31.3028291,
                        "lng" : 48.7028417
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at ساختمان کوروش 1",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mx`~DweghHg@_A"
                     },
                     "start_location" : {
                        "lat" : 31.3026348,
                        "lng" : 48.7025155
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1779
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1308
                     },
                     "end_location" : {
                        "lat" : 31.3093047,
                        "lng" : 48.7198752
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eJomhouri Hwy\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by the bridge (on the right in 270m)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "uy`~DwgghH?GCW?WE{@cAkCuAwDe@{Ae@yAs@iCyD}Nu@sCmBmHAGeAaEi@sBMe@iH{XkCiK[k@g@k@QU"
                     },
                     "start_location" : {
                        "lat" : 31.3028291,
                        "lng" : 48.7028417
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.0 km",
                        "value" : 2989
                     },
                     "duration" : {
                        "text" : "37 mins",
                        "value" : 2219
                     },
                     "end_location" : {
                        "lat" : 31.3014867,
                        "lng" : 48.7477044
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eبلوار فنی حرفه ای\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کارواش (on the right in 130m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "cbb~DgrjhHTARGLMLSDIDK~A_DfDuGXk@dAqB~@kBd@aApAiCFIp@_B@Cl@_BnAeERq@Pk@J_@Pq@n@}BLc@Ls@^mA`AiBDONc@\\oA^wAr@oCd@cBRu@^oAF]@U@}AFy@Ru@R{@\\sA|CwKXeAxCqLHYx@aDT_ABId@yBBIJk@RiABSVuBBWB[N}AHaBGqCUkBy@wCsBuDuBqCu@gA"
                     },
                     "start_location" : {
                        "lat" : 31.3093047,
                        "lng" : 48.7198752
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 926
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 695
                     },
                     "end_location" : {
                        "lat" : 31.3064768,
                        "lng" : 48.7546769
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eFani Herfehei Blvd\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by فروشگاه عرضه مستقیم کارخانه سوسیس کالباس (on the right in 140m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "iq`~Dc`phH?EAA?AAAAEEGEECCECGCMAG@mAmAs@}@}AiB_@UuDmEW[eEaFaCsCW]sBgCe@u@CCEIAGK_@GQAG?E?QHm@FUHQ`@aA"
                     },
                     "start_location" : {
                        "lat" : 31.3014867,
                        "lng" : 48.7477044
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.4 km",
                        "value" : 4411
                     },
                     "duration" : {
                        "text" : "53 mins",
                        "value" : 3209
                     },
                     "end_location" : {
                        "lat" : 31.2828887,
                        "lng" : 48.7918189
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eModares Expy\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by هایپرمارکت ادریس (on the right in 29m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "opa~DwkqhHvCsDT]HW@M@St@qBt@}A|@gBb@{@fGyKjGeLvGuLpKqRpAaCVc@pD}G`H{MdE_INWbDiG~AqCxBwCnE{GzGyJjAeBfCoDvEeHzAoBf@o@hBsC\\m@~@cBjBgDlAsCxBwEd@qA|CoIdC}Gp@cC"
                     },
                     "start_location" : {
                        "lat" : 31.3064768,
                        "lng" : 48.7546769
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "77.4 km",
                        "value" : 77373
                     },
                     "duration" : {
                        "text" : "15 hours 35 mins",
                        "value" : 56077
                     },
                     "end_location" : {
                        "lat" : 30.9980615,
                        "lng" : 49.4624326
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAhvaz-Omidieh Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 86\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Route 86\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by IRAN DRILLERS (on the left in 2.8 km)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "a}|}D{sxhHf@qAX{@DQ`AkENaANiA^yBDq@LcCNiE?sFQqFOoB?AMsAEm@}@yGAMsCaQsAsHG]aCyNMs@[oBs@mEUaCQsCCoD?U@{@BcBBWLuBJm@TqAl@sDpAaG|@}DnAsFlFkVHYNu@fBcIbAmEpAcFf@eBx@wCd@wA`@iBb@kB`@cChCaKnCkKv@mDl@eDBMd@mC\\yBp@{EzA}JfAyH?Cb@sCRoAnDgVdA}GlDkUlBiMdBiLxC}Rz@aFfB}HBIjAcEx@_CfAoC~AsDtDoI`AiC|@_CpAqEbBwGfFcR|B{IjAiEnBeHnBgH~DoOzC_LxLed@DMbD_MpBkHvC{KbBmFjCyGfCoG|BeGtAcDnCcGhEgH`BwB~AuB|OyTd@u@bBkCn@{AlAsCfByHl@iET_EHoDAiE_@aLeBuXiBo]k@iKMwE@aADgC\\}Hv@iNLkBFmArFs`A^qIPcKMgIY}GeAyLaFyk@}@eMm@wM?Y?_FFaJ@a@x@sKjEqd@v@mIhAgLzAkOpCgYt@iKTmL`@wX?MJaGXy[PeRn@on@^o`@r@cm@d@k_@ViSb@wb@LsKjAw}@n@oi@@u@j@cc@T}PK_MEsD[cYIuF@eGLcH\\oQd@{UVcGfAqIz@sD^iA`A{CvA}CFMfA}BlAeDn@gC`AgFTiCJqF@GAsHOeYGqJMsc@OuYAeDC}DKwNCoJA}CBaD?S@e@Z{Ed@}Eb@oDb@mBh@_CF_@BOTkAlAuGZaB@EhCmMp@kD@G`@uB`E}StWyqA`@wBdOew@fHy\\pBoJz@_EJi@j@}BTcAFQb@uAd@}AtAiD`AeCdAuBhA{BrDiHn@gA\\{@rBeF@GrCoIpA}DrCmJTw@bAgD`@uApB_HbCiIrBeFnAuCvCeFR]xFqIfHiKT_@pFcInFsIbBkCpF}ItBwDjBuC|B}DlI_QbKuSBEpCyEbAoAbA{AfByBdCoCbCiCdCkCnAqAv@y@zCcDxFeGRSpKcLtC{ClBuBpB}BvCiDlCaDlC_DvDiEnEeFxHaJrDiE|BkCvFwGxFwG?AvA}AtAuA~AaBr@q@`@c@xFaHdAoAtAiBnBcCz@iAz@iAj@y@\\e@`A}AJSTe@Ve@Vo@`@eARm@^eAV{@\\}A\\aBNgAVaCBUJyAD_AFgC?iA@a@JkDD{AFsATyENqGFaD@{@DcC@}A?_@?wABoADmBBu@ByA@k@DuADeABa@HcADg@Fc@TaBTuAH[@KJ_@H[FQPk@Pm@Tq@l@_BXo@Vm@x@wA^o@Zg@lBkCpX{[fByBfW}YfCgDnA}A~F_HfOoQrKcMfJ}Kp@w@hD}DvBwBd@k@~@iA`CqChBwBh@q@|@iArAaBnHuHpCuCfAoA|@iA\\i@Zi@l@u@~CiDzCcDjNwN~CgDhMyMjBoBxB}BhAiAv@{@bBcBdCiCjFwFr@u@rBuBjGuGt@w@|FiG`GaGdFsFhCmCfAeAtBgClCsCxLcMlCqCnQaQ|EaF~ByB|AcBxByBrDgDnAsAzA}AhEqDnAqArCqClAoAtDsElWu[v@cAf\\{a@b^me@bHcJ|SsXn@y@vI}KhCeDnImLfK{Mv@cAjGeIrU{Z|EqGLOnD{E|JsO~C{FZk@pC_H@AvEqK|DmInG{I~EkFdDqErF_JT]`EeIjFeMdFsI`DgDxBeBdEoBxEyAhC_@b@GbEm@rDGfIs@tI{@zIuAlHiBnGkBlDyAhIgFrEyCd@YtEiCxDqAdDi@tI?xLtClChAPHfFxBjFz@vG?bAU`FkAnAq@~EkCrNcI|@i@jBeAhN}Hpx@eb@~L}GjGcDvDmCpDmEjCmEx@sBf@yArAqEbBiKxP_lArDkWh@cFL}BDsAFuBFwA@}HCwAGcDAa@SwCKwAcAyKAUgBuNMw@w@}FeAuHEe@c@}D_@cFEuD@SFmANgALy@F[Nq@j@}AZq@p@yAb@q@T_@LUtAaBbJwK~GeInP}R|@iAt@aAzAoBV[PSv@eAzNcRfJcMbEyF"
                     },
                     "start_location" : {
                        "lat" : 31.2828887,
                        "lng" : 48.7918189
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 941
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 693
                     },
                     "end_location" : {
                        "lat" : 30.9902572,
                        "lng" : 49.4645479
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRoute 43\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{he|Des{lH^WpAwAZ[bA}@rBuAhAq@RGxB}@zBk@PEnDk@tBOpCGVGjCPxAVnAXjA^XH"
                     },
                     "start_location" : {
                        "lat" : 30.9980615,
                        "lng" : 49.4624326
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1280
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 942
                     },
                     "end_location" : {
                        "lat" : 30.9952567,
                        "lng" : 49.46849109999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cxc|Dm`|lHrA}C|BiDvAeDAuDRk@Lm@uDgDkCaCUN{An@{A[eMyAwCvByA~AiBpB"
                     },
                     "start_location" : {
                        "lat" : 30.9902572,
                        "lng" : 49.4645479
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "9.4 km",
                        "value" : 9449
                     },
                     "duration" : {
                        "text" : "1 hour 54 mins",
                        "value" : 6842
                     },
                     "end_location" : {
                        "lat" : 30.947192,
                        "lng" : 49.5470564
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAhvaz-Omidieh Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 86\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kwd|Day|lHQyCk@yLOyCWaG[iIKaCCu@Ai@Ak@@i@?M?SD{@Di@Di@Ly@@CHk@Ns@Ru@Tu@Tm@Ra@Vi@~@}Ax@mAR]lAkBrAqBlC}DtAwBhBoC`CoD~AcCvA}BbBiCdAcBlCeE|AcCp@eAb@q@rAoBjCeE`BgC`A{AxAwB^o@fBsC`BgCrAuBj@y@NUzCyE`BiCbBmCxAaClAmBf@u@d@s@z@wAfAeBp@gAr@mA~@sAtA}BtAuBLQnAsBhAgBv@oArAeBp@gAh@y@hBwCpB_DjAkBtAwBbA_B^m@|AgCvCoE`AcBlB}CnAyBl@_A^k@z@uAxAyBXa@fBoCn@iA~A{Cv@kA|AeCdBoCBEvA{B`BiCrAqB~@wAvEmHbEqG~@yAhBqCVa@lB{CVa@pB}Cp@eAlAgBvBkDhAcB|BqDfC{DbCyDT]b@u@v@iAZa@X]v@y@RQ@A^]fB}A`A}@z@{@ZYV[^e@~@{AVc@Zq@`@eAfA_C\\{@z@oBt@eBHO~@{BdA{BXq@Vc@b@o@n@eAjAqBnAmBz@sArDcG~AcC`CwDpAqBf@w@rAyBpBiD"
                     },
                     "start_location" : {
                        "lat" : 30.9952567,
                        "lng" : 49.46849109999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.1 km",
                        "value" : 3109
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2271
                     },
                     "end_location" : {
                        "lat" : 30.9264516,
                        "lng" : 49.5676287
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}j{{DcdlmH~@W~@]XKxAg@bBi@zBs@pC{@nC_Ad@O|@YDCv@Yd@Uf@UVO`@[n@g@t@{@nB}Bp@w@X]pDoENS`FcGtCmDvCoDhB{BrBaCn@w@bBqBf@g@n@o@DCh@g@x@u@vCeCbByArFsEt@o@ROdA_Av@o@xAoAvBiBl@i@b@c@b@a@`@e@V[Ze@@An@_Aj@aAV_@BEJGHEHE@CDCBABCDE@CR]Rc@P]FKNc@Pc@Rw@Lm@Ps@H]Jm@Hk@Ja@F_@DYFe@DUBS?O"
                     },
                     "start_location" : {
                        "lat" : 30.947192,
                        "lng" : 49.5470564
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "21.6 km",
                        "value" : 21591
                     },
                     "duration" : {
                        "text" : "4 hours 20 mins",
                        "value" : 15614
                     },
                     "end_location" : {
                        "lat" : 30.7812714,
                        "lng" : 49.7052759
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAhvaz-Omidieh Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 86\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by پلیس راه امیدیه (on the right in 8.4 km)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "iiw{DudpmHBGPk@XsAfAaGTiAPgAjEaV\\oBVuAT_APq@Ts@P_@b@s@R[^g@FGtAwA|AaBvA{AvC_D|CiD|CaD^a@tAyApAqAp@s@`@c@Zc@Xc@p@wA\\u@h@sAfAkCbBwD|@sB^y@d@eAdA_Cd@cA`@cAXw@z@cC`@kAd@oAz@yBr@cBTi@h@sAh@mAd@y@P]^g@TU`@_@VQNKnAi@dAa@BAv@YlGcCvBu@hByAzKsIbGiErB_BvDsCrEmEpBgBfNoN|CqDbM}NfDuEtCiCFExA{@hOgHPQh@e@xD}DfJgKh@m@xDaExB}BJQjMgQ|AsBFGl@q@`As@f@YdAe@|A_@|AUnBYb@ITCv@]`Ag@x@k@pDoCdCsBn@gAf@kAH[Ne@FQV_BZsCf@uEBKTsAReAd@cAv@sA|J{OnAqB|@gArAiArGqEbAYfCm@rA[|Bi@~Ag@zAiApCwBd@c@xGwChCwAhCsCdBkBbAwA~EgHpCiFbA}A`DyBZU~AgA~FeE`DwBxBaBlCoDlPkUb@i@lDsEfEmFjAyC|FaKrLwS|CwEd@y@bAgBj@m@XYVWbMoK`JqGhB{Av@k@vGwEdDgCt@m@t@w@Za@^c@zB{CnCeDfGaHnCcCbBeB|AqBrBkC~AyB|CcERW~AeBhHgIpA}AjAwAV[bCyD`AsBzCoGxBgFhA_CTe@|@gA|@s@l@OpA]|C{@^Qn@[pAu@zB{AbF_DbEkCpA{@bCoBzA_BjAuAdCaDbFqGjDoErE_GvEwGjAwAjAmAjAk@hCeAjAW|Cs@~AUbCS@?jB@bB?tC@tAElCY~BQj@G|@Q|Ai@zCiAVK^OjHqC`K{DJEhB}@jCgAjAs@j@]hB{A`TeP\\WdCmBtBwAdAi@zAY|Ba@tTyDn@KZGnB[fBYLCtIwAbKoBtLkCbJaB"
                     },
                     "start_location" : {
                        "lat" : 30.9264516,
                        "lng" : 49.5676287
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 4004
                     },
                     "duration" : {
                        "text" : "50 mins",
                        "value" : 2994
                     },
                     "end_location" : {
                        "lat" : 30.75061479999999,
                        "lng" : 49.724206
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eImam Khomeini Blvd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by اتو سرویس رهیده (on the left in 1.1 km)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "}}zzD_aknHAM@QDYFQPWJIJEJAJCJAL@LBJBJHHFDHX@TKdCcAv@UpBk@v@SpBg@jC]JCF?~AUhCc@xBa@NClGy@tBYtE{@~@OhBY~@c@v@_@t@[\\M`CgBl@m@?I?IDMBIBEBCDCDCBADAHAF?D@F?l@UTKrA{@rCqB~FgErDmCDCzC{BbXaRNK~AmAhAy@JKfCgCLUJUHc@AECI?M?E@EBMBKNWRUFEDABAB?FAD?F?f@[^YVYT]RUpAeBvFwGRUj@m@~@w@bCkBfAm@jAo@`CeAdCw@JCv@STEvAY~AMtAQTGNA"
                     },
                     "start_location" : {
                        "lat" : 30.7812714,
                        "lng" : 49.7052759
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 731
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 540
                     },
                     "end_location" : {
                        "lat" : 30.7442339,
                        "lng" : 49.7255333
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit onto \u003cb\u003ePersian Gulf Blvd\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "i~tzDiwnnH@G@E@C@A@C@A@CBA@AB?@ABAB?B?@?B?B@@?B@@@B@@@DB^?hAM`JiAd@GzBYbI{@HC`Fo@XE"
                     },
                     "start_location" : {
                        "lat" : 30.75061479999999,
                        "lng" : 49.724206
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 97
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 83
                     },
                     "end_location" : {
                        "lat" : 30.7444987,
                        "lng" : 49.7264978
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mvszDq_onHu@aE"
                     },
                     "start_location" : {
                        "lat" : 30.7442339,
                        "lng" : 49.7255333
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1016
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 729
                     },
                     "end_location" : {
                        "lat" : 30.7359231,
                        "lng" : 49.729638
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by دبیرستان نمونه دولتی دوره دوم علامه طباطبایی (on the right in 700m)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cxszDseonHbCy@DA`Cc@lBQbAKt@OfBMdC]lFaAbC]rCm@xA_@RIFCJG~@m@x@i@|@k@v@k@POPCJCJENKHIBI?G"
                     },
                     "start_location" : {
                        "lat" : 30.7444987,
                        "lng" : 49.7264978
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "37 m",
                        "value" : 37
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 30.735664,
                        "lng" : 49.72943919999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "obrzDgyonHXDX`@"
                     },
                     "start_location" : {
                        "lat" : 30.7359231,
                        "lng" : 49.729638
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "75 m",
                        "value" : 75
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 30.73503819999999,
                        "lng" : 49.7297422
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{`rzD_xonHzB{@"
                     },
                     "start_location" : {
                        "lat" : 30.735664,
                        "lng" : 49.72943919999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 231
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 166
                     },
                     "end_location" : {
                        "lat" : 30.7339975,
                        "lng" : 49.7276548
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by قالیشویی یکتا (on the left in 130m)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_}qzD{yonHnBbEP\\n@tB\\hA"
                     },
                     "start_location" : {
                        "lat" : 30.73503819999999,
                        "lng" : 49.7297422
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "23.5 km",
                        "value" : 23472
                     },
                     "duration" : {
                        "text" : "4 hours 45 mins",
                        "value" : 17088
                     },
                     "end_location" : {
                        "lat" : 30.5863146,
                        "lng" : 49.8974776
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOmidieh - Aghajari\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 86\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Route 86\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by فروشگاه اورجینال (طیبی)بلبرینگ تسمه (on the left in 5.8 km)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ovqzDylonHjFq@d@GnDc@bC[dFo@dC]lASzAYfAYFArAa@x@Wz@Yh@SrAk@NGp@[f@Ur@_@j@]\\U|AcAZS|@o@tAiAh@g@BCdA_A\\_@fAkAdE}ExAiBvAeBdEeFnFsGp@y@pCgDhC}C~AoBpBqCbB}Bv@eAdAyA\\e@zAqBbCeD`FsG~CeEx@gAvEyG`GaJbD}EhEuGtCoEtCgEVa@bDaFbD}EdC}Dp@cAhD_GjD{F`CcEJObBaCnDcF|BcDxCcEnAcBz@gAjAyAjBuBlBsB\\a@X[jBkBdEwDlFuE`EmDt@m@\\[bCuBjHkG`I}GdGiFtAoAv@u@pD_D`EiDtBgBx@o@l@e@VStFsD\\Od@_@fJ_IzFaFrBeBxAsA`AcA|@aAh@o@x@_AvAkBdA{Ab@m@l@aAz@wA`@s@l@iAr@wA|@aB`@}@Zm@f@aAb@}@tAiCvAsCb@}@Zm@hBqDBGlBsDfBkD~FgLxEmJzAyCHOrEaJz@aBz@_BR]N[f@mAv@}AtAoCbBcDhAwBTc@R_@\\k@j@_Ah@y@b@q@h@u@h@s@p@{@|AmBl@m@x@_A`@a@n@m@v@q@z@w@j@g@fA{@rBcBvAkAnAeA`A{@hGsEjSgQbNoLXWrPwNnHkH^Yx@q@dByAjGcIfEyFlCqDnHeKhIgLdBaC`EwFxQaWfA{AjLcPlIoLfJmM|JmNbBaC`IiLxHoJrAcBlEsE`@c@`EeEhKoKtK{KdBgBfGkGrCwChKqKdF}EzGcHxH{HbDcD|D}DrNuNdLoL|DaErEwE`M}LbBeB|DaExFaG`EwDvBqCtCkD|B{DnCoF`CcJjBkG@At@cE`Hi_@nCeOd@sB"
                     },
                     "start_location" : {
                        "lat" : 30.7339975,
                        "lng" : 49.7276548
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "55.1 km",
                        "value" : 55101
                     },
                     "duration" : {
                        "text" : "11 hours 12 mins",
                        "value" : 40298
                     },
                     "end_location" : {
                        "lat" : 30.236286,
                        "lng" : 50.1873064
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by جاده دیلم امیدیه (on the right in 55 km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m{tyDgrpoHlGfB^JnFbBbT|GfCv@lDhAZJvBp@z@VVHzEzAvC~@fCx@dCv@lGpB@?hEtAF@dEdA`MxCrFpAzMtDfCr@pGhBpHrBlD`ArMrDdBd@bCp@~NbEhHpBvEpA`Bd@tH|B~StGTFpIjCv@V@?j@PdF|AfDdAhErAlF~At@T`JnCbAZfCt@dBh@jEpAbAZj@Px@TbAX`D|@`IvBdAZt@HnANlEh@pJQzA]dGyAhDmB|@g@DCpBaAl[mOrJuEpKgF|OwHnIaEzEoCj^mSrF}CbDkBxDyB`CmA|F}Cz@e@hBe@hFqAdDe@|\\{EvBWvFq@lAOnFo@tFq@rGcBlEkAzKsCt@ShVgGvPiEnNoD~HqBrO_Gt@a@fDgBxCeCbAy@pXgUbA{@fCuB`BaBtEuEdEkDxBuCxBwBtJgLfFgGz@cApBiCbC_DnA_BtE_Er@m@rAiArAiAd@a@\\[hDcEpEsFpDmEpFwGd@k@rDkEfD}D~@gAtH}IzKqMh@o@rEiERQzAwAbCeBfCgBjFkDpGgEfAs@hFkDrA{@`BgAlIsF|@k@tA}@DElD}BlJiGLIn@a@zGiErFmDnK{G`HmEdFcDtFmDzO_KdC_BbAq@tA{@tDcCvDcCbQaLvDcC|@k@hG{DrHwEhQ}KrGaEh\\iTxE}CvDeC|ByAxA{@|GyDxBmADC\\c@p@w@pA_BLy@j@{DT{AFg@`DuGjAeC|EyJjBoCrDmFbHcKtAsBtB{ClBqC~A_ChEkGpAkBjC{D~A_CdA{AdD{EvAsBFI~@sAtB{C`@m@hCuDPWrFaIPSfDmDnAqA`@m@`CoDj@mBX_A|@wCxC_FVa@fLuXhEiKdDaIv@mBhAkC~@{BpAaDZu@|EwIJMRUbBuBNQ~\\eYrD{Cn@k@tH{GhD}CtKuJBCnCwDt@aClCqIl@oBBIr@{Bd@{AzBkHPi@RgBhAkDNi@v@gC`A_DfBmFnBuG`A_DxAwEdC{HFWfAyD`@eBBMBOXqBh@sB|BgSz@kHrAuL`AwIfB_PL}@b@gDDo@tEca@nAuKpA_MnAcLb@}DZgCFm@PsAd@kEfBoO~@eIxBqRFg@tCgWl@oFn@sFt@qG`@eDdAqJX{BtAkLXaCt@gHr@qGNoA\\qCjE_^pAcK?Gn@qDl@{CJy@ZkCRsDFwA@q@BQFaAJiAJm@Js@\\sAd@yANg@r@aCPk@bB{F`KgYd@uAnDyLf@gBRo@Ni@N{ABY~BsVBU~@cIz@oH`AiIF]R_Al@iETiBTaApAwF`BoGnA_FjAwEjCaKbCqJnAaFjBqGdB_G|DiMn@wBrB}GvEoO~CgKr@}BbByFxAuEd@oAl@kAnAsBxAmB~@oAtAiB^c@d@o@pWc]hDsEtD_F`DcEZ[nAeAtBaBvCeCfDaCpByAp@g@ZUNKz@o@\\S`@UvAq@`G{BnCmA`Bs@bDwALE~@_@`B]RCzCc@lAQXGb@ILClHuAdFcAXKNGZODEx@}@j@mAFMf@aBHW^oABGVe@`@i@JKDIHItAmAxBoBp@c@FCXMHEVADAnC?dBCh@?xCBz@P~@b@x@d@\\LhAHX@tBGj@Ox@_@v@q@DE^Y`@_@XM`@G~@BXFBB`@X`B`BbAt@NJhAx@JHZb@HV@V?NATGTOr@A\\?TDZHZPTp@|@T\\|AtB^\\XX@@\\PJ@N?PEZUPYT_@bAaBp@gAVWVS^ObAOpC]b@MZKfBq@`Bw@`EmBBCv@[d@SFCdDu@`Ci@lBg@ZItEgADANEhEiAp@UDCzBcALIpAm@`EmBXMx@[p@QTGj@Q@?pCqAp@SdBi@dCo@jBe@lA[fCo@bD{@j@OvAg@`@ULIvAuAHGb@[XMNGj@GfGCjC@l@?L@jABF@l@HVFpAZTHdCv@dBh@z@VFB~A^f@DB?b@?b@?\\Av@Kj@Of@Uf@Wn@UJCdAUjB_@nA[bAW`Du@pAWfB[d@KhEs@tAUx@WJCt@_@\\OzAeAz@k@f@[v@]TKlAa@`@KhCo@fBa@zA_@pAUzDu@x@KnDe@VCn@GvAKPENC\\MlA_AvAgABC~@y@v@w@tAaBz@y@t@i@j@g@f@q@^s@Zs@LU^i@|@mA|BaD\\c@X]tCsDf@q@rBwB\\a@\\Sp@Sn@W"
                     },
                     "start_location" : {
                        "lat" : 30.5863146,
                        "lng" : 49.8974776
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "14.2 km",
                        "value" : 14213
                     },
                     "duration" : {
                        "text" : "2 hours 49 mins",
                        "value" : 10111
                     },
                     "end_location" : {
                        "lat" : 30.1174079,
                        "lng" : 50.1713828
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBehbahan-Bandar Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 45\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کافه درویش، بندر دیلم (on the right in 230m)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "yopwDueiqHpBT~Gt@\\FvDf@|IdApDb@fANhB?fAMvAOhEo@Z@`AB|ANt@P`NzCb@L`@L`@L|@@pJWfACtCI~@?pA?XDt@Ld@f@BBb@|ALrAE`BCh@?TKhCBrBZj@T^bAf@dALhBMr@Rn@l@p@nAN`AB\\NdBNfAJXLf@^N\\Nx@HP?nC@hANv@Ln@NdAm@j@UjACF@b@BL?t@l@Hn@?DAf@IfA?dA?f@NvAZdAjAdAfAr@\\Td@XnAV~@F~@^fCvAjBn@dANDAjAK|Ae@BAhBYnIwAvAWzI{AdK{AjC_@jLgBTE`Fu@rF{@dK}AtF{@rZuE`AOxUqDj@KpUwD~F}A`Ck@jBUtBCbDRpPrAnSjAtCVjBN`R|A^DD?nIj@xF^dMx@lALhIz@hDXjGh@zFJrEOfFg@~PuChDUtD\\|Bd@tEvBre@jR`Ab@^NzGtChF`BrCj@pD\\xPzAxEf@`@Dfe@~E|MrAd^rD`@DlCX\\B"
                     },
                     "start_location" : {
                        "lat" : 30.236286,
                        "lng" : 50.1873064
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 4008
                     },
                     "duration" : {
                        "text" : "49 mins",
                        "value" : 2928
                     },
                     "end_location" : {
                        "lat" : 30.0817244,
                        "lng" : 50.1659671
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eBehbahan-Bandar Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 45\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "yhyvDcbfqHFEFABAD?FARBx@F|@FxOvAxHx@xRnBbNpAjBRtKfAp`@`Ej`@zDdUrBjEn@nBXlCZnAFfAFtA@rIPXAjJB~B@hA@"
                     },
                     "start_location" : {
                        "lat" : 30.1174079,
                        "lng" : 50.1713828
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2178
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1587
                     },
                     "end_location" : {
                        "lat" : 30.06214859999999,
                        "lng" : 50.1653721
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRoute 96\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wirvDi`eqHrHHnEFlC@`EDjJJjLFzIFzHFnEFxAB`IJjIFdHJbEDbDF"
                     },
                     "start_location" : {
                        "lat" : 30.0817244,
                        "lng" : 50.1659671
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 107
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 30.0620925,
                        "lng" : 50.1664807
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "monvDq|dqH@oB?w@@WF]"
                     },
                     "start_location" : {
                        "lat" : 30.06214859999999,
                        "lng" : 50.1653721
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 139
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 103
                     },
                     "end_location" : {
                        "lat" : 30.0608402,
                        "lng" : 50.16646679999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by چمن مصنوعی (on the left in 50m)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "aonvDoceqHr@BpA?rBA"
                     },
                     "start_location" : {
                        "lat" : 30.0620925,
                        "lng" : 50.1664807
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "88 m",
                        "value" : 88
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 65
                     },
                     "end_location" : {
                        "lat" : 30.0607759,
                        "lng" : 50.1673787
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ggnvDmceqHJuD"
                     },
                     "start_location" : {
                        "lat" : 30.0608402,
                        "lng" : 50.16646679999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "77 m",
                        "value" : 77
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 30.0600874,
                        "lng" : 50.1672957
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by ستاد اسکان فرهنگیان بندر دیلم (on the right in 34m)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{fnvDcieqHL@J@X@tAH"
                     },
                     "start_location" : {
                        "lat" : 30.0607759,
                        "lng" : 50.1673787
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 517
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 373
                     },
                     "end_location" : {
                        "lat" : 30.059585,
                        "lng" : 50.17263639999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qbnvDsheqH@GRqD@UHoCJmCLcDPuCVcG"
                     },
                     "start_location" : {
                        "lat" : 30.0600874,
                        "lng" : 50.1672957
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "62 m",
                        "value" : 62
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 30.0590285,
                        "lng" : 50.1725864
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k_nvD_jfqHlBH"
                     },
                     "start_location" : {
                        "lat" : 30.059585,
                        "lng" : 50.17263639999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "58 m",
                        "value" : 58
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 30.0589725,
                        "lng" : 50.17318540000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}{mvDuifqHJwB"
                     },
                     "start_location" : {
                        "lat" : 30.0590285,
                        "lng" : 50.1725864
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "63 m",
                        "value" : 63
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 30.0584053,
                        "lng" : 50.1731331
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "q{mvDmmfqHnBJ"
                     },
                     "start_location" : {
                        "lat" : 30.0589725,
                        "lng" : 50.17318540000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 363
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 267
                     },
                     "end_location" : {
                        "lat" : 30.0566645,
                        "lng" : 50.1754733
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کارخانه یخ سازی عربزاده (on the right in 250m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "axmvDamfqHBe@NcFLaB@IDGDEBAVIREZGxAY~A[F?FAF?N@"
                     },
                     "start_location" : {
                        "lat" : 30.0584053,
                        "lng" : 50.1731331
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.6 km",
                        "value" : 5649
                     },
                     "duration" : {
                        "text" : "1 hour 9 mins",
                        "value" : 4123
                     },
                     "end_location" : {
                        "lat" : 30.009249,
                        "lng" : 50.19579539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cmmvDu{fqHf@kA`AoAlBmATOv@i@BGDGBEDEFEDEDCFCFCFAHAFAF?F@H?F@~@C^Cp@Mp@UzAk@jBq@h@S~@]hAa@|Ak@jBs@^Ox@[`Bm@jBm@bBe@`Be@ZKLENCRAFA|DmAjFcBrEsA`Bi@bBg@~GwBhF_BnKcDtBo@~Ag@pAa@lBk@hA]nBm@~Ag@lA_@z@YhA]fA[l@SrAc@dA[zBs@nEqAzBq@`Cu@jDgA`oB{l@vLsD"
                     },
                     "start_location" : {
                        "lat" : 30.0566645,
                        "lng" : 50.1754733
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "34.2 km",
                        "value" : 34245
                     },
                     "duration" : {
                        "text" : "6 hours 53 mins",
                        "value" : 24763
                     },
                     "end_location" : {
                        "lat" : 29.7364951,
                        "lng" : 50.3397493
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGenaveh - Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "yddvDwzjqHJIHEFAf@OtAa@vC}@pC}@fBi@pBm@pA_@|Ag@rAa@zBq@vBq@`Cu@zBq@bBi@jA]`Cu@|Bs@~Bu@nBm@vBq@jA]fCy@vAa@tBq@vAa@hBk@tAa@vBo@rAa@r@Wv@[ZMj@Wh@Yh@a@z@q@n@m@p@o@j@o@b@e@d@k@bAmAvAgBpAcBzAiBrAcBlA}AtAcBhAuAvAiBnB}BbAoAjAyAJKnL}NxCsDnBaChAwAfAsAv@cAlAyAlCgDhB}BdBwB|AoBnBaCr@}@r@}@X[f@k@d@m@l@u@b@i@p@{@`@g@\\a@l@s@p@{@l@w@h@q@|@aAd@g@t@u@\\a@^[ZY`@[`@[b@Yd@[j@Yb@Uf@Uv@YhA_@vA[jAYz@S`Ci@fAY~@UxA_@rAY|A_@tD{@vBi@~@Sv@Sd@Kr@Oh@K`AWxA]~Bk@`@KxA[`B_@t@Sf@Kn@M`AW|A[`Bc@zA[bAWdBa@fAWz@Qv@Qf@MtAU\\G\\Ej@EvACfACnACnLEfA?pBAz@?vBCdC@lCCbC?zBAjBArA?lAAp@?X?nC?dBAhA?pAAnBEpA?jB@pAAhBCxA?bC?bBAxBAxBC|@?t@Ar@Ez@Iv@I~@Qn@M~@S~Aa@hAWtA]lAYrA]~@UfAYnBg@bBc@lBe@~Ac@rA[pA[|A_@rA]tA]rA]~Bm@hAYtGcBjEgA|Cw@~Cw@hDy@tDaAzCw@vCu@nSgFhCq@|Bk@zA_@nBg@`RsE~@WtA_@nA[|Aa@|@SXMv@WbA]fAg@b@Q`Bs@lDaBrDgB|As@~As@d@U|@a@bFcC~@c@`CgA`Bu@~Au@bF_C~@c@`D{A`F_C~BiA~@c@`EkB`DyAjHiD`Bu@|Aw@\\Oj@WnB}@nAm@~BeAfAi@rAm@bBw@`Ae@x@_@dAg@|@c@l@Yd@U`@W\\WXURO\\Sj@g@p@g@p@k@`@Yj@a@l@_@l@]lBaAvAm@vIaEhBy@xCuANGn@[^S`JeEr\\oOxf@iUjDaBhFaCnEsBfCmAz@a@pCoAXMRKZKd@Ol@OlBc@nA[zCk@`@GhC_@tVuE`Ba@`AUfB_@nCg@z@OlF_AfHqAdEu@hE}@dIgBrSwEfBa@zBg@|Ac@d@QnCmAdEmB^Q~@c@bHcDzG{ChD_B~BgAxAq@t@a@XQ^YfCkBbFuDzEoDlCqB`@[tB{AhAy@~AkAtCwBh@a@`@Ux@g@`@O^Kb@Kt@Kj@Gv@ErB?@@`A?tB?lB?v@A`CApBCx@ApAAr@?j@?t@?j@ArAQ|Bc@pA[bDm@|AW|A]FAXElDk@tBY|C_@pC_@l@I|EgAfCk@jAS\\CbAKhA@lCFlHDlEBpA@N@|CBh@?rDBb@?p@@x@?v@?nCDt@@x@CpAKv@Kn@OVGr@UhHkDpB_A`EmBvHuDhD_BfCiA~GaD|GcDjEsBtAs@XOzFmClAk@bEoB|HuD@A~GeD`@S~DkBf@Un@Wn@UZK|@WpDcArHuB`AWlDaAt@Sj@Wz@i@j@a@POPQZa@V]Xg@LWL[Pc@d@yA@CnAyDt@yBjAmD?CfAcD^y@f@y@z@eAh@k@lCcCf@e@fGmFvDeDpAgA|FcFnE}DzDaDlJyH~HsGtEyDxD{CtHkGvFsExFwE|DaDdA{@dBwA|FuErFqE~DcDtEsDfByAbEgDfEkDfA}@dH_GzFuEZWLKnGgFzAmAlDwClEqDzAoAhDqCn@g@p@g@rAgAxAoADE~AwA~CyCvBoBvD}CvEwDt@k@dBaAtEcCpBkApCeBhAs@hAy@"
                     },
                     "start_location" : {
                        "lat" : 30.009249,
                        "lng" : 50.19579539999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 98
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 79
                     },
                     "end_location" : {
                        "lat" : 29.7362569,
                        "lng" : 50.3391075
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eGenaveh - Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "c|ntDm~frHRCRBPHLRDRAZKTOZ"
                     },
                     "start_location" : {
                        "lat" : 29.7364951,
                        "lng" : 50.3397493
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "10.7 km",
                        "value" : 10663
                     },
                     "duration" : {
                        "text" : "2 hours 9 mins",
                        "value" : 7717
                     },
                     "end_location" : {
                        "lat" : 29.6638286,
                        "lng" : 50.41005939999999
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGenaveh - Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "szntDmzfrHVO|GiFROnDmC`BqAxEoDlA{@vAeA\\WnEaDvB{AtCsBz@m@jBuAzCaCpCyBrB_BnCyB\\Wx@q@jCsBlBgB|@{@bD_D`E{D`DaDpAoAzEwEjBkBnGmGhCgCjBkBlBkBjHeHrGkGf@e@|AuAb@]bCoBdCcB\\S`Am@tEeClB_Ar@_@~@g@~@g@|C_BxKyFBA|BoArHuDhE{B|GoDLIvA}@^[f@c@j@k@d@g@BC~B_DfAeBHKbD}ET]dA_B~D_GnBuCvB}C~D}FxAyBT_@nBwCrDmFbCmDz@sA`@k@P_@dAwBp@_BN]d@gAv@{At@mAp@}@x@_ApBmBf@g@bB{A|AwAbB}AxDoDxBoBxAqAfC{Bb@_@|AwAt@u@HIxBiCpCkDpB_CdAmApAsAjF{E~EoEhD{C~L}KbLeKdB}AvFeFfAgA`AaAz@aAxAqBjB}CrAuBj@_AvDiGvBkD`DiFdDwFbBqC"
                     },
                     "start_location" : {
                        "lat" : 29.7362569,
                        "lng" : 50.3391075
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "83 m",
                        "value" : 83
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 29.6641737,
                        "lng" : 50.4102453
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eGenaveh - Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "}u`tD{utrHQJMLMHK@IAGGEK?IFUDU"
                     },
                     "start_location" : {
                        "lat" : 29.6638286,
                        "lng" : 50.41005939999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "8.2 km",
                        "value" : 8174
                     },
                     "duration" : {
                        "text" : "1 hour 39 mins",
                        "value" : 5925
                     },
                     "end_location" : {
                        "lat" : 29.6252948,
                        "lng" : 50.4814799
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eGenaveh - Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ax`tDawtrH~BuDhAkBrAyBzCcFZg@bC}DxAaCzAeCh@aARa@t@yAn@uAj@sAtB_FbBaEv@sB\\u@xAcDfAwBtAcCp@oADEl@cA~@iBpD}HtCqG`AqBtByEjAiCdDiHp@wApCeGn@uA|BcFn@{AxBwEhAcCb@}@JSf@iA|@uBv@mB@Ad@mAv@{Bd@}Ah@mBf@gBf@yBl@sCf@_Ch@cC^_Bd@{A^kAt@oBXs@h@iAh@eAb@u@v@qAjB}CjAqBbAcBfAqB^u@Zk@^{@d@mA`BeElAiDrAuDZ_Ar@{Bh@sBb@cB`AyEJe@p@wDb@aB`A}Cr@cBt@_BdB_DhBkDxAaDv@sBvDqJ~IkUnDsIhDaJpAiDbAkCpA_DDKfD_I`AaCr@}AhAoBhA_Bz@cAFGlCyCh@k@r@w@pAwA`BmBbCsCPU"
                     },
                     "start_location" : {
                        "lat" : 29.6641737,
                        "lng" : 50.4102453
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 468
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 347
                     },
                     "end_location" : {
                        "lat" : 29.6220694,
                        "lng" : 50.4845469
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "aeysDgtbsHVIPIn@i@pAiA`BwAnAaApAoAhCwCl@q@Zi@"
                     },
                     "start_location" : {
                        "lat" : 29.6252948,
                        "lng" : 50.4814799
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3153
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2273
                     },
                     "end_location" : {
                        "lat" : 29.6013665,
                        "lng" : 50.5067545
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGenaveh - Deylam Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by موقوفه دشتی (on the left in 3 km)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}pxsDmgcsHHAFCZSbAy@bCmCnEqE|A_Bf@k@nAuAl@m@zCcDnCwChBqBpD{D|@cA|@aAf@g@dBgBNQX[vEeFfEyEh@m@rB{Bt@w@l@o@pC_DbDkDhCqC\\_@pCwC~@aAx^oa@lA}Aj@cA^iA"
                     },
                     "start_location" : {
                        "lat" : 29.6220694,
                        "lng" : 50.4845469
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 180
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 159
                     },
                     "end_location" : {
                        "lat" : 29.6000886,
                        "lng" : 50.5076268
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eفضیلت\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Aftab Restaurant (on the left in 88m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "qotsDergsHB[BKBIDGDGPORAF?@?FBpA[NEZKj@a@DO"
                     },
                     "start_location" : {
                        "lat" : 29.6013665,
                        "lng" : 50.5067545
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 267
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 201
                     },
                     "end_location" : {
                        "lat" : 29.5977512,
                        "lng" : 50.5073271
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qgtsDuwgsHNRhA\\`EJvDA"
                     },
                     "start_location" : {
                        "lat" : 29.6000886,
                        "lng" : 50.5076268
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 273
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 208
                     },
                     "end_location" : {
                        "lat" : 29.5964653,
                        "lng" : 50.5097156
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}xssDyugsHBIBE@E@C@C@E@C@C@E@C@C@C@E@C@C@E@C@C@E@C@C@E@C@CBC@E@C@C@E@C@C@E@C@C@C@E@C@EBG@C@E@C@C@C@E@C@C@E@C@C@E@C@C@E@CBC@C@C@CBE@C@CBC@CBC@C@CBC@C@CBC@C@CBC@C@EBC@CBCb@u@HQXg@"
                     },
                     "start_location" : {
                        "lat" : 29.5977512,
                        "lng" : 50.5073271
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 116
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 86
                     },
                     "end_location" : {
                        "lat" : 29.5954239,
                        "lng" : 50.5096907
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}pssDwdhsHvCHx@C"
                     },
                     "start_location" : {
                        "lat" : 29.5964653,
                        "lng" : 50.5097156
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18 m",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 29.5954202,
                        "lng" : 50.5098728
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kjssDqdhsH?c@"
                     },
                     "start_location" : {
                        "lat" : 29.5954239,
                        "lng" : 50.5096907
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "30 m",
                        "value" : 30
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 29.5951965,
                        "lng" : 50.5097029
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kjssDuehsHj@`@"
                     },
                     "start_location" : {
                        "lat" : 29.5954202,
                        "lng" : 50.5098728
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 472
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 342
                     },
                     "end_location" : {
                        "lat" : 29.5920544,
                        "lng" : 50.5128825
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by دفتر پیشخوان دولت نورافشان (on the left in 450m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_issDsdhsHBCdOqLxAmDPW"
                     },
                     "start_location" : {
                        "lat" : 29.5951965,
                        "lng" : 50.5097029
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 717
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 521
                     },
                     "end_location" : {
                        "lat" : 29.587812,
                        "lng" : 50.5183339
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eچمران شمالی\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by ساندویچ دلپذیر انتخابی بی نظیر (on the left in 170m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "iursDoxhsHCAAA?AA??AAC?C?A?A?C@A?A@??A@A?A@?@A@??A@?@??AB?JU~EuGnA_BlA}AJMbAkApDiERSdDwF"
                     },
                     "start_location" : {
                        "lat" : 29.5920544,
                        "lng" : 50.5128825
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "24 m",
                        "value" : 24
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 29.5876814,
                        "lng" : 50.5185302
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eبلوار چمران جنوبی\u003c/span\u003e‎\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yzqsDqzisHLWJO"
                     },
                     "start_location" : {
                        "lat" : 29.587812,
                        "lng" : 50.5183339
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 480
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 345
                     },
                     "end_location" : {
                        "lat" : 29.5850879,
                        "lng" : 50.5224986
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003e\u003cspan dir=\"rtl\"\u003eبلوار چمران جنوبی\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by آژانس امید گناوه (on the left in 72m)\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "_zqsDy{isHLWxByDvAeC~AwCrBsDl@iARYNQ"
                     },
                     "start_location" : {
                        "lat" : 29.5876814,
                        "lng" : 50.5185302
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 466
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 350
                     },
                     "end_location" : {
                        "lat" : 29.5812287,
                        "lng" : 50.5242423
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "yiqsDstjsH?@@??@@??@@??@@?@?@?@?@??A@??A@??A@??A?A@ARCJIREHCdCw@VItCcAFCjAa@bCcAZMhAe@z@["
                     },
                     "start_location" : {
                        "lat" : 29.5850879,
                        "lng" : 50.5224986
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 347
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 258
                     },
                     "end_location" : {
                        "lat" : 29.58003739999999,
                        "lng" : 50.52750899999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eارشاد اسلامی\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "uqpsDo_ksHZm@HQh@eABI`@iABIZcADOV}@L_A@EDi@JqAHq@Lc@"
                     },
                     "start_location" : {
                        "lat" : 29.5812287,
                        "lng" : 50.5242423
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 643
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 474
                     },
                     "end_location" : {
                        "lat" : 29.5815515,
                        "lng" : 50.5338607
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eبهار\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by بیرون بر بهار (on the right in 500m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gjpsD}sksHO]k@qAk@sAAEM_@EUEWWsBCYG{@Q{B?CWoCIcAE[OgBEa@QyA]eDEY"
                     },
                     "start_location" : {
                        "lat" : 29.58003739999999,
                        "lng" : 50.52750899999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 145
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 109
                     },
                     "end_location" : {
                        "lat" : 29.58248439999999,
                        "lng" : 50.5349048
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eجمهوری اسلامی\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "uspsDs{lsHaAgAiAsAQS[_@"
                     },
                     "start_location" : {
                        "lat" : 29.5815515,
                        "lng" : 50.5338607
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 29.5823684,
                        "lng" : 50.5350563
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003e\u003cspan dir=\"rtl\"\u003eجمهوری اسلامی\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oypsDcbmsHT_@"
                     },
                     "start_location" : {
                        "lat" : 29.58248439999999,
                        "lng" : 50.5349048
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 418
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 304
                     },
                     "end_location" : {
                        "lat" : 29.5841517,
                        "lng" : 50.5384938
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eجمهوری اسلامی\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yxpsDccmsHe@m@w@aAe@i@q@u@UQk@s@o@s@_@c@Wi@K]Ke@Ce@Cw@ZsB"
                     },
                     "start_location" : {
                        "lat" : 29.5823684,
                        "lng" : 50.5350563
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 228
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 185
                     },
                     "end_location" : {
                        "lat" : 29.5822979,
                        "lng" : 50.5390835
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit\u003cdiv style=\"font-size:0.9em\"\u003ePass by قهوه خانه محمود ملاسن (on the right in 150m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "}cqsDqxmsHJODIBEBG@EBG@IbBm@TAD?nEE"
                     },
                     "start_location" : {
                        "lat" : 29.5841517,
                        "lng" : 50.5384938
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "12.6 km",
                        "value" : 12596
                     },
                     "duration" : {
                        "text" : "2 hours 31 mins",
                        "value" : 9088
                     },
                     "end_location" : {
                        "lat" : 29.5038999,
                        "lng" : 50.6325601
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eGenaveh\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "kxpsDg|msHzBuBzEqEzDiDnJ{ItEiEHItAoAnAmAbC}Bp@s@jAwAvA_Bt@y@nC_DHIj@o@`DsD|G_I`DsDpFiGLM`DsDpAyAxDkE~AiBxAaBZ]RSfAaAvCwBbCeBnCsBPOj@c@~@cAx@eAf@q@h@}@lCcFhA}Bv@sAbB_CdBkBxB_CHKtCaD`@c@rDgEVYdCqCX[nDaEnEaF|DkEnAuArA{Al@q@hE{EtA{Aj@o@fCyC^e@rCcDRSvDeEvDaEFInDcEpDcEhE}E`AgAzCeD~G{HjCyCxDmEpAkBxAuBbBcCb@o@~CyE|@mAj@w@jAaBxAwBxCuEjCsDrAqBdA_B~AyBr@_AzD}F`CkD|D{FhBmCfCqD`@m@`CkDn@_AvCiEhDaFt@gAxAwBBCtB{CHObCiDPWjByCzE_HpCaEFKfDyEjDaF|CsE`EcGrDoFdCkD|A}Bx@kAz@oA`AuAjEuGxCgEPWdD{E|CmEjC_ErBaDp@}@tAmBvByClBmC~EoHjEkGhEmGvFcIj@s@b@wAJa@Po@"
                     },
                     "start_location" : {
                        "lat" : 29.5822979,
                        "lng" : 50.5390835
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "80.7 km",
                        "value" : 80732
                     },
                     "duration" : {
                        "text" : "16 hours 15 mins",
                        "value" : 58488
                     },
                     "end_location" : {
                        "lat" : 28.9491363,
                        "lng" : 50.9569264
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eجاده بوشهر\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کافه شهروند۴ (on the right in 800m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "knasDod`tHAGAS@SDSFQJOLMNGNGF?F?XQZKd@Wp@y@h@u@j@u@VWd@o@hH_KhIaLjGuInHaKnOcTlMmQ`KiNfHyJzB}CzAwBn@_AbA_B`AcB|AyCpAuCbBkEx@_CfByF`CoHpEkN`DeKdAaDd@mA^_A|@kBr@qAT_@\\g@r@eA~@iAdBgB~A_B|A{AzAyAtAoAhAiA^]rCkCrDkDBCZY`SsRjJqIfGyFrFgF|AoA|@q@rAy@`Ag@n@_@hAc@n@Sj@UbAYx@S|A[~@Mj@KVCf@Cx@Gv@CrBCfBBr@Bv@Dx@HfALfDl@nCh@jARfI|AfYpF`P|ClFbAjNjC~AXx@NvB`@TFfDt@bBVtBf@hB\\tAXtB^jATlAV~@PlB^hCb@hBVxAPxBV`AHbAH~@HnAFpAFt@Dr@Bj@Bp@@bABnB@pA@jAA`A?|AEtAClAElAGfEWnEc@|Dg@~AWrB]zDw@z@U|Cw@tLkE^Q^Q`Bw@ZMxAo@d@UlB{@xBoA|A}@xBwA|AcA~DuCdA{@nB}AxGoGhD{DhDiEbCkDfDwE~DuFb`@yi@pDuFdFeId@w@`BgCpIsMNUzC}ElAkBdDcFdF_IjJwNdFaIdFcIpCmElDsFzCyErCmEhDmFfC}D~EyHfBqCzCkEhBcCvF{GzAcBhEqErDkD`EqD`F{DjFoD~ByAd[oQfEaC|U_NbWwNxG{Ddc@sVdUoMjEeCjO{IhI{EZQj@[hKgGzCgBdHeEn@_@lPuJnJuFDChVqNx@g@xJyFzP_KtHoEPKtKoGtGwDx@e@xi@w[zOkJpIaFlU_NhKgGjAq@jPwJfDmBnAs@zAy@|As@jC_AbCk@~@Sd@IREbBMtCO|AEnFCzD?tVKbO?jFA|AArA?|`@WbFGvBKfBQlCg@nBm@pBcAp@]n@_@fAq@lBgBBE~AmBn@_ARWr@oAzCyFnDmHnAgC~E{JtUie@lAcCfBoDxQ{^hHqNl@sADIrAoCfAgCJU^oATs@Lc@^qAPy@d@kCb@kER{E?{C?aB?cDKqI?Y[y^_@gd@MeNIkLEmGEwEQqT?M]m\\CeEG}E?aAA_@CeF_@yh@G_FYu\\AeAEwFCcCA_AAaA?YCaCQiVKqN]_d@Ae@SmVC}CI_HAoAGuKEmGKuJIiNGsGCaBYq^AwDKgLCqFB{BFqBFmAPcBd@kDh@sBr@eClA_D`@}@j@iA|BgDNUhEiFPQjBqBzCsD~GaIjGqHhCyCnEiFn@w@hEiF\\a@zBkCxCmDl@q@^c@z@cApA}AFITYnAqAjAkAl@g@v@q@v@i@tBsAdAe@TKdBe@tCi@bE[dDE`@?bD?r@?rD?rM?~TLpJ?zO@|ZFzND~C@hKBdD@nB?|D?hE@vNBjK@dKDjA@nFDzCBpA@hMIbCDlB@dCLrF\\jEZbCPlF`@`CP~PnAdBLbHf@`AHtJr@jGb@tE\\dDVlF`@jHh@~E\\zBP`Lz@rFb@p@D`FZrBPtE\\bYrBhBN|AJjCPnAJpOhArBNhDV|Gh@pDVbIl@fU`BpDXpWjBtE\\lHh@lGd@bJp@V@`Gb@`RtAD?~E`@dHb@tCDtCKtEe@tCm@x@QdCg@xGwAbGoArDaAhC_@~BQ~@EhCKpBDrEJ@@fJXv@BlHVvENlUt@pMb@nCHvHVpHXbOb@bK\\vNb@`JZxK\\fQl@nRn@lM^l@DrABd@?\\?Z?h@ApCKtCSjD]hDs@hHsBjF{BpH{EdA{@zCsCdGoGjGsGrC{CdAiAbAkAdR{Rt_AabA`TgYz`@ei@tT{YrJqK~D}C|@s@bB{@xBiAnCiAhDcAnE{@~Ce@`@GpEm@`HJrDFlU^vNT~LR`Mb@vENtENfJZxFPrDL`Rl@vEPpVv@tNd@rDL|GTzL`@xFR~HTdBFbHTnL^|GTvEN~GTpVt@xFPl^fAnCHrDJ`M\\N@vELrr@nBpDLrDJ~GP|K`@bIXtENxAD|BHrDLrADjIPdABvDLxDDlBOfDIpFu@pCi@hBc@|Ag@`C{@ZMxGaChFiBbGeCvF{BfC{@hBw@jGyBbJgDzDuAjAg@z@a@lI_DHCfBq@HEVKbBm@LGHE"
                     },
                     "start_location" : {
                        "lat" : 29.5038999,
                        "lng" : 50.6325601
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 km",
                        "value" : 4743
                     },
                     "duration" : {
                        "text" : "57 mins",
                        "value" : 3441
                     },
                     "end_location" : {
                        "lat" : 28.9184622,
                        "lng" : 50.9906904
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSearaf Hwy\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ccuoDyo_vHZKTKTOPQPQLKLQNUJMFMNYLWLWJQN]P]b@gAdAaBn@u@h@i@^[FGX_@hDyDZm@r@s@fEyE`@e@dDwD`IaJ`JwJZ[xGqH|GwHjIgJfCuC|DqEtEgFvGmHtEgFhCuCdCqCpFeGvHuIjDuDdEwEpA}A\\_@hD_EzAiBdCqCbJoJ`FwFd@g@"
                     },
                     "start_location" : {
                        "lat" : 28.9491363,
                        "lng" : 50.9569264
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1535
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1125
                     },
                     "end_location" : {
                        "lat" : 28.9265609,
                        "lng" : 51.0012007
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "kcooDybfvHiCrBc@V]FW@c@?g@MWMmAqA{M}QsKiOuBoEiAsDgAgFScAOqAWeCImB"
                     },
                     "start_location" : {
                        "lat" : 28.9184622,
                        "lng" : 50.9906904
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.1 km",
                        "value" : 6056
                     },
                     "duration" : {
                        "text" : "1 hour 14 mins",
                        "value" : 4462
                     },
                     "end_location" : {
                        "lat" : 28.9277135,
                        "lng" : 51.0609827
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eHwy Allama Syed M. Alam Al-Hoda\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Federal (on the right in 3.9 km)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "_vpoDodhvHg@oNEaB_@qIe@oMg@_MwBai@AMAYc@sIM}D[}Ik@oOQyGCsA@_ABa@Fy@LgAXsAjCmJtEoQ`FsQ|A{FzBgIb@_BBA@?@A@A?A@??A@?@E?C?A?A?A?AA??A?A?AA??AAAACL_B@c@F{ABi@@YJoBJyBxA{[FgAf@yJD{A@U?]?c@?EMwAc@aCeBiFGQa@qAgC}Ha@oAwAiEeBqFc@uA{AsEs@sB{BmGi@eBEi@AS?E?KDU"
                     },
                     "start_location" : {
                        "lat" : 28.9265609,
                        "lng" : 51.0012007
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 974
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 767
                     },
                     "end_location" : {
                        "lat" : 28.9248994,
                        "lng" : 51.0698869
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eKhalijFars Boulevard\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by مجتمع هنری، آموزشی، تبلیغاتی و چاپ رنگین کمان (on the right in 850m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "e}poDczsvHHQBIBI@I@I?KAIAKAEAGCECGCECEECCCCCA??AA?AACAEOEQEY?YDwAHcBLuADk@Fa@HYHYJYJYXk@Zg@~@mAd@w@b@o@r@cAVc@Ve@Zs@Vq@Tq@Pq@Lk@Lq@Js@DWD]BUPyAJy@Lu@FOHONW"
                     },
                     "start_location" : {
                        "lat" : 28.9277135,
                        "lng" : 51.0609827
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 686
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 561
                     },
                     "end_location" : {
                        "lat" : 28.9226737,
                        "lng" : 51.0760564
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e4th\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "skpoDyquvHJAHCFEFEFGDGBIBGBI@IBK?K?KAKAKCKCGMQGEEoAZ}BPkARyAr@uDvAeDZm@tDcH"
                     },
                     "start_location" : {
                        "lat" : 28.9248994,
                        "lng" : 51.0698869
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.1 km",
                        "value" : 5088
                     },
                     "duration" : {
                        "text" : "1 hour 1 min",
                        "value" : 3650
                     },
                     "end_location" : {
                        "lat" : 28.9386749,
                        "lng" : 51.11931569999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "u}ooDkxvvH_@o@U_@{AoD]}@o@aBs@}Ba@sAeEsMyAsEQi@{AyEk@gB{BeHCGm@oBACAEuAkDSa@eCoFuBmEOYmCgFGKwBaE{BiEo@oAc@u@}DiHs@qA{C}Fm@kAoCmEc@e@{CiDs@w@yIyI_@a@}@iA[k@ISQi@k@iBaAwF}@cFm@qDQsASkCL]Je@BE`I{K`NyQJYDKFYBQ?WAc@?MEa@mCgF_B_DuAeC}@aBoH_N"
                     },
                     "start_location" : {
                        "lat" : 28.9226737,
                        "lng" : 51.0760564
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.1 km",
                        "value" : 3104
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2267
                     },
                     "end_location" : {
                        "lat" : 28.9200536,
                        "lng" : 51.1412501
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uasoDwf_wHxH}HbAoA\\c@l@oAdGsLb@u@`@o@z@o@hQaK|DcCrMwHhGkD~@e@j@[bAo@d@Yf@g@RYJUPe@Lm@BS?SAWYsE?kB?EF[NWJWhEkJL[bA}AHK|@iA\\c@NKTU\\q@Zu@~@}BvAqCtBaEj@iAhAiANQpAeA`Ay@"
                     },
                     "start_location" : {
                        "lat" : 28.9386749,
                        "lng" : 51.11931569999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1363
                     },
                     "duration" : {
                        "text" : "17 mins",
                        "value" : 991
                     },
                     "end_location" : {
                        "lat" : 28.9227548,
                        "lng" : 51.1541483
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at خودپرداز بانک صادرات\u003cdiv style=\"font-size:0.9em\"\u003ePass by خانه بهداشت باغک جنوبی (on the left in 180m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "imooDyocwHaAkBUg@[m@Yg@s@wAy@eBEOEM?IAQ@m@Dq@H_ADm@@UJoA^kEH}@Dg@^yDJmAP_BDa@BW?U?UCYoAsDaD{JOg@Yy@k@eB]cAy@eCKa@"
                     },
                     "start_location" : {
                        "lat" : 28.9200536,
                        "lng" : 51.1412501
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "10.5 km",
                        "value" : 10463
                     },
                     "duration" : {
                        "text" : "2 hours 8 mins",
                        "value" : 7658
                     },
                     "end_location" : {
                        "lat" : 28.8644767,
                        "lng" : 51.2342622
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAhram-Choghadak Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 94\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "e~ooDm`fwHpDcEzAcBjBqBdGyG\\_@p@u@hEwEjBuBfKgL|DmExLuMhLoM`EqExBcCnR}SzFuGrMqNtKmM|BuCv@cAv@qAl@iAf@mAr@yBpBmHpFsRdBkGlJy\\FS`H}Vv@sCvFgSlB{GlB_HlAgELe@|AuF~I}[l@wBZgAZkArKg`@|AmFx@aC~@_CFQ~@oBv@_BpAsBbAaBfBaCfBuBxBuBxAoAtAiAvA}@bBgAt@a@^SfB{@rM{F`NeG|B{@pMyF|Au@|BiAxAw@bC_BhAu@|AiAvAiAr@s@hAkAtEkFrAcB"
                     },
                     "start_location" : {
                        "lat" : 28.9227548,
                        "lng" : 51.1541483
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "20.2 km",
                        "value" : 20174
                     },
                     "duration" : {
                        "text" : "4 hours 4 mins",
                        "value" : 14636
                     },
                     "end_location" : {
                        "lat" : 28.71191009999999,
                        "lng" : 51.3218323
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eAhram-Khormuj Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Route 96\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by برج مخابراتی (on the right in 13.8 km)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "_rdoDcuuwHDBHBF@B?D?D?BADABABCFEDIBG@E?E@E?E?E?EAECICGfAkBz@wAf@aArAeCrAiC|ByFn@mBzAeExDwL~CkJhCuHrDuKfEmMhGuQlBkFlAyCjBmE~CwGHQ`IeOhDiGxN}WxHkNbB}CpDwGrBsDzCiFpBaDlLkRpCiE~@uAn@u@hAeAx@o@~A_ApCiAjAYp@M~@OtAMp@EzDIjEIhRWxWa@|CGzEKlV_@b@?tPY~EGj]g@pDEnKOtRU|R[vKKbHKfIK|FGjCElDGnAE|@C|@KlAWdA[hBk@bCaAbJqDvOgGr@YbVkJ`JoDlEeBjU}In]cNvJ{DtBy@vMgF|GmCfI}CPGb^mNbHoC^OzVwJnScIz@[fAe@vWeKpRwHfDqA~R{Hfb@oPt^uNpGaC^OzLaFfFqBtHyC|\\uMba@}O"
                     },
                     "start_location" : {
                        "lat" : 28.8644767,
                        "lng" : 51.2342622
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "7.0 km",
                        "value" : 6960
                     },
                     "duration" : {
                        "text" : "1 hour 25 mins",
                        "value" : 5077
                     },
                     "end_location" : {
                        "lat" : 28.666148,
                        "lng" : 51.3647208
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کافه کوروش(مرادیان) (on the left in 700m)\u003c/div\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "mxfnDmxfxHKEM@g@Na@L[?OEGCCECECGAQAU@IDKJKBCDATCj@?N?fAJt@@v@IpAa@h@WHEBC@C?E~@YnEgBnAe@LGfBo@xDwAdAc@nAg@tAk@DCpMcFdMeFtEkBbEaBhEeBtG_CfLkEz@[lIeDlD_Bv@i@rAgAhAmAzBcDnJmNlHaLlGkJ~C{Ej@y@HMjEuGhDcF~F}IfEoGxCqE`GyI`HkKnAmB~EmHbGcJvGwJtFqI|CuEb@m@bD}EbBaC|@_Ax@q@r@g@hEmCfC_B~@w@f@m@"
                     },
                     "start_location" : {
                        "lat" : 28.71191009999999,
                        "lng" : 51.3218323
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "16.9 km",
                        "value" : 16870
                     },
                     "duration" : {
                        "text" : "3 hours 24 mins",
                        "value" : 12210
                     },
                     "end_location" : {
                        "lat" : 28.5267361,
                        "lng" : 51.4145498
                     },
                     "html_instructions" : "At the roundabout, continue straight onto \u003cb\u003eBasij Blvd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Khormuj-Kangan Expy/\u003cwbr/\u003eRoute 96\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by سوپردکه سیراف (on the left in 450m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "mz}mDodoxH?J?F@D@F@FBDDFBBDBFDD@F@L?HADCDADEDCFMBM\\_@LOZ[rA{@`BeAlAs@~EwCzIkFbGuDxIoFbAm@hC}AZS\\UdFcDNKtEsCpAw@d@[vA}@zAaA`C}Ax@g@jAu@v@e@fAq@FGh@[lEoCfBgAvBsAZQHGZUTMRIVIRELEh@KFAZG`@Gd@Cn@CjACjACjCIpFEnCCz@EfBGjCElAEpBGnACd@ApAAJAh@?lCGf@AzBMx@?zCCjAC`ACzBEjCIvEOrBGxACP?pDId@?rDGzSYnCGb@A~CGfEKj@AzDMlEEbDKJ@`@Bh@Jd@DH@F?F@FADAFCHCTKfBQlAChCIlAC~JUlACjCAjDIjDIrCIvCEjBAzCIVApDGtBEdDINAN?BAL?xACfDI~DGr@AlACxBEbFMbAAhEK`HMtBEx@AbHMl@AvCGlGOdCCpFK~FObFGhBCjFKdDIbQ[xGMpFI`P[xZo@tDGhCG~GMdBEj@Gf@EZG`BS|AUtDs@|DoAjCeAvDgBxByAfEsC|CyBfToOxAeA`D{BnRcNdHcFjHeFbKeHfH}E`_@oWh\\gUhRsMVQhb@}YfY}RlI{FtAcA"
                     },
                     "start_location" : {
                        "lat" : 28.666148,
                        "lng" : 51.3647208
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "58 m",
                        "value" : 58
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 28.5270074,
                        "lng" : 51.4150624
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "csbmD}{xxHu@eB"
                     },
                     "start_location" : {
                        "lat" : 28.5267361,
                        "lng" : 51.4145498
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "23.9 km",
                        "value" : 23867
                     },
                     "duration" : {
                        "text" : "4 hours 49 mins",
                        "value" : 17323
                     },
                     "end_location" : {
                        "lat" : 28.3474735,
                        "lng" : 51.5182455
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Route 96\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Amir Market (on the left in 23.3 km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ytbmDc_yxHpV}P|HqFlCuBnC{BvDiDzDsDnDyDxEwFjE{FrEoGnJqMfPcUlXo_@zPyUV]hCqDbHoJjA}A~CmEzAwBlQqVhJmMtHeKvEsGrDiFtAkBlBqCrDaFpEmG~CmEhMoQlFiHdLsOtC_ExBaDjDyEzAsBbAiAn@m@jAy@~@u@hDaC`Aq@|@u@pAkAn@q@hIoKlFkH|CaEzA{BnBiCnD{EV[Xa@j@u@\\e@|DkF~BaDvB{CnBkCzDgFdAsAr@u@hAkA~B}B`A{@lBqAtAkA`@]d@[fa@aVfNuIhFsCtJyFz@i@h@[bFwCjEiCdDkBjBy@b@OPGz@U`AQxASdE_@~Ho@r`@cD~Ea@`L}@fAItIs@nFe@jFa@rAG~AE|AAzA@nAHtAJp@H|ATn@Lz@RpA^dCz@nEnBJFhF`CzHpD|BhA|IbEnIbElCjArB|@nAd@fA\\hA\\n@Nv@PlATp@Jv@JxALT@nAFrA@l@@|@?v@Cr@Ef@Az@G`@E^E~@Mx@Kr@M~A[f@It@QbJ_Cd[yHpBe@dAWbAUXGd@KtA]`@I^I`AUz@S|@UZI~@UfAWtA]dAW|DaA|@UVG`@KbBa@^I`@K~A_@bBa@~@Uv@SZIv@S^IfCo@h@MrD_A|A[xFwA`Ba@hD{@VGrCq@ZIfEcAbBa@rBg@nA[b@K|ScFpFoAz@SpCu@lD{@`AWfBc@lEeAvOyD~LyCpFsAfCm@d@MnM_DnV_GjFqAjBe@~OyDvHiBdJ{B`AUdBc@ZIfCm@vA_@n@Q~A_@j@O^IJOJEXK`@GjA_@fA[|A_@vBi@tG}AxA_@"
                     },
                     "start_location" : {
                        "lat" : 28.5270074,
                        "lng" : 51.4150624
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 408
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 310
                     },
                     "end_location" : {
                        "lat" : 28.3491451,
                        "lng" : 51.5219032
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ur_lDadmyH}CkL_@wAm@}AMOYq@{@u@"
                     },
                     "start_location" : {
                        "lat" : 28.3474735,
                        "lng" : 51.5182455
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 350
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 256
                     },
                     "end_location" : {
                        "lat" : 28.3467681,
                        "lng" : 51.5236127
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "e}_lD{zmyH^sA@oA|@k@bDk@TBj@KxA_Az@Q"
                     },
                     "start_location" : {
                        "lat" : 28.3491451,
                        "lng" : 51.5219032
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "9 m",
                        "value" : 9
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 28.3468071,
                        "lng" : 51.5236919
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "in_lDqenyHGO"
                     },
                     "start_location" : {
                        "lat" : 28.3467681,
                        "lng" : 51.5236127
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1221
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 910
                     },
                     "end_location" : {
                        "lat" : 28.3382223,
                        "lng" : 51.5314044
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by سوپرمارکت شهر (آقای کارگر) (on the right in 1.1 km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qn_lDafnyHV_@BQZe@`@]h@c@DEnB_BxAoAp@i@z@s@~@w@\\[JI|@u@^]x@g@tAiAnBcBrAeAp@e@z@o@h@a@rAaA|@u@d@_@d@e@RQ|AqA\\[PQd@c@x@w@x@w@P]RO"
                     },
                     "start_location" : {
                        "lat" : 28.3468071,
                        "lng" : 51.5236919
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 249
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 189
                     },
                     "end_location" : {
                        "lat" : 28.33925,
                        "lng" : 51.5336525
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eخیابان امام حسین\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{x}kDgvoyHK[Uw@IUK]IUq@qBSo@Us@Sk@EKGGEEGG"
                     },
                     "start_location" : {
                        "lat" : 28.3382223,
                        "lng" : 51.5314044
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2366
                     },
                     "duration" : {
                        "text" : "29 mins",
                        "value" : 1716
                     },
                     "end_location" : {
                        "lat" : 28.3199675,
                        "lng" : 51.5436007
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit\u003cdiv style=\"font-size:0.9em\"\u003ePass by the playground (on the right in 99m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "i_~kDidpyHD?@?@A@?@?@A@?@A@ABA@A?ABEBKNGZI|D{@p@QTS\\O^]TUPQn@o@fAa@PK^Ur@W|Am@tCgA~EoBnIgD|D_BrJyD~Ao@TIjAg@nEkBxGqCtImD~L{FnAq@\\EdAQp@UXK|Aq@"
                     },
                     "start_location" : {
                        "lat" : 28.33925,
                        "lng" : 51.5336525
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 1982
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1455
                     },
                     "end_location" : {
                        "lat" : 28.305543,
                        "lng" : 51.5524149
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by مغازه (on the right in 650m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yfzkDobryHsAmEKgB`Ak@v@i@HEz@e@@AHCTMx@c@@Ap@]^SzBmA~@g@|@e@`Ag@hE}BnFuCzHQNGfAa@zCiAvIcDfFoBLIf@MZS~B}@fBi@dDkAz@MzBgAv@U"
                     },
                     "start_location" : {
                        "lat" : 28.3199675,
                        "lng" : 51.5436007
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 430
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 322
                     },
                     "end_location" : {
                        "lat" : 28.3054482,
                        "lng" : 51.55659370000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "slwkDqysyHLo@c@wDzAyDSgCDaCe@wC"
                     },
                     "start_location" : {
                        "lat" : 28.305543,
                        "lng" : 51.5524149
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.4 km",
                        "value" : 3392
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2442
                     },
                     "end_location" : {
                        "lat" : 28.278025,
                        "lng" : 51.5712343
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by ایستگاه تنظیم فشار خطوط گازی (on the right in 3.1 km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "alwkDustyHbAe@x@Wn@SpAc@t@W`@[r@i@fA{@|BsA~A{A`CkBjBoAZStHeF`Ag@RK@AhF{Bh@Un@QvAe@@?`A[rAi@fJuD\\Mv@[fBg@`DG`Aa@bN}Fh[wLtF_CBAhKkEZMBA~E{Bl@a@ROHGTMHGLGFAN?R?x@S\\I\\Wx@[PGLOz@S^Q`@G"
                     },
                     "start_location" : {
                        "lat" : 28.3054482,
                        "lng" : 51.55659370000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 213
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 152
                     },
                     "end_location" : {
                        "lat" : 28.2763976,
                        "lng" : 51.5700924
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "s`rkDeowyHHHlC`BjDvB"
                     },
                     "start_location" : {
                        "lat" : 28.278025,
                        "lng" : 51.5712343
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "24.5 km",
                        "value" : 24514
                     },
                     "duration" : {
                        "text" : "4 hours 58 mins",
                        "value" : 17890
                     },
                     "end_location" : {
                        "lat" : 28.1209952,
                        "lng" : 51.7048412
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ovqkDahwyHx@mId@kEtMgpA`AkJDa@tC}X^oC^_Bh@{Al@oAr@kAhAwA|@{@vAeA|DqCrFyDdCeBlFsDdBsA`BiAl@e@zCwB`BiAhAk@jAe@`Bk@jAWfDc@nGq@dIy@xFm@lBY`Be@fBo@tAu@bHqEnMwIlHaF`JcGjD}BnP{K~NwJpFwDzAw@t@_@x@[lA_@`Em@hGu@fFmAnCeAbBy@dCsAnEkCfJ_F|GuDxCaBt@Uv@Wj@MJAx@GjAEdABD@nALRB|HfArAPtATvBb@lAZfC|@dAh@hDdBdIjElB|@dA`@`A\\XHd@Jl@LRDvIhBlEx@jGrAzE|@lIdBzAHF@z@CfAKx@KNErAc@dC}@rEmBjAg@hIeDzM{Fn@Y|RmIvCmAvS}IjDyA|EkBrCmAn@[tAq@h@U~CqAnMkFzAo@x@e@l@u@`@i@Zq@`@kARy@p@gDb@_Bb@kAn@eAp@y@p@a@p@SbAEv@?HAj@?~@Gr@Gh@OdAe@pCkAb@[f@g@z@iA|CeER[`EuFfAyAp@u@x@k@`CsArG{D@AvDgBvDaBvCmAl@[ZQ\\_@Z_@b@s@t@}AlC{HzGgRdGuP|EmNdDeJxDuK~DiL^gA`AqC~AsE~BmINm@f@qB~AkHZiAfAcEZkAxBqHh@eBNe@|@qCzA}EfLk_@jBeGNc@Na@v@aCfAeCnAeCdBuC|AoBnByBVUnAmA~EsDp@a@`A}@h@c@\\YPQfBuAn@m@vAsAPWLUXo@HO`AgCfBgEVk@l@}@`Aq@jAq@bA_@FCz@[TIJCnAWfEo@hBWb@GvEk@`AOtFy@pAMvA?vBPbJf@fEVtABp@@RETCl@Sh@q@`AuBrByFDM^g@b@a@^SDCn@MhAApCb@pBTnAHj@CPEl@Qn@_@@A|@gAr@kAPs@@s@MaBKs@@m@Ls@X}@d@sAFIT]\\i@rCaD~@eAf@a@hAm@z@YrAe@zFiBfBm@jAk@r@i@dEaDl@e@ZWXS`@_@Ta@b@eAV_AHm@?QAe@AcAIiICcBF}@l@aEJe@T_AXm@x@s@~AgABCn@a@pMsIHGb@]tB}Az@{@FQ"
                     },
                     "start_location" : {
                        "lat" : 28.2763976,
                        "lng" : 51.5700924
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "81 m",
                        "value" : 81
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 28.1202727,
                        "lng" : 51.7048217
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gksjDgrqzHTDJ@J@PANAXCf@@"
                     },
                     "start_location" : {
                        "lat" : 28.1209952,
                        "lng" : 51.7048412
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "43.6 km",
                        "value" : 43557
                     },
                     "duration" : {
                        "text" : "8 hours 46 mins",
                        "value" : 31556
                     },
                     "end_location" : {
                        "lat" : 27.8684381,
                        "lng" : 52.0348693
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کافه دکه دانوش (on the right in 6.9 km)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ufsjDcrqzHl@eB|BgGnCiGVk@jA{BvAqCxCiFJOvEiItB_EZe@bA{AdA}Ax@oAnCgE~@_B~AsDvH_RL[`FmLzKaXtWsn@`AaCzNy]z@sBxEgMbD{HpA{C`J{SbFsLr@cB|IaTvAiD|EiL~@{BfBiEj@kAl@aA`@k@j@{@v@w@lB{Ar@g@tCwBjOsKbAkAb@a@BBB@B@B@D@B@B?D?B?BAFADCFEBGBC@E@E@Mj@u@pAgAfLyJfA_AhJ_Iv@s@|AqAxIoHvF_FxHoGhCuBlCyBhAcAdFeE\\g@~LgKJCpDaDtM}KrIkHlEyDrMyKtM_LdCuBz@cAf@m@fAaB|EoH`EcG|QkYxLcR|@uAxNkThDeFdMuR~MqST_@`@o@fCmE~@sBl@_Bf@wBvGoV`Tgw@nQaq@`HeWtHwXPm@lJm]zAoFjAiELe@dBqGnDoMrBuHpAsEhB_HdDuLZkAjB}G`BiGlBaHdAiDt@eBZo@v@cAxHqJxPoTpDsEtQmUhAyAxPgTr@_AhKsMli@{q@~]ed@rIwKrDuEhJoL|M{PNS~LuOvKeN|BwCvZg`@zPmTbEmFrVk[fM{Odc@oj@|BsCl^qd@tAgBx@mAd@u@h@cA\\_AnAiDb@{AfPod@n@sBf@cBP{@TkAFWBIN[LOXe@Za@Ts@|@_CfAeDdAuCrB}FTo@Pi@f@{Ad@yAh@}Ad@sADOXw@dAwCf@yAbAwCJWXu@\\{@nAaCZa@l@s@~AqAxCoCt@q@dByAlBaB~@u@^[FCRCjGwFrAuAbJgIlIsHfDyChJgIbFmElO{MtReQpG}FvKoJrF{EzVuT`FkE|MoL~EkEtAoArO_NhKcJnBeBhRmPlBgBZY|L{KrLkK\\YZ]HGbH}GNOhBsALMfAaAxNkMpAiArIuHfByApH{GdByArEgEbC}BLKlIwHzBsBrJwIl@s@h@k@@G@E@E@A@C@CBC@ABABABABAD?D?n@e@h@_@`EqDdPwNb@e@r@q@fDyCfDyCnAgApAkApAiAbHmG`EkDnBaBRSfGqFBC~BsBdHgGzEgEpC}BNO"
                     },
                     "start_location" : {
                        "lat" : 28.1202727,
                        "lng" : 51.7048217
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 246
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 27.8668427,
                        "lng" : 52.0363169
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by دستگاه تصفیه آب نظری (on the left in 140m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w`biD}`r|HEM?G?IJOx@o@h@}@rAkA~@q@XIJAZD"
                     },
                     "start_location" : {
                        "lat" : 27.8684381,
                        "lng" : 52.0348693
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "6.8 km",
                        "value" : 6845
                     },
                     "duration" : {
                        "text" : "1 hour 24 mins",
                        "value" : 5048
                     },
                     "end_location" : {
                        "lat" : 27.8206568,
                        "lng" : 52.0810699
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKhormuj-Kangan Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by لاستیک فروشی فتحی (on the left in 56m)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wvaiD_jr|HvCiCdNcMNMpBcBhCsB~BmBzCyBTOtIqHtFqE|UkQx@o@POLIRM`WqOz@q@j@i@B[@E@EDIJKLGHCJAJAH@LBFBB@FAHCTMtAy@x@e@vBqA|A}@lBmAb@YFE|AaAXQ`B_ApDyBrBgAdBeAdAq@NKzGaEDCNKJEh@WbC{A~ByA~A_Aj@_@dAq@JGd@_@^]HIf@k@`@g@BCJMFIPWNUT]^k@BC`@o@p@eAp@eANUvBcDXc@`AwAHMR[JQV]BGPWZg@T[DGV_@dAgBf@u@V]`AyARWr@}@~A{BJOh@{@rAkBb@w@nCgDzAuBLOv@iAj@y@Xc@p@cARYBE`@k@fBcCJMx@qAhA{Av@eAhBuCpAgBlBaCx@kA`CmD~@uA~BgDZa@HKvBaDn@_AxIeM~@oAf@q@BGl@}@"
                     },
                     "start_location" : {
                        "lat" : 27.8668427,
                        "lng" : 52.0363169
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 27.8205676,
                        "lng" : 52.0809906
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eKangan-Siraf Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cvxhDua{|HPN"
                     },
                     "start_location" : {
                        "lat" : 27.8206568,
                        "lng" : 52.0810699
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18.0 km",
                        "value" : 17967
                     },
                     "duration" : {
                        "text" : "3 hours 41 mins",
                        "value" : 13262
                     },
                     "end_location" : {
                        "lat" : 27.7220968,
                        "lng" : 52.2120245
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at پلیس راهنمایی و رانندگی( امتحان آیین نامه رانندگی) onto \u003cb\u003eKangan-Siraf Expy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by تعمیرگاه اصفهان کولر غلامی (on the right in 2.2 km)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "quxhDea{|HjBiCdBgBfAw@lBiArBsAjDyBh@_@pFoDhMmItA}@tIuFpA{@\\UxBwAbBkAp@c@bDsBjDeC`CaC`H}Gx@y@hKgK|CyChCiCzByBhAoAhAiBPi@p@sBTeAv@qDr@qDT_BB_B@wB?U@sAHsAJ{@Xq@V_@d@i@v@k@~Au@d@Yt@u@h@q@j@eAPg@`A{B\\y@Zq@X[fB{@d@QxAi@jAa@`@M|DuAj@S|CiArGyBtAe@dIyCxJqDf@SzAo@nAu@NOfAiA|@eA`CyDTa@vDmHdCyE|FeKHQ~FkKjB_CzA{A~AoAjBaBtDcDfCmBzBkBjBcBPQX[VYxA}ALUXe@v@_Bv@gCdA}EV}AZ}Bb@iGHqBLwD@U?SDcE?k@?oDIwDG}ACg@Cg@UuCo@uGO{Ac@{EaA{JGg@Ee@M}AKsBEgBAq@?i@AU@Q?eADgBJcBLyA@MDWR_B\\{Bj@{CDOr@aCz@yBt@iB?AR_@d@_AhByCjAgBPYZc@rAkB~@eAlBkBXWZY`@_@hAu@~AoApB_BlEgDnCwBb@]d@_@bAw@nIkGbEuCbC}AXQzDeCHEdBaAJGjHyDnAc@bAa@`@Q@?fAo@|AgA~AyA?AlAcBl@aAdAaBdAoAxAcB`HwHjCyCtAeB~AcC|@cBPa@Ra@d@eAx@eBn@wAxAiDfAmCHSXy@j@}BJi@Je@bAgF@Gr@mC`@eBDKj@_Br@aBZs@Xo@NSbA_BpAkB~@cAX[LOlAeAdDcC@AfAo@tJoEfF_C\\KlAo@tCwAbAe@~BiArBcA|@i@l@a@\\U@CtAcA|@}@pAuALOj@q@hAaBz@yAn@mALWdAkChAqDjAsEv@eDf@iBb@cBv@gCbAuClA_CpAyBhA_BhBeChBeCjEeGX_@vBeDd@u@Zi@p@{Af@gAfAiCn@yAnD{H~CsHbAyBx@yABEfAiBd@m@V]V[hBmBBCbDuCjBcBZa@b@i@nAiB`AmBv@uCj@gC@I"
                     },
                     "start_location" : {
                        "lat" : 27.8205676,
                        "lng" : 52.0809906
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "7.3 km",
                        "value" : 7342
                     },
                     "duration" : {
                        "text" : "1 hour 33 mins",
                        "value" : 5588
                     },
                     "end_location" : {
                        "lat" : 27.6904124,
                        "lng" : 52.26780530000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by پالايشي سيراف (on the right in 140m)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "cnehDctt}H`@iAl@cCh@gEZ{AZoABIJUVo@h@m@n@_@~@YAIAMAQBM@KBIFIJKHCJAFC`@o@Z}A`A_F@E^uBZcBBOP{@BOJg@DUXyAPaABOP{@BOP}@BOH_@Ri@HSl@{@jAs@PKbBeAp@i@h@a@hA}@|@s@NKpA_ABAvAmBVi@\\u@^wANqADc@Ji@PeAFc@l@eBHOb@{@p@{@lAoAFE~F_Fv@o@~EmE`ByAdA_ArAkArAkAv@s@ZWfBgBBCV_@j@y@j@eAZm@HU^oAh@{BZmCBOJ_AFe@NgA^{BLw@FUXkABMh@_BNc@`@gApAsD~@mC@C^gA^uAJ{@?ELLLFLBLBR?TAJEJKHMJ_@BU@UAMCKCMCIGOBe@@KJ[Pg@La@b@wA`@aBZiA?Aj@wBn@mC@Ap@sC@CJc@@?`A}DJc@Lg@XiAr@wC@?l@gCl@_C?Aj@}B\\cB?Ab@sBf@}Ch@oCxAmIDY^qBToADWJw@NcAHq@@KLcAb@uD^cDl@uDDUx@_E^kB`@}BXaB^gCl@cEPiAF[Be@FaA?CNoBLqA@OJoAH}@Jo@L]@EXg@Va@Z[^SNIFCVGPAREl@CXBXDfAXB@@?xBt@nBn@vBz@FBdAd@~FlCl@Vd@Xj@V"
                     },
                     "start_location" : {
                        "lat" : 27.7220968,
                        "lng" : 52.2120245
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 km",
                        "value" : 4735
                     },
                     "duration" : {
                        "text" : "58 mins",
                        "value" : 3462
                     },
                     "end_location" : {
                        "lat" : 27.6843261,
                        "lng" : 52.31493649999999
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit\u003cdiv style=\"font-size:0.9em\"\u003ePass by گمرک عسلوئیه (on the left in 3.1 km)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "ah_hDyp_~HEECICGAIAI?I@I@IHQDGBCBCDCFCFAh@c@NUHQVcB^sCt@qF|@uENs@TmAHc@nAeH@G^uBLu@RgATuAn@aE@ELqB?CLmBTkDPeCF]f@yD\\aCb@eCVgCPsBFgABcAByAJqI@Y@aCT_NHcGHaHF}F@o@JsFD_DDyBFiCJcFHsEHmE?[TuJBo@Z}KTaEP_EHgAPiC\\kFFcAd@_HDiADw@JiBJiBNu@XeEDg@Bi@LgBBaA"
                     },
                     "start_location" : {
                        "lat" : 27.6904124,
                        "lng" : 52.26780530000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 633
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 472
                     },
                     "end_location" : {
                        "lat" : 27.6834656,
                        "lng" : 52.3212117
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e at پمپ گازوئیل",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ab~gDkwh~Hl@sCRs@Lk@\\cANm@@e@Ca@A}BCmARwE`@mK?E"
                     },
                     "start_location" : {
                        "lat" : 27.6843261,
                        "lng" : 52.31493649999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "5.5 km",
                        "value" : 5504
                     },
                     "duration" : {
                        "text" : "1 hour 7 mins",
                        "value" : 4008
                     },
                     "end_location" : {
                        "lat" : 27.65588,
                        "lng" : 52.3625216
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by the park (on the right in 3.9 km)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "u|}gDq~i~HBIXyBt@aC`@y@j@_Ah@s@h@k@DEz@q@n@_@d@U~B}@fBi@hCw@\\MbF{Ax@Wv@Un@Kd@CX?l@JbBj@rA^d@?BAb@Kj@a@`@m@HKr@oAX]@CT[\\URMp@Sp@U~@WbAYNE~@[b@QTIh@Sl@U`@Qr@YPIj@Up@YNIj@[LK`@_@HMLOxBgDn@cA^q@LQ\\o@rAuCFOt@aBl@cBd@yAXiAJi@Fg@Fi@BSL{ABULkB?CBe@@OHiAD[DeA`@wCb@qCPiAR{AL{@BQf@mD?ERyANgA@KF[?GLg@VcAJc@VmA@EJa@l@aBLsBHw@Fg@De@@IRuBFaAFcAFw@@QBg@DSBKH[T_ABMTs@Vu@Tq@HUHWJU\\{@N[BEVc@R_@RWx@gABEf@i@FG\\_@|@{@RSLOzA_BNO|@kAv@eAdB}CHKjB_EBGpBwFN]Pc@pAaDZy@HQfAsCnCiH^cA`@cAj@wAt@iBvAqDtB{ExAeDHS"
                     },
                     "start_location" : {
                        "lat" : 27.6834656,
                        "lng" : 52.3212117
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 244
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 178
                     },
                     "end_location" : {
                        "lat" : 27.6548085,
                        "lng" : 52.3646808
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eخروج بندر طاهری\u003c/span\u003e‎\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gpxgDw`r~Hh@gAN_@zCgI"
                     },
                     "start_location" : {
                        "lat" : 27.65588,
                        "lng" : 52.3625216
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.6 km",
                        "value" : 4630
                     },
                     "duration" : {
                        "text" : "56 mins",
                        "value" : 3357
                     },
                     "end_location" : {
                        "lat" : 27.652479,
                        "lng" : 52.410902
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by the park (on the right in 700m)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "qixgDgnr~HbA}BjAyCb@uA`@sAT_AT_ATcA@ILw@Ls@Hq@Hw@Hw@H_BDgA@W@O@g@Ay@?gAAeAAk@CsAGaC?UUuJ[yN?SAaCBsCBkBDkBR{DBm@F_ADy@b@uGZqID_APuDRiEH_B`@cId@kJh@kMDy@Dy@TaFTaFLcCLcCNyCLyCR}DP_EPaDDqADqADyBAiBImBOsCc@wDu@_GoAaJi@aEIo@_@yBOg@"
                     },
                     "start_location" : {
                        "lat" : 27.6548085,
                        "lng" : 52.3646808
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 405
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 311
                     },
                     "end_location" : {
                        "lat" : 27.6533826,
                        "lng" : 52.4148815
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "_{wgDco{~H?_@AUG]Ia@CKCSES_@}BSsA_AuGUcBGe@"
                     },
                     "start_location" : {
                        "lat" : 27.652479,
                        "lng" : 52.410902
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 108
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 83
                     },
                     "end_location" : {
                        "lat" : 27.6535779,
                        "lng" : 52.41594809999999
                     },
                     "html_instructions" : "At بندرگردشگری پرک, continue onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eبلوار وحدت\u003c/span\u003e‎\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by لوازم خانگی مینا (on the right in 63m)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "s`xgD_h|~HY_CKm@Ag@"
                     },
                     "start_location" : {
                        "lat" : 27.6533826,
                        "lng" : 52.4148815
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3190
                     },
                     "duration" : {
                        "text" : "40 mins",
                        "value" : 2390
                     },
                     "end_location" : {
                        "lat" : 27.6512889,
                        "lng" : 52.4469597
                     },
                     "html_instructions" : "At the roundabout, continue straight\u003cdiv style=\"font-size:0.9em\"\u003ePass by بانک صادرات پرک (on the right in 150m)\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "{axgDun|~HBA@A@A?A@A?A@??A?A?A?A@??A?A?AAA?A?AACAA?A?AA??AA??AA?AAA?AY@YBWF]H[Rm@FMHW`A}Af@u@Ta@|B}CNWR[Xs@T{@BSRiADm@Bu@@iA@a@?aB?c@[iXa@}BIa@eDiQGa@wBgLUmAFoA?ELsB`A{QXqF?E`@{HfAeSBg@Bg@?CT_EHgABUD]Jo@Pm@Pu@FWPs@n@wCDWHa@BQ@M?IAK"
                     },
                     "start_location" : {
                        "lat" : 27.6535779,
                        "lng" : 52.41594809999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "65.0 km",
                        "value" : 64994
                     },
                     "duration" : {
                        "text" : "13 hours 9 mins",
                        "value" : 47328
                     },
                     "end_location" : {
                        "lat" : 27.2831308,
                        "lng" : 52.9203706
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by کامپیوتر و دوربین مداربسته پویاسیستم (on the left in 48.4 km)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "qswgDopb_In@qCdAsEb@kB`@cBf@uB^qALc@XcAhA}Cn@aBp@_B~@kBb@w@b@w@bAkBlC}Ef@}@zAkCT]Va@\\e@`@g@v@o@jAu@dAo@dA_@ZQxAaAl@m@vAeB^k@n@aAzBaDT]vAmB|@cAHIhAkArCuCnCmChBgB`BeBjCuC`@e@`@g@Zi@\\i@N[`@u@b@u@d@s@tBaDp@aAzEoHn@iARc@`@kA^mATs@l@cD`@qCXgBHg@ZoBRw@V{@BKr@mB~@}BBGr@aBr@_BvA_EzBaFdB}Dt@{Ad@aAZi@dAeBl@y@@CbAsA\\[VWdBgBrCiCzBqB~@_Az@cAv@eAn@aAFIT_@DCn@eAvBiDfEqGbBqCBGbAqAV]nAqAZY`@]^Wr@g@|@e@vAm@v@W`Ck@tEeAJCTIj@OxA_@b@Sf@UzB{AfCkBBAlB_B@?rGkFRQrAkApAaB`@i@\\k@Vg@p@sA`CuF|@gB\\o@V[V]v@_Ap@k@NKLK`@[XQlAg@hAa@z@[lC_AjAs@b@_@BCjAoAhAqAX]X_@vAgBb@k@dBqB|BqC`@e@pAyAh@c@ZYZWr@m@nF_ElCeBf@]vAeAtB{AbBmAl@g@`Ay@f@g@Z_@dA_B\\q@d@eA\\aAn@mCNu@TkBDWNwAZoEHmAd@yGDg@LoB`@}E\\cFP{BZyBj@yCH]Pu@DU\\}AVs@Ni@HWDKr@_BBGXe@h@u@X_@V]JOj@k@\\_@~@u@LG^Uj@[jBaAb@UdCwAbAm@`@Wn@c@t@m@zBuBjAeAhAqApAcBlAuApDaErBkC`GqHnPwRX[V[tEmFxA_BlBoBnBmBtEeEtC}BJIfDqC~@{@lBgBhBaBbDmDFGX[t@u@pE}EfBmBpBwBn@y@p@y@tAuBDGb@w@lAsBpC_Fd@q@pAuBd@q@|A_B|FaGVWjBqBxDaE~BgCrAqA`DcEv@_Ap@cAtBeDpAwBjB_DfC_E^m@fAeB|AqBf@i@xD}DxD_EZ[BCRWz@aAbAwATUX[v@{@VUjEmEfBaCD]L[vAoCv@{AVg@T]|@{@v@u@|@q@~HaGVg@d@{@~BwCnAaBp@_AZe@NS\\c@~@mAvAeBzAgBz@eAr@}@hB{BnAcBtAeBbCkCt@u@~A{A`B}Ax@}@r@{@^c@`@m@b@o@p@cA~AcCfAeBn@u@j@k@hBqAx@i@z@g@`Ae@hCcAfDmAl@Wj@Y~@m@p@i@x@{@x@}@t@eAv@oA|@_BrAiCvAcCb@s@f@u@r@{@bA_A~@y@t@k@|BuAlAq@lHoElCaBhBoAzBgBbBwA|@}@jBkBjAiAbAmAbAqAz@oAx@kAx@iA^i@`@g@|@w@dAw@hAo@b@Sx@YfAYhDq@rEs@`Be@`A[nAi@bAm@dD_CxBwArE{BbCsAjC}ArA{@bAu@d@g@v@w@n@y@h@}@fAkBhAsBXg@v@{AdB{C^o@|AyBt@aAjAqAd@g@pAyAd@o@`AmAz@qAf@eAj@sAl@iB^eBN_APqBJ_C?oC?yF?eE?aE?oLD}ADw@TiCTsAT}@Z_ANc@Tq@dA{BtAaCzAkClAyBh@_AnAgBpB_Dr@eAbBsBlHwIxBsC\\c@bAsALOz@sAz@yAfA_CVi@Zo@fAyCbA}CPa@N]`AoCtDgKpAqDBI|BcH`AoCd@eAt@kBdA{CNc@nDqItAkC~GwLhCmEbCgE^q@hAqBjBiDp@qAhAwBp@}AzCkHJUxBaF`AcBn@gAd@o@lAsBf@iAVo@\\iAXgAVwALoA@]Bg@@QBaBRqJDuF?EDeA@{@AcAGaCEaAM}CGyAGqBAWI}EMsEIsCC_BA[?qAHs@\\aEFm@l@gGV{AF_@Nk@d@mBx@_CJQrByCV_@LQlC{Cn@u@v@_AfBuC`@s@p@mA`FkJ`AiB|BeEj@gAtAsCVu@r@iBlAwDRm@l@}B|@aD\\iALe@^oAdFuRLa@bCaKTgALk@p@uFFaAHoADs@|AyRv@aJFg@PqBn@uDn@}Bh@eAZo@jA}ApDgDNOhJeJV[n@iAFIDOn@mBd@{AZcBJ_BLaAXmDr@}Cb@oAp@}AtAuBjCaDj@s@tAcBnBmBrF_HnEeGjEgHxCaFJc@hLmSxKuRnD_GzCeFtA{B|AeCz@mA|@iAdBoBpCiC|DwCjBsAnCcCTUdI}G`IwGzAoA~EgEtAcBx@qAj@iAb@qAh@iBrBeH|BcIr@{BjAkDp@aB^o@R[dBuB^e@j@i@t@g@n@]n@[bAc@XI~Bo@jA[dEiAdCq@bBe@d@MnAa@t@SdAWRGvBk@PElBi@rDaATG`Bc@|C{@~Bm@p@SjD}@tBi@h@Od@MfKqCvF{AdFuAd@Md@QfCgAvH{E`GuD|EaDlCsBjNoIjC}A`ASLGfB{@dBiAt@o@DEj@}@^e@jHsGnQwM~JqInJcIxJcIhCwBbOcMzH_IbDyCpDyCtD}CpDyCdLoJn@k@bBwAj@g@ZYjA_AhAy@PKRK`@Ub@OTKLC|@S~@SvB_@`N{B`KaBpEs@PCdDg@xB_@vDm@vB_@nFkAdCg@vDw@t@OtFmAfCi@dOiD~KcCFAZMPIpHgBpAY~EgADA~D{@`EaAnCo@n@OjEcARETG^KVKZMRKb@[ZWXa@TWz@sA|CmEj@_ApDkFpG_KnAkBDCHGNEd@}@jNgThC}DT_@fEsG|CsE|DkG~@uAn@cAtAwBp@gAdAeBXa@hBqC^k@P[Te@Nc@No@VkBF_@VoCDi@p@iL@QTcEDo@ReDp@eITqFBi@Fg@PmAHe@`@qBXuAr@iELaA@MFm@RuCP}GB{@?A@e@HyBJsBHyCDs@Bg@FoANyDD_BBg@^kKJyDHoAR}@BMHURi@lBwDt@iAT]\\g@dA}APSn@{@hAwAV]hHiJfDiEn@{@hM{Pf@q@j@w@p@u@vA{AdAgAdAcAnDsDfF{FjCyClBwBfCsCtB{Bb@g@x@}@vC_DtB}BpBuBzCeDbIuI~AgB|EoFdDmDbDqDzGsHjAoAnAsAhFqFVQNMFIBG@IRKTSvBsBnBkB|B_CbAiA`AqAjBgCdBaDvDmHtEcJJSdEgIpE{IJUzEkJ@E~@iB~A}CrAmC~@iBrBkEfC_FHQdC}EbDsGtCyFfCgFxBgEp@sAbC_FdAqBz@kB|@aBbCuE~@_BfAqBbDwF~CmFxD_HjD{FjCsEj@_A|D}GhEaHxBmDnE_HdBcCp@aAp@aAxCqExFgIh@w@|D}F~DkFdG}IjCyD|CgE~AkChAoBpDkGvDoGpCaEnAkBb@o@hDmFrEuGtAsBzAyCj@yA"
                     },
                     "start_location" : {
                        "lat" : 27.6512889,
                        "lng" : 52.4469597
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "53 m",
                        "value" : 53
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 27.2834681,
                        "lng" : 52.92066
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eRoute 96\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qvoeDi__bICQEMGKCCGCMCWA"
                     },
                     "start_location" : {
                        "lat" : 27.2831308,
                        "lng" : 52.9203706
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "213 km",
                        "value" : 213381
                     },
                     "duration" : {
                        "text" : "1 day 19 hours",
                        "value" : 154456
                     },
                     "end_location" : {
                        "lat" : 26.5194265,
                        "lng" : 54.7082451
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by كفرغان العربية (on the left in 197 km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uxoeDca_bIFId@}@f@oAj@uB`@oDBOReEx@aRXeGFoAj@}JTyBn@}D`@mB`@kBl@cCfAyC~AeETm@`EcKnCwGtDwJh@uAhCmGL]@Ah@yAj@cB\\mAZeBHc@\\kBh@aCn@sBp@{A|@aBjAaBt@sAtAaCtA}ChB{Ej@_BNc@p@uBzAsEv@mCZoAd@iB~@{Cz@uBpAwC@AtA}B~@yArBgCLQn@y@v@aAvAgB~AcBl@e@n@c@dAm@~CwAfB{@tBaAhAg@nAm@pAw@^[f@e@hCaDRWfFwG`EkF~@wAj@iAt@gBfA_EjAiG~A_IxAsHz@sEl@aDpAyGh@qCv@_Ex@_ERgAl@aCV}@dA}Dz@yC|AgFf@kBfAoDx@wCV_Ah@cBn@wBhA{DzAmFzAgGv@kD^cBhAcFfByHr@iCn@}BdAiDNc@jAwDzAwE|AiF\\{@Ri@bBwD`CuD`AsAV]`AkAx@cA~AmBlCkDjA_BxD_FbDeE`B_CfBgD~AsCHK|@sAHIbAmA|A_BrFiFrGiIfDgEf@o@hDqEpDwEpCoDzAqBHK|CwDnA{Ab@m@l@_A~EeGLQvAeBxAqBbBsClEeIh@u@fAaAp@k@^YdAo@\\OnAg@dBw@hCqA`CcBvEgDbEaDb@]n@k@\\c@Va@Rc@r@kBpAcEtBeHrCeJz@aD\\eAVmATkADw@?G?A?C?G?E@G@EBEBGBCFGHEHQHMNSHIHMJUNa@@Ib@mAjA_CrJ}QnDwG~@gBHQlA}Bd@cAdBgDHS`@s@|DqHn@yAXw@T}@j@oC~@mFPaAd@kCz@aFXcBt@qENoABW@K@GBo@@E@GAKBK@C@A@A@ABAH]HYH]NgAVsAZmBd@iCBMBMj@_DReAv@{Et@kE|@mF~@kF|@oFfAeG~@uFLo@PaAj@}DX_CTwBVyCPaC^eFd@kHRkCb@uEt@iGt@_GhAkJZcC^wCJw@^{Cp@uF|@aHx@wGb@iDRcBb@mDf@iE\\qCV{BPwAHgAD}ABwAEeBCw@E_AW}B[uBe@sC]{BW{Ag@{CUsAW_BKk@M{@Ks@YqBM{BEw@AqCFwBBa@PeBH{@VkAJi@b@gB\\eATm@Nc@tAkDTg@j@yAjAuCRi@r@aBTg@z@eBTe@dCaFBChCeFVe@bAkBt@sAj@_AjCyDZa@dB_C|@uARY@Ev@_BRi@n@eB^mAH[h@aCj@sCDUfAkFp@aDH_@z@oDbAeDJ[fAuC@GdBkEL[f@mAdAaC~AoDvAiD~@uBZm@^aAj@}AZ{@z@iCLa@j@oBbA}Dn@iDlCkNTcBLoAFgADo@BwBEiEKaFK_D?aB?u@BcBDgAJaARuAj@cD`@aBJe@H[t@_Dj@kC\\oARi@Vo@h@uA^o@Xg@V[h@i@z@w@bCiBjBuAtAsA~@cA@?NQv@gAPUf@sAj@wA|@{CZqALk@l@qCf@gCPaBDUNcBJuB?GLcDTcFNmCJsAPsA@I`@{BLm@ZsAT{@Pw@Vs@Ng@f@}Aj@eB`AaD~DgMxBaIDSRgADQHMt@mETiAXuAr@_CPk@Rq@`@oAj@oBh@}BVqAJaAt@uEv@sE^_CPw@TaA\\}@h@sAh@mAv@_CFSRo@^aAj@eBj@cBd@uAr@yBbAqET{@v@yEH]l@wCPm@To@Xs@d@aAfAuB~BgDnAaCzByEpAwDrEmM~DcMfCaJd@cB|@yCh@eBp@iBp@sAr@mAfAeBv@aAj@q@fAiAf@i@rAiArBiBt@o@vA{AjAkAHADCBAHGDEHEHITOt@[jAk@h@URGLADADCBCDIXw@vBqFtCuHRm@n@aB|CyI|AgElAcDvBuF|CuHz@{B\\oAPs@LaADu@@s@Cw@EoAEoAE_AI}ACyAGyAEoABg@Fk@Lm@X}@Vo@l@_Bd@oAn@}Ad@qAf@sAb@mAn@cBn@_Bn@aBh@uAd@oA`@iA\\eAb@gAZaAj@{Ar@gBl@{A~@cCbAiC\\_AZaA^cAb@oARm@ZkA\\qAfAuD`@{An@}BZmA\\mAd@eBf@mBb@oBXkAXqAXcAZqAVy@`@cBXgAZoAPs@La@To@N[Tc@Ve@f@w@`@k@`@a@`@c@b@_@`@]l@a@p@a@~BoAvAw@bB}@jC}AzBgATK~A{@d@Y~@q@TQ\\_@PWPULUZs@Ru@Lo@Ji@Dk@D[DWFi@VgCHo@TuBReBJo@XkCDe@H{@Fg@F_@Fa@Py@XaAh@}AXk@Zq@`@o@b@u@f@w@`@w@Vi@To@V{@V_Al@eCnC}LtBeJ\\gBl@eCLg@Ty@`@wAh@wBV{@b@{A`@_BdAaEd@kBf@cBn@mBh@wAl@aB\\{@d@qA~@qCPg@d@_BZaAlAiErA_FvAcF|@}C`AqD^gBFUBSPmAN{AVgCH}@HaAXgEPsBDw@DcABw@BaAFgCF}CNkB@[@KBg@Dg@Bg@?E\\wCTsBXkC\\kBp@uDjAwHp@kFNgAD]L}@Jq@JaAJo@X}BZyBXwBX_CR_BHg@NeAHu@DWBUDSD]PsAHm@RsA`@qDNqA^iDV_CL}AJ{@PeBDg@Ho@Dk@Fe@N}AD[D_@Fg@N_BFk@LuAD]N_BNyANaBTwBB_@LeAXqCL{AB[P}ANyARyBl@yFP{APkB`@}Db@qDLw@Lw@Jw@Hu@PiANiAF[BUJ{@Fe@BSF_@PqANmAPiAHs@ZwBJs@BSLaAJu@fAmI|@sGl@eEP{APkAF]TmBJ{@`@uCLcADWHo@ZwBr@kGh@{Dl@yE`AyHp@wF|@aHp@sFl@}EXaCLeA`@yCz@aHh@{En@aFPuAj@uENoAdAmIf@}Dl@gEx@qGl@mFb@eDNcARu@b@iAb@cAl@sAp@oAdA}AtBkCrAaB|F_Ix@kAhJeM`EsFxBqCr@y@h@w@`@m@b@w@N]Pa@Z{@t@iCbB}FtFqTZeAjBmHfC}J`A{DrE_QrFgS|B{IxBsIZ_BNoAPuB?m@@i@IgD[yKQgLByBFgCLmBT}BXgCRuAr@mDXcAV}@R}@d@sBt@gCjAcEpA{Ej@wBPq@h@oBXmA`@yAFQDQP_@FSj@aAv@iAdDoEhAwAl@}@Zo@b@_An@mB~A}Ex@qC`BcFFWfAsD~AuFdAuDLe@\\mA`@sA`@uAbAeDv@eDfAoFHg@XqC^gFB}DE{ECgGA_@AoACsCAwFBcCDeDNwCf@{Fp@}E^wDn@mG\\cDFc@Hy@~BmSh@kFZwC`@{Dp@kGf@}E`@eEFo@X_EDe@RgDLgDH}EFwF@g@LkJFqFByBBoAJcIFyGVuU@kFCqBE}AEsBMeDKwBAc@e@eIS_DI_CAaBB_E@Y@Y\\kEZeD\\oCn@cDf@oCT{Ah@qD`@eCz@qJDoAPiGBcG@oABkKAkDJgDJeD@[XmEReC`@oDPoAFg@Ly@^sEPuATuBf@{CBQh@eCLm@z@wDp@uB\\}@l@yA`AsBJWnAkCvAuCjAaCdAgCZkAHWx@iCf@yBh@cD\\wBZmBj@_Fr@}Fh@eFJ}ALyBLuCB{@^wZXgVZwJf@iIH{@l@yGpAkJ^mCt@_Er@{CtCuMzCmNb@yBXuAd@sCd@sE~@mIr@mH~@aJn@yGb@yDZmDVaCPcBh@}Fb@{FdAsJB[r@sHh@}Gz@qJv@iIBQj@qGn@qGTiCb@sEx@cJ^}EFaADmBD_BHkAHeA@Mh@cFx@wHLwA|@oJd@oFh@iFh@kFp@gFd@{F|@oIj@uFP_CNeBNmBFgBDyCC{AQqCWgDOoCSwCOyBIiA[_GYsEAMM_Cy@sLAKUwDC]SeEY{EUiDKiBCg@Ew@EeAyAeVKeCBmADkDJyCNeC\\gDP}AVcCbAwGn@uEXoD`@gGf@qJ\\oE?CLqB\\{EHmAXeDF]Ry@Pg@J]@Ab@y@nAsB|BmDpD}FdJyNf@y@dAaBlBsDVo@nFmIx@uAlFsIv@sAjAoB\\k@`HeLn@eAnKyQpFgJhF}I\\i@b@u@hEqHzAeChGqK`C_Ej@_AhD_G`FuIlDiGFKnBiDb@{@hA}BrDyIhAyCfB{EbAgCl@aBVu@XcA\\sA^sA`@eBTaAP_A\\uBLoA`@{DN_CDq@f@uHBg@^yFb@wFl@cMR}FNwGBgAH{FF_DFgCD{D?m@RkKHqFL{GPiJ@oAFaDHeG@SHiE@mBDcCD_BPiFPgDZeFf@gFn@sFZmBdAoGh@yC|@cFJq@d@}B\\qBNy@p@uDBIv@wDj@uBj@wBn@aCRo@v@eCbAcD`BuEtAkDTm@zAiDN[xAaDh@mAr@{ApA{D|@uCHUNu@f@{Bv@}E?Eb@}DRaDFmAl@iJ?CLsB@KXsC^qBHg@Lk@h@gBJ[^aA^cAZs@HStAaDtAsCFMR]LS`@q@|@yAFINSjAyApB_C\\[HGpBgB~A{AzFeFlBeBvGeGVUfCeCbBeBpA}AbDwDnDgF|AyBV]h@aAhBaDhBcDfBcDhDcGpGiL|HiNT_@pBaDTYn@{@xAmBz@_Ar@w@r@u@vAwAzAwAbA{@tBkBNMr@q@`BwAnBeB`FgEl@g@bAy@\\U~EiDjAu@rEwCTOhBeAXQtDaCnHwExBwAtBsAvBqA~@q@z@m@NKJKx@o@t@w@X[VWp@}@d@s@l@gAl@mA`@_A@CZ_AZeAVeAh@iCP{B?IDwAF_CDy@FiDDeD?uCDqCHwCh@gEFm@\\mBBMpAeFRk@Pg@L_@Tg@Zq@LUl@mAb@u@p@eA|@kA~@eA~EwFrA}AnEyFj@w@Xc@Xg@tBcD`BoCbAkB|@cBf@aAbDeGTc@dBeDRa@bAgBlAmBfAwAlAsA|AuAXWvB_BzBqA~Aq@z@]f@MfCu@fD}@tDsAbCqAdBoAJGhC}BzBqBTUHI~@aA`@m@N]HQXgARcA?ARkBHyAr@uJAo@Bw@Bg@Fk@Dc@N_AF]BUTeAV}@j@mBrA}CfAmBdAaBpCsDxJ_MPUz@eAf@k@BAj@m@JMl@k@lAkAzAuA~AuAdBmAdBsA~FeEjFyDfAw@dFyD|DeDVUfDqDtCuDpAmBn@}@`BsCFMtBgEbDuGt@}ArBkEhCkFf@cALUdCqEjAkBrAiBp@_AdByB`GiGdAiAz@_AxBeCpDwEr@_A`AyAf@w@n@cAJO|AgCp@gAj@aApBkDv@wAj@cAfByCp@eAp@mAdByCz@}A`AcBn@iAn@iAt@kA~@aB|AeCz@qAd@s@d@k@hByBzEqEpCeBRKjB}@~Ay@`AYzBq@rHwB`[qIdBe@VIhCs@fGgBjA]rF}AjBi@`DeAtMiEJC`H}BnIsCrAe@|KoD~HmCtEoB|A{@|A}@x@m@f@_@|BiBhBcBxBcCrCoDpAuB~B_E|A{CrBmDpC{EvB_DzBsCjDyDpCmCbCcCjBmBbD}CnCsClEmEjBkCnAyBd@y@p@qAj@qAb@cA`@eA^cAh@cBVy@R_Ar@qCl@sCFYFUFW^_B~@{DNq@VgALo@Js@LcABGDUPmEJgCTuEBi@@YBm@@i@?k@Ae@Eo@C}AI_BKkAg@yDs@uDaAoD_CgImBcGmE{NaCiIgBmHa@eDQcBIeBEsA?aC@eCDqAPcCZmC`@uB`@mB`@cBn@qChA{EhAeHt@}FZcCt@wDZmAj@cCz@mD`B_H|@yDl@iD\\{BPcAD[j@aEl@{Fj@wEb@oEh@gFNgANsAJ{@Hs@J{@`@oDr@uGToBJw@Hk@Lg@Ng@Zm@d@aA`BcD~@iBl@mAjBqDb@w@f@eAx@{Ar@yAvAqC`BcDd@_AfSq`@|DyHlCkFdBiDfAyB`@_A^{@X{@Po@Jk@?AJq@Hw@Fe@Be@Bc@?o@?eA?a@Cy@GuAUsCQ}BWuCWoDUsCU}CQaCQsBKqAOqBIeBCoACeA?i@@]@c@By@@a@Bg@JmBJwA`@oFt@mKTyCV{DFs@LgBJiALcBH}@`@uH|@gL|@iMDu@H}@Di@HqAJuAJ_BJiAP_CNsBx@{LZkEp@wJJuARmCVqDVmDJyAX{Db@{FFiA?AFw@De@LgBb@mGNqBJaBHuAP_E^uIPgEDgBFkAD_ADo@D]Jg@Lm@z@}C|AaGZiApAuEx@_DjAmE~@oD|@eDl@yBf@kB`@{A\\oARu@f@iBbAwDn@_CjAqE|@gDZiAf@kBl@{Bl@yBv@uCf@oBPk@Pu@Po@Jc@H]Pw@L}@JaAp@aHHeAFm@`@gFbAgLLyAReCVkC\\aEHy@Fs@Hy@J}@D]Hm@Js@^{BVwArCgOTkAPcAxBwLhCgNtBkLpC_OvBsL|@}EfA}FTkAh@wC^kBd@gBXw@P_@Pe@Zk@\\g@x@iAt@_A|AkBhA{An@y@z@eAt@aAlAyAt@cA~@kAlAyAlBcCj@q@~AqBz@iAf@q@h@y@n@kAl@uA^_Ab@qARy@ZmAPeAPqAJ_AHuADaADcB?aACu@QeCUgCm@cGc@iG_@wDEg@c@eFy@wIq@qHs@wHg@gF_@cF}@sJIgAGiACsABeBBmABe@De@LoA\\gB`@uAh@yAn@wAtAyBj@u@BEv@y@RQLKv@o@dAq@tE{CtDaCbC}A|AcApD_CzCsBvCkBf@_@`@Wj@_@ZQXS\\UZQt@k@JINONMPOTWLMZ_@X]^m@Xg@Tc@P[Vo@Nc@\\gAVoATwA^iD^cE`@_E^kDPoBL_AJq@Nw@X{Ad@aCr@}DpBkKzAoIhBiJl@oDX}ALgAPgB\\aEf@uFZeDTaCVyCRuBXaD`@sELyALmATmCR_CFq@d@sELoBLy@RiARy@Ty@HUFQv@aCjBcF|AeE`BuEhCiHvByFf@wA~AkEhBaFn@gBj@}AhBgFz@yBp@iBnBqFvA{Dp@mBr@aBh@oA|A{CpB{Dz@_BpB{DzAsCzAyC^w@^q@fAuBL[Ta@\\q@Te@p@oAv@}ArAkC`B_DtAkCr@yAlBwD|A{ChAwBp@uA`@{@HUZw@X}@Ns@RqAT{AJaAp@gFn@}Ej@qEXyBZeCV}BZyBJy@Hs@Fe@Jy@d@uD^qCh@kE`AmHv@mGTeBV}BJw@Hk@D_@Fg@NkAHk@LcAHi@RgAFa@NiAZwAXeB`@oBV_Aj@{CTgAZcBn@mDZeB@IFi@J}@H_AHoAT_DXuDZ}ET{C^oFj@uH`@yFXsE\\qERuCHiANiBD}@Hu@F[Jm@X_AfEuLhA_Dt@qBv@yB~AoEX{@`@gAr@kBd@wAfAuCp@mBJWx@aCnAoDz@cCt@mBz@_CV_ANk@Ji@f@sCtBoLzD{Th@yC`AyFjAsG|@eFn@uDd@cDNcBFwA@kAHeEDiCFoCDqBB_BByAB}AFwC?SFsC@MDwA@iABcAJiAJuAJgAXqBd@gDj@cEf@oDNgARcAx@kE~@oEP{@PeAXoCJ}ADmBb@yj@DoDDsFDwBFw@JaAJs@Ji@f@uBrBiGXaA@GVuAJqABgAE}CGaDOiJAg@MyIWyJOgEKaDKuCAq@AWA]?c@BcA\\{IJ{CN{CJuCJuDJaFT{IVuC^_Eb@wEFq@Du@Dg@BUJsAL{@Lk@Rq@Ri@b@{@bAiAx@s@l@_@z@_@nAc@ZK\\Q\\Qf@Yl@c@j@e@pAiAr@s@^_@`A_Al@o@x@{@b@i@Ve@Tk@Ns@TgBV}BPuALiANuA\\_Dr@eId@eFNcBNeBHkABsAAeAGoAIy@KoAMaAMuA]gD]sDg@{EYuCYsCSkBUgCSgB_@kDU_CUuBWiCU}BK{AEo@CcAE_BGmBGkBI{DGoCCsAGkBIuDIuCGiCQcHEiACqAC{AAq@AmB?aB?uABcADcBJ}FHqCLgEJ_FLyFNiFRkJFkBDuABq@Di@De@Hg@BUFWJe@Ni@Rq@Vq@Zs@h@eAd@}@^y@rAcCnAeCjCgFlA_CrAkC`AkBvAuCfAsBdBeD`AoBl@mANWP]^s@x@aBxBcEbHyMxBgEtJkRtFmKx@yAp@{@NOf@e@|@}@ZY~@s@lKsH`NuJhE{CdHeFtDmC|@y@p@y@l@kAd@oAl@eBbAyCrA{Df@yA`EoLBIrE_Nl@{Ax@_Bl@{@DEj@o@hAkAt@s@hEcE`AgAp@gA^}@Ps@Nu@Hg@Be@Bo@?q@IiDKcDYmIEoAA[EcBMuBI{@My@_@gBWy@_@}@GMq@uAwAiB_FuF}AeBaAuAy@yAg@}Au@yBCKu@uCyEqP_BcGqBeHoA{Di@uAa@gAa@}@gCoF_@mAQeAKaAAeADyAHwARgC`@uFd@qGRkBh@eCx@kBrAkCdA}Av@gAj@w@JOx@q@j@[n@Sh@Ij@Gd@@`@B|@P`@JxHjBnDz@nBXtAJrBAbBGbCc@tAk@zAu@\\Uh@]pCcCpFcFzJaJ`DqCbBoA`B_AzEqBtCu@bJkBdPyClUoE|Bc@|\\kGjL{B~L_C|Z{Fj@KjE}@jLwBzEgAtEyAlCuAbCaBnBqA`GeEzPuLnFuDxHmFjMyIvK}HdBmAhAu@dA}@|@{@z@_AXc@dAwBpEkJxEaKzAcDlBgDxDaH|EyDbJ}Ev@]~GiDv@c@bf@uV|MaH|ImFbAo@~AoApAkApB_CbM}OdOkRhZic@~@yApPsVb@k@nH}KJKlEoGhCeEd@_A\\y@Pk@Pq@\\mBLm@^aDz@iIz@kGD[PyAj@eFb@gDn@iFxByQRcBJ}@Ls@No@h@_BrB}ErMi[bC_G|@wBbQya@lAsCjC_GnLgZnC_GfCoF|PiUVa@jDuF~FmJd@s@tIqMvIsMvD{FfJ}NjLoPlCuCBCTWLMvDkCxMeFnQyGvLcElLaEnMwE|CmA`A_@dC}@PGt\\kLv]uLnI_Dfq@mUb`@_NnAo@~@o@x@q@vAcBx@eAPe@v@mBFOb@oAZsAPmAHkAFgAEcA@w@AKAw@CWEaAKw@Oy@Os@Uw@Um@Oc@Yo@o@iAWc@S[oCyDuBuCsGaJiAaBs@_Ay@kAy@iAq@_AqAkBS]OY[s@Ug@]eA[aAe@sAa@eAa@aAk@qAq@{Aq@{Aq@wAcAyBoAmCcA{BYm@k@oAs@kBCGSk@Y{@k@sBe@uB_@yBKk@UcB]cCa@qCe@eDe@gD[yBOiAu@mFWkBG{@Gk@CsAA_ADwABu@Fk@NsARqARoATy@X}@P_@f@aA|@cBdAqBfCuEh@cAnAcCTa@rByDbAmBf@cA|@}Ad@q@hBeC|GiJp@{@|AwBpBoC`B{BdB_CxAqBfBgClAcB~HqKf@q@pJyMtDeFpBoChFiHn@{@bM}PlBiCfAwArHmKtC}D|@oAhBeCnAcBlD{Ep@_AlAgBrC{D|AuBdE{FdCgDf@s@JOBELOVYXY^[XQZS`@Q`@O`@O`A]r@SxNcEpGgBpDgAzAc@f@On@Oz@Sf@Ij@KVC\\Ct@Ax@?b@?T?|@@~@?pA@|@@r@@D@|@@n@?X?pCBhAEpAObASl@QPIb@Ot@Yl@[\\QXOp@a@t@e@j@YdAm@~HqE|H{DnAs@nOqIjI}EdHaEtAw@|QmKrO_JHErAu@lDsBpReL^UbHuDTOh@[tAo@dBo@pA]p@UjKkCzPgEnIwBz@SfIuBbFoArNmDpHmBnCs@HC`KiCxAa@x@[p@c@r@eAHM^y@xAkD~BcGTi@tCuHdAmCnCsGbAcCnEyK`AwBHSv@sAj@w@Xa@RYj@q@tAsAdC_C~HeHpFsEnAiAXWx@eAr@wAnBgEx@mBn@}AlBaHlA_GdAcGfB_KnEwUJe@~@eFn@yDTyBAyBCyC[oEUwFAgAAg@Ay@PkFJoHRaMDgBFuCBuAJ{HFkC\\sP@a@@{@DmCDqCPsJ`@gTHcFHiDRwNPiINcIVuLF_DPoQ\\{NHwEBwBPiK@k@HsFH}EBcBLoFTkK@yECcAEkBQwH]yPYmLAaAAg@CoAEaBWqMSoKUeISqKWsLAu@w@i`@"
                     },
                     "start_location" : {
                        "lat" : 27.2834681,
                        "lng" : 52.92066
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18.7 km",
                        "value" : 18681
                     },
                     "duration" : {
                        "text" : "3 hours 45 mins",
                        "value" : 13481
                     },
                     "end_location" : {
                        "lat" : 26.5512068,
                        "lng" : 54.88495409999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eRoute 96\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by ورشة الخميري لاصلاح السيارات (on the right in 9.3 km)\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "mqz`Dqe|lIFe@B_@VgJ`@_H@W|@cMp@_KDi@p@_Kv@_MXmDLcBFeA`@sGHgAFgAj@cIF_AZeETsCLaBPeCZiEPmCn@_Jf@sHPsCNaC\\sEBWn@oIz@{K`@eFP_Bb@cHHwAH{FF}FJuHJkKLmHPaORyKRaI@a@\\gHLoBXcGNeECsFIoDaAyF_A_D{@sB_AyBeIiQgC}FiB{D}D_JO_@kEoJuAgD_CeHoCgJcAaE_@gBSaAcE{SOu@kCuLiB}GsAkFiA_Ey@yDi@gDQwAO}AWgECUEkAG_ASuDAOC]W_FMoBMmCCgIAkAO{KKcH?uAYa]GaFAcCEqIGgCMaLIgGSsPC}A?iA@gADaDI_LG_AQcCEaAGoBYuFoAaPa@}EEw@g@mFIyBCwBCkAI{BYgDUaCa@yCY}Ca@aGAM]}Eq@yJq@wKq@mJQyCG{@KeAGi@W{AGWWy@KYMc@Sc@qC_GaBkCmAoBuDeFoFkHSYeCqD}EgHc@o@}@qA}BqDuCaFoCcGiB}DqIeQkCsEmI{No@gAKS{CeFaC_Ea@q@eAiBwAaCOUIQ}A{CSc@a@{@U}@c@cB_@sAo@{BeAsDs@cDc@}AeCwGa@cAy@oBK_@Ss@e@yE_@kCWmA[{@mAwDSc@"
                     },
                     "start_location" : {
                        "lat" : 26.5194265,
                        "lng" : 54.7082451
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "78 m",
                        "value" : 78
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 26.5507122,
                        "lng" : 54.8855089
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at جمارك مدينة لنجة العربية",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ax`aD}u~mITQh@k@b@q@"
                     },
                     "start_location" : {
                        "lat" : 26.5512068,
                        "lng" : 54.88495409999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "14 m",
                        "value" : 14
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 26.5508023,
                        "lng" : 54.8856096
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}t`aDmy~mIQS"
                     },
                     "start_location" : {
                        "lat" : 26.5507122,
                        "lng" : 54.8855089
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 130
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 96
                     },
                     "end_location" : {
                        "lat" : 26.5501579,
                        "lng" : 54.8863273
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ou`aDaz~mId@qAL[j@eA^b@"
                     },
                     "start_location" : {
                        "lat" : 26.5508023,
                        "lng" : 54.8856096
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "150 km",
                        "value" : 149897
                     },
                     "duration" : {
                        "text" : "9 hours 43 mins",
                        "value" : 35000
                     },
                     "end_location" : {
                        "lat" : 25.2628842,
                        "lng" : 55.2829068
                     },
                     "html_instructions" : "Take the \u003cb\u003eBandar Lengeh - Dubai\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDubai – Bandar Lengeh\u003c/b\u003e ferry to Dubai\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by ميناء مدينة لنجة العربية (on the left in 39m)\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering United Arab Emirates\u003c/div\u003e",
                     "maneuver" : "ferry",
                     "polyline" : {
                        "points" : "oq`aDq~~mIz@aAxAsAXUFGFEBCDEDABCHCJGZKh@St@WxFeBnCy@^KVKTKZMRMXO^WrCuBZUPMRKLIRINIXMNGXKTIRGZIbDy@ffIetBxxCkx@bmBui@n_Bai@vbDeeAnjC{~@dwE_{An{G}}BvkFmaBfyCy|@`wNaxDl|NoxDtReFlgEwhAjgImwBffKwnCxrAk]|t@gQb|@sS|yMcrCd\\kGFAn[eG`xC}j@fbA{PtgBaZz~@oNl}AwThj@eHzbAkLvrIg_Az{A{PnhPkhBxcPogBbqFal@jrC_Y~mAcLjpAuK|z@sFlxCoPn|@yFz\\qClYiC|dBoPxaC_XlfAwLlO}Az@KfAOxB_@lAUv@Ql@On@SdCw@nBq@tXcKzBu@`Bc@hAUtC_@jLmAbBMlDYd@E\\CZEb@KZIZOVOTQJKRUNUPWHODKHUHUBMDWFg@Jq@Fk@Be@@W@{@?eAIeDcBmXKcBE{@Co@A_@?YAa@?q@@s@@eA@YBU@M@IBK@I@C@CBC@C@CBEFEFGBABABA@?BAB?@AB?BAB?@?@?B?B?@?@?D?@?@?B@B?D@B?B@B@B@B@FBJFJFJHDBFDBDFFDHBDBB@DBF@FBJDT"
                     },
                     "start_location" : {
                        "lat" : 26.5501579,
                        "lng" : 54.8863273
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 204
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 151
                     },
                     "end_location" : {
                        "lat" : 25.26141,
                        "lng" : 55.2817411
                     },
                     "html_instructions" : "Continue straight",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "_deyCemlpIBL@F@BB@@BB@FBlBrAt@d@TPt@f@ZN"
                     },
                     "start_location" : {
                        "lat" : 25.2628842,
                        "lng" : 55.2829068
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 155
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 117
                     },
                     "end_location" : {
                        "lat" : 25.2606846,
                        "lng" : 55.2830447
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yzdyC{elpId@{@LUTg@Ra@Re@H_@HSJM"
                     },
                     "start_location" : {
                        "lat" : 25.26141,
                        "lng" : 55.2817411
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1147
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 848
                     },
                     "end_location" : {
                        "lat" : 25.2516748,
                        "lng" : 55.2788574
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eGo through 1 roundabout\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gvdyC_nlpIf@AdADfBXdA?b@ApAIN?PAT@NBRH^PBHBDDHBBDDHJJJHBFBDBD@F@NDP@J?LCJELGFGDIDKPAL?H?J@D@FBv@b@|@j@~@n@lCfBb@\\xAdAnDbCfF`DPL\\NlAz@XTFD"
                     },
                     "start_location" : {
                        "lat" : 25.2606846,
                        "lng" : 55.2830447
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "22.2 km",
                        "value" : 22185
                     },
                     "duration" : {
                        "text" : "4 hours 32 mins",
                        "value" : 16329
                     },
                     "end_location" : {
                        "lat" : 25.0920401,
                        "lng" : 55.149071
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eJumeirah St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eJumeirah Beach Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD94\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow D94\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}}byC{skpIVVv@x@VV~@fAZb@^j@b@v@FLrAjC@BBDV`@T\\\\^RRLLVRTPx@h@dGvDr@b@rAx@`@TDBz@h@pAt@jCbBPNXRxCpBbEnCxBzAhAt@`@VxA~@f@XbDpBTN`GxD~DfChBjApAx@t@d@rAx@dF`DpD~Bt@f@pChBf@\\^ZXXv@l@\\TRLb@TdBjAPLBBXP`C~AhAv@ZRTPDB~AjABBLJ`@ZvAbAPLZRl@`@x@f@f@Z~@t@`@XPLJFXPBBbG|D`An@~@l@FF|AhAz@l@`@XbD~Bz@n@JFNLZRdAv@FBdAt@`Ap@n@d@tA~@xCtBtA~@LFLLLH`@XlBtAvA`Ah@^`FvDd@\\PLLJFD`@XtA`ApA|@j@d@RNXPhBlAd@XnAv@FFd@^lA~@|@j@RLZT\\RRL|B|Ad@ZPPZTz@j@jAt@rCpBzAdAPNjExCh@`@NH\\RFD`LrH|K|H|BzAtBxARJFDHDPNLHLHVP\\V~IhGLH|B~AnDfCvAfAjA|@PLFD\\RvAdAZVRLdCvATLRNfF~C~@p@b@X\\VbFrD\\TfAt@rFrDTNb@ZfBjAfAv@lBrAdBlAvA~@f@^`@\\tCzBhE|CNHNLbExCnCjBJJ@?ZTd@\\l@f@v@f@~EnDVPVPPLRPfE|CZTzCrBtA`Ar@f@dAr@nA|@VNLJTLvA`ArClBv@j@bBlAnBvAh@\\JHt@f@ZTrA`Af@\\bAt@NLNLtB|ATPFBRPNJTNRNNLTNPLHF|@n@DBZRz@l@PNNHfAv@x@l@f@^zB~AtAdAHFvA`ANJNLb@ZJFh@`@JHtB`BZPlBxAp@b@rBzAB@\\VFDB@HDrA`A~@n@f@^j@^`@Zr@j@RN`BrAh@`@fBvA\\V`CnBtBfB`Ax@NNd@`@^XJJFDVRjA`Ap@j@p@j@VTj@d@\\ZRPd@^vAfA^XPLd@`@`@^l@f@LHf@`@nAdALJn@h@B@ZV@@|@r@`Av@\\XfAz@BBtCbCf@`@p@h@lAbA~@z@~@v@p@h@zAhA`@\\^\\LJl@h@hBvAPNd@^tBdB|@r@`@Z|DbDbDjCXTx@p@VTFFTRPNp@l@z@t@|@p@ZVNJLJBBjCvBl@`@HL^\\`At@nAdAfAx@bBpAvAfA~AlAtAdAHFbA~@ZXd@`@fDlCbCnBnB~A|@x@p@j@@@XVl@f@h@`@f@`@bCjBr@n@LJd@b@^\\PPRPHFFBNHLF`@NRFTH^Fj@DtA@hACv@ETAnBK|CQf@E^Ch@?R@PBXBVD|Aj@^NJDLH\\P\\ZDBPPp@p@\\ZRLNL\\\\^\\zAvA`@d@jF`Fd@b@NNHF\\\\vDrDb@^tApAdAbAvBvBlAjARRNNdB|ANL^^xCvC~@|@l@j@zCvCdB`Bf@d@fC`Cv@x@n@j@d@b@xHnHbGxFzBtBlApA`HtGjAhANLdAbApBhBdAlA\\`@JLRR@@ZZhAjAx@x@VVFDdBbBbGxFfBdBxExDrArAdAbAh@h@lAjAZXx@t@pBhBjBfBxEtE^^JHDFz@x@l@d@pAnAxAtAjCjCd@b@`BzABBvCpCHH\\Zd@d@\\^HHj@n@f@r@\\`@TXjBfB\\\\v@n@pAdAtArAhA~@n@h@tBfBr@p@Z^vBzB^^RP\\b@b@`@l@h@rArAtCjChAfA^\\xBvBVTZXd@h@"
                     },
                     "start_location" : {
                        "lat" : 25.2516748,
                        "lng" : 55.2788574
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "32 m",
                        "value" : 32
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 25.0917592,
                        "lng" : 55.149015
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eKing Salman Bin Abdulaziz Al Saud St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD94\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "gxcxCuhroIHBLBH@L?F?"
                     },
                     "start_location" : {
                        "lat" : 25.0920401,
                        "lng" : 55.149071
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 315
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 251
                     },
                     "end_location" : {
                        "lat" : 25.0896195,
                        "lng" : 55.14696439999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKing Salman Bin Abdulaziz Al Saud St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD94\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ovcxCkhroInApA~@|@`@^t@t@f@f@|BpB\\Z"
                     },
                     "start_location" : {
                        "lat" : 25.0917592,
                        "lng" : 55.149015
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 129
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 100
                     },
                     "end_location" : {
                        "lat" : 25.0886848,
                        "lng" : 55.14756879999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "cicxCo{qoITAL?NCLCj@KV[T[^k@"
                     },
                     "start_location" : {
                        "lat" : 25.0896195,
                        "lng" : 55.14696439999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "22 m",
                        "value" : 22
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 25.0885326,
                        "lng" : 55.1474323
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at \u003cb\u003eAl Sharta St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gccxCi_roITRFF"
                     },
                     "start_location" : {
                        "lat" : 25.0886848,
                        "lng" : 55.14756879999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 934
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 702
                     },
                     "end_location" : {
                        "lat" : 25.0819188,
                        "lng" : 55.1477969
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ibcxCm~qoIJQ\\a@zC_ET[Va@V]`@i@V]LMPMTO\\Qv@[RGf@MZE^GVCVC\\A^?h@@b@@PBF@F@ZDh@J^LPLr@\\n@b@\\V^ZRRNPX\\n@dAnAhBh@p@"
                     },
                     "start_location" : {
                        "lat" : 25.0885326,
                        "lng" : 55.1474323
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "88 m",
                        "value" : 88
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 104
                     },
                     "end_location" : {
                        "lat" : 25.0814684,
                        "lng" : 55.1470847
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "_yaxCw`roINv@d@l@JLVZ"
                     },
                     "start_location" : {
                        "lat" : 25.0819188,
                        "lng" : 55.1477969
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 259
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 224
                     },
                     "end_location" : {
                        "lat" : 25.0797013,
                        "lng" : 55.1487041
                     },
                     "html_instructions" : "Take the pedestrian overpass",
                     "polyline" : {
                        "points" : "evaxCg|qoID?@?@@@AB?@A@AFGZ]NOLKr@u@X[PQb@a@XYt@o@BAZWVS"
                     },
                     "start_location" : {
                        "lat" : 25.0814684,
                        "lng" : 55.1470847
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "42 m",
                        "value" : 42
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 25.0794604,
                        "lng" : 55.1484079
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eJLT Exit\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ckaxCkfroI@?@?B@BBFFZj@"
                     },
                     "start_location" : {
                        "lat" : 25.0797013,
                        "lng" : 55.1487041
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "30 m",
                        "value" : 30
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 25.0796541,
                        "lng" : 55.148203
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eJLT Exit\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "siaxCqdroI[`@IF"
                     },
                     "start_location" : {
                        "lat" : 25.0794604,
                        "lng" : 55.1484079
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 526
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 386
                     },
                     "end_location" : {
                        "lat" : 25.0764773,
                        "lng" : 55.1443508
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yjaxCgcroITh@h@bAj@`AXZj@v@t@~@~ApBxBfCVVNNTXJHLN@?|AfB"
                     },
                     "start_location" : {
                        "lat" : 25.0796541,
                        "lng" : 55.148203
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1642
                     },
                     "duration" : {
                        "text" : "20 mins",
                        "value" : 1224
                     },
                     "end_location" : {
                        "lat" : 25.0641299,
                        "lng" : 55.1369146
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003eAl Sarayat St\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "_w`xCekqoILTf@j@tAxAPPv@r@^\\d@`@l@b@PL^Tl@Zl@^FBZT@?PLd@`@\\Xv@t@NLj@f@XP?@NNRPTTZRLLNLJJJH~ArAVTl@j@bBtAFDJJr@l@bAx@j@f@|@t@zAlAb@\\DFz@v@FFn@j@\\TTNTLPDRDZBV@Z?t@AVAhAExDGjHO"
                     },
                     "start_location" : {
                        "lat" : 25.0764773,
                        "lng" : 55.1443508
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 25.0641324,
                        "lng" : 55.1368071
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eAl Sarayat St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yi~wCu|ooI?R"
                     },
                     "start_location" : {
                        "lat" : 25.0641299,
                        "lng" : 55.1369146
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 429
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 315
                     },
                     "end_location" : {
                        "lat" : 25.0607116,
                        "lng" : 55.1383336
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAl Sarayat St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yi~wCa|ooIpACjDIR?JALAJALAHC|@[vAcAf@a@VSXQ\\Y\\YJITYLU"
                     },
                     "start_location" : {
                        "lat" : 25.0641324,
                        "lng" : 55.1368071
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 449
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 339
                     },
                     "end_location" : {
                        "lat" : 25.0594394,
                        "lng" : 55.1417079
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eFirst Al Khail St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mt}wCqepoItBgB^g@JMZW^_@VSHIRQd@_@NMJODGFIFQBS@O?WC[CQCGCKEMGOAAUg@KSMWIUYs@"
                     },
                     "start_location" : {
                        "lat" : 25.0607116,
                        "lng" : 55.1383336
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1845
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1403
                     },
                     "end_location" : {
                        "lat" : 25.0510606,
                        "lng" : 55.1263946
                     },
                     "html_instructions" : "Sharp \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eFirst Al Khail St\u003c/b\u003e",
                     "maneuver" : "turn-sharp-right",
                     "polyline" : {
                        "points" : "ol}wCuzpoInAnBPVl@x@LNPNpAbBd@t@`@d@^`@x@`A~B`EXj@NXFNXl@V^T`@HLlApAnAlAX\\HHPRX\\^b@Z^jAnAt@x@ZZBDZ`@RXPVNXLVLTHTFTHXH`@F`@Fb@F`@XtA?HBJ^pBLn@RdAn@jDl@bDTjAf@lCxAxHJj@BNDP"
                     },
                     "start_location" : {
                        "lat" : 25.0594394,
                        "lng" : 55.1417079
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 2047
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1549
                     },
                     "end_location" : {
                        "lat" : 25.0386025,
                        "lng" : 55.1136127
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eGarden Cross Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD59\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow D59\u003c/div\u003e",
                     "polyline" : {
                        "points" : "cx{wC}zmoITjAh@vCRfAJh@FVFXHVJTJTHNHLHLJLRRZXl@h@b@^TTPNFDDFFFDFFLTd@DJBJDJ@NBL@L@J?R@h@Gt@AFITEXAFAF?F?F@F?JBNBJBHBFDHFDBDf@`@xAjAbA~@tAjALLb@\\BB@@XRVR~ApAzAvAZVbBrAXTxAjAd@\\hBjAXRt@h@TNNHLFJDJDNDPBRDX@X?TCTGp@OJELAF?JAJ?L?J?L@L@NBTF`@LFDj@`@NLZVZVb@b@PNfA|@`A|@`BvAfAdARNNJLH"
                     },
                     "start_location" : {
                        "lat" : 25.0510606,
                        "lng" : 55.1263946
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 707
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 575
                     },
                     "end_location" : {
                        "lat" : 25.042246,
                        "lng" : 55.1082301
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit and stay on \u003cb\u003eD59\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eGo through 2 roundabouts\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "gjywCakkoIC@?@A??@A??@?@A??@?@?@?B?@?BQh@yCbEERCHAH?JAX?B?HAF?BADABEDCBA@CBC@C@E?E@OFIFGFOLCDIFa@n@KNU^MZCJAJAFAL?JAFABADCBABCBC@CBEBE@E?C?C?A?EACASJGFGFGJA?U\\?@eBzCWb@o@z@SXADABABADC`@"
                     },
                     "start_location" : {
                        "lat" : 25.0386025,
                        "lng" : 55.1136127
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1299
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 961
                     },
                     "end_location" : {
                        "lat" : 25.0358162,
                        "lng" : 55.1002453
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "aazwCmijoIDFBFBD?F@BAB?FAD?@AB?@?@ABA@@L@FBD@FBBDDDDj@d@PNZVf@`@xBjB~@t@|BnBTPZTRNVNZNVLRHFBHB\\J`@LlBb@h@Ld@Jv@VRDXF`@Lb@Pj@Xb@V@@f@b@d@b@|CnCTVNRJNFLFLDR@FBJ@H@H@H?J?PAPANCPERELGLGJ{CtEG\\"
                     },
                     "start_location" : {
                        "lat" : 25.042246,
                        "lng" : 55.1082301
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 288
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 25.0348476,
                        "lng" : 55.09815620000001
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "{xxwCqwhoI@D@HAFHPBHJJjCxBn@h@PNHHDFBDBJ?D@B?D@D?DAFCJAFCDEHKNe@p@"
                     },
                     "start_location" : {
                        "lat" : 25.0358162,
                        "lng" : 55.1002453
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "61 m",
                        "value" : 61
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 25.0344441,
                        "lng" : 55.0977485
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yrxwCojhoIHFPNNLDFDJXV"
                     },
                     "start_location" : {
                        "lat" : 25.0348476,
                        "lng" : 55.09815620000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "28 m",
                        "value" : 28
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 25.0345921,
                        "lng" : 55.0975294
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gpxwC}ghoI]j@"
                     },
                     "start_location" : {
                        "lat" : 25.0344441,
                        "lng" : 55.0977485
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "33 m",
                        "value" : 33
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 25.0343541,
                        "lng" : 55.0973365
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eqxwCqfhoIn@d@"
                     },
                     "start_location" : {
                        "lat" : 25.0345921,
                        "lng" : 55.0975294
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "78 m",
                        "value" : 78
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 25.0347431,
                        "lng" : 55.0966968
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uoxwCkehoIkAdBAD?BAF@F"
                     },
                     "start_location" : {
                        "lat" : 25.0343541,
                        "lng" : 55.0973365
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 503
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 370
                     },
                     "end_location" : {
                        "lat" : 25.0354013,
                        "lng" : 55.0929994
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "crxwCkahoI@DBBbBxAfB|AJH@D@D@D?D?BABCJcAzA{BpDuApBkAjB"
                     },
                     "start_location" : {
                        "lat" : 25.0347431,
                        "lng" : 55.0966968
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 1965
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1432
                     },
                     "end_location" : {
                        "lat" : 25.0213752,
                        "lng" : 55.0811738
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gvxwCgjgoIlC|BtBfBf@`@bCnBv@n@tAjA@?VTLJhA~@~@v@RNlCzBb@\\dCtB\\VhA`AbBvA~BnB`DhCZXxAjArBdB|BlB\\VZXzAlATRZXJHbCrBr@j@~AnA|AnAh@b@VPB@VPXP`@Pr@\\NDd@RPF@B"
                     },
                     "start_location" : {
                        "lat" : 25.0354013,
                        "lng" : 55.0929994
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 511
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 387
                     },
                     "end_location" : {
                        "lat" : 25.0183044,
                        "lng" : 55.0848069
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "s~uwCi`eoIJ?F?DAB?@AHAx@oAT_@Va@Zc@LQJOHO`@k@d@q@h@{@Xa@bAeB\\QZ]Zg@~@wALIRELG"
                     },
                     "start_location" : {
                        "lat" : 25.0213752,
                        "lng" : 55.0811738
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1159
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 853
                     },
                     "end_location" : {
                        "lat" : 25.0110938,
                        "lng" : 55.0765031
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003e420 Street\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kkuwCaweoI^b@^b@`@j@|BrCh@l@\\`@V\\l@p@DFhArA^d@TXdAnAZ^fBvBrBbCfArAPR`CxCPPt@|@vAfBdAnAtBdCv@|@"
                     },
                     "start_location" : {
                        "lat" : 25.0183044,
                        "lng" : 55.0848069
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 751
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 570
                     },
                     "end_location" : {
                        "lat" : 25.0057625,
                        "lng" : 55.08019710000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e430th St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "i~swCccdoI^ZTTNFJDJBNBZ?\\ETGRMTKPGTW`A{@fAcAfC}BxBwBXUTQdByAPQj@k@j@g@z@u@|@}@RQ"
                     },
                     "start_location" : {
                        "lat" : 25.0110938,
                        "lng" : 55.0765031
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "16 m",
                        "value" : 16
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 25.0056668,
                        "lng" : 55.0800786
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003e430th St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_}rwCgzdoIPV"
                     },
                     "start_location" : {
                        "lat" : 25.0057625,
                        "lng" : 55.08019710000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 274
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 203
                     },
                     "end_location" : {
                        "lat" : 25.0037451,
                        "lng" : 55.0817623
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e430th St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m|rwCoydoIh@g@p@o@l@i@h@e@rAqAj@i@JIFELGBADCJERG"
                     },
                     "start_location" : {
                        "lat" : 25.0056668,
                        "lng" : 55.0800786
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 313
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 236
                     },
                     "end_location" : {
                        "lat" : 25.001822,
                        "lng" : 55.080098
                     },
                     "html_instructions" : "At \u003cb\u003eRoundabout 5\u003c/b\u003e, take the \u003cb\u003e2nd\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "mprwC_deoID?D@B?B?DABAHAFCDEDEDEDK@IH\\BF@B@DBDBFV\\LNnB|BPPtB~B"
                     },
                     "start_location" : {
                        "lat" : 25.0037451,
                        "lng" : 55.0817623
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 267
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 194
                     },
                     "end_location" : {
                        "lat" : 25.0000551,
                        "lng" : 55.07829899999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "kdrwCsydoIdAfArBpBXXhBjB`@f@"
                     },
                     "start_location" : {
                        "lat" : 25.001822,
                        "lng" : 55.080098
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 776
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 564
                     },
                     "end_location" : {
                        "lat" : 24.9949746,
                        "lng" : 55.08357530000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e541st St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kyqwCkndoIpAmAn@o@b@e@j@w@b@_@d@i@h@i@x@{@xA}AhBmBt@u@VY|@gAh@k@bBeBhBmBFIh@e@"
                     },
                     "start_location" : {
                        "lat" : 25.0000551,
                        "lng" : 55.07829899999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 479
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 354
                     },
                     "end_location" : {
                        "lat" : 24.9920001,
                        "lng" : 55.0801421
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qypwCkoeoIf@p@~@fAnAzA~AnB`BnBvExF"
                     },
                     "start_location" : {
                        "lat" : 24.9949746,
                        "lng" : 55.08357530000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 479
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 352
                     },
                     "end_location" : {
                        "lat" : 24.9889359,
                        "lng" : 55.0783925
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_gpwC{ydoIrCyCDAB?@?D@DBJF?@DDZ^bAjAnB~BLNh@n@RVpA|A^d@VZ"
                     },
                     "start_location" : {
                        "lat" : 24.9920001,
                        "lng" : 55.0801421
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "50 m",
                        "value" : 50
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 35
                     },
                     "end_location" : {
                        "lat" : 24.9884839,
                        "lng" : 55.0784183
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{sowC}ndoIzAE"
                     },
                     "start_location" : {
                        "lat" : 24.9889359,
                        "lng" : 55.0783925
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 km",
                        "value" : 3640
                     },
                     "duration" : {
                        "text" : "44 mins",
                        "value" : 2649
                     },
                     "end_location" : {
                        "lat" : 24.9661772,
                        "lng" : 55.0526802
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_qowCcodoIxAfBh@n@rBbChAvAn@v@`AhAd@l@fAtAxA`B`CxCrArBEFCDAFAD?F?F?F@DBJDFDDBDRFD@F?D?FADAHEfA~@`AjAbFxF~D`FbJtKhDfEt@~@lC`Dp@v@d@j@xBhCTXjBvBvBhCFJFNFL@N@NCDAJ?H@F@B?@@DBB@BBBBBBBB@B@D@B?F@FAB?L@N@H@FBLJdC|Cn@t@f@n@rA`BX^dDzDlAxA`EzEvA~A`BrBDDrB`CDFtA~Av@bApAzA~AnB~@hAx@~@X^Zb@RTHHNVFHHPFL"
                     },
                     "start_location" : {
                        "lat" : 24.9884839,
                        "lng" : 55.0784183
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 183
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 133
                     },
                     "end_location" : {
                        "lat" : 24.9670816,
                        "lng" : 55.0512838
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "sekwCgn_oI@N@J?JANELELONED_@^MLy@|@GFABAB?@?D?F_@`@"
                     },
                     "start_location" : {
                        "lat" : 24.9661772,
                        "lng" : 55.0526802
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "35 m",
                        "value" : 35
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 24.966862,
                        "lng" : 55.05109179999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gkkwCoe_oI@D@F@DBDDDB@B@F@J?"
                     },
                     "start_location" : {
                        "lat" : 24.9670816,
                        "lng" : 55.0512838
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 599
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 434
                     },
                     "end_location" : {
                        "lat" : 24.9706636,
                        "lng" : 55.046918
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{ikwCid_oIkIzIsAxAgHrHWZITGPER"
                     },
                     "start_location" : {
                        "lat" : 24.966862,
                        "lng" : 55.05109179999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 471
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 355
                     },
                     "end_location" : {
                        "lat" : 24.9679687,
                        "lng" : 55.04341239999999
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "salwCgj~nI?F?B?B?D?DADFZBNDPJVHJfBrBh@t@|@dAf@j@xA~Av@z@\\d@z@dANT"
                     },
                     "start_location" : {
                        "lat" : 24.9706636,
                        "lng" : 55.046918
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "23 m",
                        "value" : 23
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 24.968102,
                        "lng" : 55.04323369999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003e\u003cspan dir=\"rtl\"\u003e940 Street\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ypkwCit}nIYb@"
                     },
                     "start_location" : {
                        "lat" : 24.9679687,
                        "lng" : 55.04341239999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 149
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 111
                     },
                     "end_location" : {
                        "lat" : 24.9674877,
                        "lng" : 55.0420099
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003e940 Street\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sqkwCes}nIb@d@p@t@HJDHFJBLBNBN@N?NAf@"
                     },
                     "start_location" : {
                        "lat" : 24.968102,
                        "lng" : 55.04323369999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.7 km",
                        "value" : 2746
                     },
                     "duration" : {
                        "text" : "33 mins",
                        "value" : 1999
                     },
                     "end_location" : {
                        "lat" : 24.958238,
                        "lng" : 55.0170153
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit toward \u003cb\u003eAl Hesah St S\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "ymkwCqk}nIAD?D?B?@AD?D?H@J@HBJBHBHBHDHDHFFFFFFFDFDHDJDB?@@B?B@@?F@x@n@JHJNJNFLHNDPH\\BNb@`BT`Ad@hBp@pCtBtI@DlA`FlB|Hd@hBjA`Fd@hBd@jBDNLh@FRF\\Nl@VbAZrAFT?@dBdHh@rB~@xDdBdHBJlC|KHXjCtKf@rBpAnF^tAvAdG"
                     },
                     "start_location" : {
                        "lat" : 24.9674877,
                        "lng" : 55.0420099
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.7 km",
                        "value" : 2747
                     },
                     "duration" : {
                        "text" : "33 mins",
                        "value" : 1997
                     },
                     "end_location" : {
                        "lat" : 24.9780628,
                        "lng" : 55.0043899
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_tiwCkoxnIc@TOHWJiCpAeEtB}C|AkCvAMFYLi@Xk@XwAt@g@TSHODG@G?Q?OASCCCCAAAA?CAA?CAA?C?C?A@A?C@A?C@CBOFE@K@K@O?c@Ag@Ai@AM?eAAq@C_@AU?O?M@MBOBSFOD?@WJYLs@ZmAf@mAh@MDyAl@y@^_E`Be@R]NMFKFKJKHKJIJILINGNGPEXGb@YjBETE\\Kj@EXGVGRGRGFKLMNOLYNoB`A}Av@e@TMDGBG?I?Q@CAAAA?AAC?IAG@C?C@E@CBC@CBCDEJAB?@AB?@EJKNGHKJKFw@b@[NQHQFM@OBK?K?KCEAICGCGEGEKMMAKAK?OAG@G@IBIDYNm@Vi@RgAb@m@Xa@T_ChAMH_@Ta@TCDCBA@CBC@E@G@OJKDOLIHMN[pBG^q@hDIl@"
                     },
                     "start_location" : {
                        "lat" : 24.958238,
                        "lng" : 55.0170153
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 573
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 414
                     },
                     "end_location" : {
                        "lat" : 24.9823151,
                        "lng" : 55.0018561
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "{omwCm`vnIM^KXCHERO^UX]\\mAv@_Bv@m@\\sBhAMJGDIJKJMLSLQJYHUF[Hs@NQDSD_@DY?WEUE_@KME"
                     },
                     "start_location" : {
                        "lat" : 24.9780628,
                        "lng" : 55.0043899
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18 m",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 24.9823206,
                        "lng" : 55.0016737
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ojnwCspunI?d@"
                     },
                     "start_location" : {
                        "lat" : 24.9823151,
                        "lng" : 55.0018561
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2139
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1543
                     },
                     "end_location" : {
                        "lat" : 24.9994412,
                        "lng" : 54.992947
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ojnwCmounI[IWCY?g@Dm@Nk@Ra@Rk@Zo@\\_@P{BfAuBdAuAj@q@b@_D~AqBbAKFy@\\c@Lc@Fa@B_@F[Ja@Rc@VuA`Ao@d@y@p@_@V[J_@He@L_@La@TyAjAaCbBy@p@q@f@sCbCa@b@_@ZOHQFQDa@F}@Ni@NcAZa@Lw@\\i@RaDzA}Aj@qAj@_@Lo@D{CAw@?o@@k@Jy@X"
                     },
                     "start_location" : {
                        "lat" : 24.9823206,
                        "lng" : 55.0016737
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "49.1 km",
                  "value" : 49125
               },
               "duration" : {
                  "text" : "10 hours 7 mins",
                  "value" : 36400
               },
               "end_address" : "1 Sheikh Mohammed bin Rashid Blvd - Downtown Dubai - Dubai - United Arab Emirates",
               "end_location" : {
                  "lat" : 25.1983113,
                  "lng" : 55.2724376
               },
               "start_address" : "Palm Jebel Ali - Mina Jebel Ali - Dubai - United Arab Emirates",
               "start_location" : {
                  "lat" : 24.9994412,
                  "lng" : 54.992947
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2139
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1542
                     },
                     "end_location" : {
                        "lat" : 24.9823206,
                        "lng" : 55.0016737
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ouqwC}xsnIx@Yj@Kn@Av@?zC@n@E^MpAk@|Ak@`D{Ah@Sv@]`@MbA[h@O|@O`@GPEPGNI^[`@c@rCcCp@g@x@q@`CcBxAkA`@U^Md@M^IZK^Wx@q@n@e@tAaAb@W`@SZK^G`@Cb@Gb@Mx@]JGpBcA~C_Bp@c@tAk@tBeAzBgA^Qn@]j@[`@Sj@Sl@Of@EX?VBZH"
                     },
                     "start_location" : {
                        "lat" : 24.9994412,
                        "lng" : 54.992947
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "18 m",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 24.9823151,
                        "lng" : 55.0018561
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ojnwCmounI?e@"
                     },
                     "start_location" : {
                        "lat" : 24.9823206,
                        "lng" : 55.0016737
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.3 km",
                        "value" : 3321
                     },
                     "duration" : {
                        "text" : "40 mins",
                        "value" : 2420
                     },
                     "end_location" : {
                        "lat" : 24.958238,
                        "lng" : 55.0170153
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ojnwCspunILD^JTDVDX?^EREPEr@OZITGXIPKRMLMJKHKFELKrBiAl@]~Aw@lAw@\\]TYN_@DSBIJYL_@Hm@p@iDF_@ZqBLOHINMJENKFADABABC@ABCBE`@U^ULI~BiA`@Ul@YfAc@h@Sl@WXOHEHCFAFAN@J?J@L@JLFDFDFBHBD@JBJ?J?NCLAPGPIZOv@c@JGJKFIJODK?C@A?A@CDKBEBCBABCDABAB?FAH@B?@@@?@@B@PAH?F?FCLEd@U|Aw@nBaAXONMLOJMFGFSFSFWDYJk@D]DUXkBFc@DYFQFOHOHMHKJKJIJKJGLG\\Od@S~DaBx@_@xAm@LElAi@lAg@r@[XMVK?ANERGNCLCLAN?T?^@p@BdA@L?h@@f@@b@@N?JAJADANGBCBA@?BA@?@AB?B?@?B@@?B@@?@@DB@@RBN@P?F?FANERIf@UvAu@j@Yh@YXMLGjCwA|C}AdEuBhCqAVKNIb@U"
                     },
                     "start_location" : {
                        "lat" : 24.9823151,
                        "lng" : 55.0018561
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2624
                     },
                     "duration" : {
                        "text" : "32 mins",
                        "value" : 1919
                     },
                     "end_location" : {
                        "lat" : 24.9669232,
                        "lng" : 55.0411174
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_tiwCkoxnIwAeG_@uAqAoFg@sBkCuKIYmC}KCKeBeH_AyDi@sBcBaHAC?AGU[sAWcAOm@G]GSMi@EOe@kBe@iBkAaFe@iBmB}HmAaFAEuBuIq@qCe@iBUaAc@aBCOI]EQIOGMKOKOKIy@o@"
                     },
                     "start_location" : {
                        "lat" : 24.958238,
                        "lng" : 55.0170153
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 272
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 205
                     },
                     "end_location" : {
                        "lat" : 24.968102,
                        "lng" : 55.04323369999999
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003e\u003cspan dir=\"rtl\"\u003e940 Street\u003c/span\u003e‎\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "gjkwC_f}nIC?CAA?CAC?AAC?KEIEGEGEGGGGGGEIEICICICICKAIAK?I?E@E?A?C?E@E@g@?OAOCOCOCMGKEIIKq@u@c@e@"
                     },
                     "start_location" : {
                        "lat" : 24.9669232,
                        "lng" : 55.0411174
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "23 m",
                        "value" : 23
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 24.9679687,
                        "lng" : 55.04341239999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sqkwCes}nIXc@"
                     },
                     "start_location" : {
                        "lat" : 24.968102,
                        "lng" : 55.04323369999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 455
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 332
                     },
                     "end_location" : {
                        "lat" : 24.9706654,
                        "lng" : 55.0467547
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ypkwCit}nIOU{@eA]e@w@{@yA_Bg@k@}@eAi@u@gBsBIKKWEQCOG["
                     },
                     "start_location" : {
                        "lat" : 24.9679687,
                        "lng" : 55.04341239999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 615
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 457
                     },
                     "end_location" : {
                        "lat" : 24.966862,
                        "lng" : 55.05109179999999
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "ualwCei~nI@E?E?E?C?E?EDSFQHUV[fHsHrAyAjI{I"
                     },
                     "start_location" : {
                        "lat" : 24.9706654,
                        "lng" : 55.0467547
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "35 m",
                        "value" : 35
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 24.9670816,
                        "lng" : 55.0512838
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ikwCid_oIK?GACACAEECEAEAGAE"
                     },
                     "start_location" : {
                        "lat" : 24.966862,
                        "lng" : 55.05109179999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "25 m",
                        "value" : 25
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 24.9669177,
                        "lng" : 55.05145280000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gkkwCoe_oI^a@"
                     },
                     "start_location" : {
                        "lat" : 24.9670816,
                        "lng" : 55.0512838
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.8 km",
                        "value" : 3798
                     },
                     "duration" : {
                        "text" : "46 mins",
                        "value" : 2758
                     },
                     "end_location" : {
                        "lat" : 24.9884839,
                        "lng" : 55.0784183
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "gjkwCqf_oI?G?E?A@C@CFGx@}@LM^_@DENODMDM@O?KAKAOGMIQGIOWIISU[c@Y_@y@_A_AiA_BoBqA{Aw@cAuA_BEGsBaCEEaBsBwA_BaE{EmAyAeD{DY_@sAaBg@o@o@u@eC}CMKGCIAOAMAE?I@EAA?EACACACCCCCCACCCAE?AAE?CAE@K@G@CAOAOGMGOGKwBiCkBwBUYyBiCe@k@q@w@mCaDu@_AiDgEcJuK_EaFcFyFaAkAgA_AC@EBE@G@E?G?EASGCEGGCICGAE?G?G?G@E@GBEDGsAsBaCyCyAaBgAuAe@m@aAiAo@w@iAwAsBcCi@o@yAgB"
                     },
                     "start_location" : {
                        "lat" : 24.9669177,
                        "lng" : 55.05145280000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "50 m",
                        "value" : 50
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 24.9889359,
                        "lng" : 55.0783925
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_qowCcodoI{AD"
                     },
                     "start_location" : {
                        "lat" : 24.9884839,
                        "lng" : 55.0784183
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 479
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 350
                     },
                     "end_location" : {
                        "lat" : 24.9920001,
                        "lng" : 55.0801421
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{sowC}ndoIW[_@e@qA}ASWi@o@MOoB_CcAkA[_@EE?AKGECEAA?C?E@sCxC"
                     },
                     "start_location" : {
                        "lat" : 24.9889359,
                        "lng" : 55.0783925
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 479
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 356
                     },
                     "end_location" : {
                        "lat" : 24.9949746,
                        "lng" : 55.08357530000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_gpwC{ydoIwEyFaBoB_BoBoA{A_AgAg@q@"
                     },
                     "start_location" : {
                        "lat" : 24.9920001,
                        "lng" : 55.0801421
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 680
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 497
                     },
                     "end_location" : {
                        "lat" : 24.9994064,
                        "lng" : 55.0789341
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e541st St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qypwCkoeoIi@d@GHiBlBcBdBi@j@}@fAWXu@t@iBlByA|Ay@z@i@h@e@h@c@^k@v@c@d@"
                     },
                     "start_location" : {
                        "lat" : 24.9949746,
                        "lng" : 55.08357530000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 96
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 25.0000551,
                        "lng" : 55.07829899999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003e541st St\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "iuqwCirdoIo@n@qAlA"
                     },
                     "start_location" : {
                        "lat" : 24.9994064,
                        "lng" : 55.0789341
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2245
                     },
                     "duration" : {
                        "text" : "27 mins",
                        "value" : 1644
                     },
                     "end_location" : {
                        "lat" : 25.014504,
                        "lng" : 55.093616
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kyqwCkndoIa@g@iBkBYYsBqBeAgAuB_CQQoB}BMOW]CGCEAEACCGI]@E?E?C?C?EAC?ICGCECCAEECCCA?AAECIACA]IICKGICOMOKQSIKU[g@o@oFqGoA{Am@q@gAuA_@c@aBsBmBaCUW_BeBW[Y[GIOQ}D}E}AoBQQa@c@gCcC}@w@i@e@e@[UQ_@YWQUQMKYSIIQKYUm@e@MIAAMKs@k@USWUo@i@a@a@g@k@IGGM"
                     },
                     "start_location" : {
                        "lat" : 25.0000551,
                        "lng" : 55.07829899999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.1 km",
                        "value" : 4101
                     },
                     "duration" : {
                        "text" : "50 mins",
                        "value" : 2995
                     },
                     "end_location" : {
                        "lat" : 25.0166491,
                        "lng" : 55.133287
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eD57\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sstwCcngoI[[m@u@q@}@aAoAs@gAa@{@O]}@iB_@y@c@qAM]CIa@gA_@mAI[Om@S}@W}AOoAQkBKaAKaBAUIyA?MMcC?c@?Y?W?oA@mEBaBHkEDoBBgCNqMDeDDwALsIFcIFwC@g@@e@@g@NcHTwK@e@?S?AFeCHkEBs@`@yO@o@X_MPyM@eA?iSA_GA}@"
                     },
                     "start_location" : {
                        "lat" : 25.014504,
                        "lng" : 55.093616
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 637
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 498
                     },
                     "end_location" : {
                        "lat" : 25.0165394,
                        "lng" : 55.139592
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "aauwCafooIJ_@D_@@g@@mF?IAY?M@aA?g@@gA@kC?E@_A@kH?O?MGuC"
                     },
                     "start_location" : {
                        "lat" : 25.0166491,
                        "lng" : 55.133287
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "12.2 km",
                        "value" : 12226
                     },
                     "duration" : {
                        "text" : "2 hours 32 mins",
                        "value" : 9118
                     },
                     "end_location" : {
                        "lat" : 25.094147,
                        "lng" : 55.203852
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAl Asayel St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD72\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "k`uwCmmpoIq@?W?A?E?]?C?_@?c@?c@AI?k@?kBCg@@m@?S?}@@WAc@?AAe@?kGN_A?wCBs@?aAA]@oED_B?u@AoA?qC@uA?gA@c@?wEFU?S?}C@eA?{C?YCOIaCBuBKoAW_@MaA]oAm@y@q@QOuC{Bk@g@{@u@OOkAgA{@u@{AkA}@aAKKEEQQkAaAo@s@YYoAmAkAiAiDuC_@[yAmAgA_Au@{@gAqA[w@Wm@CIIUOi@S}@Sy@Cc@ImAG_BAEE{C@gADeA@SH{@L_AVwAXoANm@Po@Rs@Li@TaAJ_BGgBO}AAKIs@K]Sg@I[o@_B}BoDyAuFm@aEQ{@Su@Qk@Qa@Qa@Q[a@q@a@q@W_@e@m@]a@]_@Y[o@m@KIWUIKUSk@k@k@e@OMiBwAWSkAmA}CuCiC{BcB}AaAaAu@u@MKAAIImAgA}@{@QOoBkB_@]y@w@kAcAEEs@q@yCqCsAuAW]Y]IKOQg@g@KKw@s@s@m@_@]KIGGOMy@u@QQa@_@SSu@w@UWkAkA_AkAs@_AgAoAm@}@_CmD[e@aCiE}AyCaBoDGQK[MS]y@yA{D{@kCu@mCc@aBKe@e@qBwA_GACYaA]cAUo@[{@Sg@Sk@S_@IOkA_CACs@iAkAcBo@y@]]]c@UUqBoBwDsDwCsCCA[Y_A}@QSSU}AwA{ByBWWWSUUW]YWa@_@cAaA}A}As@u@k@m@IIIKa@Y[Q]W[Yy@w@mGcGiBcBSSsAoAKIuBuBGGkBeB_B{A_A{@o@m@eAcAk@k@IIm@g@e@Wk@[}@a@q@SKCSGMEA?wAS_BIsAAiCTg@Jw@Tg@Re@Ry@d@_Aj@}A|@SP}@l@c@X[R[RIFA@a@ViDtBOJsBjA_AX}@Rk@Jg@DwABm@IoAUu@UYMQMYOuAcAwAgAcAs@u@g@iBsAc@[UQQMCAWUkAy@QMoDqCu@m@mAgAg@c@kEuDsAiA_@[m@a@OKGC_@[YOUGMEUEKAa@C]AO@"
                     },
                     "start_location" : {
                        "lat" : 25.0165394,
                        "lng" : 55.139592
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "16 m",
                        "value" : 16
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 25.0941559,
                        "lng" : 55.2040081
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e329th Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "medxCa_}oIA_@"
                     },
                     "start_location" : {
                        "lat" : 25.094147,
                        "lng" : 55.203852
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 246
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 184
                     },
                     "end_location" : {
                        "lat" : 25.0962291,
                        "lng" : 55.2032578
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e329th Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAl Asayel St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD72\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "oedxCa`}oIWBUBQDMFC@i@ZUJc@Vi@RMFMDK@SFSDOB}AF"
                     },
                     "start_location" : {
                        "lat" : 25.0941559,
                        "lng" : 55.2040081
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1394
                     },
                     "duration" : {
                        "text" : "18 mins",
                        "value" : 1053
                     },
                     "end_location" : {
                        "lat" : 25.1072569,
                        "lng" : 55.2048364
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e23rd St\u003c/b\u003e (signs for \u003cb\u003eAl Barsha 2\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mrdxCk{|oIGGECEAGA]@I@C?C?C?AAC?CAC?AAAAAAIGGICAIEEg@Mu@I]IYQg@Qa@Ug@Yc@EIKOSUMM[]]YIEEEOG_@UUMSIs@UaAUc@G[As@EmA?U@qAD}@BqDHwELgAD{ELW@q@Ho@DoAR[DqBd@m@Va@Pe@TQLi@Zo@^"
                     },
                     "start_location" : {
                        "lat" : 25.0962291,
                        "lng" : 55.2032578
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 599
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 444
                     },
                     "end_location" : {
                        "lat" : 25.1117986,
                        "lng" : 55.2077432
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFirst Al Khail St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD86\u003c/b\u003e (signs for \u003cb\u003eD921\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAl Quoz Ind\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrade Centre\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kwfxCge}oI_@DK@GBW@WAE?EAE?[CkA{@eAs@_Am@c@YOIs@e@i@]GEi@]_CeBoCuBsAcA"
                     },
                     "start_location" : {
                        "lat" : 25.1072569,
                        "lng" : 55.2048364
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "4.4 km",
                        "value" : 4364
                     },
                     "duration" : {
                        "text" : "55 mins",
                        "value" : 3277
                     },
                     "end_location" : {
                        "lat" : 25.1445016,
                        "lng" : 55.2298245
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eFirst Al Khail St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD86\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow First Al Khail St\u003c/div\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "wsgxCkw}oIa@Yy@m@IGGEe@[MI]SwJoH{@q@uAeAWUSQaAu@oA{@cA{@kAq@{@e@GCKCe@OMCICWGqAOo@GqAI}@@Q@q@Fg@Hq@Pi@Ns@Ls@Ja@Be@@w@@u@E}@Iq@Me@Ka@MYK[Mc@Ua@Us@g@kA}@eAw@o@g@WQk@a@SQqA_AqAaAo@c@YSeEaDy@o@CAmCqBu@k@SOQO_@SYS}AkAo@g@IGu@m@cCiB_BqA]UYQ[Se@_@yC{B_@YWSMIm@e@eCiB[WMIs@k@_BmAKIo@i@c@]iCoBwAcAOKk@e@uAiA_@Y{@i@e@[uCqBq@g@]W_@YgBwAII_BiAKI[WwAeAwAeAiAw@e@_@sAiA[WeBwAu@m@OOm@e@YSAA}@k@eDiC"
                     },
                     "start_location" : {
                        "lat" : 25.1117986,
                        "lng" : 55.2077432
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "7.7 km",
                        "value" : 7669
                     },
                     "duration" : {
                        "text" : "1 hour 35 mins",
                        "value" : 5722
                     },
                     "end_location" : {
                        "lat" : 25.1972047,
                        "lng" : 55.2692183
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eFirst Al Khail St\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "c`nxCkabpIMQKIKKMK}@m@WOAAYUIGqA}@u@e@k@]e@W[UYSwDsCgFyD]W[U}BeBaBmAoGyEuAeAw@m@k@[GGQMa@Og@Oa@K[CSGQGg@Ga@CY?[?mAFa@?u@A_@?{BEw@?[AYA]E]Eg@IWIIC]KQIEASMYOWQ]W}@y@]_@[]SQMOqBkBgBcBEEw@q@[[e@e@gAoA{@_AOU{@qAwBcDa@o@s@eAi@_AUg@k@{ASs@Qq@Km@My@M{@E]WyAOm@GOAGGQIQEIYo@MSYa@i@u@IIIGqAmAyBmBsDqC[WqBeB{DqD{@eAWUa@a@cA_A]_@eAwAqB{Bw@w@iAgAaFoEw@s@A?oG{F][a@c@i@k@GGY[QUWYe@a@iAkAUSUUCCSSUUqAkACEWSUS[WSOGIW]W[Y]CEQWGMISEKMUS_@MSGIY]W[Y[GISO]U[W]UKIQK]W[U]S?A]U[UAA_@OAA_@KCA_@IYC]Aa@?]@q@HSBSFA?ODIBIBIDKFm@^GDKHUTWXEFs@lAmAvBaAlBMVMTQTKJA@KHOLMJYNQHIDEBUHQDODSDWBYBU?W?I?QAA?EAQCGAWEu@UUMGE{@q@[WOMKIu@s@k@i@II{AuAeDqCUQEEkC}BACq@o@c@a@k@i@KIYYOOSQGEw@s@QQc@a@SQuBmBiAcAGGiG{FYY[Y[YEESS[WCCWU[YWWAA[W[Y[Y[YYWOMEEEE[W[Y[W[YOMKI[YA?[W[W[WKIOM[Y]W[WCCYQm@a@]SyCgB"
                     },
                     "start_location" : {
                        "lat" : 25.1445016,
                        "lng" : 55.2298245
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 254
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 186
                     },
                     "end_location" : {
                        "lat" : 25.1991513,
                        "lng" : 55.2704439
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAl Mustaqbal St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD86\u003c/b\u003e",
                     "polyline" : {
                        "points" : "oixxCswipIw@i@y@a@[MSGu@Qi@KUKWMQMIEKKSUMQKQ"
                     },
                     "start_location" : {
                        "lat" : 25.1972047,
                        "lng" : 55.2692183
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 265
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 233
                     },
                     "end_location" : {
                        "lat" : 25.1983113,
                        "lng" : 55.2724376
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "uuxxCg_jpIMg@Mg@G]?AEc@Ag@?SDWFOHMFIZQbAc@ZQj@k@JK"
                     },
                     "start_location" : {
                        "lat" : 25.1991513,
                        "lng" : 55.2704439
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "_igfFqb`zFt~Fq{ItaR{pObvAa__@lgMy}EnvD_`DbcHolD`W_~EpVmdOdtOwnVjwHieBrsPi{I~lAqdJ_mAanGjNm|d@j}AqoUlzNu}_@|zAgyK~pRueQf`Bo|SnkIleEdwMri@jsGakOhxPytXfvCqcKfzSkoC|cHg_NluYmB~r^_iT`pOydP|nIcyLba\\_pZxxUsx\\thTanj@|cM_yOj}_@exNhy^}k\\hvImiA~tFyyIheGoaKdgDw`Al{E{tOdcXqfR`k`@}fUvxMmjK~pS{tHtzLw|MdeNisVzpH}rLzwV}|JphRedH|mFc}Od}CwbDrfCfa@|~Bge@fsDbiAbyFyoCx`GemFvvJmfHjxMaHbzGm{CpfCwwBz~LmHhaU__MnxCqbHhbGkoAznAswHb`Am{Bf{C}xGsf@wcEl`As|Ol`AouDzbHs~BlgIe{E|qGm}@|zI}_JlkRixMt}_@whKj`EfaE|~B}b@voAmkBvkKc|JjaPwmU_Smkc@flK{_a@`~OwbVtqKagYvhPyhQfhY}kj@nkMccT|nKksSpxSmoOzyVq`InnLgtJnxVa}VxbKo`LkcBy|Mv`JcvCpjAi_AiY_fDfqB{kFhlDygRxtIwqGb|I_sKzlJy|KjcHmfNjsCqmD_jBgtIbqLejThbPeyYtnM}jOdbDozHpfC{xNjpJ{nl@`n@cr_@zxEqnOttJkeObbMipOvsEonAfhDmiH|jBmiExyA{cEv|GwdJzeGe`IhaYmiTjvRobQrlMcqOxpJxvBxhZm{RrkIgnX|aHcuJhzOqp@|mZhLtnLsdEhwYykKtu\\yeRv|RobZlbXao`@hiFjMlfIchIftRikIf|ActQz`EulGnsO|s@fwFRnaIeyFpcQnNlmFeoEtDyyIoAebEzSetLddJclQdzJ}`HrvPabGxwKkvIvsRejCzcNyiOpuIuuAnhL}jDj~F{bEruN}lKl_Gc}@r}DytH`rF_}E~nV}ub@tq^k{_@nyPwaVz|GcyOp{EwlOxaDq{UzxOamSr|MqeYjwOsbMftHkqKzoTehb@hoQybn@bwGsw^ruHa{k@`dMmkYhsLikL~mAygOhqGcx]dvFe{]diDgjNjaAgyDh}N}kKhvLglMojAciDfqLytJdbEugHvQekO}|BymXwv@i|Df`aBase@z|~@{dSd_tA}eNrmB}c@g@q|@rRpCxiEbiCfzGpvEvsL|`JfdM`qJh{DjtEdaGrbEwr@~oFp]aNn\\}~GquHeqIwkH_|NicJwhCmwMqvJ"
         },
         "summary" : "Route 96",
         "warnings" : [
            "Walking directions are in beta. Use caution – This route may be missing sidewalks or pedestrian paths."
         ],
         "waypoint_order" : [ 0 ]
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
