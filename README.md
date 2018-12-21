# Unofficial [MyGate](https://mygate.co.za/ "My Gate Payments") Solution for [Oracle Commerce Cloud](https://cloud.oracle.com/en_US/commerce-cloud "Oracle Commerce Cloud")

## *Please contact me if you would like a demonstration or are a client using the solution. 

##### OCC version 16+

[MyGate's](https://mygate.co.za/ "My Gate Payments") online card payments.
https://mygate.co.za/

*Only Visa and Mastercard payments supported.  Use this as base to build in more
features.

```

// todo: add more card support
// todo: move any "blocking" operations
// todo: add in: Refund Endpoints
```

This is a working Payment Solution for Oracle Commerce Cloud.
Includes
- [Server-Side Extension](https://github.com/leedium/occ-mygate/tree/master/sse "Server-side extension")
- [Payment Gateway](https://github.com/leedium/occ-mygate/tree/master/gateway "Payment Gateway")
- [Payment Authorization Widget](https://github.com/leedium/occ-mygate/tree/master/authorization "Authorization")
- [Payment UI Globals](https://github.com/leedium/occ-mygate/tree/master/ui "UI Globals")

Only Credit Card and 3dSecure payments currently supported.

#### UI
- [knockout.js](https://knockoutjs.com/index.html "knockout.js")
- [javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript, "javascript"),
- [jquery](https://jquery.com/, "jquery")

#### Server
- [Node](https://nodejs.org/ "Node JS")
- [Express](https://expressjs.com/ "Express js").
- [eslint](https://eslint.org/ "Eslint")

#### Testing
- [Mocha](https://mochajs.org/ "Mocha")
- [Expect js](https://github.com/Automattic/expect.js/ "Expect")

### Installation
1. Package and install the gateway - /gateway
2. Package and install the ui widget - /ui
3. Package and install the authorization widget /authorization
4. See README.md for installation, test, deploy and instructions for the SSE - /sse
<br/><br/><br/>

### Performance
Artillery Test results for Card( Visa/MC) Normal & 3DSecure.  5 submissions, every second for 5 minutes.
```
All virtual users finished
Summary report @ 21:37:22(+0100) 2018-12-10
  Scenarios launched:  1500
  Scenarios completed: 1500
  Requests completed:  1500
  RPS sent: 4.67
  Request latency:
    min: 2490.1
    max: 25325.5
    median: 5204.6
    p95: 15653.4
    p99: 19713.7
  Scenario counts:
    0: 1500 (100%)
  Codes:
    200: 1500

```


### Disclaimer of Warranty.

  THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
