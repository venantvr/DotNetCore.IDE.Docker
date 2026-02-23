# DotNetCore.IDE.Docker

Environnement .NET Core sous Docker avec Visual Studio Code et acces VNC.

## Structure

| Fichier / Dossier | Role |
|-|-|
| `Dockerfile` | Image Docker .NET Core + VS Code |
| `password.txt` | Mot de passe VNC par defaut |
| `start-vnc.sh` | Script de demarrage du serveur VNC |
| `xstartup` | Configuration de session X |

## Stack

- Docker
- .NET Core
- Visual Studio Code
- VNC
