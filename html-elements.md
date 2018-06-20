---
layout: sask
gostitle: HTML Elements
---
Saskatchewan.ca Elements

1. Layout

1.1. Grid

1.2. Spacing & Gutters

1.3. Desktop

1.4. Tablet

1.5. Mobile


References
- http://www.saskatchewan.ca/government/visual-identity-and-protocol/digital-standards-and-framework/developers-building-blocks/front-end-code-standards-and-framework/grid-system 
- http://govuk-elements.herokuapp.com/layout/ 

2.	Typography

2.1.	Font
2.2.	Heading
2.3.	Body
2.4.	Link
2.5.	Caption
2.6.	 Block quote
2.7.	Bold
2.8.	Italic 

References
-	http://www.saskatchewan.ca/government/visual-identity-and-protocol/digital-standards-and-framework/developers-building-blocks/style-guide/typography 
3.	Color

3.1.	Color Pallette
3.2.	Use of Color (text, links, navigation, buttons..)
3.3.	Color Contrast

References
-	http://www.saskatchewan.ca/government/visual-identity-and-protocol/digital-standards-and-framework/developers-building-blocks/style-guide/colour-palette
-	http://www.saskatchewan.ca/government/visual-identity-and-protocol/digital-standards-and-framework/developers-building-blocks/style-guide/ui-colours 
4.	Icons

4.1.	Use of icons
4.2.	Font Awesome

References
-	http://www.saskatchewan.ca/government/visual-identity-and-protocol/digital-standards-and-framework/developers-building-blocks/style-guide/iconography 
-	https://www.nngroup.com/videos/icon-usability/ 
5.	Images

5.1.	Composition
5.2.	Tone
5.3.	Ratio

References
-	https://www.saskatchewan.ca/government/visual-identity-and-protocol/digital-standards-and-framework/sitecore-publishing/photography 
6.	Form elements
6.1.	Labels
6.2.	Hint Text
6.3.	Input Fields
6.4.	Text Areas
6.5.	Optional and Required Fields
6.6.	 Spacing
6.7.	 Select Boxes
6.8.	 Radio Buttons
6.9.	 Fieldsets
6.10.	Check boxes
6.11.	Buttons

References
-	smb://mstore/ITOGroup/DSU/Common/Program Management/Digital Standards/Digital Standards and Framework/Design Pattern Library/Saskatchewan Elements.rp
7.	Error & Validation Handling
8.	Progress Tracker
9.	Feedback Bar
10.	Header & Footer




<p>The purpose of this HTML is to help determine what default settings are with CSS and to make sure that all possible HTML Elements are included in this HTML so as to not miss any possible Elements when designing a site.</p>
<hr>
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
<h2 id="paragraph">Paragraph</h2>
<p>Lorem ipsum dolor sit amet, <a href="#" title="test link">test link</a> adipiscing elit. Nullam dignissim convallis est. Quisque aliquam. Donec faucibus. Nunc iaculis suscipit dui. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.</p>
<p>Lorem ipsum dolor sit amet, <em>emphasis</em> consectetuer adipiscing elit. Nullam dignissim convallis est. Quisque aliquam. Donec faucibus. Nunc iaculis suscipit dui. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.</p>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
<h2 id="buttons">Buttons</h2>
<button type="button" class="btn">Basic</button><br>
<button type="button" class="btn btn-default">Default</button><br>
<button type="button" class="btn btn-primary">Primary</button><br>
<button type="button" class="btn btn-success">Success</button><br>
<button type="button" class="btn btn-info">Info</button><br>
<button type="button" class="btn btn-warning">Warning</button><br>
<button type="button" class="btn btn-danger">Danger</button><br>
<button type="button" class="btn btn-link">Link</button><br>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
<h2 id="list_types">List Types</h2>
<h3>Definition List</h3>
<dl>
<dt>Definition List Title</dt>
<dd>This is a definition list division.</dd>
</dl>
<h3>Ordered List</h3>
<ol>
<li>List Item 1</li>
<li>List Item 2</li>
<li>List Item 3</li>
</ol>
<h3>Unordered List</h3>
<ul>
<li>List Item 1</li>
<li>List Item 2</li>
<li>List Item 3</li>
</ul>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
<h2 id="form_elements">Forms</h2>
<fieldset>
<legend>Legend</legend>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Nullam dignissim convallis est. Quisque aliquam. Donec faucibus. Nunc iaculis suscipit dui. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.</p>
<form lpformnum="1">
<h2>Form Element</h2>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Nullam dignissim convallis est. Quisque aliquam. Donec faucibus. Nunc iaculis suscipit dui.</p>
<p><label for="text_field">Text Field:</label><br>
		<input type="text" id="text_field" autocomplete="off"></p>
<p><label for="text_area">Text Area:</label><br>
		<textarea id="text_area"></textarea></p>
<p><label for="select_element">Select Element:</label><br>
			<select name="select_element">
			<optgroup label="Option Group 1"><option value="1">Option 1</option><option value="2">Option 2</option><option value="3">Option 3</option></optgroup>
			<optgroup label="Option Group 2"><option value="1">Option 1</option><option value="2">Option 2</option><option value="3">Option 3</option></optgroup>
		</select></p>
<p><label for="radio_buttons">Radio Buttons:</label></p>
<p>			<input type="radio" class="radio" name="radio_button" value="radio_1"> Radio 1<br>
				<input type="radio" class="radio" name="radio_button" value="radio_2"> Radio 2<br>
				<input type="radio" class="radio" name="radio_button" value="radio_3"> Radio 3
		</p>
<p><label for="checkboxes">Checkboxes:</label></p>
<p>			<input type="checkbox" class="checkbox" name="checkboxes" value="check_1"> Radio 1<br>
				<input type="checkbox" class="checkbox" name="checkboxes" value="check_2"> Radio 2<br>
				<input type="checkbox" class="checkbox" name="checkboxes" value="check_3"> Radio 3
		</p>
<p><label for="password">Password:</label></p>
<p>			<input type="password" class="password" name="password" autocomplete="off">
		</p>
<p><label for="file">File Input:</label><br>
			<input type="file" class="file" name="file">
		</p>
<p><input class="button" type="reset" value="Clear"> <input class="button" type="submit" value="Submit">
		</p>
<p></p></form>
</fieldset>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
<h2 id="tables">Tables</h2>
<table cellspacing="0" cellpadding="0">
<tbody><tr>
<th>Table Header 1</th>
<th>Table Header 2</th>
<th>Table Header 3</th>
</tr>
<tr>
<td>Division 1</td>
<td>Division 2</td>
<td>Division 3</td>
</tr>
<tr class="even">
<td>Division 1</td>
<td>Division 2</td>
<td>Division 3</td>
</tr>
<tr>
<td>Division 1</td>
<td>Division 2</td>
<td>Division 3</td>
</tr>
</tbody></table>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
<h2 id="misc">Misc Stuff – abbr, acronym, pre, code, sub, sup, etc.</h2>
<p>Lorem <sup>superscript</sup> dolor <sub>subscript</sub> amet, consectetuer adipiscing elit. Nullam dignissim convallis est. Quisque aliquam. <cite>cite</cite>. Nunc iaculis suscipit dui. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. <acronym title="National Basketball Association">NBA</acronym> Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.  <abbr title="Avenue">AVE</abbr></p>
<pre><p>
Lorem ipsum dolor sit amet,
 consectetuer adipiscing elit.
 Nullam dignissim convallis est.
 Quisque aliquam. Donec faucibus. 
Nunc iaculis suscipit dui. 
Nam sit amet sem. 
Aliquam libero nisi, imperdiet at,
 tincidunt nec, gravida vehicula,
 nisl. 
Praesent mattis, massa quis 
luctus fermentum, turpis mi 
volutpat justo, eu volutpat 
enim diam eget metus. 
Maecenas ornare tortor. 
Donec sed tellus eget sapien
 fringilla nonummy. 
<acronym title="National Basketball Association">NBA</acronym> 
Mauris a ante. Suspendisse
 quam sem, consequat at, 
commodo vitae, feugiat in, 
nunc. Morbi imperdiet augue
 quis tellus.  
<abbr title="Avenue">AVE</abbr></p></pre>
<blockquote><p>
	“This stylesheet is going to help so freaking much.” <br>-Blockquote
</p></blockquote>
<hr>
<p style="text-align: right;"><a href="#top">top</a></p>
