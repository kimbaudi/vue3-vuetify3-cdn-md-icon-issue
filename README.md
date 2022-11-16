# Vue 3 + Vuetify 3 (CDN) - Material Icon issue

Unable to change icons to Material Icons using CDN because 'aliases' and 'md' vars are not availble globally

see minimal repo by opening 'md-error.html' in a browser. The ui fails to render and viewing the console log displays error message: 'Uncaught ReferenceError: aliases is not defined'.

md-error.html - Demo of Vue 3 + Vuetify 3 + Material Icons not working in CDN because 'aliases' and 'md' vars are not available globally so I am unable to configure Material Icons.

md-esm-works.html - Demo of Vue 3 + Vuetify 3 + Material Icons working in CDN if I use importmap and the esm version to import 'aliases' and 'md' vars so I am able to configure Material Icons.

mdi-success.html - Demo of Vue 3 + Vuetify 3 + Material Design Icons (default icons) working in CDN
