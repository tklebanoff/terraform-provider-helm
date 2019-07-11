## 0.11.0 (Unreleased)
## 0.10.0 (June 18, 2019)

FEATURES:

* Automatically initialize the configured helm home directory (#185)

IMPROVEMENTS:

* Update helm and tiller to 2.14.0 (#277)
* Update terraform to 0.12.1 (#289 #290)

FIXES:

* Fix concurrency issues reading multiple repos (#272)
* Documentation fixes (#262 #270 #276)
* helm/resource_release: typo fixes (#282)

## 0.9.1 (April 24, 2019)

FEATURES:

IMPROVEMENTS:

* Migrate to Terraform 0.12 SDK
* Move to Go modules for dep-management

FIXES:

* Properly handle commas in attribute values
* Documentation fixes

## 0.9.0 (March 07, 2019)
FEATURES:

* `helm_repository` is now a data source. We retain backwards compatibility through `DataSourceResourceShim` (#221)
* Use configured helm home when reading default TLS settings (#210)
* Added `load_config_file` option to enable or disable the load of kubernetes config file (#231)

IMPROVEMENTS:

* CI and doc improvements

## 0.8.0 (February 11, 2019)

FEATURES:

* Added the possibility to set sensitive values (#153)

IMPROVEMENTS:

* Multiple README, logs and docs improvements
* Go 1.11 and modules (#179, #200 and #201)
* Default tiller version v2.11.0 (#194)
* Suppress diff of "keyring" and "devel" attributes (#193)
* Add entries to .gitignore to roughly match the Google provider (#206)

FIXES:

* Fix when Helm provider ignores FAILED release state (#161)
* Use `127.0.0.1` as default `localhost` (#207)

## 0.7.0 (December 17, 2018)

- Based on Helm 2.11

## 0.6.2 (October 26, 2018)

- Bug fix: A recursion between the read and create methods as described in PR #137

## 0.6.1 (October 25, 2018)

- Re-release after induction into 'terraform-providers'. This is to align to the de-facto repository version sequence.

## 0.1.0 (October 10, 2018)

- Initial Release by Hashicorp
