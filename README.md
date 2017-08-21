# billSharing

Checkpoints:

Make static web page

Upload from static web page to Amazon S3 (you can put your S3 info into the web page to test it)

Create lambda that logs "Hello World" when you upload to S3

Make that lamda make a call to optical character recognition (ocr) api ex. https://www.google.com/search?client=ms-android-google&biw=412&bih=322&ei=VOCaWaWTEYHMmAGhgrLgBQ&q=optical+character+recognition+ocr+api&oq=optical+character+recognition+ocr+api&gs_l=mobile-gws-serp.3..0i22i30k1l3.146264.149624.0.150137.11.10.0.0.0.0.248.1671.0j8j1.9.0....0...1.1j4.64.mobile-gws-serp..4.7.1319...0j0i13k1j0i13i30k1j0i13i5i30k1j0i67k1j0i7i30k1j0i30k1j30i10k1.JqRUf0k1PI4

Make lamda receieve a response from ocr api

Make lambda process any errors

Create a managed elasticsearch or apache solr database ex. https://aws.amazon.com/elasticsearch-service/ or https://www.elastic.co/cloud (this is a demo, so whichever is cheaper)

Do first update to database manually (like via terminal or command line)

Do first search on database manually (like via terminal or command line)

Make lambda send text to database

Make lambda get and log response from database (success/failure)

