<img src="https://github.com/kelvinzer0/DNS369-Storage/blob/main/media-kit/logo-DNS469.png?raw=true" width="450px"/>
# DNS369 Free Domain Setup Guide

To create a free domain on the DNS369 server, follow the steps below:

## Step 1: Add DNS Configuration to dns.jsonl File

1. Fork the DNS369 repository to your GitHub account.
2. Open the `dns.jsonl` file in the repository.
3. Add your DNS configuration for the desired domain in the following format:

```json
{"domain": "yourdomain.com", "type": "A", "address": "192.168.1.1"}
```

Replace `"yourdomain.com"` with your actual domain name, `"A"` with the desired DNS record type, and `"192.168.1.1"` with the IP address associated with your domain.

4. Save the changes to the `dns.jsonl` file.

## Step 2: Submit a Pull Request

1. Commit your changes to the forked repository.
2. Open a pull request to the original DNS369 repository.
3. Provide a descriptive title and details of the DNS configuration you added.
4. Submit the pull request for review.

## Important Note

Ensure that the domain you add to the `dns.jsonl` file is not already used in the public DNS network to avoid conflicts and issues.

## DNS Lookup

After your domain has been created or added, you can perform a DNS lookup by following the steps below:

1. Visit the DNS369 Lookup page at [https://kelvinzer0.github.io/dns369-lookup.html](https://kelvinzer0.github.io/dns369-lookup.html).
2. Enter your domain name in the input field.
3. Click the "Lookup" button to initiate the DNS lookup process.
4. The lookup results will be displayed, showing the DNS records associated with your domain.

Please note that DNS propagation may take some time before the changes are fully effective.

For any further assistance or inquiries, please refer to the DNS369 documentation or contact the maintainers of the DNS369 repository.
