# Desktop-Cleaner

Desktop Cleaner
Desktop Cleaner is a Python script designed to help organize and clean your desktop by automatically sorting files into designated folders based on their file types. This project helps maintain a tidy workspace, making it easier to find files and manage your desktop efficiently.

Features
Automatically moves image files to the Images folder.
Organizes document files into the Documents folder.
Sorts music files into the Music folder.
Collects video files in the Videos folder.
Groups miscellaneous files into a Misc folder.
Customizable file extensions and destination folders.
How It Works
The script scans your desktop for files and moves them into predefined folders based on their file types. You can customize the file extensions and target folders as needed.

Usage
Clone the Repository

sh
Copy code
git clone https://github.com/adityakukade32/Desktop-Cleaner.git
cd desktop-cleaner
Install Dependencies

sh
Copy code
pip install -r requirements.txt
Run the Script

sh
Copy code
python desktop_cleaner.py
Customization
You can customize the file types and their corresponding destination folders by editing the config.json file.

json  
Copy code
{
    "Images": ["jpg", "jpeg", "png", "gif"],
    "Documents": ["pdf", "docx", "txt"],
    "Music": ["mp3", "wav"],
    "Videos": ["mp4", "mkv"],
    "Misc": ["zip", "rar"]
}
Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

By using Desktop Cleaner, you can maintain an organized and clutter-free desktop, improving your productivity and efficiency.
