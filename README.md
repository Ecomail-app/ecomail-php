# PHP wrapper for Ecomail.app API

[![Build Status](https://travis-ci.org/Ecomailcz/ecomail-php.svg?branch=master)](https://travis-ci.org/Ecomailcz/ecomail-php)
[![Downloads this Month](https://img.shields.io/packagist/dm/ecomailcz/ecomail.svg)](https://packagist.org/packages/ecomailcz/ecomail)

# Installation

```
composer require ecomailcz/ecomail
```

# Usage

```
$ecomail = new Ecomail('API_KEY');
$ecomail->getListsCollection();
```

You can find your API key in your account settings in integrations tab.

# Available methods

All methods returns: `array stdClass string`

For more informations please visit API docs: https://ecomailappapiv2.docs.apiary.io/

### getListsCollection

### addListCollection

### showList

### updateList

### getSubscribers

### getSubscriber

### addSubscriber

### removeSubscriber

### updateSubscriber

### addSubscriberBulk

### listCampaigns

### addCampaign

### updateCampaign

### sendCampaign

### listAutomations

### createTemplate

### listDomains

### createDomain

### deleteDomain

### sendTransactionalEmail

### sendTransactionalTemplate

### createNewTransaction

### triggerAutomation
