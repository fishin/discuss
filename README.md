discuss
=======

discussion repo

If you are interested in contributing to this project please let me know.  I can be reached at lloyd.benson@gmail.com.  This project is a large undertaking so if you have specific areas you may think you can help out with, I'd certainly appreciate it.

You can also join me on gitter for discussion.

[![Join the chat at https://gitter.im/fishin/ficion](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fishin/ficion?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

UPDATE: This is getting to a point where I think its possible more than just me might find it useful.  I'd really like to find some early adopters who may need just a couple more features in order to find this useful.  If you would like to hear more or volunteer some time to see if this works with your project, please reach out.

Goals of the project:

- To improve my skills as a developer
- To create an alternative to jenkins thats also open source but node based
- To have tighter integration with github
- Focus on node hapi projects but keep any project in mind for future expansion (this is based on hapi.js)
- Good code coverage (in general all api level stuff is 100% code covered and FE is the only thing thats not (but still above 90%)
- Not to get too crazy and keep things simple
- Get to travis like simplicity but have a UI frontend to manage config
- Scalable instances - have one UI that could manage multiple api instances
- Plugin architecture - people want to do anything so we need to make the right hooks so they can replace the bits they dont like out of the box

Technologies:

1.  javascript
2.  hapi.js
3.  FE - React (not started), bootstrap, handlebars (has tighter integration with hapi.js and is performant), likely something like backbone (but has not been decided).  It is fairly a fairly primitive SPA at this point (more to show off the api)

How to get started:

git clone https://github.com/fishin/ficion and follow the README

Where you can help:

- Just use it and report issues you have
- If you have just a feature or 2 to make this useful for you please let me know and I will try to prioritize
- PR any open issue in any repo
- Improve error handling
- Performance Improvements
- More Mocking to improve test speed
- Code Reviews
- Refactor suggestions / help (esp. in FE, but as things progress there are areas that can be split up a bit better for better readibility)
- FE expertise (I'd like to do some React but FE is a big area of improvement I could use help with on suggestions or whatever you can spare)
- Emitter help (I need to get emitters implemented to improve things feedback of jobs)
- Statistics Engine (fillet) - trending and other stats that are useful - d3 based?
- Webhook engine (fishhook) - this handles primitive cron but webhooks would be fun and neat to do
- Any other ideas you can think of that would be useful

What do you get out of it?
 
- An improved free product
- Open source cred
- Learning experience 
- Potential reuseable components for your product

Really there are tons of things that can be done so if you are interested in a continuous integration solution based on hapijs or are just wanting to learn more about hapijs and want some mentoring this may be the project for you.
