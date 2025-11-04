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
🪟 Windows
powershell# PowerShell (Administrateur)
# Télécharger et installer
Invoke-WebRequest
