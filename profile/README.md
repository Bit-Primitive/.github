# Bit Primitive

Open-source tools that turn raw blockchain data into clean, documented tables in a warehouse you own, and the open datasets they produce. Built in Cape Town.

### [chainstar](https://github.com/Bit-Primitive/chainstar)

Raw blockchain data to clean dimensional tables in your own warehouse, from one command. **Ethereum, Base, Bitcoin and Solana** into DuckDB or Postgres, as a tested dbt star schema of transfers, fees, wallets, tokens and dates. You bring the RPC, or try it on free public endpoints; nothing passes through us.

```sh
uv tool install git+https://github.com/Bit-Primitive/chainstar
chainstar quickstart
chainstar export transfers --output transfers.xlsx
```

- **Try it live:** [query real chainstar output in your browser](https://bitprimitive.com/projects/chainstar/demo), no install
- **Docs:** [get started in 2 minutes](https://bitprimitive.com/projects/chainstar/docs/get-started)

### [Open data](https://github.com/Bit-Primitive/open-data)

Documented, checksummed Parquet datasets built with chainstar, licensed CC BY 4.0. Browse and preview them with SQL at [bitprimitive.com/data](https://bitprimitive.com/data).

---

[Website](https://bitprimitive.com) · [Releases](https://bitprimitive.com/releases) · [Data portal](https://bitprimitive.com/data)
