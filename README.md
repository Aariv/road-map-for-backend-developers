# Roadmap 2019 for backend developers

Today's Web development is completely different from a few years ago, and there are many different things that can easily shut people out. This is one of the reasons I decided to make this step-by-step guide and let anyone know clearly what they are doing. The role played in web development.

A detailed road map can be found in the picture below, and I will explain each step in the description below.

Before we started, although we didn't list HTML/CSS knowledge in the roadmap below, we recommend that you at least understand some basic HTML/CSS knowledge.

<b>Step 1 - Learn a Language</b></br></br>
There are many choices about language, and I have divided them into categories to make it easier to make decisions. For beginners who are just getting started with backend development, I suggest you choose any scripting language because they have a lot of features that will get you started quickly. If you have some front-end knowledge, you may find Node.js easier (and a big job market).

If you are already developing the backend and knowing some scripting languages, I recommend not choosing another scripting language, but choosing from "Functional" or "Multiparadigm". For example, if you are already using PHP or Node.js, don't use Python or Ruby, but try Erlang or Golang. It will definitely help you extend your thinking and bring your thoughts to a new horizon.

<b>Step 2 - Practice what you have learned (Practice what you have Learnt)</b></br>
<p>There is no better way to learn than practice. Once you've chosen a language and have a basic understanding of these concepts, you can use them and make as many small apps as you can. Here are some Ideas that let you get started:
</p>
<ul>
<li>Implement some commands you use yourself in bash, such as trying to implement ls;</li>
<li>A write access and save on reddit /r/programmingcommand of the article, and save it as JSON;</li>
<li>Write a command that lists the directory structure in JSON format, such as jsonify dir-name returns a JSON file with the internal structure of dir-name;</li>
<li>Write a command that reads the JSON obtained from the above steps and creates a directory structure;</li>
<li>Consider some of the tasks you will do every day and try to automate them.</li>
</ul>

<b>Step 3 - Learn Package Manager</b></br>
<p>After learning the basics of the language and creating some sample applications, you need to know how to use the package manager for that language. The package manager helps you use external libraries in your application and distribute your own libraries for others to use.</p>

<p>If you choose PHP, you will learn Composer, Node.js has NPM or Yarn, Python has Pip, Java has Maven/Gradle and Ruby has RubyGems. No matter what you choose, keep learning how to use its package manager.</p>

<b>Step 4 - Standards and Best Practices</b></br>
<p>Each language has its own standards and development best practices. For example, PHP has PHP-FIG and PSR. There are many different community-driven guides for using Node.js, and other languages ​​have the same guidance.</p>

<b>Step 5 - Security</b></br>
<p>Be sure to read about security best practices, read the OWASP guide and learn about different security issues and how to avoid them in the language of your choice.</p>

<b>Step 6 - Practice (Practice)</b></br>
<p>You have mastered the basics of languages, standards, and best practices, security, and how to use the package manager. Start creating a package and distribute it for others to use, and be sure to follow the standards and best practices you have learned so far. For example, if you choose PHP, you can post it on Packagist, if you choose Node.js, you can post it on Npm, If you choose Java, you can post it on maven and so on.
</p>
<p>If it's done, search for some projects on Github and mention some PR in some projects. Here are some Ideas:</p>
<ul>
<li>Refactoring and implementing the best practices learned</li>
<li>View unresolved issues and try to resolve</li>
<li>Add any additional features</li>
</ul>
<b>Step 7 - Learn about Testing</b></br>
<p>Learn how to write unit tests and integration tests in your application, and learn about different test terms such as mocks, stubsetc.</p>

<b>Step 8 - Practice</b></br>
<p>Write unit tests for the actual tasks you have done so far, especially the exercises you did in step 6. Also learn and calculate the coverage of the written tests.</p>

<b>Step 9 - Learn about the Relational Databases</b></br>
<p>Learn how to save your data in a relational database. Before choosing the tools to learn, learn about different database terms such as keys, indexes, normalizations, tuples, and more.</p>

<p>There are a few options here, but if you study one, it should be fairly easy to learn. What you want to learn should be MySQL, MariaDB and PostgreSQL. You can choose MySQL.</p>

<b>Step 10 —— Practical Time</b></br>
<p>It's time to take what you've learned and create a simple application using everything you've learned so far. To choose any of the ideas, you can create a simple blog and implement the following features:</p>
<ul>
<li>User account - registration and login</li>
<li>Registered users can create blog posts</li>
<li>Users should be able to view all blog posts he created</li>
<li>Users should be able to delete their blog posts</li>
<li>Make sure users can only see his personal blog post (but not others)</li>
<li>Writing unit/integration testing</li>
<li>You should apply an index to the query and analyze the query to make sure the index is working.</li>
</ul>

<b>Step 11 - Learning Framework (Learn a Framework)</b></br>
<p>Depending on the project and language selected, the framework may or may not be required. There are several different options for each language. Continue to see which options are available for the language you choose, then choose one.<p>

<p>If you choose PHP, I would recommend using Laravel or Symfony as well as microarchitecture (Lumen or Slim). If you choose Node.js, there are several different options, but the highlight is Express.js.
If you choose Spring MVC.
</p>

<b>Step 12 —— Practical Time</b></br>
<p>Convert the application created in step10 to use the selected framework, and be sure to port everything including the test.</p>

<b>Step 13 - Learn NoSQL Database (Learn a NoSQL Database)</b></br>
<p>Start by understanding what they are, how they differ from relational databases, and why they are needed. There are several different options, look at it a bit and compare their characteristics and differences. Some common options you can choose are MongoDB, Cassandra, RethinkDB and Couchbase. If you have to choose one, use MongoDB.</p>

<b>Step 14 - Caching</b></br>
<p>Learn how to implement application-level caching in your application, learn how to use Redis or Memcached, and use caching in applications created in step 12.</p>

<b>Step 15 - Create RESTful APIs (Creating RESTful APIs)</b></br>
<p>Learn about REST and learn how to make RESTful APIs. Read the REST section in Roy Fielding's article. If they say REST only works with HTTP APIs, make sure you can argue with others.</p>

<b>Step 16 - Learn about Different Auth Methods</b></br>
<p>To understand the different methods of authentication and authentication, you should know what they are, what is different and when to use them.</p>
<ul>
<li>OAuth — Open Authentication</li>
<li>Basic Authentication</li>
<li>Token Authentication</li>
<li>JWT — JSON Web Tokens</li>
<li>OpenID</li>
</ul>

<b>Step 17 - Message Brokers</b></br>
<p>Learn about message brokers and understand when and why. There are also many options, but the ones that stand out are RabbitMQ and Kafka. If you want to choose one, you can start with RabbitMQ.
</p>

<b>Step 18 - Search Engines</b></br>
<p>As applications grow, simple queries for relational or NoSQL databases do not meet the requirements and have to resort to search engines.
</p>

<b>Step 19 - Learn how to use Docker ( Learn how to use Docker)</b></br>
<p>Whether you're copying the same environment as your production environment, keeping your operating system clean or speeding up coding, testing, or deployment, Docker can make it easier to work during the development process and learn how to use Docker.
</p>

<b>Step 20 - Knowledge of Web Servers</b></br>
<p>If you have gone so far, you may have used the server in the previous steps. This step is mainly to find out the differences between different web servers, understand the limitations and different available configuration options, and how to make the best use of them. These restrictions are written to the application.
</p>

<b>Step 21 - Learn how to use Web Scoket (Learn how to use Web Sockets)</b></br>
<p>Although not required, it is helpful to have this knowledge in the toolkit, learn how to write real-time web applications using web-sockets and use it to create some sample applications. It can be used in the blog application created above to implement real-time updates in the blog post list.</p>

<b>Step 22 ——Learn GraphQL(Learn GraphQL)</b></br>
<p>Learn how to use the GraphQL production API to understand how it differs from REST and why it is called REST 2.0.
</p>

<b>Step 23 - Look into Graph Databases</b></br>
<p>The graph model represents a very flexible way of dealing with data relationships. The graph database provides a fast and efficient way to store, retrieve, and query, and learn how to use Neo4j or OrientDB.
</p>

<b>Step 24 —— Continue to explore (Keep Exploring)</b></br>
<p>Once you start learning and practicing, you will definitely encounter what we didn't cover in this roadmap, as long as you keep an open mind and a desire for new things.
</p>

<p>The key is to practice as much as you can. At first you may feel that you are not catching anything, but this is normal, and as time goes on, you will feel better and better.</p>
