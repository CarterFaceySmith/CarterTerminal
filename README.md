# CarterTerminal
## A Simple Guide To Beautiful Cross-shell Supremacy
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

#### 1. [iTerm](https://iterm2.com/)
- Navigate to the above page, download it, use it, don't question it.

#### 2. Configuring The Codex
- Play around with your iTerm preferences, when prompted to change the default terminal to iTerm hit yes.
- Theme -> Minimal
- Go [here](https://github.com/sindresorhus/iterm2-snazzy) to download the 'Snazzy' iTerm theme
- Enter "npm install zsh-autosuggestions" and follow the prompts

#### 3. Change. That. Font.
- Navigate to [Nerd Fonts](https://www.nerdfonts.com/)
- Pick one ya like, download it and install it to your system
  - Unzip the folder, select all, right-click then hit 'Install'

#### 4. [Starship](https://github.com/starship/starship)
- Navigate to Starship's 'Step 1: Install' section linked above
- Follow their instructions, I didn't make this prompt

#### 5. Configure Starship
- Create a directory in your home folder named ".config"
- WIthin it, copy and paste the .toml file in this repo

## Additional Notes
### Not Ya Mumma's Homespun Terminal

#### [Gum](https://github.com/charmbracelet/gum)
I recently installed Gum for writing and displaying shell scripts, so far it has been a lovely little addition to the command line, very aesthetic, we love that round here.

#### [Glow](https://github.com/charmbracelet/glow)
Further, I recently installed Glow as well. I personally use a lot of markdown files for various things, rendering them in nano is fine but *this*? Well this is much nicer.

#### [Microsoft PowerToys](https://docs.microsoft.com/en-us/windows/powertoys/)
Disclaimer: Yeah alright, *teeeechnically* it's got nothing to do with the terminal aside from making it easier to launch, but I like it and this is my guide so bugger off.

This is bar none the biggest upgrade to my Windows workflow due to Run and FancyZones, if you're on Windows and don't have it you're mising out big time.

#### Misc. Nonsense
I changed my default command line terminal to nano because I'm not smart enough to use Vim or its' derivatives.
