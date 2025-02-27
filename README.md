# EBSI4Austria

## Information

This repository contains information and examples related to the **EBSI4Austria** project, to pilot the [European Blockchain Service Infrastructure (EBSI)](https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/EBSI) in Austria.

The project is funded by the EU's Connecting Europe Facility (CEF) under the [2020 CEF Telecom Call - Blockchain (CEF-TC-2020-1)](https://ec.europa.eu/inea/en/connecting-europe-facility/cef-telecom/apply-funding/2020-cef-telecom-calls-proposals).

**WARNING:** The example data in this repository (incl. DIDs, keys, verifiable credentials, etc.) is for experimentation only. Any data in this repository must not be used for any real-life use cases, or considered real, secure, or trusted.

## Partners

* [Danube Tech](https://danubetech.com/)
* [TU Graz](https://www.tugraz.at/)
* [WU Wien](https://www.wu.ac.at/)

## DIDs

* Test DID for TU Graz: [`did:ebsi:zuoS6VfnmNLduF2dynhsjBU`](https://dev.uniresolver.io/#did:ebsi:zuoS6VfnmNLduF2dynhsjBU)
* Test DID for WU Wien: [`did:ebsi:z23EQVGi5so9sBwytv6nMXMo`](https://dev.uniresolver.io/#did:ebsi:z23EQVGi5so9sBwytv6nMXMo)

## Contexts

Note: This is something we are using internally at EBSI4Austria for experimentation; this is NOT an official EBSI/ESSIF JSON-LD context!

* [essif-schemas-vc-2020-v1.jsonld](https://github.com/danubetech/ebsi4austria-examples/blob/main/context/essif-schemas-vc-2020-v1.jsonld)

## Verifiable Credentials

* Example Diploma by TU Graz
  * [JSON-LD+LD-Proofs](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-tu-graz.jsonld)
  * [JSON-LD+JWT](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-tu-graz.jsonldjwt) (also see [JWT payload only](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-tu-graz.jsonldjwt.payload))
  * [JSON+JWT](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-tu-graz.jwt) (also see [JWT payload only](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-tu-graz.jwt.payload))
* Example Diploma by WU Wien
    * [Paper version](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/master_beispiel_de.png) (in German)
    * [Paper version](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/master_beispiel_en.png) (in English)
    * [JSON-LD+LD-Proofs](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-wu-wien.jsonld)
    * [JSON-LD+JWT](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-wu-wien.jsonldjwt) (also see [JWT payload only](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-wu-wien.jsonldjwt.payload))
    * [JSON+JWT](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-wu-wien.jwt) (also see [JWT payload only](https://github.com/danubetech/ebsi4austria-examples/blob/main/verifiablecredentials/diploma-wu-wien.jwt.payload))

## Technology

We use the following technologies in our project:

* [Universal Issuer](https://uniissuer.io/)
* [Universal Verifier](https://univerifier.io/)
* [SSI Java Libraries](https://gitlab.grnet.gr/essif-lab/infrastructure_2/danubetech/SSI_Java_Libraries_project_summary)
    * [ld-signatures-java](https://github.com/weboftrustinfo/ld-signatures-java)
    * [verifiable-credentials-java](https://github.com/danubetech/verifiable-credentials-java)

## Demonstration Websites

* https://wallet.interop.digitalbazaar.com/ - CHAPI web-based wallet
* https://tugraz.ebsi4austria.danubetech.com/ - Issuer demo website
* https://wuwien.ebsi4austria.danubetech.com/ - Verifier demo website

## Contact

markus@danubetech.com
