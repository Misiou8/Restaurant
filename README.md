# Restaurant Taste
 ASP.NET Project

Projekt strony restauracji(WIP)

Aplikacja Taste oferuje użytkownikowi możliwość zamawiania dań online. Aby tego dokonać, musisz najpierw założyć konto. Możesz zrobić to za pomocą konta Microsoft, Facebook lub tradycyjnie podając swoje dane. Po ukończeniu rejestracji możesz przejść do wyboru posiłku, na który obecnie masz ochotę. Jeżeli znajdziesz danie odpowiadające Twoim wymaganiom, dodaj je do koszyka, a następnie dokonaj zamówienia, a następnie opłać za pomocą swojej karty kredytowej. Po dokonaniu płatności pozostaje Ci tylko czekać na informację, że Twój posiłek jest gotowy do odbioru.


> SQLLocalDb create MSSQLLocalDB <br />
> SQLLocalDb start MSSQLLocalDB <br />
> SQLCmd -S "(localdb)\MSSQLLocalDB" <br />
> CREATE DATABASE [Taste]; <br />
> GO

W projekcie:

View > Server Explorer <br />
Connect to Database <br />
Server name: (localdb)\MSSQLLocalDB> <br />
Select or enter database name: Taste <br />
Test Connection > OK

Update bazy:
> Install-Package Microsoft.EntityFrameworkCore.Tools <br />
> Update-Database
