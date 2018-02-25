# German translation

#### This is a page for collaboration on terminology between German translators

Let's build a coherent dictionary for the translation of technical and other Monero-related terms, providing consistency and ease of maintainability for future translators/contributers. The initial wordlist was branched of from [the swedish collab](https://taiga.getmonero.org/project/erciccione-monero-localization/wiki/swedish-terminology). 

Everything in this document should be treated as a request for comment, so it can and probably will change in the future upon further input.

## TODO: Guidelines
#### Placeholder text
Placeholder text should not be translated, so that upstream changes are automatically displayed in the gui.  
Examples: '4...',  '78.9239845', '2324.9239845'

**TODO: Compile and check assumption**

## Not translated
| English                                     | German                   | Notes                                     |
| ------------------------------------------- | ---                      | ---                                       |


## New

| English                                     | German                   | Notes                                     |
| ------------------------------------------- | ---                      | ---                                       |
| ***node***                                  | *Knoten? Node?*          |                                           |
| **QrCode(Qr Code)** ^1                      | QR-Code                  |                                           |
| **view key**                                | View-Key                 |                                           |

**^1** : Inconsistent in upstream?

## Changed

Less ambiguous: Former translation was found to be ambiguous technically or in meaning.  

| English                                     | German                   | Notes                                     |
| ------------------------------------------- | ---                      | ---                                       |
| **mnemonic seed**                           | mnemonischer Seed        | was: *mnemonischer Code*                  |
| **public spend key**  ^1                    | öffentlicher Spend-Key   | was: *Spend-Schlüssel (öffentlich)*       |
| **private spend key**  ^1                   | privater Spend-Key       | was: *Spend-Schlüssel (privat)*           |
| **reward**                                  | Belohnung                | was: inconsistent                         |
| **seed**                                    | Seed                     | was: *(mnemonischer) Code*                |
| **spend key**                               | Spend-Key                | was: Spend-Schlüssel                      |
| **output**                                  | Output                   | was: *Ausgang*                            |

**^1** : Inconsistent in upstream?  

## Discuss Change

Mist, *balance* muss was anderes werden, da *amount* schon als "Betrag" übersetzt wurde.

| English                                     | German                   | Notes                                     |
| ------------------------------------------- | ---                      | ---                                       |
| balance                                     | *Betrag?*                | was: *Guthaben*                           |
| quick transfer                              |                          | is: *Schnellüberweisung*                  |
| security level                              | *Sicherheitslevel?*      | was: *Geheimhaltungslevel*                |
| Tx key                                      |                          | is: *Tx-Schlüsseö*                        |
| unlocked balance                            | *verfügbarer Betrag?*    | was: *verfügbares Guthaben*               |

## Unchanged

Consistent: Leaving the existing translation made sense.  

| English                                     | German                   | Notes                                     |
| ------------------------------------------- | ---                      | ---                                       |
| blockchain                                  | Blockchain               |                                           |
| block height                                | Blockhöhe                |                                           |
| confirmations                               | Bestätigungen            |                                           |
| daemon                                      | Daemon                   |                                           |
| entry                                       | Eintrag                  |                                           |
| integrated address                          | integrierte Adresse      |                                           |
| mine                                        | minen                    |                                           |
| miner                                       | Miner                    |                                           |
| mining                                      | Mining                   |                                           |
| payment ID                                  | Zahlungs-ID              |                                           |
| ringsize                                    | Ringgröße                |                                           |
| transaction                                 | Transaktion              |                                           |
| Tx ID                                       | Tx-ID                    |                                           |
| Tx note                                     | Tx-Notiz                 |                                           |
| wallet                                      | Wallet                   |                                           |

## Not in GUI

| English                                     | German                   | Notes                                     |
| ------------------------------------------- | ---                      | ---                                       |
| *anonymity set*                             | *???*                    |                                           |
| block reward                                | Blockbelohnung           |                                           |
| block time                                  | Blockzeit                |                                           |
| change                                      | Rückgeld                 |                                           |
| *coinbase transaction*                      | *Coinbase-Transaktion?*  |                                           |
| confidential transaction                    | vertrauliche Transaktion |                                           |
| cryptocurrency                              | Kryptowährung            |                                           |
| dust                                        | Dust                     |                                           |
| emission                                    | Emission                 |                                           |
| fork                                        | Fork                     |                                           |
| fungible                                    | Fungibel                 |                                           |
| fungibility                                 | Fungibilität             |                                           |
| *ledger*                                    | *???*                    |                                           |
| *proof-of-work*                             | *???*                    |                                           |
| public key                                  | öffentlicher Schlüssel   |                                           |
| private key                                 | privater Schlüssel       |                                           |
| public view key                             | öffentlicher View-Key    |                                           |
| private view key                            | privater View-Key        |                                           |
| *ring confidential transaction (Ring CT)*   | *???*                    |                                           |
| ring signature                              | Ringsignatur             |                                           |
| scalable                                    | skalierbar               |                                           |
| scalability                                 | Skalierbarkeit           |                                           |
| stealth address                             | Schattenadresse          | _Feedback appreciated!_, alt: Tarnadresse |
| *tail*                                      | *???*                    |                                           |
| *tail emission*                             | *???*                    |                                           |
| *transaction unlock time*                   | *???*                    |                                           |