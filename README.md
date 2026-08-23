**GroupDNA - The WhatsApp Chat Analyzer**

An honest and raw look into my hostel group chat.
This Python project analyzes a WhatsApp group chat export and generates a text-based dashboard with various statistics, including daily activity, longest silent streaks, top words, and automatically assigned personality archetypes for each participant.
Final Output Dashboard 📸
Here is a snapshot of the final output generated completely using Python logic, directly in the terminal: https://github.com/AbhayPSingh23/Group-DNA-Analyzer/blob/main/Group_DNA_Analyzer_Outputs.pngBuild

**Log & Process 🛠️**

**What I Allowed Myself to Use;**
Python core fundamentals (variables, dictionaries, sets, lists, loops, conditionals)
The "datetime" module (for time gap calculation)
"NumPy" (specifically for a 2D matrix for the activity heatmap)
Basic string parsing methods (split, strip, replace)

**What Was Strictly Forbidden;**
❌ "pandas" (no cocepts of DataFrame cheat codes here!).
❌ Data visualization libraries like "matplotlib", "seaborn", or "plotly" (the heatmap is 100% text-based!).
❌ External chat parsing libraries.
❌ Advance regex ( The `re` module).

**Respective Seven-Days Build Log;**
Day 1: Created the basic text parser. Handled system messages, media omitted placeholders, and deleted messages. Even tackled multi-line messages!

Day 2: Processed overall stats. Counted messages per person and total group active days.

Day 3: Calculated word frequency, stripped punctuation, and added a custom stop-words list to filter out boring conjunctions.

Day 4: Created a 6x24 `NumPy` matrix and rendered a pretty console heatmap with shading blocks.

Day 5: Used `datetime` to parse timestamps, calculated response times, and found the longest silent ghosting streaks.

Day 6: Designed a set of custom detection rules for 9 distinct archetypes and created an exclusive assignment system (the person with the highest normalized score gets the archetype).

Day 7: Polished the final output by using f-strings and box-drawing characters for the perfect terminal aesthetics.

**How to Run the Code;**
Make sure that you have Python 3(the latest version) installed in your system.
Install NumPy: "pip install numpy"
Export your WhatsApp chat (without media) as a `.txt` file.
Place the `.txt` file in the same directory as the notebook and update the file path in the code.
Run all cells in "GroupDNA\_Abhay\_DS17729.ipynb" top-to-bottom.
Check out your group's dashboard in the final cell output!
