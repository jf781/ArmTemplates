## "adminUsername"
- Must not be one of the following:
  - admin (also admin#)
  - administrator
  - user (also user#)
  - test (also test#)
  - root
  - owner
  - backup
  - console

## "adminPassword": {
Must be between 12 and 72 characters 
- Must be strong (3 of the usual suspects - Upper/lower, number, special characters)
- Cannot have "!!".  This causes issues with the mongo install script

## "storageAccountNamePrefix": {
- Must be all lower case

## "virtualNetworkName": {
No requirements

## "subnetName": {
No requirements

"addressPrefix": {
- Make sure it is in the xxx.xxx.xxx.xxx/xx format

## "subnetPrefix": {
- Make sure it is in the xxx.xxx.xxx.xxx/xx format

## "nodeAddressPrefix": {
- Make sure it is in the xxx.xxx.xxx.xxx format

## "replicaSetName":
No requirements


## "replicaSetKey": {
Must be between 12 and 72 characters 
- Must be strong (3 of the usual suspects - Upper/lower, number, special characters)
- Cannot have "!!".  This causes issues with the mongo install script