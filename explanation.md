<h1>How Browsers Work</h1>(http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
<h2>Introduction</h2>
<p>Web browsers are the most widely used software today.</p>
<p>There are five major browsers used on desktop today: 
		<ul>
		<li>Chrome</li>
		<li>Internet Explorer</li>
		<li>Firefox</li>
		<li>Safari</li>
		<li>Opera</li>
		</ul></p>

<h2>Browser's Functionality</h2>
<p>The main function of a browser is to present the web resource you choose, by requesting it from the server and displaying it in the browser window. The resource is usually an HTML document, but may also be a PDF, image, or some other type of content. The location of the resource is specified by the user using a URI (Uniform Resource Identifier).</p>
<p>The way the browser interprets and displays HTML files is specified in the HTML and CSS specifications. These specifications are maintained by the W3C (World Wide Web Consortium) organization, which is the standards organization for the web. </p>

<h2>Browser's main components</h2>
	<ol>
		<li><em><strong>User Interface</strong></em>
		<p>Includes the address bar, back/forward button, bookmarking menu, etc. Every part of the browser display except the window where you see the requested page.</p></li>
		<li><em><strong>Browser Engine</strong></em>
		<p>Marshals actions between the UI and the rendering engine.</p></li>
		<li><em><strong>The Rendering Engine</strong></em>
		<p>Responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.</p></li>
		<li><em><strong>Networking</strong></em>
		<p>For network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.</p></li>
		<li><em><strong>UI Backend</strong></em>
		<p>Used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.</p></li>
		<li><em><strong>JavaScript Interpreter</strong></em>
		<p>Used to parse and execute JavaScript code.</p></li>
		<li><em><strong>Data Storage</strong></em>
		<p>This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.</p></li>
	</ol>
	<p>The two main modules in any browser are The rendering engine also known as layout engine and JavaScript Interpreter</p>

<h2>Components of a web page</h2>(https://docs.google.com/presentation/d/1kjC_L5C-E2Y_wOVkblJxRr6GBgw1V_FBbFI4jAoh688/edit#slide=id.gc563c71b0_1_35)
	<ul>
		<li>HTML: The main component of the page/application</li>
		<li>CSS:The style of the content</li>
		<li>JavaScript: The logic of the application,sometimes also for animations, etc.</li>
	</ul>

<h2>Steps involved to render a webpage on a browser</h2>(https://varvy.com/pagespeed/display.html)
	<ul>
		<li>A request is made when a link is clicked. </li>
		<li>The page and its resources (files) are downloaded. </li>
		<li>The web browser uses the page resources to build the page. </li>
		<li>The page then is rendered (displayed) to the user. </li>
	</ul>
