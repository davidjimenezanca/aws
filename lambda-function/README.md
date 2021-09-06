# ZIP file

This project contains a zip file with the runtime environment of the test application, in binary format

 sample-project: App binary generated in Ubuntu 21.04
 bootstrap: execution file

## Prerequisites
- An account AWS console

## Development

It is deployed as "Custom runtime on Amazon Linux 2". It does not work due to a version incompatibility in the GLIBC library between the binary generated and the one supported by Amazon Linux
