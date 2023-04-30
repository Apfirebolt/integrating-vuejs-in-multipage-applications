# integrating-vuejs-in-multipage-applications
Smooth integration of Vue js in multi-page applications which might have used Vanilla JS or Jquery earlier


## Why use Vue in place of Vanilla JS ?

- Simplifies stuff like event handling, data handling, API calls and more
- Routing can be implemented on the front-end
- Component based structure encourages modularity in user interface development.
- Saves lines of code

## Data, Events and Filters

To use Vue js in your multi-page application, you need to target the section where you need to use Vue in the Vue instance through class or ID (aiming through ID is preferred). Vue prevents targeting body element of the page.

The about.html page contains examples for event handling through Vue. The section tag is wrapped with a Vue object so that event and data handling can be done through Vue instead of pure Vanilla JS.

Filtering is demonstrated using currency where $ sign is appended before each currency value in the currency array.

## Watchers

Watchers are used to keep track of changes in a given variable. For instance, if a boolean variable is monitored through a watcher, then we can hook a function to it which can be executed as soon as the boolean variable is changed.

## Animations

There are multiple ways of animating DOM elements in Vue JS.

- Use conditional classes
- Use Transition wrapper
- Animation through Javascript life-cycle hooks

Animating through classes could be the easiest way to animate stuff in Vue JS while using Transitions might be the right way to do it and supports animating multiple elements at once.

## Conditional Rendering

Conditional rendering of DOM elements can be controlled using v-if and v-show built in directives in Vue JS.


✅ ## Vue JS Resources

This would contain the resources I've went through while learning Vue JS over the years I've been working in Vue JS.

📚 ### Books

| Title              | Author |
| :---------------- | :------: |
| Python Hat        |   True   |

🔥 ### Youtube Channels

| Channel Name              | Owner | URL |
| :---------------- | :------: | ----: |
| Python Hat        |   True   | 23.99 |

🎥 ### Udemy Courses

| Title             | Teacher |
| :---------------- | :------: |
| Vuejs-2-the-complete-guide       |   Maximilian Shwarzmuller   |
| Build-web-apps-with-vuejs-firebase       |   Shaun Pelling   |
| Vuejs-from-beginner-to-professional       |   Bo Andersen   |

