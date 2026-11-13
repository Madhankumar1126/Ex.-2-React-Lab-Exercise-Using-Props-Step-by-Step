# Ex.-2-React-Lab-Exercise-Using-Props-Step-by-Step
## Name: Madhan Kumar J
## Roll no: 2305001016
## Department: CSE

## AIM
### To create a React application that demonstrates how to pass data from a parent component to a child component using Props.

## PROGRAM
### i) App.jsx
```py
import Employee from "./Employee";
function App() {
return (
<div>
<h1>Employee Information</h1>
<Employee
name="Madhan Kumar J"
id="101"
department="CSE"
designation="Software Developer"
/>
<Employee
name="Tamil"
id="102"
department="IT"
designation="Web Developer"
/>
<Employee
name="Kumar"
id="103"
department="AIDS"
designation="Data Analyst"
/>
</div>
);
}
export default App;
```
## OUTPUT
<img width="1715" height="917" alt="Dark-Themed Employee Information Page" src="https://github.com/user-attachments/assets/e08cf2ff-8697-487e-8733-ac746409d01d" />


## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
