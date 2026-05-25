# credential-badges-verifier-spike

Throwaway GitHub Pages host for the Phase 0 pre-flight verifier spike
(`andamio-platform/credential-badges`, plan P1bis-10).

This repo exists solely so independent verifiers (walt-id, spruceid/ssi,
1EdTech digital-credentials-public-validator) can resolve:

- `did:web:workshop-maybe.github.io:credential-badges-verifier-spike` →
  `https://workshop-maybe.github.io/credential-badges-verifier-spike/did.json`
- `BitstringStatusListEntry.statusListCredential` →
  `https://workshop-maybe.github.io/credential-badges-verifier-spike/status/key-epoch-2026-05.json`
- Custom `@context` →
  `https://workshop-maybe.github.io/credential-badges-verifier-spike/context/v0.jsonld`

Delete this repo when the spike closes. Production `did:web` will be
`did:web:credentials.andamio.io`, served from the `credential-badges`
static host (Unit 1, Decision 4).
