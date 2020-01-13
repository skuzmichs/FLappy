# Gra Flappy Bird.
1. Należy pobrać projekt z repozytorium.
2. Rozpakować pliki na komputerze.
3. otworzyć plik 'build', który w środowisku IJ otworzy cały projekt.
4. W pliku core/assets znajdują się resursy gry.
5. Zbudować projekt można na kilka sposoby:
a) tworzenie JAR:
IJ: File/Project Structure/Artifacts/Add/JAR/From modules with dependencies
Main clas: DesktopLauncher
nasisnąć Ok/Apply Ok
c.d: Build/Build Artifacts/Action Build
stworzy się folder out, w wewnętrzu którego można będzie znależć JAR.
można go otworzyć za pomocą Java Platform SE binary.
lub komendą w Windowsie: java -jar 'ścieżka do pliku'
b) IJ: Edit Configurations/Add New Configuration/Application
Main class: DesktopLauncher
Working directory: core/assets
Use class path of module: desktop
OK
RUN
