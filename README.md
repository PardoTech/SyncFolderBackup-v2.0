SyncFolderBackup v2.0

<img width="1024" height="1536" alt="ChatGPT Image 17_08_2025, 17_23_47" src="https://github.com/user-attachments/assets/fa907801-5c2f-4256-9927-b9c5b615d8e3" />

 => Never lose your work – automatic backups while you create. <=

A lightweight C# utility that continuously monitors a source folder and keeps a replica folder updated. Perfect for quick file backups and folder synchronization.

[Download para Windows](https://github.com/PardoTech/SyncFolderBackup-v2.0/raw/main/SyncFolderBackupv2.0_win(x64).rar)
[Download para Linux](https://github.com/PardoTech/SyncFolderBackup-v2.0/raw/main/SyncFolderBackupv2.0_linux(x64).rar)
[Download para macOS](https://github.com/PardoTech/SyncFolderBackup-v2.0/raw/main/SyncFolderBackupv2.0_osx(x64).rar)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Features:

. Automatically synchronizes a source folder with a replica folder.

. Allows setting a check interval (in seconds).

. Simple console interface with hotkeys:
[c] Change folder paths or sync interval
[h] Show help and available commands
[q] Quit the program

. Automatically logs updates in LogsData.txt, tracking added or updated files.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ How It Works:

The user provides:
 - Source folder path
 - Replica folder path
 - Sync interval in seconds

. The program compares both folders and copies any new or updated files from the source to the replica.

. The loop continues until the user exits with q.

⚠️ Note: The program does not delete files from the replica that were removed from the source.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Requirements:
 - .NET SDK (>= 8.0)
 - Windows, Linux, or macOS (any system compatible with .NET 8)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Example Usage:
 - Source folder: C:\Users\Ricardo\Documents
 - Replica folder: D:\Backups\Docs
 - Interval: 30 seconds

The program keeps the replica folder synchronized with the source, logging all changes in LogsData.txt.
