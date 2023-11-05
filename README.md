# validator-cli-demo
A very simple demo of validating a FHIR resource using the [validator_cli](https://confluence.hl7.org/display/FHIR/Using+the+FHIR+Validator).  It will output the validation result in html as an [artefact in a github action](https://github.com/actions/upload-artifact#where-does-the-upload-go).

The example resource is a [UKCore](https://simplifier.net/guide/uk-core-implementation-guide) Patient example taken from the [UKCore respository](https://github.com/NHSDigital/FHIR-R4-UKCORE-STAGING-MAIN).  This resource is part of the repo to allow tweaking/breaking it!  

The validator and UKCore package are downloaded.  

The package is the defaulted in a [github variable](https://docs.github.com/en/actions/learn-github-actions/variables#creating-configuration-variables-for-an-organization) to point to the latest UKCore package (at this time!).  Change this variable (IG_PACKAGE) to change the package.

![image](https://github.com/declankieran-nhsd/validator-cli-demo/assets/93662162/2d639b26-8a3c-4b0e-8d2b-9761ce734ddd)

Or create a fork (maybe branch) to change the resource if you want to use this beyond this particular example!
