# The-idea-of-a-plan
A study plan generator for academics
The idea is to take away the effort of planing, allowing users to spend more time focused on learning and optimizing their learning efficiency
Ideally an tool that can be part of a larger learning omnibus

Planned Features:
* repository for assignments and upcoming tests in order to keep deadlines in focus
* Project breakdown into subtasks
* Input estimates for times manually
* AI estimations for assignments that estimates the time it takes to do an assignment (based on previous performance/inputs)
* Dropdown defaults for time estimates (easy, medium, hard)
* Time to catchup on skipped lectures
* Alternative mode for self learners (self study with no teacher providing deadlines) will generate deadlines for you to keep you challenged
* Leitner system implemented for spaced repetition. 
* Connects to Google Calendar to perform two way communication, allowing study times to be scheduled into your calendar while avoiding busy times
* Option to enable flow work, blocking off 90 minute sessions
* Option to enable pomodoro with variable timing, blocking off 25 minute sessions with 5 minute breaks
* Option to enable spaced repetition, attempting to space work sessions for the same subject to boost retention
* OpenAI or other LLM premium mode, takes api key and asks to be fed tokens, uses LLM to enhance project breakdown and scheduling

Prereqs:
* install the Google client library for Python:
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
*