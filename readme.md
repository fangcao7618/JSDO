# JSDO

The JSDO is a client side typescript library for Progress Data Object Services published by Progress Software Corporation. Its purpose is to provide an easy to understand API for querying, creating, updating and deleting Progress Data Objects as well as invoke server side business logic. 
The JSDO is a free and open-source full-featured implementation that can be used in web, mobile web and hybrid mobile apps.

### Documentation

Progress® Data Objects in an OpenEdge business application can be accessed using the JSDO on the client. For more information, see the <a href="https://docs.progress.com/bundle/data-object-guide/page/Overview-of-Progress-Data-Objects-Services-and-Catalogs.html">Overview of Progress Data Objects, Services and Catalogs.</a>

### JSDO and OpenEdge compatibility

| JSDO version | OpenEdge version |
| ------------ | ---------------- |
| 6.0.1        | 11.7.x, 12.0.x   |

### Download<a name="download"></a>

You can <a href="https://github.com/progress/JSDO/zipball/master">download a copy of the full JSDO </a> to a zip file.

| Source File                                                                                                 | Purpose                                        |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [progress.js](https://github.com/progress/JSDO/blob/master/src/progress.js)                                 | JSDO core                                      |
| [progress.session.js](https://github.com/progress/JSDO/blob/master/src/progress.session.js)                 | JSDO session management                        |
| [progress.util.js](https://github.com/progress/JSDO/blob/master/src/progress.util.js)                       | Helper classes for the JSDO                    |
| [progress.data.kendo.js](https://github.com/progress/JSDO/blob/master/src/progress.data.kendo.js)           | Kendo UI DataSource for the JSDO               |
| [auth/progress.auth.js](https://github.com/progress/JSDO/blob/master/src/auth/progress.auth.js)             | JSDO authentication provider                   |
| [auth/progress.auth.basic.js](https://github.com/progress/JSDO/blob/master/src/auth/progress.auth.basic.js) | JSDO authentication provider (BASIC auth)      |
| [auth/progress.auth.form.js](https://github.com/progress/JSDO/blob/master/src/auth/progress.auth.form.js)   | JSDO authentication provider (FORM-based auth) |
| [auth/progress.auth.sso.js](https://github.com/progress/JSDO/blob/master/src/auth/progress.auth.sso.js)     | JSDO authentication provider (SSO auth)        |

| Lib File                                                                                      | Purpose                                                                        |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [progress.all.js](https://github.com/progress/JSDO/blob/master/lib/progress.all.js)           | The JSDO plus the Kendo UI DataSource for JSDO                                 |
| [progress.all.min.js](https://github.com/progress/JSDO/blob/master/lib/progress.all.min.js)   | The JSDO plus the Kendo UI DataSource for JSDO minified for deployment         |
| [progress.jsdo.js](https://github.com/progress/JSDO/blob/master/lib/progress.jsdo.js)         | The JSDO core components (JSDO, Session, Util classes)                         |
| [progress.jsdo.min.js](https://github.com/progress/JSDO/blob/master/lib/progress.jsdo.min.js) | The JSDO core components (JSDO, Session, Util classes) minified for deployment |

The JSDO can be used by hybrid mobile apps, mobile web apps and web browser apps to access OpenEdge and Rollbase servers. Other implementations include a client in a mobile Hybrid App (a variation of the browser client), a Telerik® NativeScript client, a Node.js server, and a Java server. The JSDO has successfully been used with servers other than OpenEdge such as Node.js to export data created / aggregated in Modulus™ to a Progress® Rollbase Application.

### License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
