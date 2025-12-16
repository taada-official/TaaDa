## 🇬🇧 ENGLISH

### Introduction

This tutorial will explain how to set up and use **Shizuku**, **Delta**, and **TaaDa** together to enable your Android device's hotspot without requiring root access.

- **Shizuku**: An app that connects to ADB (Android Debug Bridge) without needing a computer  
- **Delta**: An app that enables and disables the hotspot and works with Shizuku

### Prerequisites

- An Android 16 device  
- Developer options enabled  
- A stable Wi-Fi connection  
- All three apps installed (Shizuku, Delta, TaaDa)

### Step 1: Setting up Shizuku

#### 1.1 Installation

1. Download the latest version of Shizuku from [https://github.com/RikkaApps/Shizuku/releases](https://github.com/RikkaApps/Shizuku/releases) or F-Droid  
2. Install the APK

#### 1.2 Enabling Developer Mode

1. Go to **Settings** → **About phone**  
2. Tap **Build number** 7–10 times until you see “Developer mode activated”  
3. Go back to **Settings** and select **Developer options**

#### 1.3 Enabling Wireless Debugging

1. In **Developer options**, find **Wireless debugging (WiFi)**  
2. Enable this option  
3. A notification will appear with a pairing code

#### 1.4 Pairing with Shizuku

1. Open the **Shizuku** app  
2. Tap **Start pairing**  
3. Select **Pair device with pairing code**  
4. Enter the pairing code shown in Developer options  
5. Confirm the pairing

#### 1.5 Starting Shizuku

1. In the Shizuku app, select the appropriate startup method  
2. For non-rooted devices, choose wireless debugging  
3. Tap **Start** or **Launch Shizuku**

**Note:** Once configured, Shizuku can automatically start when the device reboots.

### Step 2: Installing and Setting Up Delta

#### 2.1 Installation

1. Download the latest version of Delta from [https://github.com/supershadoe/delta/releases](https://github.com/supershadoe/delta/releases) or IzzyOnDroid F-Droid  
2. Install the APK

#### 2.2 Granting Permissions to Shizuku

1. Open **Delta**  
2. The app will request access to Shizuku  
3. Tap **Allow** in the notification  
4. Confirm in the Shizuku app if necessary

#### 2.3 Configuring Delta

1. In Delta, configure your hotspot  
2. In Advanced Settings, enable compatibility with “Tasket”  
3. Delta will now use Shizuku to turn the hotspot on or off.

### Step 3: Using with TaaDa

1. Make sure you’ve selected your vehicle’s Bluetooth name in the Settings tab.  
2. That’s it — TaaDa takes care of the rest :-)

### Troubleshooting

**Shizuku won’t start:**  
- Check that wireless debugging is enabled  
- Reactivate wireless debugging and reconnect  
- Grant specific permissions for custom Android skins like MIUI, HyperOS, or ColorOS if needed  
- Restart the device  

**Delta isn’t working:**  
- Check that Shizuku is running  
- Reauthorize Delta permissions in Shizuku  
- Grant specific permissions for MIUI, HyperOS, or ColorOS if needed  
- Restart Delta  

### Battery optimization
- Disable battery optimization for Delta and Shizuku

---

## 🇫🇷 FRANÇAIS

### Introduction

Ce tutoriel vous expliquera comment configurer et utiliser **Shizuku**, **Delta** et **TaaDa** ensemble pour activer le hotspot de votre appareil Android sans avoir besoin d'accès root.

- **Shizuku** : Application qui se connecte à ADB (Android Debug Bridge) sans nécessiter un ordinateur
- **Delta** : Application qui active et désactive le hotspot et qui fonctionne avec Shizuku

### Prérequis

- Un appareil Android 16
- Options de développeur activées
- Une connexion Wi-Fi stable
- Les trois applications installées (Shizuku, Delta, TaaDa)

### Étape 1 : Configuration de Shizuku

#### 1.1 Installation

1. Téléchargez la dernière version de Shizuku depuis [https://github.com/RikkaApps/Shizuku/releases](https://github.com/RikkaApps/Shizuku/releases) ou F-Droid
2. Installez l'APK

#### 1.2 Activation du Mode Développeur

1. Allez dans **Paramètres** → **À propos du téléphone**
2. Appuyez 7-10 fois sur **Numéro de version** jusqu'à voir "Mode développeur activé"
3. Retournez aux paramètres et sélectionnez **Options de développement**

#### 1.3 Activation du Débogage Sans Fil

1. Dans **Options de développement**, cherchez **Débogage sans fil (WiFi)**
2. Activez cette option
3. Une notification apparaîtra avec un code d'appairage

#### 1.4 Appairage avec Shizuku

1. Ouvrez l'application **Shizuku**
2. Appuyez sur **Commencer l'appairage**
3. Sélectionnez **Coupler l'appareil avec le code d'appairage**
4. Entrez le code d'appairage affiché dans les options de développement
5. Confirmez l'appairage

#### 1.5 Démarrage de Shizuku

1. Dans l'application Shizuku, sélectionnez la méthode de démarrage appropriée
2. Pour les appareils non rootés, choisissez le débogage sans fil
3. Appuyez sur **Démarrer** ou **Lancer Shizuku**

**Note** : Une fois Shizuku est configuré, il peut démarrer automatiquement au redémarrage de l'appareil.

### Étape 2 : Installation et Configuration de Delta

#### 2.1 Installation

1. Téléchargez la dernière version de Delta depuis [https://github.com/supershadoe/delta/releases](https://github.com/supershadoe/delta/releases) ou IzzyOnDroid F-Droid
2. Installez l'APK

#### 2.2 Octroi des Permissions à Shizuku

1. Ouvrez **Delta**
2. L'application demandera l'accès à Shizuku
3. Tapez sur **Autoriser** dans la notification
4. Confirmez dans l'application Shizuku si nécessaire

#### 2.3 Configuration de Delta

1. Dans Delta, configurez votre hotspot
2. Dans les paramètres avancés, activer la compatibilité avec "Tasket"
3. Delta utilisera désormais Shizuku pour activer ou désactiver le hotspot.

### Étape 3 : Utilisation avec Taada

1. Assurez-vous d'avoir sélectionné le nom bluetooth de votre véhicule dans l'onglet réglage.
2. Rien d'autre, TaaDa s'occupe du reste :-)

### Dépannage

**Shizuku ne démarre pas :**
- Vérifiez que le débogage sans fil est activé
- Réactivez le débogage sans fil et reconnectez-vous
- Accorder les permissions spécifiques aux surcouches constructions du type Miui, HyperOs, ColorOs si besoin
- Redémarrez l'appareil

**Delta ne fonctionne pas :**
- Vérifiez que Shizuku est en cours d'exécution
- Accordez à nouveau les permissions à Delta dans Shizuku
- Accorder les permissions spécifiques aux surcouches constructions du type Miui, HyperOs, ColorOs si besoin
- Redémarrez Delta

### Optimisations batterie
- Désactiver les optimisations batterie pour Delta et Shizuku 

---
