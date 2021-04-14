
# Links
### types of links:

+ Links from one website to another
+ Links from one page to another on the same website
+ Links from one part of a web page to another part of the
same page
+ Links that open in a new browser window
+ Links that start up your email program and address a new email to someone


### Linking to Other Sites
```html
<a href="http://www.imdb.com">IMDB</a>
```
Linking to Other Pages on the Same Site
If all the pages of the site are in the same folder, then the value of the href attribute is just the
name of the file.
```html
<li><a href="index.html">Home</a></li>
<li><a href="about-us.html">About</a></li>
```

### Email Links

#### mailto:

To create a link that starts up the user's email program and addresses an email to a specified email address, you use the `<a>` element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
```html
<a href="mailto:mohammad@example.org">Email mohammad</a>
```
the result is `Email mohammad`
## FUNCTION

A JavaScript function is a block of code designed to perform a particular task.
```js
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
calling function:
```

```js
name()
```

## 6 Reasons for Pair Programming
1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient.
2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.
3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of.
4. Social skills
Pair programming is great for improving social skills.
5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing so, companies can get a better feel for how an applicant will fit into the team and their collaboration style
6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product