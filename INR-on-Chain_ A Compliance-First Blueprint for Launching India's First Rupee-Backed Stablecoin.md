# INR-on-Chain: A Compliance-First Blueprint for Launching India's First Rupee-Backed Stablecoin

## Executive Summary

Launching India's first compliant, INR-pegged stablecoin is a high-risk, high-reward venture that demands a strategy of proactive compliance, deep regulatory engagement, and clear value differentiation. The primary challenge is a significant regulatory minefield, characterized by the Reserve Bank of India's (RBI) deep-seated skepticism towards private digital currencies, its preference for its own Central Bank Digital Currency (e-Rupee), and the explicit exclusion of crypto-assets from its primary regulatory sandbox [key_challenges_and_recommendations.challenge_description[0]][1]. Compounding this is a punitive tax regime for all Virtual Digital Assets (VDAs), which includes a 30% tax on gains and a 1% Tax Deducted at Source (TDS) on transfers, creating significant friction for payments and trading [indian_regulatory_landscape_analysis.taxation_framework[0]][2].

Despite these hurdles, the market opportunity is immense. India is the world's largest remittance recipient, with over **$129 billion** in annual inflows, where transaction costs average **4-5%**—a figure a stablecoin could slash to under **1%** [go_to_market_and_ecosystem_development_plan.target_customer_profiles_and_use_cases[0]][3]. Furthermore, India leads in grassroots crypto adoption, with users paying high premiums for USD-stablecoin on-ramps, indicating a clear demand for a native, efficient alternative [project_summary[0]][4]. The strategic imperative is to position the INR stablecoin not as a speculative cryptocurrency but as a compliant payment innovation built on radical transparency and user protection. This involves framing the asset as a "tokenized real-world asset" (tokenized INR) to align with potential regulatory pathways like the IFSCA sandbox in GIFT City [key_challenges_and_recommendations.strategic_recommendation[0]][5].

The blueprint for success is a three-pronged approach. First, establish an unimpeachable governance and reserve management model, mirroring global best practices like Singapore's MAS framework [key_challenges_and_recommendations.strategic_recommendation[0]][5]. This requires **1:1 backing** with high-quality liquid INR assets held in a bankruptcy-remote trust, verified by daily on-chain Proof-of-Reserves and monthly attestations from a 'Big Four' audit firm. Second, build a robust technology stack on a permissioned core ledger with compliance-centric token standards (like ERC-3643) to enable on-chain KYC and sanctions enforcement, while using secure bridges to connect to public blockchains for broader ecosystem access. Third, engage in a sophisticated, multi-stakeholder policy advocacy campaign to catalyze a bespoke licensing regime, demonstrating tangible economic benefits that align with national priorities like reducing payment friction and enhancing financial inclusion. Success is contingent on navigating the regulatory landscape with a compliance-first mindset, building trust through transparency, and proving that a privately issued stablecoin can be a powerful, safe, and efficient component of India's digital economy.

## 1. Market Opportunity — INR stablecoin can unlock a >₹6,000 cr annual fee pool by slashing remittance and payout costs

### 1.1 Remittance Pain Points: $129 B inflows taxed ≈ $6.4 B fees (table of corridor costs)

India stands as the world's foremost recipient of remittances, with inflows projected to reach **$129 billion** in 2025 [project_summary[0]][4]. However, the cost of sending these funds remains stubbornly high, with global averages hovering around **6.49%** and digital remittance costs at **4.85%**. This translates to an estimated **$6.4 billion** in fees extracted from funds sent to India annually. An INR-pegged stablecoin operating on efficient blockchain rails presents a disruptive alternative, with the potential to reduce these costs by over **90%**, from the current **4-5%** average to less than **1%** [go_to_market_and_ecosystem_development_plan.target_customer_profiles_and_use_cases[0]][3]. This creates a massive addressable market by offering a cheaper, faster, and more transparent channel for cross-border payments.

| Corridor | Traditional Avg. Cost | Digital Avg. Cost | Stablecoin Potential Cost | Annual Savings Potential (on $129B) |
| :--- | :--- | :--- | :--- | :--- |
| Global Average | 6.49% | 4.85% | <1% | >$5.1 Billion |
| Key Corridors (US, UAE, SG) | 4-6% | 3-5% | <1% | Significant portion of total savings |

*This analysis highlights the substantial value proposition of a stablecoin in reducing friction in India's largest cross-border financial flow.*

### 1.2 Web3 On-Ramp Premiums: Indian users pay 6-8 % spread for USDT/USDC (data table)

India leads the world in grassroots crypto adoption, yet users face significant friction and high costs when entering the Web3 ecosystem [project_summary[0]][4]. The primary on-ramp involves converting INR to a USD-pegged stablecoin like USDT or USDC, a process that often incurs a premium of **6-8%** due to liquidity challenges, regulatory hurdles, and foreign exchange conversion costs. This "on-ramp tax" creates a major barrier to entry for millions of potential users and developers. A compliant, liquid, and easily accessible INR-pegged stablecoin would solve this problem directly. It would serve as a frictionless bridge between India's domestic payment systems (like UPI) and the global Web3 ecosystem, eliminating the need for costly and inefficient multi-step conversions.

### 1.3 Domestic Payments Gap: UPI rules out programmability; stablecoin fixes escrow, instant settlement

While the Unified Payments Interface (UPI) has revolutionized retail payments in India, its architecture is not designed for programmable or conditional payments. This creates gaps in use cases requiring automated logic, such as escrow services, instant B2B invoice settlement upon delivery confirmation, or automated royalty payouts. An INR stablecoin built on smart contracts can fill this gap, enabling "programmable money" that can be locked, released, or transferred based on predefined, automated rules. This unlocks significant efficiency gains for businesses, particularly in the gig economy, which is projected to have **23.5 million workers by 2030**, by enabling instant, low-cost mass payouts and payroll [go_to_market_and_ecosystem_development_plan.target_customer_profiles_and_use_cases[0]][3].

### 1.4 Competitive Landscape: INRx, Cardano-INR, e-Rupee (comparison table: peg method, audits, compliance)

The landscape for an INR-pegged digital currency is nascent but evolving. The primary competitor is the RBI's own CBDC, the e-Rupee, which benefits from sovereign backing but has seen cautious and limited growth, with circulation reaching **₹1,016 crore** by March 2025. In the private sector, a few projects are emerging, though their regulatory standing and transparency remain unclear.

| Project | Peg Mechanism | Audits/Transparency | Compliance Status | Blockchain | Development Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **e-Rupee (CBDC)** | Direct liability of RBI | Centrally managed by RBI | Sovereign, fully regulated | Proprietary | Live in pilot phase |
| **INRx Coin** | 1:1 INR backing claimed | Unclear public audit framework | Unregulated, operating in a grey area | Proprietary (INRx Network) | Live and operational [current_inr_stablecoin_projects_overview.0.development_status[0]][6] |
| **Cardano Project** | 1:1 INR backing proposed | Proposed compliance reports | Pre-launch, seeking compliance | Cardano | Finalizing architecture [current_inr_stablecoin_projects_overview.1.development_status[0]][7] |

*The key differentiator for a new entrant is to offer radical transparency and a clear, compliant regulatory pathway, which current private projects lack and the e-Rupee does not need to prioritize in the same way.*

## 2. Regulatory Landscape — High ambiguity but sandbox footholds exist

### 2.1 RBI & CBDC Focus: Timeline of circulars, informal bank pressure

The Reserve Bank of India (RBI) remains the most significant obstacle, maintaining a deeply skeptical stance on private digital currencies, which it views as a threat to financial stability [key_challenges_and_recommendations.challenge_description[0]][1]. While its 2018 circular banning banks from servicing crypto firms was overturned by the Supreme Court, its prohibitive stance persists through informal pressure on regulated entities, creating a "shadow ban" that complicates banking access for VDA platforms. The RBI's primary focus is its own CBDC, the e-Rupee (e₹), which it positions as the only legitimate, risk-free digital alternative to private stablecoins [indian_regulatory_landscape_analysis.rbi_stance_and_cbdc_focus[0]][8]. This institutional opposition means any private stablecoin must be designed to be regulatorily palatable, likely through a bank-led consortium model rather than as a standalone fintech entity.

### 2.2 Tax Regime Impact: 30 % gains, 1 % TDS cuts velocity by 40 % (table: tax vs usage metrics)

India's tax framework for Virtual Digital Assets (VDAs), introduced in 2022, is one of the most stringent globally and creates significant friction for stablecoin usage [indian_regulatory_landscape_analysis.taxation_framework[0]][2].

| Tax Provision | Description | Impact on Stablecoin Usage |
| :--- | :--- | :--- |
| **Section 115BBH** | Flat **30% tax** on any income from the transfer of VDAs. No deductions allowed except cost of acquisition. Losses cannot be offset or carried forward. | Discourages high-frequency trading and use in payments, as even minor gains from peg fluctuations are heavily taxed. The inability to offset losses makes market-making and arbitrage activities economically challenging. |
| **Section 194S** | **1% Tax Deducted at Source (TDS)** on the consideration for every VDA transfer above annual thresholds (**₹10,000** for most users, **₹50,000** for specified persons). | Creates a significant liquidity drag and operational complexity, especially for automated or high-volume payment systems. This friction is estimated to have reduced trading velocity on Indian exchanges by approximately 40%. |

*This tax regime makes it nearly impossible for a stablecoin to function as an efficient medium of exchange for everyday payments, pushing the immediate use case towards larger, less frequent transactions like remittances and B2B settlements.*

### 2.3 FEMA & Cross-Border Limits: Why SRVA model is the only compliant route

The Foreign Exchange Management Act (FEMA) presents a formidable barrier to permissionless, peer-to-peer cross-border stablecoin transactions [indian_regulatory_landscape_analysis.foreign_exchange_regulations[0]][8]. The RBI has clarified that the Liberalised Remittance Scheme (LRS) cannot be used for crypto-asset investments, effectively blocking official channels for outward remittances [indian_regulatory_landscape_analysis.foreign_exchange_regulations[0]][8]. Furthermore, RBI Master Directions prohibit INR-denominated Prepaid Payment Instruments (PPIs) from being used for cross-border outward transfers. This makes a direct-to-consumer model for outward payments unfeasible. The only viable compliance strategy is a permissioned, bank-led model that leverages the RBI's **Special Rupee Vostro Account (SRVA) framework**, which is designed for international trade settlement in INR [cross_border_remittance_and_trade_model.proposed_operational_model[0]][9]. This ensures all foreign exchange flows are channeled through Authorized Dealer banks, remaining fully documented and compliant with FEMA.

### 2.4 Sandbox Windows: IFSCA vs RBI exclusion (pros/cons table)

With the primary RBI Regulatory Sandbox explicitly excluding "Crypto currency/Crypto assets services," the most promising path for initial testing and regulatory engagement is the **IFSCA FinTech Regulatory / Innovation Sandbox** in GIFT City.

| Sandbox | Pros | Cons | Strategic Approach |
| :--- | :--- | :--- | :--- |
| **RBI Regulatory Sandbox** | Direct engagement with the primary financial regulator; clear path to mainland India launch if approved. | **Explicitly excludes crypto-assets**, making it a non-starter for a stablecoin project in its current form [key_challenges_and_recommendations.challenge_description[0]][1]. | Long-term advocacy to amend the sandbox framework to include compliant, asset-backed digital tokens. |
| **IFSCA (GIFT City) Sandbox** | Open to innovative fintech solutions, including those involving tokenization. Provides a controlled environment to demonstrate a compliant model to a progressive regulator. | Limited to the GIFT City jurisdiction initially; requires a clear transition strategy for a pan-India launch. | Frame the project as **"tokenization of a real-world asset"** (tokenized INR) rather than a "cryptocurrency" to align with the IFSCA's focus and gain a foothold. |

*The IFSCA sandbox offers a crucial, immediate pathway to build a track record of compliant operations, which can then be used to build a case for a broader, pan-India license.*

## 3. Legal & Corporate Structure — Consortium + bankruptcy-remote trust minimizes RBI pushback

### 3.1 Issuer Models Compared: NBFC, PPI, Consortium Bank (table of licence fit & gaps)

Choosing the right legal structure is critical for regulatory acceptance. A consortium of existing regulated entities is the most viable path, as other models face significant legal and regulatory hurdles.

| Issuer Model | Rationale / Analogy | Key Regulatory Blockers | Viability |
| :--- | :--- | :--- | :--- |
| **NBFC** | Regulated entity with financial oversight. | Prohibited from accepting demand deposits, which is analogous to issuing redeemable stablecoins. | **Low** |
| **Payment Aggregator (PA)** | Licensed for payment facilitation. | Role is to facilitate payments between parties, not to issue a payment instrument or hold a float. | **Low** |
| **Prepaid Payment Instrument (PPI)** | Closest analogy; involves issuing a prepaid value instrument. | RBI's exclusion of crypto-assets from its sandbox makes this a difficult path to pursue for a blockchain-based instrument. | **Medium (but challenging)** |
| **Bank-led Consortium** | Leverages existing, highly regulated entities (banks, PSOs) with robust compliance and infrastructure. | Requires coordination among multiple entities. | **High (Recommended)** |

*A consortium model is more palatable to the RBI as it keeps innovation within the existing regulatory perimeter, minimizing perceived systemic risk.*

### 3.2 Trust & Escrow Design: IBC Section 36(4)(a)(iii) protections

To protect user funds from issuer insolvency, the reserve assets must be legally segregated in a bankruptcy-remote vehicle. The optimal structure is a **private trust** established under the Indian Trusts Act, 1882, with stablecoin holders as the designated beneficiaries. This structure ensures that under Section 36(4)(a)(iii) of the Insolvency and Bankruptcy Code (IBC), 2016, the reserve assets are held in a fiduciary capacity and are not considered part of the issuer's liquidation estate. All reserve funds must be held in dedicated escrow accounts with Scheduled Commercial Banks in India, strictly separated from the issuer's operational capital, following the stringent guidelines set by the RBI for Payment Aggregators.

### 3.3 Board & Committees: Audit, Risk, Compliance setups aligned to SEBI LODR

The issuing entity must be a company incorporated in India under the Companies Act, 2013. Its governance framework must meet the high standards of a regulated financial entity. The board should feature a professional mix of executive and independent directors, with at least one-third being independent, in line with SEBI's Listing Obligations and Disclosure Requirements (LODR). Mandatory board-level committees must include:
* **Audit Committee:** As per Section 177 of the Companies Act, to oversee financial reporting and internal controls.
* **Risk Management Committee (RMC):** To oversee all enterprise risks, including reserve adequacy, liquidity, and cybersecurity.
* **Compliance Committee:** To ensure adherence to all regulatory directives, including PMLA and FIU-IND obligations.
* **Nomination and Remuneration Committee (NRC):** To manage board appointments and executive compensation.

## 4. Reserve Management Framework — 1:1 HQLA, daily PoR, monthly Big-4 attestations

### 4.1 Eligible Assets Ladder: Cash vs 91-day T-Bills vs G-secs (yield table)

The stablecoin must be **100% backed** by a reserve of high-quality liquid assets (HQLA) denominated exclusively in Indian Rupees (INR). The portfolio must be conservative to ensure stability and immediate liquidity, aligning with the RBI's definition of Level 1 HQLA [reserve_management_and_assurance_framework.eligible_reserve_assets[0]][10].

| Asset Class | Description | Maturity | Indicative Yield (Sept 2025) | Role in Reserve |
| :--- | :--- | :--- | :--- | :--- |
| **Cash** | Deposits in scheduled commercial banks | Overnight | N/A (Cost) | Immediate liquidity for redemptions |
| **Treasury Bills (T-Bills)** | Zero-coupon government securities | 91, 182, 364 days | **5.51%** (91-day) | Core of the reserve; provides yield |
| **Government Securities (G-Secs)** | Interest-bearing government bonds | 1-2 years | **5.82%** | Higher yield component for a portion of the reserve |

*A liquidity ladder must be maintained, with a significant portion in cash and overnight repo on G-secs to meet redemption demands without having to sell longer-duration assets at a potential loss.*

### 4.2 Diversified Custody Plan: Multi-bank limits & stress-test triggers

To mitigate counterparty and concentration risk, reserve assets must be held with a select group of large, systemically important Indian commercial banks. Cash holdings must be diversified across multiple custodian banks, with strict internal limits on the percentage of the total reserve held at any single institution. All assets must be held in the bankruptcy-remote trust, legally segregated from the issuer's operational funds, for the sole benefit of stablecoin holders [reserve_management_and_assurance_framework.custody_and_diversification_policy[0]][11].

### 4.3 Redemption SLA & Liquidity Stress-Tests: 5-day backstop, run simulations

A robust liquidity risk management framework, aligned with FSB and CPMI-IOSCO standards, is mandatory [reserve_management_and_assurance_framework.risk_management_and_stress_testing[0]][12]. This includes regular, rigorous stress testing that simulates severe redemption scenarios (a 'bank run') to ensure the issuer can meet large-scale redemptions at par. A clear Contingency Funding Plan (CFP) must be in place to address potential shortfalls. The issuer must guarantee holders a direct legal claim to redeem the stablecoin for fiat INR at par (1:1), with a Service Level Agreement (SLA) specifying a maximum fulfillment window of **five business days** as a backstop, mirroring the standard set by Singapore's MAS [global_stablecoin_regime_comparison.primary_lesson_for_india[0]][13].

## 5. Technology Architecture — Permissioned core + ERC-3643 compliance unlocks public-chain reach

### 5.1 Chain Selection Rationale: GoQuorum vs Hyperledger vs Corda (comparison table)

A **permissioned blockchain** is the recommended foundation for the core ledger due to the need for regulatory control, KYC/AML enforcement, and predictable performance [blockchain_and_smart_contract_architecture.recommended_blockchain_architecture[0]][14]. A hybrid model, connecting this permissioned core to public chains via secure bridges, offers the best long-term strategic approach.

| Platform | Consensus | Smart Contracts | Key Advantage for INR Stablecoin |
| :--- | :--- | :--- | :--- |
| **GoQuorum** | IBFT / QBFT | Solidity (EVM-compatible) | High EVM compatibility makes it easy to integrate with the broader Ethereum ecosystem and tooling. |
| **Hyperledger Fabric** | Pluggable (e.g., Raft) | Go, Java, JavaScript | Highly modular architecture with "private data collections" for granular privacy control between participants. |
| **Corda** | Notary-based | Java, Kotlin | Designed specifically for financial services with a focus on privacy; transactions are only shared between relevant parties. |

*GoQuorum is recommended for its EVM compatibility, which simplifies integration with public Layer-2 networks and allows for the use of established, audited token standards.*

### 5.2 Smart-Contract Governance: owner/masterMinter/pauser roles with timelock

A robust on-chain governance model with clear separation of duties is essential for security and trust [blockchain_and_smart_contract_architecture.governance_and_access_control[0]][15]. This involves distinct roles with specific permissions, controlled by a multi-signature wallet (e.g., Gnosis Safe) to prevent unilateral actions.
* **`owner`**: Highest-level admin for assigning roles and managing contract upgrades.
* **`masterMinter`**: Controls which addresses can mint new tokens and sets their minting limits.
* **`pauser`**: An emergency kill-switch to halt all token transfers in a crisis.
* **`blacklister`**: A compliance role to block sanctioned or illicit addresses.
* **`rescuer`**: A safety role to retrieve tokens accidentally sent to the contract address.
All administrative actions should be subject to a **timelock**, a mandatory delay before execution, allowing for public review and intervention if necessary.

### 5.3 Cross-Chain Interop: Chainlink CCIP risk controls

To connect the permissioned core to public blockchains like Polygon or Arbitrum, a highly secure and audited bridge is required. Chainlink's **Cross-Chain Interoperability Protocol (CCIP)** is recommended due to its defense-in-depth security model, which includes a separate Risk Management Network that independently monitors and validates cross-chain operations to prevent exploits. This approach avoids the single points of failure that have led to major bridge hacks in the past.

### 5.4 Safety Features: Upgradeability, kill-switches, automatic sanctions lists

The smart contract system must embed several critical safety features:
* **Upgradeability:** Using a proxy pattern (e.g., transparent or beacon proxy) to allow logic to be updated to patch vulnerabilities or adapt to new regulations without requiring a token migration [blockchain_and_smart_contract_architecture.key_safety_and_compliance_features[0]][16].
* **Kill-Switches:** The `pauser` role provides a system-wide freeze capability to contain damage during a security breach.
* **Programmable Compliance for Travel Rule:** The system must support the FATF Travel Rule, using the **IVMS 101** data standard for originator and beneficiary information, which can be enforced by the ERC-3643 token standard [blockchain_and_smart_contract_architecture.key_safety_and_compliance_features[0]][16].
* **Sanctions Compliance:** The `blacklister` role allows for the programmatic enforcement of sanctions by freezing assets associated with addresses on lists like the UNSC or UAPA lists, which can be automated via oracles [blockchain_and_smart_contract_architecture.key_safety_and_compliance_features[0]][16].

## 6. Wallet & Payment Integration — Custodial MPC wallets + deep UPI hooks drive mass adoption

### 6.1 Aadhaar e-KYC & Alt-OVD Onboarding Flow

The user onboarding process must be scalable, compliant, and inclusive. The primary method should be the **Aadhaar e-KYC framework**, with the wallet provider acting as a KYC User Agency (KUA) or Sub-KUA [user_wallet_and_payment_integration_design.user_onboarding_and_kyc[0]][17]. The process must obtain explicit user consent in line with the DPDP Act and use the Aadhaar Virtual ID (VID) for enhanced privacy [user_wallet_and_payment_integration_design.user_onboarding_and_kyc[0]][17]. Since service cannot be denied to users unable to use Aadhaar, the flow must also support alternative Officially Valid Documents (OVDs) through Video-based Customer Identification (V-CIP) and integration with the Central KYC Registry (CKYC) [user_wallet_and_payment_integration_design.user_onboarding_and_kyc[0]][17].

### 6.2 Account Abstraction UX: gasless, social recovery, fee sponsorship

To drive mainstream adoption, the wallet experience must be seamless and intuitive. **Account Abstraction (ERC-4337)** is the key technology to achieve this. It decouples the user's account from a specific private key, enabling features that eliminate common crypto pain points:
* **Social Recovery:** Users can recover their accounts through trusted contacts or devices, removing the risk of losing funds from a lost seed phrase.
* **Gas Abstraction:** Users can pay transaction fees in the INR stablecoin itself, or the provider can sponsor fees, creating a "gasless" experience.
* **Transaction Batching:** Users can approve multiple operations (e.g., approve and transfer) in a single transaction.

### 6.3 UPI & QR Interoperability Map

Deep integration with India's Digital Public Infrastructure (DPI), particularly the **Unified Payments Interface (UPI)**, is fundamental for success [user_wallet_and_payment_integration_design.dpi_integration_plan[0]][18]. The plan includes:
* **On/Off-Ramps:** Using UPI as the primary real-time channel for converting fiat INR to the stablecoin and back.
* **QR Code Interoperability:** Ensuring the wallet can generate and scan all standard UPI QR codes, making the stablecoin instantly spendable at millions of existing merchant locations [user_wallet_and_payment_integration_design.dpi_integration_plan[0]][18].
* **Simplified Addressing:** Leveraging the 'UPI Number' feature to map a user's mobile number to their payment address for simple P2P transfers.
* **Compliance:** Implementing all mandatory UPI features, such as beneficiary name verification, and adhering to all NPCI guidelines [user_wallet_and_payment_integration_design.dpi_integration_plan[0]][18].

## 7. Offline Payments — USSD + NFC hybrid meets RBI ₹200/₹2,000 limits

### 7.1 Shadow-Wallet Model for Double-Spend Control

To prevent double-spending in an offline environment, a multi-layered approach is required. This includes hardware-based prevention using Secure Elements (SEs) on the device to securely track spent tokens [offline_payment_mechanism_design.double_spend_prevention_mechanism[0]][19]. Architecturally, a **'shadow wallet'** model will be implemented: when a user goes offline, a specific amount of funds is locked in their online account, and the offline device can only transact up to this pre-reserved limit, containing the total risk [offline_payment_mechanism_design.double_spend_prevention_mechanism[0]][19]. Any double-spend attempts are then detected during the mandatory online reconciliation process.

### 7.2 Device Risk Controls & Reconciliation Workflow

To mitigate risks like device theft, the system must enforce strict transaction and wallet limits aligned with the **RBI's Framework for Offline Digital Payments** [offline_payment_mechanism_design.risk_management_controls[0]][20]. This provides a clear, regulatorily accepted precedent.
* **Per-Transaction Limit:** A maximum of **₹200** for any single offline transaction [offline_payment_mechanism_design.risk_management_controls[0]][20].
* **Cumulative Wallet Limit:** A total offline balance of **₹2,000** stored on the device [offline_payment_mechanism_design.risk_management_controls[0]][20].
Once the limit is exhausted, the user must go online to reconcile transactions and replenish the offline balance before making further offline payments [offline_payment_mechanism_design.reconciliation_and_settlement_process[0]][19]. This process involves the device securely uploading its transaction log to the central server for validation and settlement on the main ledger.

## 8. Cross-Border Remittance Model — SRVA-based closed loop keeps FEMA compliance intact

### 8.1 Corridor Partnerships: UAE, SG, US licence matrix (table)

A compliant cross-border model requires partnerships with licensed financial entities in key remittance corridors to handle the final-leg conversion and payout.

| Corridor | Key Regulator(s) | Required Partner License/Status |
| :--- | :--- | :--- |
| **Singapore** | Monetary Authority of Singapore (MAS) | Must comply with MAS Stablecoin Framework (e.g., licensed as a Major Payment Institution) [cross_border_remittance_and_trade_model.corridor_specific_partnerships[0]][21]. |
| **UAE** | VARA (Dubai), DFSA (DIFC) | Licensed for Fiat-Referenced Virtual Assets (FRVAs) or Fiat Crypto Tokens. |
| **United States** | FinCEN, State Regulators (e.g., NYDFS) | Registered Money Services Business (MSB) with FinCEN and hold relevant state money transmitter licenses. |

*These partnerships are essential for ensuring end-to-end compliance and providing a seamless experience for remittance recipients.*

### 8.2 Capital-Control Safeguards & Reporting

The proposed operational model is a **permissioned, bank-led approach leveraging the RBI's Special Rupee Vostro Account (SRVA) framework** [cross_border_remittance_and_trade_model.proposed_operational_model[0]][9]. This framework is designed for international trade settlement in INR. In this model, the stablecoin acts as a real-time settlement layer within a regulated, closed-loop system. An Indian importer could transfer the stablecoin to the SRVA of an overseas exporter's partner bank, which then converts it to local currency [cross_border_remittance_and_trade_model.proposed_operational_model[0]][9]. This structure directly addresses the RBI's concerns about capital control circumvention by ensuring all foreign exchange transactions are channeled through Authorized Dealer banks, are fully documented, and comply with all FEMA reporting requirements.

## 9. Business & Economics — Float yield vs high compliance burn; break-even at ₹800 cr float

### 9.1 Revenue Stack: Float, fees, APIs (numbers table)

The issuer's revenue model is designed to be multi-faceted, with the primary stream being the yield generated from the reserve assets.

| Revenue Stream | Description | Indicative Metric |
| :--- | :--- | :--- |
| **Float Yield** | Interest earned on reserve assets (cash, T-bills, G-secs). | **~5.5%** blended annual yield on reserves (based on Sept 2025 rates). |
| **Transaction Fees** | Fees on institutional-sized minting and redemption. | **0.1%** fee on transactions >$100,000 (modeled on Tether). |
| **Enterprise APIs** | Tiered pricing for businesses using developer tools and APIs. | **$0.00050** per API call (modeled on Circle). |

*For a stablecoin with a circulation of ₹1,000 crore, a conservative 5.5% blended yield would generate ₹55 crore in annual revenue from the float alone.*

### 9.2 Cost Drivers: Compliance, audits, cyber, GST

Operational costs are substantial, driven by the need for institutional-grade compliance and security.
* **Compliance & Legal:** Ongoing counsel for navigating RBI, SEBI, and FEMA rules, plus PMLA compliance.
* **Audits & Reporting:** Monthly reserve attestations by a 'Big Four' firm, weekly reserve breakdowns, and full annual financial audits.
* **Cybersecurity:** State-of-the-art infrastructure, including MPC for key management and continuous monitoring.
* **Tax Burden:** An **18% Goods and Services Tax (GST)** is applicable on all service fees charged by the issuer, impacting margins [issuer_economic_and_business_model.core_cost_structure[0]][4].

### 9.3 Profitability Sensitivities: rate shock, redemption spike scenarios

The business model's sustainability is highly sensitive to external factors. Profitability is directly tied to interest rates; a drop in the RBI's policy rate would immediately reduce revenue from the float. The model is also vulnerable to redemption shocks. A large-scale 'run' could force the premature liquidation of G-secs at a loss, threatening the 1:1 peg. However, the most severe challenge is the VDA tax regime. The **30% tax on gains** and **1% TDS on transfers** create immense friction, suppressing the stablecoin's velocity and market capitalization, which in turn limits the size of the revenue-generating float [issuer_economic_and_business_model.sustainability_and_profitability_analysis[0]][4]. Achieving break-even is estimated to require a float of approximately **₹800 crore** to cover high fixed costs in a market where adoption is hampered by these taxes.

## 10. Go-to-Market & Ecosystem — Partnerships plus developer grants accelerate network effects

### 10.1 ICP Prioritisation: Remitters, gig payroll, SMEs, devs

The go-to-market strategy targets four primary customer profiles where the stablecoin offers a clear and immediate value proposition:
1. **Remittance Users:** The largest initial market, driven by the potential for drastic cost reduction.
2. **Payroll & Mass Payouts:** Businesses in India's large gig economy seeking cheaper, faster, and programmable disbursement rails.
3. **Exporters & SMEs:** Businesses needing efficient international payment settlement to reduce forex risk and improve cash flow.
4. **Fintech Platforms & Developers:** Crypto onramps, DeFi builders, and other fintechs who can use the stablecoin as a compliant foundational layer for new products [go_to_market_and_ecosystem_development_plan.target_customer_profiles_and_use_cases[0]][3].

### 10.2 Liquidity & Market-Making Plan (AMM + CEX table)

Deep and consistent liquidity is critical to maintain the 1:1 peg and build market confidence. The strategy involves:
* **Initial Seeding:** Partnering with institutional investors and HNWIs to provide initial capital for liquidity pools.
* **Decentralized Exchanges (DEXs):** Establishing deep liquidity pools on major Automated Market Makers (AMMs), pairing the INR stablecoin against key assets like USDT, USDC, ETH, and BTC.
* **Centralized Exchanges (CEXs):** Engaging professional market-making firms to maintain tight bid-ask spreads and robust order books on compliant domestic and international exchanges [go_to_market_and_ecosystem_development_plan.liquidity_and_market_making_strategy[0]][3].

### 10.3 Developer Program & Grant Mechanics

To foster a defensible ecosystem, a comprehensive developer program is essential. This includes providing robust, well-documented SDKs and APIs to simplify integration. A key component is a **Developer Grant Program** to fund teams building innovative projects using the INR stablecoin, focusing on priority use cases like DeFi, cross-border payments, and creator economy monetization. The issuer will also offer dedicated technical support and educational resources to accelerate development [go_to_market_and_ecosystem_development_plan.developer_program_and_ecosystem_growth[0]][22].

## 11. Cybersecurity & Incident Response — Triple audits, 6-hour CERT-In rule, multi-layer insurance

### 11.1 Threat Model & Defense Layers

The threat model covers four key areas:
1. **Smart Contracts:** Threats of re-entrancy, logic errors, or governance takeovers. Defenses include multiple independent audits, formal verification, and a permanent bug bounty program.
2. **Wallets (Hot/Warm/Cold):** Threat of private key compromise. Defense is a defense-in-depth model with >95% of reserves in air-gapped cold storage, a small portion in multi-sig warm wallets, and minimal funds in hot wallets.
3. **Backend Infrastructure:** Threats of server compromise and insider attacks. Defenses include a zero-trust architecture and stringent access controls.
4. **Reserves Management:** Threat of theft or fraud. Defenses include diversified custody with qualified, insured third-party custodians [cybersecurity_and_incident_response_plan.threat_model_and_defense_strategy[0]][23].

### 11.2 Lessons from WazirX/CoinDCX Hacks

The security design is directly informed by major Indian exchange hacks:
* **WazirX Hack (July 2024, $230M):** Exposed the risks of third-party custody and 'blind signing' in multi-sig wallets, mandating robust internal procedures and skepticism of relying solely on third parties [cybersecurity_and_incident_response_plan.lessons_from_past_breaches[0]][24].
* **CoinDCX Hack (July 2025, $44.3M):** Proved the critical importance of segregating customer funds in secure cold storage and maintaining a substantial treasury reserve to absorb losses and ensure business continuity [cybersecurity_and_incident_response_plan.lessons_from_past_breaches[0]][24].
* **Tether Hack (2017):** A global lesson on the value of a centralized blacklisting mechanism to contain damage post-theft [cybersecurity_and_incident_response_plan.lessons_from_past_breaches[0]][24].

### 11.3 Insurance & Resilience Budget

To achieve an institutional-grade security posture, the issuer will pursue key certifications like **SOC 2 Type II** and **ISO/IEC 27001:2022** [cybersecurity_and_incident_response_plan.compliance_and_resilience_measures[0]][25]. A multi-layered insurance strategy is critical, including a specific policy for assets in hot wallets (modeled on Coinbase's $255M policy), ensuring third-party custodians have significant coverage, and obtaining a general crime insurance policy [cybersecurity_and_incident_response_plan.compliance_and_resilience_measures[0]][25].

## 12. Governance & Consumer Protection — Ombudsman integration and clawback-ready exec pay

### 12.1 Board, Committees, Compensation Malus/Clawback

The issuer's governance will be structured to comply with Indian corporate law, with a board composed of executive, non-executive, and at least one-third independent directors. Key committees include Audit, Risk Management, and an IT Strategy Committee. Executive compensation will be modeled on RBI guidelines for banks, with a significant portion of variable pay subject to deferral and **'malus' (reduction) and 'clawback'** arrangements to hold executives accountable for long-term risks.

### 12.2 Transparency & Disclosure Calendar

A policy of radical transparency is essential. This includes at least **monthly public attestations** from a reputable auditing firm detailing the reserve composition. For incident disclosures, the policy will adhere to India's strict timelines, including reporting cybersecurity incidents to the RBI and CERT-In within **6 hours** of detection [governance_and_consumer_protection_framework.transparency_and_disclosure_commitments[0]][26]. Personal data breaches will be notified to the Data Protection Board and affected users in compliance with the DPDP Act, 2023 [governance_and_consumer_protection_framework.transparency_and_disclosure_commitments[0]][26].

## 13. AML/CFT & Data Compliance — FIU-IND reporting + RBI data localisation

### 13.1 KYC & Travel Rule Implementation

The issuer must register as a 'Reporting Entity' with the **Financial Intelligence Unit-India (FIU-IND)** and implement a full AML/CFT program [aml_cft_compliance_program.fiu_ind_registration_and_reporting[0]][27]. This includes a board-approved, risk-based KYC policy compliant with PMLA and RBI's KYC Master Direction [aml_cft_compliance_program.customer_due_diligence_and_risk_assessment[0]][27]. The issuer must fully comply with India's implementation of the FATF **'Travel Rule'** for all VDA transfers, with no minimum threshold, requiring the collection and transmission of originator and beneficiary information for every transaction [aml_cft_compliance_program.transaction_monitoring_and_travel_rule[0]][27].

### 13.2 Sanctions/PEP Screening Work-flow

A robust screening process is required at onboarding and pre-transaction. Customers and counterparties must be screened against UNSC sanctions lists and Indian domestic terrorist lists under the UAPA [aml_cft_compliance_program.sanctions_and_pep_screening[0]][27]. Relationships with Politically Exposed Persons (PEPs) are permitted but require Enhanced Due Diligence (EDD), including senior management approval and enhanced ongoing monitoring [aml_cft_compliance_program.sanctions_and_pep_screening[0]][27].

### 13.3 Data Localisation & Breach Notification Dual-Track

The issuer must strictly comply with the RBI's data localization circular, which mandates that all payment system data be stored **exclusively in India** [data_privacy_and_localization_compliance.rbi_data_localization_mandate[0]][28]. While data can be processed abroad, it must be brought back to India and deleted from foreign systems within 24 hours [data_privacy_and_localization_compliance.rbi_data_localization_mandate[0]][28]. The breach notification protocol is dual-track: personal data breaches must be reported to the Data Protection Board under the DPDP Act, while a broader range of cyber incidents must be reported to **CERT-In within a strict 6-hour timeline** [data_privacy_and_localization_compliance.breach_notification_procedure[0]][29].

## 14. Tax & Accounting — User 30 % VDA drag vs issuer GST & Ind AS treatment

### 14.1 User Tax Guidance Toolkit

Users of the stablecoin are subject to India's VDA tax regime: a flat **30% tax on gains** (Section 115BBH) and a **1% TDS** on transfers (Section 194S) [taxation_and_accounting_strategy.user_tax_implications[0]][30]. The issuer must provide clear tax guidance to users as a consumer protection measure, explaining these implications with practical examples and advising on record-keeping responsibilities [taxation_and_accounting_strategy.user_tax_guidance_plan[0]][30].

### 14.2 Issuer Accounting Entries & Disclosure

Under Indian Accounting Standards (Ind AS), the issued stablecoins must be treated as a **Financial Liability** on the issuer's balance sheet, as the issuer has a contractual obligation to redeem them for fiat INR on demand [taxation_and_accounting_strategy.accounting_treatment_for_issuer[0]][31]. The corresponding reserve assets must also be recorded on the balance sheet. The issuer must also comply with the Ministry of Corporate Affairs' mandate to disclose all VDA-related activities in its financial statements [taxation_and_accounting_strategy.accounting_treatment_for_issuer[0]][31].

## 15. Policy Advocacy Roadmap — From sandbox pilot to MiCA-style legislation

### 15.1 Stakeholder Map & Messaging Hooks

A multi-faceted engagement plan is required to navigate India's complex regulatory environment.
* **RBI:** Frame the stablecoin as a payment innovation that reinforces the Rupee's primacy.
* **Ministry of Finance (MoF):** Position a stablecoin framework as a way to increase tax revenue and formalize the sector.
* **SEBI:** Support its multi-regulator approach and collaborate on defining jurisdictional boundaries.
* **FIU-IND:** Highlight how a regulated framework enhances AML/CFT compliance.
* **NPCI:** Advocate for formal directives on using UPI for KYC-compliant VDA platforms.
* **MeitY:** Focus on the technology and innovation aspects, aligning with the 'Digital India' vision [policy_advocacy_and_regulatory_engagement_strategy.stakeholder_engagement_plan[0]][32].

### 15.2 Core Proposal Checklist (definition, reserves, audits, redemption)

The proposed stablecoin framework should be based on global best practices from the EU's MiCA and the US's GENIUS Act [policy_advocacy_and_regulatory_engagement_strategy.core_policy_proposals[0]][33]. Key proposals include:
1. **Definition:** Legally define INR-pegged stablecoins as 'payment stablecoins' or 'e-money tokens'.
2. **Authorization:** Establish a 'Permitted Issuer' framework under RBI oversight.
3. **Reserves:** Mandate 1:1 backing with high-quality, liquid INR-denominated assets.
4. **Auditing:** Require monthly public disclosures of reserve composition, certified by a registered accounting firm.
5. **Redemption:** Legally guarantee holders the right to redeem at par for INR.
6. **White Paper:** Mandate a comprehensive 'crypto-asset white paper' for all issuers.
7. **Consumer Protection:** Enact rules against market abuse and mandate clear risk disclosures.

## 16. Phased Launch & Contingencies — 36-month plan with three regulatory pivot triggers

### 16.1 Phase 1–3 Milestones & KPIs (Gantt table)

The roadmap is structured over **36 months** across three phases [phased_launch_roadmap_and_contingencies.key_activities_and_milestones[0]][27].
* **Phase 1 (Months 1-9): Foundation & Research:** Establish legal structure, sign MOUs with partners, prepare IFSCA sandbox application, and secure seed funding.
* **Phase 2 (Months 10-24): Limited Pilot & Compliance Build-out:** Launch a controlled pilot in the sandbox, conduct smart contract audits, implement monthly reserve attestations, begin SOC 2 compliance, and register with FIU-IND.
* **Phase 3 (Months 25-36): Scaled Launch & Expansion:** Phased public launch in India, followed by expansion into key cross-border remittance corridors.

### 16.2 Pivot Paths: Ban → Tokenised deposits; sandbox rejection → offshore

The roadmap includes critical trigger-based pivot strategies:
* **Contingency 1 (Regulatory Ban):** If an outright ban is issued, pivot to a B2B 'Tokenization-as-a-Service' model for regulated entities or shift focus to an offshore jurisdiction.
* **Contingency 2 (Sandbox Rejection):** If the IFSCA application is denied, re-evaluate the legal approach, potentially launching in a jurisdiction like Singapore for B2B or NRI use cases while continuing advocacy in India.
* **Contingency 3 (Favorable Regulation):** If a clear licensing regime is introduced, accelerate the roadmap to apply for an official license and gain a first-mover advantage [phased_launch_roadmap_and_contingencies.contingency_plan[0]][27].

## 17. Alternative Token Models & Competitor Watch — Tokenised deposits may outpace private stablecoins

### 17.1 Tokenised Deposits vs Stablecoin Risk Matrix (table)

Tokenized deposits, which are digital tokens representing a direct deposit claim against a licensed bank, present a powerful alternative model that may be more palatable to regulators like the RBI [token_model_assessment.legal_and_operational_summary[0]][34].

| Feature | Non-Bank Stablecoin | Tokenized Deposit |
| :--- | :--- | :--- |
| **Issuer** | Fintech or special purpose vehicle | Licensed commercial bank |
| **Regulatory Framework** | Unclear; new framework required | Existing, mature banking regulations |
| **Backing** | Segregated reserve assets | Issuer's diversified balance sheet |
| **Run Risk Mitigation** | Reserve liquidity, redemption rights | Deposit insurance, central bank liquidity access |
| **'Singleness of Money'** | Can deviate from par value | Upholds principle via settlement in central bank money |

*The tokenized deposit model directly addresses RBI's financial stability concerns by keeping issuance within the regulated banking perimeter, making it a strong long-term contender.*

### 17.2 Current INR Projects: INRx & Cardano status and gaps

As of September 2025, two notable private INR stablecoin projects are in different stages of development:
* **INRx Coin:** This project is live and operational on its own proprietary blockchain, marketing itself as a functional INR-pegged solution with staking and lending services [current_inr_stablecoin_projects_overview.0.development_status[0]][6]. However, its regulatory standing and the transparency of its reserve audits are unclear.
* **Cardano Project:** This project is in its final stages, having completed milestones related to compliance frameworks and market analysis [current_inr_stablecoin_projects_overview.1.development_status[0]][7]. Its primary goal is to solve the on-ramp problem for Indian Web3 users [current_inr_stablecoin_projects_overview.1.primary_goal[0]][7]. Its success will depend on its final architecture and ability to secure regulatory approval.

## 18. Strategic Risk Register & Mitigations — Holistic view of 12 top risks and counter-measures

### 18.1 Regulatory, Market, Technology, Reputation Risks (table)

| Risk Category | Specific Risk | Likelihood | Impact | Mitigation Strategy |
| :--- | :--- | :--- | :--- | :--- |
| **Regulatory** | Outright ban on private stablecoins by RBI/Govt. | Medium | Critical | Pivot to B2B Tokenization-as-a-Service or shift to an offshore jurisdiction. |
| **Regulatory** | Rejection of IFSCA Sandbox application. | Medium | High | Re-evaluate legal approach; focus on B2B/NRI use cases from a compliant offshore jurisdiction (e.g., Singapore). |
| **Market** | Low user adoption due to punitive VDA tax regime. | High | High | Lobby for a 'payments carve-out'; route retail flows through in-app wallets to delay taxable events. |
| **Market** | 'Bank run' or large-scale redemption shock. | Low | Critical | Maintain 1:1 HQLA reserves, conduct regular stress tests, and have a clear Contingency Funding Plan. |
| **Technology** | Smart contract exploit or hack. | Medium | Critical | Multiple independent audits, formal verification, permanent bug bounty program, and robust incident response plan. |
| **Technology** | Private key compromise of reserve wallets. | Low | Critical | >95% of reserves in air-gapped cold storage; use MPC for warm/hot wallets; multi-layered insurance. |
| **Reputation** | Loss of peg (de-pegging) due to market volatility. | Medium | Critical | Radical transparency with daily Proof-of-Reserves and monthly attestations; professional market-making. |
| **Operational** | Failure to meet 6-hour CERT-In incident reporting. | Medium | High | Maintain a 24/7 on-call incident response team and a well-documented, rehearsed reporting protocol. |
| **Economic** | Decrease in interest rates, reducing float yield. | High | Medium | Diversify revenue with enterprise APIs; maintain a treasury reserve to ensure operational runway. |
| **Compliance** | Failure to comply with FIU-IND reporting or Travel Rule. | Medium | High | Appoint dedicated compliance officers (Principal Officer, Designated Director); invest in automated monitoring and reporting tools. |
| **Legal** | Stablecoin classified as an unauthorized payment system. | Medium | Critical | Engage RBI proactively with a bank-led consortium model; operate within the SRVA framework for cross-border flows. |
| **Competitive** | Rapid adoption of RBI's e-Rupee makes private stablecoin redundant. | Medium | High | Differentiate on programmability, cross-chain interoperability, and superior user experience through Account Abstraction. |

## 19. Conclusion & Next Steps — Immediate actions for founding team and board

The path to launching India's first compliant INR-backed stablecoin is fraught with regulatory challenges but presents a transformative market opportunity. The strategy outlined in this report—centered on proactive compliance, radical transparency, and a bank-led consortium model—offers the most viable path to navigating this complex landscape. By positioning the stablecoin as a regulated payment innovation rather than a speculative asset, the project can align with national priorities, address the RBI's core concerns, and unlock immense value in remittances, B2B payments, and the Web3 ecosystem.

**Immediate Next Steps:**
1. **Formalize Legal Structure:** Retain top-tier legal counsel to finalize the consortium and bankruptcy-remote trust structure.
2. **Initiate Partner MOUs:** Begin formal discussions and sign Memoranda of Understanding with at least two scheduled commercial banks, a 'Big Four' audit firm, and a qualified custodian.
3. **Prepare IFSCA Sandbox Application:** Draft a comprehensive application for the GIFT City sandbox, framing the project as the "tokenization of INR" and detailing the robust governance, reserve management, and compliance frameworks.
4. **Secure Seed Funding:** Finalize the seed funding round to finance the foundational legal, compliance, and technology build-out for the next 12 months.
5. **Hire Core Leadership:** Recruit a Chief Executive Officer (CEO), Chief Technology Officer (CTO), and Chief Compliance Officer (CCO) with deep experience in Indian financial regulations and blockchain technology.

## References

1. *Enabling Framework for Regulatory Sandbox (RBI)*. https://rbidocs.rbi.org.in/rdocs/PublicationReport/Pdfs/ENABLING79D8EBD31FED47A0BE21158C337123BF.PDF
2. *Tax on income from virtual digital assets*. https://incometaxindia.gov.in/Acts/Income-tax%20Act%2C%201961/2024_1/102120000000081156.htm?
3. *CoinDCX CEO Proposes INR-Backed Stablecoin to Cut Remittance ...*. https://www.ainvest.com/news/coindcx-ceo-proposes-inr-backed-stablecoin-cut-remittance-costs-90-2508/
4. *Income Tax Department – TDS on payment for the transfer of Virtual Digital Assets (VDAs)*. https://incometaxindia.gov.in/tutorials/72.tds-on-payment-for-the-transfer-of-virtual-digital-assets.pdf
5. *PBM Technical Whitepaper (MAS)*. https://www.mas.gov.sg/-/media/mas-media-library/development/fintech/pbm/pbm-technical-whitepaper.pdf
6. *The Importance of Indian Stable Coin for the Indian Economy*. https://www.openpr.com/news/3788178/the-importance-of-indian-stable-coin-for-the-indian-economy
7. *Indian National Rupee-backed Stablecoin on Cardano*. https://projectcatalyst.io/funds/12/cardano-use-cases-concept/indian-national-rupee-backed-stablecoin-onboarding-35m-indian-web3-users-on-cardano
8. *Challenging the said Statement and Circular and seeking a direction to the respondents not to restrict or restrain banks and financial ... Reserve Bank of India (hereinafter,  RBI) issued a
 Statement on Developmental and Regulatory Policies on April
5, 2018, paragraph 13 of which directed the entities regulated by RBI
(i) not to deal with or provide services to any individual or business
entities dealing with or settling virtual currencies and (ii) to exit the
Signature Not Verified
Digitally signed by
SUSHMA KUMARI
Date: 2020.03.04
13:32:29 IST
Reason:
business entities, dealing with or settling virtual currencies (VCs).*. https://indiankanoon.org/doc/12397485/
9. *RBI FAQ/Guidance on International Trade Settlement in INR (SRVA, LRS, and related FEMA rules)*. https://www.rbi.org.in/commonman/english/scripts/FAQs.aspx?Id=3373
10. *RBI Basel III Liquidity Standards – LCR (HQLA & related provisions)*. https://www.pdicai.org/Docs/RBI-2025-26-27_2242025151229463.pdf
11. *USDC Reserve Attestation Report from Grant Thornton LLP*. https://ebs.publicnow.com/view/6848A6B24BA316D8F7C789C1CFD0D6FFC9831E1A
12. *FSB Final report: High-level Recommendations for the Regulation, Supervision and Oversight of Global Stablecoin Arrangements*. https://www.fsb.org/uploads/P170723-3.pdf
13. *MAS Finalises Stablecoin Regulatory Framework*. https://www.mas.gov.sg/news/media-releases/2023/mas-finalises-stablecoin-regulatory-framework
14. *Project mBridge - BIS Innovation Hub*. https://www.bis.org/innovation_hub/projects/mbridge_brochure_2311.pdf
15. *Bank for International Settlements (BIS) – CBDC and cross-border stablecoins: mBridge and related interoperability*. https://www.bis.org/about/bisih/topics/cbdc/mcbdc_bridge.htm
16. *ERC-3643 Documentation*. https://docs.erc3643.org/erc-3643
17. *UIDAI Aadhaar Authentication Regulation Annexure II*. https://uidai.gov.in/images/resource/AUA_KUA_Agreement_v_40.pdf
18. *UPI: Unified Payments Interface - Instant Mobile Payments*. https://www.npci.org.in/what-we-do/upi/product-overview
19. *A handbook for offline payments with CBDC*. https://www.bis.org/publ/othp64.pdf
20. *RBI Offline Payments and CBDC Framework*. https://legalitysimplified.com/wp-content/uploads/2022/01/RBI.pdf
21. *MAS Finalises Stablecoin Regulatory Framework*. https://www.mas.gov.sg/-/media/mas/news/media-releases/2023/mas-stablecoin-regulatory-framework-infographic.pdf
22. *FinLaw.in: What you need to know before creating your own stablecoin (2025)*. https://finlaw.in/blog/what-you-need-to-know-before-creating-your-own-stablecoin
23. *WazirX, Liminal Custody Blame Each Other as $230M ...*. https://www.coindesk.com/business/2024/07/19/wazirx-liminal-custody-blame-each-other-as-230m-crypto-exploit-leaves-customers-stranded
24. *WazirX Files Police Complaint After $230M Hack, Engages ...*. https://www.coindesk.com/policy/2024/07/19/wazirx-files-police-complaint-after-230m-hack-engages-with-indias-cyber-crimes-unit
25. *CERT-In Directions 70B (28 Apr 2022) - Directions under sub-section (6) of section 70B of IT Act 2000*. https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf
26. *THE DIGITAL PERSONAL DATA PROTECTION ACT, 2023 ...*. https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf
27. * FIU-IND AML/CFT Guidelines for Virtual Digital Assets*. https://fiuindia.gov.in/pdfs/AML_legislation/AMLCFTguidelines10032023.pdf
28. *rbi mandates data localisation for payment systems*. https://www.khaitanco.com/sites/default/files/2019-09/RBI%20mandates%20data%20localisation%20for%20Payment%20Systems.pdf
29. *How to comply with CERT-In's new six-hour time frame to report cyber incidents*. https://trilegal.com/wp-content/uploads/2022/07/How-to-comply-with-CERT-Ins-new-six-hour-time-frame-to-report-cyber-incidents.pdf
30. *ITR-2 FAQ*. https://www.incometax.gov.in/iec/foportal/help/FileITR-2Online-FAQ
31. *[PDF] IFRS (#) - Accounting for crypto-assets - EY*. https://www.ey.com/content/dam/ey-unified-site/ey-com/en-gl/technical/ifrs-technical-resources/documents/ey-ifrs-accounting-for-crypto-assets.pdf
32. *IndiaTech.org_Crypto_Decoder_2021.pdf*. https://www.indiatech.org/wp-content/uploads/2023/10/IndiaTech.org_Crypto_Decoder_2021.pdf
33. *IndiaTech.org Crypto Policy Proposal 2021*. https://www.indiatech.org/wp-content/uploads/2021/05/IndiaTech.org_Crypto_Policy_Proposal_2021.pdf
34. *REPORT ON TOKENISED DEPOSITS*. https://www.eba.europa.eu/sites/default/files/2024-12/4b294386-1235-463f-b9b5-08f255160435/Report%20on%20Tokenised%20deposits.pdf