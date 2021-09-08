## TEST PLAN
## Table no: High level test plan
|Test ID|Description|Exp i/p|Exp o/p|Actual i/p|Actual o/p|
|-----|-----------------------------------------------|-------------------|-------------------------------|--------------------------------------|--------------|
|T1	|checking all the functions are working correcty|Call the functions|	All functions execute correctly|	All functions are executed correctly|	Requirement based|
|T2	|Checking whether called functions are executed |	Call a specific function |	Call function execute|	Called function is executed	|Scenario based|
|T3	|Check for features other than specified|	Choosing other values|	No output displayed|	No output is displayed	|Boundary based|

## Table no: Low level test plan
|Test ID|	Description	|Exp IN	|Exp OUT|	Actual I/P|	Actual O/P|
|-------|-------------|-------|-------|-----------|------------|
|T1	|Checking accept function is accepting users information|	user details|	accept the details|	accept the details|	Requirement based|
|T2|	Checking deposit method is able to update balance|	amount to be deposited|	updated balance|	updated balance|	Scenario based|
|T3|	checking withdraw method display insufficient balance if balance is low	|amount to withdraw|	low balance|	low balance|	Boundary based|
|T4|	search for record not present|	No information displayed	|user id|	No information displayed|	No information displayed|
|T5|	checking withdraw method is able to withdraw for sufficient balance|	amount to be withdrawn	|updated balance	|updated balance|	Scenario based|
|T6	|search for record present|	information displayed|	user id|	information displayed|	information displayed|
|T7|	search for record present|	information displayed|	user id|	information displayed|	information displayed|
