# Day Night Cycle Unity Tutorial

This tutorial shows how to create an easily expandable day night cycle system in Unity.

## 1. Setup

First create an empty gameobject and call it `TimeController`, create a script on this object and call it the same.

Next create 2 directional lights, 1 to act as sunlight and the other moonlight.

Now open the lighting tab and set the active sun an your sunlight directional light.

Then create a TMPro object to act as the display for the clock and position to your liking.

## 2. Day Night Cycle Script

Open your `TimeController` script.

### Refrences

#### Public Variables

```.cs
    public float timeMultiplier;
    public float startHour;
    public TextMeshProUGUI timeText;
    public Light sunLight;
    public float sunriseHour;
    public float sunsetHour;
    public Color dayAmbientLight;
    public Color nightAmbientLight;
    public AnimationCurve lightChangeCurve;
    public float maxSunLightIntensity;
    public Light moonLight;
    public float maxMoonLightIntensity;
```

#### Private Variables

```.cs
    private DateTime currentTime;
    private TimeSpan sunriseTime;
    private TimeSpan sunsetTime;
```

### Start Function

### Update Function

### UpdateTimeOfDay Function

### RotateSun Function

### UpdateLightSettings Function

### CalculateTimeDifference Function

## 3. Finish Setup In Unity

Change the values of the script to your liking and make sure you assign the correct objects to the correct variables.

Now hit play and make sure you have no errors.