## Latihan ASP.Net 

### Goal
* Run ASP.Net di local
* Create web service API sederhana (todo)
* Lakukan unit test sederhana (todo)

### Settings
* Laptop Windows 10
* dotnet terinstall
* powershell terinstall

### How to run
1. Buka windows powershell dan ketik command berikut untuk create project baru:

`dotnet new webapp --output aspnetcoreapp --no-https`
![image](https://github.com/user-attachments/assets/9784d76a-c088-41f3-896a-16346661ea6d)

2. Run aplikasi, masuk ke folder aspnetcoreapp dan ketik command berikut
`dotnet run`
![image](https://github.com/user-attachments/assets/dbae783d-e8bc-4eef-aec7-b14c0bcb08be)

Hasil run di http://localhost:5071/
![image](https://github.com/user-attachments/assets/c0087ecf-87e5-489d-ab83-e062ea6a63e1)


3. Tambahkan preferensi lain misal: file .gitignore (barutau ternyata bisa di add dengan command berikut ini)
`dotnet new gitignore`
![image](https://github.com/user-attachments/assets/d5d3641e-15f5-4163-96e3-30bd0bf551b9)


masih ada todo, Bismillah, semangat

referensi: https://learn.microsoft.com/en-us/aspnet/core/getting-started/?view=aspnetcore-8.0
