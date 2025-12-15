# Tutoriel Complet : Shizuku + Delta + Tasker
## Complete Tutorial: Shizuku + Delta + Tasker
## Tutorial Completo: Shizuku + Delta + Tasker

---

## 🇫🇷 FRANÇAIS

### Introduction

Ce tutoriel vous expliquera comment configurer et utiliser **Shizuku**, **Delta** et **Tasker** ensemble pour accéder à des fonctionnalités avancées de votre appareil Android sans avoir besoin d'accès root.

- **Shizuku** : Application qui se connecte à ADB (Android Debug Bridge) sans nécessiter un ordinateur
- **Delta** : Émulateur de jeux retro qui fonctionne avec Shizuku
- **Tasker** : Application d'automatisation puissante qui peut utiliser les privilèges de Shizuku

### Prérequis

- Un appareil Android (Android 10 ou plus récent recommandé)
- Options de développeur activées
- Une connexion Wi-Fi stable
- Les trois applications installées (Shizuku, Delta, Tasker)

### Étape 1 : Configuration de Shizuku

#### 1.1 Activation du Mode Développeur

1. Allez dans **Paramètres** → **À propos du téléphone**
2. Appuyez 7-10 fois sur **Numéro de version** jusqu'à voir "Mode développeur activé"
3. Retournez aux paramètres et entrez **Options de développement**

#### 1.2 Activation du Débogage Sans Fil

1. Dans **Options de développement**, cherchez **Débogage sans fil (WiFi)**
2. Activez cette option
3. Une notification apparaîtra avec un code d'appairage

#### 1.3 Appairage avec Shizuku

1. Ouvrez l'application **Shizuku**
2. Appuyez sur **Commencer l'appairage**
3. Sélectionnez **Coupler l'appareil avec le code d'appairage**
4. Entrez le code d'appairage affiché dans les options de développement
5. Confirmez l'appairage

#### 1.4 Démarrage de Shizuku

1. Dans l'application Shizuku, sélectionnez la méthode de démarrage appropriée
2. Pour les appareils non rootés, choisissez le débogage sans fil
3. Appuyez sur **Démarrer** ou **Lancer Shizuku**

**Note** : Une fois Shizuku est configuré, il peut démarrer automatiquement au redémarrage de l'appareil.

### Étape 2 : Installation et Configuration de Delta

#### 2.1 Installation

1. Téléchargez la dernière version de Delta depuis [GitHub](https://github.com/DeltaCore/Delta-iOS) ou IzzyOnDroid F-Droid
2. Installez l'APK

#### 2.2 Octroi des Permissions à Shizuku

1. Ouvrez **Delta**
2. L'application demandera l'accès à Shizuku
3. Tapez sur **Autoriser** dans la notification
4. Confirmez dans l'application Shizuku si nécessaire

#### 2.3 Configuration des Émulateurs

1. Dans Delta, configurez vos jeux retro préférés
2. Téléchargez les ROM depuis des sources légales
3. Delta utilisera désormais Shizuku pour les fonctionnalités avancées

### Étape 3 : Intégration de Tasker avec Shizuku

#### 3.1 Installation de Tasker

1. Téléchargez et installez **Tasker** depuis le Google Play Store
2. Vous aurez droit à une période d'essai gratuite de 7 jours

#### 3.2 Autoriser Tasker à Utiliser Shizuku

1. Ouvrez **Shizuku**
2. Allez dans **Paramètres** (icône d'engrenage)
3. Cherchez **Autoriser les applications**
4. Trouvez **Tasker** dans la liste et activez-le

#### 3.3 Utilisation de Shizuku dans Tasker

**Méthode 1 : Actions Directes Intégrées**

Tasker dispose désormais d'actions intégrées qui fonctionnent automatiquement avec Shizuku :

- **Mode Avion** - Activer/désactiver le mode avion
- **Wi-Fi** - Activer/désactiver le Wi-Fi
- **Bluetooth** - Activer/désactiver Bluetooth
- **Partage de Connexion** - Activer/désactiver le partage Wi-Fi
- **Terminer l'Application** - Fermer une application
- **Gérer les Permissions** - Accorder/révoquer des permissions
- **Désactiver une Application** - Désactiver/activer une application

Vous n'avez qu'à créer ces actions normalement, et Tasker les exécutera avec les privilèges de Shizuku.

**Méthode 2 : Exécuter des Commandes Shell**

1. Créez une nouvelle Tâche dans Tasker
2. Ajoutez une action **Fichier** → **Exécuter Commande Shell**
3. Dans la commande, utilisez votre commande ADB souhaitée
4. Activez l'option **Shizuku** si disponible

### Étape 4 : Exemples d'Automatisation

#### Exemple 1 : Activer le Partage Wi-Fi en Arrivant au Travail

1. Créez un profil de localisation basé sur un endroit spécifique
2. Associez une tâche avec l'action **Partage de Connexion** définie sur **ON**
3. Tasker activera automatiquement le partage quand vous arriverez à cet endroit

#### Exemple 2 : Fermer les Applications Gourmandes en Batterie

1. Créez une tâche avec l'action **Terminer l'Application**
2. Sélectionnez les applications que vous souhaitez fermer
3. Associez-la à un profil basé sur le niveau de batterie faible

#### Exemple 3 : Activer le Mode Avion à une Heure Spécifique

1. Créez un profil horaire pour une heure précise
2. Ajoutez l'action **Mode Avion** définie sur **ON**
3. Créez un profil d'annulation pour le réactiver plus tard

### Dépannage

**Shizuku ne démarre pas :**
- Vérifiez que le débogage sans fil est activé
- Réactivez le débogage sans fil et reconnectez-vous
- Redémarrez l'appareil

**Tasker n'a pas accès à Shizuku :**
- Ouvrez Shizuku et vérifiez que Tasker est autorisé
- Redémarrez les deux applications
- Vérifiez que vous utilisez Tasker 6.6.2 ou plus récent

**Delta ne fonctionne pas :**
- Vérifiez que Shizuku est en cours d'exécution
- Accordez à nouveau les permissions à Delta dans Shizuku
- Redémarrez Delta

---

## 🇬🇧 ENGLISH

### Introduction

This tutorial will explain how to set up and use **Shizuku**, **Delta**, and **Tasker** together to access advanced features of your Android device without needing root access.

- **Shizuku** : Application that connects to ADB (Android Debug Bridge) without requiring a computer
- **Delta** : Retro game emulator that works with Shizuku
- **Tasker** : Powerful automation app that can use Shizuku's privileges

### Requirements

- An Android device (Android 10 or newer recommended)
- Developer options enabled
- A stable Wi-Fi connection
- All three applications installed (Shizuku, Delta, Tasker)

### Step 1 : Setting Up Shizuku

#### 1.1 Enabling Developer Mode

1. Go to **Settings** → **About Phone**
2. Tap **Build Number** 7-10 times until you see "Developer mode enabled"
3. Return to settings and enter **Developer Options**

#### 1.2 Enabling Wireless Debugging

1. In **Developer Options**, find **Wireless Debugging (WiFi)**
2. Enable this option
3. A notification will appear with a pairing code

#### 1.3 Pairing with Shizuku

1. Open the **Shizuku** application
2. Tap **Start Pairing**
3. Select **Pair Device with Pairing Code**
4. Enter the pairing code displayed in Developer Options
5. Confirm the pairing

#### 1.4 Starting Shizuku

1. In the Shizuku app, select the appropriate startup method
2. For non-rooted devices, choose Wireless Debugging
3. Tap **Start** or **Launch Shizuku**

**Note** : Once Shizuku is configured, it can start automatically on device restart.

### Step 2 : Installing and Configuring Delta

#### 2.1 Installation

1. Download the latest version of Delta from [GitHub](https://github.com/DeltaCore/Delta-iOS) or IzzyOnDroid F-Droid
2. Install the APK

#### 2.2 Granting Shizuku Permissions

1. Open **Delta**
2. The application will request access to Shizuku
3. Tap **Allow** in the notification
4. Confirm in the Shizuku app if necessary

#### 2.3 Configuring Emulators

1. In Delta, set up your favorite retro games
2. Download ROMs from legal sources
3. Delta will now use Shizuku for advanced features

### Step 3 : Integrating Tasker with Shizuku

#### 3.1 Installing Tasker

1. Download and install **Tasker** from Google Play Store
2. You will get a free 7-day trial period

#### 3.2 Authorizing Tasker to Use Shizuku

1. Open **Shizuku**
2. Go to **Settings** (gear icon)
3. Look for **Authorize Apps**
4. Find **Tasker** in the list and enable it

#### 3.3 Using Shizuku in Tasker

**Method 1 : Built-in Direct Actions**

Tasker now has built-in actions that automatically work with Shizuku :

- **Airplane Mode** - Enable/disable airplane mode
- **WiFi** - Enable/disable WiFi
- **Bluetooth** - Enable/disable Bluetooth
- **WiFi Tether** - Enable/disable WiFi sharing
- **Kill App** - Close an application
- **Manage Permissions** - Grant/revoke permissions
- **Disable App** - Disable/enable an application

You simply create these actions normally, and Tasker will execute them with Shizuku's privileges.

**Method 2 : Running Shell Commands**

1. Create a new Task in Tasker
2. Add an action **File** → **Run Shell Command**
3. In the command, use your desired ADB command
4. Enable the **Shizuku** option if available

### Step 4 : Automation Examples

#### Example 1 : Enable WiFi Sharing When Arriving at Work

1. Create a location-based profile for a specific place
2. Link a task with the **WiFi Tether** action set to **ON**
3. Tasker will automatically enable sharing when you arrive at that location

#### Example 2 : Close Battery-Hungry Apps

1. Create a task with the **Kill App** action
2. Select the apps you want to close
3. Link it to a profile based on low battery level

#### Example 3 : Enable Airplane Mode at a Specific Time

1. Create a time-based profile for a specific hour
2. Add the **Airplane Mode** action set to **ON**
3. Create a cancellation profile to re-enable it later

### Troubleshooting

**Shizuku won't start :**
- Check that wireless debugging is enabled
- Re-enable wireless debugging and reconnect
- Restart your device

**Tasker doesn't have access to Shizuku :**
- Open Shizuku and verify that Tasker is authorized
- Restart both applications
- Check that you're using Tasker 6.6.2 or newer

**Delta isn't working :**
- Check that Shizuku is running
- Grant permissions to Delta again in Shizuku
- Restart Delta

---

## 🇪🇸 ESPAÑOL

### Introducción

Este tutorial le explicará cómo configurar y usar **Shizuku**, **Delta** y **Tasker** juntos para acceder a funciones avanzadas de su dispositivo Android sin necesidad de acceso root.

- **Shizuku** : Aplicación que se conecta a ADB (Android Debug Bridge) sin requerir una computadora
- **Delta** : Emulador de juegos retro que funciona con Shizuku
- **Tasker** : Aplicación de automatización poderosa que puede usar los privilegios de Shizuku

### Requisitos

- Un dispositivo Android (Android 10 o más nuevo recomendado)
- Opciones de desarrollador habilitadas
- Una conexión Wi-Fi estable
- Las tres aplicaciones instaladas (Shizuku, Delta, Tasker)

### Paso 1 : Configurar Shizuku

#### 1.1 Habilitar Modo de Desarrollador

1. Vaya a **Configuración** → **Acerca de**
2. Toque **Número de compilación** 7-10 veces hasta ver "Modo de desarrollador habilitado"
3. Vuelva a la configuración e ingrese **Opciones de desarrollo**

#### 1.2 Habilitar Depuración Inalámbrica

1. En **Opciones de desarrollo**, busque **Depuración inalámbrica (WiFi)**
2. Habilite esta opción
3. Aparecerá una notificación con un código de emparejamiento

#### 1.3 Emparejar con Shizuku

1. Abra la aplicación **Shizuku**
2. Toque **Comenzar emparejamiento**
3. Seleccione **Emparejar dispositivo con código de emparejamiento**
4. Ingrese el código de emparejamiento mostrado en Opciones de desarrollo
5. Confirme el emparejamiento

#### 1.4 Iniciar Shizuku

1. En la aplicación Shizuku, seleccione el método de inicio apropiado
2. Para dispositivos sin root, elija Depuración inalámbrica
3. Toque **Iniciar** o **Lanzar Shizuku**

**Nota** : Una vez que Shizuku esté configurado, puede iniciarse automáticamente al reiniciar el dispositivo.

### Paso 2 : Instalar y Configurar Delta

#### 2.1 Instalación

1. Descargue la última versión de Delta desde [GitHub](https://github.com/DeltaCore/Delta-iOS) o IzzyOnDroid F-Droid
2. Instale el APK

#### 2.2 Otorgar Permisos de Shizuku

1. Abra **Delta**
2. La aplicación solicitará acceso a Shizuku
3. Toque **Permitir** en la notificación
4. Confirme en la aplicación Shizuku si es necesario

#### 2.3 Configurar Emuladores

1. En Delta, configure sus juegos retro favoritos
2. Descargue ROMs de fuentes legales
3. Delta ahora usará Shizuku para funciones avanzadas

### Paso 3 : Integrar Tasker con Shizuku

#### 3.1 Instalar Tasker

1. Descargue e instale **Tasker** desde Google Play Store
2. Tendrá un período de prueba gratuito de 7 días

#### 3.2 Autorizar que Tasker Use Shizuku

1. Abra **Shizuku**
2. Vaya a **Configuración** (icono de engranaje)
3. Busque **Autorizar aplicaciones**
4. Encuentre **Tasker** en la lista y habilítelo

#### 3.3 Usar Shizuku en Tasker

**Método 1 : Acciones Directas Integradas**

Tasker ahora tiene acciones integradas que funcionan automáticamente con Shizuku :

- **Modo avión** - Habilitar/deshabilitar modo avión
- **WiFi** - Habilitar/deshabilitar WiFi
- **Bluetooth** - Habilitar/deshabilitar Bluetooth
- **Compartir conexión** - Habilitar/deshabilitar compartir WiFi
- **Cerrar aplicación** - Cerrar una aplicación
- **Administrar permisos** - Otorgar/revocar permisos
- **Desactivar aplicación** - Desactivar/activar una aplicación

Simplemente crea estas acciones normalmente, y Tasker las ejecutará con los privilegios de Shizuku.

**Método 2 : Ejecutar Comandos de Shell**

1. Cree una nueva Tarea en Tasker
2. Agregue una acción **Archivo** → **Ejecutar comando de shell**
3. En el comando, use su comando ADB deseado
4. Habilite la opción **Shizuku** si está disponible

### Paso 4 : Ejemplos de Automatización

#### Ejemplo 1 : Habilitar Compartir WiFi al Llegar al Trabajo

1. Cree un perfil basado en ubicación para un lugar específico
2. Vincule una tarea con la acción **Compartir conexión** establecida en **ON**
3. Tasker habilitará automáticamente el compartir cuando llegue a esa ubicación

#### Ejemplo 2 : Cerrar Aplicaciones que Consumen Batería

1. Cree una tarea con la acción **Cerrar aplicación**
2. Seleccione las aplicaciones que desea cerrar
3. Vincúlelo a un perfil basado en nivel de batería bajo

#### Ejemplo 3 : Habilitar Modo Avión a una Hora Específica

1. Cree un perfil basado en tiempo para una hora específica
2. Agregue la acción **Modo avión** establecida en **ON**
3. Cree un perfil de cancelación para rehabilitarlo más tarde

### Solución de Problemas

**Shizuku no inicia :**
- Verifique que la depuración inalámbrica esté habilitada
- Vuelva a habilitar la depuración inalámbrica y reconéctese
- Reinicie su dispositivo

**Tasker no tiene acceso a Shizuku :**
- Abra Shizuku y verifique que Tasker esté autorizado
- Reinicie ambas aplicaciones
- Verifique que está usando Tasker 6.6.2 o más reciente

**Delta no funciona :**
- Verifique que Shizuku se está ejecutando
- Otorgue permisos a Delta nuevamente en Shizuku
- Reinicie Delta

---

## 🇩🇪 DEUTSCH

### Einführung

Dieses Tutorial zeigt Ihnen, wie Sie **Shizuku**, **Delta** und **Tasker** zusammen einrichten und verwenden, um auf erweiterte Funktionen Ihres Android-Geräts zuzugreifen, ohne Root-Zugriff zu benötigen.

- **Shizuku** : Anwendung, die sich mit ADB (Android Debug Bridge) verbindet, ohne einen Computer zu benötigen
- **Delta** : Retro-Spiel-Emulator, der mit Shizuku funktioniert
- **Tasker** : Leistungsstarke Automatisierungs-App, die Shizukus Berechtigungen nutzen kann

### Anforderungen

- Ein Android-Gerät (Android 10 oder neuer empfohlen)
- Entwickleroptionen aktiviert
- Eine stabile Wi-Fi-Verbindung
- Alle drei Anwendungen installiert (Shizuku, Delta, Tasker)

### Schritt 1 : Shizuku einrichten

#### 1.1 Aktivieren des Entwicklermodus

1. Gehen Sie zu **Einstellungen** → **Über das Telefon**
2. Tippen Sie 7-10 mal auf **Build-Nummer**, bis Sie "Entwicklermodus aktiviert" sehen
3. Kehren Sie zu den Einstellungen zurück und geben Sie **Entwickleroptionen** ein

#### 1.2 Aktivieren des drahtlosen Debuggings

1. Suchen Sie in **Entwickleroptionen** das **drahtlose Debugging (WiFi)**
2. Aktivieren Sie diese Option
3. Eine Benachrichtigung erscheint mit einem Kopplungscode

#### 1.3 Mit Shizuku koppeln

1. Öffnen Sie die **Shizuku**-Anwendung
2. Tippen Sie auf **Kopplung starten**
3. Wählen Sie **Gerät mit Kopplungscode koppeln**
4. Geben Sie den in Entwickleroptionen angezeigten Kopplungscode ein
5. Bestätigen Sie die Kopplung

#### 1.4 Shizuku starten

1. Wählen Sie in der Shizuku-App die entsprechende Startmethode
2. Wählen Sie für nicht gerootete Geräte Drahtloses Debugging
3. Tippen Sie auf **Starten** oder **Shizuku starten**

**Hinweis** : Einmal konfiguriert, kann Shizuku beim Neustart automatisch starten.

### Schritt 2 : Delta installieren und konfigurieren

#### 2.1 Installation

1. Laden Sie die neueste Version von Delta von [GitHub](https://github.com/DeltaCore/Delta-iOS) oder IzzyOnDroid F-Droid herunter
2. Installieren Sie die APK

#### 2.2 Shizuku-Berechtigungen gewähren

1. Öffnen Sie **Delta**
2. Die Anwendung fordert Zugriff auf Shizuku an
3. Tippen Sie in der Benachrichtigung auf **Erlauben**
4. Bestätigen Sie in der Shizuku-App, falls erforderlich

#### 2.3 Emulatoren konfigurieren

1. Konfigurieren Sie in Delta Ihre liebsten Retro-Spiele
2. Laden Sie ROMs aus legalen Quellen herunter
3. Delta verwendet nun Shizuku für erweiterte Funktionen

### Schritt 3 : Tasker mit Shizuku integrieren

#### 3.1 Tasker installieren

1. Laden Sie **Tasker** aus dem Google Play Store herunter und installieren Sie es
2. Sie erhalten einen kostenlosen 7-Tage-Testzeitraum

#### 3.2 Tasker zum Verwenden von Shizuku autorisieren

1. Öffnen Sie **Shizuku**
2. Gehen Sie zu **Einstellungen** (Zahnradsymbol)
3. Suchen Sie nach **Apps autorisieren**
4. Suchen Sie **Tasker** in der Liste und aktivieren Sie es

#### 3.3 Shizuku in Tasker verwenden

**Methode 1 : Integrierte direkte Aktionen**

Tasker verfügt jetzt über integrierte Aktionen, die automatisch mit Shizuku funktionieren :

- **Flugzeugmodus** - Flugzeugmodus aktivieren/deaktivieren
- **WiFi** - WiFi aktivieren/deaktivieren
- **Bluetooth** - Bluetooth aktivieren/deaktivieren
- **WiFi-Hotspot** - WiFi-Freigabe aktivieren/deaktivieren
- **App beenden** - Eine Anwendung schließen
- **Berechtigungen verwalten** - Berechtigungen gewähren/widerrufen
- **App deaktivieren** - Anwendung deaktivieren/aktivieren

Sie erstellen diese Aktionen einfach normal, und Tasker führt sie mit Shizukus Berechtigungen aus.

**Methode 2 : Shell-Befehle ausführen**

1. Erstellen Sie eine neue Aufgabe in Tasker
2. Fügen Sie eine Aktion **Datei** → **Shell-Befehl ausführen** hinzu
3. Verwenden Sie in dem Befehl Ihren gewünschten ADB-Befehl
4. Aktivieren Sie die **Shizuku**-Option, falls verfügbar

### Schritt 4 : Automatisierungsbeispiele

#### Beispiel 1 : WiFi-Freigabe beim Eintreffen bei der Arbeit aktivieren

1. Erstellen Sie ein standortbasiertes Profil für einen bestimmten Ort
2. Verknüpfen Sie eine Aufgabe mit der Aktion **WiFi-Hotspot** auf **ON**
3. Tasker aktiviert automatisch die Freigabe, wenn Sie diesen Ort erreichen

#### Beispiel 2 : Apps schließen, die viel Batterie verbrauchen

1. Erstellen Sie eine Aufgabe mit der Aktion **App beenden**
2. Wählen Sie die Apps aus, die Sie schließen möchten
3. Verknüpfen Sie sie mit einem Profil basierend auf niedrigem Batteriestand

#### Beispiel 3 : Flugzeugmodus zu einer bestimmten Zeit aktivieren

1. Erstellen Sie ein zeitbasiertes Profil für eine bestimmte Stunde
2. Fügen Sie die Aktion **Flugzeugmodus** auf **ON** hinzu
3. Erstellen Sie ein Abbruchprofil, um es später wieder zu aktivieren

### Fehlerbehebung

**Shizuku startet nicht :**
- Überprüfen Sie, ob das drahtlose Debugging aktiviert ist
- Aktivieren Sie das drahtlose Debugging erneut und verbinden Sie sich neu
- Starten Sie Ihr Gerät neu

**Tasker hat keinen Zugriff auf Shizuku :**
- Öffnen Sie Shizuku und überprüfen Sie, ob Tasker autorisiert ist
- Starten Sie beide Anwendungen neu
- Überprüfen Sie, ob Sie Tasker 6.6.2 oder neuer verwenden

**Delta funktioniert nicht :**
- Überprüfen Sie, ob Shizuku ausgeführt wird
- Gewähren Sie Delta erneut Berechtigungen in Shizuku
- Starten Sie Delta neu

---

## 🇮🇹 ITALIANO

### Introduzione

Questo tutorial ti spiegherà come configurare e usare **Shizuku**, **Delta** e **Tasker** insieme per accedere a funzioni avanzate del tuo dispositivo Android senza bisogno di accesso root.

- **Shizuku** : Applicazione che si connette ad ADB (Android Debug Bridge) senza richiedere un computer
- **Delta** : Emulatore di giochi retrò che funziona con Shizuku
- **Tasker** : App di automazione potente che può utilizzare i privilegi di Shizuku

### Requisiti

- Un dispositivo Android (Android 10 o più recente consigliato)
- Opzioni sviluppatore abilitate
- Una connessione Wi-Fi stabile
- Tutte e tre le applicazioni installate (Shizuku, Delta, Tasker)

### Passaggio 1 : Configurazione di Shizuku

#### 1.1 Abilitazione della Modalità Sviluppatore

1. Vai a **Impostazioni** → **Informazioni su**
2. Tocca **Numero build** 7-10 volte fino a vedere "Modalità sviluppatore abilitata"
3. Torna alle impostazioni e accedi a **Opzioni sviluppatore**

#### 1.2 Abilitazione del Debug Wireless

1. In **Opzioni sviluppatore**, trova **Debug wireless (WiFi)**
2. Abilita questa opzione
3. Apparirà una notifica con un codice di abbinamento

#### 1.3 Abbinamento con Shizuku

1. Apri l'applicazione **Shizuku**
2. Tocca **Inizia abbinamento**
3. Seleziona **Abbina dispositivo con codice di abbinamento**
4. Inserisci il codice di abbinamento visualizzato in Opzioni sviluppatore
5. Conferma l'abbinamento

#### 1.4 Avvio di Shizuku

1. Nell'app Shizuku, seleziona il metodo di avvio appropriato
2. Per dispositivi non rooted, scegli Debug wireless
3. Tocca **Avvia** o **Avvia Shizuku**

**Nota** : Una volta configurato Shizuku, può avviarsi automaticamente al riavvio del dispositivo.

### Passaggio 2 : Installazione e Configurazione di Delta

#### 2.1 Installazione

1. Scarica l'ultima versione di Delta da [GitHub](https://github.com/DeltaCore/Delta-iOS) o IzzyOnDroid F-Droid
2. Installa l'APK

#### 2.2 Concessione delle Autorizzazioni Shizuku

1. Apri **Delta**
2. L'applicazione richiederà accesso a Shizuku
3. Tocca **Consenti** nella notifica
4. Conferma nell'app Shizuku se necessario

#### 2.3 Configurazione degli Emulatori

1. In Delta, configura i tuoi giochi retrò preferiti
2. Scarica ROM da fonti legali
3. Delta userà ora Shizuku per funzioni avanzate

### Passaggio 3 : Integrazione di Tasker con Shizuku

#### 3.1 Installazione di Tasker

1. Scarica e installa **Tasker** da Google Play Store
2. Avrai un periodo di prova gratuito di 7 giorni

#### 3.2 Autorizzazione di Tasker per Usare Shizuku

1. Apri **Shizuku**
2. Vai a **Impostazioni** (icona ingranaggio)
3. Cerca **Autorizza app**
4. Trova **Tasker** nell'elenco e abilitalo

#### 3.3 Utilizzo di Shizuku in Tasker

**Metodo 1 : Azioni Dirette Integrate**

Tasker ora ha azioni integrate che funzionano automaticamente con Shizuku :

- **Modalità aereo** - Abilita/disabilita modalità aereo
- **WiFi** - Abilita/disabilita WiFi
- **Bluetooth** - Abilita/disabilita Bluetooth
- **Condivisione WiFi** - Abilita/disabilita condivisione WiFi
- **Termina app** - Chiudi un'applicazione
- **Gestisci autorizzazioni** - Concedi/revoca autorizzazioni
- **Disabilita app** - Disabilita/abilita un'applicazione

Semplicemente crei queste azioni normalmente e Tasker le eseguirà con i privilegi di Shizuku.

**Metodo 2 : Esecuzione di Comandi Shell**

1. Crea una nuova Attività in Tasker
2. Aggiungi un'azione **File** → **Esegui comando Shell**
3. Nel comando, usa il tuo comando ADB desiderato
4. Abilita l'opzione **Shizuku** se disponibile

### Passaggio 4 : Esempi di Automazione

#### Esempio 1 : Abilita Condivisione WiFi all'Arrivo al Lavoro

1. Crea un profilo basato sulla posizione per un luogo specifico
2. Collega un'attività con l'azione **Condivisione WiFi** impostata su **ON**
3. Tasker abiliterà automaticamente la condivisione quando arriverai in quel luogo

#### Esempio 2 : Chiudi App che Consumano Batteria

1. Crea un'attività con l'azione **Termina app**
2. Seleziona le app che vuoi chiudere
3. Collegala a un profilo basato su batteria scarica

#### Esempio 3 : Abilita Modalità Aereo a un'Ora Specifica

1. Crea un profilo basato sul tempo per un'ora specifica
2. Aggiungi l'azione **Modalità aereo** impostata su **ON**
3. Crea un profilo di annullamento per riabilitarla più tardi

### Risoluzione dei Problemi

**Shizuku non si avvia :**
- Verifica che il debug wireless sia abilitato
- Riabilita il debug wireless e ricollega
- Riavvia il dispositivo

**Tasker non ha accesso a Shizuku :**
- Apri Shizuku e verifica che Tasker sia autorizzato
- Riavvia entrambe le applicazioni
- Verifica che stai usando Tasker 6.6.2 o più recente

**Delta non funziona :**
- Verifica che Shizuku sia in esecuzione
- Concedi nuovamente le autorizzazioni a Delta in Shizuku
- Riavvia Delta

---

## 📋 Résumé des Commandes ADB Utiles

Voici quelques commandes ADB courantes que vous pouvez utiliser dans Tasker via Shizuku :

```bash
# Désactiver une application
pm disable com.example.app

# Activer une application
pm enable com.example.app

# Accorder une permission
pm grant com.example.app android.permission.PERMISSION_NAME

# Révoquer une permission
pm revoke com.example.app android.permission.PERMISSION_NAME

# Fermer une application
am force-stop com.example.app

# Activer le mode avion
settings put global airplane_mode_on 1

# Désactiver le mode avion
settings put global airplane_mode_on 0

# Activer le WiFi
svc wifi enable

# Désactiver le WiFi
svc wifi disable

# Activer Bluetooth
svc bluetooth enable

# Désactiver Bluetooth
svc bluetooth disable
```

---

## 🔐 Considérations de Sécurité

- **Shizuku est sûr** : Il n'accorde que les permissions que vous lui donnez explicitement
- **N'autorisez que les apps de confiance** : N'accordez l'accès à Shizuku qu'aux applications que vous trouvez
- **Gardez Shizuku à jour** : Mettez à jour régulièrement l'application
- **Utilisez des sources fiables** : Téléchargez les applications depuis les stores officiels ou des sources de confiance

---

**Dernière mise à jour** : Décembre 2025
