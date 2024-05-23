# MVP
MAVUSO
Overview
Our proposed project is a dating application for private adult entertainers (a.k.a Service providers) and their clients. Clients will be able to request the services of their preferred entertainer and the entertainer will be able to either accept or reject the request based on the ability of the client to afford their rates.


Team
Morena Macheka - Project idea. 
                                - Interface design. 
                                - Coding.
Grace Tumbo - Research on existing solutions and technologies we will need. 
                        - Coding.

The roles have been decided based on Grace’s ability to do research and Morena’s creative ability.


 Technologies
Languages: HTML, CSS, JavaScript, Python.

Frameworks and Libraries: React.js, Vue.js, Angular, Bootstrap, 
MySQL, MongoDB.

Platforms: Flutter.

Development Tools: Visual Studio Code (Code editor), github (Version control), Postman (API Testing)

Database: MongoDB, MySQL.

Hosting and Deployment: Amazon Web Services.

Security: HTTPS, user authentication, data encryption.

Resources: Youtube, Stack Overflow, Chatgpt.


Challenges 
This project is intended to help adult private entertainers get paying clients who seek their short term services and clients who seek the services of professional adult private entertainers. In this way, the client will know that there’s an expected amount to be paid after receiving the services and the professional adult private entertainer will not be able to falsely accuse the client of forcing themselves on them after they have received the services and not paid. This project will be beneficial especially for the nightclub scene entertainment industry, as many people unfortunately get behind bars because they have received the services of an adult private entertainer and were not aware they are expected to pay an amount, and as a result they are unfortunately accused of forcing themselves onto the people they received the services from. This will also help clients who are strictly looking for the services of an adult private entertainer and not for a long term relationship. It will also solve the problem of “going fishing” for the adult private entertainer. This project is not dependent on a specific locale. This project will not help anyone get love on the platform or a relationship. It is strictly intended to connect people providing services and the people looking for those services.



Risks 
The risks involved in this project are the client causing harm to the service provider or the service provider receiving the payment and not showing up to provide the services paid for. The other risk would be the service provider being kidnapped or not being taken to a safe location without our online support. To combat this, the client will be provided with the recommended hotels  they can make use of and the services provider will be provided with a device in which they can press the panic button should they feel unsafe and our support team will immediately send help to intervene.  If the service provider accepts the request and does not show up, they will be fined and the client will be refunded or suggested another service provider.  The impact of this project is that many professional adult private entertainers will be able to do their job with the peace of mind of knowing that they will be compensated for and clients will receive the services they seek without fear of being falsely detained.


Infrastructure
Applications rely on branching and merging to manage changes. We as developers will create a separate branch from the main codebase to work on new features or bug fixes. This will isolate our work and prevent disrupting the main code. We will make edits on the branch, track changes with a version control system like Git, and write tests to ensure functionality. Once confident, we will merge the branch back into the main codebase, potentially resolving any conflicts if edits overlap. This process helps collaborate effectively and deliver updates in a controlled manner.

Continuous Integration and Continuous Delivery (CI/CD): This involves automating the building, testing, and deployment of code changes. New code is integrated frequently into a central repository, triggering automated tests and deployments. This enables faster release cycles and quicker delivery of features.

Containerization: Containerization technologies like Docker package applications with all their dependencies into isolated units. These containers can be easily deployed across different environments, promoting consistency and portability.

Content Management system(CMS) will be used for data population.this means that through user interface ,data is entered directly into the CMS.
We will also incorporate APIs which provide a structured way to access, integrate and retrieve data programmatically.

For testing, we will use APIs and Unit Testing framework in Python. The latter isolates individual units of codes to verify their functionality using tests tailored for these codes in particular.
APIs on the other hand act like a quality check for application conversations. Testers mimic how applications interact with the API, sending requests and verifying the responses match expectations for both success and error scenarios. This ensures smooth data exchange between applications.

API testing acts as a behind-the-scenes debugger for application communication, ensuring messages are exchanged flawlessly. Testers craft requests in the language of the API in our case JSON, specifying endpoints (functions) and parameters. These requests mimic how other applications would interact with the API. This tool then sends the request and analyses the response. Just like checking for errors in code, the tester verifies the response code (indicating success or error), response time (ensuring performance), and the data itself (matching expected format and content). This process, incorporating both positive (valid requests) and negative tests (invalid requests, edge cases) in various scenarios, guarantees a robust conversation between applications. By identifying issues early on, API testing acts as a safety net, preventing data corruption and ensuring smooth information exchange between software components.



Existing Solutions
Tinder: The ability to see available service providers nearby on the explore page and seeing service providers advertising their services and rates on the feed page in terms of pictures and captions. The service providers will be able to see how many clients are requesting their services, and their rates will either go up or down based on the demand. The difference with our project is clients will know that these are strictly service providers and are expected to make payment.

OnlyFans: The ability to make payments on the app but with OnlyFans, clients are paying a subscription fee for content provided but with our project they will be making payments for services received.



The flickering neon sign cast long shadows across the table, distorting Sarah's animated features as she recounted yet another disastrous blind date. "Socks with sandals," she sighed, rolling her eyes, "and wouldn't shut up about fantasy football."
I offered a sympathetic smile. Dating as a gay person in our small town felt like navigating a minefield. The few options available often led to awkward introductions through friends of friends, or worse, uncomfortable encounters at straight bars.
A memory flickered in my mind. College. A vibrant LGBTQ+ community center buzzing with life. There, I met Alex, a connection that felt instant, comfortable, a reflection rarely found. But graduation tore us apart, leaving a void that online dating, generic and impersonal, couldn't fill.
"Wouldn't it be amazing," I mused, leaning back in my chair, "if there was a safe space online? A place where LGBTQ+ people could connect, find each other, without the awkwardness?"
Sarah's eyes lit up. "A dating site, just for us? Genius!"
Mavuso was born.
That night, fueled by endless cups of coffee and the shared dream of a better dating experience, our plan began to take shape. I embarked on a journey to build a platform for the LGBTQ+ community we both craved.
Now, watching our dating site flourish, the stories of successful matches and blooming relationships fill me with a sense of accomplishment that goes beyond profit. We created a platform that not only helps people find love, but also fosters a sense of belonging in a world that sometimes feels isolating.



Cracking the Matchmaker Code: Balancing User Preferences in My Dating App
One of the most significant technical challenges I faced in building my dating app was crafting a powerful matching algorithm. Unlike some existing apps that focus heavily on appearance or simple swiping mechanics, I wanted to create a system that fostered genuine connections based on deeper compatibility factors.
The core challenge stemmed from creating a balance between user preferences and fostering a sense of discovery. A purely preference-based system, while potentially efficient, could lead to echo chambers where users only see profiles mirroring their own. On the other hand, an entirely random matching system might leave users feeling frustrated with irrelevant connections.
My Approach:
To address this, I implemented a two-tiered matching system. The first layer focused on essential criteria users establish upfront, like desired relationship type and location. This ensured users wouldn't be bombarded with incompatible profiles, for example, someone seeking a serious relationship wouldn't see profiles of those looking for casual encounters.
The second layer then delved deeper. I developed a weighted system that considered a user's interests, hobbies, how much they are willing to offer and self-identified personality traits. This layer added a layer of nuance, prioritizing matches with a higher chance of genuine connection based on shared activities or values.
The Result:
Developing and refining this system was an iterative process. I constantly monitored user feedback and analyzed in-app data to adjust the weights assigned to different factors. The result was a matching algorithm that fostered a sense of discovery while promoting meaningful connections.
The positive feedback from users – stories of successful dates, blossoming relationships, and a growing sense of community within the app – solidified the effectiveness of this approach. It proved that a well-designed matching algorithm could be more than just a matching tool; it could actively contribute to building a platform that fosters genuine connections and a fulfilling dating experience for users.




Navigating the Labyrinth: Building an Adult Entertainment App
Developing an adult entertainment app presented a unique challenge, a labyrinthine journey filled with technical breakthroughs, missed turns, and a profound personal evolution. Venturing into this uncharted territory unveiled a treasure trove of technical knowledge. Mastering the intricacies of data protection and anonymity felt like cracking a complex code, resulting in a robust security system that would make even the most discerning user feel safe. Additionally, optimizing backend infrastructure for high availability and low latency became an engrossing puzzle, requiring meticulous adjustments to deliver a seamless and enjoyable user experience.
Lessons Learned: The Road Not Taken
•	While the app functions flawlessly, the path to completion wasn't without its detours. Prioritizing tight deadlines meant sacrificing the exploration of incorporating accessibility standards (WCAG) to make the app usable for all individuals. This lingering "what if" underscores the importance of prioritizing long-term technical vision over short-term expediency in future endeavors.
Forging the Engineer: A Crucible of Growth
This project wasn't just about building the app; it was about building myself as an engineer. The sheer complexity initially filled me with apprehension. However, with each hurdle overcome, a newfound resilience bloomed. The project became a testament to the power of scalability and Performance Optimization. This skill not only streamlined collaboration but also served as a lifeline during moments of technical turmoil.
Charting the Course: A Future Illuminated
The knowledge gleaned from this project now serves as a roadmap, guiding my engineering journey towards exciting possibilities. The intricate dance between user experience and content delivery has ignited a passion for User Experience (UX) and User Interface (UI) Design. Furthermore, the project solidified the importance of Agile development which emphasizes iterative progress, collaboration, and flexibility in ensuring flexibility and adaptability in the face of unforeseen challenges.
Paradigm Shift: Rethinking My Approach
Prior to embarking on this project, I firmly believed that implementing standard encryption and authentication methods should be sufficient to secure the app. However, through in-depth user research and analysis of industry trends, I discovered the growing demand for protecting sensitive user data requires a multi-layered security approach, including encryption, secure authentication, real-time monitoring, and regular security audits. This shift in perspective underscores the importance of vigilance- Security is not a one-time setup but an ongoing process that involves staying updated with new threats and vulnerabilities.
Developing this adult entertainment app wasn't just about lines of code; it was a transformative journey that unveiled new technical frontiers, exposed areas for improvement, and ultimately, reshaped my approach to engineering. As I embark on future endeavors, the lessons learned on this captivating voyage will serve as a guiding star, propelling me towards a horizon filled with innovation and technical mastery.





I am Grace, a driven problem-solver, building the future with code.
I'm a software engineering student, fresh off the thrill of completing my first project! It was a challenging but rewarding experience that pushed me to learn new skills and problem-solve creatively. Now I'm excited to see where this path takes me, eager to tackle bigger projects and refine my coding abilities.

https://www.linkedin.com/in/grace-tumbo-2aba911b8
https://github.com/gracie-123


