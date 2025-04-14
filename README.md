# Breeze Cursors for Windows

## Preview

### Breeze Cursors from KDE Plasma 5

![](https://raw.githubusercontent.com/KDE/breeze/refs/heads/Plasma/5.18/cursors/Breeze/src/cursors.svg)

![](Assets/Breeze.png)
![](Assets/Breeze%20Snow.png)

### Breeze Cursors from KDE Plasma 6

![](Assets/Breeze%206.png)
![](Assets/Breeze%206%20Light.png)

## Installation

1. Clone the GitHub repo or download it as `*.zip`.  
    ![](Assets/Download%20ZIP.png)
2. Extract the contents of the `*.zip` archive.
3. Navigate into one of the folders: `Breeze`, `Breeze_Snow`, `Breeze6`, `Breeze6_Light`.
3. Right-click the `*.inf` file and select Install.  
    ![](Assets/Install%20inf.png)
4. Open `Control Panel` → `Hardware and Sound` → `Mouse`.
    - Alternatively, press `Win`+`R`, enter `main.cpl`, and press `Enter`:  
      ![](Assets/Run%20Dialog.png)
5. Under the `Pointer` tab, select your prefered Breeze variant and click Apply.

## How it was made

- Install [win2xcur](https://pypi.org/project/win2xcur/): `pipx install win2xcur` (requires ImageMagick)
- Clone [KDE/breeze](https://github.com/KDE/breeze)
- Navigate to `breeze/cursors/Breeze/Breeze/cursors`
- Convert everything with win2xcur
  - Run in bash: `mkdir ../cursors-win && x2wincur --output-dir ../cursors-win *`
- Place a `*.inf` file in our `cursors-win` folder.
- Win!

## See also
- https://invent.kde.org/plasma/breeze
  - KDE Plasma 6:
    - https://github.com/KDE/breeze/tree/master/cursors/Breeze
    - https://github.com/KDE/breeze/tree/master/cursors/Breeze_Light
  - KDE Plasma 5:
    - https://github.com/KDE/breeze/tree/Plasma/5.18/cursors/Breeze
    - https://github.com/KDE/breeze/tree/Plasma/5.18/cursors/Breeze_Snow
- https://github.com/quantum5/win2xcur#readme
- https://github.com/black7375/Breeze-Cursors-for-Windows
