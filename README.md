# Igual Fabricante (Domainname: IgualFabricante)
Beschreibung vom Projekt.  
Das ist eine neue Zeile.  
Eine Auflistung kann wie folgt erstellt werden:  
+ **Schritt1:**
+ **Schritt2:**
+ **Schritt3:**  

Ein Programmabschnitt kann auch eingefügt wetrden. Dazu verwende folgende Syntax:  
```csharp
public class Person 
{
    public string Firstname {get; set;}
}
```

## Projektstruktur erstellen  
+ **Schritt 1**  
Projektname überlegen und mit diesen Namen eine `Solution` erstellen 
+ **Schritt 2**  
Eine Klassenbibliothek `Common Base` erstellen. In dieser Bibliothek werden alle Algorithmen, welche unabhängig vom Domainbereich sind gesammelt.
+ **Schritt 3**    
Eine Klassenbibliothek für die Schnittstellen anlegen. Der Projektname wird wie folgt definiert: [Domainname].Contracts. 
+ **Schritt 4**  
Eine Klassenbibliothek für die Geschäftslogik. In diesem Projekt werden alle Geschäftsprozess gesammelt. Projektname wird wie folgt definiert: [Domainname].Logic  
+ **Schritt 5**  
Erstellen einer Konsolenanwendung zum Testen der Struktur. Projektname wird wie folgt definiert: [Domainname].ConApp    
**Hinweis** Im weiteren Ausbau werden noch weitere Projekte hinzugefügt (z.B.: Rest-Service)
+ **Schritt 6**   
Abhängigkeiten definieren.