# Routing-Rip
Router 1
Router1> enable
Router1# configure terminal
Router1(config)# router rip
Router1(config-router)# version 2
Router1(config-router)# network 192.168.1.0
Router1(config-router)# network 10.10.10.0
Router1(config-router)# no auto-summary
Router1(config-router)# exit

router 2 
Router2> enable
Router2# configure terminal
Router2(config)# router rip
Router2(config-router)# version 2
Router2(config-router)# network 192.168.2.0
Router2(config-router)# network 10.10.10.0
Router2(config-router)# no auto-summary
Router2(config-router)# exit
