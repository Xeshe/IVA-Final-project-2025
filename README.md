# IVA-Final-project-2025
Instructions on how to run the project
1. create the python virtual environment with typical command: python3 -m venv (env_folder_name)
2. activate the python virtual environemnt with command: (env_folder_name)/Scripts/activate
3. make sure the notebook has the kernel with (env_folder_name) selected 
4. get libraries and dependencies using command: pip freeze > requirements.txt
5. if any libraries are missing when trying to run just use pip install command on the library name
6. If the trained model and data is already stored in the folder, find markdown cell with text saying: "START RUNNING EVERYTHING FROM HERE IF YOU JUST WANT THE MAIN LOOP AND NO TRAINING/TUNING" and run all the cells below it except for the last cell
7. last cell is the main loop for running the program

Using the project:
1. when it starts to run and say recording, you can speak into the mic during that time
2. after recording ends it will attempt to transcribe the words in the voiceclip into text and classify the emotion with the wav2vec2 model
3. the LLM will then generate a response commenting on the emotion and will attempt to mention or use previous messages as context 
4. press the square/stop button on the cell to end the loop
