# PPM Frontend-Anwendung

Eine moderne, plattformübergreifende mobile Anwendung, entwickelt mit .NET MAUI, die professionelle Mobile-Development-Praktiken und Clean-Architecture-Prinzipien auf Basis des MVVM-Architekturmusters demonstriert.

## 🚀 Features

- **Plattformübergreifende Unterstützung**: Entwickelt für Android, iOS und Windows mit .NET MAUI
- **Modernes UI/UX**: Benutzerdefinierte Komponenten mit responsiven Layouts
- **Rollenbasierter Zugriff**: Mehrstufige Benutzer-Authentifizierung (Admin, SuperAdmin)
- **Dashboard-Analysen**: Interaktive Diagramme und Statistiken mit LiveChartsCore
- **PDF-Erstellung**: Dokumentenverarbeitung mit iText7
- **Theme-Unterstützung**: Mehrere Design-Themes mit dynamischem Wechsel
- **Benutzerdefinierte Steuerelemente**: Wiederverwendbare UI-Komponenten nach dem MVVM-Muster
- **Sichere Authentifizierung**: Robustes Login- und Registrierungssystem
- **Profilverwaltung**: Anpassung und Verwaltung von Benutzerprofilen
- **Arbeitsverwaltung**: Erstellen und Verwalten von Arbeitseinträgen
- **Abrechnungssystem**: Integrierte Rechnungs- und Zahlungsverwaltung

## 🛠️ Technologiestack

- **Framework**: .NET MAUI 8.0
- **Architektur**: MVVM (Model-View-ViewModel)
- **UI-Komponenten**: 
  - CommunityToolkit.Maui
  - UraniumUI.Material
  - Custom XAML controls
- **Datenvisualisierung**: LiveChartsCore.SkiaSharpView
- **PDF-Verarbeitung**: iText7
- **Zustandsverwaltung**: CommunityToolkit.Mvvm
- **Styling**: Benutzerdefinierte Themes mit dynamischem Ressourcenmanagement

## 📱 Unterstützte Plattformen

- Android (API Level 21+)
- iOS (11.0+)
- Windows 10 (10.0.17763.0+)
- MacCatalyst (13.1+)

## 🏗️ Projektstruktur

```
ppm-fe/
├── Controls/        # Benutzerdefinierte UI-Steuerelemente
├── Models/          # Datenmodelle
├── ViewModels/      # ViewModels für MVVM
├── Views/           # UI-Seiten und Layouts
├── Services/        # Geschäftslogik und Dienste
├── Resources/       # Bilder, Schriftarten und Themes
├── Helpers/         # Hilfsklassen
└── Extensions/      # Erweiterungsmethoden
```

## 🚀 Erste Schritte

1. Repository klonen
2. Sicher stellen, dass folgende Voraussetzungen erfüllt sind:
   - .NET 8.0 SDK
   - Visual Studio 2022 with MAUI workload
   - Plattformabhängige Entwicklungstools (Android SDK, Xcode, etc.)

3. Anwendung builden und starten:
   ```bash
   dotnet build
   dotnet run
   ```

## 💡 Umsetzung der Hauptfunktionen

- **Benutzerdefinierte Steuerelemente**: Implementierung wiederverwendbarer UI-Komponenten wie `LabeledEntry`, `CustomButton`, und `EditableLabel`
- **Theme-Verwaltung**: Dynamisches Wechseln zwischen verschiedenen Farbschemata
- **Datenvisualisierung**: Interaktive Diagramme und Grafiken zur Datenanalyse
- **PDF-Erstellung**: Dokumentenerstellung und -bearbeitung mit iText7
- **Responsives Design**: Anpassungsfähige Layouts für verschiedene Bildschirmgrößen und -ausrichtungen

## 🔒 Sicherheitsfunktionen

- Sicheres Authentifizierungssystem
- Rollenbasierte Zugriffskontrolle
- Passwortverschlüsselung
- Sichere Datenübertragung

## 📦 Abhängigkeiten (Dependencies)

- CommunityToolkit.Maui (9.0.3)
- CommunityToolkit.Mvvm (8.2.2)
- itext7 (8.0.5)
- LiveChartsCore.SkiaSharpView.Maui (2.0.0-rc4.5)
- UraniumUI.Material (2.9.1)

---

Mit ❤️ entwickelt mit .NET MAUI
