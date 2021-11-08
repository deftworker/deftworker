### Hi there 👋

I am a full-stack developer, software engineer, product manager, and founder who launches and iterates on a portfolio of consumer products online. While the code is private, my projects live on the web and are open for preview and signup online, so feel free to check them out. 
![GitHub followers](https://img.shields.io/github/followers/deftworker?style=social)

### DreamList.com https://www.dreamlist.com 
Go(Golang) |
JavaScript |
jQuery |
Postgres |
Redis |
Gulp |
NodeJS |
Swift |
Xcode |
Three.js |
WebRTC |
Selenium | HTML | CSS | JSON

DreamList was written from scratch in Go(Golang), and Postgres, due to much higher performance and better flexibility with the data. The architecture benefits from low levels abstraction and low dependence on third party modules, which is great for maintainability and on-boarding of additional engineers. At the time of architectural decisions, React came with IP concerns for consumer startups, so I stuck with lightweight custom JS. After multiple benchmarks and prototypes the front end was built with different external and internal facing architectures. External pages are mostly static with plain JS, JQuery, and backend optimizations for SEO performance. DreamList is a top 10 result on Google for Christmas Wish List, Online Wishlist and hundreds of other collaborative shopping categories. Internal user-facing pages have addittional privacy controls indexing prevention, and custom JS for novel UX modules, user delight, and security. Unlike any other collaborative shopping site, you won't find any user lists indexed on google. DreamList is designed to be private and ads-free by default. 

On addition to the main site, there is a product graph and api server architected to protect the privacy of users, but still get them all informatin they need about products they've added from affiliated retailers; a testing suite; a native iOS app in Swift with WKWebview, SwiftUI, and UIViewControllers and a number of other native tools so users can scan barcodes, celebrate holidays virtually, and preserve memories. The product graph is grounds for NLP experiments to build a multi-layered product recommendations and search engine for users. 

Choosing to do native iOS code for the mobile apps was hard and time consuming, but worth the effort, because of functionality gains for users. For repeatable content, I'm doing a custom implementation of WKWebView with caching, and triggers for native behavior within a UIViewController. 



### Iterator (To be open sourced soon)
Go(Golang) |
Postgres |
TypeScript |
React.js |
GraphQL | HTML | CSS | JSON

To judge market demand for new products and new DreamList features, I've developed a Go server with routes that channel different domains for a variety of landing pages with similar template structure and a divided PostgresSQL database. It's like a singleton pattern homegrown Squarespace, with better SEO and performance. The different domain pages can have custom functionality and output static code, so each can scale relatively well in case of HN features or other traffic peaks. I've been planning to outsource the iterator, but it's not cleaned up yet, due to a lot of Holiday work on the DreamList mobile apps. 


### DoerHub.com (offline, may be rewritten in Go or Rust and open-sourced eventually)
Ruby |
RubyOnRails |
JavaScript |
jQuery |
Bootstrap |
MongoDB |
Neo4j |
D3.js | HTML | CSS | JSON

A RubyOnRails and MongoDB online hub for University innovation hubs and project teams. Built in 2013, the site was used by students, coding clubs, researchers, and entrepreneurs at top universities including the University of Chicago, Stanford, UIUC, Berkeley, USC, Northwestern, and startups across the country. I loved helping organizers at entrepreneurial competitions and hackathons, lecturing at coding clubs, conecting with researchers, judging at Stanford's first TreeHacks Hackathon, and participating in YC Hacks, Launch Hackathon, and a number of other clubs and events while building the site. Many DoerHub users eventually became founders and are now either Angel Investors or Founders. The big reason the site closed, was because becoming successful meant we had to lose our users. Inherent in any team or people matching platform is the inverse success incentive. People would share projects, grow them with contributors and collaborators, and then leave to start their businesses. Unless we charged per match or per listing like dating and recruiting sites, and Devpost, we would not be able to stay afloat, and that would eliminate the best new users coming into the site. So I took the key parts of the architecture (visualisations on user badges, algorithms for matching and serving intent, and spam filtering tools) and built DreamList instead, where meeting and exceeding user needs leads to retention and growth. RubyOnRails was great for quick iteration and new models, but due to the low Request Per Second performance of the stack at the time, I used Golang thereafter and had to pay a lot less for server costs. MongoDB was replaced with PostgresSQL due to a lot better handling of relational data and JSON/JSONB availability in Postgres.  


### JavaScript Networking, Search, and Gamification core libraries for NBA.com, CNN.com, PGA.com, PGATour.com, CN.com, etc.
JavaScript | JSON

### Flash & ActionScript 3 Election result displays, Interactive Maps, Times Square Billboard, Video Player, CMS front-end for CNN.com
Flash | ActionScript 3 | Flex | JSON | XML

### Various blogs, consulting projects, 
PHP | WordPress | Bootstrap | Drupal | Alfresco | HTML | CSS | JavaScript | JSON | XML 

<!--
**deftworker/deftworker** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

