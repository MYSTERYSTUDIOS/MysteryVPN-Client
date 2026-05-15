# MysteryVPN-Client
EN:

MysteryVPN Client is a native Windows application written in C++ (WinAPI) that serves as a convenient wrapper for OpenVPN. The program doesn't embed or replace the VPN—it simply launches openvpn.exe with the user-selected configuration.

Why C++?
Zero dependency on .NET or Java

Minimal executable size

Fast startup and low memory consumption

Native Windows process handling

Features
"Select Configuration" button — downloads the .ovpn file

"Clear" button — resets the configuration path

Connection/disconnection via system OpenVPN

Display connection log

System Requirements
Windows 7 / 8 / 10 / 11 (x86/x64)

OpenVPN (any version) — install from the official website

The path to openvpn.exe must be in the PATH (added during installation)

⚠️ Without OpenVPN pre-installed, the program will return an error and will not be able to connect.

Installation and Launch
Download MysteryVPNClient.zip

Unzip all files into one folder (relative paths are required for the C++ application to work)

Run VPNClient.exe

Click "Select Configuration" → select .ovpn

Click "Connect"

RU: 

MysteryVPN Client — это нативное Windows-приложение, написанное на C++ (WinAPI), которое служит удобной оболочкой для OpenVPN. Программа не встраивает VPN и не заменяет его — она просто запускает openvpn.exe с выбранным пользователем конфигом.

Почему C++?
Нулевая зависимость от .NET или Java

Минимальный размер исполняемого файла

Быстрый запуск и низкое потребление памяти

Нативная работа с процессами Windows

Функции
Кнопка «Выбрать конфиг» — загружает .ovpn файл

Кнопка «Очистить» — сбрасывает путь к конфигу

Подключение/отключение через системный OpenVPN

Отображение лога подключения

Системные требования
Windows 7 / 8 / 10 / 11 (x86/x64)

OpenVPN (любая версия) — установить с официального сайта

Путь к openvpn.exe должен быть в PATH (добавляется при установке)

⚠️ Без предустановленного OpenVPN программа выдаст ошибку и не сможет подключиться.

Установка и запуск
Скачай MysteryVPNClient.zip

Распакуй все файлы в одну папку (обязательное условие для работы C++ приложения — относительные пути)

Запусти VPNClient.exe

Нажми «Выбрать конфиг» → укажи .ovpn

Нажми «Подключиться»
