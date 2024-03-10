# Authz Grants

Authz Grants or _Authorization Grants_ are a feature provided by the Cosmos SDK to users and delegators to allow the delgators (`granter`) to grant authorization (`grant`), or in simple words _permission_ to another account (`grantee`) to perform actions on behalf of the user (_allowed actions are explicitly specified at the time of asking for an authz grant, along with an expiration date and monetary limits of the grant_). This essentially means that the grantee cannot do anything with the granter's account that they did not ask explicit permission for.



**More Info:** [https://ida.interchain.io/tutorials/8-understand-sdk-modules/1-authz.html](https://ida.interchain.io/tutorials/8-understand-sdk-modules/1-authz.html)

**Technical Documentation:** [https://docs.cosmos.network/main/build/modules/authz](https://docs.cosmos.network/main/build/modules/authz)

**Code:** [https://github.com/cosmos/cosmos-sdk/blob/main/docs/architecture/adr-030-authz-module.md](https://github.com/cosmos/cosmos-sdk/blob/main/docs/architecture/adr-030-authz-module.md)
