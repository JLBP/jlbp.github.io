# Division 2 Stat Overlay
Using [Tabwire/TheDivisionTab-API](https://github.com/Tabwire/TheDivisionTab-API) a unoffical api for The Division 2 and allows for 
This overlay will allow for stats like;
- Total Time
- PvE Level
- DZ Level
- Gear Score
- Specializations with Emblem 
- NPC Kills
- DZ Kills


*These are subject to change at anytime*
*Please repect Tabwire's API.* 
## Requirements
 - You will need a **Web Server** 
>  **xampp** - Own PC/Server
>  **Google Cloud** - Normally have $200 of free credit which last a year
>  **A Cheap VPS/Web Host** - Look around  *Nothing powerful is needed*

## Setup
 - **Your Player ID (PID)**;
    - Replace **[name]** with your **uplay**|**xbox**|**psn** and change platform  respectively name. Then navigate to the site.
 [https://thedivisiontab.com/api/search.php?name=[name]&platform=[platform]](https://thedivisiontab.com/api/search.php?name=[name]&platform=[platform])
     - Copy the PID string. Everything in the quotation marks 
> If jalp_ needed is pid he would go to;
> https://thedivisiontab.com/api/search.php?name=jalp_&platform=uplay
> - This returns **pid:  "9d73380d-5b69-40af-a8cc-a8bcf2417093"**...
> - You just need **"9d73380d-5b69-40af-a8cc-a8bcf2417093"**
 - With that copy and pasted, Open the config  folder and open **config.json**
 - Replace **[PID]** with the string you copied.
## Usage
 - Navigate to where ever you placed the file on your web directory
   **[Server ip]/d2stats** or **localhost/d2stats/**
   
Every 10 minutes the overlay will reach out to the API and check for updates before been displayed.

## To Doa
 - [ ] Easier to change stats via config file
 - [ ] Better layout/graphics
 - [ ] Animations - Using Greensock or Animate.css
 - [ ] PID gathered via entering uplay name (PC) in URL

> ## Affiliation
>    Division 2 Stat Overlay or TheDivisionTab API is in no way shape or form affiliated with Ubisoft and its partners. Any "The Division" name, logos and/or images are registered trademarks of Ubisoft.

