# Cliniserve Engineering Recruiting Test

Thank you for your interest in working at Cliniserve and taking your time to take our engineering recruiting test! Before you get started, please read the below instructions carefully.

## Submitting
In order for your submission to be considered, please make sure to submit both your code as well as the `additional_questions.md` file extended with your answers to the questions.

Please package your application code and the `additional_questions.md` file into a single zip file with your name in it before sending it to us.

**Please exclude local build artifacts (anything you would normally include in .gitignore) from your submission**

## Coding Test

### Introduction

At Cliniserve, we help care institutions manage care personnel resource scarcity. The Covid-19 pandemic has in many cases put care managers under even more pressure, as they have had to deal with more personnel shortages due to employees falling ill or being quarantined due to a contact with an infected person. At the same time, demand for care personnel in emergency departments has been spiking, requiring even more shifting of personnel resources.

In order to help care managers understand and predict how they need to react to upcoming changes in personnel supply and demand, you are tasked to use the RKI (Robert Koch Insitute - German Federal Insitute for Health) API to provide valuable information to the Chief Nursing Officer of a large Munich-based hospital about the current trends of the virus.

You can access the API docs [here](https://api.corona-zahlen.org/docs/). It provides a route to get the number of cases per district as well as the incides per district, both of which are valuable KPIs in understanding the occurence of infection.

The AGS code of the city of Munich is **09162**.

For example, you can use the route [/districts/09162/history/cases/30](https://api.corona-zahlen.org/districts/09162/history/cases/30) to get the amount of cases in the city of Munich for the last 30 days.

### Programming Languages

You are free to build the application either for the web or for mobile, depending on your preference. We work with React-Native, ReactJS and TypeScript, and displaying confidence and fluency in those languages will obviously be seen as a plus, but is not required. As working with React-Native and the limitations of a smartphone screen size definitely adds complexity to the challenge, we would see a mobile app a considerable plus, but don't recommend it if you are not experienced with mobile development and RN. Please rather focus on displaying the quality of your thinking and writing understandable and maintainable code than displaying your ability to learn a new language/framework just for a recruiting test :)

### Task requirements

Feel free to spend as much or as little time on the test as you like as long as the following requirements have been met.

1. The user story is completed
2. The code compiles and runs in one step
3. You **must** include tests - however, you are free to choose the tools and types of tests to use

#### User Story

- As a **care manager**
- I can **view the current development of the local incidence and cases of COVID-19**
- So that **I know how my hospital might be affected by the virus in the coming days and weeks**

#### User acceptance tests
- For the city of Munich, incidence and cases per day for the last 90 days are displayed correctly in a visual representation

## Additional questions

After finishing the coding test, please answer the following questions in a markdown file called `additional_questions.md`.

1. How long did you spend on the coding test? What would you add to your solution if you had more time?
2. What alternative approaches/solutions to the user story did you consider when engineering your solution? What benefits/downsides would they have had compared to the selected solution?
3. What additional features/improvements do you think could help the customer gain more value from your application?
4. Where do you see issues in your code that might cause issues in the future? How would you monitor the performance of your app?
5. How would you improve the API that you just used or its documentation?
6. What did you think about this test? How interesting was it for you? How would you recommend us to improve the test?


**Thanks for your time, we will be in touch with you soon,**
Your [Cliniserve team](https://www.cliniserve.de/en/ueber-uns/)