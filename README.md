# matrix-by-night
 is a [matrix.org](http://matrix.org) and [element.io](http://element.io) themed dynamic background for macOS.

# Apply the wallpaper
1. [Click here](https://github.com/langleyd/matrix-by-night/raw/main/matrixByNight.heic) to download the wallpaper
2. Move it to `~/Pictures` on macOS
3. In `System Preferences -> Desktop & Screen Saver -> Pictures` select `matrixByNight`

If you'd prefer to just use one of the images as your background you can find them in [Images](/Images)

Here's a sample of the individual pictures is cylces through(based on the sun's location relative to your location):

<img width="200" alt="sunrise" src="Images/sunrise.png?raw=true"> <img width="200" alt="midday" src="Images/midday.png?raw=true">
<img width="200" alt="sunset" src="Images/sunset.png?raw=true"> <img width="200" alt="nighttime" src="Images/nighttime.png?raw=true">
<img width="200" alt="midnight" src="Images/midnight.png?raw=true">

# Generate the wallpaper
1. Install [wallpaper](https://github.com/mczachurski/wallpapper)
2. Run:
```
wallpapper -i wallpapper-solar.json -o matrixByNight.heic
```
