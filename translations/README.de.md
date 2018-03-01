# German translation

## This is a page for collaboration on terminology between German translators

Let's build a coherent dictionary for the translation of technical and other
Monero-related terms, providing consistency and ease of maintainability for
future translators/contributers. The initial wordlist was branched of from
[the swedish collab](https://taiga.getmonero.org/project/erciccione-monero-localization/wiki/swedish-terminology). 

Everything in this document should be treated as a request for comment, so it
can and probably will change in the future upon further input.

## Guidelines (WIP)

### Translation of terms ###
Whenever possible, the terms from the 'agreed-upon' list should be used.

### Handling of placeholder text
Placeholder text should not be translated, so that upstream changes are
automatically displayed in the gui.
Examples: '4...',  '78.9239845', '2324.9239845'.
This assumes that numeric value input defaults to US throughout localizations.

**TODO: Compile and check assumption**

## Workflow (WIP)
### 1. Setup
- Fork the [monero-gui repository](https://github.com/monero-project/monero-gui) on GitHub
- TODO: QT Linguist
- TODO: PR

___

## Not translated
| English                    | German | Notes         |
| ---                        | ---    | ---           |
| local daemon startup flags |        |
| signing address            |        | recherchieren |
| Spendable Wallet           |        | recherchieren |
| Tx descriptions            |        |               |
| wallet creation height     |        |               |


## New

| English                | German              | Notes       |
| ---                    | ---                 | ---         |
| **cache**              | Cache               |             |
| **daemon log path**    | Daemon-Log-Pfad     |             |
| **hidden**             | versteckt           |             |
| **QrCode(Qr Code)** ^1 | QR-Code             |             |
| **spent outputs**      | verbrauchte Outputs |             |
| **view key**           | View-Key            | really new? |
| **wallet log path**    | Wallet-Log-Pfad     |             |

**^1** : Inconsistent in upstream?


## Discuss Change

| English          | German                | Notes                       |
| ---              | ---                   | ---                         |
| clear            |                       | is: *leeren*                |
| Generate         | *erzeugen*            | was: *generieren/erstellen* |
| money            |                       | is: *Geld/Guthaben*         |
| Tracking         |                       | is: *Nachverfolgen*         |


## Changed

Less ambiguous/incoherent: Former translation was found to be ambiguous
technically or in meaning, or the term was translated differently throughout the
GUI. This can and will always happen, understandability > consistency :)

- funds: case-by-case
- key : Schlüssel, ausser >
  view-key, spend-key

| English                   | German                 | Notes                                 |
| ---                       | ---                    | ---                                   |
| **log**                   | Log                    | was: *Log/Bericht/Protokoll*          |
| **log level**             | Log-Level              | was: *Detailgrad des Berichts*        |
| **mnemonic seed**         | mnemonischer Seed      | was: *mnemonischer Code*              |
| **output**                | Output                 | was: *Ausgang*                        |
| **public spend key**  ^1  | öffentlicher Spend-Key | was: *Spend-Schlüssel (öffentlich)*   |
| **private spend key**  ^1 | privater Spend-Key     | was: *Spend-Schlüssel (privat)*       |
| **quick transfer**        | Schnelltransfer        | was: *Schnellüberweisung*             |
| **read-only**             | schreibgeschützt       | was: *nicht beschreibbar* (FS access) |
| **reward**                | Belohnung              | was: inconsistent                     |
| **seed**                  | Seed                   | was: *(mnemonischer) Code*            |
| **spend key**             | Spend-Key              | was: Spend-Schlüssel                  |
| **spend proof**           | Sendenachweis          | was: *Ausgabennachweis*               |
|                           |                        |                                       |
| ReadOnly Wallet           | *view-only Wallet*     | is: *Schreibgeschütztes Wallet*       |
| View Only Wallet          | *view-only Wallet*     | is: *schreibgeschütztes Wallet*       |
viewOnly == readOnly?

**^1** : Inconsistent in upstream?


## Unchanged

Consistent: Leaving the existing translation made sense.

| English            | German               | Notes      |
| ---                | ---                  | ---        |
| amount             | Betrag               |            |
| balance            | Guthaben             |            |
| blockchain         | Blockchain           |            |
| block height       | Blockhöhe            |            |
| confirmations      | Bestätigungen        |            |
| daemon             | Daemon               |            |
| entry              | Eintrag              |            |
| error              | Fehler               |            |
| fee                | Gebühr               |            |
| funds              | Geld/Guthaben        | contextual |
| integrated address | integrierte Adresse  |            |
| mine               | minen                |            |
| miner              | Miner                |            |
| mining             | Mining               |            |
| node               | Node (m/f/n?)        |            |
| Note:              | Info:                |            |
| payment            | Zahlung              |            |
| payment ID         | Zahlungs-ID          |            |
| proof              | Nachweis             |            |
| ringsize           | Ringgröße            |            |
| security level     | Sicherheitslevel     |            |
| transaction        | Transaktion          |            |
| testnet            |                      |            |
| Tx ID              | Tx-ID                |            |
| Tx key             | Tx-Schlüssel         |            |
| Tx note            | Tx-Notiz             |            |
| unlocked balance   | verfügbares Guthaben |            |
| wallet             | Wallet               |            |

## Not in GUI

| English                         | German                   | Notes                               |
| ---                             | ---                      | ---                                 |
| *anonymity set*                 |                          |                                     |
| block reward                    | Blockbelohnung           |                                     |
| block time                      | Blockzeit                |                                     |
| change                          | Rückgeld                 |                                     |
| *coinbase transaction*          | *Coinbase-Transaktion?*  |                                     |
| confidential transaction        | vertrauliche Transaktion |                                     |
| cryptocurrency                  | Kryptowährung            |                                     |
| dust                            | Dust                     |                                     |
| emission                        | Emission                 |                                     |
| fork                            | Fork                     |                                     |
| fungible                        | Fungibel                 |                                     |
| fungibility                     | Fungibilität             |                                     |
| *ledger*                        |                          |                                     |
| *proof-of-work*                 | *Proof-of-Work*          |
| public key                      | öffentlicher Schlüssel   |                                     |
| private key                     | privater Schlüssel       |                                     |
| public view key                 | öffentlicher View-Key    |                                     |
| private view key                | privater View-Key        |                                     |
| *(Ring CT)*                     |                          |                                     |
| *ring confidential transaction* |                          |                                     |
| ring signature                  | Ringsignatur             |                                     |
| scalable                        | skalierbar               |                                     |
| scalability                     | Skalierbarkeit           |                                     |
| stealth address                 | Schattenadresse          | _FB appreciated!_, alt: Tarnadresse |
| *tail*                          |                          |                                     |
| *tail emission*                 |                          |                                     |
| *transaction unlock time*       |                          |                                     |
