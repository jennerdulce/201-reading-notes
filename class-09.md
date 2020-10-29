## HTML
### Ch 7. Forms
- Basic form layout
```
<form method='post' or 'get>
  <fieldset>
    <legend>name of table</legend>
    <label for="name of input">
    <input type="select type" name="">
    <input type="submit" value="name of button">
  </fieldset>
</form>
```
- required="required"
  - form needs to be completed
- type=""
  - text
  - textarea
    `<textarea>Words inside box...</textarea>`
  - password
  - checkbox
    - name should be similar
    - i.e. used for ethnicity/nationality
    ```
    <input type="checkbox" name="category" value="pop"> Pop
    <input type="checkbox" name="category" value="rock"> Rock
    <input type="checkbox" name="category" value="rap"> Rap
    ```
  - radio
    - similar to checkbox, except should only have 1 choice. i.e. Gender
    ```
    <input type="radio" name="category" value="male"> Male
    <input type="radio" name="category" value="female"> Female
    ```
  - select
    - dropdown list box
    ```
    <select name="devices">
      <option value="iPod">
      <option value="Computer">
      <option value="Phone">
      <option value="None">
    </select>
    ```
  - file upload
    ```
    <input type="file" name="userUpload">
    <input type="submit" value="Upload">
    ```
  - date
    ```
    <label for="depart">Departure Date: </label>
    <input type="date" name="depart">
    <input type="submit" value="Submit">
    ```

### Ch 14. Lists, Tables, and Forms
- Basic form layout
```
<ul>
  <li></li>
  <li></li>
</ul>
```
```
<ol>
  <li></li>
  <li></li>
</ol>
```
- Basic table Layout
```
<table>
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th></th>
      <td></td>
      <td></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th></th>
      <td></td>
      <td></td>
    </tr>
  </tfoot>
</table>
```
- Basic form layout

## JavaScript
### Ch 6. Events
- Steps for handling events
1. Create HTML
2. Create Event Listener
  - `element.addEventListener('event', functionName)
3. Create function to be executed by Event Listener
```
function randomFunction(event){
  var x = event.target.name.value
}
```
- If you need to use paramaters
```
function randomFunction(event, parameter){
  var x = event.target.name.value
}

var parentElement = document.getElementById('id');
parentElement.addEventListener('event', function(event){
  randomFunction(event, argument);
});
```