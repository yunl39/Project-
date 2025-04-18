import requests

import json

import urllib.parse



token = "YOUR_TOKEN"

targetUrl = urllib.parse.quote("https://httpbin.co/anything")

url = "http://api.scrape.do/?token={}&url={}".format(token, targetUrl)

payload = json.dumps({

  "test-key": "test-value"

})

headers = {

  'Content-Type': 'application/json'

}

response = requests.request("POST", url, headers=headers, data=payload)

print(response.text)
