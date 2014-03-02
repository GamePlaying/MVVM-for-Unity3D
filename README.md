MVVM for Unity3D
================

Creating games with Unity3D and MVVM architecture !

## What is MVVM for Unity3D ?

MVVM for Unity3D is a tool that will help you to create your games/apps with the architectural pattern named M-V-VM (see paragraph below).
This tool intends to make developer life easier and to simplify the communication between developers and designers.

Images are better than words, so I let you see what it could offer you :

![MVVM in global](docs/images/mvvm.png MVVM in global)

![MVVM in global with injection](docs/images/mvvm-and-injection.png MVVM in global with injection)

![MVVM in C# with injection](docs/images/mvvm-in-code.png MVVM in C# with injection)

## What is MVVM ?

> The Model View ViewModel (MVVM) is an architectural pattern used in software engineering that originated from Microsoft. Largely based on the Model-View-Controller pattern (MVC), MVVM is a specific implementation targeted at UI development platforms which support the event-driven programming in Windows Presentation Foundation (WPF) and Silverlight on the .NET platforms. MVVM facilitates a clear separation of the development of the graphical user interface (either as markup language or GUI code) from the development of the business logic or back end logic known as the Model (also known as the data model to distinguish it from the view model). The ViewModel may also implement a mediator pattern organising access to the backend logic around the set of use cases supported by the View. MVVM was designed to make use of data binding functions in WPF to better facilitate the separation of view layer development from the rest of the pattern by removing virtually all GUI code ("code-behind") from the view layer. Instead of requiring user interface (UX) developers to write GUI code, they can use the framework markup language and create bindings to the ViewModel, which is written and maintained by application developers. This separation of roles allows interactive designers to focus on UX needs rather than programming of business logic, allowing for the layers of an application to be developed in multiple work streams for higher productivity. Even when a single developer works on the entire code base a proper separation of the View from the Model is more productive as the user interface typically changes frequently and late in the development cycle based on end-user feedback. - Wikipedia

## Why MVVM ?

So, MVVM helps you in this way :

* DRY (Don't Repeat Yourself)
    * create one, use everywhere
* KISS (Keep it simple, stupid)
    * produce less code but stay simple
* SOLID (Single responsibility, Open-closed, Liskov substitution, Interface segregation and Dependency inversion)
    * using Dependency Injection
* Separate concern
    * Developers create the game logic = MVVM Logic (View abstraction / ViewModel / Services / Model)
    * 2D / 3D Designers create the view = Graphics / 3D Model using Unity Editor

## Roadmap

Current version : X

### Main features

* Portable Model
* Portable (Abstract) ViewModel
* IoC Container - Dependency Injection
* Very useful and fluid GUI notification
* Battle system with ViewModel and Services

### Other optional features / extension

* Many services
    * Backend services (Windows Azure Mobile Services, etc..)
    * Networking Services (Photon Networking, etc...)
    * Samples services of existing battle system (FPS, RPG, etc...)
* Unit testing tool & TDD
* Service Locator = one service to control all of them
* Messenger = send messages between ViewModels
* Simplifying animation system