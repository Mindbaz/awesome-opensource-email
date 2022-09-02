<p align="center">
  <a href="https://github.com/Mindbaz/awesome-email">
    <img src="https://github.com/Mindbaz/awesome-email/blob/main/assets/icone.png" alt="Awesome Opensource Email">
  </a>
</p>

# awesome-email
Awesome Opensource Email Resources

A curated list of resources on Email tools, technology...

## Contents

## Sending
### SMTP Server

- [Postfix](http://www.postfix.org/) - The most famous email server
- [Haraka](https://haraka.github.io/) - A modern, high performance, flexible SMTP server in node
- [Zone-MTA](https://github.com/zone-eu/zone-mta) - Modern outbound MTA cross platform and extendable server application in node
- [Postal](https://github.com/postalserver/postal) - A fully featured open source mail delivery platform for incoming & outgoing e-mail 
- [vSMTP](https://github.com/viridIT/vSMTP) - a next-gen mail transfer agent (MTA) written in Rust. Faster and Greener.
- [Maddy](https://github.com/foxcpp/maddy) -  Composable all-in-one mail server.
- [Chasquid](https://github.com/albertito/chasquid) - SMTP (email) server with a focus on simplicity, security, and ease of operation
- [MailWhale](https://github.com/muety/mailwhale) - A bring-your-own-SMTP-server mail relay with REST API and web UI 
- [Cuttlefish](https://github.com/mlandauer/cuttlefish) - Transactional email server with a lovely web interface

### Email Testing Application

- [Blackhole](https://github.com/kura/blackhole) -  Blackhole is an MTA written on top of asyncio, utilising async and await statements that dumps all mail it receives to /dev/null.
- [SMTP4dev](https://github.com/rnwood/smtp4dev) - the fake smtp email server for development and testing 
- [Maildev](https://github.com/maildev/maildev) -  mailbox SMTP Server + Web Interface for viewing and testing emails during development.
- [Inbucket](https://github.com/inbucket/inbucket) - Disposable webmail server (similar to Mailinator) with built in SMTP, POP3, RESTful servers; no DB required. 
- [Opentrashmail](https://github.com/HaschekSolutions/opentrashmail) - Selfhosted trashmail solution - Receive Emails via Web UI, JSON API and RSS feed

### IMAP/POP Server

- [Wildducj](https://wildduck.email/) -  Modern mail server software for IMAP and POP3. Modern being scalable, Unicode-first, and API-controlled
- [Dovecot](https://github.com/dovecot/core) -  Dovecot mail server 
- [Cyrus](https://github.com/cyrusimap/cyrus-imapd) - Cyrus IMAP is an email, contacts and calendar server

### Complete Email Server

- [Mailu](https://github.com/Mailu/Mailu) -  Insular email distribution - mail server as Docker images 
- [iRedMail](https://iredmail.org/) - Open Source Mail Server Solution
- [Erooster Email Server](https://github.com/erooster-mail/erooster) -  A mail suite written in rust meant to be easy to use. 


### SPAM Filtering

- [Rspamd](https://github.com/rspamd/rspamd) - Advanced spam filtering system and email processing framework
- [Spamscope](https://github.com/SpamScope/spamscope) -  Fast Advanced Spam Analysis Tool 

### Inbox API

- [EmailEngine App](https://emailengine.app/) - Headless email client that makes IMAP and SMTP resources available over REST

### Forwarding

- [Forward Email](https://github.com/forwardemail/free-email-forwarding) - The best free email forwarding for custom domains. Visit our website to get started (SMTP server) 

### SMTP Testing

- [MailHog](https://github.com/mailhog/MailHog) - Web and API based SMTP testing 
- [MailCatcher](https://mailcatcher.me/) - Catches mail and serves it via a webui

## Delivrability

### Email Verification

- [Reacher](https://github.com/reacherhq) - Check if an email exists without sending any email.
- [Mailchecker](https://github.com/FGRibreau/mailchecker) - Cross-language email validation. Backed by a database of over 55 000 throwable email domains.

### Reputation

- [Google Postmaster Datas](https://github.com/Mindbaz/python-gpostmaster-domains-datas) - Downloads and flattends datas from Google Postmaster Tools (GPT) 

## Email Platform

### Marketing Platform

- [Mautic](https://github.com/mautic/mautic) - Open Source Marketing Automation Software
- [Sendportal](https://github.com/mettle/sendportal) - Open-source self-hosted email marketing. Manage your own newsletters at a fraction of the cost. 

### Newsletter Platform

- [Listmonk](https://github.com/knadh/listmonk) - High performance, self-hosted, newsletter and mailing list manager with a modern dashboard. Single binary app. 
- [Mailtrain](https://github.com/Mailtrain-org/mailtrain) -  Self hosted newsletter app 

## Code

### Framework

- [MJML](https://github.com/mjmlio/mjml) - Framework to make responsive-email easy 
- [Maizzle](https://github.com/maizzle/framework) -  HTML email development framework 

### Templating

- [Cerberus](https://github.com/TedGoas/Cerberus) -  A few simple, but solid patterns for responsive HTML email templates and newsletters. Even in Outlook and Gmail.
- [HEML](https://heml.io/) -  HEML is an open source markup language for building responsive email. 
- [Hermes](https://github.com/matcornic/hermes) -  Golang package that generates clean, responsive HTML e-mails for sending transactional mail 

### Library

- [go-smtp](https://github.com/emersion/go-smtp) - An SMTP client & server library written in Go 
- [lettre](https://github.com/lettre/lettre) - a mailer library for Rust
- [mailparse](https://github.com/staktrace/mailparse) - Rust library to parse mail files
- [Nette Mail](https://github.com/nette/mail) - Handy email creation and transfer library for PHP with both text and MIME-compliant support.
- [Stampie](https://github.com/Stampie/Stampie) - Library for using online Email providers for PHP
- [Play-Mailer](https://github.com/playframework/play-mailer) - Play mailer plugin for Scala
- [Sisimai](https://libsisimai.org/) - Mail Analyzing Interface: A library to parse RFC5322 bounce emails and generating structured data as JSON from parsed results. For Perl, Go & Ruby
- [MailKit](https://github.com/jstedfast/MailKit) -  A cross-platform .NET library for IMAP, POP3, and SMTP.
- [MimeKit](https://github.com/jstedfast/MimeKit) -  A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools. 

## Editing

### Email Builder & Visual Editing Component

- [LePatron](https://github.com/Badsender-com/LePatron.email) -  LePatron is an opensource email builder allowing to industrialize your email template production. Build tailor made email templates and make them available to your non-technical users. 
- [Mosaico](https://github.com/voidlabs/mosaico) - Responsive Email Template Editor 
- [React Email Editor](https://github.com/unlayer/react-email-editor) -  Drag-n-Drop Email Editor Component for React.js 
- [Vue Email Editor](https://github.com/unlayer/vue-email-editor) -  Drag-n-Drop Email Editor Component for Vue.js 
- [GrapesJS](https://github.com/artf/grapesjs) - Free and Open source Web Builder Framework. Next generation tool for building templates without coding 
- [MySigMail Card](https://github.com/mysigmail/card) - An open source html email template builder with drag & drop editor 

## Email Solution
### Groupware / Webmail

- [Bluemind](https://www.bluemind.net/en/) - Collaborative messaging solution
- [Tutanota](https://github.com/tutao/tutanota) - Tutanota is an email service with a strong focus on security and privacy that lets you encrypt emails, contacts and calendar entries on all your devices. 
- [Mailcow](https://mailcow.email/) - The mailserver suite with the 'moo' – 🐮 + 🐋 = 💕 

## Security

### Security Check

- [Trustymail](https://github.com/cisagov/trustymail) -  Scan domains and return data based on trustworthy email best practices
- [mailsec-check](https://github.com/foxcpp/mailsec-check) -  Another utility to analyze state of deployment of security-related email protocols. 


### DMARC

- [dmarc-report-converter](https://github.com/tierpod/dmarc-report-converter) - Convert DMARC report files from xml to human-readable formats
- [Open DMARC Analyzer](https://github.com/userjack6880/Open-DMARC-Analyzer) -  Open DMARC Analyzer is an Open Source DMARC Report Analyzer to be used with DMARC reports that have been parsed by John Levine's rrdmarc script or techsneeze's dmarcts-report-parser. 
- [DmarcSrg](https://github.com/liuch/dmarc-srg) -  A php parser, viewer and summary report generator for incoming DMARC reports.


### Privacy

- [SimpleLogin](https://github.com/simple-login/app) - Protect your online identity with email alias
