# smtp-server fork
Since the original [smtp-server](https://github.com/nodemailer/smtp-server) no longer appears to actively engage in issues or addition of any new features, I have created a fork with the focus being on adding new features and fixing existing/upcoming issues.

Should any updates or changes be made to the original smtp-server repository, those will be merged too if applicable.

For existing issues on the original repository, for the chance that may have been fixed and to avoid being overwhelmed, I will only focus on issues opened in the forked repository (feel free to re-open existing issues under this repository!).

## Documentation
At the moment this will be a bit of an iffy area since this is a new project, but as time will go on and enough significant changes/features are added I will create a copy of the smtp-server documentation to keep track of everything new as well.

For now, the original [smtp-server documentation](https://nodemailer.com/extras/smtp-server/) will be enough. 

## Roadmap
The plan is to add new features, so far the things on my radar are:
- Custom SMTP server greeting messages - being able to change the existing "Nice to meet you" greeting.
- Support for the [ENHANCEDSTATUSCODES](https://www.iana.org/assignments/smtp-enhanced-status-codes/smtp-enhanced-status-codes.xhtml) extension to keep up with modern SMTP servers.

## SMTP Specification
This project will follow the [RFC 5321](https://datatracker.ietf.org/doc/html/rfc5321) specification for SMTP.

## Original README



![Nodemailer](https://raw.githubusercontent.com/nodemailer/nodemailer/master/assets/nm_logo_200x136.png)

Node.JS module for creating SMTP and LMTP server instances on the fly.

See [smtp-server homepage](https://nodemailer.com/extras/smtp-server/) for documentation and terms.
