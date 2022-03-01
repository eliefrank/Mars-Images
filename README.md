[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6554518&assignment_repo_type=AssignmentRepo)
# ex3-Mars Images
Access site for NASA's Mars image database.
The site allows:
1. Search images.
2. Save photos to a favorites list and view the list in the carousel.

First the program obtains data on the various tasks.
Only after obtaining all the required data we will activate the search button in form (it disabled button).
If the data is not obtained, an error message will be displayed instead of the page.

The search by: date (in Earth date or sol date format), task selection, camera selection.
After validation of the input, A REST API request is sent to a NASA server upon user input.
The result will be displayed to the user in "search results".
If there are pictures each picture will be displayed inside a card with details and a save button.
If there are no pictures, the user will be notified that there are no pictures.
If the request fails, the user will be notified that the request failed.

When saving an image the image will be displayed in the list of saved images.
If the image is already saved, a message will be displayed.
In addition you can activate and stop a carousel that displays the saved images.

Other notes:
There are functions that can be written as anonymous functions but for order in the code I wrote them as regular functions.


<h1>Elie Frankenhuis</h1>
<p>Email: eliezerfr@edu.hac.ac.il</p>

<h1>Execution</h1>
<p>
The submission is a WebStorm project that can be run directly from the IDE.
</p>
<h1>Assumptions</h1>
<p>
  The site use bootstap CDN therefore assumes an internet connection is available.
</p>