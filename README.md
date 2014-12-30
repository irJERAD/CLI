CLI
===

Command Line Interface shortcuts and techniques to remember, write about or otherwise use

### Calculate Checksums
- **MD5**
```
md5 /downloaded-filename.dmg
md5 /downloaded-filename.iso
```
*According to Apache*
```
cd <path_to_AOO_and_MD5_files>
openssl dgst -md5 <AOO file>.dmg
cat <MD5 file>.md5
```
-**SHA**
  Sha-1
```
shasum -a 1 /downloaded-filename.dmg
```
Sha-256
```
shasum -a 256 /downloaded-filename.dmg
```
*According to Apache*
```
cd <path_to_AOO_and_SHA256_files>
openssl dgst -sha256 <AOO file>.dmg
cat <SHA256 file>.sha256
