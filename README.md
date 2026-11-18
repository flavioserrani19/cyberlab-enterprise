# CyberLab Enterprise

Progettazione, implementazione, sicurezza e resilienza di un'infrastruttura IT virtualizzata secondo un approccio NIS2.

Relazione tecnica finale del tirocinio "Sistemi e Reti – Cybersecurity" (140 ore) svolto presso l'Istituto CEFI, settembre – ottobre 2026.

📄 **[Leggi la relazione completa (PDF, 57 pagine)](CyberLab_Enterprise_Relazione.pdf)**

## Panoramica

Il progetto riproduce in scala ridotta un'infrastruttura aziendale: dalla progettazione della rete alla configurazione dei servizi, fino alla messa in sicurezza e al vulnerability assessment. Ogni attività segue il flusso:

**Attività → Configurazione → Test → Evidenza → Report → Mappatura NIS2**

Ciascuna configurazione è stata verificata con test positivi e negativi e documentata con evidenze (screenshot, file di configurazione, output dei comandi).

## Contenuti

| Area | Attività |
|---|---|
| Architettura di rete | Topologia in Cisco Packet Tracer, segmentazione VLAN, DMZ, inventario degli asset |
| Virtualizzazione | Provisioning delle VM con Vagrant su VMware Workstation |
| Storage | RAID software, LVM, simulazione di guasto e ripristino |
| Directory e file sharing | File server Samba con autenticazione OpenLDAP |
| Accesso amministrativo | SSH con certificati emessi da una CA e autenticazione a due fattori |
| Sicurezza perimetrale | Firewall iptables con politica deny by default, DMZ, accesso remoto OpenVPN |
| Ambiente Windows | Windows Server con Active Directory, SQL Server e SharePoint |
| Vulnerability assessment | Nmap e OWASP ZAP su sistema di laboratorio isolato |
| Gestione del rischio | Risk Register, Remediation Plan e matrice di correlazione NIS2 |
| Automazione (appendice) | Configurazione di tre server con Ansible |

## Tecnologie

Ubuntu Server · Windows Server · Active Directory · VMware Workstation · Vagrant · Ansible · Cisco Packet Tracer · iptables · OpenVPN · OpenLDAP · Samba · SQL Server · SharePoint · Nmap · OWASP ZAP

## Note

Tutte le attività di security testing sono state eseguite esclusivamente su sistemi di laboratorio autorizzati e isolati. Il riferimento alla Direttiva NIS2 ha valore metodologico e non costituisce attestazione di conformità.

## Autore

**Flavio Serrani**, tecnico sistemista e cybersecurity (qualifica regionale)
