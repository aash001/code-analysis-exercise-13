 # Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ----- | ------ |
|(Mary, Smith, 45)|{firstName: Mary lastName: Smith age: 45}| 
|(John, Smith, 47)|{firstName: John lastName: Smith age: 47}| 
|(Michael, Smith, 12)|{firstName: Michael lastName: Smith age: 12}| 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program list the function person with parameters of firstName, lastName, and age.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
