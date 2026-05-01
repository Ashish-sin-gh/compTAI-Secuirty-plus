...

# Blockchain

Way of storing data in transparent, secure, temper-resistant chain of record (block).
#### Blocks of data linked together in a chain using cryptography
#### Each block contains:
- Data (transactions, records, etc.)
- A timestamp - last modification in the block
- A hash of the previous block
#### Public ledger: 
- A record keeping system maintaining participants identities in a secure and anonymous format.
- Decentralized 
#### Example:
- **Bit Coin** 
	- Peer-to-peer payments without banks
- **Smart contract** 
	- self-executing contracts where teams of the agreement are written directly into line of code.
	- no need for intermediaries.
- **Ethereum**
	- global network where you control your assets, your data, and your identity.
	- Financial transactions
	- governance
- **IBM** 
	- commercial environment.
	- <u>Permissioned blockchain</u>
		- used for business transactions.
		- Trust and transparency - immutable public ledgers.
- **Supply chain management**
- **Voting systems**
- **Healthcare Records**

# Encryption tool

### TPM (Trusted platform Module)
- **Dedicated microcontroller designed to protect hardware using integrated cryptographic keys.**
- Hardware level security to data from being altered.
- Device level security.
- example 
	- **Bitlocker** in windows OS
		- Cryptographic key is secured inside isolated hardware
		- counter software based attacks.
- Stores keys securely **inside the chip**
- Keys **never leave TPM**
	
### HSM (Hardware Security Module)
- **Physical devices that generate, store and manages digital keys and perform cryptographic operations.**
- Used for mission-critical situations
- external/enterprise device for **high-security key management**
- protects **organization-wide secrets**
- Performs operations like:
	- Encryption / decryption
	- Digital signing
	- Key exchange
	- code signing
- eg- financial transactions

### KMS (Key Management System)
- Integrated approach for 
	- generating, 
	- distributing,
	- rotate,
	- managing,
	- revocation and deletion 
	cryptographic keys for devices and applications.
	
- example:
	- AWS key management service
	- Azure key vault
	- google cloud KMS
### Secure Enclave 
- Co-processor integrated with main processor 
- purpose - data protection
- isolated from the main processor
- provide safe processing and storing of sensitive data

- **Analogy** : fortress inside a device

- Safeguard sensitive info :
	- fingerprint
	- facial recognition
	- apple pay info

- Even if device get compromised - this secure space is untouched.

# Obfuscation

 **Intentionally making something hard to understand**.
##### <u>Steganography</u> :
- **Concealing** a message within another message so that the very existence of the message is hidden.
- Hiding secret data with-in ordinary non-secret file/message to avoid detection.
- used with encryption - extra layer of security.
- **Tool** : 
	- www.stylesuxx.github/io/steganography/
##### <u>Tokenization</u> :
- For data protection.
- Substituting Sensitive data with non-sensitive equivalent called tokens which as no meaning.
	- Real data is stored somewhere else, and only specific system can map to that original value. 
- Example :
	- credit card used to do a payment 
		- data of the credit card is not stored directly 
		- a tokenized version of that data is stored 
		- use that token to do some specific action.
		- no actual data is found.
##### <u>Data Masking / data Obsfucation</u> :
- data remains recognizable, but don't actually include sensitive info.
- authenticity and reusability of the data ensured for specific tasks.
- Example:
	- credit card masking
		- XXXX XXXX XXXX 3426

# Cryptographic attacks

- Techniques employed by an attacker to exploit the vulnerability of the cryptographic systems with the Intent to compromise the CIA of the data.
### Downgrade attack / Version role back attack :
- force the system to use weaker or older cryptographic standards or protocols than what it is currently using.
- Exploit known vulnerability in the order versions. **backward compactivity**
- Attacker will do a MITM attack and manipulate their communication to use a older version of cypher suite (handshake).

- ##### POODLE attack:
	- Padding Oracle On Downgraded Legacy Encryption attack
	- targeted SSL 3.0

- ##### Counter measure:
	- No support for older legacy versions
	- version intolerance checks 
		- system claim it support the recent version only
		- other end user if really don't support - it will downgrade
		- if any forceful downgrade - caught
### Collision attacks :
- Finding 2 different input for same hash digest (hashed value)
- ##### Birthday attack
### Quantum Computing :
- A computer that has enormous computing power by using quantum mechanics to generate and manipulate quantum bits (**qubits**)   
- Qubits - made up of **photons / electron** - superposition

- #### Quantum communication:
	- Sending multiple combinations of 1 and 0 simultaneously 
	- tamper-resistant 
	- extremely fast communications
- Quantum computing can do maths very fast 
- cryptography in danger 

- ##### Counter-measure :
	- Post-quantum cryptography.
		- Increase key size.
		- post-quantum resistant algorithms 

