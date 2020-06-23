# Django OpenID Connect Provider

[![Python Versions](https://img.shields.io/pypi/pyversions/django-oidc-provider.svg)](https://pypi.python.org/pypi/django-oidc-provider)
[![PyPI Versions](https://img.shields.io/pypi/v/django-oidc-provider.svg)](https://pypi.python.org/pypi/django-oidc-provider)
[![Documentation Status](https://readthedocs.org/projects/django-oidc-provider/badge/?version=master)](http://django-oidc-provider.readthedocs.io/)
[![Travis](https://travis-ci.org/juanifioren/django-oidc-provider.svg?branch=master)](https://travis-ci.org/juanifioren/django-oidc-provider)

## About OpenID

OpenID Connect is a simple identity layer on top of the OAuth 2.0 protocol, which allows computing clients to verify the identity of an end-user based on the authentication performed by an authorization server, as well as to obtain basic profile information about the end-user in an interoperable and REST-like manner. Like [Google](https://developers.google.com/identity/protocols/OpenIDConnect) for example.

## About the package

`django-oidc-provider` can help you providing out of the box all the endpoints, data and logic needed to add OpenID Connect (and OAuth2) capabilities to your Django projects.

Support for Python 3 and 2. Also latest versions of django.

[Read documentation for more info.](http://django-oidc-provider.readthedocs.org/)

[Do you want to contribute? Please read this.](http://django-oidc-provider.readthedocs.io/en/latest/sections/contribute.html)

## About the Nimbis Fork

This fork removes MD5 code and replaces it with sha256.  It is a work in pogress.  
Right now the version is called "0.7.0+nimbis.1"
