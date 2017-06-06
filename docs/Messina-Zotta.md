https://github.com/MessinaZotta/parking

# Daniel Messina – Daniele Zotta

## Trasformare il log attuale (tasto L) in uno strutturato verso file.

* Salvare il log su file
* Creare un programma che visualizza dati dettagliati (giorni, macchina, volte)


### Opzioni programma statistic.py

* -c, --car : Specificare la macchina di cui visualizzare le informazioni
* -s, --sensor : Specificare il parcheggio di cui visualizzare le informazioni
* -d, --date : Specificare la data di cui visulizzare le informazioni nel formato Y/M/D (Se non specificato viene sottointesa la data odierna)
* -p, --period : Specificare il periodo nel quale visualizzare le informazioni (secondo orario opzionale che viene assegnato all'orario attuale)

### Esempi d'uso del programma statistic.py

$ python statistic.py --car 2 --sensor 4 --date 2017/05/28 --period 11:58 15:46

$ python statistic.py --car 2 --period 08:53
