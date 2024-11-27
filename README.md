## Kurzbeschreibung
Dies sind die Installations- und Konfigurationsdaten von Ansible für das Hauptrojekt (siehe <a href="https://github.com/lb-bewerbung/jobscraper-springboot">Jobscraper-Springboot</a>). 

### Dateien
1. install_ansible.sh
   - Installiert Ansible auf der Kontrollmaschine
2. hosts.ini
   - Angabe von Zielservern
3. ansible-playbook.yml 
   - Konfiguration des Zielservers für die Jobscraper-Springboot App
4. ansible-playbook-dryrun.yml
   - Vorgesehen für Probelauf mit `--check`-Parameter
   - Führt alle Playbook tasks aus und ignoriert eventuelle Fehler
