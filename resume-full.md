# Mark Salisbury
fmark.salisbury@gmail.com

## about://me

* Nearly 20 years professional experience in designing, building, and maintaining software systems
* Enjoy working with and empowering others.  Teamwork!
* I thoroughly enjoy programming, designing software, testing, and improving software
* Hard-working, ambitious, curious, and organized
* Excellent problem-solving skills
* Breadth of technology skills, ranging from low level C/C++ code to backend C#/Java/PHP/SQL Database to front end JavaScript UI
* I know a ton about the inner-workings of web browsers... more on that later

## Nerdspeak

ARM, Android, **C++**, **C#**, **C**, **CMake**, COM, CSS, Digital Signatures & Encryption, **HTTP**, GTest, **HTML 5**, **Java**, **JavaScript**, **JSON**, **Linux**, MFC, MIPS, MSTest, **.NET**, **PHP**, Perl, Python, QuickBasic, QUnit, **REST**, SOAP, SQL, SSL, Unix Shell Scripting, VB/VB.Net, Web APIs, Win32, WPF, x86 Assembly, XAML, XML, Yocto.

I have deep experience with many open source projects and also with Microsoft technologies.  Contributor to several open source projects (WebKit, curl, CMake, vcpkg).

## Experience

### Aug. 2002 – Present, *Firmware Engineer*,	**HP Inc., Boise ID**

#### Localization (C++, Python), Nov 2018 - Present
* Recognized that HPs different printer business units have multiple flaws in both the localization process (making devices support multiple languages) and firmware implementation of localization.
* Led out (working with engineers in India, Spain, and the United States) on the design of a new process and firmware implementation, eliminating missing translations and minimizing firmware RAM cost of localization.  These changes will result in greater accuracy and lower cost.

#### [HP Accessibility Assistant](https://www.google.com/search?q=hp+accessibility+assistant) (C++, JavaScript), Jul 2017 - Aug 2018
* Contributor to the design and implementation of the HP Accessibility Assistant, a device and set of firmware features that make HP devices more accessible to users with disabilities (see [508 Refresh](https://www.google.com/search?q=508+refresh)).
* Though I contributed to this effort in several areas, my main deliverable was the design and implementation of a screen reader built into the browser that powers Omni UI (Enterprise Printer User Interface).
* Project was done by a team of hardware engineers and 3 software engineers – our efforts enabled HP to win hundreds of millions of dollars of contracts.

#### SysTrace WebViewer (HTML5, JavaScript), May 2014 - Present
* Developed HTML5 application to view and analyze low-level logs from HP printers; viewer shows visually how CPUs are allocating clock cycles between different tasks.  It shows key events that are occurring on the device – as well as all other log statements developers choose to trace.
* It has been instrumental in solving various performance and other defects; it’s been used by HP engineers around the globe.
* I came up for the idea of this tool fairly early in the development of the Omni UI after reading that one reason WebOS failed to take hold was poor performance.  I didn’t want our web-based UI to suffer a similar fate.

#### [Omni (Web-Based Enterprise Printer/Copier) User Interface](https://www.google.com/search?q=hp+futuresmart+4+control+panel) (C++, C#, JavaScript, CSS), Jan 2013 - Present
* Helped develop modern web-based UI for HP Printer/Copiers.  User interface has been praised by customers for responsiveness and ease of use.
* As a technical lead, worked with engineers in the US, Brazil, and India.
* Solved many technical problems – memory leaks, server driven eventing for REST based data models, key based navigation, etc.
* Made our unit test suite run FAST.  We developed a qunit based test suite.  I parallelized it to run on 8 (or more) CPU cores at a time.
* Every code integration tests our UI unit test suite of 8,000+ JavaScript driven unit tests – both behavior and screen capture based.  Test suite completes in about 3 minutes.

#### [WebKit](http://www.webkit.org) Browser (C++ / C,  HTML 5, JavaScript, ARM, MIPS & x86), Jul 2009 - Present
* Lead engineer in HP on WebKit (powers web browsers, including Safari and Chrome*).  WebKit has 3+ million lines of code.
* Worked with contractors in Canada and HP engineers in India and Korea.
* Kept WebKit up to date, adding new capabilities to our browser (like remote debugger) and created Windows CE browser platform for next generation UI.  This UI powers all HP Enterprise copiers and printers today.
* Solved challenging performance problems in our display driver more than doubling the frames per second (huge improvement in UI responsiveness).
* Lead developer of efforts to integrate WebKit browser into OZ (legacy products built on LynxOS, similar to Linux) and Jedi (new products built on Windows XP and Windows CE).  The browser is a key technology piece for OXPd 1.6, a major strategy for HP enterprise laserjet products.
* Quickly became familiar with WebKit and developed plan to make progress porting it to the target platforms.  (Project was stalled when I was brought on board in July 2009).
* Project development strategy enabled remote contract engineers to contribute, even though they don’t have access to HP’s product build environments.
* Solved complex problems, including issues with CPU architecture, compiler bugs, browser performance issues, and native to .NET (COM interop) ref counting / memory management and threading problems.
* Set up continuous integration process and created test framework, including an original scripting language to enable browser testing.
* Worked extensively on enabling webkit.org’s test suite to run on our custom browser port and fixed defects found using webkit.org’s test suite.
* Created C# webkit browser control, using .NET COM interop to communicate with native code.

#### OXPd SDKs (.NET / C#, Java, ASP.NET), Aug 2008 - Jul 2009
* Worked with senior architect responsible for OXPd 1.6 architecture to move project from prototype to production; developed initial SDK, including demo application, continuous integration process, and initial tests.

#### Jedi Extensibility SDKs (.NET / C#), Aug 2008 - Jul 2009
* Designed and implemented UI related 3rd party SDKs in firmware (Menus, Internal Pages, Help, Localization).
* Helped with some critical UI infrastructure pieces.
* Recognized (and convinced others of) supportability problems with original Menus SDK design; designed and implemented simpler solution.

#### DoD CAC (US Government Smart Card Authentication (C++/C)
* Led development work for Common Access Card (CAC) authentication and e-mail signing solution for OZ based MFP products, moving HP ahead of competitors for US Department of Defense sales.
* Integrated/ported OpenSSL and Heimdahl open source libraries.
* Created smart alloc tool, used initially for OpenSSL and Heimdahl but later used for many other libraries to help identify memory leaks by assigning unique identifiers for memory allocations without changing source code.

#### MFP Current Product Engineering Team (C++, PHP, SQL, Java)
* Delivered crucial new functionality and defects fixes to meet customer needs, often helping to make additional sales (sometimes valued in the millions of dollars).  Often worked on complex issues (like memory corruption, memory leaks, duration test issues) or parts of the system our team was not experienced with.
* A few key features delivered include:
  * **Kerberos Authentication**: I solved some key problems enabling HP to deliver a Kerberos authentication agent (authentication in enterprise environments).
  * **Simplified Address Book**:  Enabled customers to manage device address books through a web interface, including exporting and importing data, and importing contacts from Microsoft Outlook.  Delivered Local User feature on schedule despite predictions that it couldn’t be done in time for release.
  * **Authentication Manager**:  Put HP ahead of competitors in allowing pairing of specific authentication mechanisms with specific features.  Authentication had previously been added to product by separate development teams as an afterthought; I helped re-design critical aspects of authentication and put a more unified design in place.
  * **Color Copy Authentication** and **Device PIN Authentication**:  A major shortcoming in our color MFPs was the inability to require authorization to make a color copy.  I designed and implemented two features to accomplish this in a matter of weeks:  making selecting color copies an “authenticatible event” and a PIN based authentication agent.
* **Hotsite Fixes/Betas**:  I have helped HP to win/retain major customers by fixing problems in our devices considered critical by these customers, which were integrated as standard features in future firmware rolls.
* **MIMS (Mark’s Information Management System)**: Developed website / database for team, which managed many aspects of our software development lifecycle:
  *	Managed code integration requests, including integration to multiple branches and releases, and a code review process
  * Release planning – showed state of work (defects and features) for upcoming releases
  * Test requests - which governed duration testing (printing thousands of pages, performing scan and digital send operations, etc.) with automated metrics collection and Gantt chart showing test scheduling.
  * Linked test failures to defects, helping to identify trends and top issues
  * Hotsite (beta) requests – hot customer issues with short fix/release cycle
  * Website / database was successful because of a solid framework that enabled easy and rapid changes despite continually changing processes.
  * System helped make team successful despite being spread across 3 continents.
  * Developed innovative way to synchronize independent databases.
  * Team members felt that system helped dramatically with productivity.

### Aug 2013 – Oct 2014, *Software Engineer*,	**[dzinesteps.com](http://www.dzinesteps.com)** (JavaScript, MySQL)
* Designed and implemented website to help homeowners and designers visualize changes to their existing home or new home.
* Learned how to use WebGL, an API for 3D rendering in web browsers.
* Authored performant imaging algorithms in JavaScript.
* Definitely the most “start-up” environment I worked in, I didn’t receive much pay for this and wasn’t sure if it fit better in “work experience” or personal projects. ;)

### Nov 2006 – Nov 2008, *Software Engineer*,	**[www.pinpointyournewhome.com](http://www.pinpointyournewhome.com)** (PHP, JavaScript, MySQL)
* Implemented website to help locate and learn about new home communities.
* Object oriented design made changing site themes fast.
* Site heavily dependent on Google Maps API.

### Dec 2001 – Aug 2002, *Software Engineer*,	**Multimedia Data Services Corporation, Logan UT** (PHP, JavaScript, MySQL)
* Responsible for design and construction of web-based application for beef cattle ranchers.  The web application I implemented allows users to model their cattle herds and feeding operations and determine the best feeds to use to meet nutritional and weight gain criteria specific to their cattle herds.

### May 2001 – Oct 2001, *Software Engineer*,	**INL, Idaho Falls UT** (VB6, C++)
* Responsible for design and implementation of RISK Monitor, a system to support operators and managers in mission critical systems.  First implementation of RISK Monitor was for the St. Petersburg nuclear power plant, other potential implementations included International Space Station.
* Exceeded management’s expectations with RISK Monitor project in quality and speed of delivery of product.  Led team of interns in carrying out the design and implementation of RISK Monitor.

### Sep 2000 – Dec 2001, *Tutor*,	**Computer Science Department, Utah State University, Logan, UT** (C++/Java)
* Helped 10-20 students a week learn to solve computer science problems.  “In the tutor room, Mark has been one of our most popular tutors.  He is friendly and students feel immediately comfortable coming to him for help.”  Vicki Allan, Associate Professor USU.

### Dec 1999 – Sep 2001, *Undergraduate Research Assistant*,	**Space Dynamic Laboratory, Logan, UT** (C++/MFC)
* Lead programmer on team of (student) engineers developing software and hardware for experiment LADA, which flew aboard the International Space Station from 2002-2006.
* I was responsible for the software, which helped the astronaut set up the experiment, collected data as the experiment ran, and graphed probe data as it was collected.
* Software used serial interface to communicate with data logger, USB interface to communicate with webcam.  Project was MFC based.

## Personal Projects

### Sep 2018, "[Mastermind](https://mrsalt.github.io/MasterMind/)"	*HTML5 Based Game* (JavaScript)
* I play a lot of games with my kids (who are young), and tired of them breaking the rules while playing the game I spent a few hours and implemented the game in JavaScript.

### Jan 2011 - 2013, "Medieval Settlers"	*Android App* (Java, Eclipse)
* Implemented game engine, AI, and user interface, based on Settlers of Catan board game.
* Created graphics and incorporated artwork.
* Created AI test program, which has played millions of games (in a reproducible fashion) and helped me find bugs in my AI.
* I intend for app to be free, with paid expansions.  Never published, wasn't fully polished and didn't want potential legal fights.

### Jan 2009 - Nov 2009, "Dominion"	*Windows Game* (C#/ WPF)
* Implemented game engine, AI, and user interface, using C# and WPF.  Based on Dominion board game.
* Created graphics and incorporated artwork.
* Created AI test program, which has played thousands of games (in a reproducible fashion) and helped me find bugs in my AI.
* Purpose of game was to teach myself WPF and to have a little fun in the process.

### Nov 2007 - Apr 2008, "Travian Database"	*Online Game Tool* (PHP, JavaScript, MySQL, Google Maps)
*	Created website, based on Google Maps API, to help visualize changes in MMORPG Travian.  Alliance of players used website to coordinate game playing.  Working on this added a whole new dimension to the game.

### May 2006 - 2011, "www.boyscoutwebsite.com"	*Troop Progress Traking Tool* (PHP, JavaScript, MySQL)
* Created website (together with a co-worker) to help leaders and boys track progress in scouting.
* Created scripts to import merit badge and rank advancement data to keep site up to date as BSA changes requirements.
* Made site open to other troops.

### Nov 2003 - Feb 2004, "Stratego .NET"	*Windows Game* (VB.NET, C++, ActiveX)
* Created game as an opportunity to learn .NET and create a networked game.
* Main game UI control was created using C++ / ActiveX, while core game interface was written in VB.NET.

### Aug 2001 - Feb 2002, "RISK"	*Windows Game* (VB6, C++, ActiveX)
* Created game as an opportunity to get other students excited about learning new technologies and as a way to compete against each other.
* Competition was a key event for ACM chapter at USU that year.
* Main game UI control was created using C++ / ActiveX, while core game interface was written in VB 6.
* AI .dlls could be loaded dynamically as long as they were programmed using the SDK I published.

## Education

### B.S., Computer Science, Utah State University, Fall 1999 – Spring 2002
*Graduated Magna Cum Laude May 2002 3.86 GPA*
*	Worked between 20-30 hours / week in addition to participating in extra-curricular activities.
*	Selected as the *Outstanding Senior* in the Computer Science Department upon graduation.
*	Served as ACM Chapter President my senior year.
  * Organized new chapter of ACM in Computer Science Department at USU, created initial web page for club.  Organized elections of 10 officers, club had 70 members.
  * Club helped students realize academic, social, and career goals.
  * I developed a fully functional graphical RISK game.  Members of the club submitted code libraries which battled each other.  Winners received prizes from local sponsor (Staples).
  
## Personal

### Family
* My wife, Amanda, and I have 4 children with one on the way!

### Service
* I like to help with service opportunities; usually small things through my church.  I set aside two years – ’97-’99 - to serve as a missionary for my church in Ukraine.
* Boy Scouts.  I helped as a leader in a troop from 2005-2008, acting as a mentor for boys in our community.  I earned the rank of Eagle Scout at age 13.

### Hobbies
* As you can see from my Personal Projects, I enjoy programming outside of work.
* Computer/console gaming.  I enjoy strategy games (like the Civilization series), and every so often I’ll get a game going.  I also enjoy programming games, and have written a few simple games.
* Outdoors.  I enjoy hiking/backpacking and camping, mountain biking and skiing (downhill and cross-country).
* Music.  I enjoy singing in choirs – I’ve been a member of Idaho’s Hymns of Thanksgiving Choir many years.  I play the trumpet too, on occasion.


