---
eip: <to be assigned>
title: Reduce ETH block reward by 1/3rd at every hard fork until PoS arrives. 
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
discussions-to: <URL>
status: Draft
type: <Standards Track (Core, Networking, Interface, ERC)  | Informational | Meta>
category (*only required for Standard Track): <Core | Networking | Interface | ERC>
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
requires (*optional): <EIP number(s)>
replaces (*optional): <EIP number(s)>
---

Simple Summary

Reduce ETH block reward by 1/3rd at every planned hard fork until PoS. 

Abstract

We've agreed to a block reward issuance reduction of 33% (3 ETH to 2 ETH) at the constantinople hard fork. I'm simply proposing to extend that agreement and make it a rule. As i understand it, after constantinople, there will be a hard fork 8 months later, and from then on once per year. 

Motivation

1. Stop endless discussions about block-rewards. 
2. Ensure reducing supply until PoS: which is expected between 2019-2020. 
3. Creates *some* monetary policy: allows some semblance of certainty for miners, gives confidence to investors.
4. Bonus: creates some pressure for timely hard-forks.

The calculation is simple

Current: 3  
Constantinople: 2  
Constantinople +1 (June/July 2019): 1.333333333  
+2 (June/July 2020): 0.888888889  
+3 (June/July 2021): 0.592592593  
+4 (June/July 2021): 0.395061728  

Rationale

Let's be realistic. Radical reductions in issuance are being arbitrarily proposed. What we want is certainty.

Backwards Compatibility

<list current block reward EIPs>  
<rules around what to do if hard-fork dates change>

Copyright

Copyright and related rights waived via CC0.
