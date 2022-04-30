# ASCMHL

## Crea MHL

$> ascmhl create -v /disco_spola/A002R2EC

dopo la copia su un disco_server

$> ascmhl create -v /disco_server/A002R2EC

se occorre un diverso tipo di hash (es. MD5)

$> ascmhl create -v -h md5 /disco_server/A002R2EC

da verificare - hash type
- md5
- sha1
- xxh32
- xxh64
- xxh3
- xxh128
- C4


## Installazione di ascmhl in anaconda:
creare un ambiente in conda, installare i packages richiesti per mezzo del file requirements.txt

$> pip3 install --upgrade-strategy only-if-needed -r /path/to/requirements.txt

### disattivare caricamento automatico di conda base environment
$> conda config --set auto_activate_base false

quindi:
$> conda activate my_env

$> conda deactivate
