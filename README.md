# win-optimization-process

## Part 1: Scripts after new install

1. **Windows activation**: https://github.com/massgravel/Microsoft-Activation-Scripts <br>
    1.1. Activate Windows <br>
 
2. **Windows debloater**: https://github.com/ChrisTitusTech/winutil <br>
    1.1. **[Tweaks]** Select: Standard Tweaks, Disable Background Apps, Disable Fullscreen Optimizations, Disable Microsoft Copilot <br>
    1.2. **[Tweaks]** Run Tweaks <br>
    1.3. **[Tweaks]** Add and Activate Ultimate Performance Profile <br>
    
3. **Optimizer**: https://github.com/hellzerg/optimizer <br>
    1.1. **[General]** Select: Optimize Performance, Remove menus delay, Disable Office Telemetry, Disable Mozilla Firefox Telemetry, Disable Google Chrome Telemetry, Disable NVIDIA Telemetry, Disable Visual Studio Telemetry, Disable Telemetry Tasks, Disable Media Player Sharing <br>
    1.2. **[Windows 10]** Select: Disable My People, Disable Automatic Updates, Disable Telemetry Services, Disable Cortana, Disable News & Interests, Disable Start Menus Ads, Disable Edge Telemetry, Disable Edge Discover, Disable Xbox live, Disable Game Bar <br>


## Part 2: Softwares

1. **Process Lasso**: Performance profile - https://bitsum.com/ <br>
    1.1. **[Main]** Select: ProBalance Enabled, Performance Mode Enabled <br>

2. **ParkControl**: Unpark cores - https://bitsum.com/parkcontrol/ <br>
    1.1. **[CPU Settings]** Plugged In (AC) - Parking Off, Freq Scaling Off <br>

3. **ISLC** - Memory cleaner - https://www.wagnardsoft.com/forums/viewtopic.php?t=1256 <br>
    1.1. **Check**: Enable custom timer resolution <br>
    1.2. **Set**: Wanted timer resolution to 0.5 <br>
    1.3. **Click**: Start <br>

4. **MSI Afterburner** - GPU Control - https://www.msi.com/Landing/afterburner/graphics-cards

5. **DDU** - Remove old GPU drivers - https://www.guru3d.com/download/display-driver-uninstaller-download/

6. **LatencyMon** - Real time latency analysis - https://www.resplendence.com/downloads

7. **WhySoSlow** - Real time system diagnostics - https://www.resplendence.com/downloads

## Part 3: Commands

1. Timer Resolution: Use powershell with ADMIN rights <br>
- bcdedit /set useplatformtick yes <br>
- bcdedit /set disabledynamictick yes <br>
- bcdedit /deletevalue useplatformclock <br>
