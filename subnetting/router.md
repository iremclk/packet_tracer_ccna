###Router Konfigürasyon
 
  *enable
  *config

  ***eth0/0 bacağı konfigürasyon
  
   *interface e0/0
   *no shutdown(bacak aktif edildi)
   *ip address "default gateway"  "alt ağ maskesi"(router hangi bilgisayara bağlıysa onun bilgileri yazılır)
   *exit

  ***eth1/0 bacağı konfigürasyon
 
   *interface e1/0
   *no shutdown(bacak aktif edildi)
   *ip address "default gateway"  "alt ağ maskesi"(router hangi bilgisayara bağlıysa onun bilgileri yazılır)
   *exit

  ***Son olarak
   *"do write" diyerek konfigürasyonu kaydediyoruz.
 
