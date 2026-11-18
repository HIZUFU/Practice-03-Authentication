# Практическая работа №2. Web API

Каталог производственных участков и оборудования. REST API и отдельный MVC-клиент: просмотр, поиск, фильтр по участку, добавление, изменение и удаление. Связь данных — один ко многим. Хранение в SQLite, документация в Swagger. База и примеры данных создаются при запуске.

Нужен .NET 10 SDK. В первом терминале:

```powershell
dotnet restore
dotnet run --project ProductCatalogApp.Api --launch-profile http
```

Во втором терминале:

```powershell
dotnet run --project ProductCatalogApp.Client --launch-profile http
```

Клиент: http://localhost:5034. Swagger: http://localhost:5100/swagger.
