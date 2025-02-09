# Firewall Rules for Secure AWS Cloud Network

## Inbound Rules
- Allow HTTPS (443) traffic from **trusted sources**.
- Allow SSH (22) access only from **whitelisted IPs**.
- Block all other inbound traffic by default.

## Outbound Rules
- Allow only necessary outbound traffic for **API requests and DB connections**.
- Restrict outbound traffic to **untrusted external IPs**.

## Best Practices
- Use **Security Groups and NACLs** for fine-grained control.
- Monitor firewall activity using **VPC Flow Logs**.
- Regularly review and update firewall rules.
