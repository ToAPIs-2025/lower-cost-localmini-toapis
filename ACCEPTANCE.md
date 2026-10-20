# Validation boundary

- Start the authenticated loopback bridge described below on the same host as the self-hosted backend. Do not expose it publicly or disable outbound safety rules.
- In AI Configuration choose the OpenAI image protocol and copy integration/localmini-image-config.json fields manually. The UI key is the separate BRIDGE_TOKEN; the real ToAPIs key stays in the bridge.
- Leave image quality unset for this fixed-preset recipe. The selected API model determines low/standard/high behavior; unsupported fields and reference editing are rejected.
- The pinned upstream imageClient.callImageApi was exercised with fixture configuration persistence over real loopback HTTP and this batch's saved real PNGs; no new paid call or complete app run was made by that replay check.
- Native videoClient size/seconds/first-frame mapping remains pending. The supplied Seedance video is an independently validated API asset.

No full upstream UI acceptance, native video/reference editing acceptance or audio acceptance is claimed. Check cases.json for API output and billing evidence.
