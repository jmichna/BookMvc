# BookMvc
Aby uruchomić projekt trzeba zmienić scieżkę bazy danych na porpawną w appsettings.json oraz wykonać kommendę: dotnet ef database update z terminala dla części Infrastracture. Wrazie potrzeby przeprowadzenia ponownej migracji należy od komentować linijki 18,19,20 oraz 21 w pliku SqlDbContext, oraz zakomentować linijki 14,15,16 oraz 17. Po owej migracji należy wrócić do porzedniego ustawienia.
Przykładowe dane logowania:
Admin: Login: admin@example.com Hasło: Admin123!
User: Login: user@example.com Hasło: User123!
