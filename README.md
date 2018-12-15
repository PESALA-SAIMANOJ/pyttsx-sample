# pyttsx-sample
offline  voice assistant


import pyttsx3

engine=pyttsx3.init()
rate=engine.getProperty("rate")

engine.setProperty("rate",125)


engine.say("hello sam")
engine.say("you are too late!")
engine.say("wow!")

engine.runAndWait()








