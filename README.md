# MuesliSwap Entity Verification 🏢✔

The official repository to register as an entity for [Onchain Token Verification](https://onchain-token-verification.muesliswap.com/).  
As a registered entity, you will automatically appear as trusted in the [Entity section](https://onchain-token-verification.muesliswap.com/entities), and users will see which tokens you marked as trusted or untrusted.

## 👤 Who are the Intended Users of this Repository?
This is tailored primarily for organizations within the Cardano ecosystem or individuals aiming to manage tokens. Our goal is to prevent scammers who attempt to impersonate these organizations.

## ❗ The Importance of Entity Verification!
[Onchain Token Verification](https://onchain-token-verification.muesliswap.com/) is a decentralized platform open to everyone, even without authentication. However, to safeguard against scammers who might try to impersonate reputable entities, we ensure that registered entities are genuine and as they present themselves to be. Entities that pass our verification process are marked as trusted. However, users still retain the flexibility to alter the trust status, either revoking trust from verified entities or placing trust in unverified ones.

## 📜 How to register?
We uniquely identify entities via their Public Key Hash (PKH).  
To register, please do the following:  
1. 📄 Create a pull request with the correct JSON entity description in the [entities](entities) folder similar to [our example](https://github.com/MuesliSwapTeam/muesliswap-entity-verification/blob/main/entities/9a8bb44a58ed4b9bd25e3b896d5dbadcc0128ef3ebedde2a8a3de17b.json).   
The file name should be named \<PKH\>.json.  
2. 🧐 Make sure that your PKH is displayed somewhere on your website.  
3. 💸 Leave a comment with the transaction id showing you submitted 50 ADA to the [payment address](https://cardanoscan.io/address/addr1qx3hdgge0w8asfryr2duqeajy9qnz957u660f07lghzacn4e2cutfnhq0kzd5azy95vngvn2nl0x04kxvtfrhych3lcqvwsu7a)  

## 💸 Why a 50 ADA Fee?
The 50 ADA fee primarily serves as a deterrent against spam registrations. If this fee poses any financial strain, please feel free to contact us.
