<h1 align="center"><b>SHA-3 and Keccak Checksum Utility </b></h1>

<div align="center">

![Version](https://img.shields.io/github/v/tag/Aetherinox/package-libkeccak-sha3sum?logo=GitHub&label=version&color=ba5225) ![Downloads](https://img.shields.io/github/downloads/Aetherinox/package-libkeccak-sha3sum/total) ![Repo Size](https://img.shields.io/github/repo-size/Aetherinox/package-libkeccak-sha3sum?label=size&color=59702a) ![Last Commit)](https://img.shields.io/github/last-commit/Aetherinox/package-libkeccak-sha3sum?color=b43bcc)

</div>

---

<br />

SHA-3 and Keccak checksum utility 

<br />

---

<br />

# About

Fully configurable byte-orientated checksum utilities for Keccak and its close derivatives SHA-3, SHAKE and RawSHAKE.

This utilities can generate checksums or verify the checksums of files.

<br />

---

<br />

# Build

> [!WARNING]
> You must build `libkeccak` first, and then `sha3sum`.

<br />

Clone with git
```shell
git clone https://github.com/Aetherinox/package-libkeccak-sha3sum.git
```

<br />

Change to new directory
```shell
cd package-libkeccak-sha3sum/libkeccak
```

<br />

Run make && make install on `libkeccak`:

<br />

```shell
make
sudo make install
```

<br />

Next, go to the `sha3sum` folder and do the same.

<br />

```shell
make
sudo make install
```

<br />

You should be able to run a simple hash now

```shell
sha3sum <<< "Hello World"
```

Which should return

```
dc0d4419c6e5dbc2e5fbb9fcb9dc6ea16d6b3cbca34aabb618e2f782
```