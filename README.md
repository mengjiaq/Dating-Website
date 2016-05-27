# Dating-Website
Part 1: Web page content without style 

For part 1 of this assessment task, you need to assemble the components together in a web page (without style).  The result of part 1 will look like this when viewed in a browser.
Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-30%20at%2011.43.06%20PM.png


The result of this stage is a web page which contains a form. That is, after the various form elements are selected/data is entered, the submit button can be pressed. Although it is not an absolute requirement of this assessment task, it would be good if your form is sent to an appropriate server program after the submit button is selected. For this to work the data needs to be sent to a server using the post method with enctype="multipart/form-data". The destination program used in the instructional videos is http://ihome.ust.hk/~rossiter/cgi-bin/show_everything.php .

Here is a summary of the elements needed inside the web page.

At the top	

  An appropriate large heading e.g. h1 or h2 or h3
  The HTML elements to be contained within the form are listed by the company as follows.

- First fieldset, with legend ‘Your face’

  + ' input type="file" '[required]
  + ' An img element with id="preview" '
- Second fieldset, with legend ‘Your general details’

  + input type= "text" ... [required]
  + input type="radio" ... (two of these) [required]
  + input type="number" ... [required]
  + input type="date" ...
  + input type="color" ...
  + select , with 6 option , to handle ‘no selection’ plus 5 different countries 
  
- Third fieldset, with legend ‘Your indicators’

  + input type="range" min="0" max="100" ...
  + input type="range" min="0" max="100" ... 
- Fourth fieldset, with legend ‘Your Contact Information’

  + input type="email" ... [required]
  + input type="tel" ...
  + textarea ...
  + input type="checkbox" ... , three of these are needed for the three types of contact method 

- At the end (not in any fieldset):

  + input type="submit"
  + Important notes

Each of the four fieldset must have a legend, as indicated above.
** [required] ** shown in the list above means that the input must be entered by the user before the form can be successfully submitted, so you must indicate this by adding the appropriate text in the HTML i.e. required
For everything in the form except the submit button, there must be an appropriate label which has an appropriate for e.g. 

<label for="avatar">Your image:</label>
<input type="file" id="avatar" name="avatar" required>


You can see the text for each label from the designer’s image provided to you. Alternatively, you can use your own text, as long as it hasthe same meaning.
Every element which is used to provide data that gets sent to the server e.g. the input and textarea elements, need to have a name. They are sent to the server when the submit button is clicked. You are welcome to choose appropriate names. 
Where appropriate, add a break after each input i.e. <br> so the web page does not look cluttered.
Some of the input types such as input type="email" have not been introduced in previous instructional videos, but the meaning of this type of input is obvious. 
You may find one or two of the form elements are not supported in certain browsers. You are recommended to use the Chrome browser.
