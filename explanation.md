<h1>How Browsers Work</h1>
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

<h2>Browser's Function</h2>
<p>The main function of a browser is to present the web resource you choose, by requesting it from the server and displaying it in the browser window. The resource is usually an HTML document, but may also be a PDF, image, or some other type of content. The location of the resource is specified by the user using a URI (Uniform Resource Identifier).</p>

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
