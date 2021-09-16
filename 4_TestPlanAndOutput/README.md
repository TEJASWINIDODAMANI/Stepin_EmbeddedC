# test plan and test output


|  Test ID | Description  | Input  | Output  | Status |
|---|---|---|---|---|
| ID01  | Is there a presence of a person in a seat  | 1 | 1 | PASS  |
| ID02  | There is no presence of a person in the seat  | 0 | 0 | PASS  |
| ID03  | Temperature sensor | Temp=0| heater=Off | PASS  |
| ID04  | Temperature sensor | Temp<=209 | heater=20 degree | PASS  |
| ID05  | Temperature sensor | Temp=210-509 | heater=25 degree | PASS  |
| ID06  | Temperature sensor | Temp=510-709 | heater=29 degree  | PASS  |
| ID07  | Temperature sensor | Temp=710-1024| heater=33 degree | PASS  |
| ID08  | LED ON | Button=1 && Heater=1| LED=1 | PASS  |
| ID09  | LED OFF | Button=0 && Heater=0| LED=0 | PASS  |
| ID10  | LCD Display | Temperature = 33 degree celsius| Temperature = 33 degree Celsius | PASS  |
