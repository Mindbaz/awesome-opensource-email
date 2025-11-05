<p align="center">
  <a href="https://github.com/Mindbaz/awesome-opensource-email/">
    <img src="https://github.com/Mindbaz/awesome-email/blob/main/assets/icone.png" alt="Awesome Opensource Email">
  </a>
</p>

# awesome-opensource-email
Awesome Opensource Email Resources

A curated list of resources on Email tools, server, framework, technology...

## Sponsors

<p align="center">
  <a href="https://www.sweego.io/" target="_blank">
    <img src="https://www.sweego.io/wp-content/uploads/2023/12/logo_sweego.svg" alt="Sweego Logo" width="300">
  <br>Sweego is a multichannel notification platform for developers
  </a>
</p>
<br>
<p align="center">
  <a href="https://www.sweego.io/" target="_blank">
    <img src="https://www.mindbaz.com/wp-content/uploads/2024/02/mindbaz-bleu.png" alt="Mindbaz Logo" width="300">
  <br>Mindbaz is an email marketing service provider
  </a>
</p>

## Table of Contents

- [Sending](#sending)
  - [SMTP Server](#smtp-server)
  - [Email Testing Application](#email-testing-application)
  - [IMAP/POP Server](#imappop-server)
  - [JMAP Server & others](#jmap-server--others)
  - [Complete Email Server](#complete-email-server)
  - [SPAM Filtering](#spam-filtering)
  - [Inbox API](#inbox-api)
  - [Forwarding](#forwarding)
  - [SMTP Testing](#smtp-testing)
  - [Inbound](#inbound)
- [Deliverability](#deliverability)
  - [Email Verification](#email-verification)
  - [Reputation](#reputation)
- [Email Platform](#email-platform)
  - [Marketing Platform](#marketing-platform)
  - [Newsletter Platform](#newsletter-platform)
- [Code](#code)
  - [Framework](#framework)
  - [Templating](#templating)
  - [Library](#library)
  - [Other](#other)
- [Editing](#editing)
  - [Email Builder & Visual Editing Component](#email-builder--visual-editing-component)
- [Email Solution](#email-solution)
  - [Groupware / Webmail](#groupware--webmail)
  - [CLI](#cli)
- [Security](#security)
  - [Security Check](#security-check)
  - [DMARC](#dmarc)
  - [Privacy](#privacy)
- [Disposable emails domain list](#disposable-emails-domain-list)
- [Other](#other)

  

## Sending
### SMTP Server

- [Postfix](http://www.postfix.org/) - The most famous email server - `IPL-1.0`, `C`
- [KumoMTA](https://github.com/KumoCorp/kumomta) - The first Open-Source high-performance MTA developed from the ground-up for high-volume email sending environments. - `Rust`, `Lua`
- [Haraka](https://haraka.github.io/) - A modern, high performance, flexible SMTP server - `Nodejs`
- [Zone-MTA](https://github.com/zone-eu/zone-mta) - Modern outbound MTA cross platform and extendable server application - `Nodejs`
- [Postal](https://github.com/postalserver/postal) - A fully featured open source mail delivery platform for incoming & outgoing e-mail 
- [Maddy](https://github.com/foxcpp/maddy) -  Composable all-in-one mail server - `GPLv3`, `Go`
- [Chasquid](https://github.com/albertito/chasquid) - SMTP (email) server with a focus on simplicity, security, and ease of operation - `Ruby`
- [MailWhale](https://github.com/muety/mailwhale) - A bring-your-own-SMTP-server mail relay with REST API and web UI 
- [Cuttlefish](https://github.com/mlandauer/cuttlefish) - Transactional email server with a lovely web interface - `AGPLv3`, `Ruby`
- [DragonFly](https://github.com/corecode/dma) - A small MTA for home and office use - `Linux`, `UNIX`, `BSD`, `C`
- [hMailServer](https://www.hmailserver.com/) - A user friendly IMAP, SMTP and POP3 server with admin GUI and spam protection. - `Windows`, `AGPLv3`, `C++`
- [EmailRelay](https://emailrelay.sourceforge.net/) - A small SMTP and POP3 server that is easy to configure - `Windows`, `Linux`, `OpenWrt`, `GPLv3`, `C++`
- [SMTPRelay](https://github.com/decke/smtprelay) -  Simple Golang SMTP relay/proxy server - `MIT`, `Go`
- [James](https://github.com/apache/james-project) - James stands for Java Apache Mail Enterprise Server! - `Apache License Version 2.0`, `Java`


### Email Testing Application

- [Blackhole](https://github.com/kura/blackhole) -  Blackhole is an MTA written on top of asyncio, utilising async and await statements that dumps all mail it receives to /dev/null.
- [SMTP4dev](https://github.com/rnwood/smtp4dev) - the fake smtp email server for development and testing 
- [Maildev](https://github.com/maildev/maildev) -  mailbox SMTP Server + Web Interface for viewing and testing emails during development.
- [Inbucket](https://github.com/inbucket/inbucket) - Disposable webmail server (similar to Mailinator) with built in SMTP, POP3, RESTful servers; no DB required. 
- [Opentrashmail](https://github.com/HaschekSolutions/opentrashmail) - Selfhosted trashmail solution - Receive Emails via Web UI, JSON API and RSS feed
- [TestMSG](https://github.com/yaroslaff/testmsg) - Generate RFC-compliant e-mail messages for sending over SMTP. DKIM signed (optionally). - `MIT`, `Python`

### IMAP/POP Server

- [Wildduck](https://wildduck.email/) -  Modern mail server software for IMAP and POP3. Modern being scalable, Unicode-first, and API-controlled
- [Dovecot](https://github.com/dovecot/core) -  Dovecot mail server 
- [Cyrus](https://github.com/cyrusimap/cyrus-imapd) - Cyrus IMAP is an email, contacts and calendar server
- [James](https://github.com/apache/james-project) - James stands for Java Apache Mail Enterprise Server! - `Apache License Version 2.0`, `Java`


### JMAP Server & others
- [JMAP](https://github.com/jmapio/jmap) -  JSON Meta Application Protocol Specification (JMAP) Specification
- [James](https://github.com/apache/james-project) - James stands for Java Apache Mail Enterprise Server! - `Apache License Version 2.0`, `Java`
- [Gomap](https://github.com/cwinters8/gomap) -  Go module for interfacing with JMAP servers 


### Complete Email Server

- [Mailu](https://github.com/Mailu/Mailu) -  Insular email distribution - mail server as Docker images 
- [iRedMail](https://iredmail.org/) - Open Source Mail Server Solution
- [Erooster Email Server](https://github.com/erooster-mail/erooster) -  A mail suite written in rust meant to be easy to use. 
- [Zimbra Open Source Edition](https://github.com/Zimbra/zm-build) - A full featured email service.
- [Modoboa](https://modoboa.org/en/) - Modoboa brings together Open Source's finest in a single interface.
- [Mailinabox](https://github.com/mail-in-a-box/mailinabox) - Mail-in-a-Box helps individuals take back control of their email by defining a one-click, easy-to-deploy SMTP+everything else server: a mail server in a box.
- [Excision-Mail](https://github.com/Excision-Mail/Excision-Mail) -  Fullstack, security focused, personal mail server based on OpenSMTPD for OpenBSD `ISC License`
- [Docker Mailserver](https://github.com/docker-mailserver/docker-mailserver) -  Production-ready fullstack but simple mail server (SMTP, IMAP, LDAP, Antispam, Antivirus, etc.) running inside a container.  - `MIT`
- [Mox](https://github.com/mjl-/mox) -  modern full-featured open source secure mail server for low-maintenance self-hosted email - `MIT`, `Go`
- [Stalwart](https://github.com/stalwartlabs/mail-server) -  Secure & Modern All-in-One Mail Server (IMAP, JMAP, POP3, SMTP) - `GNU AGPLv3` & `Stalwart Enterprise License 1.0 (SELv1) Agreement`, `Rust`
- [Forward Email](https://github.com/forwardemail/forwardemail.net) - All-in-one 100% open-source mail server alternative to Gmail/Mailchimp/Sendgrid (IMAP, POP3, SMTP, CalDAV) - `BUSL-1.1` & `MPL-2.0`, `JavaScript`

### SPAM Filtering

- [Rspamd](https://github.com/rspamd/rspamd) - Advanced spam filtering system and email processing framework.
- [AgentJ](https://github.com/Probesys/agentj) -  AgentJ is a free software anti-spam solution with human authentication and admin panel - `AGPL`, `PHP`
- [Spamscope](https://github.com/SpamScope/spamscope) -  Fast Advanced Spam Analysis Tool. 
- [ASSP](https://sourceforge.net/p/assp/wiki/Main_Page/) - The Anti-Spam SMTP Proxy (ASSP).
- [Spamassassin](https://spamassassin.apache.org/) - Open Source anti-spam platform - `Apache License Version 2.0`, `Perl`, `C`
- [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway/overview) - Full-featured, open-source mail proxy and protects your mail server from spam, viruses, trojans, and phishing emails - `GNU AGPLv3`

### Inbox API

### Forwarding

- [Anonaddy](https://github.com/anonaddy/anonaddy) -  Anonymous email forwarding 

### SMTP Testing

- [MailHog](https://github.com/mailhog/MailHog) - Web and API based SMTP testing  - `MIT`, `Go`
- [MailCatcher](https://mailcatcher.me/) - Catches mail and serves it via a webui  - `MIT`, `Ruby`
- [MailCrab](https://github.com/tweedegolf/mailcrab) - Email test server for development, written in Rust - `Apache License`, `Rust`
- [MailPit](https://github.com/axllent/mailpit) - An email and SMTP testing tool with API for developers  - `MIT`, `Go`
- [Robin](https://github.com/mimecast/robin) -  Debug and development tool for MTA architects! Robin is a highly configurable SMTP client for testing and debugging SMTP servers. - `Java`, `Apache License 2.0`

### Inbound - Mail Parser

- [Inbound SMTP to Webhook](https://github.com/sendbetter/inbound-email) - Receive email and sent parsed content/headers to webhook, attachments to S3.
- [Mail-Parser](https://github.com/SpamScope/mail-parser) -  A tool that parses emails by enhancing the Python standard library, extracting all details into a comprehensive object. `Apache License 2.0`, `Python`
- [Libratom](https://github.com/libratom/libratom) -  Python library and supporting utilities to parse and process PST and mbox email sources  - `MIT`, `Python`

## Deliverability

### Email Verification

- [CustomerOS MailSherpa](https://github.com/customeros/mailsherpa) - A CLI for verifying email address deliverability over SMTP without sending an email. - `AGPL-3.0`, `Go`
- [Reacher](https://github.com/reacherhq) - Check if an email exists without sending any email. - `Dual Licence Commercial/AGPL`, `Rust`
- [Email-Verifier](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.  - `MIT`, `Go`
- [Mailchecker](https://github.com/FGRibreau/mailchecker) - Cross-language email validation. Backed by a database of over 55 000 throwable email domains.
- [EmailValidator](https://github.com/egulias/EmailValidator) - PHP Email address validator
- [Truemail](https://github.com/truemail-rb/truemail) - Configurable framework agnostic plain Ruby email validator/verifier. Verify email via Regex, DNS, SMTP and even more. Be sure that email address valid and exists.  - `MIT`, `Ruby`
- [email-validator-js](https://github.com/devmehq/email-validator-js) -  Verify email address checking MX records, and SMTP connection, check for disposable email addresses and free email providers. - `MIT`, `Typescript`
- [python-email-validator](https://github.com/JoshData/python-email-validator) -  A robust email syntax and deliverability validation library for Python.  `The Unlicense`, `Python`
- [validate-email](https://github.com/centminmod/validate-emails) -  Self-hosted email verification script to clean up bad invalid email address lists. Supports various commercial email verification provider APIs all in one script - `PHP`
- [Selfsend - email-sanitizer-api](https://github.com/SelfSend/email-sanitizer-api) - A high-performance and secure REST/GraphQL API built with Rust, MongoDB & Redis for cleaning email subscriber lists. Maintains sender reputation by validating, deduplicating, and pruning inactive emails.  - `MIT`, `Rust`

### Reputation

- [Google Postmaster Datas](https://github.com/Mindbaz/python-gpostmaster-domains-datas) - Downloads and flattends datas from Google Postmaster Tools (GPT)
- [Python Hetrixtools Blacklist](https://github.com/Mindbaz/python-hetrixtools-blacklist) - Tool to retrieve @hetrixtools data from their API and store them in flat file or in a database

## Email Platform

### Marketing Platform

- [Mautic](https://github.com/mautic/mautic) - Open Source Marketing Automation Software
- [Sendportal](https://github.com/mettle/sendportal) - Open-source self-hosted email marketing. Manage your own newsletters at a fraction of the cost.
- [Ferdinand](https://github.com/valyentdev/ferdinand) -  Open-source email delivery service for developers. `GNU Affero General Public License v3.0`, `templ`, `javascript`, `Go`
- [Plunk](https://github.com/useplunk/plunk) - Open-Source Email Platform - `GNU Affero General Public License v3.0`, `typescript`

### Newsletter Platform

- [Listmonk](https://github.com/knadh/listmonk) - High performance, self-hosted, newsletter and mailing list manager with a modern dashboard. Single binary app. 
- [Mailtrain](https://github.com/Mailtrain-org/mailtrain) -  Self hosted newsletter app
- [Keila](https://github.com/pentacent/keila) - Keila is an Open Source alternative to newsletter tools like Mailchimp or Sendinblue.
- [phplist3](https://github.com/phpList/phplist3) - Fully functional Open Source email marketing manager for creating, sending, integrating, and analysing email campaigns and newsletters.
- [MailCarrier](https://github.com/mailcarrierapp/mailcarrier) - Mailing platform with templates and logs included. - `MIT`, `php`, `Laravel`
- [RSS2Newsletter](https://github.com/ElliotKillick/rss2newsletter) - Convert RSS/Atom feed to email newsletters - `GNU Affero General Public License v3.0`, `Python`
- [Notifuse](https://github.com/Notifuse/notifuse) - Notifuse is an open-source & modern emailing platform - `GNU Affero General Public License v3.0`, `go`, `typescript`


## Code

### Framework

- [MJML](https://github.com/mjmlio/mjml) - Framework to make responsive-email easy 
- [Maizzle](https://github.com/maizzle/framework) -  HTML email development framework 

### Templating

- [Cerberus](https://github.com/TedGoas/Cerberus) -  A few simple, but solid patterns for responsive HTML email templates and newsletters. Even in Outlook and Gmail.
- [HEML](https://heml.io/) -  HEML is an open source markup language for building responsive email. 
- [Hermes](https://github.com/matcornic/hermes) -  Golang package that generates clean, responsive HTML e-mails for sending transactional mail
- [Maud](https://github.com/lambda-fairy/maud) - Compile-time HTML templates for Rust  - `MIT`, `Apache License`, `Rust`
- [Foundation for Emails 2](https://github.com/foundation/foundation-emails) -  Quickly create responsive HTML emails that work on any device and client. Even Outlook. - `MIT`, `HTML`
- [Inky](https://github.com/foundation/inky) - Convert a simple HTML syntax into tables compatible with Foundation for Emails. 

### Library

- [ballerina-email](https://github.com/ballerina-platform/module-ballerina-email) - Easy to use, yet comprehensive library for sending mails with Ballerina - `Apache 2.0`, `Ballerina`
- [go-smtp](https://github.com/emersion/go-smtp) - An SMTP client & server library written in Go - `MIT`, `Go`
- [go-mail](https://github.com/wneessen/go-mail) - Easy to use, yet comprehensive library for sending mails with Go - `MIT`, `Go`
- [go-msgauth](https://github.com/emersion/go-msgauth) -  🔏 A Go library and tools for DKIM, DMARC and Authentication-Results  - `MIT`, `Go`
- [lettre](https://github.com/lettre/lettre) - a mailer library for Rust - `MIT`, `Rust`
- [mailparse](https://github.com/staktrace/mailparse) - Rust library to parse mail files - `BSD Zero Clause`, `Rust`
- [Nette Mail](https://github.com/nette/mail) - Handy email creation and transfer library for PHP with both text and MIME-compliant support.
- [Stampie](https://github.com/Stampie/Stampie) - Library for using online Email providers for PHP
- [Play-Mailer](https://github.com/playframework/play-mailer) - Play mailer plugin for Scala
- [Sisimai](https://libsisimai.org/) - Mail Analyzing Interface: A library to parse RFC5322 bounce emails and generating structured data as JSON from parsed results. For Perl, Go & Ruby
- [MailKit](https://github.com/jstedfast/MailKit) -  A cross-platform .NET library for IMAP, POP3, and SMTP.
- [MimeKit](https://github.com/jstedfast/MimeKit) -  A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
- [Nodemailer](https://nodemailer.com/) - A Node.js library
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) -  The classic email sending library for PHP
- [Anymail](https://github.com/anymail/django-anymail/) - Django email backends and webhooks for multiple ESP - `BSD 3-Clause`, `Python`
- [Swoosh](https://github.com/swoosh/swoosh) -  Compose, deliver and test your emails easily in Elixir - `MIT`, `Elixir`

### Other

- [Can I email](https://github.com/hteumeuleu/caniemail) - Can I email… Support tables for HTML and CSS in emails.
- [Premail](https://github.com/peterbe/premailer/) -  Turns CSS blocks into style attributes `BSD 3-Clause`, `Python`
- [HowToTarget.email](https://github.com/customerio/howtotarget) - How to target email clients for email development.
- [Email CSS Resets](https://github.com/JayOram/email-css-resets/tree/main) - List of email CSS normalise/resets.
- [Vue-Email](https://github.com/vue-email/vue-email) - Write email templates with vue  - `MIT`, `Typescript`

## Editing

### Email Builder & Visual Editing Component

- [LePatron](https://github.com/Badsender-com/LePatron.email) -  LePatron is an opensource email builder allowing to industrialize your email template production. Build tailor made email templates and make them available to your non-technical users. 
- [Mosaico](https://github.com/voidlabs/mosaico) - Responsive Email Template Editor 
- [React Email Editor](https://github.com/unlayer/react-email-editor) -  Drag-n-Drop Email Editor Component for React.js 
- [Vue Email Editor](https://github.com/unlayer/vue-email-editor) -  Drag-n-Drop Email Editor Component for Vue.js 
- [GrapesJS](https://github.com/artf/grapesjs) - Free and Open source Web Builder Framework. Next generation tool for building templates without coding 
- [MySigMail Card](https://github.com/mysigmail/card) - An open source html email template builder with drag & drop editor 
- [Easy Email](https://github.com/zalify/easy-email) -  DnD Email Editor based on React.js and MJML. 
- [Paperbits emails](https://github.com/paperbits/paperbits-emails) - Paperbits editors and generators for email templates.
- [Drag-and-Drop-Email-Designer](https://github.com/SendWithSES/Drag-and-Drop-Email-Designer) - Drag and drop HTML email designer - `MIT`, `Typescript`
- [email-builder-js](https://github.com/usewaypoint/email-builder-js) -  A free and open-source block-based email template builder - `MIT`, `Typescript`


## Email Solution
### Groupware / Webmail

- [Bluemind](https://www.bluemind.net/en/) - Collaborative messaging solution
- [Roundcube](https://github.com/roundcube/roundcubemail) -  The Roundcube Webmail suite - `GPLv3`, `PHP`
- [Tutanota](https://github.com/tutao/tutanota) - Tutanota is an email service with a strong focus on security and privacy that lets you encrypt emails, contacts and calendar entries on all your devices. 
- [Mailcow](https://mailcow.email/) - The mailserver suite with the 'moo' – 🐮 + 🐋 = 💕
- [Cypht](https://github.com/cypht-org/cypht) -  Cypht: Lightweight Open Source webmail written in PHP and JavaScript - `GNU Lesser General Public License v2.1`, `PHP`, `Javascript`
- [Egroupware](https://github.com/EGroupware/egroupware) - Web based groupware server written in PHP - `GPLv2`, `PHP`

### CLI
- [Himalaya](https://github.com/soywod/himalaya) - CLI to manager email - `MIT`, `Rust`

## Security

### Security Check

- [Trustymail](https://github.com/cisagov/trustymail) -  Scan domains and return data based on trustworthy email best practices
- [mailsec-check](https://github.com/foxcpp/mailsec-check) -  Another utility to analyze state of deployment of security-related email protocols.
- [E-Mail Header Analyzer](https://github.com/cyberdefenders/email-header-analyzer) - E-Mail Header Analyzer
- [Domain Security Scanner](https://github.com/GlobalCyberAlliance/domain-security-scanner) -  Scan domains and receive advice based on their BIMI, DKIM, DMARC, and SPF records - `Apache License version 2.0`, `Go`
- [Mailgoose](https://github.com/CERT-Polska/mailgoose) -  A web application that allows the users to check whether their SPF, DMARC and DKIM configuration is set up correctly. - `BSD 3-Clause "New" or "Revised" License`, `Python`
- [mxcheck](https://github.com/steffenfritz/mxcheck) -  mxcheck is an info and security scanner for e-mail servers. `GPL v-3`, `Go`
- [Spamhaus-Intelligence-API-CLI](https://github.com/Mindbaz/Spamhaus-Intelligence-API-CLI) -  CLI to query Spamhaus Intelligence API `GPL v-3`, `Python`


### DMARC

- [parsedmarc](https://github.com/domainaware/parsedmarc) -  A Python package and CLI for parsing aggregate and forensic DMARC reports  - `Apache License version 2.0`, `Python`
- [dmarc-report-converter](https://github.com/tierpod/dmarc-report-converter) - Convert DMARC report files from xml to human-readable formats
- [Open DMARC Analyzer](https://github.com/userjack6880/Open-DMARC-Analyzer) -  Open DMARC Analyzer is an Open Source DMARC Report Analyzer to be used with DMARC reports that have been parsed by John Levine's rrdmarc script or techsneeze's dmarcts-report-parser. 
- [DmarcSrg](https://github.com/liuch/dmarc-srg) -  A php parser, viewer and summary report generator for incoming DMARC reports.
- [dmarcts-report-parser](https://github.com/techsneeze/dmarcts-report-parser) -  A Perl based tool to parse DMARC reports from an IMAP mailbox or from the filesystem, and insert the information into a database. ( Formerly known as imap-dmarcts ) - `GNU GPL v3`, `Perl`
- [checkdmarc](https://github.com/domainaware/checkdmarc) -  A parser for SPF and DMARC DNS records - `Apache License version 2.0`, `Python`
- [Viesti-Reports](https://github.com/antedebaas/Viesti-Reports) - DMARC & SMTP-TLS Reports processor and visualizer and BIMI file hoster - `GPL v2`, `PHP`


### Privacy

- [SimpleLogin](https://github.com/simple-login/app) - Protect your online identity with email alias

### Disposable emails domain list
- [disposable-email-domains](https://github.com/disposable-email-domains/disposable-email-domains) - a list of disposable and temporary email address domains - `Public Domain`, `Python`
- [disposable-email-domains (another one)](https://github.com/amieiro/disposable-email-domains) -  Disposable email domain lists, used in disposable email services, generated every quarter of an hour, in txt and JSON format. - `MIT`, `PHP`
- [disposable](https://github.com/disposable/disposable) -  A list of disposable/temporary email address domains - `MIT`, `Python`
- [disposable-email-domains (another one too)](https://github.com/kslr/disposable-email-domains) -  Anti-cheating, temporary (disposable/throwaway) email list - `MIT`, `Javascript`
- [email_data](https://github.com/fnando/email_data) -  This project is a compilation of datasets related to emails. Includes disposable emails, disposable domains, and free email services.  - `MIT`, `Ruby`
- [disposable-email-domain-list](https://github.com/groundcat/disposable-email-domain-list) -  A list of disposable email domains, cleaned and validated by scanning MX records. - `MIT`, `Python`

## Other
- [Email-Expiration-Manager](https://github.com/Mindbaz/Email-Expiration-Manager) - Thunderbird extension for managing emails with expiration dates  - `GPL v-3`, `Javascript`
