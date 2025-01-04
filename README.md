# msfarsi-az104-G5
salam dostan group 5 va mentor hai aziz 

in repository baray share kardan link , graph, code, rahkar va har chiz dig ke dar movred chalesh niaz hast ijad shode 
fileha shamel


1. Azure lb and backup solution  -  item haye mohem movred niaz proje va molahezat matrah shde
2. Diagram 1.0                   -  version aval diagram pishnahadi ba tavajoh be barrasi avalieh porje
3. Source&URL                    -  manabe amoozeshi dar movred topic haye matrah shode shamel microsoft learn va ....
4. run solution                  -  masir pishnahadi tarahi va ejra proje

define input variable for VNET/SUBNET, VM, LB in main.bicep file 
login in Azure subscription
    az login 
create resource with main.bicep
    az deployment group create --resource-group sch-Mostafa-Mostafavinezhad-rg --template-file main.bicep  --name webapp 

this bicep file create 3 item in scenario 
1. 1*vm (2* subnet)
2. LB (front end,backend,heal probs,snat,dnat )
3. 2*vm(interface, vm)
create mault resource (backup vault+workspace+query+agent for vm)

