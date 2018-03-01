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
### Step 0: Setup
- Fork the [monero-gui repository](https://github.com/monero-project/monero-gui)
- TODO: QT Linguist

### 1. Divide & Conquer!

- Divide the workload into chunks. These could be contexts of the GUI or ranges
  of the wordlist.

- Make your chunks exclusive: To reduce the amount of merge conflicts, the
  chosen chunks should have no overlap.

- Create a branch for your chunk on the forked repository.

### 2. Translation
Focus on the untranslated terms of your chunk exlusively.

#### 2.1. Qt Linguist
Work through the entries with a blue question mark; these entries are not
translated at all. Enter your suggested translation and move to the next entry.
#### 2.2. Text Editor
### 3. Proof-reading
#### 3.1. Qt Linguist
#### 3.2. Text Editor

___

## Not translated
| English                    | German | Notes |
| ---                        | ---    | ---   |
| local daemon startup flags |        |
| Spendable Wallet           |        |       |
| spent outputs              |        |       |

- A unique user name used in
  the address book. It is not a
  transfer of information sent
  during the transfer

## New

| English                | German          | Notes |
| ---                    | ---             | ---   |
| **hidden**             | versteckt       |       |
| **QrCode(Qr Code)** ^1 | QR-Code         |       |
| **view key**           | View-Key        |       |

**^1** : Inconsistent in upstream?

## WTF?!
| English | WTF?! |
|---      |---    |

## Discuss Change

Mist, *balance* muss was anderes werden, da *amount* schon als "Betrag"
übersetzt wurde.

| English          | German                | Notes                           |
| ---              | ---                   | ---                             |
| amount           | *Menge?*              | was: *Betrag*                   |
| balance          | *Betrag?*             | was: *Guthaben*                 |
| change           | *Rückgeld?*           |                                 |
| clear            |                       | is: *leeren*                    |
| funds            |                       | was: *Geld/Guthaben*            |
| Generate         | *erzeugen*            | was: *generieren/erstellen*     |
| log level        |                       | is: *Detailgrad des Berichts*   |
| money            |                       | is: *Geld/Guthaben*             |
| quick transfer   |                       | is: *Schnellüberweisung*        |
| ReadOnly Wallet  |                       | is: *Schreibgeschütztes Wallet* |
| security level   | *Sicherheitslevel?*   | was: *Geheimhaltungslevel*      |
| testnet          |                       | is: *Testnet*                   |
| Tracking         |                       | is: *Nachverfolgen*             |
| Tx key           | *Tx-Key*              | is: *Tx-Schlüssel*              |
| unlocked balance | *verfügbarer Betrag?* | was: *verfügbares Guthaben*     |
| View Only Wallet |                       | is: *schreibgeschütztes Wallet* |


## Changed

Less ambiguous/incoherent: Former translation was found to be ambiguous #
technically or in meaning, or the term was translated differently throughout the
GUI.

| English                   | German                 | Notes                                 |
| ---                       | ---                    | ---                                   |
| **log**                   | Log                    | was: *Log/Bericht*                    |
| **mnemonic seed**         | mnemonischer Seed      | was: *mnemonischer Code*              |
| **output**                | Output                 | was: *Ausgang*                        |
| **public spend key**  ^1  | öffentlicher Spend-Key | was: *Spend-Schlüssel (öffentlich)*   |
| **private spend key**  ^1 | privater Spend-Key     | was: *Spend-Schlüssel (privat)*       |
| **read-only**             | schreibgeschützt       | was: *nicht beschreibbar* (FS access) |
| **reward**                | Belohnung              | was: inconsistent                     |
| **seed**                  | Seed                   | was: *(mnemonischer) Code*            |
| **spend key**             | Spend-Key              | was: Spend-Schlüssel                  |

**^1** : Inconsistent in upstream?

## Unchanged

Consistent: Leaving the existing translation made sense.

| English            | German              | Notes |
| ---                | ---                 | ---   |
| blockchain         | Blockchain          |       |
| block height       | Blockhöhe           |       |
| confirmations      | Bestätigungen       |       |
| daemon             | Daemon              |       |
| entry              | Eintrag             |       |
| error              | Fehler              |       |
| fee                | Gebühr              |       |
| integrated address | integrierte Adresse |       |
| mine               | minen               |       |
| miner              | Miner               |       |
| mining             | Mining              |       |
|node                | Node (m/f/n?)       |       |
| Note:              | Info:               |       |
| payment            | Zahlung             |       |
| payment ID         | Zahlungs-ID         |       |
| proof              | Nachweis            |       |
| ringsize           | Ringgröße           |       |
| transaction        | Transaktion         |       |
| Tx ID              | Tx-ID               |       |
| Tx note            | Tx-Notiz            |       |
| wallet             | Wallet              |       |

## Not in GUI

| English                         | German                   | Notes                               |
| ---                             | ---                      | ---                                 |
| *anonymity set*                 | *???*                    |                                     |
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
| *ledger*                        | *???*                    |                                     |
| *proof-of-work*                 | *Proof-of-Work*          |                                     |
| public key                      | öffentlicher Schlüssel   |                                     |
| private key                     | privater Schlüssel       |                                     |
| public view key                 | öffentlicher View-Key    |                                     |
| private view key                | privater View-Key        |                                     |
| *(Ring CT)*                     | *???*                    |                                     |
| *ring confidential transaction* | *???*                    |                                     |
| ring signature                  | Ringsignatur             |                                     |
| scalable                        | skalierbar               |                                     |
| scalability                     | Skalierbarkeit           |                                     |
| stealth address                 | Schattenadresse          | _FB appreciated!_, alt: Tarnadresse |
| *tail*                          | *???*                    |                                     |
| *tail emission*                 | *???*                    |                                     |
| *transaction unlock time*       | *???*                    |                                     |
