# YouTube Video Manager
A simple, interactive command-line application to manage your collection of YouTube videos! 📺
Add, view, update, and delete video entries—easy, right from your terminal.

🚀 Features
📋 List all your saved YouTube videos.

➕ Add a new video by providing its name and duration.

✏️ Update details for any existing video.

❌ Delete videos you no longer want to track.

💾 Persistent storage using a simple text file (youtube.txt).

🛠️ Installation
1. Clone this repo:
    git clone https://github.com/yourusername/youtube-manager.git
    cd youtube-manager

2. (Optional) Create a Virtual Environment:
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

3. No third-party requirements!
    This project uses only Python's built-in libraries.

📦 Usage
Make sure you have Python 3.10+ (for the match-case syntax).

Run the Application:

python youtube_manager.py

You'll see a menu:

Youtube Manager | choose an option
1. List all youtube videos
2. Add a youtube video
3. Update a youtube video details
4. Delete a youtube video
5. Exit the app

👩💻 Just enter your choice & follow the prompts!

💡 Example Workflow

Enter Your Choice: 1

**********************************************************************
List of Videos:

**********************************************************************

Enter Your Choice: 2
Enter Video Name: Learn Python
Enter Video time: 15 Mins

Enter Your Choice: 1

**********************************************************************
List of Videos:

1. Name: Learn Python, Duration: 15 Mins

**********************************************************************

Enter Your Choice: 5

🗂️ File Structure
youtube_manager.py      # Main application file
youtube.txt    # Data storage (auto-created)
README.md               # This file

📝 Notes
Data is stored in /content/youtube.txt as a JSON array.

If the file does not exist, it will be created automatically.

All actions are immediately saved to file.

✨ Customization
Easily change the data fields stored per video (add URL, description, etc.)

Adapt the script for your needs!

📑 License
This project is licensed under the MIT License.

Made with ❤️ in Python. Happy managing your YouTube learning playlist!