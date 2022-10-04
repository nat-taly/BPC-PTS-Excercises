# EXERCISE 07 - Základní konfigurace přístupového směrovače

### Nastavení aktuálního data a času

Pro zobrazení aktuálního data slouží příkaz `show clock`

```
enable
clock set 15:08:00 Oct 26 2012
exit
```

### Nastavení jména zařízení

Pro zobrazení aktuálních informací slouží příkaz `show run`

```
enable
configure terminal
hostname CE
```

### Nastavení zakázaní vyhledávání
```
enable
configure terminal
no ip domain-lookup
```

### Vypnutí logování do konzole
```
enable
configure terminal
no logging console informational
```
