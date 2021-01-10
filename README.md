# Cloud Run Example

A simple example of an existing package of mine that will build, package and deploy to Google Cloud Run using Google's Cloud Build.
Point of this repo is Cloud Run and Cloud Build config for CI/CD as simple PoC. 

Original readme for this package can be found in my <https://github.com/qmilangowin/GolangPackages> GolangPackages </a> repo.

Test URL can be found here: <https://bdi-test-service-duxv4xqqlq-ew.a.run.app/sta/v1/bdi_test_service/configurations>

In the this example, the traffic is split 50/50 between an older revision and new one. Refreshing the above URL should show you 2 different messages
roughly 50% of the time.