# CMU Interactive Data Science Final Project

* **Online URL**: https://cmu-ids-2020.github.io/fp-classification_clarification/
* **Team members**:
  * Contact person: Juliette Wong (jnwong@andrew.cmu.edu)
  * Christian Deverall (cdeveral@andrew.cmu.edu)
  * Nathan Jen (njen@andrew.cmu.edu)
  * Laura Howard (lmhoward@andrew.cmu.edu)
* **Track**: Narrative

![](gifs/dt.gif)

## Work distribution

### Nathan
I was primarily responsible for the styling of our web application, which meant writing custom CSS and bolding text. Additionally, since I am the only team member with JavaScript experience, I had to build out the custom React components for our application as well as implement a lot of our app's functionality. Finally, I was responsible for figuring out how to deploy our Idyll application to GitHub pages. 

## Deliverables

### Proposal

- [x] The URL at the top of this readme needs to point to your application online. It should also list the names of the team members.
- [x] A completed proposal. The contact should submit it as a PDF on Canvas.

### Design review

- [x] Develop a prototype of your project.
- [x] Create a 5 minute video to demonstrate your project and lists any question you have for the course staff. The contact should submit the video on Canvas.

### Final deliverables

- [x] All code for the project should be in the repo.
- [x] A 5 minute video demonstration.
- [ ] Update Readme according to Canvas instructions.
- [x] A detailed project report. The contact should submit the video and report as a PDF on Canvas.

## Running the Project

* Install idyll
  * npm install -g idyll
* Install dependencies for idyll
  * npm i 
* Use es5 version for vega-lite and vega-embed (must be manually done)
  * For vega-lite: Go to node_modules/vega-lite, copy vega-lite.js from build-es5 directory to build directory
  * For vega-embed: Go to node_modules/vega-embed, copy vega-embed.js from build-es5 directory to build directory
* Run the project
  * idyll
