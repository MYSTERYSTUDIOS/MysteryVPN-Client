# MysteryVPN-Client
EN:
# MysteryVPN Client — C++ GUI for OpenVPN

A native Windows application in C++ (WinAPI) for connecting to OpenVPN via .ovpn configs.

Minimalism, speed, and no unnecessary dependencies.

## 🧱 Requirements

- Windows 7/8/10/11
- OpenVPN (any version) — [official website](https://openvpn.net/community-downloads/)
- OpenVPN must be installed and accessible via %PATH%

> This project does not contain OpenVPN. It only runs the existing installation.

## 📦 Installation

1. Download the `MysteryVPNClient.zip` archive from the **Releases** section
2. Unzip **all contents into one folder**
- Example: `C:\MysteryVPNClient\`
- The folder should contain `VPNClient.exe` and related files
3. Run `VPNClient.exe` (administrator rights are not required)

> ⚠️ Important: The program uses relative paths. Do not move files individually.

## 🎮 Usage

| Action | What to press |
|----------|-------------|
| Select `.ovpn` config | **"Select config"** button |
| Forget current config | **"Clear"** button |
| Connect | **"Connect"** button |

When connecting, the program calls:
```cmd
openvpn.exe --config "path\to\.ovpn config"

RU: 
# MysteryVPN Client — C++ GUI для OpenVPN

Нативное Windows-приложение на **C++ (WinAPI)** для подключения к OpenVPN через `.ovpn`-конфиги.  
Минимализм, скорость и никаких лишних зависимостей.

## 🧱 Требования

- **Windows** 7/8/10/11
- **OpenVPN** (любая версия) — [официальный сайт](https://openvpn.net/community-downloads/)
- OpenVPN должен быть установлен и доступен через `%PATH%`

> Этот проект **не содержит** OpenVPN. Он только запускает уже установленный.

## 📦 Установка

1. Скачай архив `MysteryVPNClient.zip` из раздела **Releases**
2. Распакуй **все содержимое в одну папку**
   - Пример: `C:\MysteryVPNClient\`
   - Внутри должны лежать `VPNClient.exe` и сопутствующие файлы
3. Запусти `VPNClient.exe` (права администратора не требуются)

> ⚠️ Важно: программа использует относительные пути. Не перемещайте файлы по отдельности.

## 🎮 Использование

| Действие | Что нажать |
|----------|-------------|
| Выбрать `.ovpn` конфиг | Кнопка **«Выбрать конфиг»** |
| Забыть текущий конфиг | Кнопка **«Очистить»** |
| Подключиться | Кнопка **«Подключиться»** |

При подключении программа вызывает:
```cmd
openvpn.exe --config "путь\к\конфигу.ovpn"
