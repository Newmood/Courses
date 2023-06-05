#### DNS
- MX records direct email to the servers that are hosting user accounts
- TXT records provides text information to sources outside your domain (includes SPF, DKIM, DMARC)
- CNAME record links an alias name to another true name, or canonical domain name.
- Address record links a domain to the physical ip address hosting that domain's services
- NS records determine which servers will commmunicate DNS information for a domain

1. Which type of DNS record determines where mail destined for your domain is routed? MX Record
2. What are common uses for a DNS TXT record when using Google Workspace? (Choose 2) Domain verification; Email security records
3. In general, from where would you manage your domain's DNS records? In your domain registrar console
4. You need to make a change to your MX records and you want the change to be implemented as soon as possible. What approach can you take? Make the change in your DNS console and reduce the Time to Live (TTL) value to 1 hour. Once the change has been implemented revert the TTL value to 24 hours


#### Email security
- Authorise SPF
- Authenticate DKIM
- Manage spam with DMARC

1. What is the main purpose of a Sender Policy Framework (SPF) record? It specifies which servers/domains can send messages on your behalf
2. You have been asked to implement DomainKeys Identified Mail (DKIM) for your organization. How would you do this?  Generate a DKIM record from Apps > Google Workspace > Gmail > Authenticate email. Add the record to your DNS records and then start authentication from the admin console
3. What policy defines what to do if an incoming message is not authenticated? DMARC
4. DKIM adds an encrypted signature to the header of all outgoing messages. What happens if you don't turn on email signing with your own domain DKIM key? Gmail signs all outgoing messages with this default DKIM domain key d=*.gappssmtp.com

#### Email safety, end user access
- Configure email safety
- End user access

1. The attachment section in the Gmail Safety settings page allows you to protect against malicious attachments. What actions can you perform on a suspicious attachment? (Choose 2) Keep email in inbox and show warning; Move email to spam
2. What are valid reasons for allowing per-user outbound gateways in your organization? (Choose 2) An outbound gateway can prevent the appearance of "on behalf of" addresses in the From field; An outbound gateway ensures that the same mail server delivers all messages from otherdomain and that server has a record that the mail has been sent
3. Google recommends against the use of the Image URL proxy whitelist? True
4. You have enabled protection against anomalous attachment types in emails from the Gmail > Safety page but you are finding some emails with valid attachment types are not being delivered. How can you resolve this? Add an allowlist of allowable file types to the entry in the Attachments section on the Safety page


#### Prevention of spam, phishing and malware






