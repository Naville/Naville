# About
I've been doing Darwin Reverse Engineering since 2013 until around 2020. Now I've quit RE for the most part, and instead focus on working with LLVM.
I spend spare time submitting all kinds of patches to LLVM upstream:
- [D137700](https://reviews.llvm.org/D137700)
- [D138641](https://reviews.llvm.org/D138641)
- [D141256](https://reviews.llvm.org/D141256)

# Identities
## Keybase
You can verify my social identities using [Keybase](https://keybase.io/navillezhang)
## GPG Keys
- ~~[EAB47648](https://keys.openpgp.org/vks/v1/by-fingerprint/2DD3AF5EF257577165BD3F09BCDB9630EAB47648)~~ Revoked. Private Key destroyed
- ~~[C03D3AB0](https://keys.openpgp.org/vks/v1/by-fingerprint/0893EC6A29D3D844E4E0C16D2380D692C03D3AB0)~~ Revoked. Private Key destroyed
- ~~[25EF1AC0](https://raw.githubusercontent.com/Naville/Naville/master/revoked/25EF1AC0CAF7C8CA01E4E1C4BD3CCE5D409CDF9A.asc)~~ Lost the physical token on 2023.07.23
- ~~[D056BE73](https://raw.githubusercontent.com/Naville/Naville/master/revoked/D056BE730C6DA3B9C2C2EA5E85FA1BF17C7EE4FB.asc)~~ Lost the physical token on 2023.07.23
- [B3D4AFE2](https://raw.githubusercontent.com/Naville/Naville/master/B3D4AFE298CA77AA776DF11AC9078243054CE41C.asc)
- [E128CB18](https://github.com/Naville/Naville/blob/master/E128CB1805D2352733356DD61A07D268D20E355C.asc)

### GPG Attestation
- Download YubiKey [Yubikey OPGP Attestation CA](https://developers.yubico.com/PGP/opgp-attestation-ca.pem)
- ``wget https://developers.yubico.com/PGP/opgp-attestation-ca.pem``
- ``openssl verify -no-CAfile -no-CApath -partial_chain -trusted opgp-attestation-ca.pem ${KEY_ID}-attestation/{auth,sign,dec}.pem``
- Verify the output for all ``.pem``s are ``.pem: OK``

# Resume
- ``Nov 2022 - `` Compiler Infrastructure @ miHoYo
    - Static Analysis
    - Link Time Optimization
    - Middle-End / Backend Transformation
    - Internal ToolChain Vendoring
- ``Nov 2021 - Oct 2022`` Secured Compiler Architecture / MobileVMP @ Tencent Mobile TenProtect
- ``June 2020 - Oct 2020`` PUBGM iOS AntiCheat @ Tencent Mobile TenProtect
- ``June 2019 - May 2020`` DevOps Engineer @ Alibaba