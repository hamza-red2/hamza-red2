import googlemaps

# Replace 'YOUR_API_KEY' with your actual API key
gmaps = googlemaps.Client(key='YOUR_API_KEY')

# Geocoding an address
geocode_result = gmaps.geocode('1600 Amphitheatre Parkway, Mountain View, CA')

print(geocode_result)

