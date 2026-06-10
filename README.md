JDWorld OS è basato su Arch Linux con KDE Plasma 6 (minimale) ove ho iniziato a costruire l'OS secondo la mia visione. 
Non contiene Bloatware(software che reputo inutile), e SandBox come: Flatpak, Snapd o Docker(se volete potete sempre installarli), in quanto sono per il nativo.  
Gli aggiornamenti li esegue da ARCH, AUR, CHAOTIC e dal mio repo (JDWOS) per il software che creo/aggiorno per il JDWorld OS

Il JDWorld OS è cosi strutturato:
* jdwos-repo è il repo, dei pacchetti compilati del JDWorld OS;
* jdwos-stm è il repo, dell’interfaccia utente di JDWorld OS è gestito da un menù avanzato, multilivello e dinamico sviluppato in Python 3 utilizzando le librerie grafiche native PyQt6 (QWidgets)

Per il JDWorld OS - System Tray Menu (jdwos-stm), ho creato dei pacchetti estensione che aggiungono voci al menu(se il software è gia installato, aggiungerà solo le voci nel menu)
* jdwos-ff-stm, installa fastfetch ed aggiunge 4 voci in menu, 3 relative alla configurazione custom(hardware, software, e hardware + software ma con meno dettagli) e 1 relativa alla configurazione predefinita(stock)
* jdwos-ytdlp-stm, installa yt-dlp e aggiunge 3 comandi nel menu(scarica immagine, video, musica), in piu abilita klipper alla cattura di MP4/MP3
