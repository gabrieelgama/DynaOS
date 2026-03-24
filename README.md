# DynaOS

DynaOS is a modern, flexible operating system designed to go beyond the traditional concept of a Linux distribution. It is built with a server-first philosophy while allowing seamless transformation into a full desktop environment when needed.

## Overview

DynaOS follows a simple idea: one system, multiple roles.

It can operate as a minimal and stable server, or as a complete desktop system with a customized user interface. The user decides how the system should behave, without needing to switch distributions or reinstall.

## Base System

DynaOS is built on top of Debian, providing:

- Long-term stability  
- Extensive package availability  
- Strong security and reliability  
- A solid foundation for both servers and desktops  

## Modes of Operation

DynaOS supports different usage modes:

- **Server Mode**: optimized for performance, low resource usage, and reliability  
- **Desktop Mode (DynaUI)**: a customized desktop experience based on Cinnamon  

The system can adapt dynamically depending on the user’s needs.

## Core Features

### System Management

- **dynaupdate**  
  A full system update mechanism based on ISO images. It allows system upgrades while preserving user data.

- **dynabackup / dyna-restore**  
  Backup and restore tools designed to work across different versions of DynaOS, ensuring data portability and resilience.

### Safety and Stability

- Protection against destructive commands  
- Improved shutdown process (`dynaoff`) to prevent filesystem corruption and boot issues  
- Recovery-oriented design  

### Custom Tools

- **dynafetch**  
  Displays system information with DynaOS branding  

- **dynahelp**  
  Lists available DynaOS commands  

- **Future feature: dynakup**  
  Planned kernel update system without requiring a reboot  

## Desktop Environment (DynaUI)

DynaUI is based on Cinnamon and heavily customized to provide:

- A modern and clean interface  
- A familiar workflow for users coming from Windows  
- Lightweight performance suitable for older hardware  
- Custom themes, icons, and branding  

## Cloud and Homelab Ready

DynaOS is designed for:

- Self-hosted services such as Nextcloud and web servers  
- API development and backend services  
- Homelab environments  
- Remote management and monitoring  

## Philosophy

DynaOS aims to be:

- Powerful like a server operating system  
- Simple like a desktop system  
- Flexible enough to adapt to any workflow  

## Goal

The goal of DynaOS is to create a unified operating system that eliminates the gap between server and desktop environments, giving users full control over how their system behaves.
