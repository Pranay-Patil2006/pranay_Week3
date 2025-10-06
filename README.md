# pranay_Week3
SoC workshop week 3 deliverables.
<details>
  <summary>Part 1</summary>
  <img width="1282" height="528" alt="image" src="https://github.com/user-attachments/assets/a2c77826-a314-429e-85db-d481d0db1127" />

<img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/1c4e5b8e-a675-44a0-86e3-4be77fa9b2bb" />

<img width="1919" height="274" alt="image" src="https://github.com/user-attachments/assets/723ad448-9fa1-46ca-83b7-ebd3702d2dbd" />

<img width="1919" height="489" alt="image" src="https://github.com/user-attachments/assets/784ffd6c-358d-4e32-91da-42ab6f852296" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/05bd03e1-4750-4f61-a499-eb6b01850315" />

<img width="1916" height="1010" alt="image" src="https://github.com/user-attachments/assets/0168f249-5e78-4391-863c-676cabb31631" />

<img width="1919" height="294" alt="image" src="https://github.com/user-attachments/assets/96b81ed5-8fd7-4cb1-8b25-f291476b24c2" />

<img width="1919" height="631" alt="image" src="https://github.com/user-attachments/assets/7c84d925-ec98-4da7-b377-f57f86ec2fcb" />

<img width="1919" height="546" alt="image" src="https://github.com/user-attachments/assets/ab638b45-3d09-4499-bb50-08e25fe60471" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/ce11fa28-a5a4-4c90-94e3-7905ede2e301" />

<img width="1917" height="551" alt="image" src="https://github.com/user-attachments/assets/8932e365-bfbf-4f7c-ab89-ece887f7a9de" />

<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/98ddb97d-ac3e-4949-807a-d7e99e3eb8df" />

```7.25. Printing statistics.

=== clk_gate ===

   Number of wires:                  5
   Number of wire bits:              5
   Number of public wires:           5
   Number of public wire bits:       5
   Number of ports:                  5
   Number of port bits:              5
   Number of memories:               0
   Number of memory bits:            0
   Number of processes:              0
   Number of cells:                  0

=== rvmyth ===

   Number of wires:               3948
   Number of wire bits:           6635
   Number of public wires:         269
   Number of public wire bits:    2941
   Number of ports:                  3
   Number of port bits:             12
   Number of memories:               0
   Number of memory bits:            0
   Number of processes:              0
   Number of cells:               5165
     $_ANDNOT_                    1412
     $_AND_                        174
     $_DFF_P_                      239
     $_MUX_                        513
     $_NAND_                        42
     $_NOR_                         99
     $_NOT_                         49
     $_ORNOT_                       74
     $_OR_                        1322
     $_SDFFE_PP0P_                 962
     $_SDFFE_PP1P_                  64
     $_SDFF_PP0_                     8
     $_XNOR_                        71
     $_XOR_                        129
     clk_gate                        7

=== vsdbabysoc ===

   Number of wires:                  9
   Number of wire bits:             18
   Number of public wires:           9
   Number of public wire bits:      18
   Number of ports:                  7
   Number of port bits:              7
   Number of memories:               0
   Number of memory bits:            0
   Number of processes:              0
   Number of cells:                  3
     avsddac                         1
     avsdpll                         1
     rvmyth                          1

=== design hierarchy ===

   vsdbabysoc                        1
     rvmyth                          1
       clk_gate                      7

   Number of wires:               3992
   Number of wire bits:           6688
   Number of public wires:         313
   Number of public wire bits:    2994
   Number of ports:                 45
   Number of port bits:             54
   Number of memories:               0
   Number of memory bits:            0
   Number of processes:              0
   Number of cells:               5160
     $_ANDNOT_                    1412
     $_AND_                        174
     $_DFF_P_                      239
     $_MUX_                        513
     $_NAND_                        42
     $_NOR_                         99
     $_NOT_                         49
     $_ORNOT_                       74
     $_OR_                        1322
     $_SDFFE_PP0P_                 962
     $_SDFFE_PP1P_                  64
     $_SDFF_PP0_                     8
     $_XNOR_                        71
     $_XOR_                        129
     avsddac                         1
     avsdpll                         1

7.26. Executing CHECK pass (checking for obvious problems).
Checking module clk_gate...
Checking module rvmyth...
Checking module vsdbabysoc...
Found and reported 0 problems.
```

```
13. Printing statistics.

=== vsdbabysoc ===

   Number of wires:               4709
   Number of wire bits:           6183
   Number of public wires:        4709
   Number of public wire bits:    6183
   Number of ports:                  7
   Number of port bits:              7
   Number of memories:               0
   Number of memory bits:            0
   Number of processes:              0
   Number of cells:               5893
     $scopeinfo                      8
     avsddac                         1
     avsdpll                         1
     sky130_fd_sc_hd__a2111oi_0      8
     sky130_fd_sc_hd__a211oi_1      12
     sky130_fd_sc_hd__a21boi_0       3
     sky130_fd_sc_hd__a21o_2         4
     sky130_fd_sc_hd__a21oi_1      682
     sky130_fd_sc_hd__a221oi_1     165
     sky130_fd_sc_hd__a22oi_1      133
     sky130_fd_sc_hd__a311oi_1       8
     sky130_fd_sc_hd__a31oi_1      333
     sky130_fd_sc_hd__a32o_1         1
     sky130_fd_sc_hd__a32oi_1        2
     sky130_fd_sc_hd__a41oi_1       13
     sky130_fd_sc_hd__and2_2         3
     sky130_fd_sc_hd__and3_2         1
     sky130_fd_sc_hd__clkinv_1     579
     sky130_fd_sc_hd__dfxtp_1     1144
     sky130_fd_sc_hd__lpflow_inputiso0p_1      1
     sky130_fd_sc_hd__mux2i_1       11
     sky130_fd_sc_hd__nand2_1      823
     sky130_fd_sc_hd__nand3_1      278
     sky130_fd_sc_hd__nand3b_1       1
     sky130_fd_sc_hd__nand4_1       48
     sky130_fd_sc_hd__nor2_1       388
     sky130_fd_sc_hd__nor3_1        33
     sky130_fd_sc_hd__nor3b_1        1
     sky130_fd_sc_hd__nor4_1         6
     sky130_fd_sc_hd__o2111a_1       2
     sky130_fd_sc_hd__o2111ai_1     24
     sky130_fd_sc_hd__o211ai_1      48
     sky130_fd_sc_hd__o21a_1         8
     sky130_fd_sc_hd__o21ai_0      867
     sky130_fd_sc_hd__o21bai_1      13
     sky130_fd_sc_hd__o221ai_1       6
     sky130_fd_sc_hd__o22ai_1      154
     sky130_fd_sc_hd__o311ai_0       4
     sky130_fd_sc_hd__o31ai_1        1
     sky130_fd_sc_hd__o41ai_1        2
     sky130_fd_sc_hd__or2_2         14
     sky130_fd_sc_hd__or4_2          1
     sky130_fd_sc_hd__xnor2_1       16
     sky130_fd_sc_hd__xor2_1        42
```

<img width="1919" height="376" alt="image" src="https://github.com/user-attachments/assets/79b725f8-5eb4-47bf-a728-5ccccb64f655" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d9527934-d22e-4fda-a6d4-e3d1f5357e06" />
<img width="1919" height="425" alt="image" src="https://github.com/user-attachments/assets/81158419-d619-422a-add7-bfb22e6226ca" />

</details>
