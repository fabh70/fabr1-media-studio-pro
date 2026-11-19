[README.md](https://github.com/user-attachments/files/35086793/README.md)
# Média Studio PRO

**Français** · [English](#english) · [Nederlands](#nederlands)

Outil Windows de tri de photos et de vidéos par reconnaissance faciale.

Média Studio PRO analyse un dossier de médias et classe automatiquement les fichiers selon les personnes qui y apparaissent. Vous créez les personnes dans l'application, et le tri se fait tout seul.

## Fonctionnalités

- Tri automatique des photos par reconnaissance faciale
- Tri automatique des vidéos par reconnaissance faciale
- Recherche de doublons (stricts et similaires) pour libérer de l'espace
- Regroupement par événements sur plusieurs jours (de 1 à 10 jours) : sorties, fêtes, vacances…
- Interface en français, anglais ou néerlandais
- Fonctionne hors ligne : aucun fichier n'est envoyé sur internet
- Version portable (clé USB, sans installation) et version installable
- Profils, réglages et journal restent sur votre PC

## Premier lancement

Au premier démarrage, l'application demande la langue de travail (français, anglais ou néerlandais). Elle se change ensuite dans **Réglages → Langue** (redémarrage nécessaire).

La version publique ne contient aucun profil de visage. Vous pouvez créer vos personnes de deux façons :

- Cliquez sur **＋ Ajouter une personne** dans l'application.
- Ou déposez des photos dans le dossier `Profils Visages Photos\<Prénom>\` (ou `Profils Visages Vidéos\<Prénom>\` pour les vidéos).

Le dossier `Profils Visages Photos` et ses sous-dossiers sont créés automatiquement. Il n'y a rien à créer à la main.

## Lancement

Lancez `FABR1_Media_Studio.exe`. Gardez impérativement le dossier complet, y compris le sous-dossier `_internal`, sinon l'application ne démarrera pas.

Les réglages et le journal sont enregistrés dans le même dossier, dans les fichiers `config_tri.json` et `fabr1_media_studio.log`.

**Version portable :** décompressez le ZIP dans un dossier court, par exemple `C:\FabR1` (ou utilisez 7-Zip). Windows limite les chemins à 260 caractères ; un dossier trop profond peut empêcher l'extraction de certains fichiers.

## Utilisation

1. Créez vos personnes ou ajoutez leurs photos de référence.
2. Indiquez le dossier source contenant les médias à trier.
3. Indiquez le dossier de destination.
4. Lancez le tri et attendez la fin du traitement.

**Important :** ne placez jamais le dossier source ni le dossier de destination à l'intérieur de `Profils Visages Photos` ou `Profils Visages Vidéos`.

## Mise à jour et désinstallation

- **Mise à jour :** lancez le nouveau `Setup` en choisissant le **même dossier** d'installation. Profils, réglages et journal sont conservés.
- **Désinstallation :** elle ne retire que le programme (`FABR1_Media_Studio.exe` et `_internal`). Vos profils, `config_tri.json` et le journal restent en place.
- **Sauvegarde conseillée :** copiez `Profils Visages Photos`, `Profils Visages Vidéos` et `config_tri.json` sur un disque externe.

## Configuration requise

- Windows 10 ou 11 (64 bits)

## Avertissement Windows SmartScreen

Lors du premier lancement, Windows peut afficher « Windows a protégé votre ordinateur ». Ce n'est pas un signe de virus : l'exécutable n'est simplement pas signé numériquement. Pour lancer l'application, cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

Pour éviter cet avertissement sur votre propre PC : clic droit sur le fichier (`Setup` ou `FABR1_Media_Studio.exe`) → **Propriétés** → cochez **Débloquer** → **OK**.

Les empreintes SHA-256 des fichiers publiés sont fournies dans `SHA256SUMS.txt`.

## Confidentialité

L'application fonctionne entièrement hors ligne. Aucune photo, vidéo, donnée de visage ou statistique n'est envoyée sur internet.

## Licence

À définir : par exemple MIT, ou « Tous droits réservés » si vous ne souhaitez pas autoriser la réutilisation.

## Auteur

FabR1

---

# English

[Français](#média-studio-pro) · **English** · [Nederlands](#nederlands)

Windows tool for sorting photos and videos using face recognition.

Média Studio PRO analyses a folder of media and automatically files each item according to the people in it. You create the people in the app, and the sorting then runs on its own.

## Features

- Automatic photo sorting using face recognition
- Automatic video sorting using face recognition
- Duplicate detection (strict and similar) to free up space
- Event grouping across several days (1 to 10 days): outings, parties, holidays…
- Interface in French, English or Dutch
- Works offline: no file is ever sent to the internet
- Portable version (USB stick, no installation) and installable version
- Profiles, settings and log stay on your PC

## First launch

On first start, the app asks for your working language (French, English or Dutch). You can change it later in **Settings → Language** (restart required).

The public version contains no face profiles. You can create your people in two ways:

- Click **＋ Add a person** in the app.
- Or drop photos into `Profils Visages Photos\<FirstName>\` (or `Profils Visages Vidéos\<FirstName>\` for videos).

The `Profils Visages Photos` folder and its subfolders are created automatically. There is nothing to set up by hand.

## Launching

Run `FABR1_Media_Studio.exe`. Always keep the whole folder, including the `_internal` subfolder, otherwise the app will not start.

Settings and the log are stored in the same folder, in `config_tri.json` and `fabr1_media_studio.log`.

**Portable version:** extract the ZIP into a short path, for example `C:\FabR1` (or use 7-Zip). Windows limits paths to 260 characters; a folder that is too deep may prevent some files from being extracted.

## Usage

1. Create your people or add their reference photos.
2. Select the source folder containing the media to sort.
3. Select the destination folder.
4. Start sorting and wait for the run to finish.

**Important:** never place the source or destination folder inside `Profils Visages Photos` or `Profils Visages Vidéos`.

## Updating and uninstalling

- **Update:** run the new `Setup` and choose the **same installation folder**. Profiles, settings and log are kept.
- **Uninstall:** only the program is removed (`FABR1_Media_Studio.exe` and `_internal`). Your profiles, `config_tri.json` and the log stay in place.
- **Recommended backup:** copy `Profils Visages Photos`, `Profils Visages Vidéos` and `config_tri.json` to an external drive.

## Requirements

- Windows 10 or 11 (64-bit)

## Windows SmartScreen warning

On first launch, Windows may show "Windows protected your PC". This is not a sign of a virus: the executable is simply not digitally signed. To run the app, click **More info**, then **Run anyway**.

To avoid this warning on your own PC: right-click the file (`Setup` or `FABR1_Media_Studio.exe`) → **Properties** → tick **Unblock** → **OK**.

SHA-256 checksums for the published files are provided in `SHA256SUMS.txt`.

## Privacy

The app works entirely offline. No photo, video, face data or statistic is ever sent to the internet.

## License

To be defined: for example MIT, or "All rights reserved" if you do not want to allow reuse.

## Author

FabR1

---

# Nederlands

[Français](#média-studio-pro) · [English](#english) · **Nederlands**

Windows-gereedschap om foto's en video's te sorteren met gezichtsherkenning.

Média Studio PRO analyseert een map met media en sorteert de bestanden automatisch volgens de personen die erop staan. Je maakt de personen aan in de app; daarna verloopt het sorteren vanzelf.

## Functies

- Automatisch foto's sorteren met gezichtsherkenning
- Automatisch video's sorteren met gezichtsherkenning
- Dubbele bestanden opsporen (strikt en gelijkend) om ruimte vrij te maken
- Media groeperen per gebeurtenis over meerdere dagen (1 tot 10 dagen): uitstapjes, feesten, vakanties…
- Interface in het Frans, Engels of Nederlands
- Werkt offline: er worden geen bestanden naar het internet verstuurd
- Draagbare versie (USB-stick, geen installatie) en installeerbare versie
- Profielen, instellingen en logboek blijven op je pc

## Eerste start

Bij de eerste start vraagt de app naar je werktal (Frans, Engels of Nederlands). Je kunt dit later wijzigen bij **Instellingen → Taal** (herstart nodig).

De publieke versie bevat geen gezichtsprofielen. Je kunt je personen op twee manieren aanmaken:

- Klik op **＋ Persoon toevoegen** in de app.
- Of plaats foto's in `Profils Visages Photos\<Voornaam>\` (of `Profils Visages Vidéos\<Voornaam>\` voor video's).

De map `Profils Visages Photos` en de submappen worden automatisch aangemaakt. Je hoeft niets handmatig in te stellen.

## Starten

Start `FABR1_Media_Studio.exe`. Bewaar altijd de volledige map, inclusief de submap `_internal`, anders start de app niet.

Instellingen en het logboek staan in dezelfde map, in `config_tri.json` en `fabr1_media_studio.log`.

**Draagbare versie:** pak het ZIP-bestand uit in een korte map, bijvoorbeeld `C:\FabR1` (of gebruik 7-Zip). Windows beperkt paden tot 260 tekens; een te diepe map kan verhinderen dat sommige bestanden worden uitgepakt.

## Gebruik

1. Maak je personen aan of voeg hun referentiefoto's toe.
2. Kies de bronmap met de media die je wilt sorteren.
3. Kies de doelmap.
4. Start het sorteren en wacht tot het klaar is.

**Belangrijk:** plaats de bron- of doelmap nooit in `Profils Visages Photos` of `Profils Visages Vidéos`.

## Bijwerken en verwijderen

- **Bijwerken:** start de nieuwe `Setup` en kies **dezelfde installatiemap**. Profielen, instellingen en logboek blijven bewaard.
- **Verwijderen:** alleen het programma wordt verwijderd (`FABR1_Media_Studio.exe` en `_internal`). Je profielen, `config_tri.json` en het logboek blijven staan.
- **Aanbevolen back-up:** kopieer `Profils Visages Photos`, `Profils Visages Vidéos` en `config_tri.json` naar een externe schijf.

## Vereisten

- Windows 10 of 11 (64-bits)

## Waarschuwing Windows SmartScreen

Bij de eerste start kan Windows melden: "Windows heeft uw pc beschermd". Dat is geen teken van een virus: het uitvoerbare bestand is eenvoudigweg niet digitaal ondertekend. Klik op **Meer informatie** en daarna op **Toch uitvoeren** om de app te starten.

Om deze waarschuwing op je eigen pc te vermijden: klik met de rechtermuisknop op het bestand (`Setup` of `FABR1_Media_Studio.exe`) → **Eigenschappen** → vink **Blokkering opheffen** aan → **OK**.

De SHA-256-controlewaarden van de gepubliceerde bestanden staan in `SHA256SUMS.txt`.

## Privacy

De app werkt volledig offline. Er worden geen foto's, video's, gezichtsgegevens of statistieken naar het internet verstuurd.

## Licentie

Nog te bepalen: bijvoorbeeld MIT, of "Alle rechten voorbehouden" als je hergebruik niet wilt toestaan.

## Auteur

FabR1
