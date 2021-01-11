Microsoft's Catapult v2 (Pikes Peak) DDR3L SDRAM pinout
```
# -----------ddr3-----------   
# U46,48,50,52,54,56,58,60,62 - H5TC4G83BFR-PBA SK hynix 4Gb 1.35V DDR3L SDRAM
#
#
# ddr3_a      : out   std_logic_vector(13 downto 0);  --//SSTL15 //Address
# ddr3_ba     : out   std_logic_vector(2 downto 0);   --//SSTL15 //Bank Address
# ddr3_clk_n  : out   std_logic;                      --//SSTL15 //Diff Clock - Neg
# ddr3_clk_p  : out   std_logic;                      --//SSTL15 //Diff Clock - Pos

# ddr3_cke    : out   std_logic;                      --//SSTL15 //Clock Enable
# ddr3_cke1   : out   std_logic;                      --//SSTL15 //Clock1 Enable
# ddr3_csn    : out   std_logic;                      --//SSTL15 //Chip Select
# ddr3_csn1   : out   std_logic;                      --//SSTL15 //Chip1 Select
# ddr3_odt    : out   std_logic;                      --//SSTL15 //On-Die Termination Enable
# ddr3_odt1   : out   std_logic;                      --//SSTL15 //On-Die1 Termination Enable

# ddr3_dm     : out   std_logic_vector(8 downto 0);   --//SSTL15 //Data Write Mask
# ddr3_dq     : inout std_logic_vector(71 downto 0);  --//SSTL15 //Data Bus
# ddr3_dqs_n  : inout std_logic_vector(8 downto 0);   --//SSTL15 //Diff Data Strobe - Neg
# ddr3_dqs_p  : inout std_logic_vector(8 downto 0);   --//SSTL15 //Diff Data Strobe - Pos

# ddr3_rasn   : out   std_logic;                      --//SSTL15 //Row Address Strobe
# ddr3_casn   : out   std_logic;                      --//SSTL15 //Column Address Strobe
# ddr3_wen    : out   std_logic;                      --//SSTL15 //Write Enable
# ddr3_resetn : out   std_logic;                      --//SSTL15 //Reset

set_location_assignment PIN_J27 -to ddr3_a[0]
set_location_assignment PIN_J21 -to ddr3_a[1]
set_location_assignment PIN_J29 -to ddr3_a[2]
set_location_assignment PIN_L28 -to ddr3_a[3]
set_location_assignment PIN_P26 -to ddr3_a[4]
set_location_assignment PIN_M26 -to ddr3_a[5]
# set_location_assignment PIN_ -to ddr3_a[6]
set_location_assignment PIN_P25 -to ddr3_a[7]
set_location_assignment PIN_N22 -to ddr3_a[8]
set_location_assignment PIN_N26 -to ddr3_a[9]
set_location_assignment PIN_K27 -to ddr3_a[10]
set_location_assignment PIN_L27 -to ddr3_a[11]
set_location_assignment PIN_N27 -to ddr3_a[12]
set_location_assignment PIN_M27 -to ddr3_a[13]
set_location_assignment PIN_N21 -to ddr3_a[14]
set_location_assignment PIN_K28 -to ddr3_a[15]

set_location_assignment PIN_J28 -to ddr3_ba[0]
set_location_assignment PIN_K21 -to ddr3_ba[1]
set_location_assignment PIN_L26 -to ddr3_ba[2]

set_location_assignment PIN_J24 -to ddr3_clk_n
set_location_assignment PIN_J23 -to ddr3_clk_p

set_location_assignment PIN_K24 -to ddr3_cke
set_location_assignment PIN_J22 -to ddr3_cke1
set_location_assignment PIN_N23 -to ddr3_csn
set_location_assignment PIN_N20 -to ddr3_csn1
set_location_assignment PIN_M21 -to ddr3_odt
set_location_assignment PIN_K22 -to ddr3_odt1

set_location_assignment PIN_L21 -to ddr3_rasn
set_location_assignment PIN_L24 -to ddr3_casn
set_location_assignment PIN_P23 -to ddr3_wen
set_location_assignment PIN_L20 -to ddr3_resetn

## U46 #0 DQ[7:0]
set_location_assignment PIN_N33 -to ddr3_dm[0]
set_location_assignment PIN_T31 -to ddr3_dq[0]
set_location_assignment PIN_R32 -to ddr3_dq[1]
set_location_assignment PIN_P32 -to ddr3_dq[2]
set_location_assignment PIN_P34 -to ddr3_dq[3]
set_location_assignment PIN_N34 -to ddr3_dq[4]
set_location_assignment PIN_M33 -to ddr3_dq[5]
set_location_assignment PIN_L33 -to ddr3_dq[6]
set_location_assignment PIN_L34 -to ddr3_dq[7]
set_location_assignment PIN_M32 -to ddr3_dqs_n[0]
set_location_assignment PIN_N32 -to ddr3_dqs_p[0]

## U48 #1 DQ[15:8]
set_location_assignment PIN_H34 -to ddr3_dm[1]
set_location_assignment PIN_K34 -to ddr3_dq[8]
set_location_assignment PIN_K33 -to ddr3_dq[9]
set_location_assignment PIN_J33 -to ddr3_dq[10]
set_location_assignment PIN_J34 -to ddr3_dq[11]
set_location_assignment PIN_G34 -to ddr3_dq[12]
set_location_assignment PIN_G33 -to ddr3_dq[13]
set_location_assignment PIN_G32 -to ddr3_dq[14]
set_location_assignment PIN_F32 -to ddr3_dq[15]
set_location_assignment PIN_E33 -to ddr3_dqs_n[1]
set_location_assignment PIN_F33 -to ddr3_dqs_p[1]

## U50 #2 DQ[23:16]
set_location_assignment PIN_C34 -to ddr3_dm[2]
set_location_assignment PIN_D33 -to ddr3_dq[16]
set_location_assignment PIN_C33 -to ddr3_dq[17]
set_location_assignment PIN_A37 -to ddr3_dq[18]
set_location_assignment PIN_A36 -to ddr3_dq[19]
set_location_assignment PIN_A35 -to ddr3_dq[20]
set_location_assignment PIN_B29 -to ddr3_dq[21]
set_location_assignment PIN_B32 -to ddr3_dq[22]
set_location_assignment PIN_A28 -to ddr3_dq[23]
set_location_assignment PIN_D34 -to ddr3_dqs_n[2]
set_location_assignment PIN_E34 -to ddr3_dqs_p[2]

## U52 #3 DQ[31:24]
set_location_assignment PIN_E30 -to ddr3_dm[3]
set_location_assignment PIN_A31 -to ddr3_dq[24]
set_location_assignment PIN_B31 -to ddr3_dq[25]
set_location_assignment PIN_C30 -to ddr3_dq[26]
set_location_assignment PIN_D30 -to ddr3_dq[27]
set_location_assignment PIN_E31 -to ddr3_dq[28]
set_location_assignment PIN_F30 -to ddr3_dq[29]
set_location_assignment PIN_G31 -to ddr3_dq[30]
set_location_assignment PIN_H31 -to ddr3_dq[31]
set_location_assignment PIN_C31 -to ddr3_dqs_n[3]
set_location_assignment PIN_D31 -to ddr3_dqs_p[3]

## U54 #4 DQ[39:32]
set_location_assignment PIN_E27 -to ddr3_dm[4]
set_location_assignment PIN_A26 -to ddr3_dq[32]
set_location_assignment PIN_B26 -to ddr3_dq[33]
set_location_assignment PIN_C26 -to ddr3_dq[34]
set_location_assignment PIN_C27 -to ddr3_dq[35]
set_location_assignment PIN_D27 -to ddr3_dq[36]
set_location_assignment PIN_F26 -to ddr3_dq[37]
set_location_assignment PIN_G26 -to ddr3_dq[38]
set_location_assignment PIN_H26 -to ddr3_dq[39]
set_location_assignment PIN_F27 -to ddr3_dqs_n[4]
set_location_assignment PIN_G27 -to ddr3_dqs_p[4]

## U56 #5 DQ[47:40]
set_location_assignment PIN_D25 -to ddr3_dm[5]
set_location_assignment PIN_G25 -to ddr3_dq[40]
set_location_assignment PIN_G24 -to ddr3_dq[41]
set_location_assignment PIN_F24 -to ddr3_dq[42]
set_location_assignment PIN_D24 -to ddr3_dq[43]
set_location_assignment PIN_C24 -to ddr3_dq[44]
set_location_assignment PIN_C25 -to ddr3_dq[45]
set_location_assignment PIN_B25 -to ddr3_dq[46]
set_location_assignment PIN_A25 -to ddr3_dq[47]
set_location_assignment PIN_E25 -to ddr3_dqs_n[5]
set_location_assignment PIN_E24 -to ddr3_dqs_p[5]

## U58 #6 DQ[55:48]
set_location_assignment PIN_D22 -to ddr3_dm[6]
set_location_assignment PIN_A23 -to ddr3_dq[48]
set_location_assignment PIN_A22 -to ddr3_dq[49]
set_location_assignment PIN_B22 -to ddr3_dq[50]
set_location_assignment PIN_B23 -to ddr3_dq[51]
set_location_assignment PIN_C22 -to ddr3_dq[52]
set_location_assignment PIN_G23 -to ddr3_dq[53]
set_location_assignment PIN_H23 -to ddr3_dq[54]
set_location_assignment PIN_H22 -to ddr3_dq[55]
set_location_assignment PIN_E23 -to ddr3_dqs_n[6]
set_location_assignment PIN_F23 -to ddr3_dqs_p[6]

## U60 #7 DQ[63:56]
set_location_assignment PIN_D21 -to ddr3_dm[7]
set_location_assignment PIN_G20 -to ddr3_dq[56]
set_location_assignment PIN_F20 -to ddr3_dq[57]
set_location_assignment PIN_E20 -to ddr3_dq[58]
set_location_assignment PIN_E21 -to ddr3_dq[59]
set_location_assignment PIN_C21 -to ddr3_dq[60]
set_location_assignment PIN_C20 -to ddr3_dq[61]
set_location_assignment PIN_B20 -to ddr3_dq[62]
set_location_assignment PIN_A20 -to ddr3_dq[63]
set_location_assignment PIN_F21 -to ddr3_dqs_n[7]
set_location_assignment PIN_G21 -to ddr3_dqs_p[7]

## U62 #8 DQ[71:64]
set_location_assignment PIN_D28 -to ddr3_dm[8]
set_location_assignment PIN_H28 -to ddr3_dq[64]
set_location_assignment PIN_G28 -to ddr3_dq[65]
set_location_assignment PIN_E28 -to ddr3_dq[66]
set_location_assignment PIN_C28 -to ddr3_dq[67]
set_location_assignment PIN_B28 -to ddr3_dq[68]
set_location_assignment PIN_B29 -to ddr3_dq[69]
set_location_assignment PIN_A29 -to ddr3_dq[70]
set_location_assignment PIN_A28 -to ddr3_dq[71]
set_location_assignment PIN_G29 -to ddr3_dqs_n[8]
set_location_assignment PIN_H29 -to ddr3_dqs_p[8]
```
