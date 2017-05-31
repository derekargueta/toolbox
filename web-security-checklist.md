Watered-down version of [this checklist](https://simplesecurity.sensedeep.com/web-developer-security-checklist-f2e4f43c9c56)

Designed more for smaller projects, not enterprise-grade services.

### Database
- [ ] Encrypt any sensitive fields
- [ ] Encrypt backups
- [ ] minimal priviledge for database user account - good password, non-root
- [ ] use prepared SQL statements

### Development
- [ ] use isolated development systems

### Authentication
- [ ] hash passwords using an algorithm of good strength such as bcrypt
- [ ] follow best-practices and use proven libraries for login, password recovery, etc.
- [ ] use simple but adequate password rules
- [ ] enable multi-factor authentication anywhere applicable

### DoS Attacks
- [ ] rate-limit APIs
- [ ] enforce limits on size and structure of user-submitted data
- [ ] use a DDoS mitigation service such as Cloudflare

### Web Traffic
- [ ] use TLS _everywhere_
- [ ] cookies should be httpOnly, secure, and scoped by path and domain
- [ ] use a content security policy (CSP) without allowing unsafe-* backdoors
- [ ] use X-Frame-Option and X-XSS-Protection headers
- [ ] use HSTS to force TLS only. Redirect HTTP traffic to HTTPS
- [ ] use CSRF tokens in forms and the new SameSite cookie

### APIs
- [ ] no enumerable resources on APIs
- [ ] ensure users are authenticated before consuming APIs

### Validation and Encoding
- [ ] use client-side validation as a sanity-check, but don't trust it.
- [ ] validate _everything_ server-side

### Cloud Configuration
- [ ] Ensure all servers have minimal ports open. Consider non-standard ports to make attacks a little harder
- [ ] Host backends and databases in a VPC
- [ ] Ensure internal services accept content from as few whitelisted IPs as possible
- [ ] restrict outgoing IP and port traffic to minimize botification
- [ ] use minimal access priviledge for all ops and development
- [ ] regularly rotate passwords and access keys

### Infrastructure
- [ ] try to automate using a tool like Terraform
- [ ] centralized logging for all services. Shouldn't have to SSH to access logs
- [ ] more SSHing is indicative of lack of automation. fix it.


[post on HTTP security headers](https://blog.appcanary.com/2017/http-security-headers.html)
