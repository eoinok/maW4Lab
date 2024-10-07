# Week 4 Lab - Build a GPA Calculator
The goals of this weeks lab are
- To process some simple information gathered from the user using Javascript
- To perform simple calculations in Javascript and report the result tot the user
- To use CSS to improve the appears of the app and the user's experince
- To use flexbox to so that app will have a responsive design and work well on different screen sizes

A students GPA on any given semester is calculated by dividing their accumulated total grade score by the total number
off possible credits they could have earned. The grade score for any given module is calculated by multipling the gradepoints 
for the grade achieved by the credits available for the module. If there are two modules SSWD and OB and the student gets an A 
in SSWD and a B in OB then the total grade score is 4.0x5 (20) + 3.0x5 (15) giving a total of 35. The GPA is calculated as 35/10 
as there were only 10 possible credits. So the GPA will be 3.5.

# Part 1
Take the starter code from App.js in the repo and make it work so that when the button is clicked, the message 
"this is the click me button" appears. Then translate the commented lines of code in the clickMe function into working Javascript
so that when the button is clicked the App will calculate the GPA for the student and output it to the screen using an alert.

# Part 2
Add the StyleSheet component to the list of components being imported at the top. Add the following block of code to your program.
Add it inside the App function but before the return statement.
```
const styles = StyleSheet.create({
  container: {

  },
  row: {

  },
  label: {

  },
  textInput: {

  }
});
```
To add these three styles to the relevant components - the outer view should get the style 'container'. Each of the inner views should
get the style 'row'. The labels and textInputs should get the other two appropriate styles. Hint - to add a style to a component add
```
style={style.mystyle}
```
as a prop inside the tag of the component.

