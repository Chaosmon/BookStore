# BookStore

### Project setup

```
Window + R

Search:
 cmd

Paste:
 git clone https://github.com/Chaosmon/BookStore.git
```
### DB setup
```
You need to reinstall the ConnectionStrings configuration in the appsettings.json file including:

1. Server

2. User Id (if User Id you not 'sa')

3. password

4. Navigate to `Tools` in the Visual Studio navbar
   Select `NuGet Package Manager` -> `Package Manager Console`.

3. In the console window, type `update-database`.
```
You need to have SQL Server Management Studio (SSMS) installed and a 'sa' account to perform this operation.
If you're not familiar with creating a 'sa' account in SSMS, refer to this link: 
[Guide to enabling the 'sa' account in SQL Server](https://qthang.net/huong-dan-bat-tai-khoan-sa-trong-sql-server).

### Run project
