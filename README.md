# ENS

[![Build Status](https://travis-ci.org/ensdomains/ens-contracts.svg?branch=master)](https://travis-ci.org/ensdomains/ens-contracts)

For documentation of the ENS system, see [docs.ens.domains](https://docs.ens.domains/).

## Nexis Deployments 

```bash

deploying "LegacyENSRegistry" (tx: 0xd0b03a6135a0b5465577478470f8884619710d9fd6a352286a2e7273093ca05b)...: deployed at 0xaa602F6e55d30D8F793AB014F02cB74cEc56e450 with 642179 gas
Setting owner of root node to owner (tx: 0xc0a4dbfc993946493ff4133c9f83c55f51b5cf533a714fc0f715f9ac6d078e6d)
Unsetting owner of root node (tx: 0xc0a4dbfc993946493ff4133c9f83c55f51b5cf533a714fc0f715f9ac6d078e6d)
deploying "ENSRegistry" (tx: 0x2f889c5fb9c80302e30cba22854683fe17ec6f7398bdb81a1e73c39a90960321)...: deployed at 0xc0f6A57581FCA9aFb6B7BCbD79869439D66eCF54 with 782381 gas
deploying "Root" (tx: 0xc2f3cb9aee1d0816c3de02a6391d00b17f4685104fff1fbbd0bcd6cb89b72590)...: deployed at 0x85b3e89A9cFd644c72D857e5F2AF139465680013 with 504089 gas
deploying "BaseRegistrarImplementation" (tx: 0xc428418ccec9b4cbe8951215d3773946402d77d66b2c159a25df1e5b1a756514)...: deployed at 0x51EE12F768EeFAD3C539Dc81d9f3a2872cccA507 with 1916601 gas
deploying "RSASHA1Algorithm" (tx: 0x3f869c4361381a52c2f62f8aab71843a8ecce3593eeb3144fbe5fa7ed776499e)...: deployed at 0x60b3BF0031944498FC9E50B1A943E7E3c27f5260 with 695004 gas
deploying "RSASHA256Algorithm" (tx: 0xeffe04e84304100446db81903df7956cab552a9936c0b08e83bf3ce3a0a857bb)...: deployed at 0xaF56115E1F545fB3f501273e9C9999e227448520 with 448849 gas
deploying "P256SHA256Algorithm" (tx: 0x425ef7b59898aaf76f1153aa83a4e0089f1c5e08d01a8478d2d229d7a846489b)...: deployed at 0xe618746e3843bC6cbfD73764b779065D8F0b9917 with 895974 gas
deploying "SHA1Digest" (tx: 0x3a8265228500bce00d7ca0cdb89cdffef74067c992a835fd8ee83d0bf576132f)...: deployed at 0xc1ef23a4e90c3FB875Cb16085fdcC2ee76176881 with 459326 gas
deploying "SHA256Digest" (tx: 0xa3ea25fc557015b7e85d118568a61ba6549ef62634f17212353415f33257030f)...: deployed at 0x6e7C8B1a89C952dc71435fE8Db404c2dA44bDE94 with 211262 gas
deploying "DNSSECImpl" (tx: 0xacf2a02aa1b31c8c3737e7ecf324262af934678b318d34bf41c671871a798d67)...: deployed at 0x94B8FF031eb8C4ED03C011CE9F3f6a4AD21e6E7D with 1800920 gas
Waiting on 6 transactions setting DNSSEC parameters
deploying "OffchainDNSResolver" (tx: 0x6de72f52e531d1b1e0e7b75ce8316b67243a40b225a4a1972f76199cb648c5ed)...: deployed at 0xB7Ac594EC8450cAF1dCF40FCF2e7f0102Fe380Fc with 1857471 gas
Deployed OffchainDNSResolver to 0xB7Ac594EC8450cAF1dCF40FCF2e7f0102Fe380Fc
deploying "SimplePublicSuffixList" (tx: 0x43a779f2d266e2a5b358fa5cc589195c90b18460a6f7b6a12be7c77e1b552425)...: deployed at 0x14921A1A18C0c86A8CCEcA664Fd27Ee6e88F5437 with 381871 gas
Starting suffix transactions
Setting suffixes (tx: 0xd3ea3861c39f9c82529de1abb670e69a99eb8db6e566bdd96c7fafe1676e5498)...
Setting suffixes (tx: 0x2df6fb352ae059f859172007dceeaad731e4661d9beb2648eb089522a8f420d6)...
Setting suffixes (tx: 0x5f4c3fa7db30a74ed95e6ea86cf1a3fb56e2073c150409bf9819218dcb06be6c)...
Setting suffixes (tx: 0x2c380e5af1f898f627aebd4e1475aa4609744843627bbeff59acb1f756b2f525)...
Setting suffixes (tx: 0x69ff57e6e7d9c58f870cd9895a76a7acfded40abc28839c741635eb069851fd8)...
Setting suffixes (tx: 0x9a6b997949517271b5010282097d26882003fb65a995667d924c9037c318f93c)...
Setting suffixes (tx: 0x47ae45b605c0530d66131accb2d0275e70ddf18aef6a52934950ea20196bdd48)...
Setting suffixes (tx: 0x97dd67c066c1ea852412c2d3c45e0513186fec66e92c7b4dddcbdc180b781110)...
Setting suffixes (tx: 0x2d20277ea59590d06fd144640f3475a7627dce52187f87ab81061d2c0876f263)...
Setting suffixes (tx: 0x0b576710b53831fa195c3d850a4d9f23f9309bfd5750a69ff9606811fff1ec18)...
Setting suffixes (tx: 0xd8bf9003937fec5a5e419b18758fdf0f027403829051bb3e59d3629c71de6012)...
Setting suffixes (tx: 0x1f5c790a3c418d3e05e6edc3c4a343ce94c4253923712429e196a7bf5698f187)...
Setting suffixes (tx: 0xc9f4af785ffe58c576c1ebed0b54af72829d5dd37430652fb55f33f0a65e60da)...
Waiting on 13 suffix-setting transactions to complete...
Running root setup
Setting owner of root node to root contract (tx: 0x9674271f0f699caf53340560607350622163f3bf66e93b4bbfedfc74cf73e85c)...
Transferring root ownership to final owner (tx: 0x82e8a5bf86266c453c580ab6610463476238596db6605ee18fb07160aa12f37c)...
Setting final owner as controller on root contract (tx: 0xa09ccce47246cab2ccfb08bc0ce424eca62c67370d6a6792c47473898bd840c6)...
deploying "DNSRegistrar" (tx: 0xa62b72586a575b03cd0a7bdcca46bb0f26780be69478125f05c42e98cab4eb10)...: deployed at 0xb90A70d10Be6ca636A2677A59ee5BfBB7FF5e366 with 1955826 gas
Deployed DNSRegistrar to 0xb90A70d10Be6ca636A2677A59ee5BfBB7FF5e366
Set DNSRegistrar as controller of Root (0x2f79c21dbf8d9d2c05c53261c9f464fd72b2b4f6e7a782ecdb0f4519475d62d1)
Running base registrar setup
Transferring ownership of registrar to owner (tx: 0x0fe4ce00228bb2d99864eff24237643425c740774ea6e01c2f84d75056de41f6)...
Setting owner of eth node to registrar on root (tx: 0xe297117f0b130bb8caef607cd93a59c375d2638d339f65636b2fd116d6ece148)...
deploying "DummyOracle" (tx: 0x4b907062751fccf7c7126c9895e3b9803195c0648ae5fc901c0b678b159c3e45)...: deployed at 0xFa17AF7F68Ec6C0d6D5D7F1696c0Cda1b302F324 with 111909 gas
deploying "ExponentialPremiumPriceOracle" (tx: 0xebce0296dd3811726a0ed8026f611371cd3277f62ae874e19483bdf017d77424)...: deployed at 0xd9b02073Cfd83Ffd02C4776cB86C68d74759c7c4 with 814592 gas
deploying "StaticMetadataService" (tx: 0x9ff7a62b2680d63b8a471e6937fc53f7d01690ed55cb93ff69da9673f4a8d21d)...: deployed at 0x7c4729633fDA10512Bca839Def9f919600c46163 with 228248 gas
deploying "ReverseRegistrar" (tx: 0x3e80140c636a158fac1a144a8a1586c3438ca84508dd9e936b5377b3f653559e)...: deployed at 0x76cAbA89CdFB44943d9ad11b47b8f7d1f8698e1D with 816656 gas
Setting owner of .reverse to owner on root (tx: 0xff77f0695faefb0557b00748d8f1d9fcfba113145afc3ac5ef1c115376db18e7)...
Setting owner of .addr.reverse to ReverseRegistrar on registry (tx: 0x071ecbc920d8821d8e71d1393c328742ea0c3d42e8ba4d8c6ebdb0873aef3b9a)...
deploying "OwnedResolver" (tx: 0xc41777e3f95ed3fc7be9a6d8dacce92cbf5d9b65e115330504aef79663def7ea)...: deployed at 0xfD684Af963B346da6f3Ecf352507C3CEB4F2e355 with 2347796 gas
set resolver for .eth to 0xfD684Af963B346da6f3Ecf352507C3CEB4F2e355
deploying "NameWrapper" (tx: 0xe7534020a9a7b6591f08269a2327c8afd27659d7b54cca682e8b765fc21fb6e5)...: deployed at 0x429A9dea4843BF1a439805cE53a10e5F093133ac with 5470684 gas
Adding NameWrapper as controller on registrar (tx: 0xf6591e51c1b675164aa7d8d2f894aad5a746e2f14dee75ba33c8889a7077f7ed)...
Setting NameWrapper interface ID 0x019a38fe on .eth resolver (tx: 0x9f12c899aebf13d9387592308d977cdf4eaf33964eb0cce6b570902e2fc361b2)...
deploying "TestUnwrap" (tx: 0x8fa717f97be3fed2abc1f0c8da175f82e6a4aa4abceb8518da5275439a0b516d)...: deployed at 0x56a617fF3C0e3778922103CA6244191f012cF03a with 969085 gas
No testnet wrappers found, skipping
deploying "LegacyPublicResolver" (tx: 0x55f8a315eb2cb16d72d1584589787e317c3ba16aa95df5366d2a63c15b6dfda4)...: deployed at 0xa8F8433Ce5801E5b6b29429648f0748DB7ff3E95 with 2380886 gas
deploying "LegacyETHRegistrarController" (tx: 0xba8fc9bfcdebb51ee2b4c0be0420aee72d249a7bad9dcd8f6d23a5600d752d9d)...: deployed at 0x7F90E4940b956590faccb10bbba9C45462D16659 with 1845959 gas
Adding controller as controller on registrar (tx: 0x3fe9239ed2400999921c2233d0039a62e3da53345d70670a39eaa91fa9e6561f)...
Setting controller of ReverseRegistrar to controller (tx: 0x2fc4fc65ede0cb1b8e859ccfc6cc4b11829beff06a05a13a977ba21bbefc7c25)...
deploying "ETHRegistrarController" (tx: 0x9000f4b72946677f3c6f7631d9244143ae2b15cc413ca636625656738dc33631)...: deployed at 0x3309F6Daed55C932dD9c1f449E2F431533991026 with 1764337 gas
WRAPPER OWNER 0x77542Fe67d92eD60F94e2396A7A077D0461a7Dd5 0x77542Fe67d92eD60F94e2396A7A077D0461a7Dd5
Adding ETHRegistrarController as a controller of NameWrapper (tx: 0x9a3cdb2a0856ab211e9058d94f3a6137dc29b841b75eb116133254c2b1b6d894)...
Adding ETHRegistrarController as a controller of ReverseRegistrar (tx: 0x6f8020ef1a00daf9adbeeb8a9b2fd6539f8568d657d0d8b882d9e268329e7a8e)...
Setting ETHRegistrarController interface ID 0x612e8c09 on .eth resolver (tx: 0xee03c1076fa36c2c7c6b97dc76adcf012c6525133f270a71e028b5c361793dca)...
deploying "StaticBulkRenewal" (tx: 0x47b0830cc403c69944d7a1a0a1676ab9a97323cc7f18733896dd043b741413d5)...: deployed at 0x86Dc43b6c57193a8e9d0C597bEa709E3B47852a6 with 395466 gas
Setting BulkRenewal interface ID 0xd1a70fd3 on .eth resolver (tx: 0xb58dd2e95fe3c306290b6f7298f7dcb7f838d14674088d1f64e4ae36f8e900a6)...
deploying "ExtendedDNSResolver" (tx: 0xcbd5a3aaccaaac71c5b6f63bf1ab6dbca4514a5061ddcecc0ef9c979c331e2a7)...: deployed at 0x6B581e42f63e382E7a966DEa554d7e68A7F94330 with 422616 gas
deploying "PublicResolver" (tx: 0x0b52e26bc0f901950515be32132d83c40c8ca298936064de0b7c97a8895e958c)...: deployed at 0x947cB7849C75d0f0480C664f904cabbA64150933 with 2757693 gas
Setting default resolver on ReverseRegistrar to PublicResolver (tx: 0x250359f12184a4cc3ad745f92112c762208d83b4a4cf43a6ead1738ba49003f2)...
resolver.eth is not owned by the owner address, not setting resolver
UniversalResolver: No batch gateway URLs provided
deploying "UniversalResolver" (tx: 0xf28cd1423bc4c9b279fd543a844e25f17403dfdb9dc845df808c159024c21585)...: deployed at 0x116314A4Ea94d7cf8B6E4aDc253d1dBC602c2e03 with 3092803 gas
Running setTLDs
Transferring .xyz to new DNS registrar
Waiting on 1 transactions setting DNS TLDs
```

## npm package

This repo doubles as an npm package with the compiled JSON contracts

```js
import {
  BaseRegistrar,
  BaseRegistrarImplementation,
  BulkRenewal,
  ENS,
  ENSRegistry,
  ENSRegistryWithFallback,
  ETHRegistrarController,
  FIFSRegistrar,
  LinearPremiumPriceOracle,
  PriceOracle,
  PublicResolver,
  Resolver,
  ReverseRegistrar,
  StablePriceOracle,
  TestRegistrar,
} from '@ensdomains/ens-contracts'
```

## Importing from solidity

```
// Registry
import '@ensdomains/ens-contracts/contracts/registry/ENS.sol';
import '@ensdomains/ens-contracts/contracts/registry/ENSRegistry.sol';
import '@ensdomains/ens-contracts/contracts/registry/ENSRegistryWithFallback.sol';
import '@ensdomains/ens-contracts/contracts/registry/ReverseRegistrar.sol';
import '@ensdomains/ens-contracts/contracts/registry/TestRegistrar.sol';
// EthRegistrar
import '@ensdomains/ens-contracts/contracts/ethregistrar/BaseRegistrar.sol';
import '@ensdomains/ens-contracts/contracts/ethregistrar/BaseRegistrarImplementation.sol';
import '@ensdomains/ens-contracts/contracts/ethregistrar/BulkRenewal.sol';
import '@ensdomains/ens-contracts/contracts/ethregistrar/ETHRegistrarController.sol';
import '@ensdomains/ens-contracts/contracts/ethregistrar/LinearPremiumPriceOracle.sol';
import '@ensdomains/ens-contracts/contracts/ethregistrar/PriceOracle.sol';
import '@ensdomains/ens-contracts/contracts/ethregistrar/StablePriceOracle.sol';
// Resolvers
import '@ensdomains/ens-contracts/contracts/resolvers/PublicResolver.sol';
import '@ensdomains/ens-contracts/contracts/resolvers/Resolver.sol';
```

## Accessing to binary file.

If your environment does not have compiler, you can access to the raw hardhat artifacts files at `node_modules/@ensdomains/ens-contracts/artifacts/contracts/${modName}/${contractName}.sol/${contractName}.json`

## Contracts

## Registry

The ENS registry is the core contract that lies at the heart of ENS resolution. All ENS lookups start by querying the registry. The registry maintains a list of domains, recording the owner, resolver, and TTL for each, and allows the owner of a domain to make changes to that data. It also includes some generic registrars.

### ENS.sol

Interface of the ENS Registry.

### ENSRegistry

Implementation of the ENS Registry, the central contract used to look up resolvers and owners for domains.

### ENSRegistryWithFallback

The new implementation of the ENS Registry after [the 2020 ENS Registry Migration](https://docs.ens.domains/ens-migration-february-2020/technical-description#new-ens-deployment).

### FIFSRegistrar

Implementation of a simple first-in-first-served registrar, which issues (sub-)domains to the first account to request them.

### ReverseRegistrar

Implementation of the reverse registrar responsible for managing reverse resolution via the .addr.reverse special-purpose TLD.

### TestRegistrar

Implementation of the `.test` registrar facilitates easy testing of ENS on the Ethereum test networks. Currently deployed on Ropsten network, it provides functionality to instantly claim a domain for test purposes, which expires 28 days after it was claimed.

## EthRegistrar

Implements an [ENS](https://ens.domains/) registrar intended for the .eth TLD.

These contracts were audited by ConsenSys Diligence; the audit report is available [here](https://github.com/ConsenSys/ens-audit-report-2019-02).

### BaseRegistrar

BaseRegistrar is the contract that owns the TLD in the ENS registry. This contract implements a minimal set of functionality:

- The owner of the registrar may add and remove controllers.
- Controllers may register new domains and extend the expiry of (renew) existing domains. They can not change the ownership or reduce the expiration time of existing domains.
- Name owners may transfer ownership to another address.
- Name owners may reclaim ownership in the ENS registry if they have lost it.
- Owners of names in the interim registrar may transfer them to the new registrar, during the 1 year transition period. When they do so, their deposit is returned to them in its entirety.

This separation of concerns provides name owners strong guarantees over continued ownership of their existing names, while still permitting innovation and change in the way names are registered and renewed via the controller mechanism.

### EthRegistrarController

EthRegistrarController is the first implementation of a registration controller for the new registrar. This contract implements the following functionality:

- The owner of the registrar may set a price oracle contract, which determines the cost of registrations and renewals based on the name and the desired registration or renewal duration.
- The owner of the registrar may withdraw any collected funds to their account.
- Users can register new names using a commit/reveal process and by paying the appropriate registration fee.
- Users can renew a name by paying the appropriate fee. Any user may renew a domain, not just the name's owner.

The commit/reveal process is used to avoid frontrunning, and operates as follows:

1.  A user commits to a hash, the preimage of which contains the name to be registered and a secret value.
2.  After a minimum delay period and before the commitment expires, the user calls the register function with the name to register and the secret value from the commitment. If a valid commitment is found and the other preconditions are met, the name is registered.

The minimum delay and expiry for commitments exist to prevent miners or other users from effectively frontrunning registrations.

### SimplePriceOracle

SimplePriceOracle is a trivial implementation of the pricing oracle for the EthRegistrarController that always returns a fixed price per domain per year, determined by the contract owner.

### StablePriceOracle

StablePriceOracle is a price oracle implementation that allows the contract owner to specify pricing based on the length of a name, and uses a fiat currency oracle to set a fixed price in fiat per name.

## Resolvers

Resolver implements a general-purpose ENS resolver that is suitable for most standard ENS use cases. The public resolver permits updates to ENS records by the owner of the corresponding name.

PublicResolver includes the following profiles that implements different EIPs.

- ABIResolver = EIP 205 - ABI support (`ABI()`).
- AddrResolver = EIP 137 - Contract address interface. EIP 2304 - Multicoin support (`addr()`).
- ContentHashResolver = EIP 1577 - Content hash support (`contenthash()`).
- InterfaceResolver = EIP 165 - Interface Detection (`supportsInterface()`).
- NameResolver = EIP 181 - Reverse resolution (`name()`).
- PubkeyResolver = EIP 619 - SECP256k1 public keys (`pubkey()`).
- TextResolver = EIP 634 - Text records (`text()`).
- DNSResolver = Experimental support is available for hosting DNS domains on the Ethereum blockchain via ENS. [The more detail](https://veox-ens.readthedocs.io/en/latest/dns.html) is on the old ENS doc.

## Developer guide

### Prettier pre-commit hook

This repo runs a husky precommit to prettify all contract files to keep them consistent. Add new folder/files to `prettier format` script in package.json. If you need to add other tasks to the pre-commit script, add them to `.husky/pre-commit`

### How to setup

```
git clone https://github.com/ensdomains/ens-contracts
cd ens-contracts
yarn
```

### How to run tests

```
yarn test
```

### How to publish

```
yarn pub
```

### Release flow

1. Create a `feature` branch from `staging` branch
2. Make code updates
3. Ensure you are synced up with `staging`
4. Code should now be in a state where you think it can be deployed to production
5. Create a "Release Candidate" [release](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases) on GitHub. This will be of the form `v1.2.3-RC0`. This tagged commit is now subject to our bug bounty.
6. Have the tagged commit audited if necessary
7. If changes are required, make the changes and then once ready for review create another GitHub release with an incremented RC value `v1.2.3-RC0` -> `v.1.2.3-RC1`. Repeat as necessary.
8. Deploy to testnet. Open a pull request to merge the deploy artifacts into
   the `feature` branch. Create GitHub release of the form `v1.2.3-testnet` from the commit that has the new deployment artifacts.
9. Get someone to review and approve the deployment and then merge. You now MUST merge this branch into `staging` branch.
10. If any further changes are needed, you can either make them on the existing feature branch that is in sync or create a new branch, and follow steps 1 -> 9. Repeat as necessary.
11. Make a deployment to ethereum mainnet from `staging`. Create a GitHub release of the form `v1.2.3` from the commit that has the new deployment artifacts.
12. Open a PR to merge into `main`. Have it reviewed and merged.

### Cherry-picked release flow

Certain changes can be released in isolation via cherry-picking, although ideally we would always release from `staging`.

1. Create a new branch from `mainnet`.
2. Cherry-pick from `staging` into new branch.
3. Deploy to ethereum mainnet, tag the commit that has deployment artifacts and create a release.
4. Merge into `mainnet`.

### Emergency release process

1. Branch from `main`, make fixes, deploy to testnet (can skip), deploy to mainnet
2. Merge changes back into `main` and `staging` immediately after deploy
3. Create GitHub releases, if you didn't deploy to testnet in step 1, do it now

### Notes

- Deployed code should always match source code in mainnet releases. This may not be the case for `staging`.
- `staging` branch and `main` branch should start in sync
- `staging` is intended to be a practice `main`. Only code that is intended to be released to `main` can be merged to `staging`. Consequently:
  - Feature branches will be long-lived
  - Feature branches must be kept in sync with `staging`
  - Audits are conducted on feature branches
- All code that is on `staging` and `main` should be deployed to testnet and mainnet respectively i.e. these branches should not have any undeployed code
- It is preferable to not edit the same file on different feature branches.
- Code on `staging` and `main` will always be a subset of what is deployed, as smart contracts cannot be undeployed.
- Release candidates, `staging` and `main` branch are subject to our bug bounty
- Releases follow semantic versioning and releases should contain a description of changes with developers being the intended audience
