# Rendering the Routes

Your eccentric friend Emily has really been making progress on her first Flask app! However, she still hasn't quite gotten the hang of using the power of Jinja to create flexible templates. She's been too busy with clients! And those costumes don't make themselves.

She still isn't sure how to take a page already written in HTML and render it in her routes. Neither has she gotten around to learning how to use Jinja variables and control structures to render elements in pages dynamically. In the meantime, she's been making her pages by previewing the HTML pages individually.

You would be happy to help, but you don't want to do everything, you've got your own business to take care of. You say you'll get her off to a good start by getting her dog costumes rendered on the page.

___

## Instructions

In this lab, you are tasked with
    1. rendering templates within routes in Flask, and
    2. using Jinja variable placeholders and control structures to dynamically show dog costumes and their descriptions

**Remember to create and use a separate Python virtual environment for each lab.** You'll be glad you did. :)

### 1. Rendering Templates

Emily gave it a better shot with the routes, but then started working on HTML pages and previewing them manually. She wants to replace the old route text with the new templates, but didn't quite get that far. Have the routes render the corresponding templates directly.

1. `welcome()` route should render the `index.html` template
2. `services()` route should render the `services.html` template
3. `costumes()` route should render the `costumes.html` template

### 2. Template Variable Placeholders

Emily has already given you list of costumes she wants displayed on the page, in the `costumes()` route in `app.py`. She's also provided an example of how she wants each costume to look in the page, in `templates/costumes.html`.

Your task is to take that list of costumes and display each in the template using Jinja. Your changes for this task will almost exclusively be in the `costumes.html` template. Take your time to understand how to display one costume using Jinja placeholders and control structures. Then, try to display all the costumes using as few lines of Jinja magic as you can. What kind of control structures would help you do that?

Hint: Displaying the image for each costume might be a little tricky. Your editor's syntax highlighting/coloring might not help you in this case.
