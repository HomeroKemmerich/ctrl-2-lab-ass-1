# Tabela de Zieger-Nichols

| Tipo de controle | $K_p$          | $T_i$     | $T_d$          | $K_i$             | $K_d$     |
| :--------------- | :---:          | :---:     | :---:          | :---:             | :---:     |
| P                | $0,50K_u$      | $-$       | $-$            | $-$               | $-$       |
| PI               | $0,45K_u$      | $0,83T_u$ | $-$            | $0,54(K_u/T_u)$   | $-$       |
| PD               | $0,80K_u$      | $-$       | $0,125T_u$     | $-$               | $0,100K_uT_u$  |
| PID Clássico     | $0,60K_u$      | $0,50T_u$ | $0,125T_u$     | $1,20(K_u/T_u)$   | $0,075K_uT_u$  |
| Integrador de Pessen | $0,70K_u$  | $0,40T_u$ | $0,150T_u$     | $1,75(K_u/T_u)$   | $0,105K_uT_u$  |
| Com overshoot    | $0,3\dot3K_u$  | $0,50T_u$ | $0,33\dot3T_u$ | $0,66(K_u/T_u)$   | $0,11\dot1K_uT_u$  |
| Sem overshoot    | $0,20K_u$      | $0,50T_u$ | $0,33\dot3T_u$ | $0,40(K_u/T_u)$   | $0,066K_uT_u$  |