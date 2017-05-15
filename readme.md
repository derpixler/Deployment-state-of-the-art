# Deployment – state of the art (de)

Auf dem [WordCamp Berlin 2017](https://2017.berlin.wordcamp.org/session/deployment-state-of-the-art/) wurde erklärt was Deployment heißt, warum und wie ein WordPress auf einen Live Server gelangt. In dieser Session wurden Mittel und Methoden vorgestellt wie WordPress/Plugin/Themes, kurz alle Daten rund um WordPress dezentral verwaltet werden können, welche Wege z.B. vom einfachen drag ’n‘ drop -> FTP bis zum automatisierten Deploy möglich sind.

*Hinweis:* Punkt 7. (Lasst uns etwas deployen) wird eine `composer.json` aus folgendem Git-Repo verwendet.
[Easy WordPress Composer Install](https://github.com/derpixler/easy-wordpress-composer-install)

![bildschirmfoto 2017-05-15 um 08 36 12](https://cloud.githubusercontent.com/assets/809219/26045249/9efcab3e-3949-11e7-9a93-14fe5647ecd7.png)

### Überblick der Folien
1. Hallo, mein Name ist - René Reimann @DerPixler
2. Was werde ich jetzt erzählen - ein Überblick
3. Begriffserklärung Deployment
4. Deployment = Verteilen
5. Wie wir Dinge verteilen? 
   - Drag & Drop uploads
   - Manuelle uploads (FTP/SFTP/SCP/CLI)
6. Deployment like a Pro
   - Easy
       - FTP-Programme mit Sync-Function: z.B Transmit
       - Commandline Tools: rsync
   - Semieasy
       - Projekt mit Composer installieren & aktualisieren
   - Full Stack
       - Services: envoyer.io, Atlassian Bamboo
       - Self hosted: deploy.org
7. Lasst uns etwas deployen.
8. Session Notes
       
### Über mich
```
/**
 * Hallo, mein Name ist René Reimann
 *
 * ich bin WordPress Professional, ausgebildeter Mediengestalter für Digital- & Printmedien,
 * Webentwickler, Webdesigner, Podcaster, Berater, Ausbilder, Mitglied in der
 * IHK-Prüfkommission (Mediengestalter für Digital & Printmedien) kurzum
 * Senior Fullstack Developer und das allerbeste ein Vater & Ehemann.
 *
 * @author          Rene Reimann 
 * @mail            info@rene-reimann.de
 * @phone           +49 171 83 66 824
 *
 * @twitter         https://twitter.com/DerPixler
 * @instagram       https://www.instagram.com/rene_reimann 
 * @github          https://github.com/derpixler 
 * @gist            https://gist.github.com 
 * @WordPress       https://profiles.wordpress.org/derpixler 
 * @Xing            https://www.xing.com/profile/Rene_Reimann 
 * @WP_Sofa         https://wp-sofa.de 
 * @Behance         https://www.behance.net/rene-reimann
 *
 **/
 ```