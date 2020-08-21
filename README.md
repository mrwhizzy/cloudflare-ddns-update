# cloudflare-ddns-update.sh
Cloudflare API v4 Dynamic DNS Update in Bash --> Working 20/08/2020

# Based on benkulbertis/cloudflare-update-record.sh
auth_email="your-email@example.com"                # The email used to login 'https://dash.cloudflare.com'
auth_key="0000000000000000000000000000000000000"   # Top right corner, "My profile" > "Global API Key"
zone_identifier="00000000000000000000000000000000" # Can be found in the "Overview" tab of your domain
sleep_seconds=300                                  # Run every 5 minutes
