# SamsungNotes to Github

## The Idea

<!-- 
import os
import glob
import requests
from github3 import login

def move_samsung_notes_to_github():
    # Path to Samsung Notes folder
    samsung_notes_folder = '/path/to/samsung/notes/folder'
    
    # Initialize GitHub client
    gh = login(token=os.environ['GITHUB_TOKEN'])

    # Get the target repository
    repo = gh.repository('username', 'repo-name')

    # Iterate through each note file in the Samsung Notes folder
    for filename in glob.glob(os.path.join(samsung_notes_folder, '*.txt')):
        # Read the content of the note
        with open(filename, 'r', encoding='utf-8') as file:
            content = file.read()
        
        # Get the relative path of the file within the Samsung Notes folder
        rel_path = os.path.relpath(filename, samsung_notes_folder)
        
        # Create a new file in the repository
        repo.create_file(rel_path, f'Exported from Samsung Notes: {os.path.basename(filename)}', content)

    print("All notes moved successfully!")

if __name__ == "__main__":
    move_samsung_notes_to_github()

-->
