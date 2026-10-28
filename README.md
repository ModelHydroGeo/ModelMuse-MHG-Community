# ModelMuse-MHG-Community
Free bilingual (English/French) edition of USGS ModelMuse 5.4, featuring French documentation and a modernized user interface.

ENGLISH
-------

1. ABOUT THIS EDITION

ModelMuse MHG Community 2026a is a free, independently adapted edition of
ModelMuse 5.4, the groundwater-model graphical user interface developed by
the U.S. Geological Survey (USGS).

ModelHydroGeo contributes an English/French user interface, a French-language
help file, and appearance options. This edition is intended to make the
original application more accessible to French-speaking users.

IMPORTANT VERSION DISTINCTION
- MHG edition/version: ModelMuse MHG Community 2026a.
- Original software baseline: USGS ModelMuse 5.4.
- The label "2026a" identifies the first MHG Community release in 2026;
  "2026b", "2026c", etc. may identify subsequent releases that year.
  It is NOT an official USGS version number.

2. SYSTEM AND DISTRIBUTION

- Platform: 64-bit Windows.
- Tested by ModelHydroGeo on Windows 11 (64-bit).
- Delivery: ZIP archive; this is not a Windows installer.
- No Delphi development environment is needed to run the packaged application.
- The ZIP includes the resources required for the bilingual interface and
  the light/dark VCL styles.

3. INSTALLATION AND STARTUP

1) Download the official ModelHydroGeo Community ZIP archive.
2) Extract the entire archive into a folder of your choice.
3) Keep the extracted folder structure intact, including the bin, Help,
   and styles subdirectories.
4) Start bin\ModelMuse.exe from the extracted distribution.

Do not run ModelMuse.exe directly from inside the ZIP archive.
No modifications to the Windows Registry are required by the ZIP extraction
itself. Application preferences may be saved in the current user profile.

4. LANGUAGE, HELP AND APPEARANCE

- Choose English or French using the application's language settings from
  the menu Customize > Interface language.
  Restart ModelMuse when prompted for the change to take effect.
- The help system follows the active language:
    English: bin\Help\ModelMuse.chm
    French:  bin\Help\ModelMuse_fr.chm
  If the French help file is unavailable, ModelMuse falls back to English help.
- Appearance modes include Classic, Light, Dark and System. The selected
  appearance is applied on startup; restart when requested.
- Preserve the bin\styles directory. It contains the VCL style files
  needed for the optional light and dark appearances.

Some illustrations in the translated help still show the original English
interface. The written French documentation and navigation are translated;
illustrations may be updated in later releases.

5. SCIENTIFIC SCOPE

This edition is primarily a language and user-interface adaptation of USGS
ModelMuse 5.4. It does not introduce a new groundwater simulation engine.
Users remain responsible for reviewing their model assumptions, inputs,
solver settings, numerical convergence and simulation results.

Professional extensions under separate ModelHydroGeo development (such as
VTK-based visualization and a CPython/Python API) are NOT part of this
Community release.

6. ORIGINAL SOFTWARE, CREDITS AND LICENSING

ModelMuse was developed by the U.S. Geological Survey (USGS). ModelHydroGeo
provides this independent Community adaptation and the French localization.
ModelHydroGeo is not affiliated with the USGS, and this adaptation is not an
official USGS release or endorsement.

For information on the original software, consult the bundled
readme_usgs.txt and the official USGS ModelMuse documentation.
Third-party components and assets remain subject to their own applicable
licenses, notices and redistribution conditions.

7. RELEASE HISTORY AND FEEDBACK

See release_notes.txt for dated release information and changes.

Website: https://modelhydrogeo.com/
Contact: contact@modelhydrogeo.com
Suggested email subject for French localization feedback: ModelMuse Fr

Please report the MHG version (2026a), Windows version, language, and steps
to reproduce any issue. Do not send confidential model files without
removing sensitive information.

This software is supplied without a ModelHydroGeo warranty of suitability
for any particular scientific, engineering or regulatory use.


FRANÇAIS
--------

1. PRÉSENTATION DE CETTE ÉDITION

ModelMuse MHG Community 2026a est une édition gratuite et adaptée de façon
indépendante de ModelMuse 5.4, l'interface graphique de modélisation des eaux
souterraines développée par l'U.S. Geological Survey (USGS).

ModelHydroGeo apporte une interface bilingue français/anglais, une aide en
français et des options d'apparence. Cette édition vise à faciliter l'accès
au logiciel d'origine pour les utilisateurs francophones.

DISTINCTION IMPORTANTE ENTRE LES VERSIONS
- Édition/version MHG : ModelMuse MHG Community 2026a.
- Version du logiciel d'origine : ModelMuse 5.4 de l'USGS.
- « 2026a » désigne la première édition MHG Community publiée en 2026 ;
  « 2026b », « 2026c », etc. pourront désigner les suivantes.
  Il ne s'agit PAS d'un numéro de version officiel de l'USGS.

2. SYSTÈME ET DISTRIBUTION

- Plateforme : Windows 64 bits.
- Testé par ModelHydroGeo sous Windows 11 (64 bits).
- Distribution : archive ZIP, sans programme d'installation automatique.
- L'exécution ne nécessite pas l'installation de Delphi.
- L'archive inclut les ressources nécessaires à l'interface bilingue et
  aux styles VCL clair/sombre.

3. INSTALLATION ET DÉMARRAGE

1) Télécharger l'archive ZIP Community officielle de ModelHydroGeo.
2) Extraire toute l'archive dans un dossier de votre choix.
3) Conserver l'arborescence extraite, notamment les sous-dossiers bin, Help
   et styles.
4) Lancer bin\ModelMuse.exe depuis le dossier extrait.

Ne pas lancer ModelMuse.exe directement depuis l'intérieur de l'archive ZIP.
L'extraction de l'archive ne nécessite pas, en elle-même, de modification du
Registre Windows. Les préférences de l'application peuvent être enregistrées
dans le profil de l'utilisateur courant.

4. LANGUE, AIDE ET APPARENCE

- Choisir le français ou l'anglais dans les préférences linguistiques du
  logiciel depuis le menu Personnaliser > Langue de l'interface. 
  Redémarrer ModelMuse si cela est demandé.
- L'aide suit la langue active :
    Anglais : bin\Help\ModelMuse.chm
    Français : bin\Help\ModelMuse_fr.chm
  Si le fichier d'aide français est absent, l'aide anglaise est utilisée.
- Les modes d'apparence comprennent Classique, Clair, Sombre et Système.
  Le mode choisi est appliqué au démarrage ; redémarrer si nécessaire.
- Conserver le dossier bin\styles : il contient les styles VCL nécessaires
  aux apparences facultatives claire et sombre.

Certaines illustrations de l'aide française présentent encore l'interface
d'origine en anglais. Les textes et la navigation sont traduits ; les
illustrations pourront être actualisées dans des versions ultérieures.

5. PÉRIMÈTRE SCIENTIFIQUE

Cette édition est avant tout une adaptation linguistique et ergonomique de
ModelMuse 5.4 de l'USGS. Elle n'introduit pas de nouveau moteur de simulation
hydrogéologique. Il appartient à l'utilisateur de contrôler les hypothèses,
les données, les paramètres des solveurs, la convergence numérique et les
résultats de ses modèles.

Les extensions professionnelles développées séparément par ModelHydroGeo
(notamment la visualisation VTK et la console/API CPython-Python) ne font PAS
partie de cette édition Community.

6. LOGICIEL D'ORIGINE, CRÉDITS ET LICENCES

ModelMuse est développé par l'U.S. Geological Survey (USGS). ModelHydroGeo
propose cette adaptation Community indépendante et sa localisation française.
ModelHydroGeo n'est pas affilié à l'USGS ; cette adaptation ne constitue pas
une version officielle ni approuvée par l'USGS.

Pour les informations concernant le logiciel d'origine, consulter le fichier
readme_usgs.txt fourni et la documentation officielle de ModelMuse (USGS).
Les composants et ressources tiers restent soumis à leurs licences, mentions
et conditions de redistribution respectives.

7. HISTORIQUE DES VERSIONS ET RETOURS UTILISATEURS

Consulter release_notes.txt pour les dates de sortie et les changements.

Site web : https://modelhydrogeo.com/
Contact : contact@modelhydrogeo.com
Objet conseillé pour les remarques sur la traduction : ModelMuse Fr

Merci de préciser la version MHG (2026a), la version de Windows, la langue
utilisée et les étapes permettant de reproduire un problème. Ne pas envoyer
de modèles confidentiels sans retrait préalable des données sensibles.

Ce logiciel est fourni sans garantie de ModelHydroGeo quant à son adéquation
à un usage scientifique, technique ou réglementaire particulier.



