# Lab8-Starter

Tim Nguyen

https://nyntim.github.io/Lab8_Starter/

Graceful degradation is the principle that a web app should keep working, perhaps with reduced functionality, when something it depends on is unavailable, such as the network, a remote API, or a browser feature. Service workers are one of the main tools that make this possible. By intercepting fetch events and serving previously cached responses, a service worker lets the site continue functioning offline or on a flaky connection instead of breaking outright. Service workers are themselves a progressively enhanced feature, so on browsers that don't support them, the page still loads normally over the network. The baseline experience stays intact, and the service worker just adds resilience on top.

