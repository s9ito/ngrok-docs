<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-05-17T21:11:57Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2gbxwZsoACXVsGBExXOkO90zDGW",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2gbxwZsoACXVsGBExXOkO90zDGW"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2gbxvD6Kgw1N3WQ1gIfcGN1G0jX",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2gbxvD6Kgw1N3WQ1gIfcGN1G0jX"
				},
				"enabled": true
			},
			"created_at": "2024-05-17T21:11:46Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2gbxvFwKqkdrckOWqiIuoxy2bgF",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2gbxvFwKqkdrckOWqiIuoxy2bgF"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
