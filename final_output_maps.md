# Fraud & Identity Sourcing Scrape — Market Maps — 2026-05-09

## Summary Counts

| Metric | Count |
|---|---|
| Market map sources catalogued | 30 text sources + 5 screenshot images |
| Raw companies extracted from maps | ~120 (~90 from text sources + ~30 from screenshots) |
| Removed — already in Notion Deals DB | 51 |
| Deduped leads (net-new vs. Notion) | ~48 |
| Removed in Phase 3 qualification | ~38 |
| **Final qualifying leads** | **10** |

**Phase 3 removal reasons (text sources):**
- Too large (>600 LinkedIn employees): Riskified, Incode, Sumsub, Quantexa, Chainalysis, ID.me, ZeroFOX (7)
- Too small (<90 LinkedIn employees): Netacea, Lucinity, Pixalate, Reality Defender, Fraudio, Deduce (6)
- HQ outside NA/W.Europe/Israel: HyperVerge, ClearSale, Kyckr, Tookitaki, Merkle Science, TrafficGuard, Bureau, IDVerse, Regula Forensics (9)
- Acquired by strategic/holding company: Nethone (Mangopay), Acuant (HID/ASSA ABLOY), Alessa (Valsoft Corp), Deduce (CHEQ) (4)
- No PitchBook data / too small/early: IPQS, Dodgeball, Neterium, CrossClassify, TrustDecision, Verisoul (6)

**Phase 3 removal reasons (screenshot maps):**
- Too large (>600 employees): EXIGER (1)
- Too small (<90 employees): PXL Vision (36), Secret Double Octopus (52), Vouched (49), Futurae (65), Verifai (17), OwnID (20), Markaaz (76) (7)
- HQ outside NA/W.Europe/Israel: VU Security (Buenos Aires) (1)
- Acquired by strategic/holding company: KEYLESS (Ping Identity, Dec 2025), Nok Nok Labs (OneSpan, Jun 2025), OwnID (Unico, Sep 2025), W2 Global Data (FullCircl/nCino, Aug 2023), Kompany (Moody's), BehavioSec (LexisNexis), SecureKey (Interac), Similia (PayPal) (8)
- No PitchBook data / too small/early: HANKO, Autotix, Detected KYB, Ever-C, CleverChain, Enigma (6)

---

## Qualifying Leads

| Company | HQ | Employees | Financing Status | Last Round Type | Last Round Date | Deal Size | Lead Investors | Sectors | One-Line Description | Data / Moat | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Chargebacks911 | Clearwater, FL | ~400 | Bootstrapped | — | — | — | — | Chargeback Management | End-to-end chargeback dispute management and representment platform for merchants, acquirers, and issuers. | 15+ years of proprietary dispute data and direct bank/card-network relationships; Intelligent Source Detection™ fingerprints chargeback root causes at scale. | Bootstrapped and profitable; US/UK offices; strong SMB and mid-market merchant base. |
| HUMAN Security | New York, NY | ~469 | PE-Backed | Growth Equity / Recapitalization | 2021 | Undisclosed | Vista Equity Partners | Bot Management, Ad Fraud, E-commerce Fraud | Bot and fraud prevention platform that verifies the humanity of digital interactions across advertising, media, and e-commerce. | Collective defense network across 3T+ weekly digital interactions; shared threat intelligence creates compounding network effect with scale. | Formerly White Ops; rebranded 2021; Vista Equity Partners majority investor; PE-backed. |
| ThreatMark | Charlotte, NC (Czech-founded) | ~100 | VC-Backed | Series A | Jan 2025 | $23M | Octopus Ventures (+ Riverside Company, Springtide Ventures) | Behavioral Biometrics, ATO Prevention | Behavioral biometrics and session intelligence platform for banks detecting ATO, social engineering scams, and session anomalies across web and mobile banking. | Behavioral models trained on bank-specific transaction and navigation patterns; deep SDK integration into banking front-ends; collects 2,000+ behavioral signals per session. | Czech-founded, US-incorporated; strong European bank customer base; Series A Jan 2025. |
| NetGuardians (now Vyntra Global) | Yverdon-les-Bains, Switzerland | 155 | PE-Backed | Buyout/LBO | Jul 2024 | Undisclosed | Summa Equity | AML, Fraud, Transaction Monitoring | Transaction intelligence platform for financial institutions combining real-time fraud detection, AML compliance, and behavioral analytics. | Deep integration with core banking systems (Temenos, Finacle, etc.) and proprietary behavioral profiling engine tuned to banking transaction patterns; strong Swiss and European FI client base. | Already PE-owned (Summa Equity LBO Jul 2024); secondary buyout or add-on scenario. |
| Transmit Security | Boston, MA | 317 | VC-Backed | Series A | Jun 2021 | $543M | General Atlantic, Insight Partners (+ Citi Ventures + 7 others) | CIAM, Authentication, Fraud Detection | Unified CIAM and fraud prevention platform offering passwordless authentication, adaptive MFA, and AI-driven fraud decisioning for enterprise digital experiences. | Single platform eliminating fragmentation across identity, authentication, and fraud stacks; strong Fortune 500 and FSI customer base; Israeli engineering team. | Unicorn valuation ($2.74B, Jun 2021); no round since 2021 — potential valuation reset; Israeli-founded, Boston HQ. |
| Ondato | London, UK | 105 | VC-Backed | Equity Crowdfunding (convertible) | Undisclosed (2024) | Undisclosed | SeedBlink (crowdfunding) | Identity Verification, KYC | KYC and identity verification platform offering digital ID verification, biometric checks, document capture, and compliance workflow automation for banks and fintechs. | Configurable multi-jurisdiction compliance workflow engine; supports EU eIDAS, UK FCA, and DORA requirements; Lithuanian engineering roots with strong European regulatory coverage. | Lithuanian-founded, London HQ; last institutional round was Aug 2022 Later Stage VC; recent round was equity crowdfunding convertible via SeedBlink — thin institutional backing. |
| Pindrop | Atlanta, GA | ~343 | VC-Backed | Debt - General | Jul 2024 | $100M | Undisclosed (debt) | Voice Fraud, Call Center Authentication | AI-powered voice fraud detection and call center authentication platform that analyzes audio signals to verify caller identity and flag fraudulent calls in real time. | Phoneprinting™ technology analyzes 1,300+ audio signals (device, carrier, network, behavior) per call; network of 600+ enterprise clients generates shared threat intelligence; ~$100M revenue signals product-market fit. | Founded 2011 Atlanta; ~$100M revenue; $100M debt facility Jul 2024 (post equity funding); strong presence in FSI, insurance, and government call centers. |
| Shift Technology | Paris, France | ~587 | VC-Backed | Series C | May 2021 | $219M | Accel, General Atlantic, Bessemer Venture Partners | Insurance Fraud, Claims Intelligence | AI-powered insurance claims fraud detection and STP (straight-through processing) automation platform for P&C, health, and life insurers globally. | Trained on hundreds of millions of insurance claims across multi-insurer consortium data; carrier network creates cross-insurer fraud signal sharing; deep core system integrations with Guidewire, Majesco, Duck Creek. | Paris HQ; $315.6M total raised; no round since May 2021 — potential valuation reset; at upper boundary of employee range (587 emp); global insurer client base. |
| Fourthline | Amsterdam, Netherlands | ~224 | VC-Backed | Later Stage VC | Apr 2023 | €50M (~$55M) | Finch Capital, Hedosophia | Identity Verification, KYC, AML | End-to-end KYC and identity verification platform for regulated financial institutions combining document verification, biometrics, NFC chip reading, and AML screening. | Proprietary ID document database covering 4,000+ documents from 195 countries; bank-grade data retention architecture; deep EU regulatory expertise (AMLD6, DORA, eIDAS 2.0); growing cross-border compliance complexity is structural tailwind. | Netherlands-founded and HQ; strong EU FSI client base; Finch Capital + Hedosophia backing; regulatory complexity in EU creates durable demand. |
| ThetaRay | Hod HaSharon, Israel | ~260 | VC-Backed | Series C | Sep 2023 | $57M | Portage Capital (+ OurCrowd, Jerusalem Venture Partners, ABN AMRO Ventures) | AML, Transaction Monitoring, Financial Crime | AI-powered transaction monitoring and AML platform for banks and fintechs detecting financial crime across cross-border and correspondent banking payment flows. | SONAR™ unsupervised AI detects novel crime typologies without labeled training data; deep integration with SWIFT and correspondent banking networks; processing 50B+ transactions/year across 60+ countries. | Israeli-founded and HQ; $154.3M total raised; SWIFT partnership provides strategic distribution; Portage Capital (FinTech specialist) Series C lead; cross-border AML is regulatory priority globally. |

---

## Already in Notion Deals Database (51 companies)

*Full list in notion_matches_maps.md. Key names: Sift, Signifyd, Forter, Sardine, SEON, Ravelin, Vesta, Chargeflow, Jumio, Veriff, Trulioo, Socure, Persona, Au10tix, iProov, Middesk, iDenfy, Mitek, 1Kosmos, ComplyAdvantage, Feedzai, DataVisor, Hawk AI, Napier AI, DataDome, Incognia, BioCatch, Unit21, Fingerprint, Prove Identity, Callsign, Beyond Identity, Daon, HYPR, TRM Labs, Elliptic, Alloy, Resistant AI, Scienaptic, Hummingbird, FRISS, Pipl, SentiLink, SpyCloud, GBG, Salv, IDnow, Oscilar, Fraud.net, Shufti Pro.*
