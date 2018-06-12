[Design Patterns](./) | [HTML Elements](./html-elements) | [About DSO](./about)

# Design Patterns
<h1 class="page-header" id="forms">Forms</h1>
## Good Defaults
*Problem summary*

The user needs to enter data into the system, where some input values are most likely to match default values.

*Example*
<form role="form">
  <div class="form-group">
    <label for="exampleName">Name</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Derek Barnes">
  </div>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="derek.barnes@gov.sk.ca">
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>

### Usage
* If signing in through Saskatchewan.ca Account, use data we have to speed up process.
* Use when the user has to choose among many options, where some are most likely to match the default values chosen by other users.
* Use when it is possible for the system to make qualified guesses regarding what the user might choose.
* Use when it seems a complicated task to fill out the form without the default: when the number of required choices hinders the user from finishing filling out a form.
* Do not use for input fields that are important for the user to think about. For instance for signing up to a newsletter or accepting the terms and agreements of a website.

### Solution
Pre-fill form fields with best guesses at what the user wants.

Drop down boxes and text fields are prefilled or preselected with reasonable default values. The default values are intelligent guesses as to what the user would possibly select.

When appropriate, reduce the cognitive load on users by pre-filling forms with default values. Use contextual information to make intelligent guesses as to what the user would most likely select. Do so only when you are reasonably sure your users would agree with your default values – otherwise, you will create extra work. Pre-filling controls to your own benefit rather than your users’ will most often backfire.

### Rationale
By providing default values in often complex forms with many choices, you save the user from the hassle of selecting all the relevant choices. Filling out a long form can sometimes be enough reason for the user to go somewhere else, where the process is easier.

The default values might not be right, but at least you provided the user with an example that he can change with as much effort as he would have put in if there was no example.

[http://ui-patterns.com/patterns/GoodDefaults](http://ui-patterns.com/patterns/GoodDefaults)

<hr>

## Input Prompt
*Problem summary*

The user needs to enter data into the system

*Example*
<form role="form">
  <div class="form-group">
    <label for="exampleName">Name</label>
    <textarea class="form-control" rows="3">Put your comments here. Begin by explaining your issue with...</textarea>
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>

### Usage
* Use when the label of an input field does not fully explain what should be filled into it or when using such a label feels like over-explaining the interface.
* Use when an example text or question answers what should be filled into an input field just as well as a label.
* Use when you want to save the space that a label otherwise takes up.
* Use in combination with a label, to further explain what kind of input is needed.

### Solution
An input field is pre-filled with example text or a question that prompts the user with what to do or type.

The Input Prompt pattern is most successfully used with dropdown lists and text fields. As dropdown lists have a fixed set of choices, words like Select or Choose are used for prompts. For text fields, the prompting string often begins with a call to action: Enter, Type, Search. End the string with the noun the input is describing, for instance Enter city or Enter an address.

Text fields use the Input Prompt pattern combined with scripting to remove the prompt text from a field, when the user’s focus is set. Once the user enters the input field to type in content, the prompting text is removed and replaced with nothing so that the input field is free for the user to fill out.

### Rationale
When a user fills out a form it is most often with the purpose of filling it out as quickly as possible to get on with the service offered. This is why the user often just scans through form fields and labels without giving the labels much of a glance. By using input prompts, immediate attention is drawn to what the user needs to fill in. The user can’t miss it. Although you must beware of removing labels entirely, as the input prompt is removed once focus has been set to the text field.

Input prompt is often used for small forms that are key to the core functionality of a site as inserting the label inside the text field itself helps save space. For more elaborate forms, there is often more than enough room available to explain each input field.

<hr>
