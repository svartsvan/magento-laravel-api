# Changelog

All notable changes to `grayloon/magento-laravel-api` will be documented in this file

## 0.9.1 - April 6, 2021
- Add Store Website Repository Interface endpoint
- Add Product Attributes Endpoint

## 0.9.0 - February 2, 2021
- Add ability to log and debug unsuccessful API requests
- Add endpoint to show specific order by order ID


## 0.8.0 - December 9, 2020
- Support for PHP 8
- Add endpoint to reset customer passwords
- Add endpoint to apply customer coupons
- Add endpoint to edit specific guest cart item
- Add endpoint to edit specific customer cart item

## 0.7.0 - November 14, 2020
- Added Bundle Product Options Endpoint
- Added Sources Endpoint
- Added Sources by name Endpoint
- Added Orders Endpoint
- Added Stocks Endpoint


## 0.6.0 - October 27, 2020
- Ability to create cart as customer
- Ability to remove items from cart as guest
- Ability to remove items from cart as customer
- Fix: support custom singular API endpoints

## 0.5.0 - October 6, 2020
- Fix for Laravel 8 Applications
- Ability to query custom extension API endpoints
- Added Delete and Put Methods
- Added Product Categories API Endpoint
- Added Payment as Guest Endpoint
- Added Payment as Customer Endpoint
- Added Cart Payment Methods Endpoint
- Added Shipping Information Endpoint
- Added Add Items as Customer to Cart Endpoint
- Now throws Exception when >500 error is thrown


## 0.4.1 - September 8, 2020
- Support for Laravel 8 applications

## 0.4.0 - September 2, 2020
- Removed Storage System (moved to its own package for less breaking changes)
- Added Guest Carts Endpoint
- Added Source Items Endpoint
- Added Product Links Endpoint
- Added Product Link Type Endpoint

## 0.3.0 - August 11, 2020
- Ability to resolve Custom Attribute values
- Added helpers to easily retrieve product custom attribute values
- Added slug column to Magento Products table

## 0.2.0 - August 7, 2020
- Ability to publish factories for application mocking
- Added slug attribute to Category Factory
- Downloads product images on product sync/import

## 0.1.0 - July 30, 2020
- Initial Release
