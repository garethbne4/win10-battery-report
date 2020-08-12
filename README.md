https://au.pcmag.com/windows-10-1/62556/how-to-check-your-laptop-battery-health-in-windows-10 


Review Recent Usage 

In the Recent usage section, take note of each time the laptop ran on battery power or was attached to AC power. Every drain over the last three days is tracked in the Battery usage section. You can also get a full history of the battery's usage under the Usage history section.

 
Access Windows PowerShell 

The Battery Report is generated via Windows PowerShell. Press the Windows key and the X key and select Windows PowerShell (Admin) from the menu that appears. A pop-up window may ask for permission to make changes to your device; say yes.

 
View the Battery Report 

The report will outline the health of your laptop battery, how well it has been doing, and how much longer it might last. At the top of the Battery Report, you will see basic information about your computer, followed by the battery's specs.

 
How to Increase Your Laptop Battery Life 

Don't love what you see in your battery report? These easy tips will help you squeeze longer battery life out of your Windows 10 or Mac laptop.

 
Locate the Battery Report 

Open Windows File Explorer and access the Windows (C:) drive. There you should find the Battery Report saved as an HTML file, which will open in your web browser.

 
Battery Capacity History 

The Battery capacity history section shows how the capacity has changed over time. On the right is Design Capacity, or how much the battery was designed to handle. On the left, you can see the current full-charge capacity of your laptop's battery, which will likely decline over time the more you use your device.

 
Generate Battery Report in PowerShell 

A PowerShell command window will pop up. Type or paste powercfg /batteryreport /output "C:\battery-report.html" into the window and press Enter to run the command. It will tell you where the report has been saved on your computer. Close PowerShell.
