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
          "started_at": "2025-09-12T10:11:05Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2wkkhbhndk2vlawz6.local-ngrok-cname.com",
      "created_at": "2025-09-12T10:11:05Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32awCooFCn2gVGb4i5JfNEvW9gr",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32awCooFCn2gVGb4i5JfNEvW9gr"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_32awCovoxQAVVFAMKLl92hpmUeN",
        "uri": "https://api.ngrok.com/tls_certificates/cert_32awCovoxQAVVFAMKLl92hpmUeN"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2wkkhbhndk2vlawz6.local-ngrok-cname.com",
      "created_at": "2025-09-12T10:11:05Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32awCmUmGLc7pyO7R0NX42LHbNF",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32awCmUmGLc7pyO7R0NX42LHbNF"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-12T10:10:35Z",
      "description": "Your dev domain",
      "domain": "optimally-spirantal-jonelle.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32aw8yMmZITlcRgqcMuQqAgOdAH",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32aw8yMmZITlcRgqcMuQqAgOdAH"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
