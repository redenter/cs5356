Social Story Builder
--------------------

### Background

Social stories are an educational tool used by teachers of developmentally disabled individuals. They are visual guides that describe social situations and behaviors. Social stories can be used to teach autistic individuals about social cues and how to react to various situations. They are a common intervention option for children and can explain social situations in a manner that is easily understood by its audience. Currently, social stories are generally created in a Word document and printed out.

### Challenge

Create a web application that would allow teachers, therapists, or parents to create social stories for a student. This would include an editor for uploading pictures and adding text. We also want to create a way for teachers to upload their social stories to a global community so that others could download their stories and edit it for their own students. There would also be a mobile component where a teacher could bring up the social story on a tablet and go through it with the student.

### Repository

[Social Story Builder Web and iOS App](https://github.com/szsen/SocialStoryBuilder)

### Project Management
* [Project Dashboard](https://waffle.io/szsen/SocialStoryBuilder)
  * [First Story](https://github.com/szsen/SocialStoryBuilder/issues/8)

### Continuous Integration

For the web app, we use CircleCI to run build tests on each commit. You can find our build statuses on CircleCI here:

[CircleCI Dashboard](https://circleci.com/gh/szsen/ssbuilder)

### Continuous Deployment

For the web app, we use CircleCI for continuous delivery via Docker Hub. We then set up [Tutum](https://www.tutum.co/) to automatically deploy our application service whenever there is a new image available on Docker Hub. You can see our latest build live here:

[Social Story Builder Latest](http://91c1fff3-rchen27.node.tutum.io/stories)

### Team

[Roger Chen](/people/roger-chen.md), [Sonia Sen](/people/sonia-sen.md), [Ruiheng Wang](/people/ruiheng-wang.md)