# [ContractShark](#)

> *in development* 
> 

## Testing Specification

| value | description |
|---------------------------|----------------|
| 'pending "([^"]*)"$'                            		| mark pending and skip all following steps in the scenario    |
| 'a "([^"]*)" of type "([^"]*)"'                 		| matches on types such as resource,data and the resource name |
| 'a "([^"]*)" of type "([^"]*)" named "([^"]*)"' 		| matches on types, resource names and instance names          |
| 'the value of "([^"]*)" always equals (\d+)'          	| matches on the value given and the value of the attribute    |
| 'the value of "([^"]*)" never equals (\d+)'      		| inverse match on attr value and given value                  |
| 'the value of "([^"]*)" always equals "([^"]*)"'      	| matches on the value given and the value of the attribute    |
| 'the value of "([^"]*)" never equals "([^"]*)"'  		| inverse match on attr value and given value                  |
| 'the value of "([^"]*)" always matches regex "([^"]*)"'   	| matches the attributes value on the given regex              |
| 'the value of "([^"]*)" is always greater than (\d+)'     	| matches on gt against the given value and attr value         |
| 'the value of "([^"]*)" is always less than (\d+)'        	| matches on lt against the given value and attr value         |
| 'attribute "([^"]*)" always equals (\d+)'              	| matches on the value given and the value of the attribute    |
| 'attribute "([^"]*)" never equals (\d+)'      		| inverse match on attr value and given value                  |
| 'attribute "([^"]*)" always equals "([^"]*)"'          	| matches on the value given and the value of the attribute    |
| 'attribute "([^"]*)" never equals "([^"]*)"'  		| inverse match on attr value and given value                  |
| 'attribute "([^"]*)" always matches regex "([^"]*)"'   	| matches the attributes value on the given regex              |
| 'attribute "([^"]*)" is always greater than (\d+)'     	| matches on gt against the given value and attr value         |
| 'attribute "([^"]*)" is always less than (\d+)'        	| matches on lt against the given value and attr value         |
| 'the value of "([^"]*)" equals (\d+)'              		| matches on the value given and the value of the attribute    |
| 'the value of "([^"]*)" does not equal (\d+)'      		| inverse match on attr value and given value                  |
| 'the value of "([^"]*)" equals "([^"]*)"'          		| matches on the value given and the value of the attribute    |
| 'the value of "([^"]*)" does not equal "([^"]*)"'  		| inverse match on attr value and given value                  |
| 'the value of "([^"]*)" matches regex "([^"]*)"'   		| matches the attributes value on the given regex              |
| 'the value of "([^"]*)" is greater than (\d+)'     		| matches on gt against the given value and attr value         |
| 'the value of "([^"]*)" is less than (\d+)'        		| matches on lt against the given value and attr value         |
| 'attribute "([^"]*)" equals (\d+)'              		| matches on the value given and the value of the attribute    |
| 'attribute "([^"]*)" does not equal (\d+)'      		| inverse match on attr value and given value                  |
| 'attribute "([^"]*)" equals "([^"]*)"'          		| matches on the value given and the value of the attribute    |
| 'attribute "([^"]*)" does not equal "([^"]*)"'  		| inverse match on attr value and given value                  |
| 'attribute "([^"]*)" matches regex "([^"]*)"'   		| matches the attributes value on the given regex              |
| 'attribute "([^"]*)" is greater than (\d+)'     		| matches on gt against the given value and attr value         |
| 'attribute "([^"]*)" is less than (\d+)'        		| matches on lt against the given value and attr value         |
| 'attribute "([^"]*)" exists'                    		| if the given attribute exists in the matching objects        |
| 'it occurs at least (\d+) times'                		| if the match set contains at least the given number          |
| 'it occurs at most (\d+) times'                 		| if the match set contains at most the given number           |
| 'it occurs exactly (\d+) times'                 		| if the match set continas exactly the given number           |
