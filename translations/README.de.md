# German translation

#### This is a page for collaboration on terminology between German translators

Let's build a coherent dictionary for the translation of technical and other Monero-related terms, providing consistency and ease of maintainability for future translators/contributers. The initial wordlist was branched of from [the swedish collab](https://taiga.getmonero.org/project/erciccione-monero-localization/wiki/swedish-terminology). 

Everything in this document should be treated as a request for comment, so it can and probably will change in the future upon further input.

## Guidelines (WIP)

### Working on the .ts file
#### Step 1: Divide & Conquer!
#### Step 2: Translation
##### Qt Linguist
##### Text Editor
#### Step 3: Proof-reading
##### Qt Linguist
##### Text Editor

#### Handling of Placeholder text
Placeholder text should not be translated, so that upstream changes are automatically displayed in the gui.  
Examples: '4...',  '78.9239845', '2324.9239845'.  
This assumes that numeric value input defaults to US throughout localizations.

**TODO: Compile and check assumption**

## Not translated
| English                                     | German                   | Notes                                          |
| ------------------------------------------- | ---                      | ---                                            |


## New

| English                                     | German                   | Notes                                          |
| ------------------------------------------- | ---                      | ---                                            |
| **hidden**                                  | versteckt                |                                                |
| ***node***                                  | *Knoten? Node?*          |                                                |
| **QrCode(Qr Code)** ^1                      | QR-Code                  |                                                |
| **view key**                                | View-Key                 |                                                |

**^1** : Inconsistent in upstream?

## Changed

Less ambiguous/incoherent: Former translation was found to be ambiguous technically or in meaning, or the term was translated differently throughout the GUI.  

| English                                     | German                   | Notes                                          |
| ------------------------------------------- | ---                      | ---                                            |
| **log**                                     | Log                      | was *Log/Bericht*                              |
| **mnemonic seed**                           | mnemonischer Seed        | was: *mnemonischer Code*                       |
| **output**                                  | Output                   | was: *Ausgang*                                 |
| **public spend key**  ^1                    | öffentlicher Spend-Key   | was: *Spend-Schlüssel (öffentlich)*            |
| **private spend key**  ^1                   | privater Spend-Key       | was: *Spend-Schlüssel (privat)*                |
| **read-only**                               | schreibgeschützt         | was: *nicht beschreibbar* (regarding FS access) |
| **reward**                                  | Belohnung                | was: inconsistent                              |
| **seed**                                    | Seed                     | was: *(mnemonischer) Code*                     |
| **spend key**                               | Spend-Key                | was: Spend-Schlüssel                           |

**^1** : Inconsistent in upstream?  

## Discuss Change

Mist, *balance* muss was anderes werden, da *amount* schon als "Betrag" übersetzt wurde.

| English                                     | German                   | Notes                                          |
| ------------------------------------------- | ---                      | ---                                            |
| amount                                      | *Menge?*                 | was: *Betrag*                                  |
| balance                                     | *Betrag?*                | was: *Guthaben*                                |
| change                                      | *Rückgeld?*              |                                                |
| funds                                       |                          | was: *Geld/Guthaben*                           |
| quick transfer                              |                          | is: *Schnellüberweisung*                       |
| security level                              | *Sicherheitslevel?*      | was: *Geheimhaltungslevel*                     |
| Tx key                                      |                          | is: *Tx-Schlüssel*                             |
| unlocked balance                            | *verfügbarer Betrag?*    | was: *verfügbares Guthaben*                    |

## Unchanged

Consistent: Leaving the existing translation made sense.  

| English                                     | German                   | Notes                                          |
| ------------------------------------------- | ---                      | ---                                            |
| blockchain                                  | Blockchain               |                                                |
| block height                                | Blockhöhe                |                                                |
| confirmations                               | Bestätigungen            |                                                |
| daemon                                      | Daemon                   |                                                |
| entry                                       | Eintrag                  |                                                |
| error                                       | Fehler                   |                                                |
| fee                                         | Gebühr                   |                                                |
| integrated address                          | integrierte Adresse      |                                                |
| mine                                        | minen                    |                                                |
| miner                                       | Miner                    |                                                |
| mining                                      | Mining                   |                                                |
| Note:                                       | Info:                    |                                                |
| payment                                     | Zahlung                  |                                                |
| payment ID                                  | Zahlungs-ID              |                                                |
| proof                                       | Nachweis                 |                                                |
| ringsize                                    | Ringgröße                |                                                |
| transaction                                 | Transaktion              |                                                |
| Tx ID                                       | Tx-ID                    |                                                |
| Tx note                                     | Tx-Notiz                 |                                                |
| wallet                                      | Wallet                   |                                                |

## Not in GUI

| English                                     | German                   | Notes                                          |
| ------------------------------------------- | ---                      | ---                                            |
| *anonymity set*                             | *???*                    |                                                |
| block reward                                | Blockbelohnung           |                                                |
| block time                                  | Blockzeit                |                                                |
| change                                      | Rückgeld                 |                                                |
| *coinbase transaction*                      | *Coinbase-Transaktion?*  |                                                |
| confidential transaction                    | vertrauliche Transaktion |                                                |
| cryptocurrency                              | Kryptowährung            |                                                |
| dust                                        | Dust                     |                                                |
| emission                                    | Emission                 |                                                |
| fork                                        | Fork                     |                                                |
| fungible                                    | Fungibel                 |                                                |
| fungibility                                 | Fungibilität             |                                                |
| *ledger*                                    | *???*                    |                                                |
| *proof-of-work*                             | *Proof-of-Work*          |
| public key                                  | öffentlicher Schlüssel   |                                                |
| private key                                 | privater Schlüssel       |                                                |
| public view key                             | öffentlicher View-Key    |                                                |
| private view key                            | privater View-Key        |                                                |
| *ring confidential transaction (Ring CT)*   | *???*                    |                                                |
| ring signature                              | Ringsignatur             |                                                |
| scalable                                    | skalierbar               |                                                |
| scalability                                 | Skalierbarkeit           |                                                |
| stealth address                             | Schattenadresse          | _Feedback appreciated!_, alt: Tarnadresse      |
| *tail*                                      | *???*                    |                                                |
| *tail emission*                             | *???*                    |                                                |
| *transaction unlock time*                   | *???*                    |                                                |
