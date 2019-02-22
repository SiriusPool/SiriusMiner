## [ 0.3.0 ] -  2019-02-22
 ### Fixed
  -  Poollist will update when miner disconnecting.
### Changed
 - AutoUpgrades will downloading from github since 0.3.0
 
## [ 0.2.9 ] -  2019-02-17
  ### Changed 
  - Nimiq Core to 1.4.3
## [ 0.2.8 ] - 	2019-02-15
  ### Added
  - AutoUpgrade background service. 
  ### Changed 
  - Nimiq Core to 1.4.2

## [0.2.7] - 2018-12-10 
  ### Added
  - Optimized Multipool. ( passed dynamicaly pool url and ports   )
	 Pool Url and Ports are not hardcoded in miners , passed each time a miner starts mining.
  ### Changed
- Now Miners Use Nimiq Core 1.4.1 instead of 1.3.1

## sirius.conf -- sample
```json
{
        "address": "NQ18 37VM K2Y5 2HPY 5U80 2E0U VHUJ R7RK QSNE",
        "threads": 16,
        "name": "miner_name",
        "email":"example@gmail.com",
        "server":"siriuspool.net" ,
        "autoUpdates": {
          "enabled": true,
          "default_install_location": "~/",
         }
}
```
