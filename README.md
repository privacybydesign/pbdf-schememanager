# Privacy by Design Foundation scheme manager

This repository contains the credential definitions, issuer information, and their public keys of the IRMA scheme manager of the Privacy by Design Foundation, called `pbdf`. This is the default and built-in scheme manager of the [IRMA app](https://github.com/privacybydesign/irma_mobile).

Use this repository by putting it in the `irma_configuration` folder of your project (for example, [the IRMA mobile app](https://github.com/privacybydesign/irma_mobile/tree/master/ios/irma_configuration) or the [IRMA API server](https://github.com/privacybydesign/irma_api_server/tree/master/src/main/resources)). Be sure to call the folder `pbdf`! E.g.,

    git clone https://github.com/privacybydesign/pbdf-schememanager pbdf

For more info, see the [`irma-demo` scheme manager](https://github.com/privacybydesign/irma-demo-schememanager).
