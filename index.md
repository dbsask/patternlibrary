[HTML Elements](./html-elements) | [About DSO](./about)

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

## Usage
* If signing in through Saskatchewan.ca Account, use data we have to speed up process.
* Use when the user has to choose among many options, where some are most likely to match the default values chosen by other users.
* Use when it is possible for the system to make qualified guesses regarding what the user might choose.
* Use when it seems a complicated task to fill out the form without the default: when the number of required choices hinders the user from finishing filling out a form.
* Do not use for input fields that are important for the user to think about. For instance for signing up to a newsletter or accepting the terms and agreements of a website.
