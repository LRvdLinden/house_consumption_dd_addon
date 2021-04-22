<h1 align="center">House consumption - Dwains Dashboard Add-on (more_page)</h1> 


<p align="center">
  <a href="https://dwainscheeren.github.io/dwains-lovelace-dashboard/">
    <img src="https://img.shields.io/badge/Dwains%20Dashboard-Default-299ec2.svg" />
  </a>
  <a href="https://github.com/custom-components/hacs">
    <img src="https://img.shields.io/badge/HACS-Default-orange.svg" />
  </a>
  <a href="https://github.com/LRvdLinden/house_consumption_dd_addon">
    <img src="https://img.shields.io/github/v/release/LRvdLinden/house_consumption_dd_addon" />
  </a>
    <a href="https://github.com/LRvdLinden/">
    <img src="https://img.shields.io/github/followers/LRvdLinden?style=social" />
  </a>
    </a>
    <a href="https://discord.gg/7yt64uX">
    <img src="https://img.shields.io/discord/688401603811999885" />
  </a>
</p>
<p align="center">House consumption in Home Assistant Dwains Dashboard.</p>


<p align="center">Created by <a href="https://discord.gg/7yt64uX">Dwains Community</a>
</p> 


<p align="center">
  <img src="https://user-images.githubusercontent.com/77990847/115602989-e945bb00-a2df-11eb-8c6b-94f84898e3c3.png" />
</p>



## Prerequisite
---
- Make sure you have installed the lovelace [mini-graph-card](https://github.com/kalkih/mini-graph-card), [fontawesome icons](https://github.com/thomasloven/hass-fontawesome), and [Button Card](https://github.com/custom-cards/button-card). This can be done manually or directly via hacs.

<img width="320" alt="image" src="https://user-images.githubusercontent.com/77990847/115438802-1cb81500-a20e-11eb-92f5-02fc2154f570.png">


## Installation Add-on
---
- Copy the `house_consumption` folder in to the `dwains-dashboard/addons/more_page` directory.
- Open your `more_page.yaml` file in `dwains-dashboard/configs` and add the following;
```yaml
 - name: House consumption
   icon: fas:chart-line
   main_menu: 'true' #Show this addon in the main navigation bar!
   path: 'dwains-dashboard/addons/more_page/house_consumption/page.yaml'
```
- Reload the theme configuration via Theme Settings

## Replace the following
---
- If some `sensors` not showing after this manual, please add the correct `sensor` to monitor
- change camera `entities` in the `page.yaml` file


## Result
---
<p align="center">
  <img src="https://user-images.githubusercontent.com/77990847/115602989-e945bb00-a2df-11eb-8c6b-94f84898e3c3.png" />
</p>


---
Enjoy our house consumption? Help us out for a couple of :beers: or a :coffee:!

[![coffee](https://www.buymeacoffee.com/assets/img/custom_images/black_img.png)](https://www.buymeacoffee.com/LRvdLinden)
