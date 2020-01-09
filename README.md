# Igual Fabricante (Domainname: IgualFabricante)
Beschreibung vom Projekt.  
Das ist eine neue Zeile.  
Eine Auflistung kann wie folgt erstellt werden:  
+ **Schritt1:**
+ **Schritt2:**
+ **Schritt3:**  

Ein Programmabschnitt kann auch eingef�gt wetrden. Dazu verwende folgende Syntax:  
```csharp
public class Person 
{
    public string Firstname {get; set;}
}
```

## Projektstruktur erstellen  
+ **Schritt 1**  
Projektname �berlegen und mit diesen Namen eine `Solution` erstellen 
+ **Schritt 2**  
Eine Klassenbibliothek `Common Base` erstellen. In dieser Bibliothek werden alle Algorithmen, welche unabh�ngig vom Domainbereich sind gesammelt.
+ **Schritt 3**    
Eine Klassenbibliothek f�r die Schnittstellen anlegen. Der Projektname wird wie folgt definiert: [Domainname].Contracts. 
+ **Schritt 4**  
Eine Klassenbibliothek f�r die Gesch�ftslogik. In diesem Projekt werden alle Gesch�ftsprozess gesammelt. Projektname wird wie folgt definiert: [Domainname].Logic  
+ **Schritt 5**  
Erstellen einer Konsolenanwendung zum Testen der Struktur. Projektname wird wie folgt definiert: [Domainname].ConApp    
**Hinweis** Im weiteren Ausbau werden noch weitere Projekte hinzugef�gt (z.B.: Rest-Service)
+ **Schritt 6**   
Abh�ngigkeiten definieren.