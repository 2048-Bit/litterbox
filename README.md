Android-Log-Analyzer
A simple python script to analyze Android logs

Setup:

After you download the py script, modify the key_words to correspond to your app

app_marker_name = all or part of your app name - "com.example" key_word_agent = "a word contained in your agent logs" key_word_device = "a word contained in your device logs (if any)" key_word_anr = "a word contained in your anr logs"

If you're analyzing a single file, please make sure it's named according to the above convention.

How to Use:

I've configured the map.txt file for my app. It's detecting connectivity changes and app restarts (based on logs that my app prints). You can change the map.txt file to make the script search for whatever you want.

:

After you have modified the python script and map.txt, pass the file/directory/zipfile you wish to analyze as the argument

python androidloganalyzer.py "your file" > output.txt
