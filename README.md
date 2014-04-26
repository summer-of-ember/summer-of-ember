# Summer Of Ember
---

The summer of Ember is a project started by @j-mcnaly and @lrdiv of @kohactive.  
Our goal is to the take great opensource project and make them even greater by adding ember js.  
The project is meant to run over the course of the summer and we would love others in the EmberJS community to join us.



## The Team
---
So far the team looks like this, but we invite anyone to send a PR that adds their person or company.



#### Individuals


- Justin McNally [(Twitter)](http://www.twitter.com/j_mcnally) [(Github)](http://www.github.com/j-mcnally)
- Lawrence Davis [(Twitter)](http://www.twitter.com/lrdiv) [(Github)](http://www.github.com/lrdiv)


#### Sponsors

- [kohactive](http://www.kohactive.com)


## The Projects
---
The following are a few projects we are suggesting as possible projects to begin with, but we also welcome PRs to include other projects.



***Smaller***
  
- Sidekiq-WebUI



***Larger***

---
**Disclaimer / Structure:**
Our background is in ruby so there is currently a bias twords ruby projects, we know how to package and easily extend ruby and rails based projects easily, if you are a node or other language expert we still want you to participate but strive to meet the following goals.

- Ember apps should be built in away where the final product can exist independent of the language, and should not rely on the asset pipeline directly.

- Your project contribution should not change the project directly, it should be included as a seperate package and be cleanly mountable as a seperate middleware, rack app or engine depending on the project and language requirements.

- Ideally projects should be built with ember-cli but other build tools are fine.

- If the project you want to contribute to requires an additional api, include it as a seperate package / engine not part of your ember project package.