---
layout: essay
type: essay
title: "Replacing my brain?"
date: 2024-05-07
published: true
labels:
  - Computer Science
  - Software Engineering
  - Artificial Intelligence
---

### I. Introduction
AI useage from my experience, has been frowned upon in many classes that require essays and assingments to be written by the student. I have no experience in any other AI services besides ChatGPT, and being at the age I am not we did not have tools like such growing up. The relevance it has to Software Engineering specifically is simply a tool to help enhance someone's knowledge, but not used to replace their knowledge. I might say that this is the first semester in college out of all 10 years being in college, that I have used AI. 

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

  1. Experience WODs e.g. E18: For these WODs I felt no need to use AI because there were clear instructions on how to approach these WODs. 

  2. In-class Practice WODs: I actually never participated in the in-class practice WODs because the times were during the time I work.

  3. In-class WODs: I used ChatGpt for a few of the WODs, however I was very hesistant to use it for coding as it generally would not do the work for you, and I had no prior experience with it. I may be old school for being hesitant on a tool that was not allowed for me in prior classes. However, here is an example of my usage:
     
Incorrect usage where I just copy pasted the prompt of the WOD: please give me a javascript code that Problem 3: Write a function called fib() that returns an array containing the first 50 Fibonacci numbers. By definition, the first two numbers in the Fibonacci sequence are 0 and 1, and each subsequent number is the sum of the previous two. As an example, here are the first 10 Fibonacci numbers: 0, 1, 1, 2, 3, 5, 8, 13, 21, and 34. (To construct this list, just use a FOR loop; underscore does not make your life easier here.)

Incorrect output answer that gave me an incorrect answer for what the WOD should have produced: 

<div class="text-center p-4">
  <img width="500px" src="/img/Example2.png" class="img-thumbnail" >
</div>

Whereas you can enhance the question and contents regarding the topic to manipulate the outcome you want: please give me a javascript code that numEvenNums(). This function takes an array of numbers, and returns a number indicating the number of even numbers (i.e. divisible by two) in the original list of numbers.

Output: 

<div class="text-center p-4">
  <img width="500px" src="/img/Example3.png" class="img-thumbnail" >
</div>

From this I clearly understood that even if you think that ChatGpt might give you the "right" answers, it actually depends on how you word the question. It is also your responsibility to be able to check the code gives the proper output, that's where having the right knowledge and understanding the concepts is key. This clearly emphasizes that AI usage is simply a tool. 

  4. Essays: ChatGpt was not used for essays as I have prior experience with writing essays for research and english classes. 

  5. Final project: I have only used AI for this matter for a snippet of code for design purposes in the landing page button design. I was not exactly sure how to implement a link into a button, even after reading some forums. Here is an example: 

Question: Please change this code so that the button component links to a url in react js : 
```
 import React from 'react';
import { Container } from 'react-bootstrap';
import { Link } from 'react-router-dom';
import { PageIDs } from '../utilities/ids';

/* A simple static component to render some text for the landing page. */
const Landing = () => (
  <div id={PageIDs.landingPage}>
    <div className="landing-green-background">
      <div className="club-background">
        <Container className="container-btn">
          <h3 style={{ paddingTop: '10px', color: 'white', fontSize: '40pt' }}>
            Search Here
          </h3>
          <div>
            <Link to="http://localhost:3000/browseClubs" />
          </div>
        </Container>
      </div>
    </div>
  </div>
);

export default Landing;
```

Output: 

```
import React from 'react';
import { Container, Button } from 'react-bootstrap';
import { Link } from 'react-router-dom';
import { PageIDs } from '../utilities/ids';

/* A simple static component to render some text for the landing page. */
const Landing = () => (
  <div id={PageIDs.landingPage}>
    <div className="landing-green-background">
      <div className="club-background">
        <Container className="container-btn">
          <h3 style={{ paddingTop: '10px', color: 'white', fontSize: '40pt' }}>
            Search Here
          </h3>
          <div>
            <Button as={Link} to="/browseClubs" variant="primary">Browse Clubs</Button>
          </div>
        </Container>
      </div>
    </div>
  </div>
);

export default Landing; 
```

Which I was able to produce a link within a button component which I was able to manipulate later for design and proper usage. 

  6. Learning a concept / tutorial: I don't think I have used it for this matter as I was keeping ontop of watching the assingment videos to better understand the concepts myself. 

  7. Answering a question in class or in Discord: I have no used AI for this purpose because I rarely talked in class, unless it was a discussion. I personally prefer to formulate my own opinions, and discuss other people's opinions as well. 

  8. Asking or answering a smart-question: I have not used AI for this matter for the same reasons, smart-questions should be something through someone's own knowledge. 

  9. Coding example e.g. “give an example of using Underscore .pluck”: I have not used AI for this matter in giving an example, as there was ample examples that were given throughout the courses on proper coding usage. 

  10. Explaining code: I have not used AI in order to exaplain code as there was no pressure to exaplain any code throughout this semester. I believe that everything was explained pretty well with all of the course material, and if I had a direct question regarding anything it would have been addressed to the professor. 

  11. Writing code: There was no real need to use ChatGpt in order to write code as I feel like most of the assignments were using templates and changing them as needed in specific files. 

  12. Documenting code: I have no used AI in this application as all of the material regardnig coding was covered in class. 

  13. Quality assurance: AI was used for quality assurance purposes to check if code written was working and producing the proper output. For example there was an instance in which my code was not working and this is what I had asked: 

Please check this code for any errors: import { Meteor } from 'meteor/meteor';
import { TasksCollection } from '/imports/api/TasksCollection';

const insertTask = taskText => TasksCollection.insert({ text: taskText });

Meteor.startup(() => {
  if (TasksCollection.find().count() === 0) {
    [
      'First Task',
      'Second Task',
      'Third Task',
      'Fourth Task',
      'Fifth Task',
      'Sixth Task',
      'Seventh Task'
    ].forEach(insertTask)
  }
});

In this instance, I was given this feedback: 

Your code seems mostly fine, but I have a couple of suggestions for improvement:
Check for Server-side Execution: Ensure that this code is executed on the server-side. If you're running this on the client, it might cause security issues.
Error Handling: It's generally a good practice to handle errors, especially when dealing with database operations like insertion.
In which I was given an altered code with the following comments as to why changes were made:

<div class="text-center p-4">
  <img width="500px" src="/img/Example1.png" class="img-thumbnail" >
</div>

Which was very helpful in the end as I was not too sure what was wrong with my code
  14. Other uses in ICS 314 not listed above: Most of my experiences using AI for this course was for checking for code errors and experiencing understanding how to use the tools. I have no other uses for AI in this course besides what was listed above. 


### III. Impact on Learning and Understanding

I don't think usage of AI has actually impacted my learning and understanding of any of the concepts covered throughout this semester. If anything, ICS 314 has actually allowed me an opportunity to be able to learn how to use AI tools such as ChatGpt. This is due to my past experiences of not having tools as such, which I am definitely still not accustomed to. 


### IV. Practical Applications:

I can see the practical applications in terms of AI usage in which it would help enhance in the ways we would like to approach an issue or topic. This could include in projects for future classes, and is definitely great for checking errors that maybe human error would not be able to catch. 


### V. Challenges and Opportunities:

The challenges and limitations that have been presented with AI usage throughout this semester has been replacing my brain. Yes, replacing my brain, as I realized AI is simply a tool and not meant to replace one's ability to think. Other than that, the only challenge was learning how to use the tool. 


### VI. Comparative Analysis:

Personally, I admire AI as it does help people to think beyond what they can think. I personally like to talk out loud or think through about my approaches for a greater outcome. As traditional teaching methods are appreciated, I do not think that AI should replace these traditional methods. One's ability to retain knowledge and think on their own is a gift in itself. The beauty of knowledge is also being able to teach someone else the knowledge that you gained. This solidifies that one actually knows the material to their best of their knowledge. 


### VII. Future Considerations: 

I believe that AI has great potential in the future and it's usage with Software Engineering. As my experience taking ICS 314 has been enhanced through learning how to use AI as a tool, and not replace knowledge, I can agree it has great potential to enhance Software Engineering overall. 


### VIII. Conclusion: 

I highly encourage the useage of AI in future courses as a tool but not as a means to do the work for someone. My recommendation would be to emphasize further and possibly explain to future users of AI that it should not replace knowledge, but rather be used to enhance to build and create better outcomes. 



