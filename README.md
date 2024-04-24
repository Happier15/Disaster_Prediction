# Disaster-Prediction-Website
## Approach:
The disaster response phase, which follows the initial disaster management cycle, encompasses various crucial components such as warning dissemination, evacuation procedures, search and rescue operations, immediate aid provision, damage assessment, ongoing support, and prompt restoration efforts.

Within this framework, our focus has been on enhancing the flood warning system. We've developed a user-friendly interface accessible to the general public, enabling them to monitor future river water levels and receive notifications of potential flood risks within the next 12 months. Additionally, users can explore historical river flow data and visualize rainfall patterns within their respective Sub-Divisions.

By empowering individuals with this comprehensive information in advance, along with insights into potential flood occurrences, we aim to facilitate proactive preparation and community alertness, thereby minimizing potential losses.


# STEPS:
## CONNECTION TO HTML:
A user initiates a request for the root URL / of a domain to access its index page.
main.py associates the URL / with a Python function.
The Python function locates a web template residing in the templates/ directory.
A web template searches the static/ directory for any necessary images or CSS files while rendering to HTML.
The rendered HTML is returned to main.py.
main.py forwards the HTML to the browser for display.

## URL IN THE BROWSER AND BACKEND CONNECTION:
Initially, we imported the Flask class and the render_template function.
Following that, we instantiated a new object of the Flask class.
Subsequently, we associated the URL / with the index() function. Henceforth, upon accessing this URL, the index() function will be executed.
The index() function utilizes the Flask function render_template() to present the index.html template, recently created in the templates/ directory, to the browser.
Lastly, we employ the run() method to launch our application on a local server. Additionally, we enable the debug mode to facilitate the viewing of relevant error messages and enable automatic reloading of the local server following code modifications.
Upon visiting http://127.0.0.1:5000/, main.py contained code that linked the URL / to the Python function index().
The index() function located the web template index.html in the templates/ directory, converted it into HTML, and dispatched it back to the browser, resulting in the displayed screen.
