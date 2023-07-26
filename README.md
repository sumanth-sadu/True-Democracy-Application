# True-Democracy-Application
# True-Democracy
<p>It as an Django based web application based on politics in india</p>
<p>The whole concept of this website is based on a single word "accountability".</p>
<p>It is a political website for people.
our intention is to make the government accountable or answerable to every step
they make.</p>
<p>At present it is only concerned with Andhra pradesh state(A state in India).</p>
<p>As we know the state is divided into 175 constituencies and it is difficult for people to
approach the head of the constituency (which is the seating mla) for every trouble
they have.</p>
<p>It is equally important for the Mla(government official) to know the problems faced by individuals in their
ruling area. so our website bridges the gap between the people and government to
present their issues and actions respectively.</p>
<p>In our website one can request or register a complaint (after proper authentication) to the political officials of state government namely MLA's on their problems in their area based on given tag's( like water,women security, etc..)</p>
<p>Based on the requests which are taken(pincodes included from gps),are shown in a graph format for better visualization to governemt officials.</p>
<p>The problems can then be reviewed by officials and can mark them as solved.</p>
<p>One can view the activeness of an government official towards the people</p>

## Tech Stacks Used
- Use Python 3.5
- Django 2.1.1
- Boot Strap 4.0.0
- Chart.js
- TensorFlow 2.0
- 2factor
- requests
- geopy
- pillow

## Highlights
- Implemented a profinity check model with Tensorflow to asess the profinity of user submitted complaint
- With chart.js we implemented the graphs to show the number of problems in an a constituency under that constituency representative page thus making it easy
- Scraped the details of MLA's and Bills from official websites using Requests and Bs4
- Desined 3 logos for our website using Blender
- Implemented a search query to return all the queries regarding a problem
- Gave power for MLA to mark the complaints solve, and then stored in database and represented in a graph form so that people can track him/her
- Phone number verification is done with help of 2factor authentication api
- With location info collected from user and eith geopy one can register a complaint when he is with in 2km range of area in which he is going to register the complaint
## Some Snippets
![]
