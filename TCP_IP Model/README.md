<h1>TCP / IP Model</h1>
<p>TCP/IP stands for <strong>Transmission Control Protocol/Internet Protocol.</strong></p>
<p>It is set of rules that explains how different computers communicate with each other over network.</p>
<p>It is also called as suite of protocols used to connect network devices on internet</p>
<p>The entire IP suite -- a set of rules and procedures -- is commonly referred to as TCP/IP.</p>
<p>TCP and IP are the two main protocols, though others are included in the suite.</p>
<p>It is like a practical implementation of OSI Model</p>
<p>The TCP/IP model was developed prior to the OSI model.</p>
<p>TCP/IP is also used as a communications protocol in a private computer network -- an intranet or extranet.</p>
<h2>OSI vs TCP/IP</h2>
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/TCP_Model_7.png">
<table border="1">
  <tr>
    <th>Aspect</th>
    <th>OSI Model</th>
    <th>TCP/IP Model</th>
  </tr>
  <tr>
    <td><strong>Full Name</strong></td>
    <td>Open Systems Interconnection Model</td>
    <td>Transmission Control Protocol/Internet Protocol Model</td>
  </tr>
  <tr>
    <td><strong>Number of Layers</strong></td>
    <td>7 Layers</td>
    <td>4 Layers</td>
  </tr>
  <tr>
    <td><strong>Layers</strong></td>
    <td>Application, Presentation, Session, Transport, Network, Data Link, Physical</td>
    <td>Application, Transport, Internet, Network Access (or Link)</td>
  </tr>
  <tr>
    <td><strong>Purpose</strong></td>
    <td>Used for teaching and understanding networks.It is like blueprint.</td>
    <td>Used for real-world internet communication.It is like one implementation of blueprint</td>
  </tr>
  <tr>
    <td><strong>Layer Details</strong></td>
    <td>More detailed, each layer has a specific role</td>
    <td>Simplified, combines some OSI layers</td>
  </tr>
  <tr>
    <td><strong>Focus</strong></td>
    <td>Theoretical and comprehensive</td>
    <td>Practical and simplified</td>
  </tr>
  <tr>
    <td><strong>Usage</strong></td>
    <td>Conceptual model for network communication</td>
    <td>Practical model for actual internet use</td>
  </tr>
</table>

<h2>Layers Of TCP/IP Model</h2>
<p>The TCP/IP model is divided into four different layers:</p>
<ul>
	<li>Application layer</li>
	<li>Transport layer</li>
	<li>Network Layer</li>
	<li>Physical Layer</li>
</ul>

<h2>Application Layer</h2>
<p>The Application Layer in the TCP/IP model is a combination of three layers from the OSI model:<strong>Application, Presentation, and Session layers.</strong></p>
<p>It is reposible for following operations</p>
<ol>
	<li><strong>Application Layer (OSI)</strong></li>
	<ul>
		<li>It provides inteface for software application to communicate(to send/receive) over internet</li>
		<li>You can think of it as the top layer that interacts directly with applications that people use, like web browsers, email clients, or messaging apps. This layer handles how software applications talk to the network and exchange information with other systems.</li>
		<li>The main role of the Application Layer is to provide services and network-based functionalities (such as web-browsing,sending email,video streaming, audio streaming, file transferring and database access) directly to user applications.</li>
		<li>It specifies what actions need to be performed, such as sending an email or requesting a web page.</li>
		<li><strong>Examples :</strong></li>
		<ul>
			<li>Imagine you’re at a post office counter. The counter staff helps you package, address, and send a letter in the right format, making sure everything is done correctly so the letter reaches its destination. In the same way, the Application Layer helps prepare data so it can be properly sent and received across the network.</li>
			<li>For example, if you’re using a web browser to visit a website, the Application Layer ensures that your browser's request for data is formatted correctly and follows the rules (called protocols) needed to get a response from the web server.</li>
		</ul>
		<li>It follows some protocols,When data is sent from one computer to another, it must follow a set of rules called a protocol. The sender uses the protocol to package and send the data. The receiver uses the same protocol to understand and use the data correctly</li>
		<li><strong>Example  :</strong>When you go to the post office, they make sure you follow the rules for mailing a letter: you put it in an envelope, add stamps, and provide the right address. The Application Layer does something similar by ensuring your data is properly packaged and follows the rules of a protocol before it is sent.</li>
		<li><strong>Protocols Used in the Application Layer (OSI)</strong></li>
		<p>Protocols are like rules or languages that help devices communicate smoothly. Some common protocols include</p>
		<ol>	
			<li><strong>HTTP/HTTPS(Hyper Text Transfer Protocol/Secured HTTP) :</strong>Used for web browsing. HTTP is what allows you to view web pages. HTTPS is the secure version, which encrypts the data for privacy.</li>
			<li><strong>FTP (File Transfer Protocol) :</strong>Used for transferring files between systems, like when you download or upload files.</li>
			<li><strong>SMTP(Simple Mail Transfer Protocol)/IMAP(Internet Messenging Access Protocol)/POP3(Post Office Protocol Version-3) :</strong>These are used for sending and receiving emails. SMTP is for sending, while IMAP and POP3 are for receiving and managing emails.</li>
			<li><strong>DNS (Domain Name System):</strong>This protocol translates domain names (like www.example.com) into IP addresses that computers can use to locate websites.</li>
		</ol>
		<li>In summary, the Application Layer acts like a helpful post office worker, making sure your data is prepared, addressed, and sent correctly, using the proper "language" or protocol to communicate smoothly across the network.</li>
	</ul>
	<li><strong>Presentation Layer (OSI)</strong></li>
	<ul>
		<li>It involves how data to should be translated, encrypted and compressed before sent it over to the network.</li>
		<li>It is also called as transalation layer,This layer is also known as the Translation Layer because it translates or converts data into a form that other devices can understand, making communication possible even if systems use different data formats.</li>
		<li><strong>Example :</strong></li>
		<ul>
			<li>Imagine you are attending a business meeting where two people from different countries are speaking different languages. A translator helps them understand each other by converting the words into the language each person knows.</li>
			<li>The Presentation Layer works in a similar way: it makes sure that data from the sender is converted into a format the receiver can understand, even if the systems use different formats or data types.</li>
		</ul>
		<li><strong>Key Functions of the Presentation Layer</strong></li>
		<ol>
			<li><strong>Data Translation</strong></li>
			<ul>
				<li>The Presentation Layer translates or converts data between different formats. For instance, if you’re sending an image, it might convert the image data into a format that can be understood by the receiving device.</li>
				<li>It ensures that text data, images, and multimedia files are encoded and decoded in the correct way, making them understandable for both the sender and receiver.</li>
			</ul>
			<li><strong>Data Encryption and Decryption:</strong></li>
			<ul>
				<li><strong>Encryption</strong> is the process of converting readable data into an unreadable format to keep it secure. For example, when you make an online purchase, your payment details are encrypted.</li>
				<li><strong>Decryption</strong> is the reverse process: converting the unreadable data back into its original form so the intended recipient can understand it.</li>
				<li>This ensures that data sent over the network remains secure and private.</li>
			</ul>
			<li><strong>Data Compression and Decompression:</strong></li>
			<ul>
				<li><strong>Compression</strong> reduces the size of data to make transmission faster and more efficient. For example, compressing a large video file makes it easier to send over the internet.</li>
				<li><strong>Decompression</strong> restores the original size and quality of the data on the receiving side.</li>
				<li>This helps in optimizing network performance and reduces the amount of bandwidth needed.</li>
			</ul>
		</ol>
		<li><strong>Common Data Formats and Protocols at the Presentation Layer</strong></li>
		<ul>
			<li><strong>Image Formats: JPEG, PNG, GIF -</strong>used for image compression and formatting.</li>
			<li><strong>Audio Formats: MP3, AAC -</strong>used for audio compression.</li>
			<li><strong>Video Formats: MP4, AVI -</strong>used for video compression and transmission.</li>
			<li><strong>Text Formats: ASCII, EBCDIC -</strong>used to represent characters and text in a format that computers can understand.</li>
			<li><strong> Protocols: SSL/TLS -</strong>used to encrypt data for secure transmission, such as when you’re browsing a secure website (indicated by “https” in the URL).</li>
		</ul>
		<li><strong>How it works</strong></li>
		<ol>
			<li>1.On The Sender Side</li>
			<ul>
				<li>The Presentation Layer translates, encrypts, or compresses the data into a common format before sending it over the network.</li>
				<li><strong>Example: </>If you’re sending an image, the layer may compress the image to reduce its size and encrypt it to keep it secure.</li>
			</ul>
			<li>2.On The Receive Side</li>
			<ul>
				<li>The layer then translates the data back into its original form, decrypts it if necessary, and decompresses it if it was compressed.</li>
				<li><strong>Example: </strong>When the receiver gets the image, it is decompressed and decrypted so that it looks just like the original image.</li>
			</ul>
		</ol>
		<li>The Presentation Layer ensures that both the sender and receiver agree on how data should be formatted, encrypted, or compressed. This agreement ensures smooth communication and makes data transmission both efficient and secure.</li>
		<li>In summary, the Presentation Layer acts as a translator, security guard, and efficiency expert. It makes sure data is correctly formatted, secure, and easy to send and receive, even if different devices use different formats.</li>
	</ul>
	<li>Session Layer (OSI)</li>
	<ul>
		<li>A session in computing refers to the time period during which a user interacts with an application or a website. During this session, the application can store information about the user's activity to make the experience smoother and more personalized.</li>
		<li>It involves creating,managing and termination these communication sessions</li>
		<li><strong>Example : </strong>Imagine you visit an online store, add items to your cart, and then move to another page within the store. The store remembers what items you added to the cart. This memory is maintained through a session. When you close the browser or log out, the session ends, and your cart might get cleared if you haven’t logged in or saved it.</li>
		<li><strong>Key Functions</strong></li>
		<ol>
			<li><strong>Establishing a Session: </strong></li>
			<ul>
				<li>Before devices can exchange data, the Session Layer sets up a session. It handles the initial communication setup, deciding the terms of the connection.</li>
				<li><strong>Example: </strong>When you log into an online banking website, the Session Layer helps establish a secure session between your browser and the bank’s server.</li>
			</ul>
			<li><strong>Managing a Session: </strong></li>
			<ul>
				<li>Once the session is established, this layer manages the ongoing communication. It ensures that data flows smoothly, keeping track of the conversation and making sure everything stays organized.</li>
				<li><strong>Example: </strong>During a file transfer, the Session Layer manages the connection so that if the transfer is interrupted, it can continue from where it left off rather than starting over.</li>
			</ul>
			<li><strong>Synchronizing Data: </strong></li>
			<ul>
				<li>The Session Layer inserts “checkpoints” or synchronization points during data transmission. These are like save points in a video game. If there’s an interruption, data transmission can restart from the last checkpoint instead of going back to the beginning.</li>
				<li><strong>Example: </strong> In a large file download, if the connection drops momentarily, the Session Layer allows the download to resume from the last saved point rather than re-downloading the entire file.</li>
			</ul>
			<li><strong>Terminating a Session: </strong></li>
			<ul>
				<li>Once communication is complete, the Session Layer properly closes the session to free up resources. This is essential to ensure the system doesn’t waste memory or processing power.</li>
				<li><strong>Example: </strong>When you finish a video call on a platform like Zoom, the Session Layer terminates the session, ensuring all connections are closed cleanly.</li>
			</ul>
		</ol>
		<li><strong> Real-World Example: Video Conferencing (e.g., Zoom, Teams)</strong></li>
		<ul>
			<li><strong>Establishing the Session: </strong>When you start a Zoom call, the Session Layer sets up a connection between your device and the devices of other participants, ensuring everyone can join the same session.</li>
			<li><strong>Managing Data Flow: </strong>Throughout the call, it keeps track of participants and manages audio, video, and any data sharing to ensure smooth communication.</li>
			<li><strong>Synchronizing:	</strong>< If someone’s connection drops for a moment, the Session Layer can use checkpoints to allow that participant to rejoin seamlessly./li>
			<li><strong>Ending the Session: </strong>When the call ends, the Session Layer terminates the session, ensuring that all resources are released.</li>
		</ul>
		<li><strong>Protocols Used in the Session Layer</strong></li>
		<ol>
			<li><strong>RPC (Remote Procedure Call): </strong>Allows a program to request a service from a program on another computer without needing to understand the details of that computer’s network.(Using Public Network).RPC is like asking someone else to do a task for you, even if they are far away. You don't need to know how they do it; you just ask for the result.</li>
			<li><strong>PPTP (Point-to-Point Tunneling Protocol) : </strong> It is used to secure internet connections, especially for VPNs (Virtual Private Networks). It creates a safe "tunnel" for your data, protecting it from being intercepted or seen by others as it travels across the internet.</li>
		</ol>
		<li>In Summary, The Session Layer is crucial for organized communication between devices, handling session setup, data flow management, synchronization, and termination. It ensures that communication is reliable and efficient, making it an essential part of networking.</li>
	</ul>
</ol>