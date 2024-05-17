<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-05-17T21:11:31Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.kyselxbwjwrxjpsc.local-ngrok-cname.com",
			"created_at": "2024-05-17T21:11:30Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2gbxtO40zp6I5JykZ9uRb9OMPfX",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2gbxtO40zp6I5JykZ9uRb9OMPfX"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2gbxtBHbJVjEZn7TdUc39fCG5ob",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2gbxtBHbJVjEZn7TdUc39fCG5ob"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.kyselxbwjwrxjpsc.local-ngrok-cname.com",
			"created_at": "2024-05-17T21:11:30Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2gbxtEPxxQMAo4cI1ccVloOqCLS",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2gbxtEPxxQMAo4cI1ccVloOqCLS"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
