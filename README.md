# net_reserves
Kod TCMB'nin haftalık yayınladığı net rezerv verisini günlük olarak hesaplamayı amaçlar. Kodun mantığı öncelikle standby bilançodan haftalık net rezervi bul ve analitik bilanço'dan günlük dış varlık usd cinsi değişimi ekle ve banka zk yp mevduatı usd cinsinden farkı bul ve çıkartarak net rezerv verisine ekle şeklinde.

TCMB EVDSAPI ile verilere daha kolay erişme imkanı olmakla birlikte APİ Key kullanmak istemedeğimden uzun yolu tercih ettim. İlgili çalışmanın sonuçları png ve xlsx şeklinde de sunulmuştur.

Kod net_Rezerv klasörü altında yer almaktadır. 
