# Documents OCR API 

## Introduction

## Source Code

```Py
import requests
import json

def main():

    url = "https://netocr.com/api/recogliu.do"

    payload = {
	'img': '/9j',
    'key': 'M***********g',
    'secret': '3***********6',
    'typeId': '2',
    'format': 'json'
	}
    files=[

    ]
	headers = {}

    response = requests.request("POST", url, headers=headers, data=payload, files=files)

    print(response.text)

	if __name__ == '__main__':
	    main()
```
