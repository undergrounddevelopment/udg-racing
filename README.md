# udg-racing
NoPixel 4.0 Racing Tablet System Underground Developments

# UNDERGROUND  Developments  - RACING  System & tablet  System - by MR R
# https://discord.gg/undergrounddevelopments 

- Hello, first of all thank you for purchasing our script !
- Don't forget to configure the `shared/config.lua` file according to your server.
- Feel free to open a support ticket to resolve your problem/question. - UNDERGROUND Developments -
- u can change the ServerLogo from = '../images/mylogo.png',
- add the images inside the file invetory image to your inventory images 

# Add this items at your `qb-core/shared/items.lua`

```lua
racetablet            = { name = 'racetablet', label = 'racetablet', weight = 500, type = 'item', image = 'np_tablet.png', unique = true, useable = true, shouldClose = true, combinable = nil, description= 'Tablet' },
racechip         = { name = 'racechip', label = 'racechip', weight = 500, type = 'item', image = 'underground_chip.png', unique = true, useable = true, shouldClose = true, combinable = nil, description ="racechip" },
trackchip            = { name = 'trackchip', label = 'trackchip', weight = 500, type = 'item', image = 'track_chip.png', unique = true, useable = true, shouldClose = true, combinable = nil, description="trackchip" },

````
-- for UNDERGROUND store config (if u want )
{
        name = "Market",
        label = "Rob's Liqour",
        type = "normal",
        blip = false,
        blipSprite = 59,
        blipColor = 2,
        blipScale = 0.5,
        categories = {
            [1] = {
                name = "Genel",
                description = "racing tools ",
                items = {
                    {name = "racetablet", label = "Su", perPrice = 5000, description = "racing tablet "},
                    {name = "racechip", label = "Sandwich", perPrice = 5000, description = "racing chip"},
                    {name = "trackchip", label = "Zar 6", perPrice = 5000, description = "track chip"}
                    
                }
            },
        },
        pedHash = 'mp_m_shopkeep_01',
        scenario = 'WORLD_HUMAN_STAND_MOBILE',
        coords = {
            {ped = nil, coords = vector4(-1221.58, -908.15, 12.33, 35.49)},
        }
    },
----------------------------------------------------


# UNDERGROUND store Discord : https://discord.gg/undergrounddevelopments
# Copyright (c) 2024, UNDERGROUND Developments . All rights reserved.
