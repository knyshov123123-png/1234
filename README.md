# MyMauiApp

Краткий шаблон проекта .NET MAUI (Windows, Android, iOS). Сгенерировано автоматически. Измените название, пространство имен и настройки по необходимости.

Требования:
- .NET 8 SDK (или совместимая версия с MAUI)
- workloads: maui, android, ios, macos, windows
- Для сборки iOS требуется macOS и Apple Developer account

Быстрый старт:
```bash
# Клонируйте репозиторий
git clone https://github.com/knyshov123123-png/1234.git
cd 1234

# Перейдите в папку src и создайте проект локально, если нужно:
# (Если вы хотите использовать шаблон dotnet вместо файлов в репозитории)
dotnet new maui -n MyMauiApp -o src/MyMauiApp

# Или сборка из добавленных файлов:
cd src/MyMauiApp
dotnet restore
dotnet build -c Release
```

Структура (включено в репозитории):
- src/MyMauiApp/ - минимальный шаблон приложения (App.xaml, MainPage и т.д.)
- .github/workflows/ci.yml - пример сборки для Windows, Android и iOS (macOS runner)
- .gitignore - для .NET/VisualStudio

---