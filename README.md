# Knockri Full Stack (React) Coding Assessment

## Overview

To complete this assessment, you will need to write a simple [React](https://facebook.github.io/react/) web app, and provide us the source files to be built.

The purpose of this assessment is to assess your **skills and approach to composing a simple web app** given an API feed.  We will also assess the **generated HTML, CSS, and JS** output.

This assessment is expected to take about 1-2 hours.

## What to do?

Your goal is to implement a simple React application, where users will be able to view a job candidate's video responses, comment on the responses & save the data. The UX/UI is totally up to you.

Although its a very basic exercise, we will be looking for simple, well-designed, well-commented and tested code in the submission.

Please include a `README` with setup instructions, and any other documentation you created as part of your solution.

Also, add very short info for the following to your `README`:

* How did you decide which technologies to use as part of your solution?
* Are there any improvements you could make to your submission?
* What would you do differently if you were allocated more time?

Once you complete implementation, please send us the link to the hosted repository (e.g. Github, Bitbucket...). Alternatively, you may submit your code as a ZIP file too.

## How should the application work?

The user of this react application should be able to view the video response(s) of job candidates applying for a job at their company. The application should have the following workflow,

1. Choose candidate from a list.
2. Depending on the selection in the first step, if the selected candidate has an application, display the video response(s) of the candidate with the relevant question displayed in text. If the selected candidate does not have an application, display appropriate message.
3. For each video response of a candidate, provide an option to enter comments.
4. Provide a "Save" button that saves the comments to the api.json file.

## Requirements

* Only step 1 should be visible when no candidate is picked. Step 1,2,3 and 4 should be visible when a candidate is picked.

* User should be able to change candidate selection at any time.

* You can use whatever libraries, task runners and build processes you like. React and plain JavaScript are the only requirements (ES6 encouraged, but no TypeScript, CoffeeScript, etc). Redux is strongly encouraged if you see a need for it.

## API Usage

API can be launched using npm start. You will need to run npm install once you starting working on the project to install dependencies.

| Endpoint                     | Result                                              |
|------------------------------|-----------------------------------------------------|
| /candidates                  | Lists all available candidates                      |
| /questions                   | Lists all available questions                       |
| /applications                | Lists all available applications                    |

More info about API usage can be found at the [json-server repo](https://github.com/typicode/json-server).

---

