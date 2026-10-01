# Read-only owner adaptation

Package: `@hathq/ihat-store-source`, immutable development version **0.10.0**.

`observeCatalog(rpc, {locale})` reads Hatter's selected catalog-source registry, the verified catalog projection, then the registry again. A changed source or registry revision rejects the observation. It does not provision, install or create a parallel trust decision.

The observation retains source ID, source registry revision, signed catalog digest, logical origin and signing-key identity. Availability and assurance are owner-derived. Publisher identity is not supplied by the current catalog contract; consumers must show unknown, not infer a publisher from a URL.

No semantic, control, installation, credential or renderer authority is transferred
to iHat. Acceptance and remaining work are recorded in
`docs/architecture/ihat-online-architecture.json` at the Wonderland root.
