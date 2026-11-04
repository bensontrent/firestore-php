# Changelog

All notable changes to `Firestore PHP` will be documented in this file.

## 3.2.0 - 2026-11-04
 - Security: Bump dev dependency `phpunit/phpunit` from `9.6` to `^9.6.33` to resolve a Dependabot advisory (affects `>= 9.0.0 < 9.6.33`). PHPUnit is a dev-only dependency and is not installed in projects that require this package.
 - Feature: Add `addNestedDocuments()` method, which converts nested arrays in the payload to `FirestoreObject` maps before inserting. Thanks to PR #3 by @Adams-Ijachi
 - Docs: Fix the `setDocument` and `deleteDocument` examples to match their actual signatures, document `addNestedDocuments`, and fix the `composer.json` install snippet.

## 3.1.0 - 2023-05-22
 - Feature: Add ability to use special characters in filenames. Thanks to PR #2 by @backendrulz 

## 3.0.0 - 2023-03-23
 - Added support for Guzzle 7
 - Added support for PHP 8
 - Minimum requirement PHP 7.3
 - Corrected several linting errors

## 2.0.1 - 2019-02-25
 - Documentation error and typos fixed.
 - Saving last response when Guzzle's `BadResponseException` exception throws.
 - Had to use `git mv` to rename files changed in `2.0.0`
 - Added `has` method to validate key existence.

## 2.0.0 - 2019-02-23
 - Added Firebase Authentication
 - All files prefixed changed from `FireStore` to `Firestore` (notice the `s` in *store*)
 - Added `Bytes` support.
 - Exception handling support added.
 - Support added to list all documents, batch listing with query parameter.
 - Pagination support for bulk and document listing.
 - Improved naming convention throughout the package.
 - `FireStoreApiClient` changed to `FirestoreClient`
 - Documentation updated

## 1.0.1 - 2019-01-16
 - Add method for casting floating point values
 - Document ID flipped on `getDocument` method

## 1.0.0 - 2018-04-20
 - Initial release
