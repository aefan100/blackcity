--// Obfuscated by jmes - discord.gg/STaq3UDbqQ

local t=string.byte;local r=string.char;local d=string.sub;local Q=table.concat;local i=math.ldexp;local O=getfenv or function()return _ENV end;local l=setmetatable;local K=select;local a=unpack;local L=tonumber;local function M(f)local o,e,c="","",{}local n=256;local a={}for l=0,n-1 do a[l]=r(l)end;local l=1;local function t()local o=L(d(f,l,l),36)l=l+1;local e=L(d(f,l,l+o-1),36)l=l+o;return e end;o=r(t())c[1]=o;while l<#f do local l=t()if a[l]then e=a[l]else e=o..d(o,1,1)end;a[n]=o..d(e,1,1)c[#c+1],o,n=e,e,n+1 end;return table.concat(c)end;local f=M('2151521527621M1X26125Y1D1X27621Q21L27A1R21L27621R1X1P2151R27D21521I1927H1927K21D2761R27X21521N21527V1R2762811X28427Q21R21523D27O28621E1P27H27N27R1H27H1H27W27V21G28021F1X24P2151W27Q21622P27H22P27621F21D28428021J21L23T27O27J21521A23527H23527621J29427O28021721D26H29K2761Y21T27H21T27621222H27H22H2761Q21527A2172862171127J21P1127621622927A21Q22927621A27925Y21727Q21721L2A829B29M29O21R2801Y24P27A21E28U21529W2AX29Z2151Q27G2AK2AQ2A72152A92AB2AD25Y2AF2AH21D2A329L2AO2BA2AQ29N2152AT29Q24H2AX24H29V29X25Y21E2B31Q27T2AK27V2152A62A82AA2C32BN2BP2151Y2552AX2552BU2B22A0112A32C62C42BA2C621N27Q1427Q2822762171Z28621X21Y22022522I22L22J21S21Z22621721928622622021W22421721A28622P22L22L22H23222422L21729127621T2DI22H22I1J161622J22022M1722621S22L21T22K22322K22I22422J22221Y21Z22L2242EE172EC21W1622922P22422H22L2221622Q22022N21Y1423G22O1422T21S2232DY22J2281621W2202D41622I21Y22K2EB2241721X22K2202171W28622Y22J2242202EF2F12232CU28622Z21X22022221U1922Y2E32282AL28623E2EG22L2D422421X21721B28622V22422M23H2202FU2D827622S2F921Z2FV2762GH22M2G82222GA2ED2G627622W22K22L21Y23322022J21W2FL2GG2GI22Z2H32H42GR2132862H22H41923J2242262DM2GL21X2DD2GN21523F21S22221T21721828622I22H2DZ2GR2122HI2H321Y1923I2FR2EA2DC2CX2GR1Y2I72HK22Z22021Z2IL2FK2FM2H12I82IA21Y21Y2252GF28622Q2862782AE2CR21L27N2B52772AJ21Q2CR2832151V28621K1X27J2AI21524P29B2152142762JJ21L26325Y21421L21724P21M2C021Q2C22CO27J1T27Q21M2CI25Y1R2C621Q28H2K628J27L29Z27P27621I22X27H22X28O29P2BO1X2CE2KF2BO29B27I2762822KK2852762982602K623T21424P21B192991V2C22182882151B27D2JJ2862JM2JI21L24P2L02L32L32L52492JB2L91X29O2LD2LI2LG2JN21L2212LL2212L321A2KA2K927621B1126X2151S2C62M725L27O2MC2CI2MF2M62AA2142K72761Z1921L2ML2C22122BR2K62BT2152131H192ML28N2B422127H2212761U24X27H24X2761I2N42K62N62MX192842C21Z1P2KE28J21B24H2N61R2MW21A2C01R2C21Y23T27H29921521B2BK2KT29C2KA1R2NO112KE2C621223L27H23L2M629J27Z2MJ2M12MM2MX27Q2KQ1Q24127H2412762JC27Y2861I2O72NO1P27J2O82AH26H27H29O2O2112KW2C61Y26927H2692M62O429B2M328I2MJ2OB29V2OE2K62OG2O22OI2802M72OL2C62HH2OW2A02OR2K62OT2JB2862KX2152OY2PK2O22P127O28J21A2P52K62P72M72PA29Q26X27H2M92O22PH2KU2JA28621521L22X25Z2JR2QU22E21L24125W2JR2R022E2CO2762CQ2922A52A427623A2322HA2762HM2HO22L2HQ2242142142D728622M2F92DN2I02762I321S22J22I2RN2762DA2DC2GS2152DL22L2G822J22N2HW2DD2IP21523I21Y22J21U2I22FZ2DD2PX2S32DM23122422I2222EG2252IL22L2RX2HT22V2DB2DD21128623H2DY21Z2SH2FP21Z2222282QR2TA2DE28623D2FY2282EA2RX2IH27622T21Y22222021X2TE2202TG22J2RE21522Y21T2H72FZ2EF2TT2JK22P22K2F821Z21Y21S22523F2IT22L23D2H72DN2IW2TV2332DY2S121628621Z2GI2TA27626124621524Z24W2UV2UV2681M21721M28623J2RV22L2FJ21X22O21Z22H2H32GP2IM2HO2TT2T02762G821Z22522Q22422823022N2G92172LH2152302RY2152RI22I21U2UP2QS2KK2UP25L1M2TA2SB2J025Y132J928428F2BH2K628021N2PS2QP2KW28628228D2Q521E2A22AK2WL21D2A82WG2CP27Q2RS2C32HT2S02DD2CV2762S42S62S82SQ2S223F22K21Z2X62S92TU2EN2UE2232FQ2DN2DF27622Y2ED2UN2GX2VS2151A2IZ2AJ2JE2QP2WC27621E2WE2OJ2812WI2812152WK2QP2WN2WL2152NR28F28L2K62N22WH2952762JE2P22LE2JK2LH2JJ2PO2142OG2JV2KI2BE2W22822CE2OV21521K2CE2152182CE2JJ2MU2142BT2JV23D2AE28D21521Q29E25Y21D29G21521E2NE1R2NG2WH2P228021M2ZB2K62ZD21Q29S2K629U2ZK2ZM2ZO2WT2KM2W82KQ2822XY2ZK2Y12WG2Y42KV28E2Y8310E2Y52KE2YA2ME2WO2BD1R2AG2Y32ZQ2KU2WW29V2A52X02SY2S22X52EA2X72DD2XL28C2TF2TH2172TJ2152TL2TN2TP31142TT2SB2TW2TY2GX2EA2172SK2332D4225311L2RW22L2TW21S21X2252H02152U32U52U7311U2RA2152RC2TU2RG2HP2232HR311V2E922L2272272FY2D621I2DG2U42IL311Z2UD2DY21X2HR21X23F22421W21Y2VP22V21Y23D21T22822I2HW2RX2WY2H621X2E921713312H311Y2U8312L2TO312O312Q312S312U312W312Y313022222I312V23E21S21W22K2FY2EF1R31162FN2TX2D522423E2RI2EF2W01F2W22DG2XU2J12KU2J32B429B2W82J82XX2Q32YJ1X2A42LA2JU27J2JQ2JM2JU2JW2AE2JZ2JF2152K22772K52OM2K92Q82KD27O27Q2KH2KJ2KL2Y227L2KP28A2KS29B310D2Q521L2552L01R2552LN2L62LQ27621824P1821528T2L321L2292LL229315K2LP2L8315N21T26G315R21T315T2LZ2JR2M124P2PJ2BE2O92M92MB2MJ310K2MG2612MI2P82JL2OM2MO2MQ2NW29V2MU2NS2762MY2N01R2N21Q31012N72N92K62NB2Q631702NH2NJ2MN2NM2QB2M62NQ27O2NT2NV2NX2NZ2L12PG2P22PI2OZ2PL316K2OD2OF2OH2YI2P82PV316U2OO27Q2OQ2OS2OU2Q42OX317N2Q92P22QC2QE1R2QG2P9316K2PC2PE317K29A2AH31842M72PM2B02PO1R2PQ21B2Y42PU2ML2PW31822PZ3180314G310G2Q72KB2M62QA2P329C3188318A2QI2CA2QK2K62QM2O3317L314F2QR21L23D2QV214319H2QY26X2R1214319M2R4310S21521F2R928631232X32SC2IC2H82GC2ED2RL2VV2RP2E32HZ2862RU2RW2VV2X1310X2DM2XD2X82SB2SD2SF2SH2X82SK2S42SN2SP2SR2ST2SV2GG310W2VG2152T22IL2T52EG2T82W02CT31122TQ2TS2TI28631192TO31B5311I311E2TX2DY311H2U13139312J2U82UA21Y2UC2UE2GE2FN2UI310W2UL2762UN22M2W02UR2UT2UW2UX2UZ2V12RF2V42V62V82VA22L2VC2202VE21731AV2VI2VK2VM2VO2VQ2VS2VU2HT2VX2VZ2UP2QT2W02W42W631472W92WB310G2Y027H310B317T315D2YA2Y92XZ2WQ31212ZP2BA2WV2R62WX310U2D9310W319X310Y2S72XE319X2XA2XC310Z2XE2SB2XG22J22L2XI2FR2TC2XM2XO2242XQ2QR2XT2J627A2XW2Y5310831CY2WF2KU310C2Y6310G2WM31EC2YB31CX2YE316X31E9317T2YK31522LV2762YO21L2YQ2YS21M2YU21Q2YW2152YY2JD2Z22Z42LI2Z72Z92ZS2ZC27E2ZG2ZI2XZ317631D82Y231F52ZU27E2ZX1R2ZZ2ZL2N531E9310Q215310531CW2WO310A31EJ2KM31D2310F2Q5282310I2QP310K28F310M310O31FC31DA2152R72B031DD2RZ31DF28631DH311031DV31132TR3115311731B9311B31GI311D313W311G2U0311J286311L2VJ311O2D1311R311T311V311X31BJ3120319V2RD319X2IB2U02IE2GZ27Q215312A312C312E217312G27631H12U6313B2TY312N2GC313F312T224312V312X312Z313131A727631343136313831HI312I31HK225313C31HN312P312R31HQ31HS313J3131313N313P313R2IC313U3117311F313Y31402IC3143314527622R31CU314E281314A2J531FO2J731CW2YZ21K21D314J31J12JO314N2JT2JV2JX314S2K12K3314X2K8318431512KQ31542K62W22AT317T315831EM2KR27Y315C31EB315E23T315H2L22L4315L31602Z31X2LP2LU2LF31EO2LX2LK2JR24P315K29O31JY2LA2M931K22YN2LX31672143169316B2M52P82ME316F2P8316J2OM2M7316M2MG316P2C62MO316W2MS2CC2K62Z22MY1P2N12A031FH2ZZ1U317I1R2O11I31L7316U2NI27O2NK317A319321B2552NR2Z22NU27U29Q318M318O2QO2O62Q8318J317P24927H2LP2PR317T318J318S317W27Y317Y319531812PY2Q6318I31922QC2PD2K62PF2P831971Y31991R319B31LU316B31LK2OA31LY31M0317S2KM31M42OM2SK2Q51Q31M9318X2Q5318Z31LK31ME2AH31MG1R31MI2QH318C26P27H26P318F2O531072TA2QT319I2QX21L26H319N31NP319Q31DB31D52CT312131232UG2IK2IM2IM31A32HT31A52RR31A82F931AA310V2S131DG31AE31DN31AG28631AI2SG2I331AL31GD2SM2SO2SQ2VJ31AR2VV2SX2S12SK22U2G12E31E22I192232281923723423531CD2T12T331AZ2T72T931B231GG31BB31AA31GK2TM31BA311C2TU311F31BF31GR2U231I2311Z31BL31BN31DR31BP2XM31BR2UK2UM2UO2UP31BY2UU31C02UY2V02V231C52TO31C72VB2IN31CC31CE2SR2VL2VN2VP2EE2VR28631CL28631CN2W031CQ2W32W52QR31IQ31E22BE2J22J4314C31IX314F31IZ314T2JH31K32JL2LX1X314N314I31J7314R310R31JA314W27H31JD31501X2KE31532YU1R31JJ2Y431JM2KQ21R315B2WJ310G21L24X315H24X315K2L72LR31K12YM2LW2LI315V2JR315X31JW31KA2L921T26W316431662M02M22M42O931KN316I316K31KS31M52P831KV2MN2NI2MR29V31L0315I316U1H31L431EI2B431LE21531L92O02NC31T221331LG316Q2152NL2NN2M631LM27O31LO317G31LR317R2QN319D31LV31902P8318K21231LZ2K631M1318P31M32OA31SO213317X2A031N22YZ31N431MD318631N8318E31MJ318C31MM31MO31TM31MQ2O931TQ31TS1R31TU318Q31TX31MY318U2B431U231UN31N52P031U629C31N931NB318B2OM1Y31NE2K631NG31TL318G31E531NK22P319I31V72QY31NP2JR31NR2R531G727Q2WP31NV31H42VV2SD2IU31O22RO2RQ31HW21531A931AS31GB31OA31OK2S531OD2SA31OF2SE31OH2SI31GS2X431OL31AP31OO2EE31VT21531OR2DD319T2GO2SO21T2SO162TL22M1423D21Y21X31P12T22242241931402U422H31P627631AX2T42I32T631B131PC31B4311C31B72TK31PH31GM2TS31PK31BE2TZ311I31PO313A2U92UB312L2UF31BQ2UJ2DD31BT21531BV31BX2US31Q22UW31Q431C32152V331DR31C62V931QA2VD311I31QD2VJ31QF31CI31QI31CK2VV31QN31CP31IO28631CS286');local n=bit and bit.bxor or function(l,e)local o,n=1,0 while l>0 and e>0 do local d,c=l%2,e%2 if d~=c then n=n+o end l,e,o=(l-d)/2,(e-c)/2,o*2 end if l<e then l=e end while l>0 do local e=l%2 if e>0 then n=n+o end l,o=(l-e)/2,o*2 end return n end local function l(e,l,o)if o then local l=(e/2^(l-1))%2^((o-1)-(l-1)+1);return l-l%1;else local l=2^(l-1);return(e%(l+l)>=l)and 1 or 0;end;end;local o=1;local function e()local d,c,e,l=t(f,o,o+3);d=n(d,41)c=n(c,41)e=n(e,41)l=n(l,41)o=o+4;return(l*16777216)+(e*65536)+(c*256)+d;end;local function c()local l=n(t(f,o,o),41);o=o+1;return l;end;local function L()local o=e();local e=e();local d=1;local n=(l(e,1,20)*(2^32))+o;local o=l(e,21,31);local l=((-1)^l(e,32));if(o==0)then if(n==0)then return l*0;else o=1;d=0;end;elseif(o==2047)then return(n==0)and(l*(1/0))or(l*(0/0));end;return i(l,o-1023)*(d+(n/(2^52)));end;local M=e;local function i(l)local e;if(not l)then l=M();if(l==0)then return'';end;end;e=d(f,o,o+l-1);o=o+l;local o={}for l=1,#e do o[l]=r(n(t(d(e,l,l)),41))end return Q(o);end;local o=e;local function M(...)return{...},K('#',...)end local function T()local f={0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0};local r={0,0,0,0,0,0};local o={};local a={f,nil,r,nil,o};a[4]=c();for c=1,e()do local d=n(e(),18);local e=n(e(),50);local n=l(d,1,2);local o=l(e,1,11);local o={o,l(d,3,11),nil,nil,e};if(n==0)then o[3]=l(d,12,20);o[5]=l(d,21,29);elseif(n==1)then o[3]=l(e,12,33);elseif(n==2)then o[3]=l(e,12,32)-1048575;elseif(n==3)then o[3]=l(e,12,32)-1048575;o[5]=l(d,21,29);end;f[c]=o;end;local l=e()local n={0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0};for e=1,l do local o=c();local l;if(o==1)then l=(c()~=0);elseif(o==0)then l=L();elseif(o==2)then l=i();end;n[e]=l;end;a[2]=n for l=1,e()do r[l-1]=T();end;return a;end;local function Q(l,o,t)local n=l[1];local e=l[2];local o=l[3];local l=l[4];return function(...)local n=n;local d=e;local J=o;local f=l;local M=M local o=1;local c=-1;local i={};local r={...};local L=K('#',...)-1;local l={};local e={};for l=0,L do if(l>=f)then i[l-f]=r[l+1];else e[l]=r[l+1];end;end;local l=L-f+1 local l;local r;while true do l=n[o];r=l[1];if r<=29 then if r<=14 then if r<=6 then if r<=2 then if r<=0 then local n=l[2];local d={};local o=0;local l=n+l[3]-1;for l=n+1,l do o=o+1;d[o]=e[l];end;local d,l=M(e[n](a(d,1,l-n)));l=l+n-1;o=0;for l=n,l do o=o+1;e[l]=d[o];end;c=l;elseif r==1 then e[l[2]][d[l[3]]]=d[l[5]];else e[l[2]][d[l[3]]]=e[l[5]];end;elseif r<=4 then if r==3 then if not e[l[2]]then o=o+1;else o=o+l[3];end;else e[l[2]]=e[l[3]][d[l[5]]];end;elseif r>5 then local f,f;local K;local L;local r;local A;local i;local f;e[l[2]]();c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];i=e[l[3]];e[f+1]=i;e[f]=i[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];f=l[2];i=e[l[3]];e[f+1]=i;e[f]=i[d[l[5]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;K,L=M(e[f](a(A,1,L-f)));L=L+f-1;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];f=l[2];A={};r=0;L=c;for l=f+1,L do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];o=o+l[3];else local o=l[2];local d,n={e[o]()};local n=o+l[5]-2;local l=0;for o=o,n do l=l+1;e[o]=d[l];end;c=n;end;elseif r<=10 then if r<=8 then if r==7 then local K;local M;local L;local r;local A;local f;e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]]*e[l[5]];o=o+1;l=n[o];e[l[2]][d[l[3]]]=e[l[5]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;else e[l[2]]=t[d[l[3]]];end;elseif r==9 then e[l[2]][d[l[3]]]=d[l[5]];else if(e[l[2]]==d[l[5]])then o=o+1;else o=o+l[3];end;end;elseif r<=12 then if r==11 then local n=l[2];local c=l[5];local l=n+2;local d={e[n](e[n+1],e[l])};for o=1,c do e[l+o]=d[o];end;local n=e[n+3];if n then e[l]=n else o=o+1;end;else local K;local M;local L;local r;local A;local f;e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]]*e[l[5]];o=o+1;l=n[o];e[l[2]][d[l[3]]]=e[l[5]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;end;elseif r>13 then local f,f;local i;local L;local r;local A;local K;local f;e[l[2]]();c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;i={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=i[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;i,L=M(e[f](a(A,1,L-f)));L=L+f-1;r=0;for l=f,L do r=r+1;e[l]=i[r];end;c=L;o=o+1;l=n[o];f=l[2];A={};r=0;L=c;for l=f+1,L do r=r+1;A[r]=e[l];end;i={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=i[r];end;c=L;o=o+1;l=n[o];o=o+l[3];else e[l[2]]=Q(J[l[3]],nil,t);end;elseif r<=21 then if r<=17 then if r<=15 then local o=l[2];local d={};local n=0;local l=o+l[3]-1;for l=o+1,l do n=n+1;d[n]=e[l];end;e[o](a(d,1,l-o));c=o;elseif r==16 then if(e[l[2]]~=d[l[5]])then o=o+1;else o=o+l[3];end;else local M;local L;local r;local K;local A;local f;e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A=e[l[3]];e[f+1]=A;e[f]=A[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];K={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;K[r]=e[l];end;M={e[f](a(K,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];f=l[2];A=e[l[3]];e[f+1]=A;e[f]=A[d[l[5]]];end;elseif r<=19 then if r==18 then if e[l[2]]then o=o+1;else o=o+l[3];end;else e[l[2]]();c=A;end;elseif r>20 then e[l[2]][d[l[3]]]=e[l[5]];else e[l[2]]=d[l[3]];end;elseif r<=25 then if r<=23 then if r>22 then o=o+l[3];else local f;local A,f;local L;local f;local K;local i;local r;e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];r=l[2];i=e[l[3]];e[r+1]=i;e[r]=i[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];r=l[2];K={};f=0;L=r+l[3]-1;for l=r+1,L do f=f+1;K[f]=e[l];end;A,L=M(e[r](a(K,1,L-r)));L=L+r-1;f=0;for l=r,L do f=f+1;e[l]=A[f];end;c=L;o=o+1;l=n[o];r=l[2];K={};f=0;L=c;for l=r+1,L do f=f+1;K[f]=e[l];end;A={e[r](a(K,1,L-r))};L=r+l[5]-2;f=0;for l=r,L do f=f+1;e[l]=A[f];end;c=L;o=o+1;l=n[o];r=l[2];A,L={e[r]()};L=r+l[5]-2;f=0;for l=r,L do f=f+1;e[l]=A[f];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];end;elseif r==24 then local M;local A;local r;local K;local L;local f;e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];L=e[l[3]];e[f+1]=L;e[f]=L[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];K={};r=0;A=f+l[3]-1;for l=f+1,A do r=r+1;K[r]=e[l];end;M={e[f](a(K,1,A-f))};A=f+l[5]-2;r=0;for l=f,A do r=r+1;e[l]=M[r];end;c=A;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];f=l[2];L=e[l[3]];e[f+1]=L;e[f]=L[d[l[5]]];else local n=l[2];local d={};local o=0;local l=n+l[3]-1;for l=n+1,l do o=o+1;d[o]=e[l];end;local d,l=M(e[n](a(d,1,l-n)));l=l+n-1;o=0;for l=n,l do o=o+1;e[l]=d[o];end;c=l;end;elseif r<=27 then if r>26 then local n=l[2];local f={};local o=0;local d=n+l[3]-1;for l=n+1,d do o=o+1;f[o]=e[l];end;local d={e[n](a(f,1,d-n))};local l=n+l[5]-2;o=0;for l=n,l do o=o+1;e[l]=d[o];end;c=l;else local M;local K;local L;local r;local A;local f;e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;end;elseif r==28 then e[l[2]]=e[l[3]][d[l[5]]];else e[l[2]]();c=A;end;elseif r<=44 then if r<=36 then if r<=32 then if r<=30 then local M;local L;local r;local K;local A;local f;e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A=e[l[3]];e[f+1]=A;e[f]=A[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];K={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;K[r]=e[l];end;M={e[f](a(K,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];f=l[2];A=e[l[3]];e[f+1]=A;e[f]=A[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];K={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;K[r]=e[l];end;M={e[f](a(K,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];if not e[l[2]]then o=o+1;else o=o+l[3];end;elseif r>31 then local o=l[2];local n=e[l[3]];e[o+1]=n;e[o]=n[d[l[5]]];else do return end;end;elseif r<=34 then if r==33 then local f,f;local K;local L;local r;local A;local i;local f;e[l[2]]();c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];i=e[l[3]];e[f+1]=i;e[f]=i[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];f=l[2];i=e[l[3]];e[f+1]=i;e[f]=i[d[l[5]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;K,L=M(e[f](a(A,1,L-f)));L=L+f-1;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];f=l[2];A={};r=0;L=c;for l=f+1,L do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];o=o+l[3];else local f,f;local K;local L;local r;local A;local i;local f;e[l[2]]();c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];i=e[l[3]];e[f+1]=i;e[f]=i[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];f=l[2];i=e[l[3]];e[f+1]=i;e[f]=i[d[l[5]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;K,L=M(e[f](a(A,1,L-f)));L=L+f-1;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];f=l[2];A={};r=0;L=c;for l=f+1,L do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=K[r];end;c=L;o=o+1;l=n[o];o=o+l[3];end;elseif r==35 then local M;local L;local r;local A;local K;local f;e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];if not e[l[2]]then o=o+1;else o=o+l[3];end;else local n=l[2];local o=e[l[3]];e[n+1]=o;e[n]=o[d[l[5]]];end;elseif r<=40 then if r<=38 then if r>37 then local o=l[2];local d={};local n=0;local l=o+l[3]-1;for l=o+1,l do n=n+1;d[n]=e[l];end;e[o](a(d,1,l-o));c=o;else e[l[2]]=t[d[l[3]]];end;elseif r==39 then local n=l[2];local f={};local o=0;local d=c;for l=n+1,d do o=o+1;f[o]=e[l];end;local d={e[n](a(f,1,d-n))};local l=n+l[5]-2;o=0;for l=n,l do o=o+1;e[l]=d[o];end;c=l;else local o=l[2];local d,n={e[o]()};local n=o+l[5]-2;local l=0;for o=o,n do l=l+1;e[o]=d[l];end;c=n;end;elseif r<=42 then if r>41 then local M;local K;local L;local r;local A;local f;e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;else e[l[2]]=d[l[3]];end;elseif r==43 then if(e[l[2]]~=d[l[5]])then o=o+1;else o=o+l[3];end;else do return end;end;elseif r<=51 then if r<=47 then if r<=45 then e[l[2]]=e[l[3]]*e[l[5]];elseif r>46 then local n=l[2];local d={};local o=0;local f=n+l[3]-1;for l=n+1,f do o=o+1;d[o]=e[l];end;local d={e[n](a(d,1,f-n))};local l=n+l[5]-2;o=0;for l=n,l do o=o+1;e[l]=d[o];end;c=l;else local K;local M;local L;local r;local A;local f;e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]]*e[l[5]];o=o+1;l=n[o];e[l[2]][d[l[3]]]=e[l[5]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;end;elseif r<=49 then if r>48 then e[l[2]]=(l[3]~=0);else e[l[2]]=Q(J[l[3]],nil,t);end;elseif r>50 then o=o+l[3];else local n=l[2];local c=l[5];local l=n+2;local d={e[n](e[n+1],e[l])};for o=1,c do e[l+o]=d[o];end;local n=e[n+3];if n then e[l]=n else o=o+1;end;end;elseif r<=55 then if r<=53 then if r>52 then if not e[l[2]]then o=o+1;else o=o+l[3];end;else local n=l[2];local d={};local o=0;local f=c;for l=n+1,f do o=o+1;d[o]=e[l];end;local d={e[n](a(d,1,f-n))};local l=n+l[5]-2;o=0;for l=n,l do o=o+1;e[l]=d[o];end;c=l;end;elseif r==54 then local K;local M;local L;local r;local A;local f;e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];e[l[2]]=e[l[3]]*e[l[5]];o=o+1;l=n[o];e[l[2]][d[l[3]]]=e[l[5]];o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;M={e[f](a(A,1,L-f))};L=f+l[5]-2;r=0;for l=f,L do r=r+1;e[l]=M[r];end;c=L;o=o+1;l=n[o];f=l[2];K=e[l[3]];e[f+1]=K;e[f]=K[d[l[5]]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=(l[3]~=0);o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;o=o+1;l=n[o];e[l[2]]=t[d[l[3]]];o=o+1;l=n[o];e[l[2]]=e[l[3]][d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;L=f+l[3]-1;for l=f+1,L do r=r+1;A[r]=e[l];end;e[f](a(A,1,L-f));c=f;else if e[l[2]]then o=o+1;else o=o+l[3];end;end;elseif r<=57 then if r==56 then e[l[2]]=(l[3]~=0);else e[l[2]]=e[l[3]]*e[l[5]];end;elseif r==58 then if(e[l[2]]==d[l[5]])then o=o+1;else o=o+l[3];end;else local K;local t;local r;local A;local L;local f;f=l[2];L=e[l[3]];e[f+1]=L;e[f]=L[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;t=f+l[3]-1;for l=f+1,t do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,t-f))};t=f+l[5]-2;r=0;for l=f,t do r=r+1;e[l]=K[r];end;c=t;o=o+1;l=n[o];f=l[2];L=e[l[3]];e[f+1]=L;e[f]=L[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];f=l[2];A={};r=0;t=f+l[3]-1;for l=f+1,t do r=r+1;A[r]=e[l];end;K={e[f](a(A,1,t-f))};t=f+l[5]-2;r=0;for l=f,t do r=r+1;e[l]=K[r];end;c=t;o=o+1;l=n[o];f=l[2];L=e[l[3]];e[f+1]=L;e[f]=L[d[l[5]]];o=o+1;l=n[o];e[l[2]]=d[l[3]];o=o+1;l=n[o];e[l[2]]=d[l[3]];end;o=o+1;end;end;end;return Q(T(),{},O())();
