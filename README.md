# DOTNET AREA 2017

# GENERAL & HOW TO USE

# DOCUMENTATION

Benjamin Girard
Quentin Fournier-Montgieux
Sébastien Le Guischer
Sébastien Vidal
Mattéo Margueritte
Dorian Voravong


## 1. Introduction

This document’s purpose is to present the AREA project in general, how it functions,
and how someone can use it.

It will first describe the basic principles of the project, followed by the different
functionalities implemented, with a step-by-step presentation of how they can be
used.

## 2. General principle

The AREA is web application that enables common actions on the web, by
interconnecting web services (Facebook, Github, Twitter, Battlenet etc). The user can
connect/sign-up to the website and then authorize app access to these services
(modules). A user can create connections between these different services in the
following way: when an action occurs on module A, a reaction occurs on module B.
Combining 2 modules in this action/reaction way is called creating an Area.

## 3. User management

Non-authenticated users can create on account on the login page. Once their account
created they can connect to the web application.
There exists an administrator page, only accessible by user accounts with the
appropriate privileges. On it, it is possible to manager user accounts: modifiy, add, or
delete accounts.

## 4. Module Authentication

Users can handle connection to available services (Facebook, Twitter etc) on a user
page. Once he connects and authorized the Area app to access his account, the access
token(s) will be saved into a database to enable automatic connection in the future, if
an Area were to be created.


## 5. Area creation

On the manage Area page, the user can see all enabled, available and unavailable
areas of the application. Enabled areas can be disabled, available modules can be
created, and unavailable modules require the user to authorize certain accesses in the
access page (for example, the Facebook-Twitter module would be unavailable if the
user had yet authorized the app access to information of his Facebook account).
