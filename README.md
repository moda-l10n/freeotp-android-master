[![Build Status](https://github.com/freeotp/freeotp-android/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/freeotp/freeotp-android/actions/workflows/build.yml)

# FreeOTP

[FreeOTP](https://freeotp.github.io) is a two-factor authentication application for systems
utilizing one-time password protocols. Tokens can be added easily by scanning a QR code.

FreeOTP implements open standards:

* HOTP (HMAC-Based One-Time Password Algorithm) [RFC 4226](https://www.ietf.org/rfc/rfc4226.txt)
* TOTP (Time-Based One-Time Password Algorithm) [RFC 6238](https://www.ietf.org/rfc/rfc6238.txt)

This means that no proprietary server-side component is necessary: use any server-side component
that implements these standards.

## Download FreeOTP for Android

* [Google Play](https://play.google.com/store/apps/details?id=org.fedorahosted.freeotp)
* [F-Droid](https://f-droid.org/packages/org.fedorahosted.freeotp)

## Contributing

Pull requests on GitHub are welcome under the Apache 2.0 license, see [COPYING](COPYING).

## Permissions

The FreeOTP app uses the following permissions

| Permission | Usage                    | Required | Permission type |
|------------|--------------------------|----------|-----------------|
| Camera     | Recognition of QR codes  | No       | Dangerous       |
| Internet   | Token image provisioning | No       | Normal          |


## 軟體中文 化
本專案為數位部開放原始碼軟體中文化專案項目之一，其中文化與專案應用可參考 Wiki。
