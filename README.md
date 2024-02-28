# Contract-App
Aplication to add and managment contracts 

**BAZA DANYCH**

TABELA UŻYTKOWNIKÓW
Id: int auto increment
Username: string
First Name: string
Last Name: string
Phone number: int
Birthda : Date
City: string
Street: string
Email: string
Email Verification: bool
Date creation account: Date
Date expired account: Date
Active: bool
Avatar_path: string
TABELA KONTRAKTÓW
Id: int
Contract number : int autoincrement
Contract status: string / int
Contract type: string
Contract notes: string
Responsible person fname:string
Responsible person lname:string
Responsible person email:string
Date start: Date
Date creation:Date
Date expired:Date
Documents_path:string
Company code: int
TABELA FIRM ZEWNETRZNYCH
Id:int
Company code: int
Company name: string
Company responsible persone fname: string
Company responsible persone lname: string
Company responsible persone ename: string

**BACKEND**
CRUD.
Obsługa zapisu plików z dokumentami.
Obsługa zapisu awatarów.


**FRONTEND**
Logowanie/resetowanie hasła
Rejestracja
Filtrowanie kontraktów
CRUD
Uzupełnianie profilu.
Tworzenie kontraktu i modyfikacja oraz usuwanie.
Przeglądanie kontraktów i wyświetlanie szczegółów danego kontraktu.
