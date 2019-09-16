<div align="center">
    <h1>Apiman</h1>
    <sub>Built with ❤︎ by
      <a href="https://github.com/grlib">grlib</a> and
      <a href="https://github.com/grlib/apiman/graphs/contributors">contributors</a>
    </sub>
</div>

---

### API request builder

**Start here: _[Story behind Apiman](https://dev.to/grlib/i-created-postwoman-an-online-open-source-api-request-builder-41md)_**

<div align="center">
  <br>
  <img src="static/screenshot.gif" alt="postwoman" width="100%">
  <img src="static/screenshot2.png" alt="postwoman" width="100%">
  <br>
</div>

### Features :sparkles:

:heart: **Lightweight**: Crafted with Ant Design and Vue

 - Faster, lighter, cleaner, minimal & responsive

:zap: **Real-time**: Send requests and get/copy responses right away!

**Methods:**
 - `GET` - Retrieve information about the REST API resource
 - `HEAD` - Asks for a response identical to that of a GET request, but without the response body.
 - `POST` - Create a REST API resource
 - `PUT` - Update a REST API resource
 - `DELETE` - Delete a REST API resource or related component
 - `OPTIONS` - Describe the communication options for the target resource
 - `PATCH` - Applies partial modifications to a REST API resource

_History entries are synced with GitHub Gist and more_

**Features:**
 - Share with social(with password option)
 - Offline support
 - Sync By GitHub Gist

:rocket: **Request**: Retrieve data from a URL without having to do a full page refresh

 - Choose `method`
 - Enter `URL`
 - Enter `Path`
 - Copy public "Share URL"
 - Generate request code for JavaScript XHR, Fetch, cURL
 - Copy generated request code to clipboard

:electric_plug: **Web Socket**: Establish full-duplex communication channels over a single TCP connection

 -  Send and receive data

:closed_lock_with_key: **Authentication**: Allows to identity the end user

**Types:**
 - None
 - Basic authentication using username and password
 - Token based authentication
 - Env suppert,You can set a request's response as authentication

:loudspeaker: **Headers**: Describes the format the body of your request is being sent as

:mailbox: **Parameters**: Use request parameters to set varying parts in simulated requests

:page_with_curl: **Request Body**: Used to send and receive data via the REST API

**Options:**
 - Set content Type
 - Toggle between RAW input and parameter list

:wave: **Responses**: Contains the status line, headers and the message/response body

 - Copy response to clipboard
 - View preview for HTML responses

_HTML responses have "Preview HTML" feature_

:alarm_clock: **History**: Request entries are synced with local session storage to reuse with a single click

**Fields**
 - Timestamp
 - Method
 - Status code
 - URL
 - Path

_History entries can be deleted one-by-one or all together_

---

## Home

[https://apiman.io](https://apiman.io)

## Usage

1. Specify your request method
2. Type in your API URL
3. Add API path
4. Send request
5. Get response!

You're done!

---

## Built with

* **[Chromium](https://github.com/chromium/chromium)** - Thanks for being so fast!
* HTML - For the web framework
* CSS - For styling components
* JavaScript - For magic!
* [Electron](http://electronjs.org) - Build cross platform desktop apps with JavaScript, HTML, and CSS
* [Vue](https://vuejs.org/) - To add to the JavaScript magic!

---

## Developing

1. [Clone this repo](https://help.github.com/en/articles/cloning-a-repository) with git.
1. Install dependencies by running `yarn` within the directory that you cloned (probably `apiman`).
1. Start the development server with `yarn dev`.

---

## Releasing
1. [Clone this repo](https://help.github.com/en/articles/cloning-a-repository) with git.
1. Install dependencies by running `npm install` within the directory that you cloned (probably `apiman`).
1. Build the release files with `npm run build`.
1. Find the built project in `./dist`.

---

## Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our [CODE OF CONDUCT](CODE_OF_CONDUCT.md), and the process for submitting pull requests to us.

---

## Continuous Integration

We use [Travis CI](https://travis-ci.com) for continuous integration. Check out our [Travis CI Status](https://travis-ci.com/grlib/apiman).

---

## Versioning

This project is developed by [GRLib](https://github.com/grlib) using the [Semantic Versioning specification](https://semver.org). For the versions available, see the [releases on this repository](https://github.com/grlib/apiman/releases).

---

## Change log

See the [CHANGELOG](CHANGELOG.md) file for details.

---

## Authors

### Lead Developers
* [**GRLib**](https://github.com/grlib) - *Author*

### Testing and Debugging
* [GRLib](https://github.com/grlib)
* ([contributors](https://github.com/grlib/apiman/graphs/contributors))
