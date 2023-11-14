# PrototypeDbConnector
This project is a working base, a prototype for a db connector in c#.

## Prerequisit

You need a MySql database engine. Version 8 or higher.

* Download and execute the model proposed [here](https://www.mysqltutorial.org/mysql-sample-database.aspx).

## Setup

* Clone the repo
* Build
* Run the program (this is a console app)
* Result expected

```
103 - Atelier graphique
112 - Signal Gift Stores
114 - Australian Collectors, Co.
119 - La Rochelle Gifts
121 - Baane Mini Imports
124 - Mini Gifts Distributors Ltd.
125 - Havel & Zbyszek Co
128 - Blauer See Auto, Co.
129 - Mini Wheels Co.
131 - Land of Toys Inc.
141 - Euro+ Shopping Channel
144 - Volvo Model Replicas, Co
145 - Danish Wholesale Imports
146 - Saveley & Henriot, Co.
148 - Dragon Souveniers, Ltd.
```

## To add MySql to your own project

For your project, you will need to add manually the MySql Package.

Tools->Nuget Packet Manager->Package Manager Console

```
[INPUT]
PM> Install-Package MySQL.Data
Restoring packages for C:\Users\nicolas.glassey\MyDevs\CPNV\CFC\226\ProjPoo\PrototypeDbConnector\PrototypeDbConnector.csproj...
Installing NuGet package MySQL.Data 8.2.0.
Generating MSBuild file C:\Users\nicolas.glassey\MyDevs\CPNV\CFC\226\ProjPoo\PrototypeDbConnector\obj\PrototypeDbConnector.csproj.nuget.g.targets.
Writing assets file to disk. Path: C:\Users\nicolas.glassey\MyDevs\CPNV\CFC\226\ProjPoo\PrototypeDbConnector\obj\project.assets.json
Restored C:\Users\nicolas.glassey\MyDevs\CPNV\CFC\226\ProjPoo\PrototypeDbConnector\PrototypeDbConnector.csproj (in 1.11 sec).
[...]
Successfully installed 'ZstdSharp.Port 0.7.1' to PrototypeDbConnector
Executing nuget actions took 743 ms
Time Elapsed: 00:00:02.8070762
