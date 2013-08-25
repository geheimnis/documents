Command Number, Parameters and Meaning
======================================

This file defines number, input parameters of core commands.

1. Codebook Related
-------------------

### 0x101 Listing Codebooks

*Parameters*: UserID

*Meaning*: List out all stored codebooks, available in database. Result should
be an array, which items are all associtive arrays, containing:
    (1) CodebookID
    (2) UsedTimes
    (3) CodebookLength
    (4) CreatedTime



### 0x111 Symmetric Encryption using a Codebook

*Parameters*: CodebookID, Plaintext

*Meaning*: Encrypts given plaintext using a codebook with CodebookID.
