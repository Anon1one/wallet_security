## Advanced Cryptocurrency Custody: The Risks and Rewards of Self-Rolled Wallet Solutions

### Understanding Self-Rolled Tools
Self-rolled tools refer to the practice of creating your own custom solutions for managing critical aspects of your cryptocurrency security. This can involve developing your own private key management systems, custom key handlers, and even proprietary cryptography functions.

**A Stern Warning**: do not attempt this unless you possess an exceptionally deep understanding of cryptographic principles, security best practices, and the intricate workings of blockchain technology. The potential for error is immense, and such mistakes frequently result in the permanent loss of assets.

The primary motivation behind adopting self-rolled tools often stems from a deep-seated (and sometimes justifiable) lack of trust in existing third-party solutions. Every other wallet option—be it hardware wallets, browser extensions, or mobile apps—comes with its own set of inherent issues, dependencies, or verification requirements. For some, these compromises are unacceptable.

### Exploring Alternative Self-Tool Implementations
Beyond developing complex software, "self-tooling" can also manifest in simpler, albeit still risky, forms:

* **Brain Wallet**: This method involves committing a private key or seed phrase entirely to memory, with no physical or digital backup. The security relies solely on the user's ability to recall the information perfectly.

* **Paper Wallet**: A user meticulously writes down their private key on a piece of paper. This single physical copy is then stored in a highly secure location, such as a safe deposit box. The integrity of the funds depends entirely on the security and preservation of this one document.

* **Self-encryption Tools**: This involves a user creating their own encryption utilities or custom password managers. These bespoke tools are then used to encrypt private keys or to authorize transactions, adding a personalized layer of security before interacting with the blockchain.

### Case Study: An Advanced Self-Tool Setup for High-Stakes Scenarios

To illustrate the extent to which individuals might go when employing self-tools, especially when substantial wealth is involved, consider this real-world example based on an acquaintance operating under a specific threat model:

* **Distributed Holdings**: Hundreds of individual wallets were created, each holding relatively small amounts of cryptocurrency to minimize the impact of any single wallet compromise.

* **Redundant Backups**: Multiple backups of critical information were maintained, physically stored in geographically distinct, secure locations.

* **Tiered Storage**: Approximately ten "main" wallets were designated to hold the majority of the funds, likely with even more stringent security measures.

* **Zero Trust in Standard Solutions**: This individual explicitly avoided all standard hardware or browser wallets, relying entirely on their custom-built systems.

* **Proprietary Key Generation**: Secret phrases and private keys were generated using tools developed in-house.

* **Layered Encryption**: Each private key was individually encrypted using their custom methods.

* **Secure Physical Storage**: The encrypted keys were then stored in a secret, custom-built database, which itself was kept on a select few air-gapped hard drives.

* **Pseudo Social Recovery Mechanism**: These hard drives were entrusted to trusted individuals who were unaware of the contents or how to decrypt them. This introduced a form of social recovery, where access required cooperation, but knowledge remained siloed.

* **Regular Rotation**: Crucially, every six months, all funds were systematically rotated to entirely new wallets, invalidating old keys and further complicating any potential attack.

This elaborate setup highlights the dedication and complexity that can be involved when one decides to take full, personal responsibility for every aspect of their digital asset security.

### Weighing the Pros and Cons of Self-Tools
The decision to use self-rolled tools comes with a distinct set of advantages and significant disadvantages.

* Pros:

   * **No External Trust Required**: The most compelling advantage is the elimination of reliance on third-party developers, manufacturers, or service providers. You are trusting only yourself and your own creations.

* Cons:

   * **Extremely Time-Consuming and Complex**: Designing, implementing, and maintaining self-rolled solutions requires a substantial investment of time and effort. The ongoing management can also be incredibly demanding.

   * **Requires Profound Expertise**: This path is exclusively for users with advanced, expert-level knowledge of computer science, cryptography, and operational security. A superficial understanding is insufficient and dangerous.

### Critical Considerations and Best Practices
If, despite the warnings, you are contemplating this advanced path, consider these non-negotiable points:

* **Extreme Caution is Paramount**: We reiterate: "Don't do this unless you really absolutely know what you're doing because you can screw this up a lot." The margin for error is virtually non-existent.

* **Seek Expert Consultation**: If you are developing a novel approach or implementing complex self-tools, it is highly recommended—if not mandatory—to have your entire setup rigorously audited by independent, reputable security experts. They can identify potential flaws or critical errors you might have overlooked.

* **Acknowledge Imperfection**: It's vital to recognize that "each of the options above have issues. One way or another, there is no perfect solution." This applies to all cryptocurrency storage methods, including self-tools. The drive to create one's own solution often arises from dissatisfaction with the compromises inherent in other available options, but self-tools introduce their own unique set of challenges and risks.

In summary, creating and using your own wallet solutions represents the apex of personal responsibility in cryptocurrency management. It offers unparalleled control but demands exceptional expertise, meticulous diligence, and a constant awareness of the severe risks involved. This approach is not a shortcut to security; it is a highly specialized discipline.

## Mastering Private Key Hygiene: Your Guide to Secure Web3 Wallet Management

1. **Practice Discretion Regarding Your Crypto Wealth**
**Question**: Should I tell people how much cryptocurrency I own?
**Answer**: A resounding **No**.

**Reasoning**: Publicly disclosing the extent of your crypto holdings can make you a target. Attackers often select their victims based on perceived wealth. The less information an attacker has about the value of assets you control, the lower your risk profile.

**Key Action - Avoid Doxxing**: Refrain from publicly linking your real-world identity to crypto addresses that hold significant funds. For instance, avoid placing an ENS name like yourname.eth in your public Twitter bio if that address manages substantial assets. Maintaining a low profile is a cornerstone of personal operational security (OpSec).

2. **Sourcing Hardware Wallets: Trust is Non-Negotiable**
**Question**: Should I accept or use a hardware wallet obtained from a hackathon or an untrusted third party?
**Answer**: Absolutely **not**.

**Reasoning**: Hardware wallets sourced from events, hackathons, or any unverified third-party channel carry a significant risk of compromise. These devices could be tampered with, pre-seeded with known private keys, or contain malicious firmware designed to steal your assets.

**Crucial Tip**: Always purchase hardware wallets **directly from the official vendor/company** (e.g., Ledger, Trezor) or from **verified official resellers**. Before purchasing from a reseller, meticulously double-check that they are genuinely authorized by the manufacturer. This diligence is critical to ensure you receive an authentic, untampered device.

3. **Long-Term Private Key Use and Regular Security Reviews**
**Question**: Is it safe to use the same private key for many years?
**Answer**: While technically possible, it's **highly recommended to rotate your keys and wallets periodically.**

**Enhanced Security with Multisig Wallets**: Solutions like multisignature wallets (e.g., Safe, formerly Gnosis Safe) offer a robust approach. They allow you to maintain a consistent public wallet address while enabling the underlying signer keys to be changed or updated. This enhances security by allowing key rotation without changing your primary on-chain identity and facilitates better recovery options.

**Recommendation: Implement Regular Security Reviews**:
It's advisable to conduct a thorough security review of your key management practices every 6 months, or more frequently based on your specific security needs and transaction volume. During this review, ask yourself critical questions:

* **Where are all my private keys and seed phrases stored?** (Be specific about physical and digital locations.)

* **Which keys control which funds?** (Maintain an inventory.)

* **What is my disaster recovery plan?** Consider scenarios like your house burning down, along with your primary computer and phone. Can you still securely recover your crypto assets?

**Actionable Exercise**: Set a recurring event in your calendar (e.g., every 6 months for 3-4 hours) dedicated to this security review. Use this time to assess your key storage, verify backup integrity, and identify potential exposure points.

4. **Securely Backing Up Your Secret Phrase or Private Key**
**Core Principle**: Your secret phrase (also known as a seed phrase or mnemonic phrase) or raw private key must be backed up in a highly secure, secret location that only you (or a trusted, planned process) can access.

**Effective Backup Methods (Examples):**

* **Metal Plates:** Stamp your seed phrase onto durable metal plates and store them securely (e.g., hidden, in a fireproof safe).

* **Commit to Memory**: While some attempt this, it is generally high-risk and not solely recommended due to human fallibility. If used, it should be part of a multi-layered strategy.

* **Piece of Paper**: Write it down and store it in an extremely secure, secret location (e.g., a high-quality safe, a bank deposit box). Consider distributing parts among trusted parties if using a scheme like Shamir's Secret Sharing (SSS), but this adds complexity.

* **Encrypted Storage:** Store it in an encrypted format within a reputable password manager (see further discussion below regarding significant risks and best practices).

* **Physical Vault**: Utilize a dedicated physical vault for maximum security.

The primary goal is to make unauthorized access exceedingly difficult while ensuring you can recover your assets when needed. Be creative in your methods, but always prioritize robustness and recoverability.

5. **Critical "DON'Ts" for Private Key and Secret Phrase Handling**
There are certain actions you must **NEVER** take with your private keys or secret phrases:

* **Never take a photo of it**: Digital images on phones or computers are highly vulnerable to malware and hacking.

* **Never upload it to the cloud (unencrypted)**: Do not store it in services like Google Drive, iCloud, Dropbox, or similar, especially in an unencrypted or easily decryptable form.

* **Never text it**: Text messages are not secure.

* **Never email it**: Email is inherently insecure for such sensitive data.

* **Never give it to anyone you don't absolutely trust with all your funds**: Your private key is your money.

6. **Operating System (OS) Security Considerations**
**Question**: Does my choice of operating system matter for crypto security?
**Answer**: Yes, it significantly matters.

**Recommendation**: Avoid using standard PC/Windows installations for storing private keys or interacting with substantial amounts of cryptocurrency if possible.

**Reasoning**: Windows, being a widely used OS, is a frequent target for malware, viruses, and phishing attacks. Its default security permissions might also be less intuitive for establishing a highly secure, hardened environment suitable for managing valuable crypto assets compared to more specialized or security-focused OS setups (e.g., a dedicated Linux environment, or using an air-gapped machine).

### The Most Important Action: Responding to Key Compromise
If, for even a single second, you suspect your private key has been:

* Lost.

* Exposed on your screen (e.g., accidentally during a live stream, screen share, or due to malware).

* Potentially accessible by an unauthorized party (e.g., you suspect malware on your device, or an untrusted individual had physical or remote access to where it's stored).

**Immediate Action: Consider that private key completely and irrevocably compromised.**

1. **Immediately begin moving all funds** controlled by that compromised key to a brand new, securely generated wallet (with a new private key that has never been exposed).

2. If the compromised key is a signer on a multisig wallet, initiate the process to replace that signer key with a new, secure one as quickly as possible.

Time is of the essence in such scenarios.

### Extended Discussion: Private Keys and Password Managers – A Critical Warning
Storing raw private keys or seed phrases directly in password managers, particularly cloud-synchronized ones, introduces significant risks. This concern was highlighted by security researchers following major breaches.

**Reference Case**: An article from `krebsonsecurity.com` ("Experts Fear Crooks are Cracking Keys Stolen in LastPass Breach," September 5, 2023) detailed significant concerns following the LastPass breach in November 2022. Attackers reportedly exfiltrated user password vaults. For some users, these vaults contained not only encrypted password data but also plaintext data, which unfortunately included crypto private keys and seed phrases.

Security researcher Taylor Monahan (formerly Product Manager at MetaMask) and others identified substantial cryptocurrency thefts (reports indicated over $35 million from more than 150 individuals) linked to this breach, where users had stored their sensitive crypto credentials within LastPass.

**Strong Recommendation for Password Manager Use:**

* **Ideally, do NOT store your raw private keys or seed phrases directly in any password manager**. This is especially true for cloud-synchronized services.

* **If you absolutely** *must* **use a password manager for key material (a practice highly discouraged for raw keys)**: The key material should be **robustly encrypted** *before* **it is placed into the password manager**. The password manager itself should not have access to the unencrypted key. What you would store in the password manager is an encrypted blob of data, requiring a separate, strong decryption password and process known only to you.

**Adopt a "What If" Security Mindset**: Always operate under the assumption that any third-party service you use (be it a password manager or cloud storage) could be breached. Evaluate who you are entrusting with your most sensitive data and implement layers of security to mitigate potential fallout.

For those looking to delve deeper into wallet security evaluations, consider exploring resources like Wallet Scrutiny (`walletscrutiny.com`). While Wallet Scrutiny primarily reviews Bitcoin hardware and software wallets for security, transparency, and reproducibility (verifying that compiled binaries match their purported open-source code), their methodologies and critical thinking are highly valuable. The principles they apply to assess wallet integrity can be adapted by users when evaluating the security posture of any cryptocurrency wallet, including EVM-compatible smart contract wallets. Continuous learning and vigilance are key to navigating the Web3 landscape securely.

### How to Securely Verify Safe{Wallet} Transactions with UI Tools

When interacting with decentralized applications (dApps), the most critical security principle is to never blindly trust the user interface (UI). A dApp's front-end can be compromised in a "what you see is not what you get" attack, showing you a safe transaction while asking you to sign a malicious one that could drain your funds. The true source of information is always your wallet's confirmation screen—be it MetaMask, Rabby, or a hardware wallet.

Using UI-based tools to verify what you are signing before approving a transaction with your Safe{Wallet} (formerly Gnosis Safe). While command-line tools offer the lowest attack surface, the methods here are essential for anyone who needs to verify transactions without a local development environment.

### Signing vs. Executing: The Safe{Wallet} Two-Step Process
Understanding the Safe{Wallet} workflow is key to proper verification. Unlike a standard wallet transaction, a Safe{Wallet} action involves two distinct steps:

1. **Signing**: When an owner approves a transaction, they are not sending it to the blockchain. Instead, they sign a structured off-chain message (an EIP-712 digest) that represents the transaction's details. This signature is stored by Safe until the required threshold of owners have signed.

2. **Executing**: Once the minimum number of owners have signed, a final on-chain transaction is sent. This transaction calls the `execTransaction` function on the Safe contract, bundling the original transaction data with all the collected signatures to execute the action.

You must verify the data at both stages—when you sign and when you (or another owner) execute.

#### Part 1: Verifying the Initial Signature Request

Let's walk through the process of verifying an `approve` transaction initiated from the Safe{Wallet} web app. In this example, we will approve a spender to use 10 WETH.

##### Step 1: Decode the Transaction Data
After creating the transaction in the Safe UI and clicking "Sign," your wallet will pop up with a "Signature request." This is your first and most important verification checkpoint. The structured data presented here is what you are actually being asked to approve.

First, focus on the `to` address and the `data` payload.

1. **Verify the** `to` **Address**: This is the contract you are interacting with.

   * Copy the `to` address from your wallet's signature request pop-up.

   * Paste this address into a trusted block explorer (e.g., Etherscan, Sepolia Etherscan for testnets).

   * Confirm that the address belongs to the correct contract you intend to interact with (e.g., the official WETH9 contract).

2. **Decode the Calldata**: The `data` field contains the function call and its parameters in a hexadecimal format. You need a tool to decode this.

   * Copy the long hexadecimal string from the `data` field in your wallet. For our `approve` example, it might look like this:
```bash
0x095ea7b30000000000000000000000003da8ebe8d7bd3eea12425adff745847fab9662e600000000000000000000000000000000000000000000000000000000100000000
```
   * Navigate to a trusted ABI decoder tool, such as those found on **tools.cyfrin.io** or **swiss-knife.xyz**.

   * Paste the data into the decoder. The tool will parse it into a human-readable format.

       * **Function**: `approve(address spender, uint256 amount)`

       * **param0 (spender)**: `0x3dA8EBe8d7bD3EEA12425adff745847FAB9662E6`

       * **param1 (amount)**: `10000000000`

    * Now, verify that the decoded function, spender address, and amount are exactly what you expect. If anything is different from your intention, reject the signature immediately.

#### Step 2: Verifying Hashes on a Hardware Wallet
Hardware wallets add a crucial layer of security, but they often can't display fully decoded transaction data on their small screens. Instead, they show you a hash of the transaction data, which you must verify independently.

1. **Use a Safe Hash Calculator**: Navigate to a tool like the **Safe Wallet Hash Calculator** on `tools.cyfrin.io` or the one on `safeutils.openzeppelin.com`.

2. **Input All Transaction Parameters**: Carefully copy every parameter from your wallet's signature request pop-up and paste it into the calculator fields. This includes:

    * Safe Address

    * The correct Chain ID (e.g., 1 for Mainnet, 11155111 for Sepolia)

    * Nonce (the Safe's nonce, not your EOA's)

    * To Address (the target contract, e.g., WETH)

    * Value (usually 0 for interactions like `approve`)

    * Data (the long hexadecimal string you decoded earlier)
 
    * Operation (`Call` or `0`)

    * All gas-related parameters (`safeTxGas`, `baseGas`, `gasPrice`, `gasToken`, `refundReceiver`). For a simple signature request, these are typically 0 or a zero address. This "zero check" is an important sanity check.

3. **Calculate and Compare Hashes**: The tool will generate a final **Safe Transaction Hash**. This is the exact hash that should be displayed on your hardware wallet's screen. Compare the hash on the tool's website with the hash on your physical device. If they match character for character, you can safely sign the transaction.

#### Part 2: Verifying the Final Execution Transaction
After enough owners have signed, the transaction is ready to be executed on-chain. This is a separate on-chain transaction that also requires verification.

1. **Initiate Execution**: In the Safe UI, click "Execute." Your wallet will now open with a standard transaction request (not a signature request).

2. **Verify the `execTransaction` Call**: This transaction is being sent to your Safe contract address. The data payload for this call contains all the original transaction details (to, value, data, operation) plus the collected signatures.

3. **Decode the Execution Calldata:**

    * In your wallet's confirmation screen, go to the `data` or `hex` tab.

    * Copy the new, even longer hexadecimal string.

    * Paste this string into your ABI decoder tool.
     
The tool will decode the outer function call, which should be `execTransaction`. More importantly, it will show you all the nested parameters of this function. You can once again review the `to` address, `value`, and `data` of the original transaction being executed to ensure nothing has changed. If all the nested details match your original intent, it is safe to execute the transaction on-chain.

## Secure Your Assets: Mastering Safe Multisig Transaction Verification

### The Lurking Threat: Why Blindly Signing Safe Transactions is Dangerous

Safe multisigs offer enhanced security by requiring M-of-N signatures, distributing trust and control. However, this security model is fundamentally undermined if signers approve transactions without truly understanding or independently verifying what they are authorizing. The core problem we address is the risk of signing malicious transactions presented by a compromised user interface (UI) or Application Programming Interface (API).

If the Safe web application (app.safe.global) or even an intermediary wallet like Metamask is compromised, it could display legitimate-looking transaction details while tricking your wallet into signing a malicious payload. This could lead to a complete drain of your multisig's funds. The hardware wallet, with its isolated environment and trusted display, becomes your last line of defense against such attacks.

### Your Hardware Wallet: The Unshakeable Foundation of Multisig Security
Your hardware wallet is your ultimate source of truth. What is displayed on its screen – be it a transaction hash or decoded transaction data – is what you must diligently verify. Any discrepancy between what the Safe UI shows and what your hardware wallet presents is a major red flag. We aim to minimize dependencies; relying solely on the hardware wallet's display, cross-referenced with independently generated data, is key.

### Introducing `safe-tx-hashes`: Your Independent Verification Co-Pilot
To aid in this verification process, you can use `safe-tx-hashes`, a command-line tool. This script, available as a fork maintained by Cyfrin (`https://github.com/Cyfrin/safe-tx-hashes`), allows you to independently compute the expected transaction hashes and call data that should be displayed on your hardware wallet. The Cyfrin version is an enhancement of the original `safe-tx-hashes-util` created by Pascal (pcaversaccio) (`https://github.com/pcaversaccio/safe-tx-hashes-util`).

This tool helps you confirm that the transaction details you intend to sign match what your hardware wallet is being asked to authorize, bypassing potentially compromised UIs.

#### Getting Started: Installing and Verifying safe-tx-hashes
You can install the `safe-tx-hashes` tool using the following command:

```bash
curl -L https://raw.githubusercontent.com/Cyfrin/safe-tx-hashes/main/install.sh | bash
```

**A note on security**: Piping curl directly to bash executes remote code on your system. While convenient, this carries inherent risks. For maximum security, you should review the `install.sh` script's contents before execution or consider building the tool from its source code if you have security concerns.

Once installed, verify the installation and explore its options:

```bash
safe_hashes -v       # Displays the installed version
safe_hashes --help   # Shows the help menu with available commands and flags
```

### Decoding the Process: Key Concepts in Safe Transaction Verification
Before diving into the practical steps, let's clarify some key concepts:

1. **Signature Verification (EIP-712) vs. Transaction Execution Verification**:

     * **Signature Verification (EIP-712)**: When you sign a Safe multisig transaction before it has enough signatures to be executed on-chain, you are signing a structured message compliant with the EIP-712 standard. Your hardware wallet should display a hash of this EIP-712 message. This is the first hash you need to verify.

     * **Transaction Execution Verification**: Once a multisig transaction has accumulated the required number of signatures (M-of-N) and is ready to be executed, the final step is to submit an actual Ethereum transaction. This transaction calls the `execTransaction` function on the Safe contract. At this stage, your hardware wallet will display the call data for this `execTransaction` call. This data also requires careful verification.

2. **Trust Assumptions Revisited**:

     * **Hardware Wallet**: Your ultimate source of truth.

     * `safe-tx-hashes tool`: Your independent verifier. It computes what should be on your hardware wallet.

     * **Safe UI/API** (`app.safe.global`): A convenient interface but considered potentially compromisable. Data presented here must be cross-verified.

     * **Metamask (if used with a hardware wallet)**: If your hardware wallet connects to Safe via Metamask (e.g., some Ledger setups), Metamask becomes an additional trusted layer. Direct hardware wallet integration with Safe (like with Keystone) is preferable, but if using Metamask, be extra vigilant and rely on the hardware wallet's clear signing capabilities.

3. **Initialized vs. Uninitialized Transactions**:

     * **Uninitialized Transaction**: A transaction proposal created in the Safe UI that has not yet received any signatures, or not enough to meet the threshold. It primarily exists within the Safe backend/API. Its integrity isn't guaranteed until verified by a signer.

     * **Initialized Transaction**: A transaction that has received at least one valid signature and is stored by the Safe API. This makes it easier for subsequent signers to retrieve its details.

4. **Clear Signing**:
This refers to a hardware wallet's ability to decode and clearly display the human-readable details of a transaction (e.g., function name, parameters like recipient addresses and amounts) rather than just showing a raw hexadecimal data blob or a cryptographic hash. Wallets like Keystone are praised for their robust clear signing capabilities, significantly enhancing security by making it easier to spot malicious parameters.

### Step-by-Step: Verifying Signatures for Uninitialized Safe Transactions
An "uninitialized" transaction is one that hasn't been signed by anyone yet, or exists only in your local Safe UI proposal. The Safe API might not be aware of it, or if it is, its details could potentially be manipulated if the API or UI is compromised.

#### Method 1: Using the Safe API (with the `--untrusted` flag)

If you've created a transaction in the Safe UI (`app.safe.global`) and it's the first signature, you can use safe_hashes to fetch its details from the Safe API. The `--untrusted` flag signifies that while we're fetching data from the API, we don't fully trust it and will rely on our hardware wallet for the final say.

The command structure is:
```bash
safe_hashes --address <YOUR_SAFE_ADDRESS> --network <NETWORK_NAME> --nonce <NONCE_FROM_SAFE_UI> --untrusted
```
* `<YOUR_SAFE_ADDRESS>`: The address of your Safe multisig wallet.

* `<NETWORK_NAME>`: The network (e.g., `ethereum`, `polygon`, `arbitrum`).

* `<NONCE_FROM_SAFE_UI>`: The nonce for this specific transaction, visible in the Safe UI.

**Example**: Let's say you're approving USDC for the Uniswap V2 Router. You'd find the nonce in the Safe UI.

1. Identify the target contract (e.g., USDC token contract: 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 on Ethereum).

2. Identify the spender (e.g., Uniswap V2 Router: 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D on Ethereum).

3. Create the transaction in the Safe UI. Note the nonce.

3. Run `safe_hashes` with `--untrusted`.

The tool will output several pieces of information, most importantly the `Safe transaction hash (EIP-712)`. **This is the hash you must compare with the hash displayed on your hardware wallet when you initiate the signing process**. If they match, you can be confident you're signing the intended EIP-712 message.

#### Method 2: Manual/Offline Verification (Maximum Security)

For ultimate security, especially with uninitialized transactions or if you suspect the Safe API might be compromised, you can provide all transaction details manually to `safe_hashes` without it needing to contact any external API.

To do this, you first need the raw call data for the transaction your Safe will execute. For an ERC20 approve, you can generate this using a tool like Foundry's `cast`:

```bash
cast calldata "approve(address,uint256)" <SPENDER_ADDRESS> <VALUE_IN_WEI>
```
For example:

```bash
cast calldata "approve(address,uint256)" 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D 1000000000000000000
```

This will output a hex string (e.g., `0x095ea7b30000000000000000000000007a250d5630b4cf539739df2c5dacb4c659f2488d0000000000000000000000000000000000000000000000000de0b6b3a7640000`).

Then, use `safe_hashes` with the `--offline` flag:

```bash
safe_hashes --address <YOUR_SAFE_ADDRESS> --network <NETWORK_NAME> --nonce <NONCE_FROM_SAFE_UI> --data <RAW_CALL_DATA_FROM_CAST> --offline --to <TARGET_CONTRACT_ADDRESS> --value <ETH_VALUE_IF_ANY_USUALLY_0>
```

   * `--data`: The raw call data generated by `cast` (or similar tool).

   * `--offline`: Instructs the script not to make any external API calls.

   * `--to`: The address of the contract the Safe will interact with (e.g., the USDC token contract address for an approve call).

   * `--value`: The amount of native currency (e.g., ETH) being sent with the transaction. For token approvals or most contract interactions, this is typically `0`.

Again, compare the output `Safe transaction hash (EIP-712)` with what your hardware wallet displays. This method minimizes trust assumptions to just your hardware wallet and the locally run safe_hashes script.

### Verifying Signatures for Initialized Safe Transactions
If a transaction has already been proposed and signed by at least one other party, it's considered "initialized" and its details are stored by the Safe API. In this scenario, you typically don't need the `--untrusted` flag because the API is expected to serve the correct, already partially signed transaction data.

The command is simpler:

```bash
safe_hashes --address <YOUR_SAFE_ADDRESS> --network <NETWORK_NAME> --nonce <NONCE_FROM_SAFE_UI>
```
The script will fetch the transaction details from the Safe API based on the address and nonce. As always, compare the `Safe transaction hash (EIP-712)` from the tool's output with the hash shown on your hardware wallet screen before signing.

#### Hardware Wallet Display Nuances:
Be aware that different hardware wallets might display EIP-712 hashes differently. For instance:

* **Trezor**: Typically shows the hexadecimal representation of the hash.

* **Ledger Nano X/S**: May show a "binary string literal" representation.
The `safe_hashes` tool conveniently outputs the hash in multiple formats (including `Transaction hash (HexEncoded)` and `Transaction hash (binary string literal)`) to facilitate comparison with various hardware wallets.

### The Final Checkpoint: Verifying Safe Transaction Execution Data

Once a Safe transaction has received the required M-of-N signatures, it's ready for execution on the blockchain. This involves one of the signers (or a third party) submitting an Ethereum transaction that calls the execTransaction function on the Safe contract itself.

It's crucial to verify the call data of this `execTransaction` call on your hardware wallet. This call data encapsulates all the details of the multisig transaction being executed (the `to` address, `value`, `data`, `operation`, etc.).

To generate the expected `execTransaction` call data using `safe_hashes`, use the `--print-mst-calldata` (print multisig transaction call data) flag:

```bash
safe_hashes --address <YOUR_SAFE_ADDRESS> --network <NETWORK_NAME> --nonce <NONCE_FROM_SAFE_UI> --print-mst-calldata
```

This command will fetch (or reconstruct, if using offline parameters) the transaction details and then compute the full call data for the `execTransaction` call that your wallet will sign and send to the Safe contract.

When you click "Execute" in the Safe UI (or your chosen interface) and your hardware wallet prompts for confirmation, it should display this call data.

   * **For wallets with clear signing (e.g., Keystone)**: You should see decoded parameters like the target contract (to), the function selector of the internal call, and any amounts or addresses involved.

   * **For wallets without robust clear signing**: You might see a long hexadecimal string representing the raw call data.

**Compare this displayed data (whether decoded or raw) meticulously with the output from** **safe_hashes --print-mst-calldata**. At a minimum, verify:

1. The `to` **address** (should be your Safe contract address).

2. The **function selector** (should be for `execTransaction`).

3. The **parameters within the call data**, especially the internal `to` address (the contract the Safe is interacting with, e.g., USDC), the *internal* `value` (amount of tokens), and the *internal* `data` (the call to `approve`, `transfer`, etc.).

### Essential Security Hygiene for Safe Multisig Users
   * **Practice Makes Perfect**: Regularly practice these verification steps in a test environment before handling significant assets.

   * **Separate Signing and Execution**: A crucial security tip is to never sign and execute a multisig transaction in a single step if your wallet interface offers this. Always sign first, allowing for EIP-712 hash verification. Then, separately, initiate the execution step, allowing for execTransaction call data verification. Combining these steps can sometimes lead to wallets skipping the display of the EIP-712 hash.

   * **Team Knowledge**: Ensure that multiple members of your team understand this verification process deeply. Don't rely on a single individual.

   * **Hardware Wallet is Key**: Reiterate that the hardware wallet's display is your ground truth. If using Metamask as an intermediary for your hardware wallet, remember it adds another layer of trust. However, good hardware wallets with clear signing capabilities will still display the full transaction details on the device itself, mitigating much of this added risk.

   * **Vigilance with Uninitialized Transactions**: Be extra cautious with uninitialized transactions. The --offline method for safe_hashes offers the highest level of assurance for verifying the EIP-712 hash as it doesn't rely on any external API for the transaction data.

   * **Stay Updated**: Keep your hardware wallet firmware, wallet software (like Metamask), and the safe_hashes tool updated to benefit from the latest security patches and features.

## Case Study: Unpacking the $1.4 Billion Bybit Hack

The cryptocurrency exchange Bybit recently suffered a significant security breach, resulting in losses of approximately $1.4 billion. This incident highlights critical vulnerabilities not in the core smart contracts of widely used wallet solutions, but in the operational security practices surrounding their use. Bybit's CEO, Ben Zhou, explained that the exploit occurred during what was believed to be a "regular cold wallet transfer." Bybit utilizes Safe (formerly Gnosis Safe, accessible via `safe.global`), a popular smart contract wallet solution, for its multisig cold storage. Mr. Zhou, acting as the final of three required signers for their 3-of-6 multisig setup, stated he believed he was authorizing a standard transaction. He reported checking the URL (`safe.global`) and the destination address on the user interface (UI), which appeared correct. However, he crucially admitted he "didn't check fully" the transaction details displayed on his Ledger hardware wallet. This oversight proved catastrophic, as an emergency call about the exploit came just thirty minutes after he signed the transaction. This lesson will dissect the technical mechanisms behind this sophisticated attack.

### The Core Exploit: Manipulating `execTransaction` via `delegatecall`
The attackers orchestrated this heist by crafting a malicious `execTransaction` call to Bybit's Safe multisig proxy contract. The Safe architecture relies on a central function, `execTransaction`, to dispatch approved transactions.

The key to this exploit lay in the `operation` parameter of the `execTransaction` call. This parameter dictates how the multisig proxy interacts with the target contract. An `operation` type of `0` signifies a standard `CALL` opcode, while an `operation` type of `1` signifies a `DELEGATECALL`. The attackers used `operation: 1`.

A `DELEGATECALL` is a powerful and potentially dangerous Ethereum Virtual Machine (EVM) opcode. When a contract (the proxy) `DELEGATECALLs` another contract (the implementation or, in this case, a malicious contract), the called contract's code executes *within the context of the calling contract*. This means that `msg.sender` remains the original caller to the proxy, and, most importantly, any changes to storage (state variables) occur in the *proxy's storage*, not the `DELEGATECALL`ed contract's storage.

In this attack, the malicious `execTransaction` forced the Bybit Safe proxy to `DELEGATECALL` a contract deployed and controlled by the hackers. The code within this attacker-controlled contract was designed to overwrite a specific storage slot in the Bybit Safe proxy contract – storage slot `0`. This slot is critical because it stores the address of the implementation contract (also known as the mastercopy) that the proxy delegates its logic to.

By overwriting storage slot `0`, the attackers replaced the address of the legitimate Safe implementation contract with the address of a new, malicious implementation contract, also under their control. Once this malicious implementation was in place, subsequent transactions initiated by the hackers, such as "Sweep ETH" and "Sweep ERC20" calls, were processed by this compromised logic, allowing them to drain all funds from the Bybit multisig wallet to an "Bybit Exploiter" address.

### Dissecting the Attacker's Payload: A Closer Look at the Malicious execTransaction
Understanding the parameters of the malicious `execTransaction` call is crucial to grasping the attack. The function signature from `GnosisSafe.sol` (the core Safe contract logic) is as follows:
```solidity
function execTransaction(
    address to,
    uint256 value,
    bytes calldata data,
    Enum.Operation operation, // 0 for call, 1 for delegatecall
    uint256 safeTxGas,
    uint256 baseGas,
    uint256 gasPrice,
    address gasToken,
    address payable refundReceiver,
    bytes calldata signatures
) external payable returns (bool success);
```

The attackers submitted a transaction (hash: `0x46deef0f52e3a983b67abf471444a41dd7ffd6d32da69d62081c68ad7882`) that interacted with Bybit's Cold Wallet 1 multisig proxy (`0x1Db92e2EeBC8E0c075a02BeA49a2935BcD2dFCF4`). The key parameters within this `execTransaction` call were:

  * `to` **(parameter 0)**: `0x96221423681A6d52E184D440a8eFCEbb105C7242`. This was the address of the first malicious contract deployed by the attacker, to which the Safe proxy would perform a `delegatecall`.

  * `value` **(parameter 1)**: `0`. No Ether was intended to be transferred by the `execTransaction` itself to this malicious contract.

  * `data` **(parameter 2)**: `0xa9059cbb000000000000000000000000bdd077f651ebe7f7b3ce16fe5f2b025be29695160000000000000000000000000000000000000000000000000000000000000000`.

      * The first four bytes, `0xa9059cbb`, are the function selector for the standard ERC20 `transfer(address,uint256)` function. This was a deceptive tactic.

      * The first argument encoded in this `data` was `0xbdd077f651ebe7f7b3ce16fe5f2b025be2969516`. When the malicious contract at `0x9622...` executed via `delegatecall` in the context of the Bybit proxy, it used this address to overwrite storage slot 0 of the proxy. This address, `0xbDd077...,` became the address of the *new, malicious implementation contract*.

      * The second argument was `0`.

  * `operation` **(parameter 3)**: `1`. This explicitly instructed the Safe proxy to use `delegatecall` when interacting with the `to` address (`0x9622...`) using the provided `data`.

The use of the `transfer` function selector in the `data` payload was a clever misdirection. While a block explorer's input data decoder might interpret this as a `transfer` call based on the selector, the crucial context is the `delegatecall` operation. The code at the `delegatecall` target (`0x9622...`) was not a standard ERC20 token; it was specifically designed to take the first argument from this "fake transfer" data and use it to modify the proxy's implementation address.

### The Human Factor: How UI Masking and Incomplete Verification Led to Disaster
The technical sophistication of the `delegatecall` exploit relied on a critical human vulnerability: the failure of signers to meticulously verify transaction details on their hardware wallets. It's highly probable that the Bybit signers, including the CEO, were victims of a "musked UI" (masked or manipulated User Interface) attack.

In such scenarios, malware on a signer's computer alters the information displayed on their screen. The signer might see what appears to be a legitimate transaction on their web browser – for example, a simple ETH transfer to a known, whitelisted address. However, the actual transaction data being packaged and sent to their connected hardware wallet for signing is entirely different: in this case, the malicious `execTransaction` call detailed above.

Ben Zhou's admission of "not check[ing] fully" the details on his Ledger hardware wallet's trusted display is the linchpin of the successful exploit. Had the signers carefully examined all parameters presented on their hardware wallet screens, they might have identified several red flags:

1. **The `to` address within the `execTransaction` data**: This would have been the unfamiliar, malicious contract address (`0x9622...`), not a known Bybit address.

2. **The** `operation` **type**: The hardware wallet, if capable of clearly signing or displaying this detail, would have shown the operation as `1` (for `delegatecall`), a highly privileged and unusual operation for routine transfers.

3. **The** `data` **payload**: While complex, the presence of an unfamiliar target address (`0xbDd077...`) embedded within this data should have raised alarms.

This attack vector, leveraging UI masking to trick users into signing malicious transactions on their hardware wallets, is not novel. It has been observed in previous high-profile incidents, such as the hacks against WazirX and Radiant Capital. Security researchers like ZachXBT have linked such attack patterns to North Korean state-sponsored threat actors.

The incident underscores the critical difference between "blind signing" and "clear signing" on hardware wallets. Blind signing occurs when a hardware wallet cannot fully decode or interpret the transaction data, presenting the user with only a hash or raw hexadecimal strings. Clear signing, conversely, involves the hardware wallet parsing the transaction and displaying its meaningful components in a human-readable format (e.g., "You are calling function `execTransaction` on contract `0xBybitProxy...` with `operation: DELEGATECALL` to `0xMaliciousContract...`"). The community, including hardware wallet manufacturers like Keystone, has been advocating for improved clear signing capabilities, especially for complex interactions like Safe multisig executions.

### Understanding Safe's Proxy Architecture: How delegatecall Hijacked Bybit's Wallet
To fully appreciate the attack, it's essential to understand the proxy pattern used by Safe:

   * **Safe (Gnosis Safe / safe.global)**: A smart contract system enabling features like multisignature asset management.

   * **Multisig Proxy Contract**: This is the contract that holds the actual assets (e.g., Bybit's Cold Wallet 1: 0x1Db92e...dFCF4). It has its own storage but delegates most of its logic execution to an implementation contract. Users interact directly with this proxy contract.

   * **Implementation Contract (Mastercopy)**: This contract contains the standard logic for all Safe wallets of a particular version (e.g., functions like `execTransaction`, `addOwner`, `removeOwner`). It is stateless in the context of a single user's Safe; its code is executed by many proxies.

The `delegatecall` opcode is fundamental to this EIP-1167 (Minimal Proxy Contract) or similar proxy patterns. When the Bybit proxy contract executed the attacker's `execTransaction` with `operation: 1` (delegatecall) targeting the malicious contract `0x9622...`, the code of `0x9622...` ran *as if it were the proxy's own code*.

Crucially, this meant that any storage modifications made by the malicious contract's code affected the *proxy's storage*. As previously mentioned, Safe proxies store the address of their current implementation contract in storage slot 0x0...0 (the very first slot). The malicious code was designed to write a new address – the address of the attacker's second malicious contract (`0xbDd077...`) – into this slot.

This change can be verified by inspecting the proxy contract's storage before and after the malicious transaction:

   * **Before the hack transaction (e.g., at block 21895237), storage slot `0` of `0x1Db92e...dFCF4` held**:
`0x00000000000000000000000034cfac646f301356faa8b21e94227e3583fe3f5f` (a legitimate Safe L2 V1.3.0 mastercopy address).

   * **After the hack transaction (e.g., at block 21895239), storage slot `0` of `0x1Db92e...dFCF4` held**:
`0x000000000000000000000000bdd077f651ebe7f7b3ce16fe5f2b025be2969516` (the address of the new, malicious implementation contract).

Once this implementation address was changed, the Bybit Safe proxy effectively operated under the attacker's complete control. Any subsequent interactions with the proxy would execute the code of this new malicious implementation, enabling the attackers to authorize arbitrary transactions and drain the funds.

According to Safe's own investigation, no codebase breach or malicious dependencies were found on their side. The vulnerability exploited was purely operational, hinging on compromised signers and the misuse of the `delegatecall` feature through social engineering.

### Investigative Tools: Verifying On-Chain State Changes
Several tools are available for on-chain investigation and verification, which can help in understanding such attacks and confirming state changes.

The Foundry toolkit's `cast` command-line utility is invaluable for inspecting contract storage directly. For example, to see the change in the implementation address (mastercopy) for the Bybit proxy, one could use:

   * To view storage slot 0 before the malicious transaction:
`cast storage 0x1Db92e2EeBC8E0c075a02BeA49a2935BcD2dFCF4 0 --block 21895237`

   * To view storage slot 0 after the malicious transaction:
`cast storage 0x1Db92e2EeBC8E0c075a02BeA49a2935BcD2dFCF4 0 --block 21895239`

These commands would clearly show the value stored at slot `0` changing from the legitimate Safe implementation address to the attacker's malicious implementation address.

Block explorers like Etherscan.io and Blockscout.com are also essential. Etherscan's input data decoder helps in breaking down the parameters of transactions like `execTransaction`. However, as noted in this attack, sometimes the default decoding (e.g., seeing `transfer` based on a selector) can be misleading without considering the full context, like the `operation` type being `delegatecall`. Blockscout was noted by some analysts to correctly show the updated malicious implementation for the Bybit proxy post-hack, while Etherscan (depending on its proxy detection heuristics) might initially still display the ABI of the original, legitimate implementation. This highlights the utility of cross-referencing information across different explorers.

### Critical Lessons for Multisig Users: Preventing Similar Attacks
The Bybit hack, despite its sophistication, underscores fundamental security principles that, if adhered to, could have prevented the loss. For all users of Safe multisigs, and indeed any smart contract wallet system, the following lessons are paramount:

1. **Hardware Wallet Verification is Non-Negotiable**: The trusted display of your hardware wallet is your last line of defense. **NEVER** sign a transaction based solely on what your computer screen or web UI shows. UI masking is a prevalent threat. Meticulously verify **ALL** transaction details on the hardware wallet itself before approving. This includes the destination address, value, function being called, and any complex data payloads. As Tayvano, a prominent security researcher, starkly warned, if attackers gain access to your device (e.g., via malware enabling UI masking), you are vulnerable if you don't verify on your hardware wallet.

2. **Understand** `execTransaction` **Parameters in Safe**: When signing an `execTransaction` for a Safe multisig, pay extremely close attention to:

   * **The** `to` **address parameter**: This is the contract your multisig will ultimately interact with. Is it known and trusted?

   * **The** `operation` **parameter**: `0` for `call`, `1` for `delegatecall`. A `delegatecall` (`operation: 1`) should be treated with extreme suspicion unless you are an advanced user performing a specific, understood administrative action (like a Safe upgrade initiated by the official Safe team). For most user-initiated transactions, this should be `0`.

   * **The** `data` **payload**: Attempt to understand what function and arguments are encoded here. If it's opaque or points to unfamiliar contracts or functions, do not proceed without absolute certainty.

3. **Beware of Blind Signing**: If your hardware wallet indicates it requires "blind signing" for a transaction (meaning it cannot fully decode and display the transaction's intent), you are taking on significant risk. Advocate for and use hardware wallets that offer comprehensive "clear signing" for the types of transactions you frequently perform, especially for complex interactions like those with Safe contracts.

4. **Proficiency in Decoding Raw Data is Essential for Security Teams**: Technical personnel, especially those on security councils, C-level executives involved in signing, or incident response teams, must be capable of decoding and understanding raw transaction call data. Relying solely on UIs is insufficient for high-value targets.

5. **Continuous Vigilance**: The threat landscape is constantly evolving. Stay informed about new attack vectors and refresh your security practices regularly. This incident was not a flaw in Safe's audited smart contracts but an exploitation of human trust and operational gaps.

## Streamlining Safe Wallet Security: Verifying Transactions with Domain and Message Hashes

### The Challenge: Overcoming "Security Fatigue" with Complex JSON
Hardware wallets provide a crucial layer of security by keeping private keys offline. Yet, when asked to sign a complex transaction, such as an EIP-712 typed data message for a Safe transaction, users are often confronted with a large, intricate JSON structure. Attempting to verify every field and value on a limited hardware wallet display is not only cumbersome but also error-prone. This can lead to "security fatigue," where users may inadvertently approve malicious transactions due to the difficulty of thorough verification. Ensuring the integrity of every parameter becomes a daunting task, undermining the very security the hardware wallet aims to provide.

#### The Solution: Focused Verification with Domain and Message Hashes

Instead of attempting to digest the entire JSON payload on your hardware wallet, a more effective method focuses on two key cryptographic hashes derived from the EIP-712 structure: the **Domain Hash** and the **Message Hash**.

The process is as follows:

1. **Hardware Wallet Configuration**: Ensure your hardware wallet is configured to display only the Domain Hash and the Message Hash when an EIP-712 signature is requested. This simplifies the on-device verification step.

2. **Independent Calculation:** Using trusted off-chain tools, independently calculate the Domain Hash and Message Hash based on the transaction details you expect to sign. This means you should have a clear understanding of the transaction's intent and its parameters before initiating the signing process.

3. **Comparison and Confirmation**: Compare the Domain Hash and Message Hash displayed on your hardware wallet with the hashes you calculated independently. If these two sets of hashes match, you can have a high degree of confidence that you are signing the intended transaction, without needing to parse every single field of the raw JSON on the small screen.

#### Example

* **Scenario**: You intend to deposit 0.1 ETH to the ZkSync Aave token pool using a Safe version 1.4.1 multisig wallet.

* **Hardware Wallet Simulation**: Upon initiating the signing process (e.g., clicking "Sign" in a dApp integrated with your Safe), a simulated hardware wallet prompt (like a Trezor) appears. Crucially, this prompt is configured to display only:

   * **Domain Hash:** `0xe0392d263ff13e09757bfce9b182ead8cebd9d1b404aa7df77e65b304969130`

   * **Message Hash**: `0xb2498e7f8d82ce5d628accdc7d7bb245557a93f420c3b8baeab1df0c11d0886`

* **Your Verification Task**: Your responsibility is to take the raw JSON data corresponding to this transaction, use a reliable EIP-712 hashing tool to compute the Domain Hash and Message Hash, and then verify that your calculated hashes precisely match those displayed by the simulated hardware wallet.

### Understanding the EIP-712 Structure for SafeTX

Safe transactions utilize the EIP-712 standard for typed structured data hashing and signing. This standard makes signing data more human-readable and less prone to phishing by defining a clear structure for the data being signed.

Here's a simplified example of the JSON structure for a SafeTX:

```json
{
  "types": {
    "SafeTX": [
      { "name": "to", "type": "address" },
      { "name": "value", "type": "uint256" },
      { "name": "data", "type": "bytes" },
      { "name": "operation", "type": "uint8" },
      { "name": "safeTxGas", "type": "uint256" },
      { "name": "baseGas", "type": "uint256" },
      { "name": "gasPrice", "type": "uint256" },
      { "name": "gasToken", "type": "address" },
      { "name": "refundReceiver", "type": "address" },
      { "name": "nonce", "type": "uint256" }
    ],
    "EIP712Domain": [
      { "name": "chainId", "type": "uint256" },
      { "name": "verifyingContract", "type": "address" }
    ]
  },
  "domain": {
    "chainId": "42161", // Example: Arbitrum
    "verifyingContract": "0x4087d2046A7435911FC26DCFac1c2Db26957Ab72" // Your Safe wallet address
  },
  "primaryType": "SafeTx",
  "message": {
    // Example values for the transaction:
    // "to": "0xRecipientAddress...",
    // "value": "0", // For a token interaction, ETH value might be 0
    // "data": "0xFunctionSelectorAndParameters...", // The call data for the transaction
    // "nonce": "29" // The Safe's current nonce
    // ... other SafeTX fields
  }
}
```
* The **Domain Hash** is a cryptographic hash derived from the `domain` object (containing `chainId` and `verifyingContract` – your Safe's address) and its corresponding type definition in types (EIP712Domain). This hash scopes the signature to a specific domain, preventing replay attacks across different contracts or chains.

* The **Message Hash** is a cryptographic hash derived from the `message` object (containing the actual transaction details like `to`, `value`, `data`, `nonce`, etc.) and its type definition (`SafeTX`). This hash represents the unique content of your transaction.

The final `safeTxHash` is the EIP-712 hash produced by combining these two hashes according to the standard. By verifying the Domain Hash and Message Hash separately, you are implicitly verifying the integrity of this `safeTxHashs`

#### sEssential Tools and Resources for Verification

Several tools can assist you in independently calculating these hashes:

* `wise-signer.cyfrin.io/tools/`: This page on the Wise Signer site lists a collection of helpful utilities for Web3 security and transaction analysis.

* `github.com/cyfrin/safe-hash-rs` : A robust Rust-based command-line tool specifically designed for verifying Safe wallet transaction data and EIP-712 messages. It efficiently calculates the Domain Hash and Message Hash from your transaction's JSON data, enabling the verification method described here. This tool is an improved iteration for reliable hash calculation.

