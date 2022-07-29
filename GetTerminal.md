# CarterTerminal
## A Simple Guide
Terminals *generally* suck, and look like shit to boot. Let's fix that and make them even *slightly* more fun to use by changing a few things.

Below are my guides to get the same terminal I use as of the date of this push, find your OS and have at it.

## Windows
### Preface
I really dislike Windows' terminal options, I use PowerShell somewhat reluctantly and much prefer the Linux-based terminal. The **_instant_** I find a way to do that seamlessly on my Windows system I will jump ship with a big 'ol smile on my face. 

That being said, we can still make the best of a bad situation.

### PowerShell, But Better

#### 1. WSL
- Open PowerShell as administrator<br>
- Enter: "wsl --install"

Further info can be found in the [official docs](https://docs.microsoft.com/en-us/windows/wsl/install)<br>

#### 2. Change. That. Font.
- Navigate to [Nerd Fonts](https://www.nerdfonts.com/)
- Pick one ya like, download it and install it to your system
  - Unzip the folder, select all, right-click then hit 'Install'

#### 3. [Starship](https://github.com/starship/starship)
- Navigate to Starship's 'Step 1: Install' section linked above
- Follow their instructions, I didn't make this prompt

#### 4. Configure Starship
- Create a directory in your home folder named ".config"
- WIthin it, copy and paste the .toml file in this repo

#### 5. Let's Think Creatively
- Open up your PowerShell however you like
- Open 'Properties'
  - Check all the boxes under the 'Edit Options' area
  - Set Font -> Size to 16
  - Set the font to whatever you installed above
  - Set Colors -> Screen Background to:
    - Red: 39
    - Green: 41
    - Blue: 53
  - Set Colors -> Opacity to 93
  - Set Terminal -> Cursor Shape to 'Vertical Bar' (If this setting could stay as what I set it to that'd be great *Windows*)
  
#### Congrats, You're Done


## Mac/Linux
### Now We're Cooking
iTerm2
iTerm2 config
Starship
Starship config
Font change
Colour change


## Additional Notes
### Not Ya Mumma's Homespun Terminal
General Notes etc etc

Gum
