# Nemesis Project module documentation
This is the documentation for the official module list.
# Modules in production
## Execution modules
### NeoadaptiveHandler
NeoadaptiveHandler is our frontier execution module. It provides full integration with the Neo architecture while providing the same speed and accuracy as all our execution modules.  
Official benchmarks:  
```
Engine top KPS: 840 KPS (test was limited by hardware)  
Engine production KPS: not measurable  
Production reaction delay: <1 ms  
Ram usage lower limit: 2.0 MB  
Ram usage upper limit: 2.4 MB  
CPU utilization classification: Low  
```  
Further details:  
```
Production filename: NeoadaptiveHandler.exe  
Development filename: NeoadaptiveHandler.ahk  
Production branch: main  
Module class: default  
```  
Keybind associations:
- F6: Start/stop
- G: Cycle output inside slot (Neo-adaptive mode only)
- 1-4: Swap active slot
### CycleHandler
CycleHandler is our frontier execution module for legacy cycle mode, but kept up-to-date.  
Official benchmarks:
```
Engine top KPS: 840 KPS (test was limited by hardware)  
Engine production KPS: not measurable  
Production reaction delay: <1 ms  
Ram usage lower limit: 2.0 MB  
Ram usage upper limit: 2.2 MB  
CPU utilization classification: Low  
```
Further details:  
```
Production filename: Cycle.exe  
Development filename: Cycle.ahk  
Production branch: legacy  
Module class: optional  
```
Keybind associations:
- F6: Start/stop
- G: Cycle output
- 1-4: Swap active slot

## Interface and configuration modules
### NeoguiHandler
NeoguiHandler (also referred to as NeoGui) is the default configuration interface for the Neo architecture, with support to Legacy modules as well.
Official benchmarks:  
```
Ram usage lower limit: 2.2 MB  
Ram usage upper limit: 3.0 MB  
CPU utilization classification: Below medium  
```  
Further details:  
```
Production filename: NeoguieHandler.exe  
Development filename: NeoguiHandler.ahk  
Production branch: main  
Module class: default  
```  
Keybind associations:
- F5: Show/Hide GUI
- F8: Retrieve pixel color from set coordinates
- F9: Check current pixel color on set coordinates

## Utility modules
### MacroHandler
CycleHandler is our frontier execution module for legacy cycle mode, but kept up-to-date.  
Official benchmarks:  
```
Engine top KPS: not measured (over CPU threshold)  
Engine production KPS: not measured  
Production reaction delay: 1-150 ms (configurable)  
Ram usage lower limit: 2.0 MB  
Ram usage upper limit: 2.7 MB  
CPU utilization classification: Variable  
```
Further details:  
```
Production filename: MacroHandler.exe  
Development filename: MacroHandler.ahk  
Production branch: main  
Module class: default  
```  
Keybind associations:  
- F2: Start/stop
- F3: Show/Hide GUI
- 1-4: Swap active slot
- $C: Intercepted and managed separately for auto-extend or spam key functionality
- z y x v f r: Spam keys sending themselves (dependent on active slot)
- Mouse3 (Middle click / scrollwheel click): Toggle auto-extend
- XButton1: Flip screen macro (unstable)
- XButton2: Lagswitch key
# Legacy modules
## Interface and configuration modules
### GuiHandler
GuiHandler is the classic Nemesis Beta experience. Offers fewer features but everything fits on a single page.  
Official benchmarks:  
```
Ram usage lower limit: 2.0 MB  
Ram usage upper limit: 2.4 MB  
CPU utilization classification: Low  
```
Further details:  
```
Production filename: GuiHandler.exe  
Development filename: GuiHandler.ahk  
Production branch: legacy  
Module class: optional  
```
Keybind associations:
- F5: Show/Hide GUI
- F9: Check current pixel color on set coordinates
# In-Dev restricted modules
## Utility modules
### Nemesis Assistive Software Client
NASC is our latest project regarding Nemesis Project. Includes a test version of an AutoHotkey v2 module framework as it's language is v2 instead of v1.  
This module is currently not functional in production.  
There are no official benchmarks for NASC.  
Further details:  
```
Production filename: - 
Development filename: undisclosed  
Production branch: Dev  
Module class: optional  
```
Keybind associations: undisclosed
## Unmaintained modules
### Nemesis Minecraft Utility
Nemesis Minecraft Utility was a small project among the developers and the testers to create a macro utility for Minecraft PvP combat.  
This module is currently unmaintained and not functional in production.  
There are no official benchmarks for Nemesis Minecraft Utility.  
Further details:  
```
Production filename: - 
Development filename: MinecraftUtility.ahk  
Production branch: Dev  
Module class: optional  
```
Keybind associations:
- 1-9: change active slot
- Left mouse button: monitored for certain macros
- Right mouse button: monitored for certain macros
- other keybinds are undisclosed
