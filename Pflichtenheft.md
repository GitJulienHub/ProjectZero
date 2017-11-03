## Pflichtenheft


### Allgemeine Beschreibung des Projekts

Community-Plattform f�r Computerspiele

### Spiele-Bibliothek
In der Spielebibliothek werden alle verf�gbaren (gekauften) Spiele angezeigt. Diese k�nnen dann aus der Spielebibliothek gestartet werden. Spiele k�nnen �ber ein Men� der Bibliothek hinzugef�gt werden. F�r jedes Spiel werden eine Beschreibung, eine Bewertung und die Kontakte angezeigt welche im Moment dieses Spiel spielen und besitzen.
### Terminplaner
Im Terminplaner soll es f�r den Benutzer m�glich seine Termine einzutragen. Diese Termine k�nnen f�r den Benutzer selber sein oder auch f�r eine ganze Gruppe in der Anwendung. Wenn der Benutzer sich daf�r entscheidet ein Termin f�r eine Gruppe zu planen, k�nnen andere f�r den Termin abstimmen und somit zeigen, dass sie an  dem Tag Zeit haben oder f�r den Termin absagen. Au�erdem wird ein Gruppenmitglied zeitnah benachrichtigt, wenn eine Veranstaltung ansteht. Zur �bersicht werden die Termine in einem Kalender dargestellt, indem man auch an einem bestimmten Tag ein Termin eintragen kann.
### Gruppen
TBD -- Es gibt einen Besitzer, der die Gruppe verwalten kann. Zur Verwaltung geh�ren z.B. die Namens�nderung, Erstellung von Terminen oder die Gruppenl�schung (alle Funktionalit�ten werden im Verlauf hinzugef�gt).
### Chatr�ume
Es wird zwischen Privatchats, Gruppenchats und �ffentliche Chatr�umen unterschieden. In den Chatr�umen stehen Emojis zur Verf�gung. Hyperlinks m�ssen anklickbar sein. Beim Senden einer Textnachricht wird zuerst der Benutzername und dann mit einem ":" getrennt die Textnachricht angezeigt.
Man kann Privatchats �ber einen Doppelklick auf den jeweiligen Kontakt �ffnen.
�ffentliche Chatr�ume k�nnen erstellt und mit Passw�rtern versehen werden. Jeder �ffentlicher Chatraum muss einen einzigartigen Namen haben. Es steht eine Liste mit aktiven in den Chat beigetretenen Benutzern zur Verf�gung. �ber diese Liste k�nnen Benutzer zu den Kontakten hinzugef�gt werden. Benutzer k�nnen Stumm geschaltet werden. 
�ber die Gruppenliste kommt man per Doppelklick in den Gruppenchat. Rechts des Gruppenchats wird eine Liste mit den Mitgliedern angezeigt.
### Freundesliste
Es gibt die Tabs "Freunde" und "Gruppen". In dem Tab "Freunde" werden die Freunde des jeweiligen Benutzers aufgelistet und in dem "Gruppen" Tab die Gruppen. Es k�nnen Freunde hinzuf�gt und gel�scht werden. Diese Freunde werden dann mit einem Status angezeigt. Der Status kann zwischen Online, Offline, Besch�ftigt und Abwesend variieren, die jeweils mit einer bestimmten Farbe gekennzeichnet sind. Au�erdem bekommt man angezeigt, in welchem Chatraum bzw. Spiel sie sich gerade befinden. Es sind ebenfalls Funktionen zum �ffnen eines Privatchats, L�schen des Freundes, Hinzuf�gen des Freundes und zum Wechseln des Status vorhanden. Das Anzeigen des derzeitigen Spiels/Chatraums erfolgt automatisch. Es k�nnen Gruppen erstellt und gel�scht werden. Man kann Gruppe beitreten und sie verlassen. Andere Kontakte k�nnen in Gruppen eingeladen werden.
### Notizen
Dem Benutzer ist es m�glich Notizen anzulegen. Diese kann er au�erdem mit anderen Benutzern oder Gruppen teilen. Die Notizen k�nnen dadurch angeguckt oder von anderen bearbeitet werden. Der Notizenersteller, kann aber auch festlegen, wer diese Notiz bearbeiten darf. Die Notizen k�nnen dann auch den Benutzer oder die Benutzergruppe �ber festgelegte Zeit benachrichtigen.
### Bewertungsfunktion
Die Bewertungsfunktion(Verweis/Bewertungssterne) wird bei jedem Spiel anzeigt und kann von jedem Benutzer individuell ausgef�llt werden. Jeder Benutzer kann zu seiner Bewertung ein kleiner Text verfassen, dort kann er schreiben was er gut und/oder schlecht an diesem Spiel findet. Andere Benutzer sehen bei jedem Spiel, die Bewertung von jedem Benutzer, der das Spiel bewertet hat.�
### Frontend
 **Clientbeschreibungen f�r ProjectZero**


#### Webclient

**Responsiver Webclient mit PHP, CSS, JavaScript**

| Framework | Sprache 
|:------------ |:--------- |
| Laravel | PHP |
| Bootstrap | CSS |
| Angular 4 | JavaScript |


#### Mobilclient f�r Android und iOS
**Ionic Framework basierend auf HTML5 und AngularJS**

| Framework | Sprache 
|:------------ |:--------- |
| Ionic | HTML5, AngularJS |


#### Desktop-Client f�r Windows
**Desktopanwendung geschrieben in C#**

### Backend

#### Server:
Ein Webserver wird f�r die Backend Applikation ben�tigt.
Der Server ben�tigt mindestens diese Anforderungen, da Laravel als Backend f�r das Projekt benutzt wird.
Larvel ist ein PHP Framework, welches als eine RESTful API L�sung benutzt wird um die Client Anfragen zu verarbeiten und mit der Datenbank kommuniziert.

https://laravel.com/

##### Server Anforderung:

##### System:
* PHP >= 7.0.0	
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension

##### Software:
* Nginx oder Appache
* Composer
* Datenbank (MySQL)
* Node
* Git

#### Datenbank:
Die Datenbank kann auch in Laravel aufgebaut werden, daf�r k�nnen Migrations verwedendet werden.

>Migrations are like version control for your database, allowing your team to easily modify and share the application's database schema. Migrations are 
>typically paired with Laravel's schema builder to easily build your application's database schema. If you have ever had to tell a teammate to manually 
>add a column to their local database schema, you've faced the problem that database migrations solve.

[Quelle](https://laravel.com/docs/5.5/migrations) 


### Optionale Features
* Forum
* Shop
* Blog


### Rollenverteilung
#### Frontend
| Desktop | Web | Mobil |
|:--------|:----|:------|
| Stefan K. | Patrick R. | Julien G. |
| Dejan N. | Marti S. | Maximilian K. |
| Pascal T. |
| Steffen D. |
| Marcel P. |
| Marvin K. |
| Luis D. |
| Phillip P. |

#### Backened
| Datenbank | Server |
|:----------|:-------|
| Nicola K. | Frank K |
| Julian W. | Marc W. |
| Chris S. | Erik E. |
| Jonas P. |

**Fehlende Eintr�ge, sowie Rollenverteilung werden hinzugef�gt, sobald es zur Entwicklung kommt.**