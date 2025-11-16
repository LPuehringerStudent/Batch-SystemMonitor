# Simple System Monitor (Batch Script)

This is a basic, single-file Windows batch script (`.bat`) for quickly checking essential system health metrics in the command line. It uses the **Windows Management Instrumentation Command-line (WMIC)** utility to fetch real-time data.

## Features

* **Real-time Metrics:** Displays current **CPU Load Percentage**, available physical memory, and total memory.

* **Disk Status:** Shows the size and free space for all detected logical drives.

* **Auto-Refresh:** Clears the screen and updates the metrics whenever any key is pressed.

* **Lightweight:** Requires no external dependencies, running entirely via native Windows tools.

## How to Use

1. Save the provided code into a file named **`monitor.bat`**.

2. Double-click the file to run the script, or execute it directly from the Command Prompt:

   ```
   monitor.bat
   ```

3. The system metrics will display immediately.

4. **Press any key** to refresh the data.

5. Press **`Q`** (or `q`) and then `Enter` to exit the monitoring loop.

## Notes

* This script requires a Windows operating system with WMIC enabled.

* The output format is raw text from the WMIC commands, which is fast but not highly graphical.
