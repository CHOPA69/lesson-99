import requests
import flask
text=requests.get("https://www.youtube.com/").text

print(text)