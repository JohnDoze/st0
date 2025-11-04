ST0 - Structure Template Zero
<div align="center">
Afficher l'image
🚀 Générateur Universel de Structures de Projets
Créez des projets professionnels en quelques secondes
Afficher l'image
Afficher l'image
Afficher l'image
Afficher l'image
Afficher l'image
Afficher l'image
Afficher l'image
Afficher l'image
🌐 Site Web • 📖 Documentation • 💬 Discord • 🐦 Twitter
</div>

📑 Table des matières complète
<details>
<summary>Cliquez pour déplier</summary>

Introduction

Qu'est-ce que ST0 ?
Pourquoi utiliser ST0 ?
Cas d'usage


Fonctionnalités

Interface Graphique
Interface CLI
Moteur de Templates
Système de Plugins


Installation

Installation rapide
Installation manuelle
Installation développeur
Vérification


Démarrage rapide

Premier projet
Mode interactif
Exemples pratiques


Guide utilisateur

Interface GUI
Interface CLI
Gestion des templates


Templates disponibles

Python
JavaScript/TypeScript
Autres langages
DevOps


Créer des templates

Structure
Variables
Templates avancés


Architecture
API et Intégrations
Contribution
Support
FAQ
Roadmap
Licence

</details>

🎯 Introduction
Qu'est-ce que ST0 ?
ST0 (Structure Template Zero) est un générateur universel et intelligent de structures de projets qui révolutionne la façon dont vous démarrez vos développements. En quelques secondes, créez des projets complets, structurés et prêts à l'emploi dans n'importe quel langage ou framework.
Pourquoi utiliser ST0 ?
<table>
<tr>
<td width="33%">
⚡ Vitesse
Créez un projet complet en moins de 15 secondes au lieu de plusieurs heures de configuration manuelle.
</td>
<td width="33%">
🎨 Qualité
Templates suivant les best practices et conventions de chaque langage/framework.
</td>
<td width="33%">
🔧 Flexibilité
Support de 50+ frameworks et personnalisation infinie via variables et conditions.
</td>
</tr>
<tr>
<td>
💎 Consistance
Maintenez une structure cohérente à travers tous vos projets et votre équipe.
</td>
<td>
🚀 Productivité
Concentrez-vous sur la logique métier, pas sur la configuration initiale.
</td>
<td>
🌐 Universel
Un seul outil pour tous vos langages : Python, JS, Go, Rust, Java...
</td>
</tr>
</table>
Cas d'usage

🏢 Entreprises : Standardiser les projets à travers les équipes
👨‍💻 Développeurs : Démarrer rapidement de nouveaux projets
🎓 Étudiants : Apprendre les bonnes pratiques
🚀 Startups : Prototyper rapidement des idées
🔬 Chercheurs : Créer des projets reproductibles
📚 Formateurs : Générer des squelettes de projets pour cours


✨ Fonctionnalités
Interface Graphique (GUI)
<details>
<summary><b>🖥️ Interface moderne et intuitive (Cliquez pour voir les détails)</b></summary>
Vue d'ensemble
Afficher l'image
Fonctionnalités principales
🎨 Design moderne

Interface basée sur CustomTkinter avec thèmes sombre/clair
Animations fluides et transitions élégantes
Responsive design adapté à toutes les résolutions
Support multi-écrans

📋 Création de projets
┌─────────────────────────────────────────────────────────┐
│ 🆕 Nouveau Projet                                       │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  📝 Configuration                                       │
│  ├─ Nom du projet: [__________________] ✓               │
│  ├─ Auteur: [__________________] ✓                      │
│  ├─ Email: [__________________] ✓                       │
│  ├─ Description: [___________________________]          │
│  ├─ Version: [0.1.0] Licence: [MIT ▼]                  │
│  └─ Langage: [Python 3.14 ▼]                           │
│                                                         │
│  🎯 Sélection du template                               │
│  ┌─────────────────────────────────────────────────┐   │
│  │ 🔍 [Rechercher templates..................] 🔎  │   │
│  │ [Catégorie: Web ▼] [Tags: #fastapi #rest]      │   │
│  │                                                 │   │
│  │ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐              │   │
│  │ │ 🚀  │ │ 🐍  │ │ ⚛️  │ │ 💚  │              │   │
│  │ │Fast │ │Djngo│ │React│ │Vue3 │              │   │
│  │ │ API │ │ REST│ │+Vite│ │+Vite│              │   │
│  │ └─────┘ └─────┘ └─────┘ └─────┘              │   │
│  └─────────────────────────────────────────────────┘   │
│                                                         │
│  [👁️ Prévisualiser]  [🚀 GÉNÉRER LE PROJET]          │
└─────────────────────────────────────────────────────────┘
🎭 Drag & Drop

Glissez-déposez vos fichiers de templates (.yaml, .json, .toml)
Import direct depuis URL
Détection automatique du format

👁️ Prévisualisation en temps réel

Visualisation de l'arborescence du projet avant génération
Aperçu du contenu des fichiers avec coloration syntaxique
Estimation de la taille et du temps de génération
Liste des variables utilisées

📊 Tableau de bord

Historique des projets générés
Statistiques d'utilisation
Templates favoris
Projets récents avec quick-access

⚙️ Paramètres avancés

Configuration de l'éditeur de code préféré
Chemins par défaut
Raccourcis clavier personnalisables
Thèmes personnalisés

</details>
Interface Ligne de Commande (CLI)
<details>
<summary><b>⌨️ CLI puissant et complet (Cliquez pour voir les détails)</b></summary>
Commandes principales
bash# ════════════════════════════════════════════════════════
# CRÉATION DE PROJETS
# ════════════════════════════════════════════════════════

# Mode interactif (recommandé pour débuter)
st0 new
st0 new --interactive

# Création rapide avec nom
st0 new myproject

# Création avec template spécifique
st0 new myproject --template fastapi_full

# Création complète avec toutes les options
st0 new my-awesome-api \
    --template fastapi_full \
    --author "John Doe" \
    --email "john@example.com" \
    --description "My awesome REST API" \
    --version "0.1.0" \
    --licence MIT \
    --output ~/Projects \
    --python 3.14 \
    --database postgresql \
    --with-docker \
    --with-redis \
    --with-celery \
    --with-tests \
    --ci-cd github_actions \
    --init-git \
    --create-venv \
    --install-deps \
    --open-vscode

# Depuis un fichier de configuration
st0 new --from-file project-config.json
st0 new --from-file project-config.yaml

# Mode non-interactif (CI/CD)
st0 new myproject \
    --template fastapi_full \
    --no-interactive \
    --yes  # Accepte tous les prompts


# ════════════════════════════════════════════════════════
# GESTION DES TEMPLATES
# ════════════════════════════════════════════════════════

# Lister tous les templates
st0 template list
st0 template list --format table
st0 template list --format json
st0 template list --sort popularity
st0 template list --sort name

# Filtrer les templates
st0 template list --category web
st0 template list --language python
st0 template list --tag fastapi
st0 template list --official-only
st0 template list --custom-only

# Rechercher un template
st0 template search "fastapi api rest"
st0 template search "react typescript" --category frontend

# Informations détaillées
st0 template info fastapi_full
st0 template info fastapi_full --show-variables
st0 template info fastapi_full --show-structure

# Créer un nouveau template
st0 template create
st0 template create --name my_template
st0 template create --from-existing fastapi_full
st0 template create --from-project ./my-project

# Éditer un template
st0 template edit fastapi_full
st0 template edit my_custom_template --editor vscode

# Valider un template
st0 template validate my_template.yaml
st0 template validate my_template.yaml --strict
st0 template validate --all

# Dupliquer un template
st0 template duplicate fastapi_full my_custom_fastapi
st0 template duplicate --with-modifications

# Supprimer un template
st0 template delete my_template
st0 template delete my_template --force

# Importer un template
st0 template import template.yaml
st0 template import --url https://example.com/template.yaml
st0 template import --from-github user/repo/path/template.yaml
st0 template import template.yaml --name my_template

# Exporter un template
st0 template export fastapi_full
st0 template export fastapi_full --output ./exports
st0 template export --all --output ./backup
st0 template export fastapi_full --format json


# ════════════════════════════════════════════════════════
# MARKETPLACE
# ════════════════════════════════════════════════════════

# Lister les templates du marketplace
st0 marketplace list
st0 marketplace list --category web
st0 marketplace list --trending
st0 marketplace list --new

# Rechercher dans le marketplace
st0 marketplace search "fastapi"
st0 marketplace search "react typescript"

# Installer depuis le marketplace
st0 marketplace install fastapi_pro
st0 marketplace install fastapi_pro --version 2.5.0

# Mettre à jour un template
st0 marketplace update fastapi_pro
st0 marketplace update --all

# Désinstaller
st0 marketplace uninstall fastapi_pro

# Publier son propre template
st0 marketplace publish my_template
st0 marketplace publish my_template --public
st0 marketplace publish my_template --premium

# Synchroniser
st0 marketplace sync


# ════════════════════════════════════════════════════════
# HISTORIQUE
# ════════════════════════════════════════════════════════

# Voir l'historique
st0 history
st0 history --limit 10
st0 history --today
st0 history --week
st0 history --month

# Filtrer l'historique
st0 history --filter "fastapi"
st0 history --template fastapi_full
st0 history --author "John Doe"

# Détails d'un projet
st0 history show <project_id>
st0 history show <project_id> --open

# Régénérer un projet
st0 history regenerate <project_id>
st0 history regenerate <project_id> --update-deps

# Nettoyer l'historique
st0 history clean --older-than 30d
st0 history clean --all


# ════════════════════════════════════════════════════════
# CONFIGURATION
# ════════════════════════════════════════════════════════

# Configuration interactive
st0 config
st0 init

# Lire la configuration
st0 config list
st0 config get default_author
st0 config get --all

# Définir une valeur
st0 config set default_author "John Doe"
st0 config set default_email "john@example.com"
st0 config set default_output_path "~/Projects"
st0 config set default_python_version "3.14"
st0 config set editor "code"

# Réinitialiser
st0 config reset
st0 config reset default_author
st0 config reset --all

# Exporter/Importer la config
st0 config export config.json
st0 config import config.json


# ════════════════════════════════════════════════════════
# PLUGINS
# ════════════════════════════════════════════════════════

# Lister les plugins
st0 plugin list
st0 plugin list --enabled-only
st0 plugin list --disabled-only

# Installer un plugin
st0 plugin install git_plugin
st0 plugin install --from-file plugin.py
st0 plugin install --from-url https://example.com/plugin.py

# Activer/Désactiver
st0 plugin enable git_plugin
st0 plugin disable git_plugin

# Informations
st0 plugin info git_plugin

# Désinstaller
st0 plugin uninstall git_plugin


# ════════════════════════════════════════════════════════
# UTILITAIRES
# ════════════════════════════════════════════════════════

# Version
st0 --version
st0 version

# Aide
st0 --help
st0 new --help
st0 template --help

# Mise à jour
st0 update
st0 update --check
st0 update --pre-release

# Diagnostics
st0 doctor
st0 doctor --fix
st0 doctor --verbose

# Statistiques
st0 stats
st0 stats --global
st0 stats --templates

# Nettoyer le cache
st0 clean
st0 clean --cache
st0 clean --logs
st0 clean --all

# Interface graphique depuis CLI
st0 gui
st0

# Tutoriel interactif
st0 tutorial
st0 tutorial --advanced

# Générer un rapport
st0 report
st0 report --output report.html
Options globales
bash# Options disponibles pour toutes les commandes
--verbose, -v       # Mode verbeux
--quiet, -q         # Mode silencieux
--debug             # Mode debug avec traces détaillées
--no-color          # Désactive les couleurs
--output, -o        # Spécifie le dossier de sortie
--force, -f         # Force l'opération sans confirmation
--dry-run           # Simule l'opération sans l'exécuter
--log-file          # Fichier de log personnalisé
--config            # Fichier de config personnalisé
Exemples d'utilisation avancée
bash# Génération batch de plusieurs projets
for lang in python javascript go; do
  st0 new "api-$lang" --template "${lang}_api" --no-interactive
done

# Pipeline CI/CD
st0 new myproject \
    --template fastapi_full \
    --no-interactive \
    --output /tmp/build \
    --with-docker \
    --ci-cd gitlab_ci \
    --log-file build.log

# Génération avec variables d'environnement
export ST0_DEFAULT_AUTHOR="John Doe"
export ST0_DEFAULT_EMAIL="john@example.com"
st0 new myproject --template fastapi_full

# Utilisation avec jq pour JSON
st0 template list --format json | jq '.[] | select(.category == "web")'

# Création de workspace multi-projets
st0 workspace create my-workspace
cd my-workspace
st0 new frontend --template react_vite
st0 new backend --template fastapi_full
st0 new mobile --template react_native
st0 workspace init  # Génère docker-compose.yml pour tous
</details>
Moteur de Templates
<details>
<summary><b>🔧 Système de templating puissant (Cliquez pour voir les détails)</b></summary>
Formats supportés
FormatExtensionUtilisationMoteurYAML.yaml, .ymlFormat principal (recommandé)PyYAMLJSON.jsonConfiguration simplejsonTOML.tomlAlternative modernetomlTXT.txtTemplates basiques-Markdown.mdDocumentation-XML.xmlStructures complexesxml
Moteurs de templating
🎨 Jinja2 (Principal)
jinja{# Commentaire #}

{# Variables #}
{{ PROJECT_NAME }}
{{ AUTHOR | upper }}
{{ VERSION | default("1.0.0") }}

{# Conditions #}
{% if USE_DOCKER %}
Docker support enabled
{% endif %}

{% if DATABASE_TYPE == 'postgresql' %}
Using PostgreSQL
{% elif DATABASE_TYPE == 'mysql' %}
Using MySQL
{% else %}
Using SQLite
{% endif %}

{# Boucles #}
{% for dep in DEPENDENCIES %}
- {{ dep }}
{% endfor %}

{# Macros #}
{% macro render_license(type) %}
This project is licensed under {{ type }}
{% endmacro %}

{{ render_license(LICENCE) }}

{# Includes #}
{% include 'header.txt' %}

{# Filtres personnalisés #}
{{ PROJECT_NAME | to_snake_case }}
{{ PROJECT_NAME | to_camel_case }}
{{ PROJECT_NAME | to_pascal_case }}
{{ PROJECT_NAME | to_kebab_case }}
🔥 Mako
mako## Commentaire

## Variables
${PROJECT_NAME}
${AUTHOR.upper()}

## Conditions
% if USE_DOCKER:
Docker support enabled
% endif

## Boucles
% for dep in DEPENDENCIES:
- ${dep}
% endfor

## Fonctions
<%def name="render_license(type)">
Licensed under ${type}
</%def>

${render_license(LICENCE)}
👨‍🎤 Mustache
mustache{{! Commentaire }}

{{! Variables }}
{{PROJECT_NAME}}
{{AUTHOR}}

{{! Conditions }}
{{#USE_DOCKER}}
Docker support enabled
{{/USE_DOCKER}}

{{! Boucles }}
{{#DEPENDENCIES}}
- {{.}}
{{/DEPENDENCIES}}
🎭 Handlebars
handlebars{{! Commentaire }}

{{! Variables }}
{{PROJECT_NAME}}
{{AUTHOR}}

{{! Conditions }}
{{#if USE_DOCKER}}
Docker support enabled
{{/if}}

{{! Boucles }}
{{#each DEPENDENCIES}}
- {{this}}
{{/each}}

{{! Helpers personnalisés }}
{{toSnakeCase PROJECT_NAME}}
Variables système
python# Variables automatiquement disponibles
CURRENT_YEAR        # 2025
CURRENT_DATE        # 2025-01-15
CURRENT_TIME        # 14:30:45
CURRENT_DATETIME    # 2025-01-15 14:30:45
USERNAME            # john
HOSTNAME            # laptop-john
OS                  # linux / windows / darwin
HOME_DIR            # /home/john
PYTHON_VERSION      # 3.14.1

# Variables calculées automatiquement
PROJECT_NAME_SNAKE    # my_awesome_api
PROJECT_NAME_KEBAB    # my-awesome-api
PROJECT_NAME_CAMEL    # myAwesomeApi
PROJECT_NAME_PASCAL   # MyAwesomeApi
PROJECT_NAME_UPPER    # MY_AWESOME_API
PROJECT_NAME_LOWER    # my awesome api
Fonctions disponibles
python# Conversions de casse
to_snake_case(text)      # my_awesome_api
to_kebab_case(text)      # my-awesome-api
to_camel_case(text)      # myAwesomeApi
to_pascal_case(text)     # MyAwesomeApi
to_upper_case(text)      # MY AWESOME API
to_lower_case(text)      # my awesome api
to_title_case(text)      # My Awesome Api

# Manipulation de strings
slugify(text)            # my-awesome-api-123
truncate(text, length)   # Tronque à N caractères
wrap(text, width)        # Word wrap
indent(text, spaces)     # Indentation
capitalize(text)         # Capitalise
upper(text)              # UPPERCASE
lower(text)              # lowercase

# Dates et heures
get_current_year()       # 2025
get_current_date()       # 2025-01-15
format_date(date, fmt)   # Format personnalisé
add_days(date, n)        # Ajoute N jours
subtract_days(date, n)   # Retire N jours

# Fichiers et chemins
basename(path)           # filename.txt
dirname(path)            # /path/to
join_path(p1, p2)        # /path/to/file
normalize_path(path)     # Normalise le chemin
absolute_path(path)      # Chemin absolu

# UUID et hashes
generate_uuid()          # uuid4
generate_uuid5(name)     # uuid5 depuis nom
hash_md5(text)           # MD5 hash
hash_sha256(text)        # SHA256 hash

# Utilitaires
random_string(length)    # Chaîne aléatoire
random_int(min, max)     # Entier aléatoire
default(value, default)  # Valeur par défaut si None
Conditions avancées
yaml# Opérateurs supportés
==  # Égalité
!=  # Différence
>   # Supérieur
<   # Inférieur
>=  # Supérieur ou égal
<=  # Inférieur ou égal
in  # Appartenance
not in  # Non-appartenance
and # ET logique
or  # OU logique
not # NON logique

# Exemples
condition: "PYTHON_VERSION >= '3.10'"
condition: "DATABASE_TYPE in ['postgresql', 'mysql']"
condition: "USE_DOCKER and USE_REDIS"
condition: "not USE_SQLITE"
condition: "(USE_DOCKER or USE_VENV) and INCLUDE_TESTS"
</details>
Système de Plugins
<details>
<summary><b>🔌 Architecture de plugins extensible (Cliquez pour voir les détails)</b></summary>
Plugins intégrés
Git Plugin
python# Initialisation automatique de Git
# Création de commits initiaux
# Gestion des .gitignore
# Hooks Git personnalisés
Docker Plugin
python# Génération Dockerfile optimisé
# docker-compose.yml multi-services
# .dockerignore automatique
# Health checks
Prettier/Linter Plugin
python# Formatage automatique du code
# Configuration ESLint/Prettier
# Pre-commit hooks
# CI/CD linting
Créer un plugin
python# plugins/my_plugin.py
from st0.plugins import PluginInterface, hook

class MyPlugin(PluginInterface):
    """
    Mon plugin personnalisé
    """
    
    name = "my_plugin"
    version = "1.0.0"
    description = "Mon super plugin"
    author = "John Doe"
    
    def __init__(self):
        super().__init__()
        self.config = {}
    
    @hook("before_project_creation")
    def before_creation(self, context):
        """Exécuté avant la création du projet"""
        print(f"Création de {context.project_name}")
        return context
    
    @hook("after_project_creation")
    def after_creation(self, context):
        """Exécuté après la création du projet"""
        print(f"Projet {context.project_name} créé!")
        
        # Exemple : Initialiser Git
        if context.init_git:
            self.init_git_repo(context.project_path)
        
        return context
    
    @hook("after_file_created")
    def after_file(self, file_path, context):
        """Exécuté après chaque fichier créé"""
        print(f"Fichier créé : {file_path}")
        return file_path
    
    @hook("before_file_creation")
    def before_file(self, file_path, content, context):
        """Exécuté avant chaque fichier"""
        # Modifier le contenu si nécessaire
        return content
    
    def init_git_repo(self, path):
        """Initialise un dépôt Git"""
        import subprocess
        subprocess.run(["git", "init"], cwd=path)
        subprocess.run(["git", "add", "."], cwd=path)
        subprocess.run(["git", "commit", "-m", "Initial commit"], cwd=path)
Hooks disponibles
python# Lifecycle hooks
@hook("before_project_creation")
@hook("after_project_creation")
@hook("before_folder_creation")
@hook("after_folder_creation")
@hook("before_file_creation")
@hook("after_file_creation")
@hook("on_project_error")
@hook("on_project_success")

# Template hooks
@hook("before_template_parsing")
@hook("after_template_parsing")
@hook("before_variable_processing")
@hook("after_variable_processing")

# Custom hooks
@hook("custom:my_event")
API du plugin
pythonclass PluginInterface:
    """Interface de base pour les plugins"""
    
    # Métadonnées
    name: str
    version: str
    description: str
    author: str
    
    # Méthodes à implémenter
    def activate(self):
        """Activé quand le plugin est chargé"""
        pass
    
    def deactivate(self):
        """Activé quand le plugin est déchargé"""
        pass
    
    # Helpers fournis
    def log(self, message, level="info"):
        """Log un message"""
        pass
    
    def get_config(self, key, default=None):
        """Récupère une config"""
        pass
    
    def set_config(self, key, value):
        """Définit une config"""
        pass
    
    def emit_event(self, event_name, data):
        """Émet un événement custom"""
        pass
    
    def run_command(self, command, cwd=None):
        """Exécute une commande shell"""
        pass
Installation et utilisation
bash# Installer un plugin
st0 plugin install my_plugin.py

# Activer
st0 plugin enable my_plugin

# Utiliser avec un projet
st0 new myproject --plugins my_plugin,git_plugin

# Configuration
st0 plugin config my_plugin
</details>

📦 Installation
Prérequis système
<table>
<tr>
<td>
Minimum requis

Python 3.11+
100 MB d'espace disque
512 MB RAM
Connexion internet (première installation)

</td>
<td>
Recommandé

Python 3.14+
500 MB d'espace disque
2 GB RAM
Git installé
VS Code ou autre IDE

</td>
</tr>
</table>
Installation rapide


# PowerShell (Administrateur)
# Télécharger et installer
Invoke-WebRequest -Uri https://raw.githubusercontent.com/st0-team/st0/main/install/install.ps1 -OutFile install.ps1
.\install.ps1

# Ou via curl (Windows 10+)
curl -o install.bat https://raw.githubusercontent.com/st0-team/st0/main/install/install.bat
install.bat

# Via winget (à venir)
winget install st0
🐧 Linux
bash# Debian/Ubuntu
curl -fsSL https://raw.githubusercontent.com/st0-team/st0/main/install/install.sh | bash

# Arch Linux
yay -S st0

# Fedora/RHEL
sudo dnf install st0

# Via snap
sudo snap install st0

# Via pip (toutes distributions)
pip install st0
🍎 macOS
bash# Homebrew (recommandé)
brew install st0

# Ou installation manuelle
curl -fsSL https://raw.githubusercontent.com/st0-team/st0/main/install/install.sh | bash

# Via pip
pip3 install st0
Installation manuelle
<details>
<summary><b>Cliquez pour voir les instructions détaillées</b></summary>
Étape 1 : Cloner le dépôt
bash# Via HTTPS
git clone https://github.com/st0-team/st0.git
cd st0

# Via SSH
git clone git@github.com:st0-team/st0.git
cd st0

# Télécharger le ZIP
wget https://github.com/st0-team/st0/archive/refs/heads/main.zip
unzip main.zip
cd st0-main
Étape 2 : Créer un environnement virtuel
bash# Python 3.14
python3.14 -m venv venv

# Activer l'environnement
# Linux/macOS
source venv/bin/activate

# Windows (PowerShell)
.\venv\Scripts\Activate.ps1

# Windows (CMD)
.\venv\Scripts\activate.bat
Étape 3 : Installer les dépendances
bash# Dépendances de production
pip install -r requirements.txt

# Dépendances de développement (optionnel)
pip install -r requirements-dev.txt

# Ou via setup.py
pip install -e .

# Ou via pyproject.toml
pip install -e ".[dev]"
Étape 4 : Vérifier l'installation
bash# Lancer l'application
python src/main.py --version

# Ou via le module
python -m st0 --version

# Tests
pytest

# Interface graphique
python src/main.py gui
Étape 5 : Créer un alias (optionnel)
bash# Linux/macOS - Ajouter à ~/.bashrc ou ~/.zshrc
echo 'alias st0="python /path/to/st0/src/main.py"' >> ~/.bashrc
source ~/.bashrc

# Ou créer un lien symbolique
sudo ln -s /path/to/st0/src/main.py /usr/local/bin/st0

# Windows - Ajouter au PATH
setx PATH "%PATH%;C:\path\to\st0\src"
</details>
Installation développeur
<details>
<summary><b>Pour contribuer au projet (Cliquez pour voir)</b></summary>
````bash
# 1. Fork le projet sur GitHub
2. Cloner votre fork
git clone https://github.com/VOTRE_USERNAME/st0.git
cd st0
3. Ajouter l'upstream
git remote add upstream https://github.com/st0-team/st0.git
4. Créer l'environnement de dev
python3.14 -m venv venv
source venv/bin/activate  # ou .\venv\Scripts\activate sur Windows
5. Installer en mode éditable avec dépendances dev
pip install -e ".[dev]"
6. Installer pre-commit hooks
pre-commit install
7. Vérifier l'installation
make test
make lint
make format
8. Créer une branche pour votre feature
git checkout -b feature/ma-super-feature
9. Développer et commiter
git add .
git commit -m "feat: ajout de ma super feature"
10. Pousser et créer une PR
git push origin feature/ma-super-feature

#### Structure de développement
````bash
st0/
├── src/              # Code source
├── tests/            # Tests unitaires et intégration
│   ├── unit/
│   ├── integration/
│   └── e2e/
├── docs/             # Documentation
├── examples/         # Exemples
├── scripts/          # Scripts utilitaires
├── .github/          # GitHub Actions
│   └── workflows/
├── Makefile          # Commandes make
├── pyproject.toml    # Configuration Python
├── setup.py          # Setup alternatif
└── requirements-dev.txt
Commandes de développement
bash# Tests
make test                 # Tous les tests
make test-unit            # Tests unitaires
make test-integration     # Tests d'intégration
make test-e2e             # Tests end-to-end
make test-coverage        # Tests avec couverture

# Quality checks
make lint                 # Linting (flake8, pylint, mypy)
make format               # Formatage (black, isort)
make type-check           # Type checking (mypy)
make security-check       # Vérification sécurité (bandit)

# Documentation
make docs                 # Générer la doc
make docs-serve           # Serveur de doc local

# Build
make build                # Build le package
make clean                # Nettoyer les fichiers temporaires

# Release
make version-bump-minor   # Bump version mineure
make version-bump-major   # Bump version majeure
make release              # Créer une release
</details>
Vérification de l'installation
bash# Vérifier la version
st0 --version
# Output: ST0 version 1.0.0

# Vérifier la santé de l'installation
st0 doctor
# ✅ Python version: 3.14.1
# ✅ Dependencies: All installed
# ✅ Templates directory: OK
# ✅ Database: OK
# ✅ Configuration: OK
# ✅ Permissions: OK

# Lister les templates disponibles
st0 template list
# ✅ 42 templates loaded

# Test rapide
st0 new test-project --template fastapi_full --dry-run
# ✅ Dry run successful
Mise à jour
bash# Via l'application
st0 update

# Via pip (quand disponible)
pip install --upgrade st0

# Via Homebrew
brew upgrade st0

# Manuel (git)
cd st0
git pull origin main
pip install -r requirements.txt
Désinstallation
bash# Via pip
pip uninstall st0

# Via Homebrew
brew uninstall st0

# Manuel
rm -rf /path/to/st0
rm -rf ~/.st0  # Données utilisateur (optionnel)

# Nettoyer la config
rm ~/.config/st0/config.json  # Linux/macOS
rm %APPDATA%\st0\config.json  # Windows

⚡ Démarrage rapide
Créer votre premier projet
Méthode 1 : Mode interactif (recommandé)
bashst0 new
```

Suivez les instructions à l'écran :
```
╔════════════════════════════════════════════════════════════╗
║           🚀 ST0 - Création de projet                      ║
╚════════════════════════════════════════════════════════════╝

📝 Nom du projet: my-awesome-api
👤 Auteur: John Doe
📧 Email: john@example.com
📄 Description: My awesome REST API
🏷️  Version: 0.1.0
⚖️  Licence: MIT

🎯 Sélectionnez un template:
  1. 🚀 FastAPI - Application complète (recommandé)
  2. 🐍 Django REST API
  3. ⚛️  React + Vite + TypeScript
  4. 💚 Vue 3 + Vite
  5. 🦀 Rust CLI Application
  ... (voir plus)

Votre choix [1]: 1

⚙️  Configuration FastAPI:
  🐍 Version Python: 3.14
  🗄️  Base de données: postgresql
  🐳 Inclure Docker? [O/n]: O
  🔴 Inclure Redis? [o/N]: N
  🧪 Inclure tests? [O/n]: O
  🚀 CI/CD: github_actions

📂 Dossier de destination: /home/john/Projects

✨ Génération du projet...
  ✅ Structure créée (12 dossiers)
  ✅ Fichiers générés (45 fichiers)
  ✅ Configuration Docker
  ✅ Tests configurés
  ✅ Git initialisé
  ✅ README.md créé

🎉 Projet créé avec succès!

📍 Emplacement: /home/john/Projects/my-awesome-api

🚀 Prochaines étapes:
  $ cd my-awesome-api
  $ make dev        # Lancer le serveur de dev
  $ make test       # Lancer les tests

📚 Documentation: http://localhost:8000/docs
Méthode 2 : Ligne de commande directe
bashst0 new my-awesome-api \
    --template fastapi_full \
    --author "John Doe" \
    --email "john@example.com" \
    --python 3.14 \
    --database postgresql \
    --with-docker \
    --with-tests
Méthode 3 : Depuis un fichier de configuration
yaml# project-config.yaml
project:
  name: my-awesome-api
  author: John Doe
  email: john@example.com
  description: My awesome REST API
  version: 0.1.0
  licence: MIT

template:
  name: fastapi_full
  variables:
    python_version: "3.14"
    database_type: postgresql
    use_docker: true
    use_redis: false
    include_tests: true
    ci_cd: github_actions

output:
  path: ~/Projects
  init_git: true
  open_in_editor: vscode
bashst0 new --from-file project-config.yaml
Mode interactif
bash# Lancer l'assistant de création
st0 new --interactive

# Avec des paramètres pré-remplis
st0 new my-api --interactive --template fastapi_full
Exemples pratiques
Exemple 1 : API REST FastAPI complète
bashst0 new ecommerce-api \
    --template fastapi_full \
    --author "Jane Smith" \
    --email "jane@company.com" \
    --description "E-commerce REST API" \
    --python 3.14 \
    --database postgresql \
    --with-docker \
    --with-redis \
    --with-celery \
    --with-tests \
    --ci-cd github_actions \
    --init-git \
    --open-vscode

cd ecommerce-api

# Structure générée:
# ecommerce-api/
# ├── ecommerce_api/
# │   ├── api/
# │   ├── core/
# │   ├── models/
# │   ├── schemas/
# │   └── services/
# ├── tests/
# ├── docker-compose.yml
# ├── Dockerfile
# ├── Makefile
# └── README.md

# Lancer avec Docker
make docker-up

# Ou en développement
make dev

# API disponible sur http://localhost:8000
# Docs sur http://localhost:8000/docs
Exemple 2 : Application React moderne
bashst0 new my-react-app \
    --template react_vite \
    --author "Bob Martin" \
    --description "Modern React application" \
    --with-typescript \
    --with-tailwind \
    --with-redux \
    --with-router \
    --with-tests \
    --init-git

cd my-react-app

# Structure générée:
# my-react-app/
# ├── src/
# │   ├── components/
# │   ├── pages/
# │   ├── hooks/
# │   ├── store/
# │   └── utils/
# ├── public/
# ├── tests/
# ├── package.json
# ├── vite.config.ts
# └── tailwind.config.js

# Installer les dépendances
npm install

# Lancer le serveur de dev
npm run dev

# Application disponible sur http://localhost:5173
Exemple 3 : CLI en Python avec Typer
bashst0 new my-cli \
    --template typer_cli \
    --author "Alice Johnson" \
    --description "Awesome CLI tool" \
    --python 3.14 \
    --with-tests

cd my-cli

# Structure générée:
# my-cli/
# ├── my_cli/
# │   ├── commands/
# │   ├── utils/
# │   └── main.py
# ├── tests/
# ├── setup.py
# └── README.md

# Installer en mode dev
pip install -e .

# Utiliser votre CLI
my-cli --help
my-cli command --option value
Exemple 4 : Microservice Go
bashst0 new user-service \
    --template go_microservice \
    --author "Charlie Brown" \
    --description "User management microservice" \
    --with-docker \
    --with-kubernetes \
    --with-grpc \
    --with-tests

cd user-service

# Structure générée:
# user-service/
# ├── cmd/
# ├── internal/
# ├── pkg/
# ├── api/
# ├── deployments/
# ├── Dockerfile
# ├── go.mod
# └── Makefile

# Build et run
make run

# Avec Docker
make docker-run

# Tests
make test
Exemple 5 : Full-stack MERN
bashst0 new social-platform \
    --template mern_stack \
    --author "David Wilson" \
    --description "Social media platform" \
    --with-docker \
    --with-tests \
    --with-ci-cd \
    --init-git

cd social-platform

# Structure générée:
# social-platform/
# ├── frontend/          # React app
# ├── backend/           # Express API
# ├── shared/            # Shared types/utils
# ├── docker-compose.yml
# └── README.md

# Lancer le stack complet
docker-compose up

# Frontend: http://localhost:3000
# Backend API: http://localhost:5000
# MongoDB: localhost:27017
Exemple 6 : Projet Data Science
bashst0 new ml-project \
    --template ml_project \
    --author "Eva Martinez" \
    --description "Machine learning project" \
    --python 3.14 \
    --with-jupyter \
    --with-mlflow \
    --with-docker

cd ml-project

# Structure générée:
# ml-project/
# ├── notebooks/
# ├── src/
# │   ├── data/
# │   ├── features/
# │   ├── models/
# │   └── visualization/
# ├── tests/
# ├── data/
# ├── models/
# └── reports/

# Installer les dépendances
pip install -r requirements.txt

# Lancer Jupyter
jupyter lab

# Lancer MLflow UI
mlflow ui

📚 Guide utilisateur détaillé
Utilisation de l'interface graphique
<details>
<summary><b>🖥️ Guide complet de l'interface GUI (Cliquez pour déplier)</b></summary>
Lancement de l'interface
bash# Méthode 1 : Via commande
st0 gui

# Méthode 2 : Commande par défaut
st0

# Méthode 3 : Double-clic sur l'exécutable (Windows/macOS)
# Méthode 4 : Via le menu Démarrer/Applications
```

#### Vue d'accueil
```
┌─────────────────────────────────────────────────────────────┐
│ ST0 - Structure Template Zero                    [─][□][×]  │
├─────────────────────────────────────────────────────────────┤
│  🏠 Accueil    📝 Nouveau    📚 Templates    📊 Historique  │
│  ⚙️  Paramètres    💡 Aide                                  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌─────────────────────────────────────────────────────┐   │
│  │              👋 Bienvenue dans ST0                  │   │
│  │                                                     │   │
│  │     Générateur universel de structures de projets  │   │
│  │                                                     │   │
│  │  ┌────────────────┐  ┌────────────────┐           │   │
│  │  │ 📝 Nouveau     │  │ 📚 Templates   │           │   │
│  │  │ Projet         │  │ (42 disponibles) │         │   │
│  │  └────────────────┘  └────────────────┘           │   │
│  │                                                     │   │
│  │  ┌────────────────┐  ┌────────────────┐           │   │
│  │  │ 📊 Historique  │  │ 🌐 Marketplace │           │   │
│  │  │ (15 projets)   │  │ (Explorer)     │           │   │
│  │  └────────────────┘  └────────────────┘           │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  📌 Projets récents:                                        │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ 📁 my-awesome-api     FastAPI      Il y a 2h    ✨ │   │
│  │ 📁 react-dashboard    React        Il y a 1j    ⭐ │   │
│  │ 📁 cli-tool           Python CLI   Il y a 3j       │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  💡 Astuce du jour: Utilisez Ctrl+N pour créer rapidement  │
│     un nouveau projet                                       │
└─────────────────────────────────────────────────────────────┘
```

#### Création d'un projet

**Étape 1 : Configuration de base**
```
┌─────────────────────────────────────────────────────────────┐
│ 📝 Nouveau Projet - Configuration                           │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  📋 Informations du projet                                  │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ Nom du projet *                                     │   │
│  │ [my-awesome-api________________________] ✅          │   │
│  │ ℹ️  snake_case: my_awesome_api                       │   │
│  │    kebab-case: my-awesome-api                       │   │
│  │                                                     │   │
│  │ Description                                         │   │
│  │ [________________________________________]          │   │
│  │ [________________________________________]          │   │
│  │                                                     │   │
│  │ Auteur *          Email *                           │   │
│  │ [John Doe______]  [john@example.com___] ✅          │   │
│  │                                                     │   │
│  │ Version    Licence     Python                       │   │
│  │ [0.1.0_]   [MIT  ▼]   [3.14 ▼]                     │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  📝 Variables personnalisées (optionnel)                    │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ Clé              Valeur             [+] [-]         │   │
│  │ GITHUB_USERNAME  johndoe             🗑️              │   │
│  │ COMPANY          ACME Inc            🗑️              │   │
│  │ [+ Ajouter une variable]                            │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  [Précédent]                          [Suivant: Templates] │
└─────────────────────────────────────────────────────────────┘
```

**Étape 2 : Sélection du template**
```
┌─────────────────────────────────────────────────────────────┐
│ 📝 Nouveau Projet - Sélection du template                   │
├─────────────────────────────────────────────────────────────┤
│  🎯 Zone Drag & Drop                                        │
│  ╔═════════════════════════════════════════════════════╗   │
│  ║  📦 Glissez vos templates ici                       ║   │
│  ║      ou cliquez pour parcourir                      ║   │
│  ║                                                     ║   │
│  ║  Formats: .yaml, .json, .toml, .txt                ║   │
│  ╚═════════════════════════════════════════════════════╝   │
│                                                             │
│  🔍 Recherche: [fastapi api rest_________] 🔎              │
│  [Catégorie: Web ▼] [Langage: Python ▼] [Officiel ✓]     │
│  Tags actifs: [#fastapi ×] [#rest ×]                       │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ [🎨 Vue Grille]  [📄 Vue Liste]   Trier: [Pop▼]    │   │
│  ├─────────┬─────────┬─────────┬─────────┐            │   │
│  │ ┌─────┐ │ ┌─────┐ │ ┌─────┐ │ ┌─────┐ │            │   │
│  │ │ 🚀  │ │ │ 🐍  │ │ │ ⚛️  │ │ │ 💚  │ │            │   │
│  │ │Fast │ │ │Djngo│ │ │React│ │ │Vue3 │ │            │   │
│  │ │ API │ │ │ REST│ │ │+Vite│ │ │+Vite│ │            │   │
│  │ │ Full│ │ │ API │ │ │  TS │ │ │     │ │            │   │
│  │ └─────┘ │ └─────┘ │ └─────┘ │ └─────┘ │            │   │
│  │ ⭐⭐⭐⭐⭐ │ ⭐⭐⭐⭐☆ │ ⭐⭐⭐⭐⭐ │ ⭐⭐⭐⭐☆ │            │   │
│  │ 2.5K↓  │ 1.8K↓  │ 3.2K↓  │ 2.1K↓  │            │   │
│  │ ✅ Off. │ ✅ Off. │ ✅ Off. │ ✅ Off. │            │   │
│  │ [☑️ Sél]│ [☐ Sél]│ [☐ Sél]│ [☐ Sél]│            │   │
│  ├─────────┼─────────┼─────────┼─────────┤            │   │
│  │   ...   │   ...   │   ...   │   ...   │            │   │
│  └─────────┴─────────┴─────────┴─────────┘            │   │
│  [◀ 1 2 3 4 5 ▶]                                       │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  📋 Template sélectionné: FastAPI Full                      │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ 🚀 FastAPI Full Stack v2.5.0                        │   │
│  │ API complète avec auth, DB, tests, Docker           │   │
│  │ 📊 45 fichiers • 12 dossiers • ~250KB • ~15s        │   │
│  │ [⚙️ Configurer] [👁️ Prévisualiser] [🗑️ Retirer]   │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  [◀ Précédent]              [Suivant: Configuration ▶]     │
└─────────────────────────────────────────────────────────────┘
```

**Étape 3 : Configuration du template**
```
┌─────────────────────────────────────────────────────────────┐
│ 📝 Nouveau Projet - Configuration FastAPI                   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ⚙️  Options du template                                    │
│                                                             │
│  🐍 Version Python                                          │
│  ◉ 3.14 (recommandé)  ○ 3.13  ○ 3.12  ○ 3.11              │
│                                                             │
│  🗄️  Base de données                                        │
│  ◉ PostgreSQL  ○ MySQL  ○ SQLite                           │
│                                                             │
│  📦 Services additionnels                                   │
│  ☑️ Docker & Docker Compose                                 │
│  ☑️ Tests (Pytest + Coverage)                               │
│  ☐ Redis (Cache & Sessions)                                │
│  ☐ Celery (Tâches asynchrones)                             │
│  ☑️ Documentation (MkDocs)                                  │
│                                                             │
│  🚀 CI/CD                                                   │
│  ◉ GitHub Actions  ○ GitLab CI  ○ Jenkins  ○ Aucun        │
│                                                             │
│  📁 Structure optionnelle                                   │
│  ☑️ Scripts d'initialisation                                │
│  ☑️ Fichiers de configuration                               │
│  ☑️ Exemples de code                                        │
│                                                             │
│  🔐 Authentification                                        │
│  ☑️ JWT Tokens                                              │
│  ☑️ OAuth2                                                  │
│  ☐ LDAP                                                     │
│                                                             │
│  📧 Services Email                                          │
│  ☐ Configuration SMTP                                       │
│  ☐ Templates d'emails                                       │
│                                                             │
│  💡 Aperçu: 45 fichiers, 12 dossiers, ~250KB               │
│                                                             │
│  [◀ Précédent]              [Suivant: Destination ▶]       │
└─────────────────────────────────────────────────────────────┘
Étape 4 : Destination et finalisation
┌─────────────────────────────────────────────────────────────┐
│ 📝 Nouveau Projet - Destination                             │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  📂 Dossier de destination                                  │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ /home/john/Projects/my-awesome-api                  │   │
│  │ [____________________________________] [📁 Parcourir]│   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  ✅ Chemin valide                                           │
│  ✅ Permissions d'écriture OK                               │
│  ✅ 50 GB d'espace disponible                               │
│  ⚠️  Le dossier existe déjà (sera créé dans un sous-dossier)│
│                                                             │
│  🔧 Actions post-génération                                 │
│  ☑️ Initialiser un dépôt Git                                │
│  ☑️ Créer un environnement virtuel Python                   │
│  ☐ Installer les dépendances (~10 min)                     │
│  ☑️ Ouvrir dans l'éditeur après création                    │
│                                                             │
│  💻 Éditeur à utiliser                                      │
│  ◉ VS Code  ○ PyCharm  ○ Sublime  ○ Vim  ○ Aucun          │
│                                                             │
│  📊 Estimation                                              │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ • Fichiers: 45                                      │   │
│  │ • Dossiers: 12                                      │   │
│  │ • Taille estimée: ~250 KB                           │   │
│  │ • Temps estimé: ~15 secondes                        │   │
│  │ • Template: FastAPI Full v2.5.0RéessayerPContinuer│  │ • Base de données: PostgreSQL                       │   │
│  │ • Docker: Oui                                       │   │
│  │ • Tests: Oui                                        │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  [◀ Précédent]  [👁️ Prévisualiser]  [🚀 GÉNÉRER]         │
└─────────────────────────────────────────────────────────────┘
Étape 5 : Prévisualisation (optionnelle)
┌─────────────────────────────────────────────────────────────┐
│ 👁️ Prévisualisation: my-awesome-api            [─][□][×]  │
├─────────────────────────────────────────────────────────────┤
│  [📁 Structure] [📄 Fichiers] [⚙️ Variables] [📊 Stats]    │
├──────────────────────┬──────────────────────────────────────┤
│                      │                                      │
│  📁 Structure        │  📄 Aperçu: main.py                  │
│                      │  ────────────────────────────────────│
│  my-awesome-api/     │  1  """                              │
│  ├─ 📁 my_awesome_api│  2  My Awesome API                   │
│  │  ├─ 📄 __init__.py│  3                                   │
│  │  ├─ 📄 main.py ◀──┤  4  Author: John Doe                 │
│  │  ├─ 📄 __main__.py│  5  Version: 0.1.0                   │
│  │  ├─ 📁 api/       │  6  License: MIT                     │
│  │  │  ├─ 📄 deps.py │  7  """                              │
│  │  │  └─ 📁 v1/     │  8                                   │
│  │  │     ├─ 📄 api.py  9  from fastapi import FastAPI      │
│  │  │     └─ 📁 endpoints/ 10  from fastapi.middleware...  │
│  │  ├─ 📁 core/      │  11                                  │
│  │  │  ├─ 📄 config.py 12  app = FastAPI(                  │
│  │  │  ├─ 📄 security.py 13      title="My Awesome API",  │
│  │  │  └─ 📄 deps.py │  14      description="A FastAPI...",│
│  │  ├─ 📁 models/    │  15      version="0.1.0",           │
│  │  │  ├─ 📄 user.py │  16      docs_url="/docs"           │
│  │  │  └─ 📄 item.py │  17  )                              │
│  │  ├─ 📁 schemas/   │  18                                  │
│  │  ├─ 📁 services/  │  19  # CORS middleware               │
│  │  ├─ 📁 db/        │  20  app.add_middleware(             │
│  │  └─ 📁 utils/     │  21      CORSMiddleware,             │
│  ├─ 📁 tests/        │  22      allow_origins=...           │
│  │  ├─ 📁 api/       │  23  )                               │
│  │  └─ 📁 unit/      │  24                                  │
│  ├─ 📁 docs/         │  25  @app.get("/")                   │
│  ├─ 📁 scripts/      │  26  async def root():               │
│  ├─ 📄 README.md     │  27      return {"message": "..."}   │
│  ├─ 📄 Dockerfile    │  28                                  │
│  ├─ 📄 docker-compose│  29  if __name__ == "__main__":     │
│  ├─ 📄 requirements.txt 30      import uvicorn            │
│  ├─ 📄 Makefile      │  31      uvicorn.run(...)           │
│  ├─ 📄 .gitignore    │                                      │
│  └─ 📄 pyproject.toml│  [◀ Précédent] [Suivant ▶]          │
│                      │                                      │
│  📊 45 fichiers      │  Variables utilisées:                │
│  📁 12 dossiers      │  • PROJECT_NAME: my-awesome-api      │
│  💾 ~250 KB          │  • AUTHOR: John Doe                  │
│  ⏱️  ~15 secondes     │  • EMAIL: john@example.com           │
│                      │  • PYTHON_VERSION: 3.14              │
│  [🔍 Zoom +/-]       │  • DATABASE_TYPE: postgresql         │
│  [📥 Exporter]       │  • USE_DOCKER: true                  │
│                      │                                      │
├──────────────────────┴──────────────────────────────────────┤
│  [⬅️ Retour]  [💾 Exporter Preview]  [✅ Confirmer]        │
└─────────────────────────────────────────────────────────────┘
Étape 6 : Génération en cours
┌─────────────────────────────────────────────────────────────┐
│ 🚀 Génération en cours...                       [─][×]      │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  📦 Création du projet: my-awesome-api                      │
│                                                             │
│  ╔═══════════════════════════════════════════════════╗     │
│  ║ ████████████████████████████████░░░░░░░░░    72% ║     │
│  ╚═══════════════════════════════════════════════════╝     │
│                                                             │
│  Étape 4/6: Génération des fichiers                        │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ ✅ [00:01] Validation des paramètres                │   │
│  │ ✅ [00:02] Parsing du template                       │   │
│  │ ✅ [00:05] Création de la structure (12 dossiers)   │   │
│  │ ⏳ [00:11] Génération des fichiers... (33/45)       │   │
│  │    └─ 📄 Création de api/v1/endpoints/users.py      │   │
│  │ ⏸️  [--:--] Application des hooks                    │   │
│  │ ⏸️  [--:--] Finalisation                             │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  📊 Progression détaillée:                                  │
│  • Fichiers créés: 33/45 (73%)                             │
│  • Dossiers créés: 12/12 ✅                                 │
│  • Taille actuelle: 182 KB / 250 KB                        │
│  • Temps écoulé: 00:11                                     │
│  • Temps restant: ~00:04                                   │
│                                                             │
│  📝 Log détaillé (dernières lignes):                        │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ [14:32:09] INFO: Processing template 'main.py'      │   │
│  │ [14:32:09] INFO: Applying Jinja2 variables          │   │
│  │ [14:32:10] INFO: Writing file: main.py              │   │
│  │ [14:32:10] INFO: Processing template 'config.py'    │   │
│  │ [14:32:11] INFO: Creating endpoint users.py         │   │
│  │ [14:32:11] DEBUG: Variable substitution completed   │   │
│  │ ▼                                                    │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  [⏸️ Pause]  [❌ Annuler]  [💾 Sauvegarder Log]            │
└─────────────────────────────────────────────────────────────┘
Étape 7 : Succès
┌─────────────────────────────────────────────────────────────┐
│ ✨ Projet créé avec succès!                     [─][□][×]  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│                      🎉 🎊 ✨ 🚀                            │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐   │
│  │                                                     │   │
│  │     Votre projet est prêt à être utilisé!          │   │
│  │                                                     │   │
│  │  📦 Projet: my-awesome-api                          │   │
│  │  📍 Emplacement:                                    │   │
│  │     /home/john/Projects/my-awesome-api              │   │
│  │                                                     │   │
│  │  ✅ 45 fichiers créés                               │   │
│  │  ✅ 12 dossiers créés                               │   │
│  │  ✅ 248 KB générés                                  │   │
│  │  ⏱️  Temps: 14 secondes                             │   │
│  │                                                     │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  🚀 Prochaines étapes:                                      │
│                                                             │
│  1️⃣  Configurer l'environnement                            │
│     $ cd my-awesome-api                                    │
│     $ cp .env.example .env                                 │
│     $ nano .env  # Éditer les variables                    │
│                                                             │
│  2️⃣  Créer l'environnement virtuel                         │
│     $ python3.14 -m venv venv                              │
│     $ source venv/bin/activate                             │
│                                                             │
│  3️⃣  Installer les dépendances                             │
│     $ pip install -r requirements.txt                      │
│                                                             │
│  4️⃣  Initialiser la base de données                        │
│     $ alembic upgrade head                                 │
│     $ python scripts/init_db.py                            │
│                                                             │
│  5️⃣  Lancer l'application                                  │
│     🐳 Avec Docker:                                        │
│        $ docker-compose up -d                              │
│     💻 En développement:                                   │
│        $ uvicorn my_awesome_api.main:app --reload          │
│        ou                                                  │
│        $ make dev                                          │
│                                                             │
│  📚 Ressources:                                             │
│  • Documentation: http://localhost:8000/docs               │
│  • API Interactive: http://localhost:8000/redoc            │
│  • README: /home/john/Projects/my-awesome-api/README.md    │
│                                                             │
│  📊 Statistiques:                                           │
│  • Template: FastAPI Full v2.5.0                           │
│  • Temps de génération: 14s                                │
│  • Taille totale: 248 KB                                   │
│  • Popularité du template: ⭐⭐⭐⭐⭐ (2,523 utilisations)   │
│                                                             │
│  [📂 Ouvrir le dossier]  [💻 Ouvrir VS Code]               │
│  [📋 Copier les commandes]  [✅ Terminer]                  │
│                                                             │
│  💡 Tip: Ajoutez ce projet aux favoris? [⭐ Oui] [Non]     │
└─────────────────────────────────────────────────────────────┘
Gestion des templates dans l'interface
Vue Templates
┌─────────────────────────────────────────────────────────────┐
│ 📚 Gestion des Templates                        [─][□][×]  │
├─────────────────────────────────────────────────────────────┤
│  [🏠 Mes Templates] [🌐 Marketplace] [➕ Créer] [📥 Import]│
├──────────────────┬──────────────────────────────────────────┤
│                  │                                          │
│  📂 CATÉGORIES   │  🔍 [Rechercher templates........] 🔎   │
│                  │  [Tous ▼] [Trier: Popularité ▼]         │
│  ▼ 🐍 Python (12)│  Tags: [#fastapi ×] [#rest ×] [+ Ajout] │
│    • Web (5)     │                                          │
│    • CLI (3)     │  ┌──────────────────────────────────────┤
│    • Data (4)    │  │ [🎨 Grille] [📄 Liste] [📊 Stats]    │
│  ▼ 💛 JavaScript │  ├──────────────────────────────────────┤
│    • Frontend (6)│  │                                       │
│    • Backend (4) │  │ ┌─────────────────────────────────┐ │
│    • Fullstack(2)│  │ │ 🚀 FastAPI Full Stack           │ │
│  ▶ 🦀 Rust (2)   │  │ │ v2.5.0 • Officiel ✅ • ⭐⭐⭐⭐⭐ │ │
│  ▶ 🔷 Go (3)     │  │ │                                 │ │
│  ▶ ☕ Java (4)   │  │ │ Application FastAPI complète    │ │
│  ▶ 📱 Mobile (4) │  │ │ avec authentification, base de  │ │
│  ▶ 🐳 DevOps (5) │  │ │ données, tests et Docker        │ │
│  ▶ 🎨 Custom (8) │  │ │                                 │ │
│                  │  │ │ 📊 45 fichiers • 12 dossiers    │ │
│  🏷️ TAGS         │  │ │ 💾 ~250KB • ⏱️ ~15s             │ │
│                  │  │ │ 🏷️ #python #fastapi #rest #jwt  │ │
│  #fastapi (8)    │  │ │                                 │ │
│  #react (12)     │  │ │ 📈 Utilisé 2,523 fois           │ │
│  #docker (15)    │  │ │ 🕒 Mis à jour il y a 2 jours    │ │
│  #api (20)       │  │ │                                 │ │
│  #typescript (10)│  │ │ [✏️ Éditer] [📋 Dupliquer]      │ │
│  [+ Nouveau]     │  │ │ [👁️ Prévisualiser] [⭐ Favori] │ │
│                  │  │ │ [🗑️ Supprimer] [📊 Stats]       │ │
│  🎯 FILTRES      │  │ └─────────────────────────────────┘ │
│                  │  │                                       │
│  ☑️ Officiels    │  │ ┌─────────────────────────────────┐ │
│  ☐ Communauté   │  │ │ 🐍 Django REST API              │ │
│  ☑️ Vérifiés     │  │ │ v1.8.0 • Personnalisé • ⭐⭐⭐⭐☆│ │
│  ☐ Premium      │  │ │                                 │ │
│  ☐ Favoris      │  │ │ Template Django avec DRF, JWT   │ │
│                  │  │ │ Celery, Redis et Docker         │ │
│  📊 STATS        │  │ │                                 │ │
│                  │  │ │ 📊 38 fichiers • 10 dossiers    │ │
│  Total: 42       │  │ │ 📈 Utilisé 89 fois              │ │
│  Officiels: 25   │  │ │                                 │ │
│  Custom: 17      │  │ │ [✏️ Éditer] [👁️ Prévisualiser]  │ │
│  Favoris: 12     │  │ └─────────────────────────────────┘ │
│                  │  │                                       │
│  🔧 ACTIONS      │  │ ┌─────────────────────────────────┐ │
│                  │  │ │ ⚛️ React + Vite + TypeScript    │ │
│  [➕ Créer]      │  │ │ v3.2.0 • Communauté • ⭐⭐⭐⭐⭐  │ │
│  [📥 Importer]   │  │ │                                 │ │
│  [📤 Exporter]   │  │ │ Template React moderne avec     │ │
│  [🔄 Sync]       │  │ │ Vite, TypeScript, Tailwind...   │ │
│  [🔧 Backup]     │  │ │                                 │ │
│                  │  │ │ 📊 52 fichiers • 234 utilisé    │ │
│                  │  │ │ [⭐ Favori] [👁️ Prévisualiser]  │ │
│                  │  │ └─────────────────────────────────┘ │
│                  │  │                                       │
│                  │  │  [◀ 1 2 3 4 5 ▶]                     │
├──────────────────┴──────────────────────────────────────────┤
│ 💡 Glissez-déposez un fichier template pour l'importer     │
└─────────────────────────────────────────────────────────────┘
Éditeur de template intégré
┌─────────────────────────────────────────────────────────────┐
│ ✏️ Éditeur: fastapi_full.yaml                  [─][□][×]  │
├─────────────────────────────────────────────────────────────┤
│ [💾 Sauv] [↩️ Annul] [👁️ Prévis] [✔️ Valid] [? Aide]       │
├──────────────┬──────────────────────────────────────────────┤
│              │                                              │
│ 📋 STRUCTURE │  1  # META                                   │
│              │  2  meta:                                    │
│ ▼ Métadonnées│  3    name: "fastapi_full"                  │
│ ▶ Variables  │  4    display_name: "FastAPI - Complete"    │
│ ▶ Structure  │  5    version: "2.5.0"                      │
│ ▼ Templates  │  6    author: "ST0 Team"                    │
│   • readme   │  7    description: "Full FastAPI app..."    │
│   • main     │  8    category: "web"                       │
│   • config   │  9    tags:                                 │
│   [+ Ajout]  │ 10      - python                            │
│              │ 11      - fastapi                           │
│ 🎨 THÈME     │ 12      - rest                              │
│              │ 13                                           │
│ [Dark ▼]     │ 14  # VARIABLES                             │
│              │ 15  variables:                              │
│ 🔧 OUTILS    │ 16    required:                             │
│              │ 17      - name: "PROJECT_NAME"              │
│ [🎨 Format]  │ 18        type: "string"                    │
│ [✔️ Valider] │ 19        description: "Project name"       │
│ [🔍 Search]  │ 20        validation:                       │
│ [⚡ Snippet]  │ 21          regex: "^[a-zA-Z][a-zA-Z0-9_]*$"│
│              │ 22          min_length: 3                   │
│ 📝 VALID.    │ 23          max_length: 50                  │
│              │ 24                                           │
│ ✅ Syntaxe OK│ 25    optional:                             │
│ ✅ Schéma OK │ 26      - name: "VERSION"                   │
│ ⚠️ 2 warnings│ 27        type: "string"                    │
│              │ 28        default: "0.1.0"                  │
│ 🔍 RECHERCHE │ 29                                           │
│              │ 30  # STRUCTURE                             │
│ [Rechercher..│ 31  structure:                              │
│  dans code]  │ 32    folders:                              │
│              │ 33      - path: "{{PROJECT_NAME_SNAKE}}"   │
│ 💡 AIDE      │ 34                                           │
│              │ 35    files:                                │
│ Variables:   │ 36      - path: "README.md"                 │
│ • {{VAR}}    │ 37        template: "readme"                │
│ • {% if %}   │ 38                                           │
│ • {% for %}  │ 39  # TEMPLATES                             │
│              │ 40  templates:                              │
│ [📚 Doc]     │ 41    readme: |                             │
│              │ 42      # {{PROJECT_NAME}}                  │
├──────────────┴──────────────────────────────────────────────┤
│ Ligne 42:12 • UTF-8 • YAML • 1.2KB • Modifié • [Erreurs: 0]│
└─────────────────────────────────────────────────────────────┘
</details>
Utilisation de l'interface CLI
<details>
<summary><b>⌨️ Guide complet de l'interface CLI (Cliquez pour déplier)</b></summary>
Workflows CLI courants
Workflow 1 : Création rapide
bash# Création avec valeurs par défaut
st0 new myproject --template fastapi_full

# Résultat
✨ Generating project 'myproject'...
  ✅ Template loaded: fastapi_full v2.5.0
  ✅ Structure created (12 directories)
  ✅ Files generated (45 files)
  ✅ Git initialized
  ⏱️  Completed in 14s

🎉 Project 'myproject' created successfully!

📍 Location: /home/user/myproject
📚 Next steps:
  $ cd myproject
  $ make dev
Workflow 2 : Création personnalisée
bash# Avec configuration complète
st0 new ecommerce-api \
    --template fastapi_full \
    --author "Jane Smith" \
    --email "jane@company.com" \
    --description "E-commerce REST API" \
    --version "1.0.0" \
    --licence "Apache-2.0" \
    --python 3.14 \
    --database postgresql \
    --with-docker \
    --with-redis \
    --with-celery \
    --with-tests \
    --ci-cd github_actions \
    --output ~/Projects \
    --init-git \
    --create-venv \
    --open-vscode \
    --verbose

# Résultat détaillé
[14:30:00] INFO: Starting project generation
[14:30:00] INFO: Template: fastapi_full v2.5.0
[14:30:01] INFO: Validating parameters...
[14:30:01] ✅ All parameters valid
[14:30:02] INFO: Parsing template...
[14:30:03] INFO: Processing variables...
[14:30:03]   • PROJECT_NAME: ecommerce-api
[14:30:03]   • PROJECT_NAME_SNAKE: ecommerce_api
[14:30:03]   • AUTHOR: Jane Smith
[14:30:03]   • EMAIL: jane@company.com
[14:30:03]   • PYTHON_VERSION: 3.14
[14:30:04] INFO: Creating folder structure...
[14:30:04]   📁 ecommerce_api/
[14:30:04]   📁 ecommerce_api/api/
[14:30:04]   📁 ecommerce_api/core/
[14:30:05]   ... (12 directories created)
[14:30:06] INFO: Generating files...
[14:30:06]   📄 README.md
[14:30:07]   📄 ecommerce_api/main.py
[14:30:07]   📄 ecommerce_api/core/config.py
[14:30:08]   ... (45 files created)
[14:30:10] INFO: Running post-generation hooks...
[14:30:11]   ✅ Git initialized
[14:30:12]   ✅ Virtual environment created
[14:30:13]   ✅ Dependencies installed
[14:30:14]   ✅ Opened in VS Code

🎉 Project created successfully!

📊 Statistics:
  • Files: 45
  • Directories: 12
  • Total size: 248 KB
  • Time: 14 seconds

📍 Location: /home/jane/Projects/ecommerce-api

🚀 Quick start:
  $ cd ~/Projects/ecommerce-api
  $ docker-compose up -d  # Start with Docker
  # OR
  $ source venv/bin/activate
  $ make dev             # Start development server

📚 Documentation: http://localhost:8000/docs
Workflow 3 : Mode interactif
bashst0 new --interactive

# Résultat interactif
┌────────────────────────────────────────────┐
│ ST0 - Interactive Project Creator         │
└────────────────────────────────────────────┘

📝 Project Configuration

? Project name: my-api
? Author: John Doe  
? Email: john@example.com
? Description: My awesome API
? Version [0.1.0]: 
? License: 
  ❯ MIT
    Apache-2.0
    GPL-3.0
    BSD-3-Clause
    Proprietary

🎯 Template Selection

? Select a category:
  ❯ Web
    CLI
    Data Science
    Mobile
    DevOps
    Custom

? Select a template (Web):
  ❯ 🚀 FastAPI Full Stack (★★★★★)
    🐍 Django REST API (★★★★☆)
    ⚛️  React + Vite (★★★★★)
    💚 Vue 3 + Vite (★★★★☆)
    More...

⚙️  Template Configuration (FastAPI)

? Python version:
  3.14 (recommended)
  3.13
  3.12
  3.11

? Database:
  ❯ PostgreSQL
    MySQL
    SQLite

? Include Docker? (Y/n): Y
? Include Redis? (y/N): N
? Include Tests? (Y/n): Y
? CI/CD:
  ❯ GitHub Actions
    GitLab CI
    Jenkins
    None

📂 Destination

? Output directory [~/Projects]: 
? Initialize Git? (Y/n): Y
? Create virtual environment? (Y/n): Y
? Install dependencies? (y/N): N
? Open in editor? 
  ❯ VS Code
    PyCharm
    Sublime Text
    None

📊 Summary

Project: my-api
Template: FastAPI Full Stack v2.5.0
Files: 45 | Directories: 12 | Size: ~250KB
Time: ~15 seconds

? Proceed with generation? (Y/n): Y

✨ Generating project...
[████████████████████████████████] 100%

🎉 Done!
Workflow 4 : Depuis fichier de configuration
bash# Créer un fichier de configuration
cat > project.yaml <<EOF
project:
  name: my-saas-platform
  author: DevTeam
  email: dev@company.com
  description: SaaS Platform MVP
  version: 1.0.0
  licence: MIT

template:
  name: mern_stack
  variables:
    use_docker: true
    use_tests: true
    ci_cd: github_actions
    auth_provider: auth0
    database: mongodb
    cache: redis
    payment_provider: stripe

output:
  path: ~/Projects/saas
  init_git: true
  create_venv: false
  install_deps: false
  open_editor: vscode

post_actions:
  - name: setup_env
    command: cp .env.example .env
  - name: install_frontend
    command: cd frontend && npm install
  - name: install_backend
    command: cd backend && npm install
EOF

# Générer depuis le fichier
st0 new --from-file project.yaml

# Résultat
✨ Loading configuration from project.yaml...
  ✅ Configuration loaded successfully

🚀 Generating project 'my-saas-platform'...
  Template: MERN Stack v2.1.0
  
  [████████████████████████] 100%
  
  ✅ Frontend created (React + Vite)

🪟 Windows
powershell# PowerShell (Administrateur)
# Télécharger et installer
Invoke-WebRequest
