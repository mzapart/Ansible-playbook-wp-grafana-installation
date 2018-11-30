Autorzy:
Sebastian Racja
Maciej Zapart

Aby poprawnie zainstalować aplikację należy uruchomić 3 serwery,
w pliku hosts.ini odpowiednio podać ich adresy publiczne
[web_nodes] dalej zwany "pierwszy" serwer
[db_nodes] dalej zwany "drugi"
[stats_nodes] dalej zwany "trzeci" serwer

Następnie w pliku install_env podmieniamy niżej wymienione zmienne wg wzoru
metrics_strorages_ip:<<prywatne ip serwera pierwszego>>
db_ip: <<prywatne ip serwera drugiego>>
apache_ip:<<publiczne ip serwera pierwszego

