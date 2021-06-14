import requests

response=requests.get('https://www.flickr.com/services/rest/?method=flickr.photos.search&api_key=f7f17bc16912a06cc3948286551dbefa&tags=dogs&format=json&nojsoncallback=1&api_sig=7bef4b0767eedc4667666f01ba909fdb')
print(response.json())
print(response.status_code)
