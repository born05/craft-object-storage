Changelog
=========

## 1.1.0 - 2019-12-11

* Requires at least Craft 3.1
* Added [Craft::parseEnv()](https://docs.craftcms.com/api/v3/craft.html#public-methods) support for `keyId` and `secret` to prevent storing credentials in the DB and project config
* Fixed: Added missing `fieldLayoutId` when syncing config

## 1.0.3.1 - 2019-03-14

Prevent multipart uploads for files smaller than 100MB (`mup_threshold` was 16MB) by using a custom S3Client class 

## 1.0.3 - 2019-03-14

Prevent multipart uploads for files smaller than 100MB (`mup_threshold` was 16MB)

## 1.0.2 - 2018-05-15

No need to set the `OBJECT_STORAGE_URL` ENV var


## 1.0.1 - 2018-04-27

Explicitly require PHP 7.1


## 1.0.0 - 2018-02-27

Initial release
