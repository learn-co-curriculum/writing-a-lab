You've written a phenomenal lesson, and now it's time to test your students to see how much they learned. A lab is a time for students to put the skills they've learned to the test.

## Purpose of A Lab

The purpose of a lab is for students to practice what is taught in a lecture or through a reading. We teach students to be productive and to do that, we want them to start applying their knowledge right away. Students become developers when they are working on labs.

Because of this, we want our labs to be challenging and students should feel pushed intellectually with each lab. Labs also give exposure to Test Driven Development and are a means for students to push their own learning forward by struggling through difficult content. Moreover, completing labs and seeing complete projects, even small ones builds confidence


For this reason, our overall curriculum should include labs of varying degrees of difficulty. For important units or even important lessons, we should make sure that there are both regular and advanced labs. 

## Naming Convention

Naming convention is helpful for students to at a glance know what a lab is covering. Labs should be named to correspond with the Topics defined on Learn. It should at the very least begin with the name of the Topic. The last word should be lab (to distinguish it from a Readme) So for example:

* "Rails-Blog-Nested-Resources-lab"
* "SQL-Library-lab"
* "Sinatra-Nested-Forms-lab"
* "Js-OO-Task-List-lab"

## Content

Ideally, a lab should focus on one Learn lesson. Of course, many of our labs require students to practice more than one skill, especially in more complex full application labs. 

For Rails and more complex topics, our labs should be granular, with each iteration building off the preceding one. An example of this is the Rails Blog Domain, which is comprised of the following labs, all of which are iterations on top of the preceding lab:

1. Rails Blog Scaffold
2. Rails Blog Associations Validations
3. Rails Blog Nested Forms
4. Rails Blog Nested Resources
5. Rails Blog Sessions
6. Rails Blog Omniauth
7. Rails Blog Asset Pipeline

At the same time however, you should never have students rely on code from a previous lab. All the starter code needed to complete the lab should be in that lab.

## Readme

Your lab's Readme is the first point of reference about your lab to a student.

Your Readme sets the student up for what scanario or context in which they're building. It's important to connect the lab with real world context or actual situations. Context provides a reason for a student to struggle. Once they know the purpose of the skill they're learning, they can become motivated by the things they can build with that skill.

If you're teaching methods, you might want a scenario in which you'd want the same action to take place over and over again. What about Facebook sending happy birthday emails to every user on their birthday? That's a good example domain model within which to frame your lab. 

If you're teaching arrays, you might want a scenario where you'd want to store a group of objects and do the same action to each item in that group. What real-world situation could that be? 

## Instructions

Lab instructions should err on the side of overly-specific. The worst thing in the world is to have a student confused and struggling with material because the instructions are unclear. We would rather give the student more instructions and risk annoyance over too much reading, than too little. If you need a student to create a database table, tell them exactly what columns the table should have. They shouldn't have to guess. It's not giving it away to tell them what to build; they still have to figure out **how** to build it.

That being said, think of your instructions more as requirements. Don't give the specifc steps and how-tos to your students. Instead, tell them what the components and requirements of their soluton should be. 

Instructions should be written in order of how to solve the problem. Really big labs or labs that cover complex topics can feel really overwhelming. Students learn the patterns of how to approach larger projects by reading instructions/requirements in the order in which they should be tackled. 

The first few tasks should be easy, and subsequent tasks should increase in complexity.

When creating a lab, think about how a video game introduces complexity. A good video game will make you complete a level where all you need to do is jump across a gap before you're introduced to a level where jumping across a gap is required to achieve some other goal.

## Tests 

All labs are test driven. For Ruby and Rails labs, we use Rspec with Cabypara for testing views. 

For Javascript/ Angular/ Node labs, we typically use Mocha. Test everything you want to make sure was completed


## Solution Branch

Every lab should have a solution branch. Your solution branch should have a clean, understandable solution that other instructors can refer to for lab reviews and helping students. Sometimes, students might want the solution pushed up to them after they've completed the lab, so it's important that the solution is straightforward.

## Regular Lab vs. Stretch Lab

A normal lab should test the student on exactly what they just learned in a previous Readme. Every piece to the solution should be able to be referenced in the previous lesson. They only lines of code they should have to write are the skills they should be practicing.

A stretch lab is a lab that requires students to put some of the pieces together themselves. The point is that a student should be far removed from their comfort zone during a stretch lab. We should be stretching the boundaries of their learning. Several components of a stretch lab:

+ Provide less instructions
+ Tests only cover the big picture and not each individual line of code they have to write
+ Provide less starter code
+ Require a student to Google some information to complete the lab
+ Incorporate past concepts a student has learned to pass all the tests


## How to Approach Building A Lab

Sometimes it can feel daunting to approach building a lab. There are many ways to do it, none more correct than the other.

If you need a little help getting started, we recommend you start at the end and work your way backwards. Start by building the solution you want your students to create in the lab, then build the tests that test the skills you want the lab to practice. From there, write your Readme with clearly stated objectives, scenarios, and instructions.

## Extras

We always want to make sure our students are having fun, and a lot of that can be achieved through the tone of the lab. Here are some ways to achieve that:

+ The lab topic or intro can be humorous
+ A good gif

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/writing-a-lab' title='You've written a phenomenal lesson, and now it's time to test your students to see how much they learned. A lab is a time for students to put the skills they've learned to the test.'>You've written a phenomenal lesson, and now it's time to test your students to see how much they learned. A lab is a time for students to put the skills they've learned to the test.</a> on Learn.co and start learning to code for free.</p>

<p class='util--hide'>View <a href='https://learn.co/lessons/writing-a-lab'>Writing a Lab</a> on Learn.co and start learning to code for free.</p>
