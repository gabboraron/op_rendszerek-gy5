# GY5

> A signalok a processzek közötti kommunikációra használhatóak

### Ha foroklunk és egyből kiküldjük a gyereket akkor nem biztos hogy a szülő létezik


## Feladat
- legyen két gyerekfolyamat
- egyik gyerejk küldjön sigusr1 a szülőnek -> szülő írja ki, hogy milyen signalt kapott
- ezután a szülő azonnal küldjön SIGUSR2 a második gyereknek. -> a második gyerek írja ki, hogy mit kapott

> `gdb` debugger, jó lehet még

a fork 0-t ad akkor

signalküldés az zh feladat
