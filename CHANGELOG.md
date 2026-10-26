## 0.1.6

- Republish the English-only README release with npm provenance so n8n Creators Portal verification can accept Resubmit (0.1.4 was published without provenance).
- Update `package.json` `repository.url` to `modelflare-ai/n8n-nodes-modelflare` so npm provenance validation matches the renamed GitHub repo (0.1.5 tag publish failed on that mismatch).

## 0.1.5

- Attempted provenance republish of the English-only README; npm rejected the publish because `repository.url` still pointed at the old `castaly-ai` org. Superseded by 0.1.6.

## 0.1.4

- Make the README English-only to meet n8n community node verification guidelines.

## 0.1.3

- Fix Creator Portal verification by shipping themed source icons, using n8n-native execution errors, and removing an unused restricted global from the built package.
- Replace open JSON request fields with typed Additional Options for text, image, and video operations.
- Continue reading the legacy JSON fields from saved 0.1.2 workflows so upgrades preserve existing model-specific parameters.

## 0.1.2

- Add authorized model filtering, optional vision input, and safer image and video routing.
