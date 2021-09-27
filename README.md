# Search Test
## Introduction
The overall test idea is to assess your ability to ship a set of real features from back to front.
Rather than focusing on your React and backend profifiency we will pay a close attention to :
- your ability to appreciate / developp a product with a minimum/minimalist set of specifications
- your ability to deliver a working feature from A to Z
- the readability of your code (variables naming, file organisation, etc.)
- how your code is reusable / extendable and robust
- how you organize your branch and commits

## The Product
Let say that we want to build a small product that should help brands to benchmark specific topics. With that in mind, we're coming up with a set of basic user stories:
- As a user, I can visit the home of the product and see some random publications with their media
- As a user, I can click on a given given publication and browse to a dedicated view of this publication. On this dedicated view, I get additionnal details. This dedicated view should be "routable", in other words I should be able to browse directly to this page or modal or whatsoever
- As a user, I can search for publications by topics and social networks (instagram or tiktok). More precisely I should be able to type a topic and see publications matching this topic and I should be able to use checkbox filters (Instagram, Tiktok) . The search should be "realtime" : when I type my topic I get realtime update of the found publications
- As a user, I can see my "Recently visited publications"

That's all 🎤!

Obviously... the specifications are really poor 😅. Don't worry, we work with more detailed, documented (mockups) and discussed specifications 😎. This is just for the sake of the test and to let you come up with a minimum UX and some "product" choices for further discussions.

## Instructions / Requirements

Apart from implementing this minimum product, there's no specific requirements:
- you're free to go for a monolith or an api/client architecture
- the backend code can be in ruby, python, js with your framework of choices
- the frontend must be in React.js but you're free to pickup a "framework" if you want
- Regarding the UX/UI, you're free. Don't lose 10h to chose a font but try to deliver a clear, simple and nice interface. You can chose an UI Libray or come up with your own set of components

Ressources: You'll find here a CSV file with more than 10K publications to seed in your app !

In terms of deliverable, you're free, again. The minimum requirements are:
- we should be able to the product on a given "production" url
- we should be able to review your backend/frontend code
