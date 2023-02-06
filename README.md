# vimeo_search_python
searching videos by search terms on Vimeo
This is a simple piece of code, using the Requests library to get the page with search results on Vimeo.
It looks for the relevant information just by searching a string-object with the search page.
It loads the relavant info as a json object. 
Then from this json object, relevant data is taken. 

:::::::::EXAMPLE:::::

To search for Dolores Keane videos:

vimeo = vimeo_search()

print(vimeo.search_vimeo("Dolores Keane"))

Returns:
{'Dolores Keane - Where Have All The Flowers Gone ? ': {'url': 'https://vimeo.com/168592052', 'play_time': 388, 'date': '2016-05', 'channel': 'Rosie j. Russell', 'title': 'Dolores Keane - Where Have All The Flowers Gone ? '}, 'Thuas ag Cort an Chornain (trad.,Ireland) by Phalaïna Belgium ': {'url': 'https://vimeo.com/42935933', 'play_time': 193, 'date': '2012-05', 'channel': 'Phalaina Belgium', 'title': 'Thuas ag Cort an Chornain (trad.,Ireland) by Phalaïna Belgium '}, 'Phil Callery ': {'url': 'https://vimeo.com/38912665', 'play_time': 1163, 'date': '2012-03', 'channel': 'barry lynch', 'title': 'Phil Callery '}, 'Archived Webcast: Interlochen Arts Academy Choir Concert, 11-4-21 ': {'url': 'https://vimeo.com/637693017', 'play_time': 3936, 'date': '2021-10', 'channel': 'Interlochen Center-Arts', 'title': 'Archived Webcast: Interlochen Arts Academy Choir Concert, 11-4-21 '}}
