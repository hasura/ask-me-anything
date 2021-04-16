## [Welcome to the Hasura #100DaysOfCode && #AMA Repo Site](https://hasura.github.io/ask-me-anything/)

If you want to clone or take a look directly navigate to the [repo](https://github.com/hasura/ask-me-anything/). If you'd like to submit a question for the AMA sessions, file an issue here, and we'll get that added to the queue to get answered! Once the question is fielded during one of the "[Hasura #100DaysOfCode && #AMA](https://twitch.tv/hasurahq)" live stream I'll get it added here as an answer file!

Cheers!

The Hasura Codes [#100DaysOfCode && #AMA](https://twitch.tv/hasurahq) is daily at 11am Pacific. Join us anytime and ask questions live during stream, fill out a [question issue here](https://github.com/hasura/ask-me-anything/issues/new/choose), or [join our discord](https://discord.com/invite/hasura) and ask there! For the questions that have answers, here's a list of questions we've covered so far:

* Where are the database URIs located in Hasura Cloud and the Hasura Console? Answer: [video](https://youtu.be/v6iHkqbjE2c)
* What is a good way to build queries or to get better perf out of table queries? Answer: [video](https://youtu.be/fnuy2FHGI1c)
* What does the .NET ecosystem look like for GraphQL & is it maintained? [video](https://youtu.be/U1sLbRl8IkQ) & [article with links from video](dotnet-graphql-links.md)
* Schema migrations console vs. 'hasura console' best practice. Answer: [video](https://youtu.be/82OnqotEBcA)
* How to connect to the database with a 3rd Party tool (like [DataGrip](https://www.jetbrains.com/datagrip/)) from the local development quickstart docker-compose setup? [video](https://youtu.be/FTSIZ7HdHc8)
* How do you draw relationships between tables in Hasura vs. the Database? [video](https://youtu.be/CMdLV4OC7G4)
* Is there a way to map db columns to GraphQL entity properties in Hasura? (Hat tip to [@iteswendell](https://github.com/itswendell)) [video](https://youtu.be/hiYwejjjNW8)
* What are some strategies to research GraphQL query performance? [video](https://youtu.be/7kN-p6fhsyw)
* Can a read-only database be connected to with Hasura? [video](https://youtu.be/vNb3m6fplwI)
* Is there a good data type to use for time stamps in Hasura? [video](https://youtu.be/ESNjXT5yHU0)
* What is the suggested way to setup Hasura for local development? [video](https://youtu.be/NnbkG5vrF_A) for even more in depth, check out the longer form video "[Hasura Coder Setup and Workflow with Migrations, Metadata, & Seeds](https://youtu.be/AUY5tV4rA4w)".
* What gets built out when I use the Hasura Console to build out migrations? [video](https://youtu.be/GjfSV-NxXaw)
* Is there a way to map GraphQL to (.NET) Entity Relationship Diagrams? [video](https://youtu.be/twdx24-xyXw) & for more .NET information, check out [these links](dotnet-graphql-links.md).
* What is the history behind the Hasura logo? [video](https://youtu.be/x3nxSD4h57Q)
* What are your favorite... specifically your go to databases? [video](https://youtu.be/aCaGJ1XR_i0)
* What are some good ways to develop applications using Hasura and have environments split like UAT, QA, Live, Prod, etc? [video](https://youtu.be/3JFc2K-WPhM)
* What is the UUID column type good for and what exactly is a UUID? [video](https://youtu.be/tQ8AaQyKKFk)
* What are the supported character data types in Hasura? [video](https://youtu.be/4FJ0QgzmptU)
* What numeric data types does Hasura support in relation to the underlying database(s)? [video](https://youtu.be/oLNjr7j8tOs)
* What's your practice when iterating through development cycles to clean up your containers and images? [video](https://youtu.be/TK6ECENT-uE)
* Is there an option or ability to use short IDs in Postgres or Hasura? [video](https://youtu.be/DdycuIVb2vI)

If you'd like to just check out the existing questions, scroll through the [questions issue list](https://github.com/hasura/ask-me-anything/issues).

Sometimes, if specific questions haven't come up, it's great to just work through tutorials and check out example code repostitories. That's what the following list is, example repos and tutorials:

* [Hasura Advanced Tutorial: Migrations and Security](https://youtu.be/MBe1AB2vlkY) - In this stream, we will look at a couple of advanced features of Hasura - Migrations/Metadata and various security aspects of using Hasura in production.
* [Hasura Advanced Tutorial: Performance and Reliability](https://youtu.be/LRAJTlKetPo) - In this stream, we will look into advanced performance optimizations for Hasura and Databases with Caching and Scaling and reliability checks with Health endpoint and observable metrics.
* [Introduction to GraphQL](https://hasura.io/learn/graphql/intro-graphql/introduction/) - A practical and concise course that will introduce you to GraphQL and its core concepts. This course explores the fundamentals of GraphQL and what makes it especially suitable for modern applications, like its realtime capabilities! 
* [React + Hasura](https://hasura.io/learn/graphql/react/introduction/) && [Vuejs + Hasura](https://hasura.io/learn/graphql/vue/introduction/) && [Nextjs + Hasura](https://hasura.io/learn/graphql/nextjs-fullstack-serverless/introduction/) && [TypeScript + Apollo Client + Hasura](https://hasura.io/learn/graphql/typescript-react-apollo/introduction/) && [React Native](https://hasura.io/learn/graphql/react-native/introduction/) && [Angular + Hasura](https://hasura.io/learn/graphql/angular-apollo/introduction/) && [Android + Hasura](https://hasura.io/learn/graphql/android/introduction/) && [Unity + Hasura](https://hasura.io/learn/graphql/unity/introduction/) - Explore the fundamentals of GraphQL and the things that make GraphQL especially suitable for modern applications, like its realtime capabilities! The course is light on opinions so that once you grok the fundamentals you can go on to choose your favorite libraries, tools and tailor your workflow.
* [Hasura Basics](https://hasura.io/learn/graphql/hasura/introduction/) - This course is a super-fast introduction to setting up a GraphQL backend with Hasura. Timed for 30 mins, you will set up a Powerful, Scalable Realtime GraphQL Backend complete with Queries, Mutations, and Subscriptions. You will also learn how Hasura helps you integrate custom business logic (in any programming language), both as custom GraphQL APIs that you write yourself, and as Event Triggers that run asynchronously and are triggered by database events.
* [Hasura & Auth](https://hasura.io/learn/graphql/hasura-auth-slack/introduction/) - This course is a super fast introduction to model and think about Auth with Hasura GraphQL. In 30 minutes, you will setup a powerful, realtime and secure GraphQL Backend for a Slack clone.
* [Hasura Advanced](https://hasura.io/learn/graphql/hasura-advanced/introduction/) - This course is meant to be taken by users of Hasura who want to optimise their application for production use cases. If you are new to Hasura, head to the Hasura Basics tutorial to get a fair idea of setting up Hasura and leveraging the fundamental features before diving into this tutorial.

Got more you'd like to suggest? Got a tutorial or blog entry that you think ought to be added? Submit a pull request and just add to the list here similar to those shown. Title, link, plus a description and we'll merge it in! 👍🏻
