# Roadmap

## Genesis (Q3 2018)

**Fairlayer starts as entirely centralized network**, just like any PoW cryptocurrency. There are 4 validators having 25 shares each. 99 shares are guaranteed to be distributed within first 2 years to public identities 1-for-1 with verified social presence. After that the 100 validators must bring on 9900 more validators over next 5-10 years (onboarding 3 at a time) reaching our goal of 10k validators with **practically unhackable attack surface and 3333 entities Byzantine tolerance.**

Originally there will be only 1 verified hub @main in order to smooth the initial UX, support first users and collect necessary analytics. As soon as we have strong understanding how to make the hub and the rebalances more effective, everyone will be allowed to register their own hub and the topology of hubs will grow organically (perhaps even turning into mesh at times).

Our priority is to get **just two things right** at genesis:

- secure payment channels network - to let users see and use the killer feature from day1

- reliable smart updates - everything else can be added with governance afterwards

## Exchanges and Payment gateways (2018-2030)

There are two sides to a successful payment network, and that's where all our marketing efforts will go 50/50:

- **buying/selling the assets (trading).** adding to exchanges and making it seamless to buy and sell FRD/FRB and other Fair assets. The final goal is having in-wallet paypal-like deposit and withdrawal user experience with minimum hassle.

- **spending the assets (adoption)**. onboarding merchants and their customers on Fair. Paypal, credit cards and alike are our direct competitors here. The rationale to choose us over them is 30-50x times lower fees, instant settlement and technical superiority and soundness of the decentralized architecture. Most merchants are expected to accept stable assets such as FRD.

## Web and mobile wallets

Desktop platforms (Windows/macOS/Linux) and servers are #1 priority (and their security model is held to a higher standard), but it's clear how important mobile platforms are. Web & mobile wallets will be released **Q1-Q4 2019**, in different flavors with different security models.

## Asset creation

There are two native assets FRD & FRB created at genesis. Custom asset creation will be turned on in Q4 2018.

## Hub creation (Q2-Q4 2019)

By this time, we are supposed to have enough data based on usage of @main hub. Entering in partnership with existing payment processors to migrate their tech-savvy user base and run their hub inside the Fair layer. Tech-savvy users are incentivized to enjoy decentralized nature and having a signed proof at all times while payment gateways are incentivized to get a spot inside developing hub & spoke ecosystem and start earning offchain fees.

## Decentralization: 2/3+ of shares are distributed

After Foundation giving up 2/3+ of shares the platform reaches "singularity" and from that point can self-develop on its own (they can even delete Foundation itself using onchain governance). In absolute worst case all shares must be given up before **Q3 2020**, but depending on public interest it should happen much earlier.

## Alternative full-node software: 2020+

It's true that Javascript is not exactly fastest or safest language. But with two-layered architecture it is not a show-stopper: no matter how slow onchain is, offchain will always be scalable and instant, only Total Risk may get high. However once we figure out what's lacking the most in current software, we must write new full node implementation from scratch in a safe, efficient and static-typed language such as Rust.

## Fair Names / Fair Login (2020+)

Decentralized DNS, identity and login. Very important infrastructure projects, but unfortunatelly low user traction of ENS/namecoin tells us that it's something you can only offer to large existing user base and the network effect is the king here.

## Atomic Multipath Payments (2020+)

Pionered by bitcoin's LN, AMP is a neat way to use multiple routes to send single payment atomically. However we believe it's only helpful in super rare edge cases hence given low priority.

## Backup servers for encrypted dispute proofs (2019+)

Losing channel db is equivalent to losing cash. Integrating seamlessly by default it into the wallet is required to be usable by general public.

## Watchtowers (2019+)

To watch chain and finish a dispute on your behalf

## Superblocks (2020+)

Once in X blocks all validators must create an aggregated meta signature for last X blocks which would allow offline clients to sync a lot faster and verify X times less precommit signatures. I.e. for 1000 validators in 1000 blocks now a full node must perform 1 M sig verifications (a pretty expensive operation). With a jump only 1000 checks are needed.

## Sharding (per asset) (2020+)

Each full node subscribes to specific assets and only receives this asset related rebalances/disputes, e.g. you still have entire history and supply transparency of every RubleToken, but you don't care about RupiahToken and don't process RupiahToken-related tx.

# [9. API](/09_receive_and_pay.md) / [Home](/README.md)
