.. _Service Level Agreement: http://www.emailhippo.com/Home/Terms

Glossary
========

..	glossary::
	:sorted:

	ACL
		**Access Control List.** 
		
		An ACL determines what networking traffic is allowed to pass and what traffic is blocked.
		
		An ACL change is sometimes required to your company firewall in order to access our API.
	
	API
		**Application Programmers Interface.**
		
		See `Wikipedia - API Definition <https://en.wikipedia.org/wiki/Application_programming_interface>`_ for 
		more information.
		
	B2B
		**Business To(2) Business**
		
		Business email hosting services are generally private, 
		enterprise grade hosting services typically hosted in either 
		private data centers or in cloud based infrastructure.
		
		Business to business refers to the activity of businesses
		sending email to clients using business email addresses.
		
	B2C
		**Business To(2) Consumer**
		
		Consumer email hosting providers are generally well known, 
		mostly web based providers such as Hotmail, Yahoo, AOL, Gmail etc.
		
		Business to consumer refers to the activity of businesses
		sending email to clients using consumer email addresses.
		
		Verifying email addresses in consumer domains is generally more 
		technically challenging than :term:`B2B`
	
	Block List
		See :term:`DNSBL`.
	
	BSON
		**Binary Object Notation**
		
		See `Wikipedia - BSON <https://en.wikipedia.org/wiki/BSON>`_ 
		for further information.
	
	CORS
		**Cross Origin Resource Scripting**
		
		Allows modern browsers to work with script (e.g. JavaScript) and :term:`JSON` data 
		originating form other domains.
		
		CORS is required to allow client script such a JavaScript, jQuery or AngularJS to 
		work with results returned from an external :term:`RESTful` :term:`API`.
		
		See `Wikipedia - CORS <https://en.wikipedia.org/wiki/Cross-origin_resource_sharing>`_ for 
		more information.
	
	DDoS
		**Distributed Denial of Service**
		
		See `Wikipedia - Denial-of-service attack <https://en.wikipedia.org/wiki/Denial-of-service_attack>`_ for 
		more information.
	
	DEA
		**Disposable Email Address**
		
		There are many services available that permit users to 
		use a one-time only email address. Typically, these email 
		addresses are used by individuals wishing to gain access 
		to content or services requiring registration of email 
		addresses but same individuals not wishing to divulge 
		their true identities (e.g. permanent email addresses).

		DEA addresses should not be regarded as valid for email 
		send purposes as it is unlikely that messages sent to 
		DEA addresses will ever be read.

	ESP
		**Email Service Provider**
		
		A service that sends emails on your behalf.
		
		See 
		`Wikipedia - Email service provider (marketing) <https://en.wikipedia.org/wiki/Email_service_provider_(marketing)>`_ for 
		more information.

	HTTP
		**Hypertext Transfer Protocol**
		
		See `Wikipedia - Hypertext Transfer Protocol <https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol>`_ for 
		more information.
	
	Grey Listing
		A technique used in mail servers as an anti-spam technique.
		Sometimes also known as \"deferred\", grey listing arbitrarily 
		delays the delivery of emails with a \"try again later\" response 
		to the client sending the email.
		
		See `Wikipedia - Grey Listing <https://en.wikipedia.org/wiki/Greylisting>`_ for more 
		information.
		
	JSON
		**JavaScript Object Notation**
		
		JavaScript Object Notation, is an open standard format that uses 
		human readable text to transmit data objects consisting of attribute value pairs. 
		It is used primarily to transmit data between a server and web application, 
		as an efficient, modern alternative to XML.
		
		See `Wikipedia - JSON <https://en.wikipedia.org/wiki/JSON>`_ for more information.
		
	License Key
		License key authentication is best for situations
		where simplicity is required and you can keep the key private.
		An ideal use case for key authentication would be for server 
		based applications calling the RESTful :term:`API`.
		
		`Click here <https://api.emailverifyapi.com/GetLicense>`_ to request a license key.
	
	DNS
		**Domain Name System**
		
		At its simplest level, DNS converts text based queries (e.g. a domain name) 
		into IP addresses.
		
		DNS is also responsible for providing the :term:`MX` records needed to locate a
		domains mail servers.
		
		See `Wikipedia - Domain Name System <https://en.wikipedia.org/wiki/Domain_Name_System>`_ 
		for more information.
	
	DNSBL
		**DNS Block List**
		
		As an anti-spam measure, mail servers can use spam black lists 
		to 'look up' the reputation of IP addresses and domains sending 
		email. If an IP or domain is on a block list, the mail server may 
		reject the senders email message.
		
		See `Wikipedia - DNSBL <https://en.wikipedia.org/wiki/DNSBL>`_ for more information.
		
	Free Mail
		Addresses served by popular :term:`B2C` service providers such as Hotmail, Yahoo, Live, AOL, Gmail and so on.
	
	IP Address
		**Internet Protocol** Address
		
		See `Wikipedia - IP Address <https://en.wikipedia.org/wiki/IP_address>`_ for more information.
	
	ISO 3166
		International standard for country codes.
		
		See `Country Codes - ISO 3166 <http://www.iso.org/iso/country_codes>`_ for more information.
	
	ms
		Milliseconds.
	
	MX
		**Mail Exchanger**
		
		The MX is a server responsible for email interchange with a client.
	
	NDR
		**Non Delivery Report**
		
		A message that is returned to sender stating that delivery of an email address was not possible.
		
		See `Wikipedia - Bounce message <https://en.wikipedia.org/wiki/Bounce_message>`_ for more information.
	
	Office 365
		Office 365 mail servers (e.g. x-com.mail.protection.outlook.com) are always configured 
		with the catch all policy, accepting all emails sent to the domain and redirecting them 
		to a central email box for manual inspection. Catch all configured servers cannot 
		respond to requests for email address verification.
		
		This does not affect our coverage of Hotmail, Live and Outlook mailboxes.
	
	protobuf
		Protocol Buffers is a method of serializing structured data.
	
		See `Wikipedia - Protocol Buffers <https://en.wikipedia.org/wiki/Protocol_Buffers>`_ for more information.
	
	Punycode
		Punycode is a way to represent Unicode with the limited character 
		subset of ASCII supported by the Domain Name System.
	
		See `Wikipedia - Punycode <https://en.wikipedia.org/wiki/Punycode>`_ for more information.
	
	RESTful
		**Representational state transfer**
		
		See `Wikipedia - RESTful <https://en.wikipedia.org/wiki/Representational_state_transfer>`_ 
		for further information.
	
	RFC
		**Request for Comments**
		
		The principal technical development and standards-setting bodies for The Internet.
		
		See `Wikipedia - Request for Comments <https://en.wikipedia.org/wiki/Request_for_Comments>`_ 
		for further information.
	
	Role Address
		A role address is a generic mailbox such as info@<domain>, sales@<domain> used by organizations to manage email messages of similar 
		organizational types. For example, email messages sent to sales@<domain> can be routed to an organizations sales team where a team of sales 
		people can deal with enquiries.
		
		Role addresses allow collaborative working based on groups rathert than indiviidual mailboxes.
	
	SLA
		**Service Level Agreement**
		
		See `Wikipedia - SLA <https://en.wikipedia.org/wiki/Service-level_agreement>`_ for more information and description of SLA.
		
		See our `Service Level Agreement`_.
	
	SMTP
		**Simple Mail Transport Protocol**
		
		SMTP is a protocol. It is the sequence of commands and responses between a client (the 
		software sending an email) and server (the software receiving an email) that facilitates
		the sending and receiving of email between computer based email messaging systems.
		
	Spam Trap
		Spam traps are email addresses used for the sole purpose of detecting spamming activities.
		
		Spam traps are used by many block lists (:term:`DNSBL`) to detect spammers.
		
		For more information, see `Wikipedia - Spam Traps <https://en.wikipedia.org/wiki/Spamtrap>`_.
		
	TXT
		TXT records associate arbitary and unformatted text with a domain. TXT records uses include Sender Policy Framework (SPF) and other domain validation applications.
		
		For more information, see `Wikipedia - TXT record <https://en.wikipedia.org/wiki/TXT_record>`_.
	
	XML
		**e(X)tensible Markup Language**
		
		See `Wikipedia - XML <https://en.wikipedia.org/wiki/XML>`_ 
		for further information.
		
