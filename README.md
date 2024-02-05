# Prework - *Colorful*

Submitted by: **Selam Mitike**

**Colorful** is an app that has a text box that allows users to answer the question above it. It also has a button below that changes the background color when clicked, the color choice is randomized.  

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] Users are see a screen with three labels and a button
- [x] Tapping the button changes the screen color to a random color
 
## Video Walkthrough
![codepath_prework](https://github.com/smitike/CodePath-Pre-Work/assets/122339212/0ee414e7-4d20-4a11-a3a6-8674bdac040c)

## App Brainstorming (Step 4)
Tik Tok:
  - Post view and profile view so we can see who viewed our video and profile
  - Saving videos and sounds
  - Watch history

Musi:
 - Recently added musics are organized in one section
 - Sleep Timer feature so the song playing stops after the specified time
 - Adding songs to favorite and/or to playlist

Instagram:
 - Like button for stories
 - QR codes to share profile and posts
 - Notes feature above messages for friends to see

I want to build an app to elevate students' productivity often lacking in existing tools. Even though there are several apps to track daily tasks and take notes, most apps are overwhelmingly organized or don't provide some tools to help us track habits. The Task and Assignment Tracker will be organized, allowing students to categorize assignments by courses, providing a clear view of deadlines. To combat distractions, the Study Timer, inspired by the Pomodoro technique, ensures focused study sessions. In the Note Taking Tool, notes are structured by courses for easy retrieval and review. The Collaborative Working Area functions as a dynamic to-do checklist for group assignments, offering seamless sharing capabilities via email. The Book Reading List and Recommendation feature not only lets users compile reading lists but also suggests relevant books, employing algorithms based on user preferences and academic focus.  For the Planner, integration with the Google Calendar API amalgamates assignment deadlines and events into a unified daily schedule, preventing oversights. Implementing these features requires backend system data organization, user authentication, and API integrations. Data organization and user authentication can be done utilizing Firebase ensuring the security of users' information. The book recommendation aspect presents interesting challenge, requiring a machine learning algorithm to provide personalized suggestions. While I may not have extensive experience in this domain, I am committed to seeking and utilizing available resources to gain the necessary knowledge. A clean UI with the help of Figma will tie together these features bringing an all-in-one platform for consistent and better productivity.

## Notes

I encountered two challenges while building the app. One issue was difficulty typing in the label boxes, and another was trouble connecting the UI elements to the logic. When I inserted three label boxes, all I could see were dots. Attempting to zoom out the boxes didn't seem to work, I could only zoom horizontally instead of vertically. In terms of UI and logic, I mistakenly connected the entire screen instead of just the button. Consequently, the screen changed colors during runtime, but clicking the button had no effect. I initially thought the problem might be related to the function's placement in the ViewController, so I attempted to move it, resulting in errors. Upon closer inspection, I realized the function's connection was declared as an IBOutlet instead of IBAction. This indicated that it wasn't properly linked to the button. After correcting the connection to IBAction and associating it specifically with the button, the issue was resolved, and the app functioned as intended.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
