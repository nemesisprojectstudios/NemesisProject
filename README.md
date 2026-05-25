# Nemesis Project
A modular macro launcher platform built entirely in raw AutoHotKey v1.1.37

## What is Nemesis Project about?
We started off as a simple macro for a Roblox game under the name ZxMacro, but eventually became a whole platform, built on transparency and honesty. We want to supply a platform for AHK developers to collaborate and work together on making their own macros or utilities
## What is Nemesis Project?
Nemesis by itself is a transparency-first macro launcher platform running a modular file-relay system. The system consists of one main script (which is Nemesis itself) and several modules.
## How does Nemesis work?
Nemesis uses a file-relay system to communicate with its modules. The main script itself reads the hotkey inputs and sends them over to the modules that require those specific keybinds and execute outputs. The modules themselves aren't able to read user input. Alongside hotkey information, Nemesis also uses an array of commands to control the modules.
## Why is there a login system if Nemesis is free?
We used to be a paid software, so we made quite a few additions to secure the script. Currently, Nemesis requires users to be registered into our public database before allowing them to use the platform. This will change in the future, when we make a proper login system
## What is this repository for then?
While we stay closed source, we will use this repositors as a source for our installer to clone from. Once we decide to go open-source, we'll publish all of our unobfuscated uncompiled code into this repository under the GNU Public License.
## How does Nemesis stay transparency-first while being closed source?
Initially, one would think transparency and closed-source are conflicting terms. We wish to change this approach. Nemesis itself sticks to its reputable past and avoids any sort of suspicious relations. Our main script and modules are carefully reviewed before published, ensuring that no malicious code is added. Our verification system works entirely locally and we use military-grade encryption for login data inside our database. Nothing leaves your device without your knowledge. Optional data is only sent with user consent. The only data we actively receive inside auth logs is your username, authorization hashes and login timestamp. Modules are also additionally validated to ensure that unauthorized modules aren't able to connect to our platform.
## What other projects does Nemesis Studios work on?
We have multiple open-source projects, both older and newer. Our current list consists of: **RemappX Indev** (keyboard remapping utility), **XORCrypt** (portable text encryptor tool) and **FileGovernor** (startup manager and launcher utility)
