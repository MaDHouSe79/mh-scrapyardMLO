<p align="center">
    <img width="140" src="https://icons.iconarchive.com/icons/iconarchive/red-orb-alphabet/128/Letter-M-icon.png" />  
    <h1 align="center">Hi 👋, I'm MaDHouSe</h1>
    <h3 align="center">A passionate allround developer </h3>    
</p>
<p align="center">
  <a href="https://github.com/MaDHouSe79/mh-scrapyardMLO/issues">
    <img src="https://img.shields.io/github/issues/MaDHouSe79/mh-scrapyardMLO"/> 
  </a>
  <a href="https://github.com/MaDHouSe79/mh-scrapyardMLO/watchers">
    <img src="https://img.shields.io/github/watchers/MaDHouSe79/mh-scrapyardMLO"/> 
  </a> 
  <a href="https://github.com/MaDHouSe79/mh-scrapyardMLO/network/members">
    <img src="https://img.shields.io/github/forks/MaDHouSe79/mh-scrapyardMLO"/> 
  </a>  
  <a href="https://github.com/MaDHouSe79/mh-scrapyardMLO/stargazers">
    <img src="https://img.shields.io/github/stars/MaDHouSe79/mh-scrapyardMLO"/> 
  </a>
  <a href="https://github.com/MaDHouSe79/mh-scrapyardMLO/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/MaDHouSe79/mh-scrapyardMLO?color=black"/> 
  </a>  
</p>

<p align="center">
  <img alig src="https://github-profile-trophy.vercel.app/?username=MaDHouSe79&margin-w=15&column=6" />
</p>

<p align="center">
<img alig src="https://raw.githubusercontent.com/kamranahmedse/driver.js/master/demo/images/split.png" />
</p>

## MY Scrapyard MLO 
- This is my first ymap that i made.
- I know that the spray booth loses his colors in the evening/night but I don't know how to solve this.
- If you know how i can fix that, please let my know.

i created this ymap for my mh-carlift that is also available [here](https://github.com/MaDHouSe79/mh-carlift)

### Screenshot
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20151815.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20151856.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20151929.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152012.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152120.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152150.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152229.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152255.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152320.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152347.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152415.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152443.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152522.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152813.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152904.png)
![foto](https://www.madirc.nl/fivem/scrapyardMLO/Schermafbeelding%202022-11-10%20152947.png)

<p align="center">
<img alig src="https://raw.githubusercontent.com/kamranahmedse/driver.js/master/demo/images/split.png" />
</p>

### IF you have my scrapyard mlo then use this for qb-doorlocks so you lock the gates
-- just change the job name
```lua
-- gate1 created by MaDHouSe
-- gate1 created by MaDHouSe
Config.DoorList['Scrapyard-gate1'] = {
    pickable = true,
    doors = {
        {objName = -768731720, objYaw = 249.52587890625, objCoords = vec3(2386.989258, 3125.980225, 48.316544)},
        {objName = -419676332, objYaw = 70.624954223633, objCoords = vec3(2383.785156, 3117.284912, 48.316544)}
    },
    doorLabel = 'gate1',
    authorizedJobs = { ['scrapyard'] = 0 },
    locked = true,
    doorType = 'double',
    doorRate = 1.0,
    distance = 10,
}

-- gate2 created by MaDHouSe
Config.DoorList['Scrapyard-gate2'] = {
    pickable = true,
    doors = {
        {objName = -768731720, objYaw = 249.89984130859, objCoords = vec3(2383.708984, 3117.118896, 48.316544)},
        {objName = -768731720, objYaw = 71.293762207031, objCoords = vec3(2379.629883, 3105.638428, 48.316544)}
    },
    doorLabel = 'gate2',
    authorizedJobs = { ['scrapyard'] = 0 },
    locked = true,
    doorType = 'double',
    doorRate = 1.0,
    distance = 10,
}

-- gate3 created by MaDHouSe
Config.DoorList['Scrapyard-gate3'] = {
    pickable = true,
    doors = {
        {objName = -768731720, objYaw = 268.43069458008, objCoords = vec3(2435.224609, 3116.781006, 48.316544)},
        {objName = -768731720, objYaw = 89.824485778809, objCoords = vec3(2435.158203, 3104.599365, 48.316544)}
    },
    doorLabel = 'gate3',
    authorizedJobs = { ['scrapyard'] = 0 },
    locked = true,
    doorType = 'double',
    doorRate = 1.0,
    distance = 10,
}

-- haloutgate created by MaDHouSe
Config.DoorList['scrapyard-haloutgate'] = {
    fixText = false,
    objName = -1483471451,
    doorType = 'sliding',
    locked = true,
    objYaw = 259.20663452148,
    objCoords = vec3(2362.751953, 3129.694092, 47.231808),
    distance = 5,
    doorRate = 1.0,
    pickable = true,
    doorLabel = 'haloutgate',
    authorizedJobs = { ['scrapyard'] = 0 },
}

-- halingate created by MaDHouSe
Config.DoorList['scrapyard-halingate'] = {
    fixText = false,
    objName = -1483471451,
    doorType = 'sliding',
    locked = true,
    objYaw = 259.14694213867,
    objCoords = vec3(2338.730469, 3133.779053, 47.221008),
    distance = 5,
    doorRate = 1.0,
    pickable = true,
    doorLabel = 'halingate',
    authorizedJobs = { ['scrapyard'] = 0 },
}
```

<p align="center">
<img alig src="https://raw.githubusercontent.com/kamranahmedse/driver.js/master/demo/images/split.png" />
</p>

### 🙈 Youtube & Discord
- [Youtube](https://www.youtube.com/@MaDHouSe79)
- [Discord](https://discord.gg/cEMSeE9dgS)


# LICENSE
[GPL LICENSE](./LICENSE)<br />
&copy; [MaDHouSe79](https://www.youtube.com/@MaDHouSe79)

