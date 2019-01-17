---
title: How to use React components in Angular app
date: '2019-01-17'
---

React is everywhere! 

It is the most famous library for building frontend apps currently. This has led to development of a lot of third party component libraries and community support for React ecosystem.

These industry trends along with organizational pressure can lead to mandates regarding the use of component libraries or migration from one technology to another (Angular to React).
For example, in the case of [patternfly-react](https://github.com/patternfly/patternfly-react), where its use is required, the client must be written in React (there is no Angular component library for the latest version). Rewrite from Angular to React may be cost-prohibitive or ill advised for other reasons.

#### Typical use cases for using a react component in angular app would be - 
- Use react component libraries like patternfly-react in angular applications.
- Incrementally rewrite an Angular application into React (moving from atomic/leaf nodes upward into full features/pages until the entire app is re-written).

So, this blog will focus on explaining how we can use a react component in angular applications.

We'll start off with a very basic solution for the problem. We'll take a `<Button/>` component that is written in react and try to use it in the angular app.

#### Setup the env 
```sh

npm install -g @angular/cli
ng new angular-react-app
cd angular-react-app
ng serve

```





