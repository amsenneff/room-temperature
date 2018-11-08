Database Info:

DB: homepi
User: homepi

DATA DATABASE:
  Table: data_temp
  Rows: zone[1-7] (int)
 
CONFIG DATABASE:
  Table: config
  Rows: zn[1-7] (str) (zone name), disable_all (int) (1=on, 0=off)
  
STATUS DATABASE:
  Table: status
  Rows: zs[1-7] (int) (1=ok, 0=error) (zone status)
 
LAST UPDATED DATABASE:
  Table: updated
  Rows: zu[1-7] (str) (zone updated)
