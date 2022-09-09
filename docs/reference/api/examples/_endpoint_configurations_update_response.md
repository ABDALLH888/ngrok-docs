
###### Example Response
```
{
  "id": "ec_2E8b1jMtxgc2cKSLpDSz95Sa6Aq",
  "type": "https",
  "description": "app servers",
  "metadata": "",
  "created_at": "2022-08-31T21:05:45Z",
  "uri": "https://api.ngrok.com/endpoint_configurations/ec_2E8b1jMtxgc2cKSLpDSz95Sa6Aq",
  "basic_auth": null,
  "circuit_breaker": null,
  "compression": null,
  "request_headers": {
    "enabled": true,
    "add": {
      "x-frontend": "ngrok"
    },
    "remove": [
      "cache-control"
    ]
  },
  "response_headers": null,
  "ip_policy": {
    "enabled": true,
    "ip_policies": [
      {
        "id": "ipp_2E8b1ol6Fy7l3BkewGneuLMQ5dP",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2E8b1ol6Fy7l3BkewGneuLMQ5dP"
      }
    ]
  },
  "mutual_tls": null,
  "tls_termination": null,
  "webhook_validation": null,
  "oauth": null,
  "saml": null,
  "oidc": null,
  "backend": null
}