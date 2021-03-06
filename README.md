# Flutter Currency Converter

### Description
This is a practice project inspired by the currency converter tutorial provided by Tutorials.EU. The original tutorial uses C#, WPF, and Microsoft SQL database on Windows, and can be found here: https://tutorials.eu/build-a-currency-converter-application-using-wpf-in-c-with-database/. I have adapted the project to use Dart, Flutter, and MySQL/Sqlite instead. The project can run on desktop and mobile. Web is not supported.

If you want to setup and run this project yourself, you will need to download and install Flutter for your platform per the documentation on https://Flutter.dev. Once complete, you will need to clone this repository as well as [Spark Lib](https://github.com/Cshooltz/spark_lib) into the same parent directory. The Currency Converter project expects the `spark_lib` folder to be in the same directory as itself. With all that done, you can run `flutter pub get` then `flutter run` to run the project in debug mode.

Also note, if you do run this project, it is currently configured to use my API key from https://openexchangerates.org/. If you plan on building and running the app a lot, for whatever reason, I recommend getting and using your own API key since each free tier key has limited uses per month.

### Source Code Layout
The bulk of the app's source code is located under [lib/app](lib/app). The app has two screens (or pages): One for the main converter interface and one for editing the database entries, which are located under [app/screens](lib/app/screens). The widget tree root is contained in [app/app.dart](lib/app/app.dart), which instantiates the top-level application widgets including the root MaterialApp.

### Screenshots
![Desktop Converter Screen](docs/screenshots/Converter%20screen.png)
![Desktop Converter Screen](docs/screenshots/Editor%20screen.png)
![Desktop Converter Screen](docs/screenshots/Mobile%20converter.png)
