# Voice_Assist

speech recognition for speech to text
pttsx3 for text to speech
datetime for time date
webbrowser for opening urls or websites
Wikipedia for Wikipedia
requests for api handling
tkinter for gui
threading - to make sure that the gui is responsive even while the voice assistant is processing the commands


def initialize_engine - gets and sets properties of engine like voice and rate using pytts(text to speech) (in voices 1 is for female & 0 is for male)

def speak - says the text and waits OR for speaking

def listening - {for listening and recognizing speech

listen :
set microphone as source
print listening
listen through the microphone and store it in a variable called audio

recognize: (try except)
try [print recognizing
recognize speech using google api and store it in a variable called query
print query]
except [unknownvalueerror = print(sorry did not understand)]

}


def tell_time - fetch time from datetime in format 12hrs and store it in a variable called now
print now
speak now

def tell_date - fetch date from datetime in format (month day year) and store it in a variable called today
print today
speak today


def open_browser - speak ("opening" + url) 
open url/website using webbrowser

def search_wikipedia - fetch 2sentences from the summary of topic using Wikipedia and store it in a variable called result
print result
speak result

def get_weather - fetch weather using request(data handling) & weather api (postman for api management/ generating base url)
store weather in variables
print weather using variables
speak weather using variables

def run_assistant - responsible for the working of voice assistant
call function initialize_engine() in a variable called engine
while loop (condition - true(runs infinitely))
inside while loop, call above defined function using if elif conditional statements 





FUNCTIONS: [

time in 12hr format

date in format(month day year)

open website

Wikipedia

weather temperature in Celsius up to 2 decimal places, humidity, description

]
