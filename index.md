####
import requests


response = requests.get("https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY")
print(response.status_code)

response = requests.get("https://api.nasa.gov/planetary/apod?api_key=IcJtHeyl4r2aLcbUcoNzA5zfZCM3tgu5dl54a05b")
print(response.json())

<img src="https://apod.nasa.gov/apod/image/2204/NGC3628-crop.jpg"    
         alt="image from Nasa <3"
         width=35%>

#### Markdown





