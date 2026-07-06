# Crypto Fraud Prevention & Security Checklist

# Crypto Fraud Prevention & Security Checklist

## Common Scam Types & Red Flags

### 1. Phishing & Fake Websites
- **Red Flags:** Slightly misspelled domain names, urgent login requests, poor design quality
- **Prevention:** Bookmark official URLs, enable 2FA, verify SSL certificates, never click email links

### 2. Fake Coins & Token Impersonation
- **Red Flags:** Near-identical names to legitimate projects, fake social media accounts, no verifiable team
- **Prevention:** Check official contract address on block explorer, verify on CoinGecko/CMC, confirm team credentials

### 3. Fraudulent Projects & Pump-and-Dump
- **Red Flags:** Unrealistic promises, anonymous teams, pressure to buy "limited-time," celebrity endorsements
- **Prevention:** Research whitepaper, check GitHub activity, review team backgrounds, audit reports

### 4. Fake Support/Customer Service
- **Red Flags:** Impersonating official support, DM offers to "recover funds," asking for seed phrases
- **Prevention:** Contact support only via official channels, official reps never ask for private keys

## Personal Security Checklist

- [ ] Use hardware wallet for large holdings
- [ ] Enable 2FA on all exchanges & wallets (authenticator app, not SMS)
- [ ] Never share seed phrases or private keys with anyone
- [ ] Verify addresses character-by-character before sending funds
- [ ] Use different passwords for each service
- [ ] Keep software/firmware updated
- [ ] Avoid public WiFi for sensitive transactions
- [ ] Bookmark official sites; never click email links
- [ ] Use multisig wallets for team/organizational funds

## If You've Been Scammed

### Immediate Steps
1. **Document everything:** screenshots, transaction hashes, wallet addresses
2. **Report to platform:** contact exchange/wallet support immediately
3. **File official report:**
   - **China:** 中国互联网联合辟谣平台 (China Internet Joint Rumor Debunking Platform)
   - **US:** SEC Complaint, FBI IC3 (ic3.gov), CFTC
   - **International:** Interpol, local law enforcement
4. **Monitor wallets:** check if stolen funds move on blockchain explorer
5. **Alert your bank:** if funds were transferred via fiat on/off ramp

### Recovery Resources
- Contact blockchain analysis firms (Chainalysis, TRM Labs)
- Report to exchange where stolen funds are likely to be cashed out
- Pursue legal action if funds are substantial
- File tax loss deduction (jurisdiction-dependent)

## Verification Tools & Resources

| Resource | Purpose |
|----------|----------|
| Etherscan, Solscan, BscScan | Verify contract code & holder distribution |
| CoinGecko, CoinMarketCap | Confirm legitimate listing |
| GitHub | Check project code activity & commits |
| Twitter/Discord | Verify official accounts (blue check, verified link) |
| Blockchain Explorers | Track fund movement & wallet history |
| Audit Reports | OpenZeppelin, Trail of Bits (smart contract security) |

## Reporting Channels by Region

**China:**
- 中央网信办举报中心 (Cyberspace Administration)
- 全国"扫黑除恶"举报平台

**US:**
- SEC Complaint Portal: sec.gov/complaint
- FBI Internet Crime Complaint Center: ic3.gov
- CFTC Whistleblower: cftc.gov/complaint

**EU:**
- Local financial regulator (FCA, BaFin, etc.)
- ESMA (European Securities and Markets Authority)

**APAC:**
- Hong Kong SFC, Singapore MAS, Australia ASIC

## Developer Integration Notes

When building crypto applications:
- Implement address verification warnings
- Display contract audit status (if available)
- Add scam-report mechanisms in your UI
- Educate users on seed phrase safety in onboarding
- Validate token contracts against official registries

## Reference

[read this 数字货币怎么防止被骗：完整防骗指南与实战技巧 article](https://trendkoin.com/security/how-to-avoid-scams)
