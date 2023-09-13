# viet-qr

## Installation

```sh
npm install @hoanle396/viet-qr
```

## Quick Start

Example file: 

```js
const qrCode = new QRCode();
  const value = qrCode
    .setBeneficiaryOrganization("bankid", "bankaccount")
    .setTransactionAmount("amount")
    .setAdditionalDataFieldTemplate("message")
    .build();
  console.log({ value });
```
