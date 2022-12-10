# trpd1

https://stackoverflow.com/questions/72774371/how-to-compile-a-qt-program-without-qtcreator-on-windows
https://download.qt.io/archive/qt/5.14/5.14.2/


https://www.technewstoday.com/install-and-use-make-in-windows


https://robots.uc3m.es/installation-guides/install-boost.html

bootstrap.bat

.\b2 --build-type=complete

https://levelup.gitconnected.com/the-definite-guide-on-compiling-and-linking-boost-c-libraries-for-visual-studio-projects-c79464d7282d


https://aprentis.net/how-to-resolve-msbuild-is-not-recognized-as-internal-or-external-command-error/

cmake -G "Visual Studio 12 Win64" ..

cmake -G "Visual Studio 15 Win64" ..

cmake -G"Visual Studio 16 2019" ../


%ProgramFiles(x86)%\Microsoft Visual Studio\2019\Community\MSBuild\Current\Bin

cmake .. -G "Visual Studio 16 2019" -A x64 -DBOOST_LIBRARYDIR="c:\local\boost_1_73_0\lib64-msvc-14.2"

msbuild pitcoinX.sln /p:Configuration=Release /m
