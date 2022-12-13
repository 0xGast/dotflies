# ❄ Frostic

![image](https://user-images.githubusercontent.com/117211251/207260448-b0b7739c-1777-43d2-88e8-e6c9b3ace6b9.png)

# Applications
### Vscode / Discord / YouTube / Twitter/ Spotify / CMUS / Reddit / Netflix / Zoro.to

![image](https://user-images.githubusercontent.com/117211251/207262451-404a7401-4eac-40f9-95b2-f6a957a8e281.png)

![image](https://user-images.githubusercontent.com/117211251/207260736-3bfd55c4-994c-47ad-968c-3fa9007a2062.png)

![image](https://user-images.githubusercontent.com/117211251/207261176-f2454e40-279f-4b8a-ad02-db02616887d6.png)

![image](https://user-images.githubusercontent.com/117211251/207261375-4859dbb4-1694-4977-8903-7f1ec57e8172.png)

![image](https://user-images.githubusercontent.com/117211251/207261012-e6c7350d-f23c-4334-a2a3-fae2d4e87668.png)

![image](https://user-images.githubusercontent.com/117211251/207260846-3996db93-a62f-4573-bcbe-ecbe52cfa681.png)

![image](https://user-images.githubusercontent.com/117211251/207261284-b425900b-bcdf-4adf-b30a-855dd974ff56.png)

![image](https://user-images.githubusercontent.com/117211251/207261674-e2d6a5de-509d-4f14-8f77-5eeb51e4ef66.png)

![image](https://user-images.githubusercontent.com/117211251/207261722-d2b09d00-53c7-45d5-87a1-1babac494ab1.png)

1. Picom Fork ( Pijulius )
  
    * Installing Packages
    
    ```
    sudo apt install libxext-dev libxcb1-dev libxcb-damage0-dev libxcb-xfixes0-dev libxcb-shape0-dev libxcb-render-util0-dev libxcb-render0-dev libxcb-randr0-dev libxcb-composite0-dev libxcb-image0-dev libxcb-present-dev libxcb-xinerama0-dev libxcb-glx0-dev libpixman-1-dev libdbus-1-dev libconfig-dev libgl1-mesa-dev libpcre2-dev libpcre3-dev libevdev-dev uthash-dev libev-dev libx11-xcb-dev
    ```
    
    * Building
    
    ```
    git clone https://github.com/pijulius/picom
    cd picom
    git submodule update --init --recursive
    meson --buildtype=release . build
    ninja -C build
    ninja -C build install
    ```

2. Rice Firefox ( Manuall )
  
    * Enabling the Modules
   
      Firstly you need to visit `about:config` by puting it in your URL Bar and Clicking Enter. It will display a Popup with the message I accept the risk, click yes and then search for these but one at a time and set everything to **True** by double Clicking them!
      `toolkit.legacyUserProfileCustomizations.stylesheets` <br />
      `layers.acceleration.force-enabled`<br />
      `gfx.webrender.all`<br />
      `svg.context-properties.content.enabled`<br />
      <br />
      
    * Creating the Folder and Files
    
      You need to open Alacritty and execute `cd .mozilla/firefox/` then you can list the files by doing `ls`.
      After that you have to find the folder that has `.default-release` at the end of it and then cd inside it.
      If youre inside the profile Directory you can now execute `mkdir chrome && cd chrome` after that you can move the files from the [Firefox Files](https://github.com/FastShard/Shardic/tree/main/firefox) inside the chrome folder! When you're done close Firefox using ctrl + q!
      
# Contact Me

Twitter   - [@0xGast](https://twitter.com/0xGast)
| Github    - [@0xGast](https://github.com/0xGast)
| Tryhackme - [@0xGast](https://tryhackme.com/p/0xGast)
